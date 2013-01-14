<h2>Usage:</h2>

<code>
$("input").inputClear();
</code>

To exclude certain input elements from having clear option:

<code>
<input type="text" class="no-clear" />
</code>

or if you can't touch your existing code just add exclude option:

<code>
var options= {'exclude':'myclass' }
$("input").inputClear(options);
</code>

Live example on JsFiddle:  http://jsfiddle.net/ELGga/embedded/result/