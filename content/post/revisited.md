---
title: "my.awesomeBible revisited"
date: 2021-12-19T15:47:30+01:00
image: "/images/revisited/feature_image.png"
---
Die Entwicklung von my.awesomeBible hat in letzter Zeit ein wenig stagniert.

Ich hatte viel anderes zu tun und habe irgendwie die Energie für das Projekt verloren. Aber jetzt - nach fast 3 Monaten - hatte ich ein Wochenende wo ich wieder Motivation gefunden habe. 😊

## $ npm install && npm run dev
Als ich die Web UI nach 3 Monaten wieder gestartet habe, ist mir mir direkt eine Sache ins Auge gefallen: *Alles ist grau.*
An vielen stellen hat einfach die Farbe gefehlt.

Alles funktionerte noch wie gewohnt, aber es fehlte eben an Farbe.

## $ npm update
Das erste was ich dann gemacht habe, ist zu [TailwindCSS 3](https://tailwindcss.com/blog/tailwindcss-v3) zu upgraden.
Passender Weise, sind eine der Neuerungen [eine Menge mehr Farben](https://tailwindcss.com/blog/tailwindcss-v3#every-color-out-of-the-box).
Das war die perfekte Gelegenheit die Dominanz von Grau zu beheben.

Außerdem habe ich mir die Zeit genommen, endlich einen Dark-Mode zu implementieren. 🌒
Das ging mit dem Tailwind `dark:`-Prefix einfach und schnell.

~~Jetzt fehlt uns nur noch Comic Sans.~~

![Die Featureübersicht im Darkmode](/images/revisited/Screenshot153522.png)
![Das FAQ im Darkmode](/images/revisited/Screenshot153609.png)
![Der Footer im Darkmode](/images/revisited/Screenshot153656.png)

* * * 

Mir hat es ziemlich gut getan, mal 2 oder 3 Monate nicht an my.awesomeBible zu arbeiten, und so einen völlig neuen Blick darauf zu bekommen.
So, dass wars.

Hast du Gedanken zu diesem Post oder zum Projekt - schreib uns auf Matrix: [@awesomebible:matrix.org](https://matrix.to/#/@awesomebible:matrix.org) oder tritt unserem [Matrix-Space](https://matrix.to/#/#awesomebible:matrix.org) bei.