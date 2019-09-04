# Þrjú spjallborð

Þessi mappa inniheldur 30.000 þræði af þremur íslenskum spjallborðum.  Aldur textanna er á árabilinu 2000-2019 en þar sem um slembiúrtak úr stærra safn er að ræða er óvíst að textar frá öllum árum séu til staðar.


## Skipulag

Hvert spjallborð er í sérstakri möppu. Hver mappa inniheldur svo 10.000 JSON skjöl, eitt fyrir hvern þráð.
Skráarheiti eru einstök innan mappa, en ekki á milli þeirra. Skema JSON skránna er svipað, en ekki eins á milli mappa. Nánar er gert grein fyrir því hér að neðan.

## Barnaland

Barnaland, eða bland.is, er í möppunni `bland`.

### Dæmi

    {
      "url": "https://bland.is/umraeda/barnaleikir-a-netinu-/636417/?page=1720",
      "date": "2004-07-14 10:40:52",
      "id": "636417",
      "items": [
        {
          "text": "Getið þið bent mér á einhverjar síður með góðum barnaleikjum fyrir 6 ára snót á netinu. Helst íslenskum?",
          "title": "Barnaleikir á netinu.",
          "username": "Saffran1",
          "message_id": "636417",
          "user_id": "306",
          "response_to": null,
          "datetime": "2004-07-14 10:40:52",
          "datestring": "14. júl. '04, kl: 10:40:52"
        },
        {
          "response_to": "636417",
          "username": "Kelly Belly",
          "message_id": "636428",
          "user_id": "14572",
          "datetime": "2004-07-14 10:43:53",
          "datestring": "14. júl. '04, kl: 10:43:53",
          "text": "Það eru einhverjir leikir a"
        },
        {
          "response_to": "636428",
          "username": "lúllilaukur",
          "message_id": "636577",
          "user_id": "12779",
          "datetime": "2004-07-14 11:35:52",
          "datestring": "14. júl. '04, kl: 11:35:52",
          "text": "Það eru einhverjir leikir á síðunni"
        }
      ]
    }

### Athugasemdir

Hver þráður hefst á upphafsinnleggi sem hefur `id`. Þar er slóð á þráðinn og dagsetning tilgreind. Innlegg eru í fylkinu `items`. Það á einnig við um upphafsinnleggið og er þá `message_id`það sama og `id`. Texti innleggs er í `text`. `response_to`eigindið vísar til þess innleggs sem svarað er, og með því er því hægt að endurskapa þráðinn í réttri röð.

## Hugi

Hugi, eða hugi.is, er í möppunni `hugi`.

