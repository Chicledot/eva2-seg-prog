# eva2-seg-prog
Repositorio para evaluaciones de AIEP: Clases de programacion segura.

-¿Qué es OWASP y cuál es su principal objetivo?
El OWASP (Open Web Aplication Security Project) es una organización sin fines de lucro,
el cual su principal objetivo es mejorar la seguridad del software, con enfasis en la transparencia,
para que las organizaciones y comunidades tomen decisiones informadas.

-¿Qué es el OWASP Top 10 y por qué es importante para los desarrolladores?
Es un documento que describe los dies riezgos de seguridad más importantes en cuanto se refiere a el desarrolo de aplicaciones web.
Esta lista se actualiza cada 3 años.
Esto es importante para la comunidad de desarrolladores porque enseña de las consecuencias de las debilidades más comunes
e importantes de la seguridad de aplicaciones web.

-Describe brevemente dos de las vulnerabilidades del OWASP Top 10 2017
  1) Inyección: las vulnerabilidades de inyeccion pueden causar, perdida o corrupcion de informacion, perdida de realizar auditoria de datos o denegación de acceso.
  2) Perdida de autenticacion: estos suceden en casos de ataques automatizados con nombres o contraseñas de usuarios o administradores, el cual, eventualmente permite
     un acceso a el sistema, para evitar esto se sugiere evitar usar las credenciales por defecto de algun software o hardware, al igual que, ocupar 2FA.

- ¿Qué es OWASP ASVS y cuáles son sus niveles de verificación? y ¿Cuál es la diferencia entre los niveles 1 y 3 de OWASP ASVS?
  el OWASP ASVS (de el ingles, Application Secutity Verification Standard (Estandar de verificacion de seguridad de aplicaciones)) es una base la cual permite a los desarolladores probar los controles tecnicos de seguridad de las aplicaciones web, ademas proporciona a los desarrolladores y/o programadores una lista de requisitos para un desarrollo seguro.
    -ASVS nivel 1 Se dirige a todo tipo de software o aplicación. se aplican en situaciones donde no se requiere mucha confianza.
    -ASVS nivel 2 es usado en aplicaciones que contienen datos sensibles, que requieren proteccion.
    -ASVS nivel 3 es para aplicaciones que realizan transacciones de alto valor, que contienen datos medicos confidenciales, o cualquier aplicación que requiera el más alto
      valor de confianza.

-¿Qué es el modelado de amenazas y cuáles son sus beneficios?
  Son tecnicas utilizadas para identificar amenazas, ataques y identificar vulnerabilidades o contramedidas que pueden afectar una aplicación, se ocupan para cumplir con      los objetivos de seguridad de una empresa y reducir el riesgo, definiendo la forma de el diseño de una aplicacion.

-Nombra dos metodologías de modelado de amenazas:
  Stride: es una metodologia que tiene como enfoque principal ayudar a garantizar que los desarrolladores de software de windows de microsoft piensen en la seguridad     
  durante la fase de diseño
  Dread: consiste en mitigar el riesgo de amenazas a travez de la identificación de amenazas, para luego puntuarlas de acuerdo con el riesgo que suponen. se identifican los riesgos más grandes a travez de una lista de puntuaciones.
  
-¿Qué es el SDL y cómo ayuda a la seguridad del software?
El enfoque principal de SDL es reducir el numero y la gravedad de las vulnerabilidades del softwar, esto se logra a travez de estos criterios:
  Anticipando fallas en el codigo
  Intrusos atacan todo el código
  No enfocarse en "hacerlo bien la proxima vez"
  Y limpieza de codigo, removiendo codigo antiguo sin utilizar, ya sea funciones o protocolos viejos o sin usar. 
  Así, reduciendo la superficie de ataque.

- Define vulnerabilidad, amenaza y riesgo en el contexto de la seguridad informática
   Vulnerabilidad: se define como cualquier debilidad o fallo en un sistema de información que pone en riesgo la seguridad de los datos y, por tanto, la infromación.
    Amenaza: se conocen como las acciones que aprovecha una vulnerabilidad o falla para atnetar con la seguridad de un sistema de infromación.
    Riesgo: es una medida de la probabilidad de que se materialice una amenaza o un incidente de seguridad.


-¿Qué es CVE y cuál es su propósito?
  CVE (desde el ingles, Common Vulnerabilities and Exposures) es una lista de nombres de vulnerabilidades de seguridad de la información estandarizadas, con el fin de identificar cada vulnerabilidad y exposiciones de seguridad asignando un codigo de identificación unico a cada uno. tiene como proposito propiciar la distribución de datos en bases de datos de vulnerabilidades y herramientas de seguridad separadas y facilita la busqueda de informacion.

-Mencione tres ventajas del uso de CVE.
  -Ayuda a tener una plateforma para reconocer vulnerabilidades conocidas.
  - Puede ayudar a diferenciar las vulnerabilidades y referirse a ellas, con sus diferencias.
  - se encuentra en constane actualización de la base de datos de la lista, lo que posibilita ir ademas monitorieando cambios o actualizaciones.

