---
title: Buttons
---

<div class="library__header">
	<div>
		<h1 class="library__header_title">Buttons</h1>
	</div>
</div>

<div class="library__main">

<div class="library__example__group">
	<h3 class="library__example_title">Basic Button</h3>
	<p>Utilizamos la clase <code class="code-class">.re-button</code> en un elemento <code class="code-html">&lt;a&gt;</code> o en un elemento <code class="code-html">&lt;button&gt;</code> siempre que estemos en el contexto de un formulario.</p>
	<div class="library__example">
		<a type="button" class="re-button">Basic Button</a>
		<button type="button" class="re-button">Form Basic Button</button>
	</div>

```html
<a href="#" class="re-button">Basic Button</a>
<button type="button" class="re-button">Form Basic Button</button>
```
</div>

<div class="library__example__group">
	<h3 class="library__example_title">Primary Button</h3>
	<p>Añadiremos la clase <code class="code-class">.re-button--primary</code> a nuestro botón.<br />
	Se utiliza para destacar aquellas <strong>acciones que son principales</strong> dentro de la página.<br />
	En una misma página pueden coexistir varios Primary Buttons.</p>
	<div class="library__example">
		<a href="#" class="re-button re-button--primary">Button Primary</a>
		<button type="button" class="re-button re-button--primary">Form Button Primary</button>
	</div>

```html
<a href="#" class="re-button re-button--primary">Primary Button</a>
<button type="button" class="re-button re-button--primary">Form Primary Button</button>
```
</div>

<div class="library__example__group">
	<h3 class="library__example_title">Accent Button</h3>
	<p>Añadiremos la clase <code class="code-class">.re-button--accent</code> a nuestro botón.<br />
	Se utiliza para <strong>destacar una única acción</strong> dentro de la página.</p>
	<div class="library__example">
		<a href="#" class="re-button re-button--accent">Button Accent</a>
	  	<button type="button" class="re-button re-button--accent">Form Button Accent</button>
	</div>

```html
<a href="#" class="re-button re-button--accent">Accent Button</a>
<button type="button" class="re-button re-button--accent">Form Accent Button</button>
```
</div>

<div class="library__example__group">
	<h3 class="library__example_title">Disabled Button</h3>
	<p>Añadiremos la clase <code class="code-class">.re-button--disabled</code> a nuestro botón.<br />
	Se utiliza en <strong>botones de formulario desactivados.</strong></p>
	<div class="library__example">
	  	<button type="button" class="re-button re-button--disabled" disabled>Form Button Disabled</button>
	</div>

```html
<button type="button" class="re-button re-button--disabled">Form Button Disabled</button>
```
</div>

<div class="library__example__group">
	<h3 class="library__example_title">Full Button</h3>
	<p>Añadiremos la clase <code class="code-class">.re-button--full</code> a nuestro botón.<br />
	Se utiliza para lograr que el ancho del botón <strong>sea el mismo ancho que el de su contenedor.</strong></p>
	<div class="library__example">
	  	<a href="#" class="re-button re-button--full">Basic Button Full</a>
	  	<a href="#" class="re-button re-button--primary re-button--full">Primary Button Full</a>
	  	<button type="button" class="re-button re-button--accent re-button--full">Form Accent Button Full</button>
	</div>

```html
<a href="#" class="re-button re-button--full">Basic Button Full</a>
<a href="#" class="re-button re-button--primary re-button--full">Primary Button Full</a>
<button type="button" class="re-button re-button--accent re-button--full">Form Accent Button Full</button>
```
</div>

<div class="library__example__group">
	<h3 class="library__example_title">Small Buttons</h3>
	<p>Podemos utilizar la <strong>versión reducida</strong> de los botones <em>Basic</em>, <em>Primary</em> y <em>Disabled</em> añadiendo la clase <code class="code-class">.re-button--small</code><br />
	El botón <em>Accent</em> no tiene versión reducida.</p>
	<div class="library__example">
		<a href="#" class="re-button re-button--small">Basic Button Small</a>
	  	<a href="#" class="re-button re-button--primary re-button--small">Primary Button Small</a>
	  	<button href="#" class="re-button re-button--disabled re-button--small" disabled>Form Button Disabled Small</button>
	</div>

```html
<a href="#" class="re-button re-button--small">Basic Button Small</a>
<a href="#" class="re-button re-button--primary re-button--small">Primary Button Small</a>
<button class="re-button re-button--disabled re-button--small" disabled>Form Button Disabled Small</button>
```
</div>

<div class="library__example__group">
	<h3 class="library__example_title">Icon Button</h3>
	<p>Podemos utilizar la <strong>versión reducida</strong> de los botones <em>Basic</em>, <em>Primary</em> y <em>Disabled</em> añadiendo la clase <code class="code-class">.re-button--small</code><br />
	El botón <em>Accent</em> no tiene versión reducida.</p>
	<div class="library__example">
		<a href="#" class="re-button ">
		<svg class="re-icon re-icon--small"><use xlink:href="../assets/images/fotocasa.sprite.svg#search"/></svg>
		Basic Icon Button</a>
	  	<a href="#" class="re-button re-button--primary">
	  	<svg class="re-icon re-icon--small"><use xlink:href="../assets/images/fotocasa.sprite.svg#search"/></svg>
	  	Primary Icon Button</a>
	  	<a href="#" class="re-button re-button--accent">
		<svg class="re-icon"><use xlink:href="../assets/images/fotocasa.sprite.svg#search"/></svg>
	  	Accent Icon Button</a>
	</div>

```html
<a href="#" class="re-button re-button--small">Basic Button Small</a>
<a href="#" class="re-button re-button--primary re-button--small">Primary Button Small</a>
<button href="#" class="re-button re-button--disabled re-button--small" disabled>Form Button Disabled Small</button>
```
</div>

</div>
