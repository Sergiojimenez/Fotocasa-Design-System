---
title: Typography
---
<div class="library__header">
	<div>
		<h1>Typography</h1>
	</div>
</div>

<div class="library__main">

<div class="library__example__group">
	<h3 class="library__example_title">Heading Basic</h3>
	<p>Establecemos tres niveles de Headings: <code class="code-html">&lt;h1&gt;</code>, <code class="code-html">&lt;h2&gt;</code> y <code class="code-html">&lt;h3&gt;</code>.</p>
	<div class="library__example">
		<h1>Header Level 1</h1>
		<p>Lorem ipsum dolor sit amet, consectetur adipisicing elit.</p>
		<h2>Header Level 2</h2>
		<h3>Header Level 3</h3>
	</div>

```html
<h1>Header Level 1</h1>
<h2>Header Level 2</h2>
<h3>Header Level 3</h3>
```
</div>
<div class="library__example__group">
	<h3 class="library__example_title">Heading Display</h3>
	<p>Utilizamos las clases <code class="code-class">.re-display-1</code> y <code class="code-class">.re-display-2</code> en encabezados publicitarios y de landings.</p>
	<div class="library__example">
		<h1 class="re-display-1">Header Display 1</h1>
		<h2 class="re-display-2">Header Display 2</h2>
	</div>

```html
<h1 class="re-display-1">Header Display 1</h1>
<h2 class="re-display-2">Header Display 2</h2>
```
</div>
<div class="library__example__group">
	<h3 class="library__example_title">Heading Modifiers</h3>
	<p>Utilizamos la clase <code class="code-class">.re-heading-compact</code> para resetear el margen inferior del Heading.<br />
	Utilizaramos las variantes <code class="code-class">.re-bold</code> y <code class="code-class">.re-light</code> para modificar el peso de los Headings.</p>
	<div class="library__example">
		<h1 class="re-heading-compact">Header Level 1 - Compact</h1>
		<p>Lorem ipsum dolor sit amet, consectetur adipisicing elit.</p>
		<h1 class="re-bold">Header Level 1 Bold</h1>
		<h2>Header Level 2 <span class="re-regular">a varios niveles de peso</span></h2>
	</div>

```html
<h1 class="re-heading-compact">Header Level 1 - Compact</h1>
Lorem ipsum dolor sit amet, consectetur adipisicing elit.
<h1 class="re-bold">Header Level 1 Bold</h1>
<h2>Header Level 2 <span class="re-regular">a varios niveles de peso</span></h2>
```
</div>

<div class="library__example__group">
	<h3 class="library__example_title">Paragraphs</h3>
	<p>Utilizamos la clase semántica <code class="code-html">&lt;p&gt;</code> para los párrafos de texto. Evitaremos usar las etiquetas <code class="code-html">&lt;span&gt;</code> o <code class="code-html">&lt;div&gt;</code> para dicho cometido.</p>
	<div class="library__example">
		<p>Lorem ipsum dolor sit amet, consectetur adipisicing elit. Non quidem at rerum. Fugiat, culpa maxime voluptatem iure voluptates quaerat magni, possimus recusandae repellat atque commodi aliquam quidem. Labore, enim, praesentium.</p>
	</div>

```html
<p>Lorem ipsum dolor sit amet, consectetur adipisicing elit. Non quidem at rerum. Fugiat, culpa maxime voluptatem iure voluptates quaerat magni, possimus recusandae repellat atque commodi aliquam quidem. Labore, enim, praesentium.</p>
```
</div>

<div class="library__example__group">
	<h3 class="library__example_title">Text Modifiers</h3>
	<p>Utilizaremos tags semánticos de HTML para dar énfasis al texto o para destacarlo visualmente: <code class="code-html">&lt;b&gt;</code>, <code class="code-html">&lt;i&gt;</code>, <code class="code-html">&lt;strong&gt;</code> y <code class="code-html">&lt;em&gt;</code>.<br />
	Disponemos de las clases auxiliares <code class="code-class">.re-bold</code>, <code class="code-class">.re-regular</code> y <code class="code-class">.re-light</code>, para poder variar el peso de la fuente.<br />
	Disponemos de la clase <code class="code-class">.re-small</code> para texto pequeño.</p>

	<div class="library__example">
		<p><b>Este sería un destacado en Bold por razones puramente estéticas.</b><br />
		<i>Este sería un destacado en Italic por razones puramente estéticas.</i><br />
		<strong>Este sería un detacado en Bold para dar énfasis al texto.</strong><br />
		<em>Este sería un detacado en Italic para dar énfasis al texto.</em><br />
		Variación del peso de la fuente: "Regular text" por defecto, <span class="re-light">"Light Text" mediante clase</span> y <span class="re-bold">"Bold Text" mediante clase</span>.<br />
		<span class="re-small">Este sería un texto small (p. ej para un caption).</span></p>
	</div>
	<div class="library__hint">
		¿Quieres conocer la diferencia entre usar <code class="code-html">&lt;b&gt;</code> <code class="code-html">&lt;i&gt;</code> y usar <code class="code-html">&lt;strong&gt;</code> <code class="code-html">&lt;em&gt;</code>? <a href="https://www.nosegraze.com/difference-between-b-strong-html/" target="_blank">Hazlo aquí</a>
	</div>

