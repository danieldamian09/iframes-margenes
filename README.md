# Archivo final-info.html

# Detalles

## Titulo qué debes hacer para ganar en

### Linea 33 Campo dinámico: “Mes” :

```html
<!--!Campo Dinamico current__month -->
<h3 class="task__title">Qué debes hacer para ganar en <span class="current__month">Mayo</span></h3>
```

## Slider

### Linea 74 Slider campo dinámico “Meta de compras”:

```html
<!--! Campo Dinamico  -->
<p class="swiper__goal">Compra <span class="current__buy">8</span> paquetes</p>
</div>
```

### Linea 85 Slider campo dinámico “Meta 1C1P”:

```html
<!--! Campo Dinamico  -->
<p class="swiper__goal">Realiza <span class="current__oneClick">2</span> pedidos</p>
```

## Tabla con los 3 Objetivos

### Linea 107 Tabla de Objetivos campo dinámico “Mes”:

```html
<!--! Campo dinamico  -->
<h3 class="table__title">Tabla de objetivos de  <span class="current__month">Mayo</span></h3>
```

### Linea 113 Card Desafío de Tareas estado condicional:

```html
<!--! Estado Condicional -->
<div class="task__card">
```

Estados en el CSS desde linea 292-313

```css
/* Estado Condicional INICIAL para la Card Desafio de tareas */
.task__card {
	width: 95%;
	max-width: 309px;
	margin: 17px auto;
	background: #e3ecea;
	padding: 25px 0;
	border-radius: 5px;
	-webkit-border-radius: 5px;
	-moz-border-radius: 5px;
	-ms-border-radius: 5px;
	-o-border-radius: 5px;
}
/* Estado Condicional PROCESO para la Card Desafio de tareas  */
.task__card-process {
	background-color: #fff0d9;
}

/* Estado Condicional REALIZADO para la Card Desafio de tareas  */
.task__card-effective {
	background-color: #effbed;
}
```

### Linea 116 Circulo del Icono Desafío de Tareas estado condicional:

```html
<!--! Estado Condicional -->
<div class="task__circle">
```

Estados en el CSS linea 322-351

```css
/* Estado Condicional INICIAL para el Circulo del Icono Card Desafio de tareas */
.task__circle {
	display: flex;
	justify-content: center;
	align-items: center;
	width: 70px;
	height: 70px;
	margin: 0 auto;
	background-color: #e3ecea;
	border-radius: 50%;
	border: solid 4px #b9d5ee;
}

/* Estado Condicional PROCESO para el Circulo del Icono Card Desafio de tareas */
.task__circle-process {
	background-color: #fff0d9;
	border-color: #f79429;
	border-left-color: transparent;
	transform: rotate(45deg);
	-webkit-transform: rotate(45deg);
	-moz-transform: rotate(45deg);
	-ms-transform: rotate(45deg);
	-o-transform: rotate(45deg);
}

/* Estado Condicional REALIZADO para el Circulo del Icono Card Desafio de tareas */
.task__circle-effective {
	background-color: #effbed;
	border-color: #3eb22b;
}
```

### Linea 118 SVG Icono Desafío de Tareas estado condicional:

