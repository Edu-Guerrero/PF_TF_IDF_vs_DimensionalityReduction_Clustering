# PF_TF_IDF_vs_DimensionalityReduction_Clustering
Final Project Comparing the simple use of term frequency inverse document frequency vs Reducing dimensionality and clustering

# Analisis del Dataset #
El dataset se trata de 186 documentos que contienen la descripción de distintas asignaturas ofrecidas por la Universidad San Franciso de Quito.

Contiene las siguientes asignaturas:

* 100_Principios_de_Seguros.txt
* 101_Analisis_de_Datos.txt
* 102_Principios_de_Finanzas.txt
* 103_Coloquios_adm.txt
* 104_Finanzas_Corporativas.txt
* 105_Marketing_Digital.txt
* 106_Negociacion.txt
* 107_Operaciones_+Lab.txt
* 108_Economia_y_Negocios.txt
* 109_Investigacion_de_Mercados.txt
* 10_Autoconocimiento.txt
* 110_Creatividad_Empresarial.txt
* 111_Proyectos_Empresariales.txt
* 112_Gestion_del_Talento.txt
* 113_Negocios_Internacionales.txt
* 114_Innovacion_y_Sustentabilidad.txt
* 115_Tributacion_y_Entorno_Legal.txt
* 116_Analisis_Estrategico_ADM.txt
* 117_Herramientas_Digitales_1.txt
* 118_Fundamentos_de_las_Artes.txt
* 119_Composicion_Visual_1.txt
* 11_Ser_y_Cosmos.txt
* 120_Laboratorio_de_Creacion_1.txt
* 121_Dibujo_para_Arte_y_Diseno.txt
* 122_Fotografia_1.txt
* 123_Fundamentos_de_Escultura.txt
* 124_Teoria_Critica_1__Arte_&_Media.txt
* 125_Nuevos_Medios.txt
* 126_Arte_Contemporaneo.txt
* 127_Laboratorio_de_Creacion_2.txt
* 128_Taller_de_Arte_1.txt
* 129_Coloquios_ART.txt
* 12_Ingles_Nivel_3.txt
* 130_Arte_y_Contexto_Social.txt
* 131_Taller_de_Investigacion.txt
* 132_Enfasis_1.txt
* 133_Taller_de_Arte_2.txt
* 134_Enfasis_2.txt
* 135_Gestion_y_Produccion_Cultural.txt
* 136_Laboratorio_de_Creacion_3.txt
* 137_Matematicas_Cotidianas.txt
* 138_Enfasis_3.txt
* 139_Taller_de_Arte_3.txt
* 13_Ingles_Nivel_4.txt
* 140_Arte_y_Educacion___Curaduria.txt
* 141_Temas_en_Comunicacion_y_Arte.txt
* 142_Produccion_&_Exhibicion.txt
* 143_Programacion_Para_Dise�o_1.txt
* 144_Programacion_Para_Dise�o_2.txt
* 145_Programacion_Para_Dise�o_3.txt
* 146_Juegos_y_Narrativa.txt
* 147_Modelado_3D_1.txt
* 148_Calculo_para_Ciencias_1.txt
* 149_Teoria_de_Grupos.txt
* 14_Programacion_Avanzada_en_C++.txt
* 150_Variable_Compleja.txt
* 151_Ecuaciones_Diferenciales.txt
* 152_Calculo_para_Ciencias_2.txt
* 153_Introduccion_a_Probabilidades.txt
* 154_Fundamentos_de_Geometria.txt
* 155_Logica_y_Teoria_de_Conjuntos.txt
* 156_Inferencia_Estadistica.txt
* 157_Analisis_Numerico.txt
* 158_Teoria_de_Numeros.txt
* 159_Combinatoria_y_Grafos.txt
* 15_Matematicas_Discretas.txt
* 160_Ecuaciones_Diferenciales_Parciales.txt
* 161_Algebra_Lineal_2.txt
* 162_Algebra_Abstracta_1.txt
* 163_Geometria_Diferencial.txt
* 164_Analisis_Funcional.txt
* 165_Algebra_Abstracta_2.txt
* 166_Topologia_1.txt
* 167_Topologia_2.txt
* 168_Analisis_Real.txt
* 169_Improvisacion.txt
* 16_Introduccion_a_la_Economia.txt
* 170_Danza_Moderna_2.txt
* 171_Barra_para_danza_contemporanea.txt
* 172_Composicion.txt
* 173_Performance.txt
* 174_Proyecto_final_en_Danza.txt
* 175_Lenguaje_del_Cine.txt
* 176_Lenguaje_Visual_y_Montaje.txt
* 177_Cinematografia.txt
* 178_Sonido.txt
* 179_Storytelling.txt
* 17_Fisica_para_Ingenieria_1_+Lab_Ej.txt
* 180_Dise�o_de_Produccion.txt
* 181_Inv._de_Operaciones_1_+Lab.txt
* 182_Control_de_Produccion.txt
* 183_Procesos,_Metodos_y_Estandares.txt
* 184_Ergonomia.txt
* 185_Ingenieria_de_la_Calidad_+_Lab.txt
* 186_Sistemas_Lean.txt
* 18_Calculo_Vectorial.txt
* 19_Ingles_Nivel_5.txt
* 1_Escritura_Academica.txt
* 20_Ingles_Nivel_6.txt
* 21_Programacion_de_Apps.txt
* 22_Algebra_Lineal_1_+Ej.txt
* 23_Fisica_para_Ingenieria_2_+Lab_Ej.txt
* 24_Aprendizaje_y_Servicio_PASEC.txt
* 25_Cultura_Gastronomica.txt
* 26_Electronica_Basica_+Lab.txt
* 27_Estructuras_de_Datos.txt
* 28_Probabilidad_y_Estadistica_+Ej.txt
* 29_Teoria_de_la_Computacion.txt
* 2_Taller_de_Ing._Cs._Computacion.txt
* 30_Programacion_Avanzada_de_Apps.txt
* 31_Organizacion_de_Computadores.txt
* 32_Emprendimiento.txt
* 33_Dise�o_de_Sistemas.txt
* 34_Inteligencia_Artificial.txt
* 35_Base_de_Datos.txt
* 36_Aprendizaje_Automatico.txt
* 37_Redes_+Lab.txt
* 38_Sistemas_Operativos.txt
* 39_Proyectos__Gerencia_y_Analisis.txt
* 3_Calculo_Diferencial_+_Ej.txt
* 40_Practica_Pre-Profesional_PASEM.txt
* 41_Coloquios_ING.txt
* 42_Seguridad_Informatica.txt
* 43_Mineria_de_Datos.txt
* 44_Aplicaciones_Distribuidas.txt
* 45_Proyecto_Integrador_CMP.txt
* 46_Matematica_Empresarial_+Ej.txt
* 47_Conceptos_y_Tecnicas_1.txt
* 48_Principios_de_Administracion.txt
* 49_Panaderia.txt
* 4_Quimica_General_1_+Lab_Ej.txt
* 50_Nutricion_Humana_+Lab.txt
* 51_Introduccion_a_la_Hospitalidad.txt
* 52_Contabilidad_Empresarial.txt
* 53_Conceptos_y_Tecnicas_2_+PRA.txt
* 54_Practica_Culinaria_1.txt
* 55_Administracion_de_A_&_B.txt
* 56_Carniceria.txt
* 57_Alta_Cocina_Ecuatoriana.txt
* 58_Introduccion_a_la_Biologia_+Ej.txt
* 59_Introduccion_al_Marketing_HSP.txt
* 5_Cosmos.txt
* 60_Coloquios_Gastr.txt
* 61_Alta_Cocina_Francesa.txt
* 62_Pasteleria.txt
* 63_Servicio_y_Protocolo.txt
* 64_Practica_Culinaria_2.txt
* 65_Alta_Cocina_Mundial.txt
* 66_Reposteria_y_Chocolateria.txt
* 67_Innovacion_Culinaria.txt
* 68_Enologia_y_Cocteleria.txt
* 69_Administracion_de_Eventos.txt
* 6_Ingles_Nivel_1.txt
* 70_Gerencia_Financiera_HSP.txt
* 71_Identidad_Culinaria.txt
* 72_Fundamentos_de_la_Educacion.txt
* 73_Teorias_del_Aprendizaje.txt
* 74_Desarrollo__Ni�o_y_Adolescente.txt
* 75_Planificacion_y_Evaluacion_1.txt
* 76_Estadistica_para_CCSS.txt
* 77_Neurociencia_y_Educacion.txt
* 78_Planificacion_y_Evaluacion_2.txt
* 79_Coloquios_EDU.txt
* 7_Ingles_Nivel_2.txt
* 80_Ensenanza_de_Lenguaje.txt
* 81_Practica_1.txt
* 82_Metodologias_de_Ensenanza.txt
* 83_Ensenanza_de_Matematicas.txt
* 84_Ensenanza_de_Ciencias_Sociales.txt
* 85_Arte_y_Educacion.txt
* 86_Bilingualism.txt
* 87_Practica_2.txt
* 88_Ensenanza_de_Ciencias.txt
* 89_Ensenanza_Integrada_de_CITIAM.txt
* 8_Programacion_en_C++_+Ej.txt
* 90_Practica_3.txt
* 91_Inclusion_y_Diversidad.txt
* 92_Proyecto_Integrador_EDU.txt
* 93_Practica_4.txt
* 94_Zoologia_+Lab.txt
* 95_Fisiologia_+Lab.txt
* 96_Evolucion.txt
* 97_Principios_de_Marketing.txt
* 98_Estadistica_Empresarial_+Lab.txt
* 99_Gerencia_de_Costos.txt
* 9_Calculo_Integral_+_Ej.txt

