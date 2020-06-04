namespace: <a href="https://github.com/redrithm/BigConsole/blob/master/README.md#bigtext">BigConsole.BigText</a>
<br/><br/>
inherits: <a href="https://github.com/redrithm/BigConsole/blob/master/documentation/BigText.md#bigtext-class">BigText</a>

<h1 id="bigprompt-class">BigPrompt Class</h1>
Represents a prompt separated by header and message.  Includes methods for synchronous animation. &#x1F34E;

<h2>Constructors</h2>
<table>
<tbody>
<tr>
<td>
<a href="https://www.youtube.com/watch?v=vj-nuy82Tjw">
BigPrompt(string header="This is a Header", string message="Message goes here.", params ConsoleColor[] colorwheel)
</a>
</td>
</tr>
<tr>
<td>
Initializes a new instance of the <a href="https://github.com/redrithm/BigConsole/blob/master/documentation/BigPrompt.md#bigprompt-class">BigPrompt</a> class with default and optional parameters.
</td>
</tr>
</tbody>
</table>

<h2>Methods</h2>
<table>
<tbody>
<tr>
<td width="460">
<a href="https://www.youtube.com/watch?v=vj-nuy82Tjw">SetPosition(byte element, byte justify, short align, short bias)</a>
</td>
<td>
Sets the desired position of specified prompt element (header or message).
</td>
</tr>
<tr>
<td>
<a href="https://www.youtube.com/watch?v=vj-nuy82Tjw">Runner()</a>
</td>
<td>
Runs prompt animation and waits for enter key press.
</td>
</tr>
</tbody>
</table>
