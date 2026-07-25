# Encriptador de Texto 🔐

Aplicación web desarrollada para **encriptar y desencriptar textos** mediante un sistema de sustitución de caracteres, creada como parte del desafío **Oracle Next Education (ONE) / Alura Latam**.

---

## 🚀 Funcionalidades Principales

* 🔒 **Encriptación de Texto:** Transforma el texto ingresado reemplazando las vocales según las reglas establecidas:
  * La letra `e` se convierte en `enter`
  * La letra `i` se convierte en `imes`
  * La letra `a` se convierte en `ai`
  * La letra `o` se convierte en `ober`
  * La letra `u` se convierte en `ufat`
* 🔓 **Desencriptación de Texto:** Convierte el mensaje encriptado de vuelta a su estado original.
* 📋 **Copiar al Portapapeles:** Botón integrado para copiar el resultado directamente con un solo clic.
* ⚠️ **Validaciones:** Restricción para trabajar únicamente con letras minúsculas y sin caracteres especiales.

---

## 🛠️ Tecnologías Utilizadas

* **HTML5:** Estructura semántica de la página.
* **CSS3:** Estilos personalizados y diseño adaptativo (*responsive*).
* **JavaScript (ES6+):** Lógica de encriptación, desencriptación y manipulación del DOM.

---

## 📂 Estructura del Proyecto

```text
Encriptador/
│── img/          # Ilustraciones y recursos visuales de la interfaz
│── index.html    # Estructura principal de la aplicación
│── style.css     # Hojas de estilo y diseño visual
│── app.js        # Lógica de encriptación, desencriptación y eventos
└── README.md     # Documentación del proyecto

⚙️ Ejecución Local
No requiere la instalación de dependencias ni servidores. Para probarlo:

1. Clonar el repositorio:

Bash
git clone [https://github.com/Arturo802/Encriptador.git](https://github.com/Arturo802/Encriptador.git)

2. Abrir la aplicación:
Abre el archivo index.html directamente en tu navegador web.

👤 Autor
Arturo

Técnico Superior en Desarrollo de Aplicaciones Multiplataforma (DAM)
