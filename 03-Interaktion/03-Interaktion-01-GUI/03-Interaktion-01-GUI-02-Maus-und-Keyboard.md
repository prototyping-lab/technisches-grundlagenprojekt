# Interaktion — Animation : Maus & Keyboard

## Maus

### Douglas Engelbart

- Die Mutter aller Demos
- Erfinder der Maus 

## Wieviele Knöpfe?
- Erste Maus: 1 Knopf (kein Platz für mehr)
![](https://images.computerhistory.org/blog-media/fellow-douglas-engelbart-mouse.jpg)
- Nächster Prototyp: 3 Knöpfe (kein Platz für mehr) 
- Doug Engelbart wollte soviele Knöpfe wie möglich 

## Fragen

- Warum überhaupt Knöpfe auf der Maus?
- Wieviele Knöpfe will man mindestens haben, wieviele höchstens?

## Klaviatur (linke "Maus")

![](https://www.dougengelbart.org/images/pix/img0030.jpg)

- Zustände: Knopf hat 2 Zustände (gedrückt, nicht gedrückt)
- Was sind Vor und Nachteile von:
	- Einer Taste?
	- Fünf Tasten?
	- Hundert Tasten?
- Wieviele Kombinationen (Combos) kann ich mit 5 Tasten ausführen (Tipp: Binärcode!)
- Wieviele Kombos kann ich mit einer Drei-Button-Maus ausführen?
- Wieviele Kombos mit einer One-Button-Maus plus [Shift], [Control] [Alt] [Fn] und [Command]?
- Andere Dimensionen: Dauer, Rhythmus, Druck, Anschlag 
- Welche Dimensionen werden bei der Maus genutzt, welche bei Touch interfaces?

## Augment

- Werkzeuge zur Erweiterung menschlicher Fähigkeiten
- Deaugment: Backstein + Stift:

![](https://www.dougengelbart.org/images/pix/img0039.jpg)

## 3D-Mäuse

- 2D-Mäuse
	- Steuerung in der XY-Ebene
- [3D-Mäuse]()
	- Maus-Gesten (2D + Zeit = 3D)
	- Steuerung im Raum

### 3D Tisch-Mäuse (eigentlich 3D-Joystick)

![](https://upload.wikimedia.org/wikipedia/commons/thumb/1/17/Space-Navigator.jpg/640px-Space-Navigator.jpg)

- Zusätzliche Freiheitsgrade: 
  [6DOF](https://en.wikipedia.org/wiki/Six_degrees_of_freedom)  
  ![](https://upload.wikimedia.org/wikipedia/commons/thumb/2/2a/6DOF.svg/200px-6DOF.svg.png)
- 3 Freiheitsgrade der Translation: links-rechts, vor-zurück, hoch-runter
- 3 Freiheitsgrade der Rotation (Yaw, Pitch, Roll)   
    deutsch auch [Roll,Nick,Gier](https://de.wikipedia.org/wiki/Roll-Nick-Gier-Winkel)-Winkel

### 3D Raum-Mäuse

- Sehr beliebt in der VR
- Controller als Alternative zu Datenhandschuhen
![](https://steamcdn-a.akamaihd.net/steamcommunity/public/images/clans/5519564/ac1662a3852771653f7d51232fac92672889cdaf.jpg)

### Maus vs Touch

- Maus: Position = Lokalisieren, Knopf = Aktivieren
- Touch: Finger-Position = Lokalisieren und Aktivieren in einem (!)
- Maus, Touchpad usw. sind ist immer indirekt
	
## Maus-Interaktion im Browser

### Maus-Interaktion mit CSS

- Pseudoklasse `:hover` – Maus drüber (mouseover)     
  [Beispiel-SVG](https://upload.wikimedia.org/wikibooks/de/b/bb/SVG_CSShover01.svg)
- Pseudoklasse `:active` – Maus gedrückt (mousedown)    
  [Beispiel-SVG](https://upload.wikimedia.org/wikibooks/de/d/da/SVG_CSSactive01.svg)


### Maus-Interaktion mit Javascript
- Mouse-Events – [Beispiele auf W3-School](https://www.w3schools.com/js/js_htmldom_events.asp) 
- Maus-Klick
	- click (drücken, loslassen)
	- dblclick (drücken, loslassen, drücken, loslassen)
	- mousedown (drücken)
	- mouseup (loslassen)
- Mause-Bewegung
	- mouseleave,  mouseout (Maus verlässt Bereich / Element)
	- mousenter, mouseover (Maus "betritt" Bereich / Element)
