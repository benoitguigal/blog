---
title: "Pollution et science collaborative"
date: 2019-03-13 10:38:00
---

### Les AASQA

En France, les mesures de pollution de l'air sont réalisées par les AASQA ou *associations agréés de surveillance de la qualité de l'air*. Constituées dans les années 70, les AASQA sont présentes dans chaque région et son regroupées au sein de la fédération Atmo. Leurs rôle est de mesurer, informer, sensibiliser et imaginer des solutions pour améliorer la qualité de l'air. Elles sont notamment à l'origine du déclenchement des épisodes de pollution qui permettent de mettre en place des  mesures de mitigation (réduction de la vitesse, circulation différenciée, etc). Autrement dit, les AASQA sont à la pollution ce que Météo France est à la météo.

<blockquote class="twitter-tweet" data-lang="en"><p lang="fr" dir="ltr">[EPISODE DE POLLUTION ] Les niveaux en <a href="https://twitter.com/hashtag/particules?src=hash&amp;ref_src=twsrc%5Etfw">#particules</a> sont élevés en Ile-de-France du fait d&#39;une forte inversion des températures. Pour comprendre ce phénomène et l’accumulation des émissions qui a lieu ⏬ <a href="https://twitter.com/hashtag/pollution?src=hash&amp;ref_src=twsrc%5Etfw">#pollution</a> <a href="https://twitter.com/hashtag/air?src=hash&amp;ref_src=twsrc%5Etfw">#air</a> <a href="https://twitter.com/hashtag/AirPollution?src=hash&amp;ref_src=twsrc%5Etfw">#AirPollution</a> <a href="https://t.co/rewk0N5q7n">pic.twitter.com/rewk0N5q7n</a></p>&mdash; Airparif (@Airparif) <a href="https://twitter.com/Airparif/status/1100682096509665280?ref_src=twsrc%5Etfw">February 27, 2019</a></blockquote>
<script async src="https://platform.twitter.com/widgets.js" charset="utf-8"></script>
<figcaption style="text-align: center">Tweet de AirParif expliquant les causes du dernier pic de pollution</figcaption>
<br/>

Les données des AASQA sont ouvertes [^1] et librement accessibles en téléchargement depuis les sites respectifs des différentes associations ou depuis les plateformes de publication de données comme [data.gouv](https://www.data.gouv.fr).

### Mobilisation citoyenne

Cependant, devant les dernières études qui révèlent l'ampleur des risques sanitaires causés par la pollution [^2] [^3] et devant une relative inaction des pouvoirs publics [^4], de nombeux citoyens et associations se mobilisent [^5]. On pense notamment à l'action menée par Greenpeace en février dernier et consistant à tagguer dans différentes villes dont Marseille des graffitis #onveutrespirer pour inciter les pouvoirs publics à changer de politique en matière de transports.

![#onveutrespirer]({{site.url}}/assets/images/pollution/onveutrespirer.png)

### Science participative

Le développement de l'électronqique opensource (Arduino, Raspberry Pi, etc), des fablabs et de capteurs *low cost* a permis l'essor de nombreux projets partipatifs de mesure de la qualité de l'air. Ces projets ont avant tout une vocation éducative de sensibilisation mais offrent de réelles perspectives dans le champs de la recherche scientifique en apportant une grande quantité de données *crowd sourcées*.

On peut citer entre autres les projets suivants:

* [Luftdaten](https://luftdaten.info/)
* [SmartCitizen](https://smartcitizen.me)
* [AirCitizen](http://aircitizen.org/)
* [AirCasting](http://aircasting.org/)

<br/>

Ils permettent de créer des cartes collaboratives de la qualité de l'air à partir de données récoltées par des stations de mesures DIY. Exemple avec le projet *Luftdaten* de l'Opendata lab de Stuttgart.

<iframe id="Lufdaten"
    title="Luftdaten"
    width="100%"
    height="500"
    src="http://deutschland.maps.luftdaten.info/#5/46.514/11.316">
</iframe>

<br/>

Ci-dessous ma propre station de mesure de la qualité de l'air sur mon balcon à Marseille


![station diy]({{site.url}}/assets/images/pollution/station-diy.jpg)
<br/>

Les données du capteur de particules fines sont disponibles en temps réel à cette adresse:
[https://www.madavi.de/sensor/graph.php?sensor=esp8266-2682864-sds011](https://www.madavi.de/sensor/graph.php?sensor=esp8266-2682864-sds011)


[^1]: [https://atmo-france.org/les-donnees/](https://atmo-france.org/les-donnees/)

[^2]: [La polution de l'air tue deux fois plus que prévu](https://www.lemonde.fr/planete/article/2019/03/12/la-pollution-de-l-air-tue-deux-fois-plus-que-prevu_5435029_3244.html)

[^3]: [La pollution de l'air tue désormais davantage que le tabac](https://www.franceinter.fr/sciences/la-pollution-de-l-air-tue-desormais-davantage-que-le-tabac?fbclid=IwAR1TV4KOIz2o34e-5U9LaHGsPEzNwquRoAXw3wjy6Vr0tXmdlpmDfSv8MJI)

[^4]: [Bruxelles renvoie la France devant CJ de l'UE](https://www.lemonde.fr/pollution/article/2018/05/17/pollution-de-l-air-bruxelles-renvoie-la-france-devant-la-cour-de-justice-de-l-union-europeenne_5300331_1652666.html)

[^5]: [Marseille, mobilisation citoyenne contre la pollution de l'air](https://france3-regions.francetvinfo.fr/provence-alpes-cote-d-azur/bouches-du-rhone/marseille/marseille-mobilisation-citoyenne-contre-pollution-air-1450715.html)






