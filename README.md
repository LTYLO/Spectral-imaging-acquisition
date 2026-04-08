<!-- ============================================================== -->
<!-- PROJECT ····· SPECTRAL-SCAN-SIM                               -->
<!-- CLASS ······· SCIENTIFIC SIMULATION · PYTHON                   -->
<!-- METHODS ····· POINT · LINE · WAVELENGTH                        -->
<!-- ORIGIN ······ COLOMBIA 🇨🇴                                     -->
<!-- BUILD ······· v1.0                                             -->
<!-- ============================================================== -->

<!-- ░░░░░░░░░░░░░░░░░░░░░░░░ HEADER ░░░░░░░░░░░░░░░░░░░░░░░░░░░░ -->
<div align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&height=240&text=SpectralScanSim&fontSize=72&color=0:020B18,40:051428,100:020B18&stroke=00FFB2&strokeWidth=2&fontColor=00FFB2&animation=twinkling&desc=Point+·+Line+·+Wavelength+Scanning+Simulation&descSize=15&descAlignY=80&descAlign=50&descFontColor=5AFFD6" width="100%"/>
</div>

<!-- TYPING -->
<div align="center">
  <img src="https://readme-typing-svg.herokuapp.com?font=Fira+Code&weight=500&size=16&duration=3000&pause=1000&color=00FFB2&center=true&vCenter=true&width=700&lines=🔬+Hyperspectral+Imaging+Simulation;📡+Point+Scan+·+Line+Scan+·+Wavelength+Scan;🌈+Real+Methods+·+Real+Physics+·+Python;🇨🇴+Built+from+Colombia+with+precision" />
</div>

<!-- STATUS ROW -->
<div align="center">
  <img src="https://img.shields.io/badge/●_STATUS-Active-00FFB2?style=flat-square&labelColor=020B18" />
  &nbsp;
  <img src="https://img.shields.io/badge/🐍-Python_3.10+-00FFB2?style=flat-square&labelColor=020B18" />
  &nbsp;
  <img src="https://img.shields.io/badge/📡-3_Scan_Methods-5AFFD6?style=flat-square&labelColor=020B18" />
  &nbsp;
  <img src="https://img.shields.io/badge/🔬-Spectroscopy_Sim-00FFB2?style=flat-square&labelColor=020B18" />
  &nbsp;
  <img src="https://img.shields.io/badge/📜-MIT_License-5AFFD6?style=flat-square&labelColor=020B18" />
</div>

<br/>

---

<!-- ░░░░░░░░░░░░░░░░░░░░ MAIN TABLE ░░░░░░░░░░░░░░░░░░░░░░░░░░░░ -->
<table width="100%" border="0" cellspacing="0" cellpadding="16">
<tr>

<!-- COLUMNA 1 — ABOUT -->
<td width="33%" valign="top" align="center">

### `◈ About`

<img src="https://img.shields.io/badge/SpectralScanSim-Scientific_Simulation-00FFB2?style=for-the-badge&labelColor=020B18" /><br/><br/>

<img src="https://img.shields.io/badge/📍-Colombia_🇨🇴-5AFFD6?style=for-the-badge&labelColor=020B18" />

<br/><br/>

