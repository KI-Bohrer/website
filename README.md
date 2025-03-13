# Forschungsprojekt zur KI-Steuerung zum Schallschutz bei urbanen Geothermiebohrungen
Laufzeit: 6/23 - 12/26

<img src="BMBF.jpeg" width=300>

## Projektbeschreibung
### Geothermie als alternative Strom- und Wärmequelle zur Erreichung der Klimaziele. 
Die Einhaltung der international vereinbarten Klimaziele inklusive der Begrenzung der globalen
Erwärmung auf möglichst unter 1.5 Grad Celsius ist sicherlich eine der größten technischen
und gesellschaftlichen Herausforderungen der nächsten Jahrzehnte. Ohne einen weiteren
massiven Ausbau der CO2 neutralen Energiegewinnung werden diese Ziele nicht erreicht
werden können. Geothermische Kraftwerke, insbesondere siedlungsnahe Anlagen mit
Wärmekopplung könnten hier einen entscheidenden Beitrag zur klimaneutralen Wärme- und
Stromversorgung in Ballungszentren leisten. Vorausgesetzt einer geologischen Eignung
eines Standorts, haben geothermische Anlagen einige entscheidende Vorteile gegenüber
anderen regenerativen Technologien: I) dezentrale Anlagen kleiner bis mittlerer Leistung
erlauben eine lokale Versorgung mit Fernwärme und erreichen so einen sehr hohen
Wirkungsgrad; II) existierende Kohle- und Gaskraftwerke können unter Nutzung der
bestehenden Infrastruktur nachhaltig und kostengünstig umgerüstet werden; und III) im
Betrieb sind die Anlagen optisch unauffällig, leise und geruchsfrei, was zu einer hohen
Akzeptanz in der Bevölkerung beiträgt.

### Problemstellung: Schallschutz bei urbanen Geothermiebohrungen. 
Neben den
vielfältigen Vorteilen im Betrieb, hat die Errichtung geothermischer Anlagen in
Ballungsräumen aber auch ein wesentliches technisches und gesellschaftliches Problem: mit
aktuell verfügbaren Verfahren führen die notwendigen Tiefenbohrungen an den urbanen
Standorten zu erheblichen und langwierigen Lärmbelästigungen für die Anwohner.
Insbesondere da Bohrungen aus technischen und wirtschaftlichen Gründen kontinuierlich, 24
Stunden am Tag, 7 Tage die Woche über Monate hinweg laufen müssen, stellt die
Einhaltung gesetzlicher Schallgrenzwerte von typischerweise 35dB (nachts in
Wohngebieten) eine enorme technische und logistische Herausforderung dar. Derzeitige
Ansätze zum Schallschutz setzen auf eine Kombination aus I) kontinuierlicher Überwachung
der Schallemissionen durch akustische Messungen in der Umgebung; II) Optimierung der
Baustellenlogistik, z.B. Verlagerung lauter Aktivitäten auf bestimmte Tageszeiten; III)
passiven Schalldämmungen durch Schutzwände und Einhausungen der Bohranlagen; IV)
aktiver Schallreduktion durch (aktuell) manuelle Wahl von Steuerparametern der Bohrungen.

### Lösungsansatz: aktive Schallreduktion durch KI-basierte Steuerung der Bohranlagen.
Während die Ansätze I-III derzeit zum technischen Standard gehören, sehen wir bei der
aktiven Schallreduktion noch erheblichen Innovationsspielraum und Bedarf. Mit der aktuell
geläufigen manuellen Steuerung kann der umfassenden Komplexität des gestellten
Optimierungsproblems nur unzureichend begegnet werden: Schallschutz und technisch
sicherer, wirtschaftlicher Vortrieb der Bohrung sind nicht nur gegenpolige Ziele, auch die
Überwachung vielfältiger Zustands- und gleichzeitige Anpassung hunderter Steuerparameter
ist manuell nur suboptimal umsetzbar. Daher ist es das Ziel dieses Projektes, die
Optimierung des Bohrbetriebs mittels aktueller KI-Verfahren zu automatisieren. Wir erwarten
durch diesen grundsätzlich neuen Ansatz eine deutliche Verbesserung des Schallschutzes
für die Anwohner bei gleichzeitiger Steigerung der Vortriebsgeschwindigkeit. Dadurch soll
nicht nur die Akzeptanz von Geothermieprojekten, sondern auch deren Wirtschaftlichkeit
erheblich erhöht werden. Beide Verbesserungen gegenüber dem Stand der Technik könnten
einen wesentlichen Beitrag zum weiteren Ausbau der Geothermie und somit zur Erreichung
der übergeordneten Klimaziele beitragen.

