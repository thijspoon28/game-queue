# game-queue
this dipository is for all that has to do with my game queue program

oke duss
to research:
how do games rate: 
how are players and player groups that queue rated and compaired to other players and groups

how do games match:
do queue's and how do they match diffrent searching groups together to form a game lobby. (is this set or does it keep searching and are search loops a thing)

how do games find: 
how does the queue bot decide that players x are the best match for now and starts the game

what optimises the process and reduces the work load: !!!


wiki site voor gliko gating met voorbeeld
https://en.wikipedia.org/wiki/Glicko_rating_system
https://github.com/deepy/glicko2

priority queues how they work
makkelijk te snappen, lastiger om te coden (denk ik)
https://www.youtube.com/watch?v=CXT-xcnXCBI
betere uitleg over hoe priority queues werken
https://towardsdatascience.com/introduction-to-priority-queues-in-python-83664d3178c3



duss voor een game queue heb je nodig:
priority queues
glicko gating






ZELF EEN QUEUE BOT SCHRIJVEN
nodig is een prote input aan spelers met een non defined rank.
een vorm van matchmaking die ze verdeeld en tegen elkaar op zet.
per player ranking.
en vooral een manier om searching players samen te stellen


V1
spelers met random rating tegen elkaar laten laten spelen en zo de playerbase sorteren.



SPELER (waar moet een speler uit bestaan)

in dit voorbeeld is iedere speler een dobelsteen.
het aantal ogen zit tussen de 0 en de 999
iedere speler heet een laagste worp,
een hoogste worp en een gat ertussen. duss:
1-6 zou een normale dobbel steen zijn en
10-20 kan overal tussen de 9 en 21 kunnne gooien.



MATCH

een match bestaat uit 2 spelers die tegen elkaar op moeten. ze speler een aantal rondes (wat voor nu warschijnlijk gewoon 1 is)
waarin ze allebij HUN steen opgooien. beste worp wint slechtste worp verliets. 
skill verschil word bepaald met hoe groot of hoe klein de winst is. (bot bepaald dus acurater met mer rodes)