```html
<svg class="task__imgDiferent" width="32" height="30" fill="none" xmlns="http://www.w3.org/2000/svg">
  <path
    d="M27.36 15.207c-.13 0-.13 0-.258-.136-.13-.136-.13-.271 0-.407l2.194-1.9c.387-.407.645-.814.645-1.492 0-.543-.13-.95-.516-1.357l-1.807-2.30135-.13-.27 0-.407 0 0 .129-.135.258-.135.903.135 1.936-.136 2.581-.814 1.42-1.222 1.549-3.528.387-5.02C29.683-.262 27.49-.398 26.07.823a3.410 0 0-1.161 2.578c0 .136 0 .136-.13.272-.128.135-.258.135-.386 0l-2.065-2.578a1.36 1.36 0 0 0-.904-.407c-.516 0-1.032.135-1.42.407l-8 7.19c-.2517.544-.646.95-.387 0-.645.272-1.033.408l-2.194 1.9c-.129.135-.258.135-.387 0 0 0-.129-.136-.129-.272.13-.95-.129-2.035-.774-2.714-1.162-355-1.628-4.775-.407-1.42 1.221-1.549 3.528-.387 5.02.645.815 1.548 1.222 2.452 1.222.129 0 .129 0 .258.135.129.136.129.272 0 .407l-2.194 1.814-.645 2.035 0 2.985L4 22.127c.129.135.129.271 0 .407 0 0-.13.135-.258.135-.904-.135-1.936.136-2.581.814C.516 24.162 0 24.976 0 25.927s.258 2.578c.646.678 1.42 1.221 2.323 1.221h.258c.775 0 1.55-.271 2.194-.814a3.412 3.412 0 0 0 1.162-2.578c0-.136 0-.136.129-.271.129-.136.258-.136.807 2.306c.645.814 1.936.95 2.71.272l8.002-7.192c.258-.271.516-.542.645-.95.387 0 .645-.135 1.032-.407l2.194-1.9c.13-.135.258-.135.387 0 0 0 13.272-.13.95.128 2.035.774 2.714 1.161 1.492 3.355 1.628 4.775.407 1.42-1.221 1.548-3.528.387-5.02-.904-.95-1.807-1.357-2.71-1.357Zm-8.776 002 7.191h-.258L8.39 24.705c-.517-.543-1.162-.814-1.807-.679-.387.136-.645.272-.904.407-.387.407-.645.95-.645 1.493 0 .543-.258.95-.516 1.3271-.774.407-1.162.407-.387 0-.774-.272-1.032-.543-.516-.407-.645-.814-.645-1.221 0-.407.258-.814.516-1.221.387-.272.774-.407 1.161-.407h.388a0 0 0 1.548-.543c.13-.136.258-.407.387-.814.259-.679.13-1.493-.387-2.171l-1.807-2.307v-.271l2.194-2.035c.517-.543.775-1.222.646-2.036-.13-.40678-.387-.95a3.036 3.036 0 0 0-1.42-.814c-.516 0-.903-.27-1.29-.542-.517-.679-.517-1.764.128-2.443a1.709 1.709 0 0 1 2.323.136c.259.407.517.9493 0 .542.129 1.085.516 1.628.258.271.516.543.903.678.645.272 1.42.136 2.065-.407l2.194-1.9h.258l1.936 2.307v.136s0 .136-.13.136c0 0-.128.1135-.904-.135-1.936.136-2.581.814-1.033.95-1.42 2.443-1.033 3.8.13.407.387.814.646 1.22 1.161 1.493 3.355 1.629 4.775.408a3.413 3.413 0 0 0 578c0-.136 0-.136.13-.272.128-.135.257-.135.386 0l1.936 2.307c-.258.271-.258.407-.387.407Zm9.68.136a1.709 1.709 0 0 1-2.324-.136c-.258-.407-.5387-1.492 0-.543-.13-1.086-.516-1.629-.258-.271-.517-.542-.904-.678-.258-.136-.516-.136-.645-.136-.516 0-.903.136-1.29.543l-2.194 1.9h-.259L102c-.517-.543-1.162-.814-1.807-.679-.387.136-.645.272-.903.407-.388.408-.646.95-.646 1.493 0 .543-.258.95-.516 1.357a1.708 1.708 0 0 1-2.32313-.136-.258-.407-.258-.543-.13-.678 0-1.356.516-1.763.387-.272.904-.543 1.42-.408a2.4 2.4 0 0 0 1.548-.542c.259-.272.517-.543.646-.95 0-.1271.129-.543v-.542c0-.408-.13-.679-.516-1.086L13.293 9.78v-.27l7.872-6.92h.258l1.936 2.306c.516.543 1.161.814 1.807.678.387-.135.645-.271.9387-.407.646-.95.646-1.492 0-.543.258-.95.516-1.357.387-.272.774-.407 1.161-.407s.774.271 1.033.542c.516.679.516 1.764-.13 2.443-.129.271-.6416.407a2.4 2.4 0 0 0-1.55.543c-.258.135-.387.407-.516.814a2.257 2.257 0 0 0 .258 2.035l1.936 2.307v.271l-2.194 2.035c-.516.543-.774 1.221-.645 1.9.129.407.258.678.387.95.387.407.904.678 1.42.678.516 0 .903.271 1.29.543.517.95.517 2.035-.258 2.578Z"
    fill="#91B7D9" />
</svg>
```

Estado en el CSS linea 353-370

```css
/*! Estado Condicional PROCESO para el Icono de Card Desafio de tareas DIFERENTE POR EL SVG */
.task__imgDiferent-process path {
	fill: #f79429;
}

/*! Estado Condicional REALIZADO para el Icono de Card Desafio de tareas DIFERENTE POR EL SVG */
.task__imgDiferent-effective path {
	fill: #3eb22b;
}

/*! Estado Condicional PROCESO para el Icono de Card Desafio de tareas DIFERENTE POR EL SVG  */
.task__imgDiferent-process {
	transform: rotate(-45deg);
	-webkit-transform: rotate(-45deg);
	-moz-transform: rotate(-45deg);
	-ms-transform: rotate(-45deg);
	-o-transform: rotate(-45deg);
}
```

### Linea 126 Titulo Desafío de Tareas estado condicional:

```html
<!--! Estado Condicional -->
<p class="task__challenge">Desafío de tareas:</p>
```

