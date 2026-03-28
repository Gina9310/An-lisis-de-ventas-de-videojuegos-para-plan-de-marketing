
# 📊 Análisis de Ventas de Videojuegos para Plan de Marketing

Este proyecto analiza las ventas de videojuegos a nivel mundial con el objetivo de identificar tendencias de mercado y apoyar la toma de decisiones en estrategias de marketing.  
El análisis se realiza en Python dentro de un Jupyter Notebook.

---

## 📂 Contenido del repositorio
- `videojuegos por todo el mundo.ipynb` → Notebook principal con el análisis paso a paso.
- `games.csv` → Dataset con información de ventas de videojuegos.
- `dashboard_videojuegos.png` → Visualización resumen de los resultados.
- `README.md` → Documentación del proyecto.

---

## ⚙️ Requisitos
- Python 3.10+
- Jupyter Notebook
- Librerías:
  - pandas
  - matplotlib
  - seaborn

Instalación rápida:
```bash
pip install pandas matplotlib seaborn

Hallazgos:

1.- las ventas totales dentro de un periodo de 36 años (1980-2016) fueron de 8,816.75 millones de dolares, de las cuales el 49% tuvieron lugar en norteamerrica, el 27% en europa y el 14% en japón y solo el 10% en algún otro lugar del mundo.

2.-las plataformas con las que más ventas se han registrado son: PS2,X360,PS3,wii y DS, lo cual no quiere decir que todos y cada uno de los 36 años fue asi, pues para empezar de 1980-1990 habia tan solo de 1 a 4 plataformas, para el año 2000 habia 9 y asi hasta 2016, es decir, los primeros años la plataforma número uno en ventas era NES pero los ultimos 10 años lo fueron PS4,Xbox, PS3.

3.-Del 1985-2000 la plataforma PS fue la pionera en ventas, del 2000 al 2007 lo fue PS2 y GBA y de 2012-2016 lo fue PS3, PS4, X360 y Xone.

4.-Con relación al juego, los juegos que mayor ventas acumularon, dentro del perido de analisis, fueron: wii sports (wii), Grand theft acto (NES), super mario (wii), tetris(wii) y Marios kart (GB). Resulta curioso como ningun juego de la plataforma PS2 aparece en este listado, pues es la plataforma con mas ventas, quizás esto se responde resaltando que también es la plataforma con más cantidad de juegos disponibles, para ser exactos 2127. Quizas es la plataforma con mas ventas pero no precisamente porque algun juego haya sido la sensación, de hecho el juego Grand theft acto en la plataforma PS2, es el juego con más ventas:20.8)

5.-Con relación al género, el analisis permite visualizar que aunque en las ventas totales, el género acción es el número uno. hubo años en la que otros géneros repuntaron, por ejemplo: género shooter fue el género con mayores ventas (1980,1984,2006), o el género puzzle (1982), platform (1983,1985,1988)

6.- las calificaciones de usuarios no esta directamente relacionada con la cantidad de ventas, la calificación de los expertos tienen mas relación con las ventas.

7.- finalmente y por región se tienen las siguientes conclusiones:

en ventas:

*las principales plataformas en la zona de norteamerica son: x360, PS2, wii, PS3 y DS.

*las principales plataformas en la zona de europa son: PS2,PS3,X360,WII Y PS

*las principales plataformas en la zona de europa son: DS,PS,PS2, SNES Y 3DS

en géneros:

*los principales géneros en japon son: role-playing, action, sports, platfomr y misc

*los principales géneros en la zona de norteamerica son: action, sports,shooter, platform y misc

*los principales géneros en europa son: action, sports, shooter, racing y misc

