# Información general sobre el Portal Geoespacial del Proyecto Cosecha de Agua en Nicaragua
Esta [organización GitHub](https://docs.github.com/en/github/setting-up-and-managing-organizations-and-teams/about-organizations) contiene los repositorios del Portal Geoespacial del Proyecto Cosecha de Agua en Nicaragua. En este documento, se brinda una descripción del proyecto, de la implementación del portal geoespacial y una breve reseña de cada uno de los repositorios que componen esta organización GitHub.

## El proyecto Cosecha de Agua en Nicaragua
La segunda fase del proyecto “Adaptación de la Agricultura al Cambio Climático a través de la Cosecha de Agua en Nicaragua” (llamado también proyecto *Cosecha de agua en Nicaragua*, iniciada en 2019, se identifica como una oportunidad de consolidar esfuerzos en la promoción de la tecnología de cosecha de agua, de su adopción por parte de las familias productoras de las regiones del corredor seco y de la generación de importantes esfuerzos en materia de investigación, sistematización y generación de espacios para el intercambio y difusión del conocimiento generado. Su objetivo principal es contribuir a que 2500 familias de pequeños y medianos productores de diez municipios del corredor seco en el centro norte de Nicaragua, establezcan sistemas productivos más resilientes al cambio climático y mejoren su seguridad alimentaria y nutricional, asegurando una adecuada sistematización de los aprendizajes. El proyecto se ejecuta con recursos de la [Agencia Suiza para el Desarrollo y la Cooperación (Cosude)](https://www.eda.admin.ch/deza/es/home/cosude.html) y está sustentado en un acuerdo de contribución entre esa agencia y el [Centro Agronómico Tropical de Investigación y Enseñanza (Catie)](https://www.catie.ac.cr/), el cual brinda servicios de asesoría técnica.

El proyecto consiste de tres componentes:

1. **Sistemas productivos**: el objetivo de este componente es contribuir a que pequeños y medianos productores diversifiquen sus sistemas de producción, adoptando buenas prácticas de cosecha y uso de agua, en función de mejorar la disponibilidad de alimentos e ingresos económicos. Se construye infraestructura para la cosecha de agua y se promueve la implementación de tecnologías y prácticas de uso y manejo de agua con los productores.
2. **Gestión del conocimiento**: este componente está dirigido a fortalecer las capacidades de los actores participantes en el proyecto, para que puedan tomar mejores decisiones, desarrollar eficientemente las alternativas tecnológicas sobre la cosecha de agua de lluvias, así como lograr una mejora en la producción agrícola y pecuaria y por ende en la seguridad alimentaria y nutricional de las familias y el ingreso.
3. **Gobernanza y participación ciudadana**: las premisas básicas de este componente comprenden un estímulo y apoyo a la gobernanza y la participación ciudadana en el uso y manejo eficiente del agua de lluvia para fines productivos, apoyándose en acciones de comunicación para el desarrollo, incidencia y creación de ciudadanía.

Los diez municipios de la zona centro norte de Nicaragua en los que se ejecuta el proyecto son: Ciudad Antigua, Mozonte, Totogalpa, Telpaneca, Palacagüina, Yalagüina, Somoto, San Lucas, Pueblo Nuevo y Condega. Las 2500 familias de pequeños y medianos productores beneficiadas recibirán apoyo para construir obras de cosecha de agua, instalar sistemas de riego y promover sistemas productivos.

El proyecto cuenta con un sistema de información denominado Siscan, el cual, además de la interfaz de usuario, incluye una interfaz de programación de aplicaciones (API, *Application Programming Interface*), la cual permite el acceso a los datos a través de lenguajes de programación.

## El portal geoespacial
Como parte del componente de gestión del conocimiento, se ha desarrollado un portal en Internet para la visualización y el análisis de los datos geoespaciales relacionados con la cosecha de agua, el cual permite dar seguimiento a un conjunto de indicadores de impacto y efecto previamente definidos, así como monitorear el avance del proyecto en general. El portal está disponible en la dirección [https://geo-cosecha-agua.github.io/](https://geo-cosecha-agua.github.io/).

A la fecha de escritura de este documento, el portal maneja dos conjuntos de datos principales:

- **Beneficiarios**: son productores seleccionados para participar en el proyecto. Sobre estos, se incluyen datos personales (nombre, género, edad), datos de las fincas (ubicación, área), datos de la evaluación (fecha, puntaje, técnico evaluador) y tipo de obra planificada (ej. escorrentía, techo, manantial, asistencia técnica).
- **Obras**: obras de cosecha de agua implementadas en las fincas de los productores, incluyendo su tipo (ej. reservorio, tanque tipo Zamorano, pila de concreto, conformación de manantiales), ubicación, capacidad y monto.

El portal se aloja en la plataforma geoespacial del Catie, implementada a través de [ArcGIS Online](https://www.arcgis.com/). La interfaz de usuario final está basada en tableros de control (*dashboards*) desarrollados con la herramienta [ArcGIS Dashboards](https://www.esri.com/es-es/arcgis/products/arcgis-dashboards/overview), los cuales combinan mapas con gráficos estadísticos e información tabular. Los tableros de control acceden repositorios de datos publicados como servicios web.

## Repositorios
- [https://github.com/geo-cosecha-agua/geo-cosecha-agua.github.io](https://github.com/geo-cosecha-agua/geo-cosecha-agua.github.io): sitio web del portal geoespacial.
- [https://github.com/geo-cosecha-agua/geo-cosecha-agua-informacion-general](https://github.com/geo-cosecha-agua/geo-cosecha-agua-informacion-general): este repositorio.
