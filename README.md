# Skall-til-kontroller
## Her er filer for å lage skallet til kontrolleren.

![Bilde av ferdig kontroller](https://github.com/Konsollkameratene/Skall-til-kontroller/assets/113992886/c645173a-9f41-493b-ae03-45b2acde618c)


###Materialer
*6 mm MDF
*4 mm Acryl
*PLA
*Limpistol
*2 knapper
*Joystick
*Raspberry pi pico

###3D-printing
Veggen til kontrolleren er printet med tree support, 5mm brim og infill satt til 15%.

Vi endte med å kutte vek noe av noe ved topp- og bunnplate for å skape en bedre overgang. Topp- og bunnplate skal limes på plass for at den skal sitte.

###Laserkutte
I SVG-filen er rødt der den skal kutte og gråskalaen skal graveres. 

Avhengig av knapper og joystick kan det være at hullene i topp platen skal være større eller mindre.

###Tilkobling til pico

| Raspberry pico  | Joystick        |
| --------------- |:---------------:|
| GND             | GND             |
| 3V3             | 5V              |
| VRx             | GP26            |
|VRy              |GP27             |
|SW               |GP28             |

Koble venstre knapp til GND og GP14, og høyre knapp til GND og GP17.

###Montering av pico, knapper og joystick
Både knapper og joystick ble festet med limpistol. Picoen ble skrudd på en plate som ble limt til bunnplaten til konsollen.
