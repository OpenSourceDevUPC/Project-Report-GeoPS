<div align="center">
<img src="https://github.com/DevWebUPC/report/blob/main/resources/imgs/UPC_logo_transparente.png" alt="Logo-UPC" width="150">
  
## Universidad Peruana de Ciencias Aplicadas

**Ingeniería de Software**

**Ciclo:** 2025-2

**Curso:** Desarrollo de Aplicaciones Open Source

**Sección:** 7391

**Profesor:** Mori Paiva, Hugo Allan

----

## Informe de Trabajo Final

**Startup:** GeoPsLabs

**Nombre del producto:** GeoPs

#### Relación de integrantes

| Integrante                              | Código         |
|-----------------------------------------|----------------|
| Huapaya Galindo, Dyaron                 | U202322855     |
| Huarcaya Matias, Gilbert Alonso         | u202322187     |
| Cotrina Siclla, Sofia Alessandra        | u20231b120     |
|                                         |                |
|                                         |                |


<br><div align="center"><h3>Agosto 2025</h3></div><br>
</div>
<br><br>

---
### Registro de Versiones
<div align="justify">
  
|**Versión**|**Fecha**|**Autor**|**Descripción de modificación**|
| - | - | - | - |
</div><br><br>

---

# Project Report Collaboration Insights