# Creación de los vectores #
Se crearon dos formas de vectores, un tf_idf normal y un tf_idf con tf logarítmico.

## Fórmulas de TF y TF Logarítmico

La frecuencia de término (TF) se calcula de la siguiente manera:

$$ \text{TF}(t, d) = \frac{f_{t,d}}{n_d} $$

donde:
- $f_{t,d}$ es la frecuencia del término 4t$ en el documento $d$.
- $n_d$ es el número total de términos en el documento $d$.

La frecuencia de término logarítmica (Log-TF) se calcula de la siguiente manera:

$$\text{Log-TF}(t, d) = 1 + \log(f_{t,d})$$

donde:
- $f_{t,d}$ es la frecuencia del término $t$ en el documento $d$.
- Si $f_{t,d} = 0$, entonces $\log(f_{t,d})$ se define como 0.

# Queries usados para pruebas 

Se usaron cinco queries

* Curso de programación, diseño gráfico y cocina internacional con técnicas avanzadas de cocina y recetas modernas
* Curso de escritura creativa y técnica para estudiantes de música interesados en mejorar sus habilidades de composición
* Curso de idiomas inicial para estudiantes que quieren aprender inglés de manera interactiva y efectiva con enfoque en conversación
* Curso sobre inteligencia artificial, tecnología de vanguardia, innovación disruptiva y desarrollo de aplicaciones inteligentes en el mercado
* Curso para estudios de matemáticas aplicadas y artes liberales, combinando teoría matemática avanzada con análisis crítico cultural

