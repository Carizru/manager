---
description: >-
  Cómo se produce un KO, qué ocurre con los Stocks, cómo se gana la partida y
  cómo se resuelven los empates por KO simultáneo.
---

# Knockouts and Winning the Game

Un **Knockout** (KO) es el evento que hace avanzar la partida hacia su final: cada KO consume una reserva (**Stock**) del equipo afectado y, cuando un equipo se queda sin Stocks, la partida termina de inmediato.

Este capítulo define **cuándo** se produce un KO, **qué consecuencias** tiene, **cómo se gana** la partida y **cómo se resuelve** el caso excepcional de varios KO simultáneos.

> **Requisito previo:** este capítulo asume que ya conoces la resolución de fichas de Empuje descrita en [Push](push.md) y la estructura de rondas y secuencias explicada en [Gameplay](gameplay.md).

***

## 1. Qué es un Knockout

Una Leyenda es **noqueada** cuando termina **una o más casillas más allá de un borde** de la Arena.

Los bordes son las dos cartas de los extremos de la Arena. Quedar **sobre** el borde no es un KO; el KO exige **rebasarlo**.

### Formas de provocar un KO

| Origen                | Cuándo se comprueba                          | Descripción                                                                                    |
| --------------------- | -------------------------------------------- | ---------------------------------------------------------------------------------------------- |
| **Empuje (Push)**     | Al final de cada ronda, en la fase de Empuje | Las fichas de Empuje acumuladas desplazan a la Leyenda más allá del borde. Es la vía habitual. |
| **Movimiento (Move)** | Al resolver el efecto de la carta            | Una Leyenda puede rebasar el borde por su propio movimiento y **auto-noquearse**.               |
| **Efectos de carta**  | Al resolver el efecto de la carta            | Cualquier efecto que mueva o empuje a una Leyenda puede sacarla de la Arena.                    |

> **Atención:** el Empuje se resuelve **al final de cada ronda**, no al final de la secuencia. Una Leyenda puede ser noqueada en la ronda 1 de una secuencia sin llegar a jugar sus cartas 2 y 3.

***

## 2. Resolución del Empuje y comprobación del KO

La fase de Empuje sigue siempre estos tres pasos, **en este orden**:

| Paso | Nombre                                   | Efecto                                                                                                                      |
| ---- | ---------------------------------------- | --------------------------------------------------------------------------------------------------------------------------- |
| 1    | **Empujar** (*Push*)                     | Por cada ficha de Empuje, mueve a la Leyenda una casilla en la dirección de la ficha. Después retira todas las fichas.        |
| 2    | **Agarrarse al borde** (*Grab the edge*) | Si la Leyenda ha quedado **exactamente sobre** un borde, gira hacia el centro de la Arena y avanza 1 casilla. **No hay KO.** |
| 3    | **¡Knockout!**                           | Si la Leyenda ha quedado **1 o más casillas más allá** del borde, es noqueada.                                               |

> **Fichas opuestas:** las fichas de Empuje en direcciones contrarias se cancelan. Si una Leyenda acumula fichas en ambos sentidos, retira una de cada dirección hasta que todas apunten al mismo lado.

***

## 3. Consecuencias de un Knockout

Cuando tu Leyenda es noqueada ocurre **una** de estas dos cosas:

### 3.1. Tu equipo conserva al menos 1 Stock

1. Retira **un Stock** de la reserva de tu equipo.
2. Coloca tu peana (*standee*) en la casilla donde está el **Portal** de tu equipo.
3. Elige **libremente** la dirección hacia la que mira tu Leyenda.

> La Leyenda **conserva su Fatiga acumulada**: volver a la Arena no reinicia el marcador de Fatiga.

### 3.2. Tu equipo no tiene Stocks

El equipo contrario **gana la partida inmediatamente**. No se resuelve el resto de la ronda ni de la secuencia.

***

## 4. Stocks y condición de victoria

Los Stocks son las «vidas» compartidas del equipo. Su cantidad inicial depende del formato de la partida:

| Formato | Stocks por equipo | KO necesarios para ganar |
| ------- | ----------------- | ------------------------ |
| **1v1** | 1                 | 2                        |
| **2v2** | 2                 | 3                        |
| **3v3** | 3                 | 4                        |

> **Cómo leer la tabla:** los Stocks absorben los primeros KO. El KO que gana la partida es el que se produce cuando el rival ya está a 0 Stocks; de ahí que hagan falta *Stocks + 1* KO.

**Condición de victoria:** gana el equipo que provoque un KO a un rival que ya no tenga Stocks en su reserva.

***

***
