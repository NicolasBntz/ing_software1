# HTML + Docker Demo

Este es un sitio HTML estático que corre dentro de un contenedor Docker usando nginx.

---

## ¿Cómo probarlo?

### Clonar el repositorio

```bash
git clone https://github.com/NicolasBntz/ing_software1.git
cd ing_software1
```

### Construir la imagen docker
```bash
docker build -t html-docker-demo .
```

### Ejecutar el contenedor
```bash
docker run -d -p 8080:80 html-docker-demo
```

###  Ver el sitio
```bash
http://localhost:8080
```

### Este contenedor usa la imagen oficial de nginx como base

---