# Oefening klassen : ladders versie 2  

## TOELICHTING

Deze oefening maak je wanneer je volgende leerstof onder de knie hebt :   
  * Je weet wat een entiteitsklasse is
  * Je kan werken met verkorte props (of fields), constructors en je weet wat override tostring() betekent
  * Je weet nog niet wat een serviceklasse is    
  
Deze oefening bouwt verder op de voorgaande oefening (ladders versie 1).  
Je kan dus een groot gedeelte van je code uit de eerste oefening hergebruiken.  

![demo](/assets/demo.gif)

## BEDOELING  

Wat de klasse en de basisfunctionaliteiten betreft kan je vorige oefening gebruiken.  

### Wat komt er bij ?

  * Je dient er voor te zorgen dat de combobox gevuld wordt met alle merken van je ladders.  Uiteraard zorg je er voor dat elk merk slechts 1 keer voor komt in deze keuzelijst.  Je zorgt er eveneens voor dat de eerste waarde in deze combobox de tekst "<alle merken>" is.  Bij opstart is deze eerste waarde geselecteerd (zodat je alle ladders te zien krijgt).  
  * Je zorgt er bij opstart ook voor dat de radiobutton rdbAll geselecteerd (gechecked) staat (de rest van de radiobuttons dus niet) zodat je zeker alle ladders te zien krijgt.  
  * Wordt in de combobox een merk geselecteerd dan dien je er voor te zorgen dat enkel de ladders van dat merk verschijnen in de listbox.  
  * Wordt één van de andere radiobuttons geselecteerd, dan zorg je er voor dat enkel die ladders in de listbox verschijnen die het corresponderend aantal secties hebben.  
  * Uiteraard dient een combinatie van deze filters (merk en secties) ook te werken.  
  * Bij de detailgegevens van een ladder is een nieuwe knop voorzien om 1 ladder te verkopen.  Deze knop is zichtbaar wanneer een ladder geselecteerd is, én wanneer de stock van deze ladder groter is dan 0.  
  * Wordt op deze knop geklikt dan dient de stock van deze ladder met 1 verminderd te worden en dient de totale verkoopswaarde van deze ladder aangepast te worden, alsook de volledige statistiek herberekend te worden.  
  * Wordt de stock 0, dan moet de knop uiteraard weer verborgen worden.  
  