Estado en el CSS linea 392-406

```css
/* Estado Condicional INICIAL para el texto de Card Desafio de tareas */
.task__challenge {
	font-size: 15px;
	color: #91b7d9;
	font-weight: 600;
}

/* Estado Condicional PROCESO para el texto de Card Desafio de tareas */
.task__challenge-process {
	color: #f79429;
}

/* Estado Condicional REALIZADO para el texto de Card Desafio de tareas */
.task__challenge-effective {
	color: #3eb22b;
}
```

### Linea 128 Mensaje de Felicitaciones estado condicional:

```html
<!--! Estado Condicional -->
<p class="task__congratulations">¡COMPLETADO!</p>
```

Estado en el CSS linea  409-421

```css
/* Estado Condicional INICIAL para Felicitaciones de Card Desafio de tareas */
.task__congratulations {
	font-weight: 400;
	font-size: 14px;
	line-height: 14px;
	color: #3eb22b;
	margin: 5px auto;
	display: none;
}

/* Estado Condicional REALIZADO para Felicitaciones de Card Desafio de tareas */
.task__congratulations-effective {
	display: block;
}
```

### Linea 130 Valor Dinámico a realizar para alcanzar meta Desafío de Tareas

```html
<!--! Estado Condicional y Dinamico para "current__task" -->
<p class="task__detail">Realizar <span class="current__task">2</span> tareas en el mes para cumplir este desafío.</p>
```

### Linea 130 Detalle del Desafío de Tareas estado condicional:

```html
<!--! Estado Condicional -->
<p class="task__detail">Realizar 2 tareas en el mes para cumplir este desafío.</p>
```

Estado en el CSS linea 424-440

```css
.task__detail {
	width: 90%;
	font-size: 12px;
	color: #91b7d9;
	font-weight: 400;
	margin-top: 5px;
}

/* Estado Condicional PROCESO para el Detalle de Card Desafio de tareas */
.task__detail-process {
	color: #f79429;
}

/* Estado Condicional REALIZADO para el Detalle de Card Desafio de tareas */
.task__detail-effective {
	display: none;
}
```

### Linea 132 Valor realizado Desafío de Tareas estado condicional:

```html
<!--! Estado Condicional -->
<p class="task__current">Has hecho <span class="task__value">0</span> <span>tarea</span></p>
```

Estado en el CSS linea 443-457

```css
.task__current {
	font-size: 12px;
	color: #91b7d9;
	font-weight: 400;
	margin-top: 10px;
}
/* Estado Condicional PROCESO para el Valor de Card Desafio de tareas */
.task__current-process {
	color: #444444;
}

/* Estado Condicional REALIZADO para el Valor de Card Desafio de tareas */
.task__current-effective {
	color: #444444;
}
```

### Linea 137 Linea Divisora Desafío de Tareas estado condicional:

```html
<div class="task__line"></div>
```

Estado en el CSS linea 465-479

```css
/* Estado Condicional INICIAL para Linea  de Card Desafio de tareas */
.task__line,
.oneClick__line {
	width: 80%;
	height: 1px;
	background-color: #b9d5ee;
	margin: 20px auto;
}
/* Estado Condicional PROCESO para Linea  de Card Desafio de tareas */
.task__line-process {
	background-color: #f79429;
}
/* Estado Condicional REALIZADO para Linea  de Card Desafio de tareas */
.task__line-effective {
	background-color: #3eb22b;
}
```

### Linea 149 Card Meta de Compras estado condicional:

```html
<!--! Estado Condicional -->
<div class="buy__card">
```

Estado en el CSS linea 507-534

```css
/* Estado Condicional INICIAL para la Card Meta de Compras*/
.buy__card,
.oneClick__card {
	width: 95%;
	max-width: 151px;
	background: #e3ecea;
	display: flex;
	flex-direction: column;
	justify-content: center;
	align-items: center;
	padding: 20px 0px 15px;
	border-radius: 5px;
	-webkit-border-radius: 5px;
	-moz-border-radius: 5px;
	-ms-border-radius: 5px;
	-o-border-radius: 5px;
}

/* Estado Condicional PROCESO para la Card Meta de Compras*/
.buy__card-process,
.oneClick__card-process {
	background: #fff0d9;
}

/* Estado Condicional REALIZADO para la Card Meta de Compras*/
.buy__card-effective,
.oneClick__card-effective {
	background: #effbed;
}
```

### Linea 151 Titulo Card Meta de Compras estado condicional:

```html
<!--! Estado Condicional -->
<p class="buy__title">Meta de compras:</p>
```

Estado en el CSS linea 543-561