### Dæmi

    {
      "forum_title": "Mótorhjól",
      "user": "Doror",
      "user_id": "3493",
      "date": "2001-06-29 13:05:40",
      "title": "Viðhaldið góða..",
      "text": "Ég eignaðist nýlega mótorhjól, yamaha fzr 600 og er svona rétt að byrja þetta eðlilega viðhald.  Þar sem hjólið er ekki með tvöföldum standara þá á ég svolítið erfitt með að vinna í því, hvað gerið þið sem kannist við þetta??  Það er full mikið mál að rífa alltaf plastið af því til að tjakka upp eða eitthvað svoleiðis rugl.  Ég þarf til dæmis að fara að skipta um legur að framan og ég get náttúrulega ekki lagt hjólið á hliðina þannig að ég veit bara ekki alveg hvernig ég á að snúa mér í þessu.  Ef einhverjir veteran hjólarar hafa einhverjar lausnir endilega póstiði og bara generalt um viðhald….. Er t.d. í lagi að smyrja keðjuna með wd 40???",
      "url": "https://www.hugi.is/motorhjol/greinar/32874/vidhaldid-goda/",
      "url_id": "32874",
      "id": "221524",
      "replies": [
        {
          "user": "Gulag",
          "user_id": "48",
          "date": "2001-06-29 14:51:09",
          "id": "221525",
          "reply_to_id": "221524",
          "text": "til hamingju með hjólið..!!! þetta er þrælskemmtileg hjól…\nanyways,, einfaldast er sennilega fyrir þig að hengja hjóolið upp,, þér er alveg óhætt að binda í stýrið og hengja það upp þannig,, ef þú getur ekki hengt hjólið upp þá skaltu láta smíða fyrir þig stand,, ætti ekki að kosta meira en 2-3000 kall, ef þú kíkir undir þar sem stýrisbrúin er fest í grindina þá sérða að þar á að vera tiltölulega stórt gat, fáðu þér stöng sem passar í gatið og láttu sjóða lappir á hana, þannig að þetta lítur út svipað og búkki,,,þú þarft reyndar að lyfta hjólinu á þennan búkka og þa þarftu smá aðstoð, en þetta er mjög einföld lausn,,,\ngetur líka séð aðra lausnir á\nhttp://www.worksstand.com/standinfo.html\nþar eru svona smá fancy standar..\nReyndar er þér alveg óhætt að leggja hjólið á hliðina,, ef þú setur eitthvað undir það þannig að það skemmist ekki hlífarnar,, það á ekkert að leka úr hjólinu þó það liggi á hliðinni, ef þú átt t.d. gamla dýnu?  passa bara spegilinn…leggja hann að ef þú getur eða takann af…\nEkki nota WD40 á keðjuna, WD40 er alltof þunn olía til að nota á drifkeðjur,, fjárfestu í góðri keðjuolíu, hjá t.d. bílanust, Wurth eða í ísboltum..keðjuolíur eru þykkari en WD40.."
        },
        {
          "user": "Doror",
          "user_id": "3493",
          "date": "2001-06-29 17:31:45",
          "id": "221526",
          "reply_to_id": "221525",
          "text": "Takk kærlega, þetta með dýnuna er algjör snilld, á einmitt gamla gormadýnu sem er ekkert að gera.  Þá get ég auðveldlega rifið framhjólið undan."
        }
      ]
    }

### Athugasemdir

Hver þráður hefst á upphafsinnleggi sem hefur `id`. Þar er slóð á þráðinn, hvaða umræðuborði hann tilheyrir og dagsetning tilgreind. Einnig er texti innleggsins (`text`) og titill (`title`) þess tilgreint. Innlegg eru í fylkinu `replies`. Texti innleggs/svars er í `text`. `reply_to`eigindið vísar til þess innleggs sem svarað er, og með því er því hægt að endurskapa þráðinn í réttri röð.

## Live2cruize

Live2cruize, eða Live2cruize.com, er í möppunni `live2ruize`.

