# Hola, soy Santiago Lovisotto 🧉👋

Buenos Aires, Argentina.

Estudio Ingeniería en Informática en la UNAJ y trabajo desarrollando software, principalmente backend. Mi día a día transcurre entre Java, Spring Boot, PostgreSQL y, de vez en cuando, .NET.

También tengo un pequeño universo propio: Opellio, un emprendimiento de desarrollo de software donde diseño y construyo sistemas para clientes reales.

Me gustan Linux, las terminales, el software libre y entender qué pasa detrás de las cosas. Supongo que por eso terminé estudiando informática: siempre me interesó más saber cómo funciona algo que simplemente usarlo.

## Un poco de historia

Mi relación con las computadoras empezó bastante antes de escribir la primera línea de código. A los once años hice un curso de armado y reparación de PC. Después vinieron las computadoras de amigos, familiares, conocidos y hasta un pequeño emprendimiento de reparación. Siempre había alguna máquina por abrir, algún problema por resolver o algo que podía funcionar un poco mejor.

En el secundario estudié electromecánica y me recibí de técnico. Más adelante hice el curso de Experto Universitario en Hacking Ético de la UTN. Ahí conocí Debian, Kali y el mundo de Linux. Fue uno de esos descubrimientos que terminan cambiando la forma en que uno mira una computadora.

Con el tiempo fui encontrando lo que más me interesa: los sistemas operativos, las redes, la infraestructura y el desarrollo. Me gusta pensar en el recorrido completo de un programa: desde que existe como código hasta que termina ejecutándose en algún servidor, atendiendo a alguien que probablemente no tenga idea de todo lo que sucede detrás.

Tengo pendiente, entre otras cosas, contribuir a algún proyecto open source importante. No tanto por ponerlo en un currículum, sino por la posibilidad de participar en algo que otras personas usan, estudian y mejoran.

## Mi manera de trabajar

Me interesa entender los problemas antes de empezar a resolverlos. En el desarrollo intento mantener las cosas simples, separar responsabilidades y evitar que una solución termine siendo más complicada que el problema original.

Trabajo principalmente con arquitectura hexagonal, principios SOLID y patrones de diseño. No los considero recetas para seguir a ciegas, sino herramientas que tienen sentido cuando ayudan a que el código sea más fácil de entender, mantener y modificar.

Algunas cosas de mi entorno de trabajo:

- Sistema operativo: Arch Linux. También uso Ubuntu, Debian y Fedora.
- Terminal: Alacritty. Paso bastante tiempo ahí.
- IDEs: IntelliJ IDEA y Rider para backend; VS Code para frontend.
- Bases de datos: DBeaver.
- Entornos: Docker y Docker Compose.
- Git: uso ollama-commit, un modelo local ejecutado con Ollama que me ayuda a redactar los mensajes de commit.
- Por curiosidad: cada tanto vuelvo a Neovim o micro para probar algo distinto.

Me gusta la filosofía GNU y, siempre que puedo, elijo herramientas de código abierto que respeten la privacidad. No es una postura que siga a rajatabla en todos los casos, pero sí una dirección en la que intento moverme.

## Herramientas y tecnologías

### Backend

- Java
- Spring Boot
- PostgreSQL
- Hibernate / JPA
- APIs REST
- Swagger / OpenAPI
- JWT
- OWASP

### Arquitectura y desarrollo

- Arquitectura hexagonal
- Monolitos modulares y microservicios
- SOLID y patrones de diseño
- Clean Code
- Tests unitarios
- Scrum y eXtreme Programming (XP)

### Infraestructura y herramientas

- Linux (Arch, Ubuntu, Debian y Fedora)
- Git, GitHub y GitHub Actions
- Dependabot
- Docker y Docker Compose
- VPS y Vercel
- Postman y DBeaver

### Otras tecnologías con las que trabajé

- C# / .NET 8 / ASP.NET Core
- SQL Server
- Entity Framework
- Angular
- React
- Astro.js


## Experiencia profesional

### Opellio Software · Software developer (fundador, freelance)

Buenos Aires, Argentina | Junio 2025 – Actualidad

Emprendimiento propio de desarrollo de software a medida.

