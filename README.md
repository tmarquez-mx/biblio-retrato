# Biblio-retrato. Un proyecto de Humanidades Digitales  ![imagen](https://user-images.githubusercontent.com/69394840/173283398-25a352a4-c7a2-4acb-926e-824d7f40ec95.png)
## Descripción breve
Proyecto de visualización que busca complementar los datos visuales de un retrato fotográfico con los metadatos de un gestor de referencias bibliográficas.  Esta superposición explora digitalmente la identidad acádemica en relación con el trabajo de lectura profesional realizado ¿somos lo que leemos? ¿en dónde se ubica ese cúmulo de lecturas bibliográficas respecto a nuestra propia presentación como investigadores?  Es un proyecto híbrido que desarrollará herramientas de minería de textos y visualización para Zotero [^1],así como galerías en web que superpondrán (overlap) esas visualizaciones que se generarán desde el gestor bibliográfico, con retratos fotográficos subidos por la web obteniendo por el mismo medio, el biblio-retrato en formato .png o .jpg
[^1]: Herramientas como Paper Machine y Zotero Voyant Export no han sido actualizadas a las últimas versiones de Zotero pero sus códigos están disponibles en Github. https://github.com/papermachines/papermachines; https://github.com/corajr/zotero-voyant-export/
## Objetivos
1. Explorar la identidad académica en relación a las métricas y visualizaciones de su quehacer profesional
2. Desarrollar herramientas de minería de textos y visualización para Zotero, a fin de contruir analíticas y visualizaciones de su uso y contenido.
3. Crear visualizaciones que de manera estética a través de autorretarto, interroguen los vacíos de la fotografía digital convencional y el lugar de las prácticas de lectura académica.

## Antecedentes

El proyecto explora la conformación de las identidades académicas a partir de las métricas y analíticas de la producción científica cada vez vez más frecuentes en los sistemas de evaluación de la producción científica a la que son sometidos los investigadores en las universidades. Típicamente son visualizaciones construidas desde fuera sobre el trabajo de investigación. Este proyecto en cambio se enfoca específicamente en las métricas y visuales que resultan del trabajo de lectura de textos que pueden o no resultar en un producto evaluable. Serán además visualizaciones de datos que están totalmente bajo control del investigador y que él mismo generará. Se parte del supuesto que la lectura constituye una *práctica académica de literacidad*, y, en tanto práctica de literacidad, la lectura de textos científicos influye en la conformación de la identidad como investigador(a).(Ver Calle-Arango et  frecuentes al., 2021; Kirka 2021)

Para identificar el trabajo de lectura se tomará las bases bibliográficas donde el investigador gestiona sus fuentes. Concretamente, se trabajará con Zotero por ser un programa de código abierto y de amplia difusión. Se desarrollarán o actualizarán plugins que permitirán construir analíticas de las fuentes registradas y de sus usos, así como generar visualizaciones con esos datos. Tales imágenes se superpondrán con una forografía del investigador dando como resultado un "biblio-retarto" que reflejará cómo su presentación como investigador está conformada -al menos en parte- por la relación que guarda con lo que lee.

## Justificación
1. Estímulo a los estudiantes a sistematizar su información bibliográfica a través de software
2. Incentivo a los profesores e investigadores a monitorear y evaluar sus fuentes de lectura
3. Formación de un grupo de trabajo interdisciplinario
4. Desarrollo de metodologías para la documentación de procesos de trabajo y su apertura pública
5. Incursión en el terreno de las Humanidades Digitales y en los principios FAIR de ciencia abierta
6. Desarrollo de herramientas para la visualización de corpus bibliográficos que se abrirán a una comunudad global de usuarios de Zotero
7. Reflexión sobre cómo los datos y la experiencia de consulta de fuentes nos constituyen (identificación y análisis de patrones y trayectorias)
8. Desarrollo de código en el terreno de la IA para la generación de imágenes a partir de análiticas
9. Desarrollo de código para la superposición y composición de imágenes agregadas vía web.
10. Sensibilización sobre el tema de las identidades académicas y el papel político de las visualizaciones y métricas.