# Similitud de los documentos con distintas métrica #

Se utilizó la similitud del coseno y la distancia manhattan para ver la similitud de los documentos.

## Similitud del Coseno

La similitud del coseno mide la similitud entre dos vectores calculando el coseno del ángulo entre ellos. Es una medida que varía entre -1 y 1, donde 1 indica que los vectores son idénticos, 0 indica que son ortogonales y -1 indica que son opuestos.

La fórmula para la similitud del coseno es:

$$ \text{Similitud del Coseno} = \cos(\theta) = \frac{\vec{A} \cdot \vec{B}}{\|\vec{A}\| \|\vec{B}\|} $$

donde:
- $\vec{A} \cdot \vec{B}$ es el producto punto de los vectores $\vec{A}$ y $\vec{B}$.
- $\|\vec{A}\|$ y $\|\vec{B}\|$ son las magnitudes de los vectores $\vec{A}$ y $\vec{B}$, respectivamente.

## Distancia Manhattan

La distancia Manhattan, también conocida como distancia L1 o distancia de la ciudad, mide la distancia entre dos puntos sumando las diferencias absolutas de sus coordenadas. Es una medida que varía entre 0 y el infinito, donde 0 indica que los puntos son idénticos.

La fórmula para la distancia Manhattan es:

$$ \text{Distancia Manhattan} = \sum_{i=1}^{n} |A_i - B_i| $$

donde:
- $A_i$ y $B_i$ son las coordenadas de los puntos $A$ y $B$ en la dimensión $i$.
- $n$ es el número de dimensiones.

## tf_idf

![](Images/tf_idf_cosine.png)


![](Images/tf_idf_manhattan.png)

## tf_idf_log

![](Images/tf_idf_2_cosine.png)

![](Images/tf_idf_2_manhattan.png)

# Reduccion de dimensionalidad

Originalmente, para ambos tipos de df, se tiene 1156 dimensiones.

## Para tf_idf

### Isomap

![](Images/isomap_tf_idf.png)

### Autoencoders

![](Images/auto_sparse_tf_idf.png)

![](Images/auto_deno_tf_idf.png)

### Umap

![](Images/umap_tf_idf.png)

### Mejor resultado

**Para isomap:**

20 componentes

40 vecinos

**Para autoencoder:**

Tipo: Sparse

60 dimensiones

1e-05 sparsity

**Para Umap**

2 componentes

20 vecinos

0.7 distancia minima

metrica coseno

## Para tf_idf_log

### Isomap

![](Images/isomap_tf_idf_2.png)

### Autoencoders

![](Images/auto_sparse_tf_idf_2.png)

![](Images/auto_deno_tf_idf_2.png)

### Umap

![](Images/umap_tf_idf_2.png)

### Mejor resultado

**Para isomap:**

30 componentes

60 vecinos

**Para autoencoder:**

Tipo: Sparse

60 dimensiones

1e-05 sparsity

**Para Umap**

2 componentes

