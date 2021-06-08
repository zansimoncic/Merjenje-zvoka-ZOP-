# Merjenje-zvoka-ZOP-
Dijaka Žan Simončič in Jaka Škof sva si omenjen projekt izbrala zaradi želje po preučevanju zvoka. Cilj dotičnega projekta je merjenje jakosti zvoka, ter prikaz le tega na LCD zaslon. Zaradi netočnosti samega mikrofona (nizki cenovni razred, potreba samo za simulacijo) meritev ni tako učinkovita, vendar pa dovolj dobro prikazuje samo delovanje.\
Delovanje:\
Vezje je sestavljeno iz nekaj osnovnih komponent kot so: arduino uno, mikrofon, potenciometer… Vse elemente prek protoboarda in žičk povežemo med seboj. Za izpis končnih podatkov pa uporabimo LCD zaslon. Samo vezje deluje tako, da mikrofon zaznava različne jakosti zvoka iz okolice. Ta  sam signal pošlje v Arduino, kjer ga ta pretvori ter vrednost v decibelih izpiše na LCD zaslonu.\
Kosovnica:\
•	Arduino\                                                    
•	Mikrofon\
•	LCD zaslon\
•	Potenciometer\
•	Upor 220Ω\
•	Protoboard\
•	Žičke\
•	Baterija\
Program deluje po pričakovanjih. Samo točnost sva preverila tudi z drugim merilnikom. Napaka je relativno majhna. Vendar pa nastaja ti. prebijanje frekvenc oz. mikrofonija. Zato se opazijo zelo velike spremembe v merjenju. Verjetno bi z bolj zanesljivim mikrofonom zmanjšala napake. Poleg meritve sva dodala še indikator stopnje glasnosti, ki nam izpiše kako velika je možnost, da nam glasnost škodi. Upava še na kakšen projekt s podobno vsebino.
