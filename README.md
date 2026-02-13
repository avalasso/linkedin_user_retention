# 📈 Strategic Networking Segmentation: Maximizing Engagement on LinkedIn for University Students

## 🎯 Business Problem

Professional networking, understood as a tool for strategically building and cultivating a network of valuable contacts to generate business opportunities, support, and personal growth, has become a key element in the workplace, specifically due to branding and personal branding. In this context, social networks play a fundamental role because they help to achieve, among other benefits, reach and visibility. In the professional world, this is well known and leveraged through the quintessential social network for this purpose: LinkedIn. However, there is not much information about the perception and behavior of university students toward this social network. Given the lack of information to address this issue, the question arises: **How can we segment students based on their online behavior to predict their long-term loyalty to the platform?**. This project transforms behavioral data into **retention strategies**.

* **Objetive:** Identificar segmentos de usuarios para personalizar campañas de marketing
* **KPI Impactado:** Retención de usuarios (Retention Rate)

## 🧠 Metodología y Solución
Utilicé un algoritmo de **K-Means Clustering** para agrupar a los estudiantes según su nivel de interacción, conexiones y uso de la plataforma.
* **Población de estudio:** Estudiantes universitarios que recibieron capacitación específica en marca personal y visibilidad laboral.
* **Procesamiento:** [Pandas, Numpy, Matplotlib, Seaborn, wordcloud, Scikit-Learn].
* **Validación:** Selección de 'k' mediante el método de Silhouette Score.

## 👥 Personas de Marketing Identificadas
| Estudiante Tipo | Descripción | Estrategia de Marketing |
| :--- | :--- | :--- |
| **Constructor estratégico** | *“Utilizo LinkedIn como una herramienta clave para construir mi carrera”* | Mentoría - Eventos de reclutamiento |
| **Observador Exploratorio** | *“Sé que existe LinkedIn y para que sirve, pero no se como extraer todo su potencial”* | Alfabetización digital profesional - Ejemplos claros de utilidad |
| **Conocedor Pasivo** | *“LinkedIn es importante, aunque todavía no lo uso activamente”* | Talleres prácticos - Incentivos para la interacción |

## 📊 Visualización de Resultados
Nube de palabras (wordcloud) de los comentarios de los estuidantes encuestados:
![WordCloud Comentarios](wordcloud_linkedin.png)
Los estudiantes reconocen el valor de LinkedIn, pero en el largo plazo.

Mapa de influencia de variables
![Mapa_Influencia de variables](Influence_feature_map.png)
las variables que apuntan en la misma direccion dan a conocer:

* *primer cuadrante:* Estuidantes para los que la exposicion y ser visisbles pesa mas (a veces el doble) que su desarrollo profesional sin decir que este ultimo no es importante.
* *cuarto cuadrante:* Estudiantes en donde el desarrollo profesional es moderadamente importante pero sus perfiles no generan visibilidad en la red social.

![Clusters](clusters.png)


