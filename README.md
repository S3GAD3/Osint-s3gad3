# 🔎 OSINT · S3GAD3

**Directorio operativo de herramientas OSINT para investigación en fuentes abiertas.**

🌐 **Acceso a la herramienta:**  
https://s3gad3.github.io/Osint-s3gad3/

---

## 📌 Descripción

**OSINT · S3GAD3** es un portal web diseñado para facilitar el acceso a herramientas y fuentes de información abierta utilizadas en investigaciones OSINT (*Open Source Intelligence*).

El proyecto reúne en una única interfaz recursos para investigar:

- correos electrónicos y usernames;
- identidades y presencia digital;
- números de teléfono e IMEI;
- dominios, URL, IP e infraestructura;
- empresas, sociedades y marcas;
- IBAN, BIN, entidades financieras y pagos;
- criptomonedas y blockchain;
- imágenes, vídeo y metadatos;
- redes sociales y SOCMINT;
- GEOINT, mapas y transporte;
- GitHub, código y artefactos técnicos;
- archivos y documentos;
- filtraciones y exposición de datos;
- histórico web;
- recursos de formación OSINT.

El objetivo no es simplemente acumular enlaces, sino disponer de un **punto de partida organizado y operativo para una investigación OSINT**.

---

## 🚀 Acceso directo

La herramienta está publicada mediante GitHub Pages y puede utilizarse directamente desde el navegador:

### 👉 https://s3gad3.github.io/Osint-s3gad3/

No requiere instalación ni servidor propio. La interfaz es responsive y está diseñada para funcionar tanto en **ordenadores como en dispositivos móviles**.

---

## 🧭 Áreas de investigación

Las herramientas se organizan por el tipo de información o fase de investigación:

- 🔎 Buscadores y metaherramientas
- 👤 Identidad, personas, email y username
- 🌐 Redes sociales y SOCMINT
- ☎️ Telefonía e IMEI
- 🌍 Dominios, URL, IP e infraestructura
- 🏢 Empresas, marcas y registros
- 💶 FININT, bancos y pagos
- ₿ Criptoactivos y blockchain
- 🖼️ Imágenes, vídeo y verificación
- 📍 GEOINT, mapas y transporte
- 💻 Código, GitHub y artefactos técnicos
- 📄 Archivos, documentos y metadatos
- ⚠️ Filtraciones y exposición de datos
- 🕒 Histórico, archivos y preservación
- 🎓 Formación OSINT

La selección incluye tanto fuentes oficiales como servicios especializados y herramientas de investigación ampliamente utilizadas.

---

## ⚡ Análisis rápido de datos

El portal incorpora un sistema de **detección automática del tipo de dato**.

Puedes introducir, por ejemplo:

```text
usuario@dominio.es
+34600111222
8.8.8.8
ejemplo.com
https://ejemplo.com/login
ES9121000418450200051332
```

También puede reconocer determinados formatos de hash, BIN y usernames.

Cuando es posible, el sistema identifica automáticamente el tipo de dato y propone herramientas adecuadas para continuar la investigación.

La clasificación inicial se realiza **localmente mediante JavaScript en el navegador**.

---

## 🕵️ Integración con RASTRO

El portal funciona también como punto de acceso al ecosistema:

# RASTRO — Kit de Investigación de Fuentes Abiertas

RASTRO es una colección de herramientas OSINT desarrolladas por **S3GAD3**, orientadas a diferentes tipos de datos y fases de una investigación.

Entre los módulos integrados se encuentran:

- **RASTRO-PHONE** — investigación de números de teléfono.
- **RASTRO-USER** — usernames y correos electrónicos.
- **RASTRO-GOOG** — pivotes relacionados con cuentas Google/Gmail.
- **RASTRO-SOCMINT** — investigación en redes sociales.
- **RASTRO-WEB** — dominios, URL, IP e infraestructura.
- **RASTRO-COMPANY** — empresas y sociedades.
- **RASTRO-FININT** — IBAN, BIN y análisis financiero.
- **RASTRO-IMAGE** — imágenes, metadatos y verificación.
- **RASTRO-GH** — GitHub y repositorios públicos.
- **RASTRO-HEADER** — análisis de cabeceras y artefactos técnicos.

