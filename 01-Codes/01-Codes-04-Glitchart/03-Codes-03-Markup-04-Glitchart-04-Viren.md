## SVG-Glitch-Art – Viren

### Polynomic

JS-Bibliothek zum arbeiten mit SVG-Pfaden

- [Codepen](https://codepen.io/anthonydugois/pen/ORyaRz)-Beispiel
- [Polynomic Beispiel-Code](https://codesandbox.io/s/02oqn) und [Demo](https://02oqn.csb.app/) (Chrome!)
- Einbinden via unpkg: `https://unpkg.com/polynomic@0.2.1/dist/polynomic.js`


**Pfad einlesen, rotieren und ausgeben:**
		
	let path = Polynomic.pathstring.parse(pathstring);
	path = Polynomic.transforms.rotate(path,  Math.PI / 3, "center", "center");
	pathstring = Polynomic.pathstring.build(path);
	
### Snap

JS-Bibliothek für Erzeugung von SVG. 

**Relative in absolute Pfade umwandeln (und andersrum):**

	let relpath = Snap.path.toRelative(pathstring).toString();
	let abspath = Snap.path.toAbsolute(pathstring).toString();

### Glitch-Animation


**Glitch-Funktion bei jedem Frame aufrufen** (mit `requestAnimationFrame`)  
Beispiel: [Umbrella Animation ](https://tb01l.csb.app/) (Chrome) + [Code](https://codesandbox.io/s/svg-glitch-tb01l)

	let g = 0;
		
	function updateSVG() {
	  g = (g + 1) % 50;
	  glitch(g);
	  requestAnimationFrame(updateSVG);
	}
				
	function glitch(d) {
	  d = pathstring.replace(/c/g, `l${d},${d} h10 l-${d}-${d}c`);
	  document
	  	.querySelector("#party svg path")
	  	.setAttribute("d", d);
	}
		
	requestAnimationFrame(updateSVG);
		

	


