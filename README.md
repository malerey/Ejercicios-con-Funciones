# Funciones


### 1. `sumar(a, b)`

Crear una función `sumar` que tome como argumentos dos números y devuelva la suma de ellos

```javascript
sumar(2, 3) // 5
sumar(1.2, 3.4) // 4.6
sumar(3, -5) // -2
```

###  2. `restar(a, b)`

Crear una función `restar` que tome como argumentos dos números y devuelva la resta de ellos

```javascript
restar(3, 2) // 1
restar(10, 5.5) // 4.5
restar(3, 5) // -2
```
### 3. `multiplicar(a, b)`

Crear una función `multiplicar` que tome como argumentos dos números y devuelva la multiplicación de ellos

```javascript
sumar(2, 3) // 6
sumar(4, 0.5) // 2
```

### 4. `dividir(a, b)`

Crear una función `dividir` que tome como argumentos dos números y devuelva la suma de ellos

```javascript
sumar(2, 3) // 5
sumar(1.2, 3.4) // 4.6
sumar(3, -5) // -2
```


### 5. `calcularAreaTriangulo(base, altura)`

Crear una función `calcularAreaTriangulo` que tome como argumentos la base y la altura de un triángulo y devuelva el área del mismo

```javascript
calcularAreaTriangulo(3, 4) // 6
calcularAreaTriangulo(5, 6) // 40
```

### 6. `gritar(str)` 

Crear una función `gritar` que tome como argumento un string y devuelva el mismo string con un signo de exclamación al principio y al final del mismo

```javascript
gritar('hola') // ¡hola!
gritar('aaaaaa') // ¡aaaaaa!
```

### 7. `obtenerNombreCompleto(nombre, apellido)`

Crear una función `obtenerNombreCompleto` que tome como argumento un nombre y un apellido y devuelva un string con la unión de ambos valores

```javascript
obtenerNombreCompleto('Ada', 'Lovelace') // 'Ada Lovelace'
```

### 8. `saludar(nombre)`

Crear una función `saludar` que tome como argumentos un nombre y devuelva un saludo que lo incluya.

```javascript
saludar('Ada') // 'Hola Ada, un gusto conocerte'
```

### 9. `saludarGritando(nombre, apellido)`

Usando las funciones anteriores (`obtenerNombreCompleto`, `saludar` y `gritar`), crear una función `saludarGritando` que tome como argumentos un nombre y un apellido y devuelva un saludo con signos de exclamación.

```javascript
saludarGritando('Ada', 'Lovelace') // ¡Hola Ada Lovelace, un gusto conocerte!
```

**TIP:** recordá que los resultados de funciones se pueden guardar en variables para usarlos más adelante

```javascript
const nombreCompleto = obtenerNombreCompleto('Ada', 'Lovelace')
const saludo = saludar(nombreCompleto)
const grito = gritar(saludo)
console.log(grito) // ¡Hola Ada Lovelace, un gusto conocerte!
```

### 10. obtenerDatosDeCiudad(nombre, poblacion, pais)

Crear una función `obtenerDatosDeCiudad` que tome como argumentos un string `nombre`, un número `poblacion` y un string `pais` y devuelva string con el siguiente formato: `La ciudad de NOMBRE tiene una población de POBLACION habitantes y está ubicada en PAIS`

```javascript
obtenerDatosDeCiudad('Santa Fe', 545606, 'Argentina') // 'La ciudad de Santa Fe tiene una población de 545606 habitantes y está ubicada en Argentina'
```


### 11. `convertirHorasEnSegundos(horas)`

Crear una función `convertirHorasEnSegundos` que tome como argumento un número de horas y devuelva la conversión a segundos de dicha cantidad de horas

```javascript
convertirHorasEnSegundos(1) // 3600
convertirHorasEnSegundos(3) // 10800
convertirHorasEnSegundos(4.5) // 16200
```

### 12. `calcularPerimetroRectangulo(ancho, alto)`

Crear una función `calcularAreaTriangulo` que tome como argumentos el ancho y el alto de un rectángulo y devuelva su perímetro

```javascript
calcularPerimetroRectangulo(3.2, 5) // 16.4
calcularPerimetroRectangulo(10, 20) // 60
```

### 13. `calcularPorcentaje(numero, porcentaje)`

Crear una función `calcularPorcentaje` que tome como argumentos un número y un porcentaje y devuelva el valor del porcentaje correspondiente al número

```javascript
calcularPorcentaje(100, 15) // 15
calcularPorcentaje(10, 50) // 5
calcularPorcentaje(200, 10) // 20
```

### 14. `sumarPorcentaje(numero, porcentaje)`

Crear una función `sumarPorcentaje` que tome como argumentos un número y un porcentaje y devuelva la suma de dicho número con la de su porcentaje. Usar la función `calcularPorcentaje` para obtener el porcentaje a sumar

```javascript
sumarPorcentaje(100, 15) // 115
sumarPorcentaje(10, 50) // 15
sumarPorcentaje(200, 10) // 220
```
### 15. `restarPorcentaje(numero, porcentaje)`

Crear una función `restarPorcentaje` que tome como argumentos un número y un porcentaje y devuelva la resta de dicho número con la de su porcentaje. Usar la función `calcularPorcentaje` para obtener el porcentaje a restar

```javascript
restarPorcentaje(100, 15) // 85
restarPorcentaje(10, 40) // 6
restarPorcentaje(200, 10) // 180
```

### 16. `calcularFPS(fps, minutos)`

FPS son _cuadros por segundo_ (_frames per second_). Crear una una función `calcularFPS` que tome como argumentos una cantidad de cuadros por segundo y una cantidad de minutos, y devuelva cuántos cuadros hubo en esa cantidad de minutos

```javascript
calcularFPS(1, 1) // 60
calcularFPS(10, 2) // 1200
calcularFPS(2, 3) // 360
```


### 17. `obtenerCompetencia(a, b)`

Crear una función `obtenerCompetencia` que tome como argumentos dos strings `a` y `b` y devuelva un string con el formato `a vs. b`

```javascript
obtenerRivales('JavaScript', 'Python') // `JavaScript vs. Python`
obtenerRivales('Coca', 'Pepsi') // `Coca vs. Pepsi`
obtenerRivales('Perros', 'Gatos') // `Perros vs. Gatos`
```

### 18. `generarEmail(usuario, dominio)`

Crear una función `generarEmail` que tome como argumentos dos string `usuario` y `dominio` y el un string email con el formato `usuario@dominio.com`

```javascript
generarEmail('adalovelace', 'gmail') // 'adalovelace@gmail.com'
```

### 19. `calcularPuntaje(facil, normal, dificil)`

Crear una función `calcularPuntaje` que calcule el puntaje de un examen que consiste en ejercicios de distinto nivel. Debe tomar como argumento tres numeros que consisten en la cantidad de ejercicios resueltos en cada nivel y devolver un número con el puntaje correspondiente. El puntaje se calcula de la siguiente forma:

```
facil: 3 puntos
normal: 5 puntos
dificil: 10 puntos
```

```javascript
calcularPuntaje(3, 0, 0) // 9
calcularPuntaje(0, 2, 1) // 20
calcularPuntaje(5, 1, 2) // 40
```
