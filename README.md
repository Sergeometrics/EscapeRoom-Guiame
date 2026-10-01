# ESCAPE ROOMS EDUCATIVOS // PROTOCOLO DE SEGURIDAD

Dos juegos de escape room colaborativos en un solo archivo HTML cada uno. Estilo
"terminal de servidor corporativo" (fondo oscuro, texto monoespaciado verde, sin
emojis, sin colores infantiles). Pensados para trabajar en equipo con 4 roles.

## Archivos

| Archivo | Grado | Niveles |
|---|---|---|
| `escape-room-tercero.html` | 3 (8-9 anos) | 3 niveles |
| `escape-room-quinto.html` | 5 (10-11 anos) | 10 niveles |

## Como usar

1. Abrir el archivo en cualquier navegador (doble clic). No requiere internet,
   servidor ni instalacion.
2. En la pantalla "Asignacion de Protocolo" registrar el nombre o alias de los
   4 agentes. El boton de inicio se desbloquea solo cuando los 4 campos estan
   completos.
3. Imprimir la tabla criptografica (boton dentro del juego, exclusivo para el
   Criptografo): cada agente Criptografo necesita una copia fisica.

## Los 4 roles (bloqueo mutuo)

- **Criptografo**: unico autorizado para traducir las secuencias de simbolos
  (@ = A, # = B, * = C, etc.) usando la tabla impresa.
- **Matematico**: unico autorizado para usar papel y lapiz.
- **Agente Logistico**: unico que toca los objetos fisicos (lapices, clips,
  cuadernos, bolsillos, etc.).
- **Operador**: unico que toca teclado y pantalla; recibe los datos de los demas
  por voz.

Ningun nivel puede resolverse en solitario: la contrasena de cada nivel exige
la cadena completa traducir -> calcular -> contar/manipular -> ingresar.

## Estructura de cada nivel

- Transmision cifrada en pantalla (el Criptografo la traduce).
- Instrucciones dirigidas por nombre a cada agente.
- Campo de validacion: una respuesta incorrecta muestra un mensaje generico
  (nunca revela la solucion).
- Nivel 5 (quinto grado) y Nivel 2 (tercer grado) usan verificacion en dos
  fases con conteo fisico variable.
- El nivel final se resuelve seleccionando un simbolo en un panel tactil.

## Respuestas (para el docente)

Tercer grado:
- N1 "OCHO POR TRES": 8x3 = 24, montones de 6 -> **4**
- N2 "CHAQUETAS": (bolsillos contados) x 10 -> se valida en dos fases
- N3: 4 cuadernos x 3 = 12 = letra L -> simbolo **<**

Quinto grado:
- N1: 6x9=54, digitos 5+4 -> **9** | N2: mitad de 24=12, /3 -> **4**
- N3: 15+9=24, /8 -> **3** | N4: 40-17=23, 2x3 -> **6**
- N5: libros contados x 10 (dos fases, variable)
- N6: 90/6=15, /5 -> **3** | N7: tercera parte de 24=8, /2 -> **4**
- N8: doble de 15=30, /6 -> **5** | N9: 3/5 de 25=15, /5 -> **3**
- N10: 8 cuadernos x 3 = 24 = letra X -> simbolo **"**

## Material fisico necesario

Lapices, clips o borradores, cuadernos del equipo, chaquetas (N2 tercer grado),
libros (N5 quinto grado), papel y lapiz solo para el Matematico, copias
impresas de la tabla criptografica.

## Requisitos tecnicos

- Cualquier navegador moderno (Chrome, Firefox, Edge, Safari).
- Funciona con raton o pantalla tactil; responsive para tablets.
- Sin alertas del navegador: toda la interaccion es mediante la propia interfaz.