-¿Qué es CVSS y para qué se utiliza?
  Common Vulnerability Scoring System, se trata de un sistema de puntaje, especialmente diseñado para identificar vulnerabilidades, cuantificando la severidad que puede presentar para la organizacion y los datos de información que maneja por medio de esta plataforma.

-Describe los tres grupos métricos del CVSS.
    Grupo Metrico Base: proporciona informacion sonbre la ubicacion de el atacante el instante de llevar a cabo la explotación.
    Grupo Métrico Temporal: represenan caracteristicas de una vulnerabilidad que pueden cambiar en el tiempo.
    Grupo de metrica de ambiente o entorno: representan caracteristicas de una vulnerabilidad, que es unica y relevanta para el entorno de un usuario en particular.

Explica el concepto de "componentes con vulnerabilidades conocidas" (OWASP A9:2017).
son vulnerabilidades conocidas que existen en una biblioteca, si se aprovecharan pueden debilitar las defensas de las aplicaciones y permitir diversos ataques e impactos. 

-¿Qué es la encriptación y cuál es su objetivo?
  Es un algoritmo que permite que cualquier tipo de documento, base de datos y/o archivo se vuelvan completamente ilegibles, por lo tanto, si no cuenta con las claves correctas, no se puede acceder a la informacion.
  
-¿Qué significan las siglas SOAP, WS y XML?
SOAP: De el ingles, SImple Object Access Protocol, es un protocolo creado por Microsoft, IBM, Y otros, que se usa actualmente en los servicios Web. Es bastante robusto, sirve para intercambiar informacion, ademas soporta elementos de validacion de mensajes, los cuales se pueden ocuar en HTTP, SMTP, TCP Y JMS, o sea, por internet, correos electronicos, protocolos entre clientes servidor, etc.
WS: Del ingles web service o web services, se basa en un conjunto de protocolos y estándares por los cuales se intercambian datos entre aplicaciones.
XML: significa eXtenxible Markup Language (Lenguaje de marcas extensibles). es un metalenguaje, el cual se ocupa para decir algo acerca de otro, extensible de etiquetas que fue desarrollado por el World Wide Web Consortium (W3C), una sociedad mercantil internacional que elbora recomendaciones para la World Wide Web

-¿Qué es hardening y cómo se relaciona con la seguridad de sistemas?
el hardening, (o endurecimiento en español) tiene como finalidad, reducir la superficie de vulnerabilidad en el sistema (puntos de accesso para un posible ataque informatico), para lograr de esta manera evitar en gran medida los posibles ataques.

-Describe tres acciones comunes de hardening.
Software, usuarios o servicios que no sean necesarios o que simplemente no se estén utilizando (en desuso)
Cerrar puertos que no estén en funcionamiento, instalar cortafuegos, estableciendo políticas de contraseñas seguras, bloquear la transferencia de archivos entre programas, usar datos encriptados siempre cuando sea posible, etc.


CAPTCHA, sirve para distinguir bots de humanos reales, lo cual, reduce el spam, y el descifrado de contraseñas.

Autenticacion Robusta: ya que el captcha identifica si el usuario ingresando es humano o no, este se encarga de identificar es quien ingresa a el sistema sea quien dice ser, esto se logra a travez de preguntas a el mismo usuario que este debería de saber: "Algo que tiene el usuario (Tarjetas Clavez, Token SMS)", "Algo que sabe el usuario (Claves)" o "Algo que hace o es el usuario (como factores biométricos)"

¿Qué significa PCI DSS y cuál es su propósito principal?
Payment Card Industry Security Standards Council (o al Español Consejo de Estandares de Seguridad de la Industria de Tarjetas de Pago)
Evita fraudes de robo de datos de tarjetas, al igual que, evita el robo de los datos de los dueños de estas mismas tarjetas. 
Permite que la comunicacion y cooperacion de distintas compañias de tarjetas de credito (en lo que se trata de los datos de estas mismas) tengan una protección mayor.

¿A qué tipo de empresas afecta PCI DSS?
Todo tipo de empresa que maneje datos de tarjeta de credito o debito, por ejemplo, mastercard, visa, Discover, etc.

Menciona tres ejemplos de datos que PCI DSS busca proteger.
Coordenadas de tarjetas de credito/debito
Robo de datos de usuarios/dueños de estas tarjetas.
Empresas que gestionan pagos de manera online.

¿Por qué es importante la certificación PCI DSS para las empresas?
Porque el certificado de PCI DSS demuestra que el usuario puede confiar de que sus datos no seran robados, y estan en manos seguras, en si, es una manera de demostrar
que tu empresa no es estafa.


Describe brevemente tres de los doce requisitos de PCI DSS.

1.-Disponer de un Firewall bien mantenido e implementado
2.-Evitar el uso de Ip's o de Contraseñas por defecto, o sea, cambiar estos datos para asegurar la red.
3.-Dotar de protección a los sistemas de almacenamiento.














