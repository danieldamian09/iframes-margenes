# Archivo final-status.html

## Detalle

## Premio de Compras

### Linea 44 Icono Desafío de Tareas estado condicional:

```html
<!--! Estado Condicional  -->
                <div class="icon__task">
                  <img class="task" src="./assets/img/box-desafio.png" alt="Icono Desafio Tareas">
                  <!--! Estado Condicional  -->
                  <img class="checked" src="./assets/img/checked.png" alt="Icono Cheked">
                </div>
```

Estado en el CSS linea 139-154

```css
/* Clase para el estado INICIAL del Desafio Tareas y Meta de Compras */
.icon__task {
	background-color: var(--start);
	width: 49px;
	height: 49px;
	display: flex;
	flex-direction: column;
	justify-content: center;
	align-items: center;
	border-radius: 50%;
	position: relative;
}

/* clase una vez realizado el Desafio Tareas y Meta de Compras */
.icon__task-end {
	background-color: var(--end);
}
```

### Linea 48 Checked Desafío de Tareas estado condicional:

```html
<!--! Estado Condicional  -->
                  <img class="checked" src="./assets/img/checked.png" alt="Icono Cheked">
```

Estado en el CSS linea 156-167

```css
/* Clase para el estado INICIAL de Checked */
.checked {
	display: none;
	position: absolute;
	top: -2px;
	right: -2px;
}

/*  Clase para el estado REALIZADO de Checked */
.checked-end {
	display: inline-block;
}
```

### Linea 59 Icono Meta de Compras estado condicional:

```html
<div class="icon__task">
                  <img class="task" src="./assets/img/box-cesta.png" alt="Icono Meta de Compras">
                  <!--! Estado Condicional  -->
                  <img class="checked" src="./assets/img/checked.png" alt="Icono Cheked">
                </div>
```

Estado en el CSS linea 139-154

```css
/* Clase para el estado INICIAL del Desafio Tareas y Meta de Compras */
.icon__task {
	background-color: var(--start);
	width: 49px;
	height: 49px;
	display: flex;
	flex-direction: column;
	justify-content: center;
	align-items: center;
	border-radius: 50%;
	position: relative;
}

/* clase una vez realizado el Desafio Tareas y Meta de Compras */
.icon__task-end {
	background-color: var(--end);
}
```

### Linea 62 Checked Meta de Compras estado condicional:

```html
<!--! Estado Condicional  -->
                  <img class="checked" src="./assets/img/checked.png" alt="Icono Cheked">
```

Estado en el CSS linea 156-167

```css
/* Clase para el estado INICIAL de Checked */
.checked {
	display: none;
	position: absolute;
	top: -2px;
	right: -2px;
}

/*  Clase para el estado REALIZADO de Checked */
.checked-end {
	display: inline-block;
}
```

### Linea 74 Premio  Compras estado condicional:

```html
<!--! Estado Condicional  -->
                  <img class="prize" src="./assets/img/box-premio.png" alt="Icono Premio">
```

Estado en el CSS linea 178-187

```css
/* Clase para el estado INICIAL del Premio */
.prize {
	filter: grayscale(100%);
	-webkit-filter: grayscale(100%);
}

/* clase una vez REALIZADO el Premio */
.prize-end {
	filter: grayscale(0%);
	-webkit-filter: grayscale(0%);
}
```

### Linea 77 Texto Premio  Compras estado condicional:

```html
<!--! Estado Condicional  -->
                <p class="icon__prize">Premio de compras</p>
```

Estado en el CSS linea 190-201

```css
/* Clase para el estado INICIAL del Texto Premio */
.icon__prize {
	font-size: 12px;
	width: 90%;
	text-align: center;
	color: var(--gray);
	margin-top: 5px;
	font-weight: 700;
}
/* clase una vez REALIZADO el Texto Premio */
.icon__prize-end {
	color: var(--red);
}
```

## Premio de 1C1P

### Linea 115 Icono Desafío de Tareas estado condicional:

```html
							<div class="icon__task">
                  <img class="task" src="./assets/img/box-desafio.png" alt="Icono Meta de Compras">
                  <img class="checked" src="./assets/img/checked.png" alt="Icono Cheked">
                </div>
```

Estado en el CSS linea 139-154

```css
/* Clase para el estado INICIAL del Desafio Tareas y Meta de Compras */
.icon__task {
	background-color: var(--start);
	width: 49px;
	height: 49px;
	display: flex;
	flex-direction: column;
	justify-content: center;
	align-items: center;
	border-radius: 50%;
	position: relative;
}

/* clase una vez realizado el Desafio Tareas y Meta de Compras */
.icon__task-end {
	background-color: var(--end);
}
```

### Linea 117 Checked Desafío de Tareas estado condicional

```html
<!--! Estado Condicional  -->
                  <img class="checked" src="./assets/img/checked.png" alt="Icono Cheked">
```

Estado en el CSS linea 156-167

```css
/* Clase para el estado INICIAL de Checked */
.checked {
	display: none;
	position: absolute;
	top: -2px;
	right: -2px;
}

/*  Clase para el estado REALIZADO de Checked */
.checked-end {
	display: inline-block;
}
```

### Linea 129 Icono Meta 1C1P estado condicional:

```html
<!--! Estado Condicional  -->
                <div class="icon__task">
                  <img class="task" src="./assets/img/box-1C1P.png" alt="Icono Carrito">
                  <img class="checked" src="./assets/img/checked.png" alt="cono Cheked">
                </div>
```

Estado en el CSS linea 139-154