Ciclo completo: relevamiento con el cliente para entender qué necesita, diseño, desarrollo, despliegue y mantenimiento. Aplico Clean Code y arquitectura hexagonal, con autenticación y autorización mediante JWT. Uso Claude como apoyo para revisar PRs, optimizar consultas y generar tests. Proyectos en producción:

#### Turnerapp ([turnerapp.com.ar](https://turnerapp.com.ar)) · SaaS multi-tenant de gestión de turnos

- Plataforma propia que vendo como servicio: cada negocio tiene su perfil público y gestiona su agenda. En su primer mes en producción procesó más de 120 reservas y automatizó la agenda de 4 clientes B2B reales.
- Cobro automatizado de señas con la API de Mercado Pago: más de 40 transacciones exitosas en el primer mes, con reducción del ausentismo.
- Mails automáticos con Resend y captcha de Cloudflare en la reserva para evitar bots.
- Stack: Java, Spring Boot y SQL Server en un VPS de Hostinger con Ubuntu; frontend en Angular desplegado en Vercel.

#### Didio Destacadas ([didiodestacadas.com.ar](https://didiodestacadas.com.ar)) · Sistema inmobiliario

- Carga y gestión de propiedades con fotos reordenables, filtros, login con autenticación y cierre de sesión por inactividad.
- Chatbot que responde consultas de los visitantes sobre las propiedades.
- Stack: .NET 8, arquitectura hexagonal y SQL Server en MonsterASP; frontend desarrollado con React y V0.

#### UOP3D ([uop3d.com.ar](https://uop3d.com.ar)) · Tienda de insumos de impresión 3D

- En producción hace más de un año: funciona como tienda online que deriva la compra a WhatsApp.
- Panel de administración para gestionar stock, proveedores, materiales, insumos, filamentos e impresoras 3D.
- Stack: .NET con arquitectura hexagonal y SQL Server (MonsterASP); frontend desarrollado en Astro.js.

## Proyectos

### OpenLeetcode · Plataforma de programación competitiva (GitHub)

En desarrollo

- Plataforma simplificada tipo LeetCode: los usuarios envían código y se evalúa contra casos de prueba. Monolito modular con arquitectura hexagonal y tres módulos (auth, challenges, submissions), con límites verificados por un test de arquitectura automatizado.
- Entorno reproducible con Docker Compose y PostgreSQL, migraciones versionadas con Flyway, health checks con Actuator y CI. Ejecución del código diseñada como puerto aislado en contenedores Docker descartables, sin red y con límites de recursos.
- Primer proyecto con integración continua: GitHub Actions (build y tests) y Dependabot, que abre pull requests cuando hay nuevas versiones de dependencias.
- Scrum individual: 28 tareas en 6 sprints (tablero en Trello) y diagramas de arquitectura en el repositorio.
- Stack: Java 21, Spring Boot, Gradle, PostgreSQL, Spring Data JPA, Flyway, Docker. JUnit y Testcontainers en los próximos sprints; frontend planificado en Angular.

### Ticketech · Sistema de gestión de eventos con microservicios

UNAJ | Sept – Dic 2025

- Líder del proyecto y referente técnico de un equipo que trabajó con Scrum y eXtreme Programming, con tests unitarios en los módulos críticos.
- Diseñé una arquitectura distribuida de 4 microservicios independientes y desarrollé la capa de integración entre ellos.
- Apliqué los patrones Factory y Prototype para generar mapas de asientos reutilizables entre eventos con configuraciones visuales distintas.
- Presentamos el avance en 3 exposiciones (una por sprint), simulando la interacción con un cliente real.
- Stack: C# y .NET 8, SQL Server; frontend en React.

### Protein Aligner · Alineador de proteínas (GitHub)

UNAJ | En desarrollo

- Trabajo final de Bioinformática. Aplicación web que compara dos proteínas con alineamiento global (Needleman-Wunsch) y local (Smith-Waterman) usando BioJava, y muestra score, identidad, similitud y gaps, analizando casos donde ambos enfoques difieren.
- Stack: Java, Spring Boot, BioJava, Docker y Docker Compose, con CI en GitHub Actions.

### Otros proyectos en GitHub

- Stock System: gestión de stock y facturación para comercios, con PostgreSQL, scanners 1D e impresoras térmicas (Java).
- SayIt: app de escritorio para practicar inglés oral, con text-to-speech, reconocimiento de voz (Sphinx) y distancia de Levenshtein.

## Educación y formación