```css
/* Estado Condicional INICIAL para El Titulo Card Meta de Compras*/
.buy__title,
.oneClick__title {
	font-size: 14px;
	font-weight: 600;
	color: #91b7d9;
	text-align: center;
}

/* Estado Condicional PROCESO para El Titulo Card Meta de Compras*/
.buy__title-process,
.oneClick__title-process {
	color: #df0021;
}

/* Estado Condicional REALIZADO para El Titulo Card Meta de Compras*/
.buy__title-effective,
.oneClick__title-effective {
	color: #444444;
}
```

### Linea 153 Subtitulo Meta de Compras estado condicional:

```html
<!--! Estado Condicional -->
<p class="buy__subtitle">Comprar <span class="current_buy">8</span> paquetes</p>
```

Estado en el CSS linea 564-582

```css
/* Estado Condicional INICIAL para El Subtitulo Card Meta de Compras*/
.buy__subtitle,
.oneClick__subtitle {
	font-size: 11px;
	font-weight: 400;
	color: #91b7d9;
	margin-bottom: 14px;
}

/* Estado Condicional PROCESO para El Subtitulo Card Meta de Compras*/
.buy__subtitle-process,
.oneClick__subtitle-process {
	color: #df0021;
}

/* Estado Condicional REALIZADO para El Subtitulo Card Meta de Compras*/
.buy__subtitle-effective,
.oneClick__subtitle-effective {
	color: #444444;
}
```

### Linea 153 Subtitulo Meta de Compras campo dinámico:

```html
<!--! Estado Condicional -->
<p class="buy__subtitle">Comprar <span class="current_buy">8</span> paquetes</p>
```

### Linea 155 Circulo Icono Meta de Compras estado condicional:

```html
<!--! Estado Condicional -->
<div class="task__circle">
```

Estado en el CSS linea 323-351

```css
/* Estado Condicional INICIAL para el Circulo del Icono Card Desafio de tareas */
.task__circle {
	display: flex;
	justify-content: center;
	align-items: center;
	width: 70px;
	height: 70px;
	margin: 0 auto;
	background-color: #e3ecea;
	border-radius: 50%;
	border: solid 4px #b9d5ee;
}

/* Estado Condicional PROCESO para el Circulo del Icono Card Desafio de tareas */
.task__circle-process {
	background-color: #fff0d9;
	border-color: #f79429;
	border-left-color: transparent;
	transform: rotate(45deg);
	-webkit-transform: rotate(45deg);
	-moz-transform: rotate(45deg);
	-ms-transform: rotate(45deg);
	-o-transform: rotate(45deg);
}

/* Estado Condicional REALIZADO para el Circulo del Icono Card Desafio de tareas */
.task__circle-effective {
	background-color: #effbed;
	border-color: #3eb22b;
}
```

### Linea 157 SVG Icono Meta de Compras estado condicional:

```html
<!--! Estado Condicional -->
<svg class="task__img" width="32" height="34" viewBox="0 0 29 32" fill="none"
  xmlns="http://www.w3.org/2000/svg">
  <path
    d="M14.137 10.3659C13.7843 10.3659 13.498 10.1469 13.498 9.87696V0.488958C13.498 0.219053 13.7843 0 14.137 0C14.4898 0 14.776 0.219053 14.776 0.488958V9.87696C14.776 10.1469 14.4898 10.3659 14.137 10.3659Z"
    fill="#91B7D9" />
  <path
    d="M14.1377 10.624C13.955 10.624 13.7825 10.5453 13.661 10.4085L10.2425 6.53744C10.0073 6.27163 10.0303 5.86387 10.2936 5.62644C10.5568 5.38902 10.9607 5.41224 11.1958 5.67806L14.1377 9.00849L17.0796 5.67806C17.3148 5.41224 17.7186 5.38902 17.9819 5.62644C18.2452 5.86387 18.2682 6.27163 18.033 6.53744L14.6144 10.4085C14.493 10.5453 14.3192 10.624 14.1377 10.624Z"
    fill="#91B7D9" />
  <path
    d="M6.82576 6.77247L6.8295 6.76593L6.83311 6.75931C6.85363 6.72173 6.88918 6.69736 6.92918 6.69111C6.93572 6.69083 6.94243 6.69064 6.94912 6.69055C6.97933 6.69229 7.00887 6.70421 7.03125 6.72328C7.05785 6.74714 7.0742 6.77829 7.07913 6.81025L7.07912 6.81025L7.07966 6.81363C7.085 6.8473 7.07818 6.88243 7.06055 6.91178L7.05632 6.91882L7.05225 6.92594L3.28674 13.5167L2.64568 14.6388H3.93795H24.4188H25.7122L25.0697 13.5162L21.2974 6.92544L21.2975 6.9254L21.2918 6.91589C21.2654 6.87128 21.2638 6.81334 21.2887 6.76638C21.3141 6.72034 21.3588 6.69543 21.4026 6.69407L21.4063 6.69393C21.4297 6.69308 21.4531 6.69857 21.4748 6.71093C21.4967 6.72332 21.5151 6.7415 21.5284 6.76544L21.5284 6.76547L21.533 6.77349L25.8197 14.2614L26.0358 14.6388H26.4706H27.4669C27.4985 14.6392 27.5315 14.6516 27.5588 14.6782C27.585 14.7056 27.6005 14.7431 27.6009 14.7823V18.3959C27.6005 18.439 27.5839 18.4757 27.5589 18.5009C27.5324 18.5276 27.4988 18.5409 27.4659 18.5413H27.3435H26.6945L26.6013 19.1836L24.9409 30.6279C24.9409 30.6284 24.9408 30.6289 24.9407 30.6294C24.935 30.6645 24.9172 30.696 24.8914 30.7185C24.8689 30.738 24.8386 30.75 24.8046 30.75H3.54338C3.51405 30.75 3.48384 30.7394 3.45855 30.7175C3.43428 30.6964 3.41622 30.6656 3.41021 30.6284C3.41013 30.6279 3.41005 30.6274 3.40997 30.6269L1.74961 19.1826L1.65642 18.5403H1.00738H0.889498V18.5403L0.88324 18.5403C0.852757 18.5406 0.819415 18.5284 0.792433 18.5013C0.765545 18.4743 0.75 18.4373 0.75 18.3981V14.78C0.75 14.7405 0.764014 14.7057 0.78751 14.6795L0.787667 14.6793C0.805931 14.6589 0.829576 14.6447 0.855779 14.6382L0.865096 14.6388H0.889498H1.88811H2.32298L2.53902 14.2614L6.82576 6.77247ZM1.77218 14.9282H1.02218V15.6782V17.5V18.25H1.77218H26.5797H27.3297V17.5V15.6782V14.9282H26.5797H1.77218ZM2.79807 18.5413H1.93147L2.05583 19.3989L3.56691 29.8193L3.66006 30.4616H4.30914H24.0398H24.6889L24.7821 29.8193L26.2931 19.3989L26.4175 18.5413H25.5509H2.79807Z"
    fill="#91B7D9" stroke="#91B7D9" stroke-width="1.5" />
</svg>
```

Estado en el CSS linea 373-389

```css
/* Estado Condicional PROCESO para el Icono de Card Desafio de tareas */
.task__img-process path {
	stroke: #f79429;
}

/* Estado Condicional REALIZADO para el Icono de Card Desafio de tareas */
.task__img-effective path {
	stroke: #3eb22b;
}

/* Estado Condicional PROCESO para ROTAR LA IMAGEN Y SIMULAR EN PROCESO de Card Desafio de tareas */
.task__img-process {
	transform: rotate(-45deg);
	-webkit-transform: rotate(-45deg);
	-moz-transform: rotate(-45deg);
	-ms-transform: rotate(-45deg);
	-o-transform: rotate(-45deg);
}
```

### Linea 172 Linea Divisora Meta de Compras estado condicional:

```html
<!--! Estado Condicional -->
<div class="task__line"></div>
```

Estado en el CSS linea 465-479

```css
.task__line,
.oneClick__line {
	width: 80%;
	height: 1px;
	background-color: #b9d5ee;
	margin: 20px auto;
}
/* Estado Condicional PROCESO para Linea  de Card Desafio de tareas */
.task__line-process {
	background-color: #f79429;
}
/* Estado Condicional REALIZADO para Linea  de Card Desafio de tareas */
.task__line-effective {
	background-color: #3eb22b;
}
```

### Linea 174 Detalle de cuanto has comprado Meta de Compras estado condicional:

```html
<!--! Estado Condicional -->
<p class="buy__current">Has comprado</p>
```

Estado en el CSS linea  600-620

```css
/* Estado Condicional INICIAL para Valor Card Meta de Compras*/
.buy__current,
.oneClick__current {
	font-size: 11px;
	color: var(--gray);
	text-align: center;
}

.buy__value,
.oneClick__current {
	font-weight: 600;
}

/* Estado Condicional REALIZADO para Valor Card Meta de Compras*/
.buy__current-effective,
.oneClick__current-effective {
	display: none;
}
.buy__value-effective,
.oneClick__value-effective {
	display: none;
}
```

### Linea 176 Cantidad de paquetes comprado Meta de Compras estado condicional:

```html
<!--! Estado Condicional -->
<p class="buy__current"><span class="buy__value"> 3</span> <span>paquetes</span></p>
```

Estado en el CSS linea 599-620