Los módulos RASTRO aparecen tanto en su panel específico como dentro de las categorías correspondientes del directorio.

---

## 🔄 Flujo de trabajo recomendado

```text
DATO INICIAL
     │
     ▼
OSINT · S3GAD3
     │
     ▼
Identificación del tipo de dato
     │
     ▼
Selección de herramientas
     │
     ▼
Obtención de información
     │
     ▼
Nuevos identificadores
     │
     ▼
Pivote a otras fuentes
     │
     ▼
Contraste y documentación
```

En OSINT, un resultado debe considerarse normalmente **un nuevo punto de partida y no una conclusión automática**.

---

## 📱 Uso desde móvil

La interfaz está diseñada para adaptarse a pantallas pequeñas y permite utilizar desde el móvil:

- el buscador global;
- la navegación por categorías;
- el detector de datos;
- los módulos RASTRO;
- las fuentes externas.

Esto permite utilizar el portal como un **panel de acceso rápido OSINT** desde cualquier navegador moderno.

---

## 🔐 Privacidad

El portal es una aplicación web estática.

La identificación inicial de los datos introducidos en el apartado de análisis rápido se realiza en el propio navegador.

El dato solo se comunica a un servicio externo cuando el usuario decide abrir una herramienta o realizar una consulta que dependa de dicho servicio.

Cada herramienta externa dispone de sus propias políticas, condiciones de uso y mecanismos de tratamiento de datos.

---

## ⚠️ Uso responsable

Este proyecto está destinado a:

- investigación legítima en fuentes abiertas;
- ciberseguridad;
- análisis de inteligencia;
- investigación académica;
- formación;
- verificación de información.

La presencia de una herramienta en este directorio **no implica que cualquier uso de la misma sea legítimo**.

El usuario es responsable de cumplir la legislación aplicable, las condiciones de uso de cada servicio y las normas relativas a privacidad y protección de datos.

Los resultados obtenidos mediante OSINT deben ser **contrastados antes de extraer conclusiones**.

---

## 🛠️ Tecnología

El proyecto utiliza una arquitectura deliberadamente sencilla:

```text
HTML
CSS
JavaScript
GitHub Pages
```

No requiere backend para el funcionamiento básico del portal.

Esto facilita su auditoría, despliegue, mantenimiento, adaptación y creación de forks.

---

## 🤝 Contribuciones

Las mejoras son bienvenidas.

Puedes:

1. hacer un **fork** del repositorio;
2. crear una rama para tus cambios;
3. realizar y probar las modificaciones;
4. enviar un **Pull Request**.

También puedes proponer:

- nuevas herramientas OSINT;
- eliminación de servicios obsoletos;
- corrección de enlaces;
- nuevas categorías;
- mejoras de interfaz;
- mejoras de accesibilidad;
- nuevas funcionalidades.

Se recomienda priorizar herramientas que aporten **valor real al flujo investigador** y evitar añadir enlaces únicamente para aumentar el tamaño del directorio.

---

## 📚 Manual OSINT

El proyecto se complementa con el:

**Manual de Fuentes Abiertas para la Investigación de Cibercrimen**

https://s3gad3.github.io/manual-osint-cibercrimen/

---

## 👨‍💻 Autor

Desarrollado y mantenido por **S3GAD3**.

- GitHub: https://github.com/S3GAD3
- Portal OSINT: https://s3gad3.github.io/Osint-s3gad3/

---

## 📄 Licencia

Este proyecto se distribuye bajo licencia **MIT**.

Puedes utilizarlo, modificarlo, distribuirlo y crear trabajos derivados conforme a los términos de dicha licencia, manteniendo el aviso de copyright y licencia exigido por MIT.

Consulta el archivo [`LICENSE`](LICENSE) para más información.

---

**OSINT · S3GAD3**  
*Investigar · Pivotar · Contrastar · Documentar*