20 vecinos

0.7 distancia minima

metrica coseno

# Clustering #

## Para tf_idf

### Mejor Isomap

#### Kmeans

![](Images/isomap_kmeans_1_1.png)

![](Images/isomap_kmeans_2_1.png)

![](Images/isomap_kmeans_3_1.png)

#### GMM

![](Images/isomap_gmm_1.png)

![](Images/isomap_gmm_2_1.png)

### Mejor autoencoder

#### Kmeans

![](Images/auto_kmeans_1_1.png)

![](Images/auto_kmeans_2_1.png)

![](Images/auto_kmeans_3_1.png)

#### GMM

![](Images/auto_gmm_1_1.png)

![](Images/auto_gmm_2_1.png)

### Mejor Umap

#### Kmeans

![](Images/umao_kmeans_1_1.png)

![](Images/umap_kmeans_2_1.png)

![](Images/umap_kmeans_3_1.png)

#### GMM

![](Images/umap_gmm_1_1.png)

![](Images/umap_gmm_2_1.png)

## Para tf_idf_2

### Mejor Isomap

#### Kmeans

![](Images/isomap_kmeans_1_2.png)

![](Images/isomap_kmeans_2_2.png)

![](Images/isomap_kmeans_3_2.png)

#### GMM

![](Images/isomap_gmm_1_2.png)

![](Images/isomap_gmm_2_2.png)

### Mejor autoencoder

#### Kmeans

![](Images/auto_kmeans_1_2.png)

![](Images/auto_kmeans_2_2.png)

![](Images/auto_kmeans_3_2.png)

#### GMM

![](Images/auto_gmm_1_2.png)

![](Images/auto_gmm_2_2.png)

### Mejor Umap

#### Kmeans

![](Images/umao_kmeans_1_2.png)

![](Images/umap_kmeans_2_2.png)

![](Images/umap_kmeans_3_2.png)

#### GMM

![](Images/umap_gmm_1_2.png)

![](Images/umap_gmm_2_2.png)

## Mejor Clustering

### Para Umap

Kmeans con 6 clusters

Kmeans con 3 clusters

### Para Isomap

Kmeans con 22 clusters

Kmeans con 22 clusters



# Resultados de los queries

## tf_idf

### Cosine

#### Curso de programación, diseño gráfico y cocina internacional con técnicas avanzadas de cocina y recetas modernas

|          | Isomap          |       | Umap            |       | Normal          |       |
|----------|-----------------|-------|-----------------|-------|-----------------|-------|
|          | Document Name   | Score | Document Name   | Score | Document Name   | Score |
|  1       | Practica PreProfesional PASEM        | 0.73  | Alta Cocina Francesa        | 0.99  | Programacion para diseño 3        | 0.30  |
|  2       | Paseteleria        | 0.72  | Alta cocina Ecuatoriana        | 0.99  | Conceptos y Tecnicas 2        | 0.29  |
|  3       | Tributacion y Entorno Legal        | 0.70  | Practica Culinaria        | 0.99  | Alta Cocina Francesa        | 0.27  |
|  4       | Reposteria y Chocolateria        | 0.61  | Conceptos y Técnicas        | 0.99  | Alta Cocina Mundial        | 0.26  |
|  5       | Enologia y Cocteleria        | 0.99  | Identidad Culinaria        | 0.99  | Programación para Diseño 2        | 00.24  |

#### Curso de escritura creativa y técnica para estudiantes de música interesados en mejorar sus habilidades de composición

|          | Isomap          |       | Umap            |       | Normal          |       |
|----------|-----------------|-------|-----------------|-------|-----------------|-------|
|          | Document Name   | Score | Document Name   | Score | Document Name   | Score |
|  1       | Lenguaje Visual y Montaje        | 0.96  | Lenguaje del Cine        | 0.99  | Composicion        | 0.24  |
|  2       | Enologia y Cocteleria        | 0.89  | Composicion Visual        | 0.99  | Cinematografia        | 0.17  |
|  3       | Introduccion a la Economia        | 0.59  | Storytelling        | 0.99  | Ingles Nivel 3        | 0.15  |
|  4       | Fisica para Ingeniera        | 0.50  | Cinematografia        | 0.99  | Creatividad Empresaria        | 0.14  |
|  5       | Gerencia Financiera        | 0.50  | Juegos y Narrativas        | 0.99  | Composicion Visual        | 0.13  |

#### Curso de idiomas inicial para estudiantes que quieren aprender inglés de manera interactiva y efectiva con enfoque en conversación

