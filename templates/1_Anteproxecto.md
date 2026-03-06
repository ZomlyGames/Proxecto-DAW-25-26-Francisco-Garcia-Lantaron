# Anteproxecto

- [Anteproxecto](#anteproxecto)
  - [1- Idea del proyecto](#1--idea-del-proyecto)
  - [2- Contextualización](#2--contextualización)
  - [3- Estudio de alternativas y viabilidad](#3--estudio-de-alternativas-y-viabilidad)
    - [3.1- Estudio de alternativas](#31--estudio-de-alternativas)
    - [3.2 Justificación de la alternativa](#32-justificación-de-la-alternativa)
  - [4- Requisitos técnicos](#4--requisitos-técnicos)
  - [5- Planificación](#5--planificación)

> _EXPLICACIÓN_: Este documento será a páxina de explicación de en que consiste o teu proxecto. Coida a súa redacción con todo ou teu mimo. Elimina posteriormente todas as lineas "EXPLICACIÓN" cando creas finalizada a súa redacción.
> Podes acompañar á redacción deste ficheiro con imaxes, pero non abuses deles.
> Explica da mellor forma posible de en que consiste o proxecto é que ferramentas e linguaxes de programación empregarás.

## 1- Idea del proyecto

El proyecto está enfocado en la creación de un sitio web dedicado a la venta de merchandising del canal [zomly Games](https://www.youtube.com/c/zomlyGames), del cual soy propietario, ubicado en la plataforma de vídeo YouTube. Merchandising hace referencia a productos licenciados, aquellos que se venden apoyados en la marca de otro producto o servicio. En este caso, estos productos estarían apoyados por la marca de mi canal.

## 2- Contextualización

Este proyecto surge como respuesta a la necesidad del canal de publicitarse y de generar ingresos. Consistirá principalmente en un punto de venta online donde se ofrecerá a los posibles clientes productos exclusivos y únicos que contendrán el logotipo y/o nombre del canal, tales como camisetas, chapas, sudaderas, viseras, etc. De esta manera, no solo se consigue el objetivo de dar más visibilidad a la marca, si no que, a la vez, se puede convertir en una fuente pasiva de ingresos para el canal.

Esta aplicación abrirá la oportunidad de negocio, ya que, como mencioné antes, el objetivo principal de esta es vender productos. Además, será posible comercializarla mediante estrategias relativas a las características de los productos, al precio y la competencia, a la distribución y a las estrategias de comunicación y promoción.

Las estrategias relacionadas con las características de los productos se compondrán de: una variedad de artículos distintos para adaptarse a cada cliente (si solo vendiese, por ejemplo, viseras, cualquier persona que no use viseras en su vida cotidiana no estaría interesada en comprar en la web), de un precio acorde al valor de la marca (cuánto más popular sea la marca, mayores serán los precios y viceversa) y de unos materiales de buena calidad, pero a la vez asequibles. Una característica extra que también mencioné en otros apartados, pero que considero importante mencionar aquí es que la principal característica de estos productos (por encima de las anteriormente mencionadas) es que estos productos son únicos, es decir que ninguna otra persona, entidad o empresa podrá crear productos como estos, y exclusivos, ya que solo podrá existir 1 único sitio web como este y solo este podrá vender los productos.

En relación a la competencia, como tal no existirá competencia de los productos en sí mismos o de la web ya que son únicos, si no que más bien sería cuestión de la competencia que suponen otros creadores de contenido al crecimiento de mi canal, lo cual está estrechamente relacionado con las ventas y popularidad de los propios productos.

Por último, quedarían por determinar las estrategias de distribución y promoción. Estos productos se fabricarán y distribuirán mediante la contratación de los servicios de empresas de creación de merchandising/productos a medida y de empresas de reparto respectivamente. La promoción del sitio web se haría en los propios vídeos del canal de YouTube y en otras plataformas de redes sociales. También se podrían llevar a cabo ventas de productos por tiempo limitado de colaboraciones con otros creadores de contenido, entre otros métodos para publicitar la web y sus productos.

## 3- Estudio de alternativas y viabilidad

### 3.1- Estudio de alternativas

Mi canal de YouTube precisa un sitio web para vender merchandising a los subscriptores. Analizo tres alternativas para su desarrollo:

Alternativas

- A1- Framework Angular + Firebase + Firestore
- A2- Framework Angular + NestJS (Backend con TypeScript)
- A3- Desarrollo desde cero modelo MVC en php + HTML5 + CSS3 + javascript nativo.
- A4- Desarrollo desde cero con API Rest Node.js + HTML5 + CSS3 + javascript nativo

| **Alternativa** | **Viabilidad técnica** | **Viabilidad económica** | **Temporalidad** | **Valoración Global** |
| ------ | ------ | ------ | ------ | ------ |
| A1 | Media (5/10): Angular usa TypeScript que en pocas palabras es JavaScript pero con tipado estricto (siendo en tiempo de compilación, a diferencia de JS que es en tiempo de ejecución), por lo tanto esto sería sencillo de aprender, pero debido a que Angular cuenta con muchas funcionalidades y conceptos nuevos (componentes, subscripciones, pipes, etc) esta opción acaba teniendo una curva de aprendizaje considerable. Firebase y Firestore no tienen una curva de aprendizaje importante (no necesitas gestionar ni configurar servidores ni infraestructura).**Fortalezas**: Escalable, simplicidad en el bakckend y frontend organizado (html+css+TypeScript dividido en componentes). **Debilidades**: Curva de aprendizaxe importante. | Alta (8/10): Requiere comprar un dominio y configurarlo en Firebase Hosting, el resto de aspectos son gratuitos pero limitados hasta cierto punto (a partir de cierta cantidad de recursos que se necesiten en la web, habrá que pagar por hosting, almacenamiento, nº usuarios activos, etc). | Viabilidad media (5/10): curva de aprendizaxe de Angular. Duración entre 3 y 4 meses | **6/10** |
| A2 | Baja (3/10): NestJS usa TypeScript, por lo tanto esto sería sencillo de aprender, pero debido a que NodeJS cuenta con funcionalidades y conceptos similares a Angular y que además esta alternativa también incluye Angular para frontend acaba teniendo una curva de aprendizaje muy elevada. **Fortalezas:** Estructura organizada tanto en frontend como en backend y también escalable. **Debilidades:** Exceso de complejidad para un solo desarrollador sin experiencia en frameworks. | Media (6/10): Herramentas gratuitas. Requiere Hosting del backend entre 5-7€/mes, adquirir dominio y certificados SSL (la Alternativa 1 no necesita SSL ya que Firebase lo proporciona gratuitamente por defecto). | Viabilidad baja (3/10): curva de aprendizaxe elevada (4-5 meses) | **4/10** |
| A3 | Alta (9/10): non existe curva de aprendizaxe coas linguaxes seleccionadas. **Fortalezas:** Linguaxe coñecido, baixo limiar de entrada, execución rápida. **Debilidades:** Require implementar manualmente aspectos como seguridade, rutas y validacións. | Alta (9/10): Hosting compartido PHP/MySQL dende 2–5 €/mes. | Viabilidad alta (8/10): desenvolvemento e despregue rápido, de 2 a 3 meses. | **9/10** |
| A4 | Media-Alta (6/10): Node permite construír APIs REST facilmente. **Fortalezas:** Simplicidade, entorno JavaScript unificado (backend e frontend). **Debilidades:** Necesidade de estruturar ben o proxecto dende cero. | Alta (8/10): Require hosting compatible con Node.js (plataformas como Render, Railway, Verceo o Fly.io) permiten despregar de forma gratuita ou de baixo custe. | Viabilidad media (6/10): duración entre 2 meses e medio e 4. | **7/10** |

### 3.2 Justificación de la alternativa

>_EXPLICACIÓN_: Tras analizar os resultados seleccionamos unha alternativa. Xustifica a elección indicando as razóns da elección.
>
> **Exemplo**
>
> - A alternativa A3 (PHP MVC desde cero) se consolida como a máis viable globalmente, e polo tanto é a elexida xa que:
>
>   - É a máis económica (hosting moi barato).
>   - Ten mínima fricción técnica para o despregue.
>   - Permite obter un prototipo funcional en pouco tempo.
>   - Emprega tecnoloxías coñecidas polo alumno.
>   - Rapidez de desenvolvemento.
>
> - A2 (Node.js) poderíase considerar como unha opción moderna e máis axeitada se se dispuxera de máis tempo para implementala. Permitiría ampliar os coñecementos técnicos.
>
> - As opcións A1 (Spring Boot) e A4 (Larabel + React) resultan menos axeitadas pola súa complexidade e custo.

## 4- Requisitos técnicos

>_EXPLICACIÓN_: - Que tecnoloxías son as máis axeitadas para a realización do proxecto?
> _EXPLICACIÓN_: Descrición dos medios materiais e das tecnoloxías necesarias que se usarán para desenvolver o proxecto incluíndo as linguaxes de programación frontend e backend, técnicas, librerías, bases de datos, servizos usados, servidores, API’s, etc.
>
> - **Infraestructura:** dominio web, hosting, servidor de base de datos, almacenamento, memoria, ...
> - **Backend:** tecnoloxías usadas.
> - **Frontend:** tecnoloxías usadas

## 5- Planificación

> _EXPLICACIÓN_: Inclúe un calendario co tempo estimado a adicar a cada fase do proxecto.
>
> O proxecto estará formado polas seguintes fases:
>
> - Estudo preliminar
> - Análise
> - Deseño
> - Codificación e probas (debe ser a fase máis longa).
>
> Debe facerse un calendario ou un diagrama de Gantt indicando, para cada fase, a data de inicio, a súa duración e breve descrición das tarefas a realizar.

[**<-Anterior**](../README.md)
