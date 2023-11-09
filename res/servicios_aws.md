# Servicios aws

- [**Indice**](#)
  - [Analytics](#Analytics)
    - [Amazon Athena](#Amazon-Athena)
    - [Amazon CloudSearch](#Amazon-CloudSearch)
    - [Amazon Elasticsearch Service](#Amazon-Elasticsearch-Service)
    - [Amazon EMR](#Amazon-EMR)
    - [Amazon FinSpace](#Amazon-FinSpace)
    - [Amazon Kinesis](#Amazon-Kinesis)
    - [Amazon Redshift](#Amazon-Redshift)
    - [Amazon QuickSight](#Amazon-QuickSight)
    - [AWS Data Exchange](#AWS-Data-Exchange)
    - [AWS Data Pipeline](#AWS-Data-Pipeline)
    - [AWS Glue](#AWS-Glue)
    - [AWS Lake Formation](#AWS-Lake-Formation)
    - [Amazon Managed Streaming for Apache Kafka (Amazon MSK)](#Amazon-Managed-Streaming-for-Apache-Kafka)
  - [Compute Services](#Compute-Services)
  - [Management and Governance](#Management&Governance)
    - [Amazon CloudWatch](#Amazon-CloudWatch)
    - [AWS Auto Scaling](#AWS-Auto-Scaling)
    - [AWS Chatbot](AWS-Chatbot)
    - [AWS Compute Optimizer](AWS-Compute-Optimizer)
    - [AWS Control Tower](AWS-Control-Tower)
    - [AWS CloudFormation](AWS-CloudFormation)
    - [AWS CloudTrail](AWS-CloudTrail)
    - [AWS Config](AWS-Config)
    - [AWS Launch Wizard](AWS-Launch-Wizard)
    - [AWS Organizations](AWS-Organizations)
    - [AWS OpsWorks](AWS-OpsWorks)
    - [AWS Proton](AWS-Proton)
    - [AWS Service Catalog](AWS-Service-Catalog)
    - [AWS Systems Manager](AWS-Systems-Manager)
    - [AWS Trusted Advisor](AWS-Trusted-Advisor)
    - [AWS Personal Health Dashboard](AWS-Personal-Health-Dashboard)
    - [AWS Managed Services](AWS-Managed-Services)
    - [AWS Console Mobile Application](AWS-Console-Mobile-Application)
    - [AWS Console Mobile Application](AWS-Console-Mobile-Application)
    - [AWS License Manager](AWS-License-Manager)
    - [AWS Well-Architected Tool](AWS-Well-Architected-Tool)  
    - [AWS Application Migration Service](#AWS-Application-Migration-Service)
    - [AWS Migration Hub](#AWS-Migration-Hub)
    - [AWS Application Discovery Service](#AWS-Application-Discovery-Service)
  - [Developer Tools](#Developer-Tools)
    - [Amazon Corretto](Amazon-Corretto)
    - [AWS Cloud9](AWS-Cloud9)
    - [AWS CloudShell](AWS-CloudShell)
    - [AWS CodeArtifact](AWS-CodeArtifact)
    - [AWS CodeBuild](AWS-CodeBuild)
    - [AWS CodeCommit](AWS-CodeCommit)
    - [AWS CodeDeploy](AWS-CodeDeploy)
    - [AWS CodePipeline](AWS-CodePipeline)
    - [AWS CodeStar](AWS-CodeStar)
    - [AWS Fault Injection Simulator](AWS-Fault-Injection-Simulator)
    - [AWS X-Ray](AWS-X-Ray)
  - [Database](#database)
    - [Amazon Aurora](#Amazon-Aurora)
    - [Amazon DynamoDB](#Amazon-DynamoDB)
    - [Amazon ElastiCache](#Amazon-ElastiCache)
    - [Amazon Keyspaces](#Amazon-Keyspaces)
    - [Amazon Neptune](#Amazon-Neptune)
    - [Amazon RDS](#Amazon-RDS)
    - [Amazon Quantum Ledger Database](#Amazon-Quantum-Ledger-Database)
    - [Amazon  Timestream](#Amazon-Timestream)
    - [Amazon DocumentDB](#Amazon-DocumentDB)
  - [Migration and Transfer](#Migration-and-Transfer)
    - [AWS Application Migration Service](#AWS-Application-Migration-Service)
    - [AWS Migration Hub](#AWS-Migration-Hub)
    - [AWS Application Discovery Service](#AWS-Application-Discovery-Service)
    - [AWS Database Migration Service](#AWS-Database-Migration-Service)
    - [AWS Server Migration Service](#AWS-Server-Migration-Service)
    - [AWS Snow Family](#AWS-Snow-Family)
    - [AWS DataSync](#AWS-DataSync)
    - [AWS Transfer Family](#AWS-Transfer-Family)  
  - [Networking and Content Delivery](#Networking-and-Content-Delivery)
    - [Amazon API Gateway](#Amazon-API-Gateway)
    - [Amazon CloudFront](#Amazon-CloudFront)
    - [Amazon Route 53](#Amazon-Route-53)
    - [Amazon VPC](#Amazon-VPC)
    - [AWS App Mesh](#AWS-App-Mesh)
    - [AWS Cloud Map](#AWS-Cloud-Map)
    - [AWS Direct Connect](#AWS-Direct-Connect)
    - [AWS Global Accelerator](#AWS-Global-Accelerator)
    - [AWS PrivateLink](#AWS-PrivateLink)
    - [AWS Transit Gateway](#AWS-Transit-Gateway)
    - [AWS  VPN](#AWS-VPN)
    - [Elastic Load Balancing](#Elastic-Load-Balancing)
  - [Security, Identity, and Compliance](#Security-Identity-and-Compliance)
    - [Amazon Cognito](#Amazon-Cognito)
    - [Amazon Cloud Directory](#Amazon-Cloud-Directory)
    - [Amazon Detective](#Amazon-Detective)
    - [Amazon GuardDuty](#Amazon-GuardDuty)
    - [Amazon Inspector](#Amazon-Inspector)
    - [Amazon Macie](#Amazon-Macie)
    - [AWS Artifact](#Aws-Artifact)
    - [AWS Audit Manager](#AWS-Audit-Manager)
    - [AWS Certificate Manager](#AWS-Certificate-Manager)
    - [AWS CloudHSM](#AWS-MacCloudHSM)
    - [AWS Directory Service](#AWS-Directory-Service)
    - [AWS Firewall Manager](#AWS-Firewall-Manager)
    - [AWS Identity and Access Management](#AWS-Identity-and-Access-Management)
    - [AWS Key Management Service](#AWS-Key-Management-Service)
    - [AWS Network Firewall](#AWS-Network-Firewall)
    - [AWS Resource Access Manager](#AWS-Resource-Access-Manager)
    - [AWS Secrets Manager](#AWS-Secrets-Manager)
    - [AWS Security Hub](#AWS-Security-Hub)
    - [AWS Shield](#AWS-Shield)
    - [AWS Single Sign On](#AWS-Single-Sign-On)
    - [AWS Waf](#AWS-Waf)
  - [Storage](#Storage)
    - [Amazon Elastic Block Store ](#Amazon-Elastic-Block-Store)
    - [Amazon Elastic File System ](#Amazon-Elastic-File-System)
    - [Amazon FSx for Lustre ](#Amazon-FSx-for-Lustre)
    - [Amazon FSx for Windows File Server](#Amazon-FSx-for-Windows-File-Server)
    - [Amazon Simple Storage Service ](#Amazon-Simple-Storage-Service-S3)
    - [Amazon S3 Glacier ](#Amazon-S3-Glacier)
    - [AWS Backup ](#AWS-Backup)
    - [AWS Storage Gateway ](#AWS-Storage-Gateway)
    <br>

  ## **Analytics**

    ### Amazon Athena
    > servicio de consulta interactivo que facilita el análisis de datos en Amazon S3 utilizando SQL estándar

    ### Amazon CloudSearch
    > servicio administrado en la nube de AWS que puedes configurar, administrar y escalar una solución de búsqueda para su sitio web o aplicación

    ### Amazon Elasticsearch Service
    > buscar, analizar y visualizar datos en tiempo real
    Se integra con herramientas de codigo abierto como Kibana y Logstash ademas 
    con otros servicios de AWS VPC, KMS, lambda, IAM

    ### Amazon EMR
    > plataforma de big data en la nube líder en la industria para procesar grandes cantidades de datos utilizando herramientas de código abierto como Apache Spark, Colmena, hbase, flink, hudi y Presto

    ### Amazon FinSpace
    > servicio de análisis y gestión de datos diseñado específicamente para la industria de servicios financieros **(FSI)** incluye una biblioteca de más de 100 funciones, como barras de tiempo y bandas de Bollinger

    ### Amazon Kinesis
    > puede ingerir datos en tiempo real, como videos, audio, registros de aplicaciones, secuencias de clics en sitios web y datos de telemetría de IoT para aprendizaje automático, análisis y otras aplicaciones para responder instantáneamente, ofrece 4 servicios: 
    > - `K Data Firehose` servicio administrado capturar, puede procesar por lotes, comprimir, transformar y cifrar los datos antes de cargarlos de transmisión en Amazon S3, Amazon Redshift, Amazon Elasticsearch Service y Splunk
    > - `K Data Analytics` Los usuarios de SQL pueden consulta utilizando plantillas y un editor SQL interactivo
    Los desarrolladores de Java pueden crear aplicaciones de transmisión para transformar y analizar
    > - `K Data Streams` Los datos recopilados están disponibles en milisegundos para permitir casos de uso de análisis en tiempo real, como paneles de control, detección de anomalías, precios dinámicos y más.
    > - `K Video Streams` análisis, aprendizaje automático (ML), reproducción ... y  mediante la integración con Amazon Rekognition Video y bibliotecas para marcos de aprendizaje automático como Apache MxNet, TensorFlow y OpenCV. .

    ### Amazon Redshift
    > almacén de datos en la nube puedes analizar sus datos utilizando SQL estándar y sus herramientas de Business Intelligence (BI) existentes
    consultas analíticas TB, PB de datos estructurados

    ### Amazon QuickSight
    > servicio de inteligencia empresarial (BI) basado en la nube, permite crear y publicar paneles interactivos a los que se puede acceder desde navegadores o dispositivos móviles

    ### AWS Data Exchange
    > Suscripcion y uso de datos de terceros, cargarlos en s3 y analizarlso 

    ### AWS Data Pipeline
    > servicio web que le ayuda a procesar y mover datos de forma fiable entre diferentes servicios informáticos y de almacenamiento de AWS, así como fuentes de datos locales, en intervalos específicos

    ### AWS Glue
    > descubre sus datos y almacena los metadatos asociados (por ejemplo, definición de tabla y esquema) en el catálogo de datos de AWS Glue. Una vez catalogados, sus datos se pueden buscar, consultar y disponibles de inmediato para ETL.

    ### AWS Lake Formation
    > configuración de un lago de datos seguro en días. Un lago de datos es un repositorio centralizado, curado y seguro que almacena todos sus datos, tanto en su forma original como preparados para el análisis

    ### Amazon Managed Streaming for Apache Kafka
    > servicio totalmente administrado que aprovisiona y ejecuta automáticamente sus clústeres de Apache Kafka. Amazon MSK monitorea continuamente el estado del clúster y reemplaza automáticamente los nodos en mal estado sin tiempo de inactividad para su aplicación. Además, Amazon MSK protege su clúster de Apache Kafka cifrando los datos en reposo

    <br> 

  ## **Management and Governance**

    ### Amazon CloudWatch
    > Servicio de monitoreo y administración, configurar alarmas de alta resolución, visualizar registros y métricas en paralelo, tomar decisiones automatizadas

    ### AWS Auto Scaling
    > proporciona una interfaz de usuario sencilla y potente que le permite crear planes de escalamiento para recursos (EC2, dynamoDB, Aurora)

    ### AWS CloudFormation
    > crear y administrar una colección de recursos de AWS relacionados, aprovisionándolos y actualizándolos de manera ordenada y predecible

    ### AWS CloudTrail
    > servicio web que registra las llamadas a la API de AWS para su cuenta y le entrega archivos de registro    

    ### AWS Config
    > servicio administrado que proporciona un inventario de recursos de AWS, un historial de configuración y notificaciones de cambios de configuración para habilitar la seguridad y la gobernanza
    permite crear reglas que verifican automáticamente la configuración de los recursos de AWS registrados por AWS Config

    ### AWS Organizations
    > administrar y gobernar de forma centralizada su entorno, crear y agrupar nuevas cuentas de AWS y simplificar la facturacion

    ### AWS Service Catalog
    > permite a las organizaciones crear y administrar catálogos de servicios de TI aprobados para su uso en AWS

    ### AWS Trusted Advisor
    >  recurso en línea que le ayudará a reducir costos, aumentar el rendimiento y mejorar la seguridad optimizando su entorno de AWS

    ### AWS Well-Architected Tool
    >  revisar el estado de sus cargas de trabajo y las compara con las mejores prácticas arquitectónicas de AWS más recientes

    <br>

  ## **Developer Tools**

    ### Amazon Corretto
    > distribución gratuita, multiplataforma y lista para producción del Open Java Development Kit (OpenJDK)

    ### AWS Cloud9
    > entorno de desarrollo integrado (IDE) basado en la nube, puede compartir rápidamente su entorno de desarrollo con su equipo

    ### AWS CloudShell
    > shell basado en navegador, puede ejecutar scripts con la interfaz de línea de comandos de AWS (AWS CLI)

    ### CodeArtifact
    > servicio de repositorio de artefactos totalmente administrado que facilita a las organizaciones de cualquier tamaño almacenar, publicar y compartir de forma segura paquetes de software utilizados en su proceso de desarrollo de software

    ### CodeBuild
    > servicio de compilación totalmente administrado que compila código fuente, ejecuta pruebas y produce paquetes de software que están listos para implementar

    ### CodeCommit
    > servicio de control de código fuente totalmente administrado que facilita a las empresas alojar repositorios Git privados seguros y altamente escalables

    ### CodeDeploy
    > servicio que automatiza las implementaciones de código en cualquier instancia

    ### CodePipeline
    > servicio de entrega continua totalmente administrado, puede integrar fácilmente CodePipeline con servicios de terceros como GitHub 

    ### CodeStar
    > proporciona una interfaz de usuario unificada que le permite administrar fácilmente sus actividades de desarrollo de software 

    ### Fault Injection Simulator
    > servicio totalmente administrado para ejecutar experimentos de inyección de fallas en AWS 

    ### AWS X-Ray
    > Con X-Ray, puede comprender cómo se están desempeñando su aplicación y sus servicios subyacentes para poder identificar y solucionar la causa raíz de los problemas y errores de rendimiento

    <br>

  ## Containers

    ### Amazon Elastic Container Registry
    > (ECR) es un registro de contenedores Docker completamente administrado
    ECR aloja sus imágenes en una arquitectura escalable y de alta disponibilidad
    integrado en (ECS) y (IAM)

    ### Amazon Elastic Container Service 
    > servicio de orquestación de contenedores altamente escalable y de alto rendimiento

    ### Amazon Elastic Kubernetes Service
    > (Amazon EKS) facilita la implementación, administración y escalado de aplicaciones en contenedores utilizando Kubernetes en AWS
    ejecuta la infraestructura en múltiples zonas de disponibilidad
    certificación de conformidad con Kubernetes

    ### AWS App2Container
    > (A2C) es una herramienta de línea de comandos para modernizar aplicaciones .NET y Java en aplicaciones en contenedores

    ### Red Hat OpenShift Service on AWS


  ## **Database**

    ### Amazon Aurora
    > motor de base de datos relacional compatible con MySQL y PostgreSQL
    5 veces más rápido que las bases de datos MySQL estándar
    3 veces más rápido que las bases de datos PostgreSQL estándar
    administrado por Amazon Relational Database Service (Amazon RDS)
    escala automáticamente hasta 128 TB por instancia de base de datos
    replicación en tres zonas de disponibilidad (AZ)

    ### Amazon DynamoDB 
    > es una base de datos de documentos y valores clave 
    10 billones de solicitudes por día y soportar picos de más de 20 millones de solicitudes por segundo

    ### Amazon ElastiCache 
    > servicio web que facilita la implementación, operación y escalado de una caché en memoria en la nube,  admite dos motores de almacenamiento en caché en memoria de código abierto:
    > - `Redis:` almacén de datos clave-valor en memoria, rápido, de código abierto y para usar como base de datos, caché y mensajes. Están disponibles clústeres de un solo nodo y de hasta 15 fragmentos, lo que permite una escalabilidad de hasta 3,55 TiB de datos en memori
    > - `Memcache:` sistema de almacenamiento en caché de objetos de memoria ampliamente adoptado

    ### Amazon Keyspaces
    > servicio de base de datos compatible con Apache Cassandra, escalable, de alta disponibilidad y administrado, datos están cifrados de forma predeterminada

    ### Amazon Neptune
    > servicio de base de datos de gráficos rápido, confiable y totalmente administrado, admite los modelos de gráficos populares Property Graph y RDF del W3C, y sus respectivos lenguajes de consulta Apache TinkerPop Gremlin y SPARQ

    ### Amazon RDS
    > proporciona seis motores de bases de datos, Amazon Aurora, PostgreSQL, mysql, MaríaDB, base de datos oracle, y servidor SQL

    ### Amazon Quantum Ledger Database 
    > (QLDB) es una base de datos contable totalmente administrada que proporciona un registro de transacciones transparente, inmutable y criptográficamente verificable propiedad de una autoridad central confiable, realiza un seguimiento de todos y cada uno de los cambios en los datos de las aplicaciones y mantiene un historial completo inmutable y verificable
    elimina la necesidad de desarrollar sus propias aplicaciones tipo libro mayor

    ### Amazon  Timestream 
    > servicio de base de datos de series temporales rápido, escalable y totalmente administrado para IoT y aplicaciones operativas que facilita el almacenamiento y análisis de billones de eventos por día
    puede almacenar y analizar fácilmente datos de registros para DevOps, datos de sensores para aplicaciones de IoT y datos de telemetría industrial para mantenimiento de equipos

    ### Amazon DocumentDB 
    > (with MongoDB compatibility) operar cargas de trabajo de MongoDB implementa las API MongoDB 3.6 y 4.0 de código abierto de Apache 2.0

    <br>

  ## **Migration and Transfer**

    ### AWS Application Migration Service
    ### AWS Migration Hub
    ### AWS Application Discovery Service
    ### AWS Database Migration Service

    ### AWS Server Migration Service
    > (SMS) permite automatizar, programar y realizar un seguimiento de replicaciones incrementales de volúmenes de servidores activos

    ### AWS Snow Family

    > - `AWS Snowcone` 8TB por dispositivo, múltiples capas de seguridad y cifrado
    > - `AWS Snowball` admite tipos de instancias de Amazon EC2 específicos y funciones de AWS Lambda, puede desarrollar y probar en la nube de AWS y luego implementar aplicaciones en dispositivos en ubicaciones remotas para recopilar, preprocesar y enviar los datos a AWS
    > - `AWS Snowmobile`: 100 PB por contenedor, cifrado de 256 bits administradas a  través de AWS KMS, personal de seguridad, rastreo por GPS, monitoreo de alarmas, videovigilancia y vehículo de escolta opcional

    ### AWS DataSync
    > servicio de transferencia de datos que le facilita la automatización de la transferencia de datos entre el almacenamiento local y Amazon S3 o Amazon Elastic File System (Amazon EFS)
    DataSync utiliza un agente de software local para conectarse a sus sistemas de archivos o almacenamiento existentes mediante el protocolo Network File System **(NFS)**

    ### AWS Transfer Family
    > soporte totalmente administrado para transferencias de archivos directamente hacia y desde Amazon S3 o Amazon EFS
    Protocolo seguro de transferencia de archivos **(SFTP)**, el Protocolo de transferencia de archivos sobre SSL **(FTPS)** y el Protocolo de transferencia de archivos **(FTP)**

    <br>   

  ## **Networking and Content Delivery**
    
    ### Amazon API Gateway
    > servicio totalmente administrado que facilita a los desarrolladores la creación, publicación, mantenimiento, monitoreo y protección de API a cualquier escala

    ### Amazon CloudFront
    > servicio rápido de red de entrega de contenido (CDN) que entrega de forma segura datos, videos, aplicaciones y API a clientes de todo el mundo con baja latencia y altas velocidades de transferencia

    ### Amazon Route 53
    > servicio web de sistema de nombres de dominio (DNS) en la nube altamente disponible y escalable
    configurar comprobaciones de estado de DNS para enrutar el tráfico a puntos finales o monitorear de forma independiente el estado de su aplicación y sus puntos finales
    también ofrece registro de nombres de dominio

    ### Amazon VPC
    > permite aprovisionar una sección lógicamente aislada de la nube de AWS donde puede lanzar recursos de AWS en una red virtual que usted defina

    ### AWS App Mesh
    > supervisión y el control de los microservicios ejecutándose en AWS
    configura cada microservicio para exportar datos de monitoreo e implementa una lógica de control de comunicaciones consistente en toda su aplicación

    ### AWS Cloud Map
    > permite registrar cualquier recurso de aplicación, como bases de datos, colas, microservicios y otros recursos de la nube con nombres personalizados
    verifica constantemente el estado y consultar el registro para conocer la ubicación de los recursos necesarios según la versión de la aplicación y el entorno de implementación

    ### AWS Direct Connect
    > establecimiento de una conexión de red dedicada desde sus instalaciones a AWS

    ### AWS Global Accelerator
    > servicio de red que mejora la disponibilidad y el rendimiento de las aplicaciones que ofrece a sus usuarios globales
    administración de sus aplicaciones globales al proporcionar direcciones IP estáticas, elimina la complejidad de administrar direcciones IP específicas para diferentes regiones y zonas de disponibilidad de AWS

    ### AWS PrivateLink
    > AWS PrivateLink proporciona conectividad privada entre VPC, servicios de AWS y aplicaciones locales, de forma segura en la red de Amazon

    ### AWS Transit Gateway
    > servicio que permite a los clientes conectar sus nubes privadas virtuales (VPC) de Amazon y sus redes locales a una única puerta de enlace

    ### AWS VPN
    > Las soluciones establecen conexiones seguras entre sus redes locales, oficinas remotas, dispositivos de clientes y la red global de AWS
    > - `AWS Site-to-Site VPN` crea túneles cifrados entre su red y sus Amazon Virtual Private Clouds o AWS Transit Gateways
    > -  `AWS Client VPN` conecta a sus usuarios con AWS o con recursos locales mediante un cliente de software VPN.

    ### Elastic Load Balancing
    > (ELB) Distribuye automáticamente el tráfico entrante de aplicaciones entre múltiples destinos, como instancias, contenedores y direcciones IP de Amazon EC2
    > - `de aplicaciones` adecuado para el equilibrio de carga del tráfico HTTP y HTTPS
    operar a nivel de solicitud individual (Capa 7)
    > - `del trafico (TCP)` (Network Load B) enruta el trafico a objetos dentro de VPC
    opera a nivel de conexion (capa 4)
    > - `de Gateway` implementación, ampliación y ejecución de redes virtuales de terceros
    > - `de carga clasico` equilibrio de carga básico entre múltiples instancias de Amazon EC2 y opera tanto a nivel de solicitud como de conexión

    <br>

  ## **Security, Identity, and Compliance**

    ### Amazon Cognito
    > permite agregar registro de usuario, inicio de sesión y control de acceso a sus aplicaciones permite guardar datos localmente en los dispositivos de los usuarios y luego sincronizar datos

    ### Amazon Cloud Directory
    > permite crear directorios flexibles nativos de la nube para organizar jerarquías de datos en múltiples dimensiones

    ### Amazon Detective
    > análisis, investigación y identificación de posibles problemas de seguridad o actividades sospechosas

    ### Amazon GuardDuty
    > monitorea continuamente comportamientos maliciosos o no autorizados
    envía una alerta a la consola GuardDuty y a Amazon CloudWatch Events

    ### Amazon Inspector
    > evaluación de seguridad automatizado ayuda cumplimiento de las aplicaciones implementadas en AWS

    ### Amazon Macie
    > aprendizaje automático para descubrir, clasificar y proteger automáticamente datos confidenciales en AWS

    ### AWS Artifact
    > proporciona acceso bajo demanda a los informes de seguridad y cumplimiento de AWS y a acuerdos en línea seleccionados

    ### AWS Audit Manager
    > ayuda a auditar continuamente su uso de AWS para evaluar el riesgo y el cumplimiento de las regulaciones y estándares de la industria

    ### AWS Certificate Manager
    > le permite aprovisionar, administrar e implementar fácilmente Secure Sockets Certificados de seguridad de capa/capa de transporte (SSL/TLS) para usar con servicios de AWS y su información interna

    ### AWS CloudHSM
    > módulo de seguridad de hardware (HSM) basado en la nube que le permite generar y utilizar fácilmente sus propias claves de cifrado en la nube de AWS

    ### AWS Directory Service
    > AWS Managed Microsoft AD, permite que sus cargas de trabajo con reconocimiento de directorio y recursos de AWS 

    ### AWS Firewall Manager
    > configuración y administración centralizada de las reglas de AWS WAF en sus cuentas y aplicaciones para sus balanceadores de carga y distribuciones de Amazon CloudFront

    ### AWS Identity and Access Management
    > (IAM) le permite controlar de forma segura el acceso a los servicios y recursos de AWS para sus usuarios
    >> - crear usuarios en IAM, asignarles seguridad individual
    >> - crear roles en IAM y administrar permisos para controlar qué operaciones puede realizar la entidad o servicio de AWS que asume el rol
    >> - permitir que las identidades existentes (usuarios, grupos y roles) en su empresa accedan a la Consola de administración de AWS, llamen a las API de AWS y accedan a los recursos, sin la necesidad de crear un usuario de IAM para cada identidad.

    ### AWS Key Management Service
    > (KMS) creación y administración de claves y el control del uso del cifrado en una amplia gama de servicios de AWS y en sus aplicaciones
    utiliza módulos de seguridad de hardware validados por FIPS 140-2
    integrado con AWS CloudTrail

    ### AWS Network Firewall
    > servicio administrado que facilita la implementación de protecciones de red esenciales para todas sus nubes privadas virtuales (VPC) de Amazon
    permite definir reglas de firewall que le brindan un control detallado sobre el tráfico de la red, como el bloqueo de solicitudes salientes de bloques de mensajes del servidor (SMB)
    filtrado web que puede detener el tráfico a URL incorrectas conocidas y monitorear nombres de dominio completos
    crear o importar sus reglas de firewall, agrúpelas en políticas y aplíquelas a las VPC que desea proteger, el precio se basa en la cantidad de firewalls implementados y la cantidad de tráfico inspeccionado

    ### AWS Resource Access Manager
    > (RAM) compartir de forma segura sus recursos entre cuentas de AWS
    compartir gateways de tránsito, subredes, configuraciones de licencia de AWS License Manager, reglas de Amazon Route 53 Resolver y más tipos de recursos.

    ### AWS Secrets Manager
    > proteger los secretos necesarios para acceder a sus aplicaciones, servicios y recursos de TI
    permite rotar, administrar y recuperar fácilmente credenciales de bases de datos, claves API y tokens OAuth
    ofrece rotación de secretos con integración integrada para Amazon RDS para MySQL, PostgreSQL y Amazon Aurora

    ### AWS Security Hub
    > agrega, organiza y prioriza sus alertas de servicios como Amazon GuardDuty, Amazon Inspector y Amazon Macie

    ### AWS Shield
    > servicio de protección administrado de denegación de servicio distribuido (DDoS)
    >> - `AWS Shield Standard` protege contra los ataques DDoS más comunes y frecuentes de la capa de transporte y de red que tienen como objetivo su sitio web o sus aplicaciones  con Amazon CloudFront y Amazon Route 53, recibirá protección integral de disponibilidad contra todos los ataques conocidos a la infraestructura (Capas 3 y 4)
    >> - `AWS Shield Advanced` proporciona detección y mitigación adicionales contra ataques DDoS grandes y sofisticados, visibilidad de los ataques casi en tiempo real e integración con AWS WAF, un firewall de aplicaciones web, tambien  brinda acceso las 24 horas, los 7 días de la semana al equipo de respuesta DDoS (DRT) de AWS

    ### AWS Single Sign On
    > (SSO) administración centralizada del acceso SSO a múltiples cuentas de AWS y aplicaciones comerciales, incluye integraciones SAML

    ### AWS Waf
    > control sobre qué tráfico permitir o bloquear en su aplicación web mediante la definición de reglas de seguridad web personalizables como inyección SQL o secuencias de comandos entre sitios

    <br>

  ## **Storage**
    EBS, EFS, FSx, FSx Win, s3, glacier

    ### Amazon Elastic Block Store 
    > Volúmenes de almacenamiento en bloque persistentes para su uso con instancias Amazon EC2 Cada volumen se replica automáticamente dentro de su zona de disponibilidad 

    ### Amazon Elastic File System
    > sistema de archivos escalable y elástico para cargas de trabajo basadas en Linux para su uso con servicios de AWS y recursos locales

    ### Amazon FSx for Lustre
    > sistema de archivos optimizado para cargas de trabajo con uso intensivo de computación, se integra con S3 a través de Amazon Direct Connect o VPN

    ### Amazon FSx for Windows File Server
    > sistema de archivos nativo de Microsoft Windows

    ### Amazon Simple Storage Service S3
    > almacenamiento de objetos que ofrece escalabilidad, disponibilidad de datos, seguridad y rendimiento. durabilidad del 99,999999999 % (11 9)

    ### Amazon S3 Glacier
    > almacenamiento seguro, duradero y de costo extremadamente bajo para archivar datos y realizar copias de seguridad a largo plazo

    ### AWS Backup
    > permite centralizar y automatizar la protección de datos en todos los servicios de AWS

    ### AWS Storage Gateway
    > almacenamiento híbrido que permite que sus aplicaciones locales utilicen sin problemas el almacenamiento en la nube de AWS

    