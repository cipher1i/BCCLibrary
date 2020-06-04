namespace: <a href="https://github.com/redrithm/BigConsole/blob/master/documentation/BigText/NAMESPACE.md#bigconsole-bigtext-namespace">BigConsole.BigText</a>
<h1 id="bigtext-class">BigText Class</h1>
Provides the base class for big text as a sequence of strings.  Provides methods for customizing and animating text color. &#x1F34E;

<h2>Constructors</h2>
<table>
<tbody>
<tr>
<td>
<a href="https://www.youtube.com/watch?v=vj-nuy82Tjw">
BigText(params ConsoleColor[] colors)
</a>
</td>
<td>
  Initializes a new instance of the <a href="#bigtext-class">BigText</a> class with optional parameters for customizing the color wheel.
</td>
</tr>
<tr>
<td width="511">
<a href="https://www.youtube.com/watch?v=vj-nuy82Tjw">
BigText(int top = 3, int start_color = 0, params ConsoleColor[] colors)
</a>
</td>
<td>
  Initializes a new instance of the <a href="#bigtext-class">BigText</a> class with default and optional parameters.
</td>
</tr>
</tbody>
</table>

<h2>Methods</h2>
<table>
<tbody>
<tr>
<td>
<a href="https://www.youtube.com/watch?v=vj-nuy82Tjw">SetText(string[] text)</a>
</td>
<td>
Sets the main text with an array of strings.
</td>
</tr>
<tr>
<td width="300">
<a href="https://www.youtube.com/watch?v=vj-nuy82Tjw">Animate(params char[] outliers)</a>
</td>
<td width="650">
Displays a brief animation of color wheel effects on the main text and provides support for optional outliers for a secondary color effect.
</td>
</tr>
</tbody>
</table>
