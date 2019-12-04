# Medien — Animation : Video-Formate

## Bild-Formate

Englisch: **Aspect-Ratio**
 
- Welche Bildformate gibt es?
	- 1:√2 (DIN-A-Hochformat) 
	- √2:2 (DIN-A-Querformat)
	- 4:3 (Fernsehen: PAL, NTSC, SECAM)
	- 16:9 (Widescreen)
	- [Aspect-Ratio](https://en.wikipedia.org/wiki/Aspect_ratio_(image)) auf Wikipedia

### Frage

- Was ist das ideale Bildformat?

### Gesichtsfeld
- Gesichtsfeld des Menschen  
  
  ![](http://vmrz0100.vm.ruhr-uni-bochum.de/spomedial/content/e866/e2442/e8554/e8574/e8610/e8656/e8660/boc_auge_gesichtsfeld_ger.png)
	- Verikal: ca. 130° 
	- Horizotal: ca. 180° - 200°
	- Horizotal mit Augen-Bewegung: 270°
	
 - **Perimetrie**: Messung des Gesichtsfeldes
 
 ![](https://www.gesundheitsinformation.de/papaya-files/thumbs/f/ff0525ac0345ffe078466d23ac13a52dv1_max_500x368_b3535db83dc50e27c1bb1392364c95a2.jpg)
 
Quellen:

- [Ruhr-Uni Bochum](http://vmrz0100.vm.ruhr-uni-bochum.de/spomedial/content/e866/e2442/e8554/e8574/e8610/e8656/index_ger.html)  
-  [History of Perimetry](http://webeye.ophth.uiowa.edu/ips/PerimetryHistory/)
- [Hemispheric Perimeters of the 19th Century](http://histoph.com/wp-content/uploads/2015/03/Remky-Hemispheric-Perimeters-19th-Century.pdf) (PDF)

### Digitale Bild-Formate

![](https://upload.wikimedia.org/wikipedia/commons/thumb/f/f0/Vector_Video_Standards4.svg/1280px-Vector_Video_Standards4.svg.png)


## Digitale Farb-Auflösung

[Farbtiefe](https://de.wikipedia.org/wiki/Farbtiefe_(Computergrafik)) auf Wikipedia, gemessen in **BPP** (Bits pro Pixel)

- 1 Bit : Monochrom 
- 4 Bit : EGA-Grafikkarten (Retro-Computer, C64 ...)
- 24 Bit : True Color (je 8 bit für RGB)
- 30 Bit Deep Color (je 10  bit für RGB) 
- 48 Bit Deep Color (je 16  bit für RGB)
	
#### Fragen

- Wieviele Farben kann ich mit 1, 4, 24, 30 Bit darstellen?
- Wieviele Farben kann das menschliche Auge unterscheiden?
- Wie würde eine Apparatur aussehen um das zu testen?



## Zeitliche Video-Auflösung

**FPS** = Frames pro Sekunde

- Welche zeitliche Auflösung haben Videos?
	- Kinofilm: 24 fps
	- The Hobbit: 48 fps
	- Animation im Browser: 60 fps
	- VR-Anwendungen: 90 fps
	- Gamer: 120 fps, 240 fps
- Welche zeitliche Auflösung hat das menschliche Auge?
	- Farbwahrnehmung: ca. 30 fps
	- Helligkeit: ca. 60 fps
	- Bewegung: ca. 100 fps

## Aufgabe:

1. Welche Auflösung hat mein Display?
2. Welche Farbtiefe hat mein Display?
3. Welchen Aspect-Ratio hat mein Display

### Displays

- **DPI** — Wie groß ist ein Punkt auf dem Papier?
- **PPI** — Wie groß ist ein Pixel auf dem Display?
	- Faktoren: Auflösung und Display-Größe
	- [Dot-Pitch](https://en.wikipedia.org/wiki/Dot_pitch) auf Wikipedia

# Video-Formate und Codecs

## Container-Formate

### Codecs

- [Moving Pictures Expert Group](https://de.wikipedia.org/wiki/Moving_Picture_Experts_Group) -Standards (Für Videos)
	- MPEG 1 ( `.mpg`, `.mpeg` )
	- MPEG 2 ( `.mpg`, `.mpeg`, `.vob`, `.m2p`, `.ts`)
	- MPEG 4 (  `.mp4` )
- [H-Standards](https://de.wikipedia.org/wiki/H.-Standards) (Für Videokonferenzen)
	- H.264 – [H.264](https://de.wikipedia.org/wiki/H.264)
	- H.265 – [HVEC](https://de.wikipedia.org/wiki/High_Efficiency_Video_Coding)
- Windows-Codecs
	- WMV – [Windows Media Video](https://de.wikipedia.org/wiki/Windows_Media_Video) ( `.wmv` )
- Mobile-Video (extrem kleine Datenraten)
	- [3GP](https://de.wikipedia.org/wiki/3gp) (`.3gp`)
- Freie Codecs (keine Patente, lizenzfrei)
	- OGG [Theora](https://de.wikipedia.org/wiki/Theora) 
	- [Truemotion](https://de.wikipedia.org/wiki/TrueMotion) VPX (Google)
		- [VP8](https://de.wikipedia.org/wiki/VP8)
		- [VP9](https://de.wikipedia.org/wiki/VP9)

### Container-Formate

- Windows
	- AVI – [Audio Video Interleave](https://de.wikipedia.org/wiki/Audio_Video_Interleave) ( `.avi` )
	- ASF – [Advanced Streaming Format](https://de.wikipedia.org/wiki/Advanced_Streaming_Format) (`.asf`)
- Apple
	- MOV – [Quicktime](https://de.wikipedia.org/wiki/QuickTime#Unterst%C3%BCtzte_Formate_und_Codecs)  (`.mov`)
- Adobe
	- FLV – [Flash Video](https://de.wikipedia.org/wiki/Flash_Video) (`.flv`)
- Google
	- [WebM](https://de.wikipedia.org/wiki/WebM) ( `.webm`) 
- OGG (freies Format)
	-  [OGG](https://de.wikipedia.org/wiki/Ogg) (`.ogg`)



Siehe auch:  [Videoformate im Vergleich](https://www.nrwision.de/mitmachen/wissen/videoformate-vergleich/)

## Tools

### Video-Player
- [VLC-Player](https://www.videolan.org) (OpenSource für Linux, Windows, Mac, Android, iOS, Raspi ...)
- [Miro-Player](http://www.getmiro.com/) (OpenSource für Linux, Windows, Mac)

### Video-Encoder
- [FFmpeg](https://de.wikipedia.org/wiki/FFmpeg) (OpenSource, Kommandozeile)
	- [Handbrake](https://handbrake.fr/) (Gui)

### Raspberry-Pi

- [OMX-Player](https://www.raspberrypi.org/documentation/raspbian/applications/omxplayer.md)

## Video-Walls (Multi-Screen)

- Aufteilen des Screens auf mehrere Flächen
- Anwendung: [Digital Signage](https://de.wikipedia.org/wiki/Digital_Signage)

#### Fragen
- Welche Auflösung hat mein Original-Bild?
- Auf wieviele Bildschirme soll es verteilt werden?
- Wie bekomme ich ein Bild in dieser Auflösung vom Computer auf die Bildschirme?

### Wo wird das Video-Bild aufgeteilt?

- Auf Software-Ebene?
	- z.B. VLC: `Video Effects > Geometry > Wall`
	![](https://i.stack.imgur.com/wlYYl.png)
- Auf Betriebssystem-Ebene? (Split-Desktop)
	- z.B. [Nvidia Surround](https://www.geforce.com/hardware/technology/surround) (5 Screens)
	- z.B. [AMD Eyefinity](https://www.amd.com/de/technologies/eyefinity-professionals) (6 Screens)
- Auf Hardware-Ebene?
	- Spezial-Rechner
	- Video-Wall-Controller
- In der Cloud?
	- Networked Video-Wall
	
### Spezial-Rechner

Rechner mit mehreren oder speziellen Grafikkarten:

- z.B. [Matrox C900](https://www.matrox.com/graphics/en/products/graphics_cards/c-series/c900/) (9 Screens)
- z.B. [NVidia Quadro Mosaic](https://www.nvidia.com/de-de/design-visualization/solutions/nvidia-mosaic-technology/) (16 Screens)	

### Video-Wall-Controller

Dezidierte Hardware-Box zum decodieren / encodieren eines Video-Signals in individuelle Signale für jedes Segment

- Kleine Video-Wall Controller
	-  für kleine Installationen  — (bis 4 Screens) ca. 2000 Euro.
	- z.B. [Matrox Multimonitor](https://www.matrox.com/graphics/en/products/gxm/)
	- z.B. [DataPath X4](https://www.datapath.co.uk/legacy-products/datapath-x4)
- Große Video-Wall Controller 
	- Für Große Installationen — (16 und mehr Screens) mehrere tausend Euro.
	- z.B. [Brightlink 4x4](https://brightlinkav.com/brightlink-3x6-4k-udh-hdmi-2-0-video-wall-controller-large-scale-large-scale-up-to-18-display-2.html)
	- z.B. [Christie Spyder X80](https://www.christiedigital.com/emea/video-walls/video-wall-solutions/video-wall-controllers/christie-spyder-x80)


### USB-Videowall 

- USB-Adapter als "Externe Videokarte" 
- Pluggable — [14 Screens Demo](https://www.youtube.com/watch?v=heB94f6FHd8) (USB 2)
- Pluggable — [7 Screens Demo](https://www.youtube.com/watch?v=pYUdAWOGJ_Y) (USB 3)
- Monitors Anywhere - [USB-Wall](https://monitorsanywhere.com/usbwall/)
- OSX und Linux nicht offiziell unterstützt ([Treiber hier](https://www.displaylink.com/downloads/ubuntu))

### Networked-Videowall


- Viele kleine Einplatinen-Rechner (Zero-Client Hardware) von denen jeder einen Bildschirm ansteuert.
- Steuerung / Synchronisierung via LAN
- **Supergünstig** —  20 bis 200 EUR pro Screen statt 500 bis 2000 EUR pro Screen
- **Delay** (Echtzeit-Anwendungen)

- Open Source (Raspi-Based)
	- [Pi-Wall](http://www.piwall.co.uk/) — [Demo](https://www.youtube.com/watch?v=SSERda2aJHM)
	- [OMX-Player-Sync](https://github.com/turingmachine/omxplayer-sync) — [Demo](https://www.youtube.com/watch?v=zupHpzgcJqc)
	- [Pi-Zero-Videowall](https://github.com/reinzor/videowall/) — [Demo](https://www.youtube.com/watch?v=f5Dp35RL9q8) 
- Kommerziell (Raspi-Based)

	- [MiniMad](https://madmapper.com/minimad/) — [Demo](https://www.youtube.com/watch?v=YqKo7WgSI88)  
	![](https://madmapper.com/wp-content/uploads/MiniMad-Pierre-5-1.jpg)
	- [PocketVJ](https://pocketvj.com/)
- Kommerziell (Zero-Client)
   - [Userfull](https://www.userful.com/video-wall) (Belgien)  
     ![](https://i.ytimg.com/vi/gLtgyN8ZYlk/maxresdefault.jpg) [Control-Center Demo](http://demo.userful.com)
	- [Monitors-Anywhere](https://monitorsanywhere.com/network-video-wall/) (USA)



## Synchronisierung

- Wie präzise muß die Synchronisierung sein?
	- Standbild: Keine Synchronisierung nötig
	- Langsame Bewegung: Frame-Genau (Frame-Lock)
	- Schnelle Bewegung: Zeilengenau (Genlock)

### Synchronisierung von Video

#### Probleme
- Horizontales Screen-Tearing innerhalb eines Bildschirms — Grund: verschiedene / dynamische Frameraten → Lösung: (dynamisches) V-Sync (G-Sync, Freesync)
- Vertikales Screen-Tearing zwischen Bildschirmen — Grund: Keine Zeilengenaue Synchronisation → Lösung: Framelock, Genlock
- Horizontales Screen-Tearing zwischen Bildschrim-Reihen — Grund: Aufbau des Bildes von Oben nach Unten → [Scan Inversion](https://www.schneider-digital.com/support/download/Documents_Flyer/LCDs_OLED_LED_Videowalls/LEYARD/Leyard_WallSync_Overview.pdf) oder zusätzlicher Framebuffer für jede Bildschirm-Reihe

#### Hardware

##### Sync-Karte	 mit Ausgängen für Framelock und Genlock:  
[NVidia-Quadro-Sync](https://www.nvidia.com/de-de/design-visualization/solutions/quadro-sync/)
![](https://prographics24.de/media/image/90/2d/86/QC.jpg)  
[AMD Firepro S400](https://www.amd.com/system/files/documents/ati-firepro-s400-data-sheet.pdf)
![](https://static.bhphoto.com/images/images500x500/1464798043_1238377.jpg)  

##### Videowallcontroller mit Eingang für Genlock:
![](https://www.datapath.co.uk/images/product_images/multi_display/fx4/Datapath-Fx4-Back.png)
[Datapath-fx4](https://www.datapath.co.uk/datapath-products/multi-display-products/datapath-fx4)

### Synchronisierung von Networked Video
- Wie kann man eine Networked Videowall synchronisieren?
	- Frame-Genau?
		- Genauigkeit für 60 fps – 17 Millisekunden (1000 ms / 60 frames = 17ms )
		- [NTP](https://de.wikipedia.org/wiki/Network_Time_Protocol) — Genauigkeit: ca. 1ms im LAN ✅   
		  ([Siehe Stack Overflow](https://stackoverflow.com/questions/97853/whats-the-best-way-to-synchronize-times-to-millisecond-accuracy-and-precision-b))
		- Websockets? (z.B. [Signage OS](https://blog.signageos.io/universal-digital-signage-video-wall-sync))
	- Zeilen-Genau
		- Genauigkeit für HD (1080p) – 17 Mikrosekunden (1.000.000 μs / 60 Bilder /  1000 Zeilen = 17μs)
		- [PTP](https://de.wikipedia.org/wiki/Precision_Time_Protocol) — im LAN Genauigkeit im Mikrosekundenbereich ✅
		- GPS — Genauigkeit aus PPS-Signal: ca 2 Mikrosekunden! ✅   
		 (Siehe [Raspberry-Pi PPS-Client](https://github.com/rascol/Raspberry-Pi-PPS-Client))

Siehe auch [Clock Synchronization](https://en.wikipedia.org/wiki/Clock_synchronization) auf Wikipedia

### Networked Video mit "Genlock"?

-  Die Clients müssen ihre Videosignale im Microsekunden-Bereich synchronisieren
	- Raspberry Pi [kann das leider nicht](https://www.raspberrypi.org/forums/viewtopic.php?t=78252) :(
	- Alternativen?
		- Composite Video mit ESP? — [ESP32 Composite Video](https://bitluni.net/esp32-composite-video)
		- Arduino HDMI-Shield? — [HDMI-Shield](https://github.com/techtoys/HDMI-Shield/tree/master/Ra8876_Lite) (ca. 60 EUR)
		- Mojo (FPGA) HDMI-Shield? — [HDMI Shield](https://alchitry.com/blogs/tutorials/hdmi-shield-basics) für [Alchitry Au](https://alchitry.com/products/alchitry-au-fpga-development-board) (ca. 150 EUR)




	