```html
<b>Este sería un destacado en Bold por razones puramente estéticas.</b>
<i>Este sería un destacado en Italic por razones puramente estéticas.</i>
<strong>Este sería un detacado en Bold para dar énfasis al texto.</strong>
<em>Este sería un detacado en Italic para dar énfasis al texto.</em>
Variación del peso de la fuente: "Regular text" por defecto, <span class="re-light">"Light Text" mediante clase</span> y <span class="re-bold">"Bold Text" mediante clase</span>.
<span class="re-small">Este sería un texto small (p. ej para un caption).</span>
```
</div>

<div class="library__example__group">
	<h3 class="library__example_title">List Basic</h3>
	<p>Por defecto utilizaremos listas sin bullets y sin un padding predefinido aplicando la clase <code class="code-class">.re-list</code>.</p>
	<div class="library__example">
		<ul class="re-list">
            <li>Primer elemento de la lista.</li>
            <li>Segundo elemento de la lista.</li>
            <li>Tercer elemento de la lista.</li>
        </ul>
	</div>

```html
<ul class="re-list">
<li>Primer elemento de la lista.</li>
<li>Segundo elemento de la lista.</li>
<li>Tercer elemento de la lista.</li>
</ul>
```
</div>

<div class="library__example__group">
	<h3 class="library__example_title">List Bullet</h3>
	<p>Añadiremos la clase modificadora <code class="code-class">.re-list--bullet</code> a nuestra lista para añadirle "bullets".</p>
	<div class="library__example">
		<ul class="re-list re-list--bullet">
            <li>Primer elemento de la lista.</li>
            <li>Segundo elemento de la lista.</li>
            <li>Tercer elemento de la lista.</li>
        </ul>
	</div>

```html
<ul class="re-list re-list--bullet">
<li>Primer elemento de la lista.</li>
<li>Segundo elemento de la lista.</li>
<li>Tercer elemento de la lista.</li>
</ul>
```
</div>

<div class="library__example__group">
	<h3 class="library__example_title">List Ordered</h3>
	<p>Añadiremos la clase modificadora <code class="code-class">.re-list--ordered</code> a nuestra lista para convertirla en una lista ordenada.<br />
	Para crear una lista ordenada utilizaremos el tag <code class="code-html">ol</code>.</p>
	<div class="library__example">
		<ol class="re-list re-list--ordered">
            <li>Primer elemento de la lista.</li>
            <li>Segundo elemento de la lista.</li>
            <li>Tercer elemento de la lista.</li>
        </ol>
	</div>

```html
<ol class="re-list re-list--ordered">
<li>Primer elemento de la lista.</li>
<li>Segundo elemento de la lista.</li>
<li>Tercer elemento de la lista.</li>
</ol>
```
</div>

<div class="library__example__group">
	<h3 class="library__example_title">List Inline</h3>
	<p>Añadiremos la clase modificadora <code class="code-class">.re-list--ordered</code> a nuestra lista para convertirla en una lista ordenada.<br />
	Para crear una lista ordenada utilizaremos el tag <code class="code-html">ol</code>.</p>
	<div class="library__example">
		<ol class="re-list re-list--inline">
            <li>Primer elemento de la lista</li>
            <li>Segundo elemento de la lista</li>
            <li>Tercer elemento de la lista</li>
        </ol>
	</div>

```html
<ol class="re-list re-list--ordered">
<li>Primer elemento de la lista.</li>
<li>Segundo elemento de la lista.</li>
<li>Tercer elemento de la lista.</li>
</ol>
```
</div>

<div class="library__example__group">
	<h3 class="library__example_title">Links</h3>
	<p>
		Se aplican estilos a los links por defecto en sus estados <i>link</i> y <i>hover</i>.<br />
		Para tener un link deshabilitado añadiremos la clase <code class="code-class">.re-link--disabled</code>.<br />
		Disponemos de las clases <code class="code-class">.re-link--icon-left</code> y <code class="code-class">.re-link--icon-right</code> para añadir iconos a ambos lados del link.
	</p>
	<div class="library__example">
		<a href="#">Basic link</a><br />
		<a href="#" class="re-link--disabled">Disabled link</a><br />
		<a href="#" class="re-link--icon-left"><svg class="re-icon re-icon--small"><use xlink:href="../assets/images/fotocasa.sprite.svg#caret-down"/></use></svg>Icon left link</a><br />
		<a href="#" class="re-link--icon-right">Icon right link<svg class="re-icon re-icon--small"><use xlink:href="../assets/images/fotocasa.sprite.svg#caret-down"/></use></svg></a>
	</div>

```html
<a href="#">Basic link</a><br />
<a href="#" class="re-link--disabled">Disabled link</a>
<a href="#" class="re-link--icon-left"><svg class="re-icon re-icon--small"><use xlink:href="../assets/images/fotocasa.sprite.svg#caret-down"/></use></svg>Icon left link</a>
<a href="#" class="re-link--icon-right">Icon right link<svg class="re-icon re-icon--small"><use xlink:href="../assets/images/fotocasa.sprite.svg#caret-down"/></use></svg></a>
```
</div>
</div>