## Estrategia de documentacion
El proyecto se documentará a través de Github y siguiendo la Guía de buenas prácticas para la elaboración y evaluación de proyectos de HD y Checklist de la Red HD. http://humanidadesdigitales.net/guia-de-buenas-practicas-para-la-elaboracion-y-evaluacion-de-proyectos-de-humanidades-digitales-y-checklist/
## Revisión y evaluación académica
Se buscará financiamiento académico por evaluación (DINV/Ibero). Además de la documentación en Github donde también se compartirá la metodología y los códigos desarrollados, habrá un sitio web desde donde se podrá hacer uso en línea de las aplicaciones desarrolladas. Se espera también desarrollar plugins para Zotero que estarán disponibles en la página de recursos de esa aplicación. De esta manera, los componentes del proyecto al estar abiertos al uso de una amplia comunidad académica, estará evaluación de pares y no-pares.
## Estrategia de sostenibilidad
Se trata de un punto crítico pues el biblio-retrato depende de las actualizaciones de Zotero que exigirá revisiones  constantes de los plugins que se desarrollen. Al abrir el código, se espera que de no contar con recursos para el mantenimiento, la comunidad de usuarios pueda hacerlo.
##  Experticias necesarias:
1.	Conocimiento del código abierto de Zotero y programación en JavaScript y SQLite 
2.	Manipulación de imagen digital y programación en HTML y Python
## Equipo
1. Teresa Marquez. Responsable
2. UnX programadorX. 
3. UnX diseñadorX Transmedia. 
## Influencias de proyectos HD
Proyectos en HD: 
1. “Intercambios oceánicos” https://oceanicexchanges.org/mx/ 
2. “I ♥ E-Poetry” https://iloveepoetry.org/
## Herramientas
Biblio-retrato, deberá hacer uso de Zotero y de OpenRefine, pues el primero contiene el corpus que se usará y el segundo es una herramienta para depurar los datos, por ello no se considerarán aquí como herramientas por separado.

Consideraré como herramientas, aquellas que traduzcan o transformen datos, como las aplicaciones de visualización siguientes

Voyant Tools, recibirá los textos desde un .CSV para generar las analíticas y las visualizaciones. Extisten ya dos plugins sin mantenimiento (Ver nota al pie 2). La tarea es actualizarlo a la versión vigente de Zotero.

Palladio, es otra herramienta de visualización de archivos .CSV que complementaria la galería de Voyant permitiendo mapear y conectar dos datos formando conjuntos.

La tercera  herramienta o código, deberá permitir recibir a través de una página web las visualizaciones de los plugins de Voyant y Palladio, así como las fotos que suba el usuario y realizar la superposición de ambas imágenes a través de IA. Una opción es trabajar sobre Pine Tools, una herramienta online gratuita. Habrá una galería con opciones preestablecidas de acuerdo al gráfico (nube, mapa, barras, etc.) y al encuadre de la foto. Finalmente, la aplicación web deberá devolver el biblio-retrato para ser bajado por el usuario.

Ningún elemento ni objeto digital (i.e. archivos .csv; .svg; .jpg; .png, etc.) se conservará en servidores por lo que los datos del usuario estarán plenamente seguros y libres de todo uso o almacenamiento indebido.

## Recursos en revisión (en proceso)
1. https://vispo.com/index.html  (animación)
2. https://www.usandizaga.com/design/pinacogramas-y-caligramas-retratos-con-letras/![imagen](https://user-images.githubusercontent.com/69394840/173201608-666907ba-def1-455e-8030-35f75e47067d.png) (retratos con letras)
3. https://wordart.com/  (Online cloud creator)
4. https://openrefine.org
5. https://voyant-tools.org/?corpus=451e87665270278b3512bc72bbe3472c&panels=cirrus,reader,trends,summary
6. http://musingsaboutlibrarianship.blogspot.com/2019/09/the-rise-of-new-citation-indexes-and_5.html
7. https://www.vosviewer.com

## Acceso y sustentabilidad
La aplicacación estará alojada en un sitio institucional y los datos que se reciban a través del sistema (como fotografías personales y analíticas), no se conservarán como parte de la protección de los datos personales.
## Productos esperables
Al ser el primer proyecto de HD que se realizará en la Ibero, herramientas de software que se desarrollen, sinergias, infraestructura, metodologías y procesos (incluidos los de documentación) serán en sí mismos productos de la investigación. Como resultado final se pueden considerar participaciones en reuniones académicas o congresos; al menos dos artículos académicos y una exposición multimedia donde se mostrarán fotos impresas y en pantalla, así como animaciones del proceso de trabajo. La página web de biblio-retratos es el producto principal y contendrá además toda la documentación del proyecto lo que en sí mismo generará aprendizaje y antecedentes para buenas prácticas de la investigación abierta en la Ibero. 
## Licencia
<p xmlns:cc="http://creativecommons.org/ns#" >This work is licensed under <a href="http://creativecommons.org/licenses/by-nc-sa/4.0/?ref=chooser-v1" target="_blank" rel="license noopener noreferrer" style="display:inline-block;">CC BY-NC-SA 4.0<img style="height:22px!important;margin-left:3px;vertical-align:text-bottom;" src="https://mirrors.creativecommons.org/presskit/icons/cc.svg?ref=chooser-v1"><img style="height:22px!important;margin-left:3px;vertical-align:text-bottom;" src="https://mirrors.creativecommons.org/presskit/icons/by.svg?ref=chooser-v1"><img style="height:22px!important;margin-left:3px;vertical-align:text-bottom;" src="https://mirrors.creativecommons.org/presskit/icons/nc.svg?ref=chooser-v1"><img style="height:22px!important;margin-left:3px;vertical-align:text-bottom;" src="https://mirrors.creativecommons.org/presskit/icons/sa.svg?ref=chooser-v1"></a></p> 
<img width="965" alt="Captura de Pantalla 2022-06-11 a la(s) 21 00 29" src="https://user-images.githubusercontent.com/69394840/173211143-62becfaf-af07-4c53-9b94-302b48ec98c8.png">

