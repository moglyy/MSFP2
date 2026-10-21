[![Open in MATLAB Online](https://www.mathworks.com/images/responsive/global/open-in-matlab-online.svg)](https://matlab.mathworks.com/open/github/v1?repo=moglyy/MSFP2)
# Práctica 2:  Modelado y control del sistema cardiovascular mediante el modelo de Windkessel

## Información de la estudiante

Kiara Vianney Trinidad Diaz\[23212240]; L23212240@tijuana.tecnm.mx

Modelado de Sistemas Fisiológicos

Ingeniería Biomédica

## Docente

Dr. Paul Antonio Valle Trujillo; paul.valle@tectijuana.edu.mx

Departamento de Ingeniería Eléctrica y Electrónica, Tecnológico Nacional de México/IT Tijuana, Blvd. Alberto Limón Padilla s/n, Tijuana, C.P. 22454, B.C., México.

## Descripción de la asignatura

El modelizado de sistemas fisiológicos es una herramienta importante en Ingeniería Biomédica, permite comprender el funcionamiento del cuerpo humano, así como diseñar y evaluar terapias y dispositivos médicos; se define como el proceso de formular modelos matemáticos o computacionales que representan el comportamiento y la interacción de los sistemas biológicos y fisiológicos. Esta asignatura pretende aportar al perfil del Ingeniero Biomédico la capacidad de realizar investigación científica en el área de Biología de Sistemas con la finalidad de dirigir y participar en equipos de trabajo interdisciplinarios en contextos nacionales e internacionales, así como de proporcionar soluciones informáticas para resolver problemas en el campo de la Ingeniería Biomédica con ética profesional; lo anterior al proporcionar al estudiante bases sólidas para modelizar sistemas y diseñar controladores para la solución de problemas en las áreas de atención médica y del sector industrial médico. La construcción de analogías entre circuitos eléctricos y sistemas fisiológicos para la formulación de modelos matemáticos y el diseño de controladores mediante la experimentación in silico brindan herramientas de gran aplicación en el quehacer profesional del Ingeniero Biomédico.

La asignatura de Modelado de Sistemas Fisiológicos forma parte del plan de estudios de la carrera en Ingeniería Biomédica con la siguiente competencia general del curso: Utiliza las propiedades de los circuitos RLC para describir la dinámica de sistemas fisiológicos, obtener modelos matemáticos y aplicar el control clásico, esto con el objetivo de integrar los principios de la Ingeniería de Control, la Electrónica Analógica y las Ciencias de la Computación con la Anatomía y Fisiología del cuerpo humano para proporcionar descripciones cuantitativas y cualitativas de sistemas fisiológicos complejos con el objetivo de modelizar, analizar, controlar, ilustrar y predecir su dinámica tanto en el corto como en el largo plazo.

## Objetivos

1. Identificar las variables hemodinámicas y relacionar los elementos del circuito Windkessel de cuatro elementos con sus propiedades fisiológicas correspondientes.
2. Formular el modelo dinámico en espacio de estados y obtener el modelo de ecuaciones integro-diferenciales.
3. Obtener la función de transferencia para las condiciones normotensa, hipotensa e hipertensa.
4. Analizar la estabilidad del sistema mediante la localización de sus polos en el plano complejo y calcular el error en estado estacionario.
5. Generar una señal de excitación aleatoria uniforme e imitar la respuesta dinámica cardiovascular en lazo abierto.
6. Sintonizar las ganancias de un controlador PID mediante la herramienta Tune de Simulink para los casos hipotenso e hipertenso, tomando como referencia la respuesta normotensa.
7. Simular la respuesta en lazo cerrado en MATLAB/Simulink para verificar la reducción del error de seguimiento respecto al individuo sano de referencia.
8. Implementar el modelo de funciones de transferencia y sistemas en lazo cerrado en Python mediante Visual Studio Code, realizando una verificación cruzada de los resultados entre plataformas.


Palabras clave: Modelo Windkessel; Sistema cardiovascular; Controlador PID; Espacio de estados; Simulaciones numéricas.

## Lista de archivos incluidos en el repositorio

1. Cuaderno computacional de MATLAB \[.mlx].
2. Modelo de Simulink \[.slx].
3. Archivos de Visual Studio Code \[.py].
4. Imagen con los parámetros del controlador.
5. Imágenes de las simulaciones \[.pdf y .png].
6. Análisis matemático: Función de transferencia, modelo de ecuaciones integro-diferenciales, estabilidad y error en estado estacionario.
7. Diagrama Biologico de BioRender\ [png].
## Referencias

\[1] P. A. Valle, Syllabus para Modelado de Sistemas Fisiológicos, Tecnológico Nacional de México / Instituto Tecnológico de Tijuana, Tijuana, B.C., México, 2025. Permalink: https://biomath.xyz/course/

\[2] M. C. Khoo, Physiological Control Systems Analysis Simulation, and Estimation, 2nd ed. Piscataway, New Jersey, USA: IEEE Press, 2018, Section 4, Page 93.

\[3] N. S. Nise, Control Systems Engineering, 8th ed. Hoboken, New Jersey, USA: John Wiley \& Sons, 2020.