![Python](https://img.shields.io/badge/Python-020B18?style=flat-square&logo=python&logoColor=3776AB)
![NumPy](https://img.shields.io/badge/NumPy-020B18?style=flat-square&logo=numpy&logoColor=013243)
![Matplotlib](https://img.shields.io/badge/Matplotlib-020B18?style=flat-square&logo=python&logoColor=00FFB2)
![SciPy](https://img.shields.io/badge/SciPy-020B18?style=flat-square&logo=scipy&logoColor=8CAAE6)

<br/>

> *Simulación de tres métodos reales de adquisición espectral usados en óptica, teledetección e imágenes hiperespectrales.*

<br/>

![](https://img.shields.io/badge/🔬-Spectroscopy-00FFB2?style=flat-square&labelColor=020B18)
![](https://img.shields.io/badge/📊-Data_Viz-5AFFD6?style=flat-square&labelColor=020B18)
![](https://img.shields.io/badge/🛰️-Remote_Sensing-00FFB2?style=flat-square&labelColor=020B18)

<br/>

<img src="https://media.giphy.com/media/3oKIPEqDGUULpEU0aQ/giphy.gif" width="200" height="150" />

</td>

<!-- COLUMNA 2 — HYPERCUBE -->
<td width="33%" valign="top" align="center">

### `◈ Hyperspectral Cube`

<br/>

Un **cubo hiperespectral** es una estructura de datos 3D donde cada píxel de una imagen 2D contiene un espectro completo de longitudes de onda.

<br/>

```
Hyperspectral Cube (X, Y, λ)

        λ →→→→→→→→→
   ┌───┬───┬───┬───┐
 Y │   │   │   │   │
 ↓ ├───┼───┼───┼───┤
   │   │ ● │   │   │  ← pixel (x,y)
   ├───┼───┼───┼───┤     contiene espectro
   │   │   │   │   │     completo
   └───┴───┴───┴───┘
```

<br/>

Cada método recorre este cubo de forma distinta, con diferentes implicaciones en **velocidad**, **ruido** y **aplicaciones reales**.

</td>

<!-- COLUMNA 3 — STACK -->
<td width="33%" valign="top" align="center">

### `◈ Stack`

<br/>

<img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/python/python-original.svg" height="45" alt="python" />
&nbsp;
<img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/numpy/numpy-original.svg" height="45" alt="numpy" />
&nbsp;
<img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/matplotlib/matplotlib-original.svg" height="45" alt="matplotlib" />

<br/><br/>

**Librerías principales:**

| Librería | Uso |
|----------|-----|
| `numpy` | Operaciones matriciales |
| `matplotlib` | Visualización espectral |
| `scipy` | Filtros y ruido gaussiano |
| `time` | Medición de tiempos de escaneo |

</td>

</tr>
</table>

---

### `◈ Métodos de Escaneo`

<br/>

<!-- POINT SCAN -->
<table width="100%" border="0" cellspacing="0" cellpadding="20">
<tr>
<td width="8%" align="center" valign="top"><h2>📍</h2></td>
<td valign="top">

### Point Scan

El **Point Scan** es el método más básico y preciso. El sensor se posiciona sobre un único píxel `(x, y)` y adquiere el espectro completo de longitudes de onda `λ` para ese punto. Luego se desplaza al siguiente píxel y repite el proceso hasta cubrir toda la imagen.

**¿Cómo funciona?**

> El detector captura la señal en un único punto espacial, lo que permite un tiempo de integración muy largo por píxel. Esto maximiza la relación señal/ruido (SNR), pero hace que el proceso sea extremadamente lento para imágenes grandes, ya que requiere `X × Y` posicionamientos individuales.

**Características:**

| Parámetro | Valor |
|-----------|-------|
| Unidad de adquisición | 1 píxel `(x, y)` |
| Complejidad temporal | `O(X × Y × λ)` |
| Velocidad | 🐢 Muy lenta |
| Relación señal/ruido | ✅ Excelente |
| Sensibilidad al movimiento | ✅ Nula |
| Hardware típico | Fotodetector puntual, PMT |

**Aplicaciones reales:**
- Microscopía confocal de barrido
- Espectroscopía Raman punto a punto
- Caracterización de materiales en laboratorio de alta precisión

</td>
</tr>
</table>

---

<!-- LINE SCAN -->
<table width="100%" border="0" cellspacing="0" cellpadding="20">
<tr>
<td width="8%" align="center" valign="top"><h2>📏</h2></td>
<td valign="top">

### Line Scan *(Push-Broom)*

El **Line Scan** captura una línea espacial completa (toda la fila `X`) en una sola adquisición, obteniendo simultáneamente la información espectral de todos los píxeles de esa fila. El sensor avanza fila a fila en la dirección `Y`.

**¿Cómo funciona?**

> Una rendija óptica (slit) proyecta la línea sobre un detector 2D: un eje representa la dimensión espacial `X` y el otro el espectro `λ`. Esto reduce el número de pasos de adquisición de `X × Y` a solo `Y`, multiplicando significativamente la velocidad respecto al Point Scan.

**Características:**

| Parámetro | Valor |
|-----------|-------|
| Unidad de adquisición | 1 fila completa `(X, λ)` |
| Complejidad temporal | `O(Y × λ)` |
| Velocidad | ⚡ Media |
| Relación señal/ruido | ✅ Buena |
| Sensibilidad al movimiento | ⚠️ Moderada (entre líneas) |
| Hardware típico | Cámara con rendija + espectrógrafo |

**Aplicaciones reales:**
- Sensores satelitales push-broom (Sentinel-2, Landsat)
- Inspección industrial en líneas de producción
- Agricultura de precisión desde plataformas aéreas

</td>
</tr>
</table>

---

<!-- WAVELENGTH SCAN -->
<table width="100%" border="0" cellspacing="0" cellpadding="20">
<tr>
<td width="8%" align="center" valign="top"><h2>🌈</h2></td>
<td valign="top">

### Wavelength Scan *(Tunable Filter)*

El **Wavelength Scan** adquiere la imagen espacial 2D completa `(X, Y)` para una única longitud de onda `λ` a la vez. Un filtro sintonizable selecciona la banda espectral deseada y la cámara captura toda la escena. Luego se cambia `λ` y se repite el proceso.

**¿Cómo funciona?**

> Un filtro de cristal líquido (LCTF) o Fabry-Pérot sintonizable bloquea todas las longitudes de onda excepto la seleccionada. El detector 2D captura la imagen espacial completa en esa banda espectral. El proceso se repite para cada `λ` del rango de interés, haciendo que solo sean necesarias tantas adquisiciones como longitudes de onda haya.

**Características:**

| Parámetro | Valor |
|-----------|-------|
| Unidad de adquisición | 1 imagen 2D completa `(X, Y)` por `λ` |
| Complejidad temporal | `O(λ)` |
| Velocidad | 🚀 Más rápida |
| Relación señal/ruido | ⚠️ Variable (depende del filtro) |
| Sensibilidad al movimiento | ❌ Alta (entre bandas espectrales) |
| Hardware típico | Cámara 2D + filtro sintonizable (LCTF, FPI) |

**Aplicaciones reales:**
- Imágenes de fluorescencia en biomedicina
- Teledetección con filtros sintonizables en campo
- Control de calidad en industria alimentaria y farmacéutica

</td>
</tr>
</table>

---

### `◈ Comparativa General`

<div align="center">

| Característica | 📍 Point Scan | 📏 Line Scan | 🌈 Wavelength Scan |
|:---|:---:|:---:|:---:|
| **Unidad de lectura** | 1 píxel | 1 fila | 1 imagen completa |
| **Complejidad** | `O(X·Y·λ)` | `O(Y·λ)` | `O(λ)` |
| **Velocidad** | 🐢 Muy lenta | ⚡ Media | 🚀 Rápida |
| **Relación señal/ruido** | ✅ Excelente | ✅ Buena | ⚠️ Variable |
| **Artefactos por movimiento** | ✅ Ninguno | ⚠️ Moderados | ❌ Altos |
| **Complejidad del hardware** | 🟢 Baja | 🟡 Media | 🔴 Alta |
| **Aplicación típica** | Laboratorio | Satélite / industria | Biomédica / campo |

</div>

---

### `◈ ¿Cuándo usar cada método?`

<div align="center">

```
¿La escena está en movimiento?
         │
        YES ──────────────────→ 📍 Point Scan   (mínimo artefacto)
         │
        NO
         │
¿Necesitas máxima velocidad?
         │
        YES ──────────────────→ 🌈 Wavelength Scan
         │
        NO
         │
¿Es una plataforma en movimiento?
         │
        YES ──────────────────→ 📏 Line Scan    (push-broom)
         │
        NO  ──────────────────→ Cualquiera según SNR requerido
```

</div>

---

<!-- ░░░░░░░░░░░░░░░░░░░░░░░ FOOTER ░░░░░░░░░░░░░░░░░░░░░░░░░░░░░ -->

<div align="center">
  <br/>
  <sub><i>"Spectroscopy is seeing light in a language science can read."</i></sub>
  <br/><br/>
  <sub>🔬 <code>Point · Line · Wavelength</code> · SpectralScanSim © 2025 · Colombia 🇨🇴</sub>
  <br/><br/>
  <img src="https://capsule-render.vercel.app/api?type=waving&height=100&color=0:020B18,60:051428,100:020B18&stroke=5AFFD6&strokeWidth=2&section=footer" width="100%"/>
</div>

<!-- ╔══════════════════════════════════════════╗ -->
<!-- ║  EASTER EGG — YOU READ THE SOURCE 🔬    ║ -->
<!-- ║  Each photon tells its own story.        ║ -->
<!-- ║  Keep scanning, keep discovering. 🌈     ║ -->
<!-- ╚══════════════════════════════════════════╝ -->