```css
/* Estado Condicional INICIAL para Valor Card Meta de Compras*/
.buy__current,
.oneClick__current {
	font-size: 11px;
	color: var(--gray);
	text-align: center;
}

.buy__value,
.oneClick__current {
	font-weight: 600;
}

/* Estado Condicional REALIZADO para Valor Card Meta de Compras*/
.buy__current-effective,
.oneClick__current-effective {
	display: none;
}
.buy__value-effective,
.oneClick__value-effective {
	display: none;
}
```

### Linea 178 Felicitaciones Meta de Compras estado condicional:

```html
<!--! Estado Condicional -->
<p class="buy__congratulations">¡COMPLETADO!</p>
```

Estado en el CSS linea 623-638

```css
/* Estado Condicional INICIAL para Felicitaciones Card Meta de Compras*/
.buy__congratulations,
.oneClick__congratulations {
	font-weight: 600;
	font-size: 14px;
	line-height: 12px;
	text-align: center;
	letter-spacing: -0.01em;
	color: #3eb22b;
	display: none;
}

/* Estado Condicional REALIZADO para Felicitaciones Card Meta de Compras*/
.buy__congratulations-effective {
	display: block;
	margin: 6.5px auto;
}
```

### Linea 182 Card Meta 1C1P estado condicional:

```html
<!--! Estado Condicional -->
<div class="oneClick__card">
```

Estado en el CSS linea 507-534

```css
/* Estado Condicional INICIAL para la Card Meta de Compras*/
.buy__card,
.oneClick__card {
	width: 95%;
	max-width: 151px;
	background: #e3ecea;
	display: flex;
	flex-direction: column;
	justify-content: center;
	align-items: center;
	padding: 20px 0px 15px;
	border-radius: 5px;
	-webkit-border-radius: 5px;
	-moz-border-radius: 5px;
	-ms-border-radius: 5px;
	-o-border-radius: 5px;
}

/* Estado Condicional PROCESO para la Card Meta de Compras*/
.buy__card-process,
.oneClick__card-process {
	background: #fff0d9;
}

/* Estado Condicional REALIZADO para la Card Meta de Compras*/
.buy__card-effective,
.oneClick__card-effective {
	background: #effbed;
}
```

### Linea 184 Titulo Card Meta 1C1P estado condicional:

```html
<!--! Estado Condicional -->
<p class="oneClick__title">Meta 1C1P:</p>
```

Estado en el CSS linea 543-561

```css
/* Estado Condicional INICIAL para El Titulo Card Meta de Compras*/
.buy__title,
.oneClick__title {
	font-size: 14px;
	font-weight: 600;
	color: #91b7d9;
	text-align: center;
}

/* Estado Condicional PROCESO para El Titulo Card Meta de Compras*/
.buy__title-process,
.oneClick__title-process {
	color: #df0021;
}

/* Estado Condicional REALIZADO para El Titulo Card Meta de Compras*/
.buy__title-effective,
.oneClick__title-effective {
	color: #444444;
}
```

### Linea 186 Subtitulo Meta 1C1P  estado condicional:

```html
<!--! Estado Condicional -->
<p class="oneClick__subtitle">Realizar <span class="current_1C1P">2</span> pedidos</p>
```

Estado en el CSS linea 564-582

```css
/* Estado Condicional INICIAL para El Subtitulo Card Meta de Compras*/
.buy__subtitle,
.oneClick__subtitle {
	font-size: 11px;
	font-weight: 400;
	color: #91b7d9;
	margin-bottom: 14px;
}

/* Estado Condicional PROCESO para El Subtitulo Card Meta de Compras*/
.buy__subtitle-process,
.oneClick__subtitle-process {
	color: #df0021;
}

/* Estado Condicional REALIZADO para El Subtitulo Card Meta de Compras*/
.buy__subtitle-effective,
.oneClick__subtitle-effective {
	color: #444444;
}
```

### Linea 186 Subtitulo Meta 1C1P  campo dinámico:

```html
<!--! Estado Condicional -->
<p class="oneClick__subtitle">Realizar <span class="current_1C1P">2</span> pedidos</p>
```

### Linea 188 Circulo Icono Meta 1C1P  estado condicional:

```html
<!--! Estado Condicional -->
<div class="task__circle">
```

Estado en el CSS linea 323-351

```css
/* Estado Condicional INICIAL para el Circulo del Icono Card Desafio de tareas */
.task__circle {
	display: flex;
	justify-content: center;
	align-items: center;
	width: 70px;
	height: 70px;
	margin: 0 auto;
	background-color: #e3ecea;
	border-radius: 50%;
	border: solid 4px #b9d5ee;
}

/* Estado Condicional PROCESO para el Circulo del Icono Card Desafio de tareas */
.task__circle-process {
	background-color: #fff0d9;
	border-color: #f79429;
	border-left-color: transparent;
	transform: rotate(45deg);
	-webkit-transform: rotate(45deg);
	-moz-transform: rotate(45deg);
	-ms-transform: rotate(45deg);
	-o-transform: rotate(45deg);
}

/* Estado Condicional REALIZADO para el Circulo del Icono Card Desafio de tareas */
.task__circle-effective {
	background-color: #effbed;
	border-color: #3eb22b;
}
```

