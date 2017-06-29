<h1>replacer</h1>

string-replace in files. regular-expression. input passed as base64 escaped argument to nodejs, which is a better workaround from escaping stuff with \\\\\\\

<hr/>

Better than <code>sed</code>,
works cross-OS, no need to escape anything with \\\\\\\\

steps:
think of a javascript-like regular-expression,
you would like to run on the content of the file,
remember that you can use i/g/m/u modifiers.

go to your browser and type the regex, wrap it with '', and run <code>btoa(....)</code> on it.
you'll get a base64 string, just pass it to index.cmd.

you need nodejs, but I've already included it (compressed 7zip),
and it is already compressed with UPX, to get it from 18mb to 5mb..
no need to download/configure nodejs.