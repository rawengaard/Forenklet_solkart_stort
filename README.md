# Forenklet_solkart

Forenklet solkart over optimale steder for å oppleve soloppgang og solnedgang i Oslo (sommertid).

Solkartet er laget ved bruk av programmet QGIS. Bakgrunnskartet er Kartverkets N50 topo, og fylkesgrensen for Oslo er hentet fra Kartverkets «Administrative enheter fylker». 

Det er gjort en Viewshed-analyse basert på Kartverkets digitale overflatemodell (DOM), som inkluderer vegetasjon og bygninger, kombinert med gjennomsnittlige posisjoner for solen ved soloppgang og solnedgang sommerstid. For å forenkle lesingen av kartet, gjennomgikk rasterlagene en naboanalyse. Dette betyr at man i bygater direkte bak 
bygninger også vil få en markering som om man har direkte siktlinje til solen, til tross for at det kun gjelder når man står ved siden av eller foran bygningen. Det blir noe upresist, men større flater med fargekoding vil være lettere å lese.

Kartet er publisert på GitHub, i dimensjoner som passer de fleste smarttelefoner. 

Lenke til kartet: https://rawengaard.github.io/Forenklet_solkart/#9/59.9832/10.6828

----------------------------------------------------------

Simplified sunmap of optimal places to experience the sunrise and sunset in Oslo (summertime).

The sunmap was made in QGIS. The background map is the Norwegian Mapping Authority (Kartverket) N50 topo, and the county bounary of Oslo is collected from "Administrative enheter fylker" by the Norwegian Mapping Authority.

The map has a Viewshed analysis based on the Norwegian Mapping Authority's digital surface model (DSM), which includes vegetation and buildings, combined with the average position of the sun at sunrise and sunset in the summer. To simplify the reading of the map, the raster layers went through a neighbour analysis. This means that streets behind buildings will be marked as if they have direct lines of sight to the sun, even though that is only true when standing next to or in front of the bulding. This makes the map slightly imprecise, but the larger areas of colors will be easier to read.

The map is published on GitHub, in dimensions suitable for most smart phones.

Link for the map: https://rawengaard.github.io/Forenklet_solkart/#9/59.9832/10.6828
