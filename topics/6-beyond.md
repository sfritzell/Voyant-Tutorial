# Beyond Voyant

Voyant is designed to function as a standalone environment (voyant-tools.org) or as a set of more independent modules that can be embedded into remote sites (much like a YouTube clip). Technically, this is done using an iframe tag that creates a sandbox within your page where Voyant can do its thing.

## Exporting a Corpus

The export feature in Voyant allows you to generate an HTML snippet to embed the current corpus and tool (or skin) in a page of your choice. Click the "export" icon in the upper right-hand corner of the page or individual tool panel, expand the "export view" section, select an HTML snippet radio button, click the "export", and copy the snippet that appears in the text box. For example:
 
 ```
 <iframe src='http://voyant-tools.org/tool/Cirrus/?corpus=austen'
    style='width: 400%; height: 400px'></iframe>
```

It's also possible to embed Voyant into a current page and to use the contents of the current page as a corpus. Here is an example of such code provided by Voyant.  Notice how the URL changes.

```
<iframe src="http://voyant-tools.org/tool/Cirrus/?useReferer=true"
    style="width: 300px; height: 300px;"></iframe>
```

You can also embed a specific page using the input parameter (or a variant format from a given page, such as generated XML or PDF). For more details on how to do this, refer to the Voyant [documentation](https://voyant-tools.org/docs/#!/guide/embedding).

---

[< Previous](5-advanced.md) | [Home >](https://sfritzell.github.io/Voyant-Tutorial/)
