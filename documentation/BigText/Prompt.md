<a href="https://github.com/cipher-1i/BCCLibrary/blob/master/README.md#bigconsole">🏠</a><br/><br/>
namespace: <a href="https://github.com/cipher-1i/BCCLibrary/blob/master/documentation/BigText/README.md#bigtext-namespace">BigText</a>
<br/><br/>
inherits: <a href="https://github.com/cipher-1i/BCCLibrary/blob/master/documentation/BigText/Text.md#text-class">Text</a>

<h1 id="prompt-class">Prompt Class</h1>
Represents a prompt separated by header and message.  Includes methods for synchronous animation. &#x1F34E;

<h2>Constructors</h2>
<table>
<tbody>
<tr>
<td>
<a href="#">
Prompt(string header="This is a Header", string message="Message goes here.", params ConsoleColor[] colorwheel)
</a>
</td>
</tr>
<tr>
<td>
Initializes a new instance of the <a href="#prompt-class">Prompt</a> class with default and optional parameters.
</td>
</tr>
</tbody>
</table>

<h2>Methods</h2>
<table>
<tbody>
<tr>
<td width="489">
<a href="#">SetPosition(byte element, byte justify, short alignment, short bias)</a>
</td>
<td>
Sets the desired position of specified prompt element (header or message).
</td>
</tr>
<tr>
<td>
<a href="#">Runner()</a>
</td>
<td>
Runs prompt animation and waits for enter key press.
</td>
</tr>
</tbody>
</table>
