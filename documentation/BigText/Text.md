<a href="https://github.com/cipher-1i/BigConsole/blob/master/README.md#bigconsole">🏠</a><br/><br/>
namespace: <a href="https://github.com/cipher-1i/BigConsole/blob/master/documentation/BigText/README.md#bigtext-namespace">BigText</a>
<h1 id="text-class">Text Class</h1>
Provides the base class for big text as a sequence of strings.  Provides methods for customizing and animating text color. &#x1F34E;

<h2>Constructors</h2>
<table>
<tbody>
<tr>
<td>
<a href="#">
Text(string[] text, params ConsoleColor[] colorwheel)
</a>
</td>
<td>
  Initializes a new instance of the <a href="#text-class">Text</a> class and sets the text content. Includes optional parameters for customizing the color wheel.
</td>
</tr>
<tr>
<td width="592">
<a href="#">
Text(int alignment = 3, int start_color = 0, params ConsoleColor[] colorwheel)
</a>
</td>
<td>
  Initializes a new instance of the <a href="#text-class">Text</a> class with default and optional parameters.
</td>
</tr>
</tbody>
</table>

<h2>Methods</h2>
<table>
<tbody>
<tr>
<td>
<a href="#">SetText(string[] text)</a>
</td>
<td>
  Sets the <a href="#text-class">Text</a> content.
</td>
</tr>
<tr>
<td width="300">
<a href="#">Animate(params char[] outliers)</a>
</td>
<td width="650">
Displays a brief animation of color wheel effects on the main text and provides support for optional outliers for a secondary color effect.
</td>
</tr>
</tbody>
</table>
