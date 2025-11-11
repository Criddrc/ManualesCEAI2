# Manuales CEAI 📚

> Un proyecto de documentación estática y segura construido con MkDocs y el tema Material.

---

## 📝 Descripción

Este proyecto utiliza **Python** y la herramienta **MkDocs** para generar documentación estática. Se han incorporado varias extensiones clave, incluyendo la localización de contenido (i18n), integración de lightbox para imágenes y cifrado de contenido, para crear una solución de documentación robusta y completa.

---

## 🛠️ Requisitos e Instalación

Se deben seguir estos pasos para configurar y ejecutar el entorno de documentación localmente.

### Prerrequisitos

Tener instalado **Python 3.x** y el gestor de paquetes **pip**.

### Instalación

1.  **Clonar el Repositorio**

    Abrir la terminal y ejecutar:

    ```bash
    git clone https://github.com/DianapiSol/manualesCEAI.git
    cd manualesCEAI
    ```

3.  **Instalar el Entorno Virtual (Recomendado)**

    Crear y activar un entorno virtual:

    ```bash
    python -m venv .venv
    
    # Activación (Linux/macOS):
    source venv/bin/activate
    
    # Activación (Windows):
    CMD: .venv\Scripts\activate.bat
    POWERSHELL: .venv\Scripts\Activate.ps1
    ```

5.  **Instalar Dependencias (Orden Estricto)**

    **IMPORTANTE:** Las extensiones deben instalarse en el siguiente orden para evitar conflictos y asegurar el correcto funcionamiento del entorno de MkDocs.

    | Orden | Requerimiento (Comando) | Propósito Clave |
    | :---: | :--- | :--- |
    | 1 | `pip install mkdocs` | Instala el paquete **MkDocs**. |
    | 2 | `pip install mkdocs-material` | Instala el tema base **MkDocs Material**. |
    | 3 | `pip install mkdocs-static-i18n[material]` | Añade soporte para **internacionalización (i18n)**. |
    | 4 | `pip install mkdocs-glightbox` | Integra la funcionalidad de **Lightbox** para imágenes. |
    | 5 | `pip install mkdocs-site-urls` | Herramienta para gestionar URLs del sitio. |
    | 6 | `pip install mkdocs-encryptcontent-plugin` | Permite **cifrar y proteger** contenido específico. |

    ```bash
    # 1. Instalar el paquete base
    pip install mkdocs
    
    # 1. Instalar el tema base
    pip install mkdocs-material

    # 2. Instalar el plugin de internacionalización (i18n)
    pip install mkdocs-static-i18n[material]

    # 3. Instalar el plugin GLightbox
    pip install mkdocs-glightbox

    # 4. Instalar el plugin de URLs del sitio
    pip install mkdocs-site-urls

    # 5. Instalar el plugin de cifrado de contenido
    pip install mkdocs-encryptcontent-plugin
    ```

---

## ⚙️ Uso

### Iniciar el Servidor de Desarrollo

Para visualizar la documentación en la máquina local (generalmente en `http://127.0.0.1:8000`):

```bash
mkdocs serve
