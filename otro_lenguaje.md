# Condicionales en Java ☕

**Integrantes:** Marcos · Quico · Alberto
**Lenguaje:** Java
**Reto:** Condicionales (`if` / `else`)

---

## 🐍 Ejemplo en Python

```python
edad = 20

if edad >= 18:
    print("Mayor de edad")
else:
    print("Menor de edad")
```

## ☕ Ejemplo en Java

```java
int edad = 20;

if (edad >= 18) {
    System.out.println("Mayor de edad");
} else {
    System.out.println("Menor de edad");
}
```

---

## ❓ Preguntas

### ¿Cómo se declaran las variables?

Hay que indicar el **tipo de dato** que vas a crear:

```java
int edad = 20;               // número entero
double altura = 1.75;        // número decimal
String nombre = "Ana";       // texto
boolean tieneEntrada = true; // verdadero o falso
```

### ¿Cómo se delimitan los bloques de código?

Con **llaves `{ }`**. Todo lo que está entre la llave de apertura y la de cierre pertenece al `if` o al `else`. La condición va siempre entre **paréntesis `( )`**, y cada instrucción termina con **punto y coma `;`**.

> La sangría (indentación) se usa para que el código se lea mejor, pero Java no la necesita: lo que manda son las llaves.

### ¿Qué cambia en la sintaxis respecto a Python?

- En los condicionales, en vez de `:` se ponen llaves `{ }`.
- La condición del `if` va entre paréntesis `( )`.
- Los `print` en Java se hacen así: `System.out.println("...");`

### ¿Qué parte de la lógica se mantiene igual?

La lógica es **exactamente la misma**: se comprueba una condición y, si se cumple, se ejecuta el bloque del `if`; si no, el del `else`.