### Linea 190 SVG Icono Meta 1C1P estado condicional:

```html
<!--! Estado Condicional -->
<svg class="task__img" width="30" height="33" fill="none" xmlns="http://www.w3.org/2000/svg">
  <path
    d="M11.614 31.18c1.25 0 2.264-1.026 2.264-2.291s-1.014-2.291-2.264-2.291c-1.25 0-2.263 1.026-2.263 2.291s1.013 2.291 2.263 2.291ZM20.89 31.18c1.25 0 2.263-1.026 2.263-2.291s-1.013-2.291-2.263-2.291-2.264 1.026-2.264 2.291 1.013 2.291 2.264 2.291Z"
    stroke="#91B7D9" stroke-width="2" stroke-miterlimit="10" />
  <path
    d="M27.927 6.664a2.074 2.074 0 0 0-1.624-.784H7.702s-.32-1.109-.652-1.457L4.17 1.397a1.27 1.27 0 0 0-1.808-.037 1.307 1.307 0 0 0-.025 1.83l2.867 3.026c.036.037.049.074.061.112l2.596 15.501c.221 1.357 1.365 2.354 2.73 2.354l12.943.074h.012c.701 0 1.28-.573 1.28-1.282 0-.71-.566-1.295-1.267-1.295l-12.967-.075a.204.204 0 0 1-.21-.187l-.516-2.477c.258.062.53.1.812.1h13.004c1.328 0 2.472-.947 2.743-2.267l1.92-8.33a2.143 2.143 0 0 0-.42-1.78Z"
    stroke="#91B7D9" stroke-width="1.5" stroke-miterlimit="10" stroke-linecap="round"
    stroke-linejoin="round" />
  <path
    d="M9.067 11.98H1.193A1.202 1.202 0 0 1 0 10.774c0-.66.529-1.208 1.193-1.208h7.874c.664 0 1.193.536 1.193 1.208 0 .672-.529 1.208-1.193 1.208ZM12.204 15.442H4.33a1.194 1.194 0 0 1-1.193-1.208c0-.672.529-1.208 1.193-1.208h7.873c.665 0 1.194.536 1.194 1.208 0 .672-.53 1.208-1.194 1.208Z"
    fill="none" />
</svg>
```

Estado en el CSS linea 373-389

```css
/* Estado Condicional PROCESO para el Icono de Card Desafio de tareas */
.task__img-process path {
	stroke: #f79429;
}

/* Estado Condicional REALIZADO para el Icono de Card Desafio de tareas */
.task__img-effective path {
	stroke: #3eb22b;
}

/* Estado Condicional PROCESO para ROTAR LA IMAGEN Y SIMULAR EN PROCESO de Card Desafio de tareas */
.task__img-process {
	transform: rotate(-45deg);
	-webkit-transform: rotate(-45deg);
	-moz-transform: rotate(-45deg);
	-ms-transform: rotate(-45deg);
	-o-transform: rotate(-45deg);
}
```

### Linea 205 Linea Divisora Meta 1C1P estado condicional:

```html
<!--! Estado Condicional -->
<div class="oneClick__line"></div>
```

Estado en el CSS linea 465-479

```css
.task__line,
.oneClick__line {
	width: 80%;
	height: 1px;
	background-color: #b9d5ee;
	margin: 20px auto;
}
/* Estado Condicional PROCESO para Linea  de Card Desafio de tareas */
.task__line-process {
	background-color: #f79429;
}
/* Estado Condicional REALIZADO para Linea  de Card Desafio de tareas */
.task__line-effective {
	background-color: #3eb22b;
}
```

### Linea 207 Detalle de cuanto has comprado Meta 1C1P  estado condicional:

```html
<!--! Estado Condicional -->
<p class="oneClick__current">Has hecho</p>
```

Estado en el CSS linea  600-620

```css
/* Estado Condicional INICIAL para Valor Card Meta de Compras*/
.buy__current,
.oneClick__current {
	font-size: 11px;
	color: var(--gray);
	text-align: center;
}

.buy__value,
.oneClick__current {
	font-weight: 600;
}

/* Estado Condicional REALIZADO para Valor Card Meta de Compras*/
.buy__current-effective,
.oneClick__current-effective {
	display: none;
}
.buy__value-effective,
.oneClick__value-effective {
	display: none;
}
```

### Linea 209 Cantidad de paquetes comprado Meta 1C1P  estado condicional:

