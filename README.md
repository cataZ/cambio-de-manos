# cambio-de-manos

Búsqueda de camino optimo en caso de un recorrido con calles mano y contramano utilizando grafos (networkx)

---

DESCRIPCION DEL PROBLEMA

---

Un colectivo escolar recoge alumnos de un barrio lejano y viaja todas las mañanas hasta la escuela, siempre eligiendo el camino más corto. La ciudad, dentro de la cual se desplaza el colectivo, se puede representar con un mapa de esquinas unidas por calles, cada calle tiene una sola mano. Las esquinas han sido numeradas.<br />
Para ahorrar tiempo el colectivo sale de una esquina del barrio y los padres acercan sus hijos al mismo. El intendente de la ciudad quiere reducir además el tiempo del recorrido matutino del colectivo, para lo cual ofreció cambiar la mano de todas las calles que sea necesario, con el fin de que el trayecto sea mínimo.<br />
Antes de concretar la medida el intendente quiere saber el largo resultante y las calles a modificar para lograr el mínimo recorrido. Puedes ayudarle escribiendo un programa cambio.pas, cambio.cpp o cambio.c que evalúe la distancia que surja tras realizar los cambios de sentido y la individualización de las calles que debieran cambiar.<br />

---

DATOS DE ENTRADA

---

Se recibe un archivo cambio.in con el siguiente formato:

-- Una línea con el número E ( 1 ≤ E ≤ 80.000) de esquinas, el número de la esquina de donde parte el colectivo, y con el número de la esquina donde se ubica la escuela<br />
-- Una línea con el número C ( 1 ≤ C ≤ 250.000) de calles<br />
-- C líneas que describen las calles con tres números<br />
-- El primer número es la esquina de salida de la calle (siguiendo su mano)<br />
-- El segundo es la esquina de llegada<br />
-- El tercero es la distancia D de la calle en decámetros (1 ≤ D ≤ 50)<br />

---

DATOS DE SALIDA

---

Se debe generar un archivo cambio.out conteniendo:

-- Una línea con la distancia, expresada en decámetros, del recorrido más corto que se puede lograr aplicando cambios de mano a ciertas calles.<br />
-- Una línea con los números de calles que deben cambiar de mano separados por un espacio. A tal efecto hay que tener en cuenta que las calles están numeradas por el orden de su descripción, comenzando con 1.<br />

---

EJEMPLO

---

Dado el input:

8 2 7<br />
13<br />
2 4 4<br />
2 1 5<br />
2 3 2<br />
3 1 3<br />
4 1 4<br />
7 5 3<br />
1 5 3<br />
1 6 7<br />
8 4 2<br />
6 8 1<br />
8 7 6<br />
6 7 8<br />
5 3 2<br />

El resultado esperado es:

7<br />
6 13<br />
