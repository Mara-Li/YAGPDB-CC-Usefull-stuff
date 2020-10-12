{{$rc:=reFindAllSubmatches `^\$rc` .Message.Content}}
{{$rcc:=reFindAllSubmatches `^\$rcc` .Message.Content}}
{{$img := "https://www.pixenli.com/image/1qak3D2B"}}


{{if .CmdArgs}}
	{{$y := (toFloat (index .CmdArgs 0))}}
	{{if eq $y (toFloat 0)}}
			Merci de rentrer un nombre.
	{{else}}
		{{if $rc}}
			{{$x:= (toInt (mult 1.4 $y))}}
			{{$embed := cembed
				"author" (sdict "name" "Réussite critique" "icon_url" $img)
				"description" (joinStr " " "Vous avez maintenant un bonus de" $x "% sur cette compétence non-offensive")
				"color" 0xACDFD1}}
				{{sendMessage nil $embed}}
		{{else if $rcc}}
			{{$x:= (toInt (mult 1.8 $y))}}
			{{$embed := cembed
				"author" (sdict "name" "Réussite critique" "icon_url" $img)
				"description" (joinStr " " "Vous avez maintenant un bonus de" $x "% sur cette compétence non-offensive")
				"color" 0xACDFD1}}
			{{sendMessage nil $embed}}
		{{end}}
	{{end}}
{{else}}
	**Usage** : `$(rcc|rc) valeur`
{{end}}
{{deleteTrigger 1}}
{{deleteResponse 30}}
