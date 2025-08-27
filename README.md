# 📅 Autor 
Julian Andres Santamaria Bustamante

# 📅 Línea de Tiempo con Listas HTML

## 🎯 Objetivo
Aplicar el uso de **listas desordenadas (`<ul>`) y elementos de lista (`<li>`)**, incluyendo listas **anidadas**, para construir una línea de tiempo con experiencias personales o profesionales.

## 📋 Instrucciones

### 1. Crear el documento base
```html
<!doctype html>
<html lang="es">
<head>
  <meta charset="utf-8">
  <title>Línea de Tiempo</title>
</head>
<body>
  <h1>Mi Línea de Tiempo</h1>
</body>
</html>
```

### 2. Agregar lista principal
```html
<ul>
  <li>2022</li>
  <li>2020</li>
  <li>2015</li>
</ul>
```

### 3. Anidar listas secundarias
```html
<ul>
  <li>2022
    <ul>
      <li>Trabajo en Adevinta</li>
      <li>Proyecto de desarrollo en Angular</li>
    </ul>
  </li>
  <li>2020
    <ul>
      <li>Trabajo en Hubii</li>
      <li>Implementación de API REST</li>
    </ul>
  </li>
  <li>2015
    <ul>
      <li>Trabajo en Nacencia</li>
      <li>Primeros pasos en desarrollo web</li>
    </ul>
  </li>
</ul>
```

### 4. Validar
- Abrir el archivo en el navegador
- Inspeccionar elementos (F12)
- Verificar que las etiquetas estén correctamente cerradas

## ✅ Checklist
- [ ] Documento HTML creado
- [ ] Lista principal implementada
- [ ] Listas anidadas añadidas
- [ ] Validación completada