|          | Isomap          |       | Umap            |       | Normal          |       |
|----------|-----------------|-------|-----------------|-------|-----------------|-------|
|          | Document Name   | Score | Document Name   | Score | Document Name   | Score |
|  1       | Lenguaje Visual y Montaje        | 0.96  | Storytelling        | 1.00  | Ingles Nivel 5        | 0.22  |
|  2       | Enologia y Cocteleria        | 0.89  | Composicion Visual        | 0.99  | Planificacion y Evaluacion        | 0.18  |
|  3       | Introduccion a la Economia        | 0.60  | Cinematografia        | 0.99  | Practica 4        | 0.13  |
|  4       | Gerencia Financiera        | 0.51  | Juegos y Narrativa        | 0.99  | Bilingualism        | 0.13  |
|  5       | Fisica para Ingeniera        | 0.49  | Lenguaje del Cine        | 0.99  | Ingles Nivel 7        | 0.90  |

#### Curso sobre inteligencia artificial, tecnología de vanguardia, innovación disruptiva y desarrollo de aplicaciones inteligentes en el mercado

|          | Isomap          |       | Umap            |       | Normal          |       |
|----------|-----------------|-------|-----------------|-------|-----------------|-------|
|          | Document Name   | Score | Document Name   | Score | Document Name   | Score |
|  1       | Tributaciones y Entorno Legal        | 0.72  | Sistemas Operativos        | 0.99  | Inteligencia Artificial        | 0.20  |
|  2       | Redes        | 0.62  | Estructura de Datos        | 0.99  | Emprendimiento        | 0.18  |
|  3       | Base de Datos        | 0.54  | Redes        | 0.99  | Enseñanza Integrada de Citiam        | 0.17  |
|  4       | Organizacion Computadores        | 0.46  | Procesos Metodos y Estandares        | 0.99  | Nuevos Medios        | 0.13  |
|  5       | Fisica para Ingenierias        | 0.46  | Proyectos Gerencia y Analisis        | 0.99  | Creatividad Empresarial        | 0.11  |

#### Curso para estudios de matemáticas aplicadas y artes liberales, combinando teoría matemática avanzada con análisis crítico cultural

|          | Isomap          |       | Umap            |       | Normal          |       |
|----------|-----------------|-------|-----------------|-------|-----------------|-------|
|          | Document Name   | Score | Document Name   | Score | Document Name   | Score |
|  1       | Lenguaje Visual y Montaje        | 0.96  | Electronica Basica        | 0.99  | Arte y Educacion        | 0.24  |
|  2       | Enologia y Cocteleria        | 0.90  | Matematica Discreta        | 0.99  | Matematicas cotidianas        | 0.24  |
|  3       | Introduccion a la Economia        | 0.99  | Matematicas Cotidianas        | 0.95  | Logica y Teoria de Conjuntos        | 0.20  |
|  4       | Gerencia Financiera        | 0.52  | Fisica para Ingeniera 2        | 0.99  | Gestion y Produccion Cultural        | 0.18  |
|  5       | Fisica para Ingeniera        | 0.49  | Fisica para Ingeniera 1        | 0.99  | Enseñanza de Matematicas        | 0.18  |

### Manhattan

#### Curso de programación, diseño gráfico y cocina internacional con técnicas avanzadas de cocina y recetas modernas

|          | Isomap          |       | Umap            |       | Normal          |       |
|----------|-----------------|-------|-----------------|-------|-----------------|-------|
|          | Document Name   | Distancia | Document Name   | Score | Document Name   | Score |
|  1       | Proyecto Integrador CMP        | 28.61  | Alta Cocina Ecuatoriana        | 0.88  | Dibujo para Arte y Diseño        | 5.32  |
|  2       | Taller de Arte 2        | 29.05  | Practica culinaria        | 1.05  | Taller de Arte 3        | 5.54  |
|  3       | Taller de Arte 3        | 30.25  | Alta Cocina Francesa        | 1.07  | Herramientas Digitales 1        | 5.73  |
|  4       | Proyectos Empresariales        | 30.51  | Alta Cocina Mundial        | 1.33  | Programacion para Diseño 3        | 5.74  |
|  5       | Taller de Investigacion        | 30.52  | Practica Culinaria        | 1.42  | Laboratorio de Creacion        | 5.77  |

#### Curso de escritura creativa y técnica para estudiantes de música interesados en mejorar sus habilidades de composición

|          | Isomap          |       | Umap            |       | Normal          |       |
|----------|-----------------|-------|-----------------|-------|-----------------|-------|
|          | Document Name   | Score | Document Name   | Score | Document Name   | Score |
|  1       | Proyecto Integrador        | 27.67  | Nuevos Medios        | 0.96  | Composicion Visual        | 4.86  |
|  2       | Taller de Investigacion        | 27.94  | Composicion Visual        | 0.97  | Composicion        | 5.47  |
|  3       | Taller de Arte 3        | 28.10  | Ingles Nivel 1        | 1.23  | Enfasis 3        | 5.56  |
|  4       | Taller de Arte 2        | 28.45  | Composicion        | 1.30  | Fotografia 1        | 5.57  |
|  5       | Control de Produccion       | 28.69  | Cinematografia        | 1.39  | Enfasis 1        | 5.61  |

