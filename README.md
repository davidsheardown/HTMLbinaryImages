# HTML binary Images

Quick example of how to include Base64/Binary images inline without any URL references.
Good for HTML inline emails or just so you don't have to reference external links.

Take a look at the index.html page. The first example uses a standard IMG HTML tag to display a PNG image from a URL.
The second example has a data format URL version with the image encoded as Base64/binary.

The trade-off is the binary image is a fairly large "string" in the IMG src however, there are no external references.
This makes it a great fit for most email clients to display HTML or where you can't/don't want to use external links.
