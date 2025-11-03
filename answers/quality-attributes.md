# 5 ytri + 3 innri gæðaeiginleikar

> Ytri (external) — upplifun notenda/rekstur: 
> Innri (internal) — viðhald/þróun: 

Veljið eina kröfu og lýsið henni í sér skrá með PLanguage sniði 
## Ytri (5)
| Eiginleiki | Krafa (1 setning) | Rök/forsemdir (2–3 setn.) |
|---|---|---|
| 1. Performance| hafa hraða spilun á efni í Rúv kerfinu, og tryggja lítinn biðtíma áður en efnið byrjar að spilast. (Sjá PLanguage neðst) | Notendur búast við snöggu aðgengi að efni, hæg virkni á kerfinu getur leitt til pirrings og minnkun á áhorfstíma. Hröð virkni er því mikilvæg til að halda einbeitingu hjá notendum.
| 2. Usability |  Rúv kerfið skal einfalt og leiðandi svo að nýir notendur geti léttilega fundið efni og byrjað að horfa á það innan við 30 sekúndur án þess að þurfa frekari leiðbeiningar.| Rúv kerfið er fyrir alla landsmenn, sem inniheldur fólk af öllum aldri sem hefur mismunandi þekkingu á tækni, því er mikilvægt að kerfið skal hafa einfalda leiðandi hönnun sem minnkar líkur á pirring og eykur líkur á því að notendur noti kerfið aftur, sem hjálpar Rúv að ná markmiði sínu að auka áhorfs tíma hjá notendum.
| 3. Accessibility |Kerfið skal fara eftir helstu stöðlum fyrir aðgengi (WCAG 2.1), Kerfið skal innihalda textaskýringar fyrir heyrnarskerta og talsetta leiðsögn fyrir sjónskerta einstaklinga. |  Þar sem Rúv er ætlað fyrir alla landsmenn er mjög mikilvægt að kerfið sé með gott aðgengi, svo að allir geti nýtt sér það, jafnvel fólk með einhvers konar fötlun. Einföld leiðsögn hjálpar líka að eldri kynslóðin geti notað kerfið.
|4. Reliability | Kerfið skal vera notanlegt 99% af mánuðinum og skal hafa einhvers konar ferli til að laga einhverjar kerfisvillur eins fljótt og hægt er.  | Notendur eru vanir að horfa á Rúv á ákveðnum tímum, eins og kvöldfréttir í beinni útsendingu. Truflanir á þeim tímum sem notendur eru vanir að nota kerfið getur valdið vantrausti á kerfinu. Því er áreiðanleiki mikilvægur til að halda trausti notenda.
| 5. Security & Privacy |Notenda upplýsingar eins og uppáhalds efni og innskráningar upplýsingar þurfa að vera vel verndaðar og kerfið skal fylgja GDPR staðli.| Til að halda trausti notenda á kerfinu er mjög mikilvægt að vernda persónuupplýsingar. Sterkt öryggi í kerfinu er einnig mikilvægt til að koma í veg fyrir að það verði notað af ólöglegum notendum og á rangan hátt.|

## Innri (3)
| Eiginleiki | Krafa (1 setning) | Rök/forsemdir (2–3 setn.) |
|---|---|---|
| 1. Modifiability |  Kerfið ætti að vera sveigjanlegt svo að mismunandi fyrirtæki sem nota kerfið geta bætt/eytt sumum fídusum án þess að þurfa eyða miklum tíma í að endurhanna kerfið. | Þar sem viðskiptavinir okkar eru ekki bara Rúv þá þarf kerfið að geta sleppt því að hafa til dæmis beina útsendingu, og ef Rúv vill beita fréttum í kerfið þá þarf það að vera auðvelt að gera líka.
| 2. Testability | Kerfið á að hafa sjálfvirkar prófanir á stórum hlut af kerfinu.
  | Nýjar uppfærslur og laganir á kerfinu geta átt sér stað oft og til að flýta fyrir því ferli er mikilvægt að hafa sjálfvirkar prófanir til að staðfesta að virkni er rétt fljótt, sjálfvirkar prófanir hjálpa líka með stöðugleika.
| 3. Maintainability | Hönnunin á kerfinu og kóðinn á því skal vera vel skjalaður og skýr svo að nýjir forritarar geti skilið kerfið fljótt. | Viðskiptavinir eiga að geta léttilega breytt um forritara og teymi sem vinna í kerfinu án þess að það taki langan tíma fyrir þá að skilja kerfið til að vinna í því. Það hjálpar einnig með langtíma kostnað fyrir viðskiptavini. 
  |


PLanguage 

1. Performance
Merkimiði (TAG): Performance.Video.StartTime

Tilgangur/Ásetningur (AMBITION): hafa hraða spilun á efni í Rúv kerfinu, og tryggja lítinn biðtíma áður en efnið byrjar að spilast.

Mælikvarði (SCALE): Tími er mældur eftir að ýtt er á efni til að spila og þangað til að efnið byrjar að spilast.

Mæliaðferð (METER): Prófað að spila mismunandi efni á mismunandi vöfrum og tækjum með sömu nettengingu.

Markmið (GOAL): Efnið byrjar að spilast innan við 5 sekúndur fyrir 90% af tilvikum.

Æskilegt (STRETCH): Efnið byrjar að spilast innan við 3 sekúndur fyrir 90% af tilvikum

Óska (WISH): Efnið byrjar að spilast innan við 2 sekúndur fyrir öll tilvik.

Grunnkerfi (Base user platform DEFINED): Nútíma vafrar eins og Chrome, Firefox, Safari eða app á snjalltækjum, tækið þarf að hafa a.m.k. 10mbps nethraða og a.m.k. 4gb RAM vinnsluminni.