#### Curso de idiomas inicial para estudiantes que quieren aprender inglés de manera interactiva y efectiva con enfoque en conversación

|          | Isomap          |       | Umap            |       | Normal          |       |
|----------|-----------------|-------|-----------------|-------|-----------------|-------|
|          | Document Name   | Score | Document Name   | Score | Document Name   | Score |
|  1       | Proyecto Integrador        | 27.63  | Ingles Nivel 1        | 1.31  | Economia y Negocios        | 5.32  |
|  2       | Taller de Investigacion        | 27.86  | Nuevos Medios        | 1.93  | Composicion Visual        | 5.52  |
|  3       | Taller de Arte 3        | 27.91  | Composicion        | 1.98  | Analisis Estrategico        | 5.60  |
|  4       | Taller de Arte 2        | 28.22  | Improvisacion        | 2.19  | Enfasis 3        | 5.71  |
|  5       | Ingeniera de la Calidad       | 28.44  | Composicion Visual        | 2.22  | Enfasis 1        | 5.74  |

#### Curso sobre inteligencia artificial, tecnología de vanguardia, innovación disruptiva y desarrollo de aplicaciones inteligentes en el mercado

|          | Isomap          |       | Umap            |       | Normal          |       |
|----------|-----------------|-------|-----------------|-------|-----------------|-------|
|          | Document Name   | Score | Document Name   | Score | Document Name   | Score |
|  1       | Taller de Investigación        | 33.91  | Sistemas Lean        | 0.87  | Economia y Negocios        | 0.80  |
|  2       | Programacion Avanzada en C++        | 34.09  | Operaciones + Lab        | 1.36  | Nuevos Medios        | 0.75  |
|  3       | Taller de Arte 2        | 34.96  | Analisis de Datos        | 1.48  | Innovacion y sustentabilidad        | 0.90  |
|  4       | Ingeniera de la Calidad        | 35.09  | Mineria de Datos        | 1.49  | Composicion Visual        | 0.75  |
|  5       | Principios de Finanzas        | 35.22  | Inv. de Operaciones        | 1.56  | Fundamentos de las artes        | 5.70  |

#### Curso para estudios de matemáticas aplicadas y artes liberales, combinando teoría matemática avanzada con análisis crítico cultural

|          | Isomap          |       | Umap            |       | Normal          |       |
|----------|-----------------|-------|-----------------|-------|-----------------|-------|
|          | Document Name   | Score | Document Name   | Score | Document Name   | Score |
|  1       | Proyecto Integrador CMP       | 27.57  | Matematicas Discretas        | 0.63  |  Matemáticas Cotidianas        | 5.24  |
|  2       | Taller de Investigación        | 28.00  | Logica y Teoria de Conjuntos        | 0.81  | Gestion y Produccion Cultural        | 5.82  |
|  3       | Taller de Arte 3        | 28.05  | Variable Compleja        | 1.20  | Arte y contexto Social        | 5.93  |
|  4       | Ingeniera de la Calidad        | 28.31  | Ecuaciones Diferenciales        | 1.40  | Logica y Teoria de Conjuntos        | 5.93  |
|  5       | Taller de Arte 2        | 28.36  | Teoria de Grupos        | 1.62  | Teoria Critica 1 Arte        | 6.07  |

## tf_idf_2

### Cosine

#### Curso de programación, diseño gráfico y cocina internacional con técnicas avanzadas de cocina y recetas modernas

|          | Isomap          |       | Umap            |       | Normal          |       |
|----------|-----------------|-------|-----------------|-------|-----------------|-------|
|          | Document Name   | Score | Document Name   | Score | Document Name   | Score |
|  1       | Base de Datos        | 0.89  | Alta Cocina Ecuatoriana        | 0.99  | Programacion para diseño 3        | 0.25  |
|  2       | Performance        | 0.46  | Reposteria y Chocolateria        | 0.99  | Conceptos y Tecnicas 2        | 0.24  |
|  3       | Modelado 3D        | 0.46  | Neurociencia y Educacion        | 0.99  | Alta Cocina Francesa        | 0.23  |
|  4       | Geometria Diferencial        | 0.43  | Alta Cocina Francesa        | 0.99  | Practica Culinaria        | 0.22  |
|  5       | Marketing Digital        | 0.41  | Identidad Culinaria        | 0.99  | Alta Cocina Mundial       | 0.22  |

#### Curso de escritura creativa y técnica para estudiantes de música interesados en mejorar sus habilidades de composición

