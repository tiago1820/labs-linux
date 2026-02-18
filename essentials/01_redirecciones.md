# PREPARACIÓN
- Para crear una carpeta llamada lab_redirecciones
```
mkdir lab_redirecciones
```

- Para entrar en la carpeta recién creada:
```
cd lab_redirecciones
```

- Para ver la ruta completa del directorio actual:
```
pwd
```

# ARCHIVOS DE TRABAJO
- Para crear el archivo datos.txt y permitir escribir contenido hasta encontrar EOF.
```
 cat > datos.txt <<EOF
```
- Contenido del archivo:
```
 ana:ventas:100
 juan:it:200
 maria:ventas:150
 luis:it:300
 sofia:rrhh:120
```
- Para indicar el final del contenido que se escribirá en el archivo:
```
  EOF
```

- Para mostrar en pantalla el contenido del archivo datos.txt:
```
 cat datos.txt
```

# REDIRECCIÓN DE SALIDA
- Para guardar la lista de archivos de directorio actual en listado.txt, sobrescribiendo
el contenido si ya existe.
```
 ls > listado.txt
```

- Para mostrar en pantalla el contenido del archivo listado.txt.
```
 cat listado.txt
```

# REDIRECCIÓN DE ENTRADA (<)

Para contar líneas, palabras y caracteres del archivo datos.txt usando el archivo como
entrada estándar.
```
 wc < datos.txt
```