## KI-Bohrer in der Presse
* [Schwarzwälder Bote: Künstliche Intelligenz soll Bohrungen leiser machen (28.9.23)](https://www.schwarzwaelder-bote.de/inhalt.hochschule-und-herrenknecht-forschen-kuenstliche-intelligenz-soll-bohrungen-leiser-machen.d9c38ef0-6662-44ab-8e5d-6c5a202c9303.html)

* [Badische Neuste Nachrichten: Künstliche Intelligenz soll leisere Erdwärme-Bohrungen in Offenburg ermöglichen (27.9.23)](https://bnn.de/mittelbaden/ortenau/offenburg/ki-soll-leisere-erdwaerme-bohrungen-in-offenburg-ermoeglichen)


## Publikationen

### Konferenzbeiträge
* [*M. Spitznagel, J. Keuper, Urban Sound Propagation: a Benchmark for 1-Step Generative Modeling of Complex Physical Systems, DMLR Workshop at ICRL 2024*](https://openreview.net/pdf?id=1vCAi53AVj)
* [Ladwig, D., Spitznagel, M., Vaillant, J., Dorer, K., & Keuper, J. (2024, October). AI-Guided Noise Reduction for Urban Geothermal Drilling. In Proceedings of the Upper-Rhine Artificial Intelligence Symposium (pp. 85-94).](https://journals.hs-offenburg.de/index.php/urai/article/view/7)
*[Spitznagel, M., Vaillant, J., Keuper, J., PhysicsGen: Can Generative Models Learn from Images to Predict Complex Physical Relations?, Accepted at IEEE/CVF International Conference on Computer Vision Workshops (CVPR) 2025](https://arxiv.org/abs/2503.05333)

### Datensätze
#### Urban Sound Data: 
*This dataset is assembled for research into urban sound propagation, comprising 25,000 data points across 10 diverse cities. Each city is represented by 2,500 locations, offering a comprehensive analysis of various urban configurations. The dataset utilizes OpenStreetMap (OSM) imagery to detail the urban layout within a 500m x 500m area for each location, where buildings are delineated with black pixels and open spaces with white pixels.*

<img src="https://www.urban-sound-data.org/figures/sample_overview_reduced.png">

[https://www.urban-sound-data.org/](https://www.urban-sound-data.org/)

#### PhysicsGen Benchmark
*The image-to-image translation abilities of generative learning models have recently made significant progress in the estimation of complex (steered) mappings between image distributions. While appearance based tasks like image in-painting or style transfer have been studied at length, we propose to investigate the potential of generative models in the context of physical simulations. Providing a dataset of 300k image-pairs and baseline evaluations for three different physical simulation tasks, we propose a benchmark to investigate the following research questions: i) are generative models able to learn complex physical relations from input-output image pairs? ii) what speedups can be achieved by replacing differential equation based simulations? While baseline evaluations of different current models show the potential for high speedups (ii), these results also show strong limitations toward the physical correctness (i). This underlines the need for new methods to enforce physical correctness.*

<img src="https://www.physics-gen.org/figures/teaser_vertical_3.png">

[https://www.physics-gen.org/](https://www.physics-gen.org/)

## Partner:
&nbsp;<img src="hso.png" width=150>&nbsp;&nbsp;<img src="IMLA.png" width=250><img src="hk.jpg" width=250>

## Kontakt
Prof. Janis Keuper <br>
Institute for Machine Learning and Analytics <br>
HS Offenburg <br>
*janis.keuper* -at- *hs-offenburg.de*  <br>