|          | Isomap          |       | Umap            |       | Normal          |       |
|----------|-----------------|-------|-----------------|-------|-----------------|-------|
|          | Document Name   | Score | Document Name   | Score | Document Name   | Score |
|  1       | Base de Datos        | 0.89  | Taller de Arte        | 0.99  | Composicion        | 0.20  |
|  2       | Performance        | 0.47  | Teoria de la Computacion        | 0.99  | Cinematografia        | 0.15  |
|  3       | Modelado 3D       | 0.46  | Taller de Investigacion        | 0.99  | Ingles Nivel 3        | 0.13  |
|  4       | Geometria Diferencial        | 0.43  | Laboratorio de Creacion        | 0.99  | Composición Visual        | 0.12  |
|  5       | Marketing Digital        | 0.42  | Taller de Arte 3        | 0.99  | Barra para Danza Contemporanea        | 0.12  |

#### Curso de idiomas inicial para estudiantes que quieren aprender inglés de manera interactiva y efectiva con enfoque en conversación

|          | Isomap          |       | Umap            |       | Normal          |       |
|----------|-----------------|-------|-----------------|-------|-----------------|-------|
|          | Document Name   | Score | Document Name   | Score | Document Name   | Score |
|  1       | Base de Datos        | 0.90  | Coloquios EDU        | 0.99  | Ingles Nivel 5        | 0.19  |
|  2       | Performance        | 0.47  | Planificacion y Evaluacion        | 0.99  | Planificacion y Evaluacion        | 0.14  |
|  3       | Modelado 3D       | 0.44  | Enseñanza de Citiam        | 0.99  | Ingles Bilingualism        | 0.12  |
|  4       | Marketing Digital        | 0.42  | Enseñanza Lenguaje        | 0.99  | Enseñana de Matematicas        | 0.12  |
|  5       | Geometria Diferencial        | 0.42  | Bilingualism        | 0.99  | Juegos y Narrativa        | 0.11  |

#### Curso sobre inteligencia artificial, tecnología de vanguardia, innovación disruptiva y desarrollo de aplicaciones inteligentes en el mercado

|          | Isomap          |       | Umap            |       | Normal          |       |
|----------|-----------------|-------|-----------------|-------|-----------------|-------|
|          | Document Name   | Score | Document Name   | Score | Document Name   | Score |
|  1       | Base de Datos        | 0.87  | Juegos y Narrativa        | 1.00 | Inteligencia Artificial        | 0.19  |
|  2       | PModelado 3D        | 0.45  | Modelado 3D        | 1.00  | Emprendimiento        | 0.18  |
|  3       | Performance       | 0.44  | Quimica General        | 0.99  | Ingles Enseñanza Integrada de Citiam        | 0.15  |
|  4       | Marketing Digital        | 0.42  | Base de Datos        | 0.99  | Nuevos Medios        | 0.12  |
|  5       | Geometria Diferencial        | 0.41  | Introduccion a la Biologia        | 0.99  | Programacion Avanzada de Apps        | 0.11  |

#### Curso para estudios de matemáticas aplicadas y artes liberales, combinando teoría matemática avanzada con análisis crítico cultural

|          | Isomap          |       | Umap            |       | Normal          |       |
|----------|-----------------|-------|-----------------|-------|-----------------|-------|
|          | Document Name   | Score | Document Name   | Score | Document Name   | Score |
|  1       | Teoria de Grupos        | 0.61  | Teoria del Aprendizaje        | 0.99  | Matematicas Cotidianas        | 0.22  |
|  2       | Teoria de Numeros        | 0.55  | Arte y Educacion        | 0.99  | Logica y Teoria de Conjuntos        | 0.20  |
|  3       | Calculo Diferencial        | 0.40  | Enseñanza de Matematicas        | 0.95  | Enseñanza de Matematicas        | 0.17  |
|  4       | Algebra Abstracta        | 0.39  | Fundamentos de la Educacion        | 0.99  | Arte y Educacion        | 0.16  |
|  5       | Neurociencia y Educación        | 0.39  | Enseñanza de Ciencias Sociales        | 0.99  | Matemática Empresaria        | 0.16  |

### Manhattan

#### Curso de programación, diseño gráfico y cocina internacional con técnicas avanzadas de cocina y recetas modernas

|          | Isomap          |       | Umap            |       | Normal          |       |
|----------|-----------------|-------|-----------------|-------|-----------------|-------|
|          | Document Name   | Distancia | Document Name   | Score | Document Name   | Score |
|  1       | Juegos y Narrativa        | 0.45  | Alta Cocina Ecuatoriana        | 0.60  | Laboratorio de Creacion        | 28.97  |
|  2       | Herramientas Digitales        | 1.21  | Alta Cocina Francesa        | 1.13  | Taller de Arte 3        | 30.17  |
|  3       | Storytelling        | 1.44  | Alta Cocina Mundial        | 1.24  | Fundamentos de las Artes        | 31.21  |
|  4       | Lenguaje Visual y Montaje        | 1.48  | Identidad Culinaria        | 1.37  | Composicion Visual        | 32.23  |
|  5       | Lenguaje del Cine        | 1.48  | Conceptos y Técnicas        | 1.69  | Laboratorio de Creacion        | 32.93  |

