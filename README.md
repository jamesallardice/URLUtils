<h1>URLUtils JavaScript Library</h1>

URLUtils is a simple, lightweight library that makes it easier to perform some common URL-related tasks in JavaScript.

<h2>URLUtils.getParam(name)</h2>

`name` - The name of the URL parameter of which the value should be returned.

Returns a string, or `false` if a parameter matching `name` is not found in the page URL.

<h2>URLUtils.getParams()</h2>

Returns an object containing the name-value pairs of all parameters found in the page URL. Returns an empty object if no parameters are found in the URL.

<h2>URLUtils.getHash()</h2>

Returns a string containing the string following the `#` character in the URL. If no `#` character is found an empty string is returned.

<h2>URLUtils.makeSlug(str)</h2>

`str` - A string to be converted into a URL friendly "slug".

Returns a string containing a URL friendly "slug" of the argument. The input is converted to lower case, special characters are removed and spaces are replaced by hypens. For example, the input string "Quick &amp; Easy" would become "quick-easy".