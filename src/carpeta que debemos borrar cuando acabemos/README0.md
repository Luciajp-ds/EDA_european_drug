
**1. INTRODUCCIÓN**

El consumo de drogas es un fenómeno global que plantea desafíos de salud pública, con repercusiones económicas y sociales. La expansión del uso de sustancias psicoactivas entre la población juvenil y adulta joven ha generado preocupación debido a su impacto en la salud física y mental (Jongenelis et al., 2019; Martínez, Rodríguez & Vinces, 2019; Arteaga-Lozada & Plaza-Macías, 2021; Kendler et al., 2017). En este sentido, comprender los patrones de consumo entre países, género y grupos de edad es fundamental para desarrollar estrategias efectivas de prevención y tratamiento. Además, identificar los factores que influyen en la iniciación y mantenimiento del consumo permite orientar políticas públicas basadas en evidencia (Jongenelis et al., 2019; Martínez, Rodríguez & Vinces, 2019; Arteaga-Lozada & Plaza-Macías, 2021; Kendler et al., 2017).

Por ello, este EDA se focaliza en estudiar el consumo de estupefacientes en Europa, utilizando un dataset que permite examinar la prevalencia por sustancia, país, edad y género.


---


**2. ANÁLISIS EXPLORATORIO Y TEMA ESCOGIDO: EL CONSUMO DE ESTUPEFACIENTES EN EUROPA**

El consumo de estupefacientes constituye un problema de salud pública relevante a nivel mundial y europeo, con implicaciones sociales, educativas, familiares y laborales. A nivel global, aproximadamente 275 millones de individuos (5.6% de la población) consumieron psicotrópicos al menos una vez en 2016 (Martínez, Rodríguez & Vinces, 2019; Jongenelis et al., 2019). En Europa, los patrones de consumo muestran diferencias según país, género y edad, siendo los jóvenes y adultos jóvenes los grupos con mayor prevalencia, así como los hombres quienes registran consumos más elevados. Este consumo puede progresar de un uso puntual hasta la dependencia, afectando, de esta forma, la salud mental y física, así como el desempeño laboral y las relaciones sociales (Martínez, Rodríguez & Vinces, 2019; Jongenelis et al., 2019).

Por su parte, existen diversos factores que influyen en el consumo de los estupefacientes, tales como el entorno social y familiar, la presión de los pares, las normas culturales y la disponibilidad de las sustancias. Asimismo, los factores socioculturales y psicológicos (como la exclusión social o el abuso) aumentarían la vulnerabilidad de los adolescentes a dicho consumo (Arteaga-Lozada & Plaza-Macías, 2021; Kendler et al., 2017).

Asimismo, el consumo de sustancias conlleva notables riesgos para los individuos. Como ejemplo, los opioides pueden generar depresión respiratoria; el cannabis puede alterar la memoria y percepción, la cocaína produciría ansiedad y riesgos cardiovasculares y el LSD alteraciones de la conciencia (Valverde Farías, Farías Moya & Benítez-Guerra, 2009).

Por lo anteriormente mencionado, el tema escogido para el presente EDA en el marco del Bootcamp de Data Science lo constituye el consumo de estupefacientes en Europa, analizado a partir de un dataset que incluye información sobre la prevalencia de consumo por sustancia (como alcohol o cocaína), estado, edad y género.

Concretamente, se busca caracterizar los patrones de consumo, así como identificar diferencias demográficas y estudiar como el uso de drogas se distribuye en diversos grupos poblacionales:

- Diferencias de consumo por género
- Prevalencia de consumo por país
- Prevalencia y diferencias por edad
- Prevalencia del tipo de sustancia por país


---


**3. JUSTIFICACIÓN**

El estudio del consumo de estupefacientes es relevante debido a que el mismo constituye un problema social y sanitario de creciente relevancia. El estudio del consumo de estupefacientes en Europa es fundamental para poder planificar políticas de prevención y salud pública, así como reducir los riesgos y consecuencias vinculados a su uso. Por ello, es imprescindible comprender las inferencias de consumo por edad, género y país ya que ello permite identificar grupos vulnerables, la prevalencia de los tipos de psicotrópicos y, así, priorizar los recursos (Jongenelis et al., 2019; Parrales-Pincay et al., 2023).

Entender estos patrones es imprescindible para poder orientar políticas sanitarias, así como diseñar estrategias preventivas. Por lo anterior, se justifica la elaboración de un análisis que nos permita estudiar la prevalencia, así como la distribución de su consumo de Europa a partir de diversas fuentes oficiales.