### Dæmi

    {
      "forum_title": "Almennt spjall",
      "id": "129",
      "title": "Ljósastilling ?",
      "url": "http://www.live2cruize.com/spjall/showthread.php/129-Ljósastilling",
      "posts": [
        {
          "user_name": "Jón Ragnar",
          "text": "Daginn.\n\r\nVitið þið hvar er hægt að fara með bíl í ljósastillingu? er með mözdu 323f ´92 með svona flip ljósum \n\r\nKv Jón R",
          "date": "2003-02-19 12:33:00",
          "post_id": 1
        },
        {
          "user_name": "Páll Óskar",
          "text": "Flest öll werkstæði eru með tæki til þess\n\r\nBtw, geðveikt gamalt  <<<icon_rolleyes.gif>>>",
          "date": "2004-10-09 20:24:00",
          "post_id": 2
        },
        {
          "user_name": "Jón Ragnar",
          "text": "SHit hahahah   <<<icon_cool.gif>>>",
          "date": "2004-10-09 20:34:00",
          "post_id": 3
        },
        {
          "user_name": "muggzSTi",
          "text": "hahahaha róóólegur, Wed Feb 19, 2003  <<<icon_mrgreen.gif>>> <<<icon_lol.gif>>>",
          "date": "2004-10-09 22:10:00",
          "post_id": 4
        },
        {
          "user_name": "gr33n",
          "text": "LOL",
          "date": "2004-10-09 22:12:00",
          "post_id": 5
        },
        {
          "user_name": "Gunninn",
          "text": "díses  <<<icon_rolleyes.gif>>>",
          "date": "2004-10-09 22:49:00",
          "post_id": 6
        },
        {
          "user_name": "gunnar",
          "text": "Stirring old coco are we...  <<<icon_rolleyes.gif>>>",
          "date": "2004-10-10 03:02:00",
          "post_id": 7
        },
        {
          "user_name": "Arnþór",
          "text": "Já það er alveg ótrúlega leiðinlegt stundum að póstar færist fremst þegar þeim er svarað óháð því hversu gamlir þeir eru...",
          "date": "2004-10-10 21:40:00",
          "post_id": 8
        },
        {
          "user_name": "Dezzice",
          "text": "Jæja læsum þessu barasta <<<icon_smile.gif>>>",
          "date": "2004-10-10 21:49:00",
          "post_id": 9
        }
      ],
      "file_urls": [
        "http://live2cruize.com/spjall/images/smilies/icon_rolleyes.gif",
        "http://live2cruize.com/spjall/images/smilies/icon_cool.gif",
        "http://live2cruize.com/spjall/images/smilies/icon_mrgreen.gif",
        "http://live2cruize.com/spjall/images/smilies/icon_lol.gif",
        "http://live2cruize.com/spjall/images/smilies/icon_rolleyes.gif",
        "http://live2cruize.com/spjall/images/smilies/icon_rolleyes.gif",
        "http://live2cruize.com/spjall/images/smilies/icon_smile.gif"
      ],
      "date": "2003-02-19 12:33:00",
      "files": [
        {
          "url": "http://live2cruize.com/spjall/images/smilies/icon_rolleyes.gif",
          "path": "full/81e9b91273b9ca2ad696cfd6f3bec8f7bff28bd6.gif",
          "checksum": "19071b1af987946e96dcef6ce0611c6b"
        },
        {
          "url": "http://live2cruize.com/spjall/images/smilies/icon_cool.gif",
          "path": "full/268b6de7ac68d94c2755e424eca1572f6620d521.gif",
          "checksum": "25c83ea511f206e88f214719dad9c88c"
        },
        {
          "url": "http://live2cruize.com/spjall/images/smilies/icon_mrgreen.gif",
          "path": "full/c4c4e06a2fb0f6c1748cf2b636f549245bc91197.gif",
          "checksum": "54e8505227edae1e583cf2f9554abc3a"
        },
        {
          "url": "http://live2cruize.com/spjall/images/smilies/icon_lol.gif",
          "path": "full/fa705ed47e899453195f9b57838cc55ca8fdd97f.gif",
          "checksum": "b76e7729d43c4a49182d020741285bef"
        },
        {
          "url": "http://live2cruize.com/spjall/images/smilies/icon_rolleyes.gif",
          "path": "full/81e9b91273b9ca2ad696cfd6f3bec8f7bff28bd6.gif",
          "checksum": "19071b1af987946e96dcef6ce0611c6b"
        },
        {
          "url": "http://live2cruize.com/spjall/images/smilies/icon_rolleyes.gif",
          "path": "full/81e9b91273b9ca2ad696cfd6f3bec8f7bff28bd6.gif",
          "checksum": "19071b1af987946e96dcef6ce0611c6b"
        },
        {
          "url": "http://live2cruize.com/spjall/images/smilies/icon_smile.gif",
          "path": "full/1b4c582c326e1f58ed353744337401937e95b553.gif",
          "checksum": "9ee646ffab71107d1a11407be52f33a5"
        }
      ]
    }

## Athugasemdir

Hver þráður hefst á upphafsinnleggi sem hefur `id`. Þar er slóð á þráðinn, hvaða umræðuborði hann tilheyrir og dagsetning tilgreind. Einnig er texti innleggsins (`text`) og titill (`title`) þess tilgreint. Innlegg eru í fylkinu `posts`. Texti innleggs/svars er í `text`.  Hvert innlegg hefur `post_id`eigindi þar sem það fyrsta fær 1 og það næsta 2 og svo koll af kolli.

Í texta hvers innleggs hefur tjáknum verið skipt út fyrir streng sem hefst á `<<<`, þar næst heiti skráarinnar sem tjáknið vísar í og svo endar strengurinn á `>>>`.

Fylkið `files`inniheldur svo upplýsingar um tjáknin. Upprunalegu gif-myndirnar eru svo í möppu nefnd `emojis`.


Páll Hilmarsson
pallih@gogn.in
Mars, 2019