## Procedimiento para maqueta (en proceso)
1. Limpieza de la base Zotero con OpenRefine 
2. Separación del corpus en las columnas de un CSV utilizando delimitadores.
3. Extracción de columnas: título; autor; fechas; lugar de edición; subcolección. Separación del campo autor para extraer solo apellidos.
4. Generar en Palladio y Voyant visualizaciones a partir del archivos .CSV depurado
5. Remover fondo de las imágenes .SVG  con removeBG
6. Capturar foto retratos
7. Fundir ambas imágenes

## Fuentes consultadas
Bucchi, M., & Saracino, B. (2016). “Visual Science Literacy”: Images and Public Understanding of Science in the Digital Age. Science Communication, 38(6), 812-819. https://doi.org/10.1177/1075547016677833

Engebretsen, M., & Kennedy, H. (Eds.). (2020). Data Visualization in Society. Amsterdam University Press. https://doi.org/10.5117/9789463722902

Guzmán-Valenzuela, C., & Martínez Larraín, M. (2016). Tensiones en la construcción de identidades académicas en una universidad chilena. Estudios pedagógicos (Valdivia), 42(3), 191-206. https://doi.org/10.4067/S0718-07052016000400010

Hullman, J., & Diakopoulos, N. (2011). Visualization Rhetoric: Framing Effects in Narrative Visualization. IEEE Transactions on Visualization and Computer Graphics, 17(12), 2231-2240. https://doi.org/10.1109/TVCG.2011.255

Imagen: Text-to-Image Diffusion Models. (s. f.). Recuperado 16 de junio de 2022, de https://imagen.research.google/

Kennedy, H., & Hill, R. L. (2017). The Pleasure and Pain of Visualizing Data in Times of Data Power. Television & New Media, 18(8), 769-782. https://doi.org/10.1177/1527476416667823

Kirca, H. S., & Glover, P. (2021). We are what we read: Reading identity of university students of English language teaching. RumeliDE Dil ve Edebiyat Araştırmaları Dergisi. https://doi.org/10.29000/rumelide.997589

Renteria, A. L. (2016). Identidades académicas en cambio en el seno de la universidad multilingüe. Papeles del CEIC, 163-163. https://doi.org/10.1387/pceic.15978

Saharia, C., Chan, W., Saxena, S., Li, L., Whang, J., Denton, E., Ghasemipour, S. K. S., Ayan, B. K., Mahdavi, S. S., Lopes, R. G., Salimans, T., Ho, J., 

Fleet, D. J., & Norouzi, M. (2022). Photorealistic Text-to-Image Diffusion Models with Deep Language Understanding (arXiv:2205.11487). arXiv. https://doi.org/10.48550/arXiv.2205.11487

Text-to-Image Generation. (s. f.). Recuperado 16 de junio de 2022, de https://vision-explorer.allenai.org/text_to_image_generation

Visualizing Identity. (s. f.). Chrissy Brimmage. Recuperado 16 de junio de 2022, de http://www.chrissybrimmage.com/visualizing-identity

Xiong, C., Shapiro, J., Hullman, J., & Franconeri, S. (2020). Illusion of Causality in Visualized Data. IEEE Transactions on Visualization and Computer Graphics, 26(1), 853-862. https://doi.org/10.1109/TVCG.2019.2934399

Xu, T., Zhang, P., Huang, Q., Zhang, H., Gan, Z., Huang, X., & He, X. (2018). AttnGAN: Fine-Grained Text to Image Generation with Attentional Generative Adversarial Networks. 2018 IEEE/CVF Conference on Computer Vision and Pattern Recognition, 1316-1324. https://doi.org/10.1109/CVPR.2018.00143

Zakraoui, J., Saleh, M., Al-Maadeed, S., & Jaam, J. M. (2021). Improving text-to-image generation with object layout guidance. Multimedia Tools and Applications, 80(18), 27423-27443. https://doi.org/10.1007/s11042-021-11038-0




## Narrativa visual a partir de biblio-retratos simulados con fines demostrativos
![4](https://user-images.githubusercontent.com/69394840/173243391-75859132-e8fd-4829-8866-111a3d8e076d.png)
![1](https://user-images.githubusercontent.com/69394840/173243415-7db81dea-86e8-4159-bf9d-0d6c52f6efeb.png)
![2](https://user-images.githubusercontent.com/69394840/173243418-13b82350-55a1-4452-b328-10b69ccd38c6.png)
![3](https://user-images.githubusercontent.com/69394840/173243423-1f146093-2b5b-453a-a0b2-cbd8ca7b0817.png)
