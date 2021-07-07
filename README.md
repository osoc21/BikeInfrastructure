# BikeInfrastructure

This file contains some information about the data model used.

## Op de hoofdweg (met `cycleway=*`)

Enkele algemene eigenschappen:
| Sleutels             | Beschrijving            |
|----------------------|-------------------------|
| `cycleway:surface=*` | Ondergrond fietspad     |
| `cycleway:buffer=*`  | Afstand tot autoverkeer |
| `cycleway:width=*`   | Breedte fietspad        |

### Verschillend per kant

Als eigenschappen verschillende per wegkant zijn, kan er een kant aan toegevoegd worden.
Bijvoorbeeld `cycleway:right=lane` als een aleen aan de rechterkant een fietsstrook is.
Let er hier wel op dat het hier om de kant in de richting van de OSM-weg gaat.

### Varianten `cycleway`

#### Suggestiestrook `cycleway=shared_lane`

Andersgekleurde strook asfalt, zonder markeringen. Geeft alleen ruimte voor fietser aan, maar geen verdere betekenis.

#### Fietsstrook `cycleway=lane`

![Fietsstrook](https://wiki.openstreetmap.org/w/images/1/16/Cyclelane_be.png)

#### Afzonderlijk fietspad `cycleway=track`

![Afzonderlijk fietspad](https://wiki.openstreetmap.org/w/images/9/92/Cycleway_track2_be.jpg)

## Afzonderlijk (`highway=cycleway`)
