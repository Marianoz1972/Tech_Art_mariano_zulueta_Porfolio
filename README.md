


![image alt](https://github.com/Marianoz1972/Tech_Art_mariano_zulueta_Porfolio/blob/b466b7c6acd616cbc2327045522d062c5c35319a/ChatGPT%20Image%2023%20abr%202026%2C%2007_18_49%20p.m..png)

#  Desarrollo de herramientas para Maya

Desarrollaremos un acceso directo en nuestro panel para simplificar porcesos

La intención es acceder de manera sencilla a la visualización de errores en nuestra topología.

---

## 📌 Descripción

Como primera medida, desarrollamos el código en lenguaje MEL.

Este código será robusto y confiable y se transformará en nuestro botón de acceso a las herramientas.
---

## 📷 Capturas

![image alt](https://github.com/Marianoz1972/Tech_Art_mariano_zulueta_Porfolio/blob/0154bb875d2409886d6c1f06945ab7b79dd5d37f/Bio_Mariano_zulueta/inicio.JPG )

Como segunda medida, elegiremos nuestros assets para comprobar su estructura.
Al dar inicio a nuestro código, se desplegará una consola con las opciones.

- Podremos analizar nuestra topología.

- Detectar engons

- Detectar cantidad de engons y triángulos.


![image alt](https://github.com/Marianoz1972/Tech_Art_mariano_zulueta_Porfolio/blob/2f4e4e1ee8ba2b68529d9a9f23fca2fce46d7683/Bio_Mariano_zulueta/mala%20topologia.JPG)

hora que tenemos nuestro asset vamos a generar mala topología para el ejemplo.

![image alt](https://github.com/Marianoz1972/Tech_Art_mariano_zulueta_Porfolio/blob/bd10d927235041469ae16568193631a414b1f1e7/Bio_Mariano_zulueta/detecta%20engons%20y%20trialgulos.JPG)

Al utilizar nuestra herramineta podremo visualizar que los engons se iluminan de color rojo.

El resto de los colores son triangulos.

Tambien tendremos el recuento de los mismos.


![image alt](https://github.com/Marianoz1972/Tech_Art_mariano_zulueta_Porfolio/blob/c16f6cda578f5903557eeed36945f05c5afe06d8/Bio_Mariano_zulueta/final.JPG)

Con estos resultados podremos transformar los engons en triángulos, limpiar topología o generar cuats.


## 🎬 Video Demo



https://github.com/user-attachments/assets/63724867-c765-469e-81cd-db70c0502347




Acá podemos visualizar la demostración.

---




---
![image alt](https://github.com/Marianoz1972/Tech_Art_mariano_zulueta_Porfolio/blob/b466b7c6acd616cbc2327045522d062c5c35319a/ChatGPT%20Image%2023%20abr%202026%2C%2007_18_49%20p.m..png)

#  Desarrollo de herramientas para Maya

🎯 1. OBJETIVO DE LA HERRAMIENTA

Esta herramienta dentro de Autodesk Maya automatiza:

Renombrado masivo de archivos .fbx
Corrección de naming interno de los objetos
Clasificación automática de assets
Estandarización de convenciones de naming

👉 Objetivo principal:
reducir errores humanos y optimizar el pipeline de assets

🧰 2. CONTEXTO DE USO

En producción, es común tener:

![image alt](https://github.com/Marianoz1972/Tech_Art_mariano_zulueta_Porfolio/blob/078209cba3b103761ab682676fb066289602288c/nombre%20inicial.JPG)

👉 Problema:

Naming inconsistente
Difícil de integrar en motores como Unreal o Unity

⚙️ 3. SOLUCIÓN PROPUESTA

Se desarrolla una herramienta en Maya que:

Procesa múltiples FBX desde una carpeta
Analiza cada asset
Aplica reglas de naming automáticamente
Reexporta los archivos corregidos

🖥️ 4. INTERFAZ DE LA HERRAMIENTA

La tool se ejecuta dentro de Maya y presenta:

Selector de carpeta
Opción Dry Run (simulación)
Botón de ejecución

👉 Pensada para artistas (uso simple y directo)

🔄 5. FLUJO DE TRABAJO
🔹 Paso 1 — Selección de carpeta

El usuario elige una carpeta con archivos .fbx

![image alt](https://github.com/Marianoz1972/Tech_Art_mariano_zulueta_Porfolio/blob/4d6cbb46491fa4a26fc22436af399ce78982e03e/elegimos%20carpeta.JPG)

🔹 Paso 2 — Simulación (Dry Run)

La herramienta:

Analiza los archivos
Determina cambios necesarios
No modifica nada

👉 Permite validar antes de ejecutar

🔹 Paso 3 — Procesamiento real

La herramienta:

Abre cada FBX en Maya
Limpia la escena
Detecta tipo de asset
Renombra el objeto principal
Reexporta el archivo


![image alt](https://github.com/Marianoz1972/Tech_Art_mariano_zulueta_Porfolio/blob/49134d2059150a3b468570519aaffe6dc7138333/cambio%20de%20nombre.JPG)

🧠 6. LÓGICA DE CLASIFICACIÓN

La herramienta detecta el tipo automáticamente:

🦴 Si tiene joints → personaje
🧩 Si tiene múltiples meshes → FX
🧱 Caso contrario → entorno

🔤 7. SISTEMA DE NAMING

Se aplican prefijos estándar:

Tipo	Prefijo
Entorno	                 prop_env_
FX	                     sm_fx_
Personaje	               char_npc_

CONCLUSIÓN

La herramienta transforma un proceso manual y propenso a errores
en un sistema automatizado, consistente y escalable dentro de Maya,
alineado con prácticas reales de producción.


![image alt](https://github.com/Marianoz1972/Tech_Art_mariano_zulueta_Porfolio/blob/49134d2059150a3b468570519aaffe6dc7138333/cambio%20de%20nombre.JPG)

🎥 video



https://github.com/user-attachments/assets/6a05380a-71e5-4aa7-a574-ef0e22b87d7d







🚀 BENEFICIOS EN PIPELINE
✔ Consistencia

Naming uniforme en todos los assets

✔ Automatización

Elimina tareas manuales repetitivas

✔ Escalabilidad

Procesa cientos de assets sin intervención

✔ Integración

Compatible con motores como Unreal Engine

![image alt](https://github.com/Marianoz1972/Tech_Art_mariano_zulueta_Porfolio/blob/b466b7c6acd616cbc2327045522d062c5c35319a/ChatGPT%20Image%2023%20abr%202026%2C%2007_18_49%20p.m..png)



💡 Lighting Tool PRO

🎯 ¿Qué hace esta herramienta?

Lighting Tool PRO es una herramienta desarrollada para Autodesk Maya que automatiza la creación de setups de iluminación profesionales con un solo clic.

Permite generar diferentes moods visuales sin necesidad de configurar luces manualmente.

🧠 Objetivo principal

Reducir el tiempo de trabajo en iluminación y garantizar:

Consistencia visual
Rapidez en iteración
Resultados cinematográficos inmediatos

⚙️ ¿Cómo funciona?

La herramienta:

Detecta el objeto seleccionado
Calcula su posición en el espacio
Genera automáticamente un sistema de luces
Orienta las luces hacia el objeto
Ajusta intensidad/exposure según el motor de render

🎛️ Presets incluidos

🌙 Luz de Luna

Tipo: Iluminación nocturna

Características:

Luz direccional azul (luz lunar)
Fill suave para conservar detalle
Sombras frías y profundas

Uso ideal:

Escenarios exteriores
Ambientes fríos / nieve
Narrativa cinematográfica nocturna

⚪ NEUTRO

Tipo: Iluminación dramática

Características:

Luz principal roja profunda
Fill azul frío
Alto contraste

Uso ideal:

Escenas con tensión
Storytelling visual
Composición cinematográfica

🎨 Portfolio Setup

Tipo: Iluminación de estudio

Características:

Sistema de 3 luces (key / fill / rim)
Iluminación balanceada
Sombras suaves

Uso ideal:

Presentación de assets
Portfolio
Render final limpio

Escenario Inicial

![image alt](https://github.com/Marianoz1972/Tech_Art_mariano_zulueta_Porfolio/blob/9420c66e9cc0cde0a2a0e205e7c39e792170f1b4/escena%20inicial.JPG)

Herramienta en PANTALLA








```bash





