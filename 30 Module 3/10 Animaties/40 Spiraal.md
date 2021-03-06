# Opdracht: animatie van spiraliserende stip

Een balletje draait met een bepaalde hoeksnelheid rond en met elke stap in de
tijd verandert niet alleen de hoek, maar wordt ook de straal steeds kleiner tot
hij uiteindelijk precies in het midden stilstaat:

![](AnimationInspiral.gif)

Op elk moment wordt een punt beschreven door twee coordinaten $$(x,y)$$, maar je
kan ook 2 andere variabelen gebruiken ($$\alpha$$, R), waarbij $$\alpha$$ de
hoek is met de positieve $$x$$-as en $$R$$ de afstand tot de oorsprong. De
variabelen kunnen in elkaar omgeschreven worden zoals in de grafiek is
aangegeven.

![](UitlegPolarCoordinates.png)

Schrijf een functie `spiraal()` in een bestand **spiraal.py** waarin de stip geanimeerd wordt zoals hierboven beschreven. Details voor de animatie:

   - $$\alpha$$ varieert van $$0$$ tot $$20$$ in stappen van $$0.1$$
   - $$R$$ hangt af van $$\alpha$$, nl: $$R=10-0.5\alpha$$

Zorg dat alle code voor de animatie in diezelfde functie `spiraal()` staat.
