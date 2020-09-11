{{$col := 16777215}}
{{$p := 0}}
{{$r := .Member.Roles}}
{{range .Guild.Roles}}
	{{if and (in $r .ID) (.Color) (lt $p .Position)}}
	{{$p = .Position}}
	{{$col = .Color}}
	{{end}}
{{end}}

{{if reFindAllSubmatches `https://(?:\w+\.)?discord(?:app)?\.com/channels\/(\d+)\/(\d+)\/(\d+)` .Message.Content}}
    {{$m := reFindAllSubmatches `https://(?:\w+\.)?discord(?:app)?\.com/channels\/(\d+)\/(\d+)\/(\d+)` .Message.Content}}
    {{if not (eq (toInt64 (index (index $m 0) 1)) .Guild.ID)}}
        {{sendMessage nil (cembed
            "author" (sdict
                "name" "Utilisateur inconnu"
                "icon_url" "https://cdn.discordapp.com/emojis/565142262401728512.png")
            "description" (print "\n\n**[➥ Lien vers l'original](" (index (index $m 0) 0) "/) to <#" (index (index $m 0) 2) ">**\n" "❗ Ce message est issue d'un autre serveur, son contenu ne peut pas être affiché ❗")
            "color" 0x36393F
            "footer" (sdict
                "text" (print "Cité par : " .Message.Author.String))
            "timestamp" ((newDate 1970 1 1 0 0 0).Add (toDuration (mult (fdiv (toInt64 (round (add (fdiv (toInt64 (index (index $m 0) 3)) 4194304) 1420070400000))) 1000) .TimeSecond))))}}
    {{else}}
        {{$msg := getMessage (index (index $m 0) 2) (index (index $m 0) 3)}}
        {{$mc := reReplace `(?:https?://)?(?:www\.)?(discord(?:app)?\.gg(?:/|\\+/+)|discord(?:app)?\.com(?:/|\\+/+)(?:invite/))[A-z+0-9]{2,}|(?:https?://)?(?:www\.)?discord(?:app)?\.(?:io|me|li)(?:/|\\+/+)[A-z+0-9]{2,}` $msg.Content "[Invitation retirée](https://discord.gg/GRns3fg)"}}
        {{$e := sdict
            "author" (sdict
                "name" (print $msg.Author.String)
                "icon_url" ($msg.Author.AvatarURL "1024"))
            "color" $col
            "footer" (sdict
                "text" (print "Cité par : " .Message.Author.String ))
            "timestamp" $msg.Timestamp}}
        {{$fo := $e.Get "footer"}}
        {{$ti := $msg.Timestamp}}
        {{if $msg.Attachments}}
            {{range $c,$ma := $msg.Attachments}}
                {{$e.Del "footer"}}
                {{$e.Del "timestamp"}}
                {{if eq $c 0}}
                    {{$e.Set "description" (print $mc "\n\n [➥ Original](" (index (index $m 0) 0) "/)")}}
                {{end}}
                {{if eq (len $msg.Attachments) (add $c 1)}}
                    {{$e.Set "footer" $fo}}
                    {{$e.Set "timestamp" $ti}}
                {{end}}
                {{if (reFind "(?i)(.jpg|.jpeg|.png|.gif|.tif|.tiff)$" .Filename)}}
                    {{$e.Set "image" (sdict "url" .URL)}}
                    {{sendMessage nil (cembed $e)}}
                {{else}}
                    {{$e.Set "fields" (cslice
                        (sdict "name" "Nom du fichier" "value" (print "`" .Filename "`") "inline" true)
                        (sdict "name" "URL" "value" (print "[Lien](" .URL ")") "inline" true))}}
                    {{sendMessage nil (cembed $e)}}
                {{end}}
                {{$e.Del "fields"}}
                {{$e.Del "image"}}
                {{$e.Del "description"}}
                {{$e.Del "author"}}
            {{end}}
        {{else}}
            {{if $msg.Content}}
							{{$e.Set "description" (print $mc "\n\n [➥ Original](" (index (index $m 0) 0) "/)")}}
              {{sendMessage nil (cembed $e)}}
            {{end}}
        {{end}}
        {{if $msg.Embeds}}
            {{sendMessage nil (index $msg.Embeds 0)}}
        {{end}}
    {{end}}
    {{if eq (len (index (index $m 0) 0)) (len .Message.Content)}}
        {{deleteTrigger 0}}
    {{end}}
{{end}}
