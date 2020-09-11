{{$ri :="**Rixolam** : Restaure 10 PV" }}
{{$ban := "**Bandage** : Réduit de 1 tour un malus "}}
{{$eu := "**Eufyrusant** : Augmente les capacités PSI pour 1 tour."}}
{{$im := "**Implant temporaire** : Implant sur une caractéristique pendant 3 tours (ou cycle, si hors combat)."}}
{{$so := "**Soma** : Réduit de 1 tours les cooldown d'un module ou d'un PSI."}}
{{$eu := "**Eufyrusant** : Augmente une compétence de 8% pour 1 tour."}}
{{$ro := "**Sirop de betapropyl** : Divise par deux les effets des malus."}}
{{$gr := "**Grenade Nécrotique** : 5% bonus projectile"}}
{{$fn := "**Liquide antifongique : Annule bouclier mush durant 1Tour**"}}
{{$th := "**Gaz anesthésiant** : Endort la cible si jet de karma raté"}}
{{$sng := "**Sang Ethérique** : 7% bonus sur une attaque"}}
{{$cr := "**Huile carotonixique** : Malus sur toutes les caractéristiques pendant 1 tour"}}
{{$di := "**Huile digestive** : Divise par 2 les effets d'une armure sur 3 tours"}}



{{$d:=""}}
{{$v:="722755391498485800"}}
{{$m:=""}}
{{$k:=""}}
{{$id:=""}}
{{$f:=print "Recherche faite par " (getMember .User.ID).Nick }}
{{$b:=true}}
{{$a:="https://cdn.discordapp.com/attachments/726496591489400872/727978845185245283/download20200605012708.png"}}
{{$l:="https://i.imgur.com/o557fMx.png"}}

{{if .CmdArgs}}
	{{$i:=lower (index .CmdArgs 0)}}
	{{$flag:=reFind `(?i)(analgésiques?|(Armes? biologiques?)|(armes? bio)|Armes?)` (index .CmdArgs 0)}}
	{{$flag =lower $flag}}
	{{if eq $i "rixolam"}}
		{{$d =$ri}}
	{{else if eq $i "bandage" "bandages"}}
		{{$d =$ban}}
	{{else if eq $i "eufyrusant" "eufy"}}
		{{ $d =$eu}}
	{{else if eq $i "soma"}}
		{{$d =$so}}
	{{else if eq $i "implant temporaire" "implant" "temporaire" "implants temporaires" "implants" "temporaires" "implants temporaire" "implants temporaire"}}
		{{$d = $im}}
	{{else if eq $i "sirop" "betapropyl" "sirop de betapropyl"}}
		{{$d =$ro}}
	{{else if eq $i "grenade" "grenade nécrotique" "grenade necrotique" "nécrotique" "necrotique" "necro" "nécro"}}
		{{$d =$gr}}
	{{else if eq $i "liquide antifongique" "liquide" "antifongique"}}
		{{$d =$fn}}
	{{else if eq $i "anesthésiant" "gaz anesthésiant" "gaz"}}
		{{$d =$th}}
	{{else if eq $i "sang etherique" "sang ethérique" "sang" "éthérique" "etherique" "étherique" "ethérique" "sang étherique"}}
		{{$d =$sng}}
	{{else if eq $i "carotoxinique" "caro" "huile carotoxinique"}}
		{{$d =$cr}}
	{{else if eq $i "huile digestive" "digestive"}}
		{{$d =$di}}
	{{else if eq $i "huile"}}
		{{$d =joinStr "" $di "\n" $cr}}
	{{else if eq $flag "analgésique" "analgésiques"}}
		{{$id ="736005431582916638"}}
	{{else if eq $flag "arme biologique" "armes biologiques" "arme biologiques" "armes biologique" "arme bio" "armes bio"}}
		{{$id ="736005737452404778"}}
	{{else if eq $flag "arme" "armes"}}
		{{$id ="736006328668913684"}}
	{{end}}

	{{if $flag}}
		{{$msg:=getMessage $v $id}}
		{{$m =(index $msg.Embeds 0).Description}}
		{{$k:=(print "(https://discordapp.com/channels/" .Guild.ID "/" $v "/" $id ")")}}
		{{$d =(joinStr "" $m )}}
	{{end}}

{{else}}
	{{$b = false}}
{{end}}
{{if eq $b true}}
	{{$embed:=cembed
		"author" (sdict "name" "[Sola-UI] BDD : Objet bas de gamme" "icon_url" $a)
		"thumbnail" (sdict "url" $l)
		"description" $d
		"footer" (sdict "text" $f )
		"color" 0x94CAF0}}
	{{sendMessage nil $embed}}
{{else if eq $b false}}
	{{$d = "Vous cherchez un objet à bas coût ? Mais lequel ?"}}
	{{$embed:=cembed
		"author" (sdict "name" "[Sola-UI] BDD : Objet - ERREUR" "icon_url" $a)
		"thumbnail" (sdict "url" $l)
		"description" (joinStr " " $d "\n\n Voici les commandes : \n▫️ **Analgésique** : `?search faible analgésique`\n▫️ **Armes biologiques** : `?search faible \"Arme biologique\"`\n▫️ **Armes** : `?search faible arme`\n")
		"fields" (cslice
			(sdict "name" "_ _" "value" "_ _" "inline" false)
			(sdict "name" "Analgésique" "value" ":white_small_square:**Rixolam :** `?search faible rixolam`\n:white_small_square:**Bandage :** `?search faible bandage(s)`\n:white_small_square:**Eufyrusant :**`?search faible eufy(rusant)`\n:white_small_square:**Soma :** `?search faible soma`\n:white_small_square: **Sirop de betapropyl :** `?search faible (sirop|betapropyl|\"sirop de betapropyl\")`\n:white_small_square: **Implant temporaire :** `?search faible (\"implant(s) temporaire(s)|implant(s)|temporaire(s))`" "inline" false)
			(sdict "name" "_ _" "value" "_ _" "inline" false)
			(sdict "name" "Armes biologiques" "value" ":white_small_square: **Grenade Nécrotique :** `?search faible (grenade|grenade nécrotique|nécro)`\n:white_small_square: **Liquide antifongique :**`?search faible (antifongique|liquide|\"liquide antifongique\")`\n:white_small_square: **Gaz anesthésiant de combat :** `?search faible (anesthésiant|gaz|\"gaz anesthésiant\")`\n:white_small_square: **Sang Etherique :** `?search faible (\"sang éthérique\"|sang|éthérique)`\n:white_small_square: **Huile carotoxinique :** `?search faible (huile|carotonixique|caro|\"huile carotoxinique\")`\n:white_small_square: **Huile digestive :**  `?search faible (huile|digestive|huile digestive`" "inline" false))
		"footer" (sdict "text" $f )
		"color" 0xA75454}}
		{{sendMessage nil $embed}}
{{end}}