#### Curso de escritura creativa y técnica para estudiantes de música interesados en mejorar sus habilidades de composición

|          | Isomap          |       | Umap            |       | Normal          |       |
|----------|-----------------|-------|-----------------|-------|-----------------|-------|
|          | Document Name   | Score | Document Name   | Score | Document Name   | Score |
|  1       | PASEM        | 0.41  | Composicion        | 0.79  | Composicion Visual        | 27.93  |
|  2       | Proyecto Integrador EDU        | 0.59  | Danza Moderna        | 0.90  | Laboratorio de Creacion        | 28.39  |
|  3       | Coloquios Gastr.        | 0.61  | Improvisacion        | 0.99  | Fundamentos de las Artes        | 28.93  |
|  4       | Inclusion y Diversidad        | 0.67  | Composicion Visual        | 1.23  | Taller de Arte 3        | 31.59  |
|  5       | Proyecto Final Danza       | 0.80  | Performance       | 1.36  | Principios de Finanzas        | 32.14  |

#### Curso de idiomas inicial para estudiantes que quieren aprender inglés de manera interactiva y efectiva con enfoque en conversación

|          | Isomap          |       | Umap            |       | Normal          |       |
|----------|-----------------|-------|-----------------|-------|-----------------|-------|
|          | Document Name   | Score | Document Name   | Score | Document Name   | Score |
|  1       | Alta Cocina Ecuatoriana        | 0.70  | Teoria Critica 1 Arte        | 0.41 | Composición Visual        | 29.93  |
|  2       | Alta Cocina Francesa        | 1.10  | Enseñanza Integrada Citiam        | 0.82  | Economia de Negocios        | 30.38  |
|  3       | Alta Cocina Mundial        | 1.35  | Nuevos Medios        | 1.02  | Laboratorio de Creacion        | 30.39  |
|  4       | Identidad Culinaria        | 1.47  | Enseñanza Ciencias Sociales        | 1.11  | Fundamentos de las Artes        | 30.93  |
|  5       | Conceptos y Tecnicas       | 1.55  | Enfasis 3        | 1.15  | Tallr de Arte 3        | 31.59  |

#### Curso sobre inteligencia artificial, tecnología de vanguardia, innovación disruptiva y desarrollo de aplicaciones inteligentes en el mercado

|          | Isomap          |       | Umap            |       | Normal          |       |
|----------|-----------------|-------|-----------------|-------|-----------------|-------|
|          | Document Name   | Score | Document Name   | Score | Document Name   | Score |
|  1       | Teoria Critica 1 Arte        | 0.95  | Estadistica Empresarial        | 0.53  | Fundamentos de las Artes        | 27.93  |
|  2       | Nuevos Medios        | 1.01  | Matematica Empresaria        | 11.13  | Composicion Visual        | 29.23  |
|  3       | Barra para danza contemporanea        | 1.48  | Analisis de Datos        | 1.23  | Economia y Negocios        | 29.68  |
|  4       | Enfasis 3        | 1.70  | Mineria de Datos        | 1.43  | Laboratorio de Creacion        | 29.69  |
|  5       | Enfasis 1       | 1.76  | Seguridad Informática        | 1.71  | Taller de Arte        | 30.88  |

#### Curso para estudios de matemáticas aplicadas y artes liberales, combinando teoría matemática avanzada con análisis crítico cultural

|          | Isomap          |       | Umap            |       | Normal          |       |
|----------|-----------------|-------|-----------------|-------|-----------------|-------|
|          | Document Name   | Score | Document Name   | Score | Document Name   | Score |
|  1       | Analisis Real       | 1.12  | Enseñanzas de Ciencias Sociales        | 0.64  |  Laboratorio de Creacion        | 31.69  |
|  2       | Algebra Abstracta        | 1.15  | Enseñanza de Ciencias        | 1.18  | Matematicas Cotidianas        | 32.28  |
|  3       | Topologia        | 1.26  | Enseñanza Integrada de Citiam        | 1.18  | Taller de Arte        | 32.88  |
|  4       | Analisis Funcional        | 1.34  | Arte y Educacion        | 1.40  | Composicion Visual 1        | 33.23  |
|  5       | Teoria de Grupos       | 1.49  | Teoria Critica 1 y Arte        | 1.71  | Coloquios ADM        | 33.62  |