```html
<!--! Estado Condicional -->
<p class="oneClick__current"> <span class="oneClick__value">1</span> <span> pedido en 1C1P</span></p>
```

Estado en el CSS linea 599-620

```css
/* Estado Condicional INICIAL para Valor Card Meta de Compras*/
.buy__current,
.oneClick__current {
	font-size: 11px;
	color: var(--gray);
	text-align: center;
}

.buy__value,
.oneClick__current {
	font-weight: 600;
}

/* Estado Condicional REALIZADO para Valor Card Meta de Compras*/
.buy__current-effective,
.oneClick__current-effective {
	display: none;
}
.buy__value-effective,
.oneClick__value-effective {
	display: none;
}
```

### Linea 211 Felicitaciones Meta 1C1P estado condicional:

```html
<!--! Estado Condicional -->
<p class="oneClick__congratulations">¡COMPLETADO!</p>
```

Estado en el CSS linea 623-638

```css
/* Estado Condicional INICIAL para Felicitaciones Card Meta de Compras*/
.buy__congratulations,
.oneClick__congratulations {
	font-weight: 600;
	font-size: 14px;
	line-height: 12px;
	text-align: center;
	letter-spacing: -0.01em;
	color: #3eb22b;
	display: none;
}

/* Estado Condicional REALIZADO para Felicitaciones Card Meta de Compras*/
.buy__congratulations-effective {
	display: block;
	margin: 6.5px auto;
}
```

## ¡BONUS! Meta: Marcas del mes

### Linea 224, 232, 240, 248, 256 Marca cajetillas campo dinámico:

```html
<div><span class="current__goal">X3</span></div>
<div><span class="current__goal">X3</span></div>
<div><span class="current__goal">X3</span></div>
<div><span class="current__goal">X3</span></div>
<div><span class="current__goal">X3</span></div>
```


# Archivo final-status.html

## Detalle

## Premio de Compras

### Linea 44 Icono Desafío de Tareas estado condicional:

```html
<!--! Estado Condicional  -->
<div class="icon__task">
	<img
		class="task"
		src="./assets/img/box-desafio.png"
		alt="Icono Desafio Tareas"
	/>
	<!--! Estado Condicional  -->
	<img class="checked" src="./assets/img/checked.png" alt="Icono Cheked" />
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
<img class="checked" src="./assets/img/checked.png" alt="Icono Cheked" />
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
	<img
		class="task"
		src="./assets/img/box-cesta.png"
		alt="Icono Meta de Compras"
	/>
	<!--! Estado Condicional  -->
	<img class="checked" src="./assets/img/checked.png" alt="Icono Cheked" />
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
<img class="checked" src="./assets/img/checked.png" alt="Icono Cheked" />
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

### Linea 74 Premio Compras estado condicional:

```html
<!--! Estado Condicional  -->
<img class="prize" src="./assets/img/box-premio.png" alt="Icono Premio" />
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

### Linea 77 Texto Premio Compras estado condicional:

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
	<img
		class="task"
		src="./assets/img/box-desafio.png"
		alt="Icono Meta de Compras"
	/>
	<img class="checked" src="./assets/img/checked.png" alt="Icono Cheked" />
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
<img class="checked" src="./assets/img/checked.png" alt="Icono Cheked" />
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
	<img class="task" src="./assets/img/box-1C1P.png" alt="Icono Carrito" />
	<img class="checked" src="./assets/img/checked.png" alt="cono Cheked" />
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
<img class="checked" src="./assets/img/checked.png" alt="Icono Cheked" />
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

### Linea 144 Premio 1C1P estado condicional:

```html
<!--! Estado Condicional  -->
<img class="prize" src="./assets/img/box-premio.png" alt="Icono Premio" />
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

### Linea 147 Texto Premio 1C1P estado condicional:

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
	<img
		class="task"
		src="./assets/img/box-desafio.png"
		alt="Icono Meta de Compras"
	/>
	<img class="checked" src="./assets/img/checked.png" alt="Icono Cheked" />
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
<img class="checked" src="./assets/img/checked.png" alt="Icono Cheked" />
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

### Linea 206 Premio Meta Marcas estado condicional:

```html
<!--! Estado Condicional  -->
<div class="icon__task">
	<img class="task" src="./assets/img/box-marcas.png" alt="Icono Marca" />
	<!--! Estado Condicional -->
	<img class="checked" src="./assets/img/checked.png" alt="Icono Cheked" />
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
<img class="checked" src="./assets/img/checked.png" alt="Icono Cheked" />
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

### Linea 221 Premio Bonus estado condicional:

```html
<!--! Estado Condicional  -->
<img class="prize" src="./assets/img/box-premio.png" alt="Icono Premio" />
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

### Linea 224 Texto Premio Bonus estado condicional:

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


