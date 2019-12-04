# Medien — Animation : Video-Streaming

Von der Aufnahme zur Wiedergabe:

- Analoges Bild
- Quantisierung (Bild → Pixel, Licht → RGB-Wert) 
- Codieren (Komprimieren, Physiologisches Modell)
- Übertragen (Netzwerk)
- Decodierung (Dekomprimieren)
- Display (Pixel → Bild, RGB-Wert → Licht )

### Videoformate / Codecs

- Interframe-Kompression
- Intraframe-Kompression (I-Frames bei MPEG)


### Buffer

*Wie groß muß der Buffer sein?*

- möglichst groß (Video soll nicht hängen)
- möglichst klein (Video soll sofort starten, Echtzeit-Anforderungen)

### Broadcasting

- Ein Sender
- Viele Empfänger
	- Unterschiedliche Formate
	- Unterschiedliche Qualität

## Webcam-Input

- Browser: [getUserMedia](https://developer.mozilla.org/en-US/docs/Web/API/MediaDevices/getUserMedia)	— [Demo](https://webrtc.github.io/samples/src/content/getusermedia/gum/)
- Processing: [Video Library](https://processing.org/tutorials/video/)


## App-to-App

### OS X → [Syphon](http://syphon.v002.info/)

- Video-Sharing: [VLCSyphon](https://github.com/rsodre/VLCSyphon), [Syphoner](http://www.sigmasix.ch/syphoner/), [Syphon Recorder](http://syphon.v002.info/recorder/)
- VJ-Software: [MadMapper](https://madmapper.com/), [VidVox](https://vidvox.net/), ...
- Projection-Mapping: Resolume, VDMX
- Dome-Projection: [OmniDome](https://github.com/WilstonOreo/omnidome/), 
- Creative Coding: [Processing](https://github.com/Syphon/Processing/releases), [OpenFrameworks](https://github.com/astellato/ofxSyphon), [Cinder](https://github.com/rezaali/Cinder-Syphon), [Max/Jitter](https://github.com/Syphon/Jitter)
- Virtual Reality: [Unity](https://github.com/keijiro/KlakSyphon)


### Windows → [Spout](http://spout.zeal.co/)

- VJ-Software: [MadMapper](http://resolume.com/blog/11110/spout-sharing-video-between-applications-on-windows)
- Creative Coding: [Processing](https://github.com/leadedge/SpoutProcessing),  [OpenFrameworks](https://github.com/elliotwoods/ofxSpout), [Cinder](https://github.com/brucelane/Cinder-Spout), [VVVV](https://vvvv.org/blog/spout-0), [Max/Jitter](http://spout.zeal.co/forums/topic/max-package-manager/)...
- Virtual-Reality: [Unity](https://github.com/sloopidoopi/Spout4Unity)
- Light-Show: [ENTEC LED-Mapper](https://www.enttec.com/product/controls/addressable-led-pixel-control/pixel-mapping-software/)
	

## Computer-zu-Computer

### MJPEG

- [Motion JPEG](https://de.wikipedia.org/wiki/Motion_JPEG)
	- Supersimpel
	- Browser, VLC, iPhone (Safari) ...
- MJPEG-Streamer ([Windows](https://www.microsoft.com/de-de/p/mjpeg-streamer/9n7g34wvvpnk)
- [IPCapture](http://www.stefanobaldan.com/projects/ipcapture/) (Processing)

### NDI
- High Quality, Low Latency (~1 Frame)
- [NDI Tools](https://ndi.tv/tools/)
 	- Video Distribution, Video Walls (NDI Studio Monitor)
	- Screen Recording (NDI Scan Converter)
	- Virtuelle Kamera (NDI Virtual Input)
	- [NDI Viewer](https://orfast.com/) (Windows, Linux) 


- [NDI Tools](https://ndi.tv/tools/): NDI Virtual Input (Webcam Simulator)

## Browser-zu-Browser

### WebRTC

- [WebRTC](https://de.wikipedia.org/wiki/WebRTC) auf Wikipedia
- [Web RTC: Videotelefonie ohne Browser-Plugin](Web RTC: Videotelefonie ohne Browser-Plugin)
- Raspberry Pi: [Balena Cam](https://www.balena.io/blog/build-a-raspberry-pi-based-network-camera/)