### Universidad Nacional Arturo Jauretche (UNAJ)

Ingeniería en Informática · 4to año en curso | Florencio Varela, Buenos Aires | Marzo 2023 – Diciembre 2027 (estimado)

Estudiante avanzado: 69,57 % de la ingeniería completada y 96,43 % de Analista Programador. Formación en desarrollo de software, algoritmos y estructuras de datos, sistemas operativos, redes y bases de datos. Metodologías ágiles: Scrum, Kanban.

### Universidad FASTA

Tramo de formación pedagógica para técnicos | Campus online | Marzo 2023 – Noviembre 2024

Habilita a dar clases en escuelas secundarias técnicas. Desarrolló mis habilidades de comunicación, exposición y coordinación de grupos, que aplico al presentar proyectos y trabajar con clientes.

### Técnico Electromecánico · Instituto San Juan Bautista

Secundario técnico | Florencio Varela, Buenos Aires | Marzo 2016 – Diciembre 2022

200 horas de prácticas profesionales en la fábrica metalúrgica Stampin Marek (2022), rotando por distintos puestos del taller: aprendí a comunicarme, liderar y trabajar en equipo. Trabajo integrador: generador eólico fabricado con impresión 3D.

### UTN FRBA · Centro de e-Learning

Experto Universitario en Hacking Ético | Septiembre 2019 – Noviembre 2020

Mi primer contacto con Linux (Debian y Kali) y la terminal. Uso de nmap, Wireshark, Hydra y Maltego; fundamentos de seguridad de la información y guías OWASP, que aplico al desarrollar software.

## Idiomas

Inglés intermedio-avanzado · C1, EF SET (2026). Lectura de documentación técnica y bibliografía en inglés con fluidez.

## Habilidades técnicas

- Backend: Java (Spring Boot), C# (.NET 8), APIs REST, Swagger/OpenAPI, JWT, OWASP.
- Datos: PostgreSQL, SQL Server, Hibernate (JPA), Entity Framework, Flyway.
- Calidad: arquitectura hexagonal, SOLID, patrones de diseño, tests unitarios, Scrum, XP.
- DevOps: Linux (Arch, Ubuntu, Debian, Fedora), Docker y Docker Compose, GitHub Actions, Dependabot, VPS, Vercel.
- Frontend: Angular, React, Astro.js.
- Herramientas: Git, IntelliJ IDEA, Rider, DBeaver, Postman, VS Code, Neovim.

## Lecturas

Hay libros que uno lee para aprender algo y otros a los que vuelve porque siempre queda alguna idea dando vueltas. Esta es una pequeña lista de lecturas de informática que hice y otras que tengo pendientes.

### Programación y arquitectura

- The Pragmatic Programmer — buenas ideas sobre el oficio de programar.
- Design Patterns (Gang of Four) — un clásico sobre patrones de diseño.
- Fundamentals of Software Architecture — distintas formas de pensar y diseñar arquitecturas.
- Joel on Software — artículos sobre desarrollo, equipos y la industria del software.

### Sistemas y redes

- Operating Systems: Three Easy Pieces — sistemas operativos, desde sus fundamentos.
- Network Warrior — redes y todo lo que sucede detrás de ellas.

### Papers

- Architectural Styles and the Design of Network-based Software Architectures, de Roy Fielding. La tesis doctoral en la que se presenta REST.

## Cuando no estoy programando

No todo sucede frente a una pantalla, aunque a veces cueste creerlo.

- Música. Escucho variado, especialmente Sumo y Pescado Rabioso. También B.B. King. Me gusta escuchar música en FLAC y prestar atención a los detalles. Es una de mis formas favoritas de desconectar.
- Filosofía. Leo principalmente en inglés. Schopenhauer es uno de mis autores favoritos. On the Suffering of the World es uno de esos libros que dejan algunas ideas rondando bastante después de haber terminado de leerlos.
- Calistenia. Entreno hace varios años y me interesa especialmente la resistencia. Hay algo de la filosofía de Zef Zakaveli que intento llevar al entrenamiento: calidad antes que cantidad. Que la última repetición se parezca a la primera, sin atajos ni movimientos hechos por cumplir.

## Contacto

- [LinkedIn](https://www.linkedin.com/in/santiagolovisotto/)
- [Email](mailto:santiagolovisotto@protonmail.com)