---


**4. OBJETIVOS**

Por todo lo anteriormente mencionao, el objetivo principal de este EDA es analizar los patrones de consumo de estupefacientes en la población europea, identificando tendenciais y diferencias por país, sustancias, edad y género.

Como **objetivos específicos** podemos destacar:

- Comparar la prevalencia de distintos estupefacientes entre los países de la UE
- Analizar diferencias de consumo según género y rango de edad
- Identificar qué sustancias tienen mayor prevalencia y en qué grupos poblacionales


---


**5. HIPÓTESIS**

🔹 H1. Los hombres consumen más estupefacientes que las mujeres en todos los grupos de edad y en todos los paises

📌 Problema que se aborda: diferencia de la prevalencia de consumo por grupo de edad, por género y por tipo de estupefaciente 
- Análisis que hacemos: cantidad qu consumen hombrees y mujeres, cantidad que consumen por grupo de edad, relaciones entre consumo y genero, relacion entre consumo y grupo de edad, analisis de que tipo de droga consumen mas por genero y que tipo de droga consumen mas por edad
Aquí unimos la hipótesis 1 y la hipótesis 2

🔹 H2. Existen diferencias en la prevalencia del consumo de estupefacientes entre países europeos
📌 Problema que se aborda: analizamos qué droga se consume más en cada país
- Análisis que hacemos: la prevalencia del consumo por país y podemos determinar si hay diferencias o no por países respecto el consumo: en qué países se consume más, que tipo de droga consumen más e incluso podemos añadir información para cada pais de genero, edad y tipo de droga (si son muchos países podemos unificarlo tipo: paises mediterraneos, paises nordicos, paises europa central)

Aquí la junto con la hipótesis 3

🔹 H3. La prevalencia del consumo varía de forma notable según el recall period, siendo mayor en medidas de consumo a lo largo de la vida que en periodos recientes.

📌 Problema: interpretación correcta de indicadores.




**Hipótesis anteriores:::** 

*H1. Los hombres consumen más estupefacientes que las mujeres en todos los grupos de edad*

📌 Problema: Analizar si todas las drogas presentan la misma brecha de género y de edad

*H2. Los jóvenes de 15-34 años tienen mayor prevalencia de consumo que los grupos poblacionales mayores* 

📌 Problema: Analizar si todas las drogas presentan la misma brecha de edad

*H3. El alcohol es la sustancia más consumida en todos los países europeos*

📌 Problema: Analizar qué droga tiene un consumo más generalizado en Europa

*H4. Existen diferencias en la prevalencia del consumo de estupefacientes entre países europeos*

📌 Problema que aborda: comparación entre países de los diversos tipos de drogas, como cannabis o cocaina.


---

**6. PREGUNTA DE INVESTIGACIÓN**

*¿Existen patrones de consumo de estupefacientes en Europa, como la prevalencia de determinada sustancias en rangos de edad o género?*

---


## 🛠️ 7. HERRAMIENTAS UTILIZADAS

**Lenguaje y entorno**

- Python 3.10+
- Jupyter Notebook / Visual Studio Code

**Librerías principales para análisis**

- Pandas: limpieza y manipulación de datos
- NumPy

**Visualización**

- Matplotlib + Plotly 
- Seaborn

**Control de versiones**

- Git y GitHub

**Gestión de archivos y datos**

- OpenPyXL (Excel)
- JSON / CSV
  
---

## 📂 8. ESTRUCTURA DEL REPOSITORIO


EDA_Ansioliticos_España/
│

├── README.md → Documentación del proyecto

├── main.ipynb → Notebook final con el EDA limpio y ordenado

├── Memoria.pdf → Informe técnico con el análisis completo

├── Presentacion.pdf → Diapositivas utilizadas en la presentación

├── requirements.txt → Librerías necesarias para la reproducción

└── src/
   ├── data/ → Datos (muestras, CSV, etc.)
   ├── img/ → Gráficos exportados e imágenes
   ├── notebooks/ → Notebooks de desarrollo (borradores)
   └── utils/ → Funciones auxiliares (scripts .py)


---

## 🚀 9. INSTRUCCIONES PARA REPRODUCIR EL ANÁLISIS


```bash
git clone https://github.com/luciajp-ds/EDA_ansioliticos_esp.git
cd eda_european_drug

pip install -r requirements.txt

jupyter notebook main.ipynb
```


## 📊 10. PRINCIPALES CONCLUSIONES


## 👥 7. Autores


## 📎 8. Posibles líneas futuras de trabajo
