## SVG-Glitch-Art – Mutation

### Find & Replace

- Relative durch Absolute Kommandos ersetzen
- Absolute durch Relative Kommandos ersetzen
- Kommandos mit gleicher Anzahl Argumente 
	- MoveTo durch LineTo ersetzen
	- 6n → 3 x 2n
	- 6n → 2n + 4n
- Einfügen von Extra-Loops
	- Schnörkel
	- Glitches
	- ...
- ...

### Pfad-Kommandos 

Nach Anzahl der Argumente

#### 0 args

- `Z` close path

#### 1n args

- `H` horizontal line to — `x`
- `V` vertical line to  — `y`

#### 2n args

- `M` moveto —  `x,y`
- `L` lineto  — `x,y`
- `T` smooth quadratic bezier  — `x,y`


#### 4n args

- `Q` quadratic bezier to —  `x1,y1, x,y`
- `S` smooth cubic bezier to —  `x2,y2 x,y`

#### 6n args

- `C` cubic bezier curve to —  `x1,y1 x2,y2 x,y`

#### 7n args

- `A` elliptic arc to — `rx,ry  x-axis-rotation large-arc-flag,sweep-flag  x,y`
	
