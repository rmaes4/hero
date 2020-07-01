# [AwaitedDOM](/docs/basic-interfaces/awaited-dom) <span>/</span> DocumentType

<div class='overview'>The <strong><code>DocumentType</code></strong> interface represents a <a href="/en-US/docs/Web/API/Node" title="Node is an interface from which various types of DOM API objects inherit, allowing those types to be treated similarly; for example, inheriting the same set of methods, or being testable in the same way."><code>Node</code></a> containing a doctype.</div>

## Properties

### .name <div class="specs"><i>W3C</i></div> {#name}

A <a href="/en-US/docs/Web/API/DOMString" title="DOMString is a UTF-16 String. As JavaScript already uses such strings, DOMString is mapped directly to a String."><code>DOMString</code></a>, eg <code>"html"</code> for <code>&lt;!DOCTYPE HTML&gt;
</code>.

#### **Type**: `null`

### .publicId <div class="specs"><i>W3C</i></div> {#publicId}

A <a href="/en-US/docs/Web/API/DOMString" title="DOMString is a UTF-16 String. As JavaScript already uses such strings, DOMString is mapped directly to a String."><code>DOMString</code></a>, eg <code>"-//W3C//DTD HTML 4.01//EN"
</code>, empty string for HTML5.

#### **Type**: `null`

### .systemId <div class="specs"><i>W3C</i></div> {#systemId}

A <a href="/en-US/docs/Web/API/DOMString" title="DOMString is a UTF-16 String. As JavaScript already uses such strings, DOMString is mapped directly to a String."><code>DOMString</code></a>, eg <code>"http://www.w3.org/TR/html4/strict.dtd"
</code>, empty string for HTML5.

#### **Type**: `null`