```css
/* Clase para el estado INICIAL del Desafio Tareas y Meta de Compras */
.icon__task {
	background-color: var(--start);
	width: 49px;
	height: 49px;
	display: flex;
	flex-direction: column;
	justify-content: center;
	align-items: center;
	border-radius: 50%;
	position: relative;
}

/* clase una vez realizado el Desafio Tareas y Meta de Compras */
.icon__task-end {
	background-color: var(--end);
}
```

### Linea 132 Checked Meta 1C1P estado condicional

```html
<!--! Estado Condicional  -->
                  <img class="checked" src="./assets/img/checked.png" alt="Icono Cheked">
```

Estado en el CSS linea 156-167

```css
/* Clase para el estado INICIAL de Checked */
.checked {
	display: none;
	position: absolute;
	top: -2px;
	right: -2px;
}

/*  Clase para el estado REALIZADO de Checked */
.checked-end {
	display: inline-block;
}
```

### Linea 144 Premio  1C1P estado condicional:

```html
<!--! Estado Condicional  -->
                  <img class="prize" src="./assets/img/box-premio.png" alt="Icono Premio">
```

Estado en el CSS linea 178-187

```css
/* Clase para el estado INICIAL del Premio */
.prize {
	filter: grayscale(100%);
	-webkit-filter: grayscale(100%);
}

/* clase una vez REALIZADO el Premio */
.prize-end {
	filter: grayscale(0%);
	-webkit-filter: grayscale(0%);
}
```

### Linea 147 Texto Premio  1C1P estado condicional:

```html
<!--! Estado Condicional  -->
                <p class="icon__prize">Premio de compras</p>
```

Estado en el CSS linea 190-201

```css
/* Clase para el estado INICIAL del Texto Premio */
.icon__prize {
	font-size: 12px;
	width: 90%;
	text-align: center;
	color: var(--gray);
	margin-top: 5px;
	font-weight: 700;
}
/* clase una vez REALIZADO el Texto Premio */
.icon__prize-end {
	color: var(--red);
}
```

## Premio de Bonus

### Linea 192 Icono Desafío de Tareas estado condicional:

```html
							<div class="icon__task">
                  <img class="task" src="./assets/img/box-desafio.png" alt="Icono Meta de Compras">
                  <img class="checked" src="./assets/img/checked.png" alt="Icono Cheked">
                </div>
```

Estado en el CSS linea 139-154

```css
/* Clase para el estado INICIAL del Desafio Tareas y Meta de Compras */
.icon__task {
	background-color: var(--start);
	width: 49px;
	height: 49px;
	display: flex;
	flex-direction: column;
	justify-content: center;
	align-items: center;
	border-radius: 50%;
	position: relative;
}

/* clase una vez realizado el Desafio Tareas y Meta de Compras */
.icon__task-end {
	background-color: var(--end);
}
```

### Linea 195 Checked Desafío de Tareas estado condicional

```html
<!--! Estado Condicional  -->
                  <img class="checked" src="./assets/img/checked.png" alt="Icono Cheked">
```

Estado en el CSS linea 156-167

```css
/* Clase para el estado INICIAL de Checked */
.checked {
	display: none;
	position: absolute;
	top: -2px;
	right: -2px;
}

/*  Clase para el estado REALIZADO de Checked */
.checked-end {
	display: inline-block;
}
```

### Linea 206 Premio  Meta Marcas estado condicional:

```html
<!--! Estado Condicional  -->
                <div class="icon__task">
                  <img class="task" src="./assets/img/box-marcas.png" alt="Icono Marca">
                  <!--! Estado Condicional -->
                  <img class="checked" src="./assets/img/checked.png" alt="Icono Cheked">
                </div>
```

Estado en el CSS linea 139-154

```css
/* Clase para el estado INICIAL del Desafio Tareas y Meta de Compras */
.icon__task {
	background-color: var(--start);
	width: 49px;
	height: 49px;
	display: flex;
	flex-direction: column;
	justify-content: center;
	align-items: center;
	border-radius: 50%;
	position: relative;
}

/* clase una vez realizado el Desafio Tareas y Meta de Compras */
.icon__task-end {
	background-color: var(--end);
}
```

### Linea 209 Checked Desafío de Tareas estado condicional

```html
<!--! Estado Condicional  -->
                  <img class="checked" src="./assets/img/checked.png" alt="Icono Cheked">
```

Estado en el CSS linea 156-167

```css
/* Clase para el estado INICIAL de Checked */
.checked {
	display: none;
	position: absolute;
	top: -2px;
	right: -2px;
}

/*  Clase para el estado REALIZADO de Checked */
.checked-end {
	display: inline-block;
}
```

### Linea 221 Premio  Bonus estado condicional:

```html
<!--! Estado Condicional  -->
                  <img class="prize" src="./assets/img/box-premio.png" alt="Icono Premio">
```

Estado en el CSS linea 178-187

```css
/* Clase para el estado INICIAL del Premio */
.prize {
	filter: grayscale(100%);
	-webkit-filter: grayscale(100%);
}

/* clase una vez REALIZADO el Premio */
.prize-end {
	filter: grayscale(0%);
	-webkit-filter: grayscale(0%);
}
```

### Linea 224 Texto Premio  Bonus estado condicional:

```html
<!-- !Estado Condicional -->
                <p class="icon__prize">Premio Bonus</p>
```

Estado en el CSS linea 190-201

```css
/* Clase para el estado INICIAL del Texto Premio */
.icon__prize {
	font-size: 12px;
	width: 90%;
	text-align: center;
	color: var(--gray);
	margin-top: 5px;
	font-weight: 700;
}
/* clase una vez REALIZADO el Texto Premio */
.icon__prize-end {
	color: var(--red);
}
```