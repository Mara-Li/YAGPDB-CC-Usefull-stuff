{{$flag := reFind `^\?(malus|soin|poison|support|soutien)` .Message.Content}}

{{$id := ""}}
{{$s := "+"}}
{{$ec := "Malus de -"}}
{{if eq $flag "?soutien"}}
	{{$s = "-"}}
	{{$ec := "Malus de +"}}
{{else if eq $flag "?malus"}}
	{{$s = "+"}}
	{{$ec := "Bonus de -"}}
{{end}}
{{if .CmdArgs}}
	{{if eq $flag "?soin"}}
		{{$embed := cembed
			"title" "Soin"
			"Description" "**0** : URC / Bonus + 40 pv → IMPLANT UNIQUEMENT \n**1** : 40\n**2** : 35\n**3** : 30\n**4** : 25\n**5** : 20\n**6** : 15\n**7** : 10\n**8** : 5\n**9** : Echec\n**10** : Echec + Malus\n\nEn cas d'utilisation avec un pouvoir ou un module :\n:white_small_square: Les PV rendus sont augmentés de 1.\n:white_small_square: Il n'y a pas de malus en cas d'EC."
		"color" 0xb66dc1
		"thumbnail" (sdict "url" "https://www.sphanalytics.com/wp-content/uploads/2018/01/Health-Icon334.png")}}
      {{$id = sendMessageRetID nil $embed}}

	{{else if eq $flag "?malus" "?soutien"}}
		{{$embed := cembed
			"title" "Malus de caractéristiques"
			"Description" "**0** : {{$s}}4 → IMPLANT UNIQUEMENT\n**1** : {{$s}}3\n**2** : {{$s}}3\n**3** : {{$s}}2\n**4**: {{$s}}2\n**5**: {{$s}}2\n**6**: {{$s}}1 \n**7**: {{$s}}1 \n**8**: {{$s}}1\n**9** : Echec\n**10** : EC → {{ec}}2 à l'adversaire"
			"color" 0x2B7697
			"thumbnail" (sdict "url" "https://i.imgur.com/fuHvIUn.png")}}
      {{$id = sendMessageRetID nil $embed}}

	{{else if eq $flag "?poison"}}
		{{$embed := cembed
			"title" "Empoisonnement"
			"Description" "Attention, les poisons ne sont pas en pourcentages, et les dégâts sont multipliés, au final, par 3 car une altération dure trois tours. \n\n  **0** : -10 (-30 PV) → IMPLANT UNIQUEMENT \n**1** : -9 (-27PV)\n**2** : -8 (-24 PV)\n**3** : -7 (-21PV)\n**4**: -6 (-18PV)\n**5** : -5 (-15PV)\n**6** : -4 (-12PV) \n**7** : -3 (-9PV)\n**8** : -2 (-6PV)\n**9** : Echec\n**10** : +15 PV (+45PV)"
			"color" 0x370E6A
			"thumbnail" (sdict "url" "https://i.imgur.com/CmgNFYu.png")}}
      {{$id = sendMessageRetID nil $embed}}
	{{end}}

{{else if eq $flag "?support"}}
{{$embed := cembed
			"title" "Informations sur les résultats de dés"
			"fields" (cslice
(sdict "name" "Soin" "value" "**0** : URC / Bonus + 40 pv → IMPLANT UNIQUEMENT \n**1** : 40\n**2** : 35\n**3** : 30\n**4** : 25\n**5** : 20\n**6** : 15\n**7** : 10\n**8** : 5\n**9** : Echec\n**10** : Echec + Malus\n\nEn cas d'utilisation avec un pouvoir ou un module :\n:white_small_square: Les PV rendus sont augmentés de 1.\n:white_small_square: Il n'y a pas de malus en cas d'EC." "inline" false)
		(sdict "name" "_ _" "value" "_ _" "inline" false)
			(sdict "name" "Poison" "value" "Attention, les poisons ne sont pas en pourcentages, et les dégâts sont multipliés, au final, par 3 car une altération dure trois tours. \n\n  **0** : -10 (30) → IMPLANT UNIQUEMENT \n**1** : -8 (24)\n**2** : -7 (21)\n**3** : -6 (18)\n**4**: -5 (15)\n**5** : -4 (12)\n**6** : -3 (9) \n**7** : -2 (6)\n**8** : -1 (3)\n**9** : Echec\n**10** : +3 PV (+9)" "inline" false)
		(sdict "name" "_ _" "value" "_ _" "inline" false)
(sdict "name" "Malus ou support de caractéristiques" "value" "**0** : (+/-)4 → IMPLANT UNIQUEMENT\n**1** :  (+/-)3\n**2** :  (+/-)3\n**3** :  (+/-)2\n**4**:  (+/-)2\n**5**:  (+/-)2\n**6**:  (+/-)1 \n**7**:  (+/-)1 \n**8**:  (+/-)1\n**9** : Echec\n**10** : EC → Bonus ou malus de -/+ 2 à l'adversaire" "inline" false))
			"color" 0x2B7697}}
      {{$id = sendMessageRetID nil $embed}}
{{end}}
{{deleteTrigger 1}}