URL de Organización de GitHub DevWebUPC: 
[https://github.com/OpenSourceDevUPC](https://github.com/OpenSourceDevUPC)

URL del Repositoria del Project Report:
[https://github.com/OpenSourceDevUPC/Project-Report-GeoPS](https://github.com/OpenSourceDevUPC/Project-Report-GeoPS)

<strong>*Entrega TB1:*</strong>

+ Desarrollo de Actividades:
+ Evidencias de colaboracion y commits:

---
# Contenido
- [Contenido](#contenido)
- [Student Outcome](#student-outcome)
- [Capítulo 1: Introducción](#capitulo-1-introducción)
  - [1.1. Startup Profile](#11-startup-profile)
    - [1.1.1. Descripción de la StartUp](#111-descripcion-del-startup)
    - [1.1.2. Perfiles de integrantes del equipo](#112-perfiles-de-integrantes-del-equipo)
  - [1.2. Solution Profile](#12-solution-profile)
    - [1.2.1 Antecedentes y problemática](#121-antecedentes-y-problemática)
    - [1.2.2 Lean UX Process](#122-lean-ux-process)
      - [1.2.2.1 Lean UX Problem Statement](#1221-lean-ux-problem-statements)
      - [1.2.2.2 Lean UX Assumptions](#1222-lean-ux-assumptions)
      - [1.2.2.3 Lean UX Hypothesis Statements](#1223-lean-ux-hypothesis-statements)
      - [1.2.2.4 Lean UX Canvas](#1224-lean-ux-canvas)
  - [1.3. Segmentos Objetivo](#13-segmentos-objetivos)
  
- [Capítulo 2: Requirements Elicitation & Analysis](#capitulo-2-requirements-elicitation--analysis)
  - [2.1. Competidores](#21-competidores)
    - [2.1.1. Análisis competitivo](#211-analisis-competitivo)
    - [2.1.2. Estrategias y tácticas frente a competidores](#212-estrategias-y-tácticas-frente-a-competidores)
  - [2.2 Entrevistas](#22-entrevistas)
    - [2.2.1 Diseño de entrevistas](#221-diseño-de-entrevistas)
    - [2.2.2 Registro de Entrevistas](#222-registro-de-entrevistas)
    - [2.2.3. Análisis de entrevistas](#223-análisis-de-entrevistas)
  - [2.3. Needfinding](#23-needfinding)
    - [2.3.1. User Personas](#231-user-personas)
    - [2.3.2 User Task Matrix](#232--user-task-matrix)
    - [2.3.3. User Journey Mapping](#233-user-journey-mapping)
    - [2.3.4. Empathy Mapping](#234-empathy-mapping)
    - [2.3.5. As-is Scenario Mapping](#235-as-is-scenario-mapping)
  - [2.4. Ubiquitous Language](#24-ubiquitous-language)
    
- [Capítulo 3: Requirements Specification](#capitulo-3-requirements-specification)
  - [3.1. To-Be Scenario Mapping](#31-to-be-scenario-mapping)
  - [3.2. User Stories](#32-user-stories)
  - [3.3. Impact Mapping](#33-impact-mapping)
  - [3.4. Product Backlog](#34-product-backlog)

- [Capítulo 4: Product Design](#capítulo-4-product-design)
  - [4.1 Style Guidelines](#41-style-guidelines)
    - [4.1.1. General Style Guidelines](#411-general-style-guidelines)
    - [4.1.2. Web Style Guidelines](#412-web-style-guidelines)
  - [4.2. Information Architecture](#42-information-architecture)
    - [4.2.1. Organization Systems](#421-organization-systems)
    - [4.2.2. Labeling Systems](#422-labeling-systems)
    - [4.2.3. SEO Tags and Meta Tags](#423-seo-tags-and-meta-tags)
    - [4.2.4. Searching Systems](#424-searching-systems)
    - [4.2.5. Navigation Systems](#425-navigation-systems)
  - [4.3 Landing Page UI Design](#43-landing-page-ui-design)
    - [4.3.1. Landing Page Wireframe](#431-landing-page-wireframe)
    - [4.3.2. Landing Page Mock-up](#432-landing-page-mock-up)
  - [4.4 Web Applications UX/UI Design](#44-web-applications-uxui-design)
    - [4.4.1. Web Applications Wireframes](#441-web-applications-wireframes)
    - [4.4.2. Web Applications Wireflow Diagrams](#442-web-applications-wireflow-diagrams)
    - [4.4.3. Web Applications Mock-ups](#443-web-applications-mock-ups)
    - [4.4.4. Web Applications User Flow Diagrams](#444-web-applications-user-flow-diagrams)
  - [4.5. Web Applications Prototyping](#45-web-applications-prototyping)
  - [4.6. Domain-Driven Software Architecture](#46-domain-driven-software-architecture)
    - [4.6.1. Software Architecture Context Diagram](#461-software-architecture-context-diagram)
    - [4.6.2. Software Architecture Container Diagrams](#462-software-architecture-container-diagrams)
    - [4.6.3. Software Architecture Components Diagrams](#463-software-architecture-components-diagrams)
  - [4.7. Software Object-Oriented Design](#47-software-object-oriented-design)
    - [4.7.1. Class Diagrams](#471-class-diagrams)
    - [4.7.2. Class Dictionary](#472-class-dictionary)
  - [4.8. Database Design](#48-database-design)
    - [4.8.1. Database Diagram](#481-database-diagram)
    
- [Capítulo 5: Product Implementation, Validation & Deployment](#capítulo-5-product-implementation-validation--deployment)
  - [5.1. Software Configuration Management](#51-software-configuration-management)
    - [5.1.1. Software Development Environment Configuration](#511-software-development-environment-configuration)
    - [5.1.2. Source Code Management](#512-source-code-management)
    - [5.1.3. Source Code Style Guide & Conventions](#513-source-code-style-guide--conventions)
    - [5.1.4. Software Deployment Configuration](#514-software-deployment-configuration)
  - [5.2. Landing Page, Services & Applications Implementation](#52-landing-page-services--applications-implementation)
    - [5.2.1. Sprint 1](#521-sprint-1)
      - [5.2.1.1. Sprint Planning 1](#5211-sprint-planning-1)
      - [5.2.1.2. Aspect Leaders and Collaborators](#5212-aspect-leaders-and-collaborators)
      - [5.2.1.3. Sprint Backlog 1](#5213-sprint-backlog-1)
      - [5.2.1.4. Development Evidence for Sprint Review ](#5214-development-evidence-for-sprint-review)
      - [5.2.1.5. Execution Evidence for Sprint Review](#5215-execution-evidence-for-sprint-review)
      - [5.2.1.6. Services Documentation Evidence for Sprint Review](#5216-services-documentation-evidence-for-sprint-review)
      - [5.2.1.7. Software Deployment Evidence for Sprint Review](#5217-software-deployment-evidence-for-sprint-review)
      - [5.2.1.8. Team Collaboration Insights during Sprint](#5218-team-collaboration-insights-during-sprint)
      
- [Conclusiones](#conclusiones)
- [Bibliografía](#bibliografía)
- [Anexos](#anexos)




# Student Outcome
 <div aligh="justify">
   
   |Criterio Específico|Acciones Realizadas|Conclusiones|
   |-------------------|-------------------|------------|
   
 </div>

## Capitulo 1: Introducción
### 1.1. Startup Profile
  #### 1.1.1. Descripcion del Startup
  #### 1.1.2. Perfiles de Integrantes del equipo
### 1.2. Solution Profile
  #### 1.2.1. Antecedentes y problemática
  #### 1.2.2. Lean UX Process
  ##### 1.2.2.1. Lean UX Problem Statements
  ##### 1.2.2.2. Lean UX Assumptions
  ##### 1.2.2.3. Lean UX Hypothesis Statements
  ##### 1.2.2.4. Lean UX Canvas
### 1.3. Segmentos objetivos

## Capitulo 2: Requirements Elicitation & Analysis
### 2.1. Competidores
  #### 2.1.1. Analisis competitivo

| Competitive Analysis Landscape | Su startup <p align="center"><img src="images for chapter ii/logo_geops.png" alt="PI5" width="1000"></p>  GeoPs | Competidor 1 <p align="center"><img src="images for chapter ii/logo_groupon.jpeg" alt="PI5" width="1000"></p> Groupon | Competidor 2 <p align="center"><img src="images for chapter ii/logo_tiendeo.png" alt="PI5" width="1000"></p> Tiendeo | Competidor 3 <p align="center"><img src="images for chapter ii/logo_retailmenot.png" alt="PI5" width="1000"></p> RetailMeNot |
|--------------------------------|------------------|----------------------|----------------------|--------------------------|
| Overview                                               | Plataforma de publicidad hiperlocalizada que utiliza la geolocalización del navegador y notificaciones push para conectar negocios con usuarios cercanos. | Plataforma web de descuentos en productos, servicios y experiencias, con ofertas por tiempo limitado. Su fuerte está en la compra de cupones antes de ir al negocio. | Plataforma web y móvil que agrega folletos y ofertas digitales de tiendas físicas. Facilita la consulta de promociones para planificar compras en un área específica. | Plataforma web de cupones y ofertas online. Ofrece códigos de descuento para compras en línea y cupones imprimibles o para mostrar en tiendas físicas. |
| Ventaja competitiva ¿Qué valor ofrece a los clientes?  | Publicidad relevante sin descarga. Ofrecemos ofertas contextuales y en tiempo real a los clientes, y un canal de marketing efectivo y asequible a los negocios locales. | Descuentos atractivos. Facilitan el descubrimiento de nuevas experiencias a menor costo para los clientes y garantizan un alto volumen de ventas para los negocios. | Planificación de compras. Ayudan a los clientes a comparar precios y planificar sus compras con folletos digitales, mientras digitalizan las campañas de folletos de los negocios. | Ahorro versátil. Proporcionan a los clientes acceso a una amplia variedad de cupones para compras online y físicas, y a los negocios un canal para distribuir descuentos a una gran base de usuarios. |
| Mercado objetivo                                       | Usuarios que buscan ofertas personalizadas y negocios que buscan publicitarse. | Usuarios que buscan descuentos en una amplia gama de categorías. | Consumidores que planifican sus compras en tiendas físicas y buscan las mejores ofertas en su área. | Consumidores que buscan descuentos al comprar en tiendas físicas y en línea. |
| Estrategias de marketing                               | Marketing digital y publicidad en redes sociales dirigida a PyMEs y usuarios interesados en ofertas locales y tecnología de geolocalización. | Ofertas diarias y por tiempo limitado, marketing por correo electrónico, publicidad en redes sociales y promociones especiales. | Agregación de folletos digitales de diversas tiendas, notificaciones de nuevas ofertas y tiendas cercanas, publicidad online. | Promoción de cupones y ofertas a través del sitio web y publicidad digital. |
| Productos & Servicios                                  | Publicidad contextual por ubicación, notificaciones de ofertas cercanas y gestión de campañas con analíticas. | Cupones digitales para productos, servicios y experiencias; ofertas limitadas; marketplace. | Folletos digitales de tiendas locales, buscador de ofertas por ubicación/categoría y alertas de promociones. | Cupones y códigos online/en tienda y extensión de navegador para descuentos automáticos. |
| Precios & Costos                                       | Modelo gratuito para usuarios consumidores. De pago para negocios. | Modelo gratuito para usuarios (pagan solo los cupones). De pago para negocios. | Modelo gratuito, con anuncios. De pago para negocios. | Modelo Gratuito. De pago para negocios. |
| Canales de distribución (Web y/o Móvil)                | Página web. | Página web, aplicación móvil y correo electrónico. | Página web y aplicación móvil. | Página web y aplicación móvil. |
| Fortalezas                                             | Sin fricción de descarga. Acceso instantáneo por web. Publicidad en tiempo real. Impacta a clientes por proximidad.Herramientas para PyMEs. Dashboard analítico. | Sin fricción de descarga. Acceso instantáneo por web. Publicidad en tiempo real. Impacta a clientes por proximidad. Herramientas para PyMEs. Dashboard analítico. | Formato familiar. Los folletos digitales son fáciles de usar. Centralización. Reúne ofertas de múltiples tiendas. Credibilidad. Relaciones con grandes minoristas. | Variedad de descuentos. Amplia base de datos de cupones. Cobertura online/offline. Cubre diferentes hábitos de compra. Extensión de navegador. Automatiza el ahorro en línea. |
| Debilidades                                            | Depende del navegador. Requiere permisos de ubicación. Privacidad. La recolección de datos es un tema sensible. | Modelo agresivo. Puede devaluar la marca de los negocios. Sin tiempo real. Las ofertas son limitadas y no contextuales. | Poca personalización. Depende de lo que los minoristas publican. Actualización manual. El contenido no es dinámico ni en tiempo real. | Sin hiper localización. No ofrece la experiencia de proximidad. Calidad de cupones. Algunos códigos pueden no funcionar. |
| Oportunidades                                          | Crecimiento del comercio local. Aumento de la preferencia por negocios de barrio. Expansión del marketing de proximidad. Los negocios buscan publicidad más dirigida. | Expansión de servicios. Podrían incluir nuevas categorías. Mayor integración. Posibilidad de ofrecer ofertas más personalizadas por ubicación. | Alertas personalizadas. Notificar a usuarios sobre ofertas de tiendas favoritas. Mayor interacción. Crear listas de compras desde los folletos. | Expansión geográfica. Oportunidad de entrar con fuerza en nuevos mercados. Integración con billeteras digitales. Facilitar el uso de los descuentos. |
| Amenazas                                               | Competencia de apps nativas. Pueden ofrecer una integración más profunda. Monopolio de gigantes. Google Maps es una fuerte competencia indirecta. | Nuevas startups. El surgimiento de apps locales más ágiles. Fatiga del usuario. El modelo de cupones puede volverse predecible. | Competencia de Google Ads. Los minoristas pueden optar por publicidad más efectiva. Obsolescencia. Los usuarios jóvenes pueden considerar los folletos digitales obsoletos. | Competencia de tiendas. Los minoristas desarrollan sus propias apps de lealtad. Fatiga de cupones. Los usuarios se cansan de buscar descuentos y prefieren precios directos. |

  #### 2.1.2. Estrategias y tácticas frente a competidores 

**1. Estrategias para Mitigar Debilidades Propias**
Frente a la dependencia del navegador y la privacidad: La principal debilidad de GeoPS es la necesidad de que el usuario dé su permiso de ubicación. Para mitigar esta fricción, la plataforma debe ser transparente y construir confianza.

**Táctica:** Ofrece la opción de explorar la plataforma sin compartir la ubicación de inmediato, permitiendo al usuario buscar ofertas manualmente por distritos o categorías antes de que se sientan cómodos compartiendo su ubicación.

**2. Estrategias para Aprovechar Oportunidades**
Frente al crecimiento del comercio local y el marketing de proximidad: Este es el momento ideal para que GeoPS se posicione como el líder del marketing de proximidad en el mercado peruano.

**Táctica:** Organizar webinars y talleres gratuitos dirigidos a dueños de PyMEs para educarlos sobre el marketing de proximidad y cómo pueden usar la plataforma para crecer.

**Táctica:** Crear un programa de referidos para que los negocios existentes reciban descuentos al invitar a otros a unirse a la plataforma, expandiendo la red de forma orgánica.

**3. Estrategias para Afrontar Amenazas**
Frente a la posible saturación y el surgimiento de nuevas apps: El riesgo de que el mercado se sature con ofertas irrelevantes es alto. GeoPS debe enfocarse en la calidad sobre la cantidad.

**Táctica:** Establecer criterios estrictos para los negocios que deseen unirse a la plataforma. Priorizar la calidad de las ofertas y la reputación de los negocios para mantener la confianza de los usuarios.

**Táctica:** Ofrecer herramientas de segmentación avanzadas para que los negocios publiquen ofertas ultra-específicas, evitando el "ruido" publicitario para el usuario final.

Frente a la preferencia por las apps nativas: Aunque GeoPS es web, puede ofrecer una experiencia muy similar a una app.

**Táctica:** Destacar las ventajas de no tener que descargar ni actualizar la aplicación. Usar mensajes como "Accede a ofertas al instante, sin descargas, sin ocupar memoria". Esto posiciona la plataforma como una solución ágil y moderna.

### 2.2. Entrevistas
  #### 2.2.1. Diseño de entrevistas

**Segmento 1: Dueños de negocios de diferentes rubros**

**Características demográficas:**
* ¿Cuál es tu edad?
* ¿De qué rubro es tu negocio?
* ¿Dónde se encuentra ubicado tu local principal?
  
**Preguntas principales:**
* ¿Cuál consideras que es el mayor reto para atraer nuevos clientes hoy en día?
* ¿Qué estrategias de promoción has usado antes? ¿Cuáles funcionaron y cuáles no?
* ¿Qué tan efectivas son para ti las redes sociales como canal publicitario?
* ¿Qué temores o barreras tienes al invertir en nuevas formas de publicidad?
* ¿Cómo mides actualmente si tu publicidad está funcionando?
* ¿Qué papel juegan las ofertas y descuentos en tu estrategia de ventas?
  
**Preguntas sobre el proyecto:**
  
* Si existiera una plataforma que conecte tu negocio con clientes cercanos, ¿qué funcionalidades te gustaría que tuviera?
* ¿Qué tipo de clientes te interesa atraer más (nuevos, frecuentes, turistas, vecinos)?
* ¿Qué tan dispuesto estarías a pagar por una herramienta digital que realmente te acerque a clientes locales?
* Si pudieras diseñar la aplicación perfecta para promocionar tu negocio, ¿qué funciones no podrían faltar?

**Segmento 2: Consumidores de ofertas de diferentes ámbitos**

**Características demográficas:**

* ¿Cuál es tu edad?
* ¿En qué distrito/ciudad vives?
* ¿Con qué frecuencia sueles buscar o aprovechar ofertas?
* ¿Qué tan familiarizado estás con el uso de plataformas digitales?
  
**Preguntas principales:**
  
* Cuéntame de la última vez que buscaste ofertas locales. ¿Cómo fue la experiencia?
* ¿Qué aspectos te resultan más molestos o poco prácticos en la forma en que te enteras de promociones hoy?
* ¿Qué tipo de publicidad sueles ignorar o rechazar? ¿Por qué?
* ¿Qué tan importante es para ti la facilidad y rapidez al encontrar una oferta?
* ¿Usas herramientas como Google Maps o redes sociales para decidir si visitar un local? ¿Por qué sí o por qué no?
* ¿Qué factores te hacen confiar o desconfiar de una promoción?
  
**Preguntas sobre el proyecto:**

* ¿Qué te gustaría que fuera diferente en la forma de recibir promociones cerca de ti?
* ¿Qué preocupaciones tendrías al compartir tu ubicación o datos personales en una app de este tipo? ¿Qué te daría seguridad?
* ¿Cómo sería para ti la experiencia ideal al descubrir ofertas en tu zona?

  #### 2.2.2. Registro de entrevistas

  ## Segmento 1: Dueños de negocios de diferentes rubros

| Número de registro | Datos del entrevistado | Captura |
|--------------------|-------------------------|---------|
| **1** | **Nombre:** Mirta <br> **Edad:** 57 años <br> **Distrito:** Jesús María <br> **Duración de la entrevista:** 5 minutos y 54 segundos <br> **Link:** [https://youtu.be/fC130lduBCM](https://youtu.be/fC130lduBCM) <br> **Resumen:** En esta entrevista, Mirta, una comerciante de 57 años, dueña de una piñatería, habla sobre los desafíos de su negocio, especialmente la promoción y la competencia. Menciona que utiliza redes sociales como Instagram y Facebook, pero que la clave para ella es el trato personalizado al cliente y las recomendaciones de boca en boca. Prefiere usar WhatsApp para comunicarse con sus clientes y valora la interacción directa. También expresa su interés en una herramienta digital que la conecte con clientes locales. | <p align="center"><img src="images for chapter ii/entrevista1_segmento1.png" alt="PI5" width="1000"></p> |
| **2** | **Nombre:** Kelly <br> **Edad:** 21 años <br> **Distrito:** Jesús María <br> **Duración de la entrevista:** 3 minutos y 8 segundos <br> **Link:** [https://youtu.be/k7YhV_pqApc](https://youtu.be/k7YhV_pqApc) <br> **Resumen:** En esta entrevista, Kelly, la dueña de una tienda de mascotas, de 21 años, comparte sus ideas sobre el marketing digital. Destaca que el mayor desafío es el uso de las redes sociales para atraer clientes, y que las ofertas como "compra uno y lleva uno gratis" han sido muy efectivas. También menciona que se están enfocando en TikTok para transmisiones en vivo, lo cual ha aumentado sus ventas y seguidores. Explica que miden el éxito de su publicidad directamente a través de las ventas y que buscan clientes recurrentes. Finalmente, describe una aplicación ideal que le gustaría para su negocio, con funciones para ver productos, ofertas y realizar compras desde casa. | <p align="center"><img src="images for chapter ii/entrevista2_segmento1.png" alt="PI5" width="1000"></p> |
| **3** | **Nombre:** Cesar <br> **Edad:** 50 años <br> **Distrito:** Miraflores <br> **Duración de la entrevista:** 3 minutos y 34 segundos <br> **Link:** [https://youtu.be/VHkTCRW2Igc](https://youtu.be/VHkTCRW2Igc) <br> **Resumen:** En este video, se entrevista al dueño de un negocio de comida. Habla sobre la efectividad del "boca a boca" y el uso de WhatsApp para las ventas. Mide el éxito de su promoción directamente a través de las ventas generadas por WhatsApp. Expresa interés en una plataforma digital para negocios locales que le permita mostrar sus platos con fotos y videos, y que le ayude a atraer clientes, especialmente turistas, ya que considera que tienen mayor poder adquisitivo. Además, está dispuesto a pagar por una aplicación si esta le garantiza la captación de clientes locales de manera efectiva. | <p align="center"><img src="images for chapter ii/entrevista3_segmento1.png" alt="PI5" width="1000"></p> |

  ## Segmento 2: Consumidores de ofertas de diferentes ámbitos

| Número de registro | Datos del entrevistado | Captura |
|--------------------|-------------------------|---------|
| **1** | **Nombre:** Andrés Torres <br> **Edad:** 19 años <br> **Distrito:** San Miguel <br> **Duración de la entrevista:** 3 minutos y 29 segundos <br> **Link:** [https://youtu.be/lss8fRI5_3g](https://youtu.be/lss8fRI5_3g) <br> **Resumen:** En este video, se entrevista a Andrés Torres, un joven de 19 años del distrito de San Miguel. Habla sobre cómo busca ofertas para el cine usando aplicaciones como Yape. Le molesta la publicidad intrusiva en la calle y en aplicaciones que no le interesa. Su confianza en las promociones depende de la reputación de la empresa, aunque también consideraría ofertas de empresas menos conocidas si tienen buena presentación. Andrés sugiere que las promociones deberían adaptarse a los intereses de los usuarios y que las aplicaciones deberían solicitar datos básicos a los creadores de los proyectos para generar mayor seguridad. | <p align="center"><img src="images for chapter ii/entrevista1_segmento2.png" alt="PI5" width="1000"></p> |
| **2** | **Nombre:** Ángel José <br> **Edad:** 22 años <br> **Distrito:** Cercado de Lima <br> **Duración de la entrevista:** 4 minutos y 47 segundos <br> **Link:** [https://youtu.be/s_zL-OGBqJE](https://youtu.be/s_zL-OGBqJE) <br> **Resumen:** En este video, Ángel José, de 22 años, del Cercado de Lima, comparte su experiencia buscando ofertas. Explica que usa plataformas como Yape, Instagram y Facebook. Le molesta tener que buscar manualmente y a menudo pide recomendaciones a conocidos. Desconfía de los descuentos muy altos que podrían ser estafas o productos falsos. Su experiencia ideal sería recibir notificaciones de ofertas que le interesen, que sean de locales conocidos y fáciles de canjear. Además, se sentiría seguro compartiendo sus datos si la empresa es profesional y cifra la información. | <p align="center"><img src="images for chapter ii/entrevista2_segmento2.png" alt="PI5" width="1000"></p> |
| **3** | **Nombre:** Elian <br> **Edad:** 25 años <br> **Distrito:** San Martín de Porres <br> **Duración de la entrevista:** 5 minutos y 10 segundos <br> **Link:** [https://youtu.be/h1kiEyQ9aIY](https://youtu.be/h1kiEyQ9aIY) <br> **Resumen:** En esta entrevista, Elian, de 25 años, del distrito de San Martín de Porres, habla sobre su experiencia con la búsqueda de ofertas en línea. Menciona que las páginas web no son fáciles de usar y le molesta la publicidad de ofertas que ya no están vigentes. Su principal interés es encontrar ofertas de manera rápida y fácil. Desconfía de las promociones "demasiado buenas para ser verdad" y sugiere que las plataformas deberían personalizar las ofertas según su historial de compras. No le preocupa compartir sus datos o ubicación, ya que es algo común en aplicaciones de entrega. Su experiencia ideal sería encontrar ofertas buenas y cercanas a su ubicación. | <p align="center"><img src="images for chapter ii/entrevista3_segmento2.png" alt="PI5" width="1000"></p> |

  #### 2.2.3. Análisis de entrevistas

*Segmento 1: Dueños de negocios de diferentes rubros*

A partir de las entrevistas a tres dueños de negocios, de edades y rubros variados, podemos extraer las siguientes conclusiones:

**a) La tecnología es una herramienta de apoyo, no un reemplazo de las estrategias tradicionales.** El 100% de los entrevistados (Mirta, Kelly y Cesar) enfatiza la importancia del contacto personal y el "boca a boca". Aunque todos usan plataformas digitales (WhatsApp, Facebook, Instagram, TikTok), lo hacen para complementar sus métodos tradicionales, como el trato personalizado o la venta directa. Esto demuestra que valoran la conexión humana tanto o más que las herramientas digitales.

**b) Existe una clara y urgente necesidad de una plataforma digital centralizada y adaptada a negocios locales.** El 100% de los entrevistados expresa su interés en una herramienta digital que resuelva problemas específicos. Mirta busca una que la conecte con clientes locales, Kelly describe una app ideal para mostrar productos y gestionar ventas, y Cesar menciona que pagaría por una solución que le garantice la captación de clientes de su zona. Esto evidencia que los dueños de negocios están buscando una solución que vaya más allá de las redes sociales genéricas, y que les ofrezca funcionalidades específicas para su tipo de negocio.

**c) El éxito del marketing digital se mide directamente en ventas, no en interacciones superficiales.** El 100% de los entrevistados evalúa la efectividad de sus esfuerzos de promoción en función de los resultados tangibles. Kelly y Cesar mencionan explícitamente que miden su éxito a través de las ventas generadas por WhatsApp, y Mirta se enfoca en que sus acciones de marketing se traduzcan en nuevas recomendaciones. Esto indica que para este segmento, el objetivo principal de cualquier herramienta digital es el crecimiento de los ingresos.

*Segmento 2: Consumidores de ofertas de diferentes ámbitos*

A partir de de las entrevistas a tres jóvenes consumidores de ofertas, podemos extraer las siguientes conclusiones:

**a) Existe una desconfianza generalizada hacia la publicidad intrusiva y las ofertas poco realistas.** Un 100% de los entrevistados (Andrés, Ángel y Elian) manifiesta su rechazo a las estrategias de marketing que no son de su interés. Andrés detesta la publicidad en la calle, Ángel desconfía de los descuentos "muy llamativos" que parecen estafas, y a Elian le molesta la publicidad de ofertas ya caducadas. Esto demuestra que este segmento prefiere la proactividad de buscar sus propias ofertas en plataformas que confían en vez de ser interrumpidos por información irrelevante o sospechosa.

**b) La conveniencia, la relevancia y la personalización son elementos clave para la adopción de plataformas de ofertas.** El 100% de los entrevistados valora la facilidad de uso y la personalización. Andrés sugiere que las promociones se adapten a sus intereses, mientras que Elian desearía ofertas personalizadas basadas en su historial de compras, similar a TikTok. Ángel, por su parte, busca recibir notificaciones de ofertas que le interesen sin tener que buscar manualmente. Para este segmento, una experiencia ideal no implica buscar constantemente, sino que las ofertas adecuadas "lleguen a ellos" de manera organizada y relevante.

**c) La seguridad y la transparencia son esenciales para generar confianza.** Dos de los tres entrevistados (Andrés y Ángel) mencionan la importancia de la confianza. Andrés afirma que la reputación de la empresa es crucial y sugiere que las aplicaciones deberían solicitar datos a los creadores para generar seguridad. Ángel se sentiría seguro compartiendo sus datos si la empresa es profesional y cifra la información. Por otro lado, Elian, que no tiene preocupaciones sobre compartir datos en aplicaciones de entrega, muestra que la confianza se puede construir si la plataforma es conocida y tiene un historial de uso común, como un app de delivery. Esto demuestra que este segmento tiene un nivel de conciencia sobre la seguridad de sus datos y que la transparencia es fundamental para que se sientan cómodos usando una plataforma de ofertas.

### 2.3. Needfinding
  #### 2.3.1. User Personas
  #### 2.3.2  User Task Matrix
  #### 2.3.3. User Journey Mapping
  #### 2.3.4. Empathy Mapping
  #### 2.3.5. As-is Scenario Mapping
### 2.4. Ubiquitous Language   

## Capitulo 3: Requirements Specification 
### 3.1. To-Be Scenario Mapping
### 3.2. User Stories
### 3.3. Impact Mapping
### 3.4. Product Backlog

## Capítulo 4: Product Design
### 4.1. Style Guidelines
  #### 4.1.1. General Style Guidelines  
  #### 4.1.2. Web Style Guidelines
### 4.2. Information Architecture
  #### 4.2.1. Organization Systems 
  #### 4.2.2. Labeling Systems 
  #### 4.2.3. SEO Tags and Meta Tags
  #### 4.2.4. Searching Systems
  #### 4.2.5. Navigation Systems  
### 4.3. Landing Page UI Design
  #### 4.3.1. Landing Page Wireframe  
  #### 4.3.2. Landing Page Mock-up 
### 4.4. Web Applications UX/UI Design
  #### 4.4.1. Web Applications Wireframes  
  #### 4.4.2. Web Applications Wireflow Diagrams  
  #### 4.4.3. Web Applications Mock-ups  
  #### 4.4.4. Web Applications User Flow Diagrams  
### 4.5. Web Applications Prototyping.
### 4.6. Domain-Driven Software Architecture
  #### 4.6.1. Software Architecture Context Diagram  
  #### 4.6.2. Software Architecture Container Diagrams  
  #### 4.6.3. Software Architecture Components Diagrams
### 4.7. Software Object-Oriented Design
  #### 4.7.1. Class Diagrams  
  #### 4.7.2. Class Dictionary 
### 4.8. Database Design
  #### 4.8.1. Database Diagram 

  ## Capítulo 5: Product Implementation, Validation & Deployment
### 5.1. Software Configuration Management
  #### 5.1.1. Software Development Environment Configuration  
  #### 5.1.2. Source Code Management  
  #### 5.1.3. Source Code Style Guide & Conventions  
  #### 5.1.4. Software Deployment Configuration
### 5.2. Landing Page, Services & Applications Implementation
### 5.2.1. Sprint 1
#### 5.2.1.1. Sprint Planning 1  
#### 5.2.1.2. Aspect Leaders and Collaborators  
#### 5.2.1.3. Sprint Backlog 1  
#### 5.2.1.4. Development Evidence for Sprint Review  
#### 5.2.1.5. Execution Evidence for Sprint Review  
#### 5.2.1.6. Services Documentation Evidence for Sprint Review  
#### 5.2.1.7. Software Deployment Evidence for Sprint Review  
#### 5.2.1.8. Team Collaboration Insights during Sprint

## Conclusiones
## Anexos
## Bibliografía
