# 03-shorthand-grid-y-grid-area
shorthand grid en contenedor padre. shorthand grid-area contenedor de hijos
*  Grid: row row / column columns columns 
*  grid: 50% 50% / 33% 33% 33%

*  grid-area shorthands. primero es row de inicio / sigue la column de start / row end / column end
*   grid-area: 1 / 1 / 3 / 2;

```javascript
.servicios {
    border: 3px solid black;
    height: 300px;
    display: grid;
    /* grid-template-columns:  33% 33% 33%;
    grid-template-rows: 50% 50%; */

    /* grid Shorhands de grid-template-columns y grid-template-rows */
    /* Grid: row row / column columns columns */
    grid: 50% 50% / 33% 33% 33%
}

.servicio {
    color: white;
    text-align: center;
}

.servicio-1 {
    background-color: darkviolet;
    /* para establecer el espacio que ocupará */
    /* grid-row-start: 1;
    grid-row-end: 3;
    grid-column-start: 1;
    grid-column-end: 2; */

    /*shorthand para realizar la tarea*/
    /* grid-row: 1 / 3;
    grid-column: 1 / 2; */

    /* grid-area shorthands. primero es row de inicio / sigue la column de start / row end / column end*/
    grid-area: 1 / 1 / 3 / 2;

}
```
