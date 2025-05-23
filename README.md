# 📬 Queue-Rabbit

Repositorio que contiene la configuración de la cola de mensajería basada en **RabbitMQ**, utilizada para la comunicación entre microservicios en el ecosistema **IWellness**.

Esta cola permite la transmisión eficiente y desacoplada de datos entre módulos como: servicios, usuarios, análisis y base de datos.

---

## 🚀 ¿Cómo usar?

> 💡 **Requisitos previos:** Tener instalado [Docker Desktop](https://www.docker.com/products/docker-desktop).
                            El front y el back tienen que estar corriendo

### 1. Clona el repositorio

```bash
git clone https://github.com/tu-usuario/Queue-Rabbit.git
cd Queue-Rabbit
```

### 2. Levanta el contenedor
```bash
En la terminal, indica el siguiente comando:
docker-compose up
```

### 3. Verifica que este corriendo
Espera unos segundos a que la terminal cargue todas las colas de los micros
Puedes también acceder a la interfaz web de RabbitMQ en:

🔗 http://localhost:15672
- Usuario: user
- Contraseña: user
- Nota: puede cambiar en el docker-compose. Pero deben modificar los microservicios para que puedan acceder a la cola.
