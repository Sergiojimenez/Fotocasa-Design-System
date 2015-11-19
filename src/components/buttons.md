---
title: Buttons
---

<div class="library__header">
	<div>
		<h1>&lt; Buttons &gt;</h1>
		<h2>Los distintos tipos de botones y cómo usarlos en la aplicación</h2>
	</div>
</div>

<div class="library__main">

<div class="library__example__group">
	<h3>Normal Button:</h3>
	<p>Este sería el botón básico. Se utilizaría siempre que no exista un criterio de jerarquización.</p>
	<div class="library__example">
		<button type="button" class="re-button">Button</button>
  		<button type="button" class="re-button re-button--small">Button Small</button>
	</div>
</div>

<div class="library__example__group">
	<h3>Primary Button:</h3>
	<p>El botón primario se utiliza para destacar aquellas acciones que son primarias dentro de la página.<br />
	En una misma página pueden coexistir varios primary buttons.<br />
	El botón principal de envío de un formulario siempre será un primary button.</p>
	<div class="library__example">
		<button type="button" class="re-button re-button--primary">Button Primary</button>
		<button type="button" class="re-button re-button--small re-button--primary">Button Small Primary</button>
	</div>
</div>

<div class="library__example__group">
	<h3>Accent Button:</h3>
	<p>El botón primario se utiliza para destacar aquellas acciones que son primarias dentro de la página.<br />
	En una misma página pueden coexistir varios primary buttons.<br />
	El botón principal de envío de un formulario siempre será un primary button.</p>
	<div class="library__example">
	  <button type="button" class="re-button re-button--accent">Button Accent</button>
	</div>
</div>

### Code
```html
<button type="button" class="button">Button</button>
<button type="button" class="button button--small">Button Small</button>
<button type="button" class="button button--large">Button Large</button>

<button type="button" class="button button--primary">Button Primary</button>
<button type="button" class="button button--accent">Button Accent</button>

<button type="button" class="button button--small button--primary">Button Small Primary</button>
<button type="button" class="button button--large button--primary">Button Large Primary</button>
```

</div>
