# Advanced text formatting

### description

Description lists use a different wrapper than the other list types — `<dl>`; in addition each term is wrapped in a `<dt> (description term)` element, and each description is wrapped in a `<dd> (description definition)` element. Let's finish marking up our example:

```
<dl>
	<dt>
		<dd></dd>
		<dd></dd>
	</dt>
<dl>
```

### Quotations

```
<blockquote>
</blockquote>
```

### q

The quote element — `<q>` — is intended for short quotations that don't require paragraph breaks.

```
<p><q>good job</p>
"good job"
```

### Citations

`cite`引用文章

### abbreviations

```
<abbr title="good description">TEST</abbr>
```

### Superscript and subscript

```
<sup>2</sup>
<sub>2</sub>
```

### Document and website srtucture

header: <header>.
navigation bar: <nav>.
main content: <main>, with various content subsections represented by <article>, <section>, and <div> elements.
sidebar: <aside>; often placed inside <main>.
footer: <footer>.

