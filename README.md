# Sublime Text 2 Bookchef Snippets

Collection of snippet for Bookchef proyect: <a href="https://github.com/snitko/bookchef">https://github.com/snitko/bookchef</a>

Type the snippet shortcode and then press <kbd>Tab</kbd> to complete the snippet.

Snippets listed bellow:

__bcbook__

```XML
<book>

  <cover><img src="${1:cover.png}"/><${2:InsertBookVersion}/></cover>

</book>
```

__bccodeinline__

```XML
<code>
	${1:yourCode}
</code>
```

__bccode__

```XML
<code description="${1:description}">
	${2:yourCode}
</code>
```

__bcchapter__

```XML
<chapter>

  ${1:yourSectionsHere}

</chapter>
```

__bcchaptersrc__

```XML
<chapter src="${1:file.xml}"></chapter>
```

__bcfootnote__

```XML
<footnote id="${1:index}">${2:yourNote}</footnote>
```

__bcfootnotes__

```XML
<footnotes>
	${1:yourFootnotes}
</footnotes>
```

__bcreference__

```XML
<reference id="${1:index}" type="${2:type}" url="${3:url}">${4:description}</reference>
```

__bcreferences__

```XML
<references>
    ${1:yourReferences}
</references>
```

__bcsection__

```XML
<section>
  <title>${1:SectionTitle}</title>
  <p>
  	${2:sectionContent}
  </p>
</section>
```

__bcsectionsrc__

```XML
<section src="${2:file.xml}"/>
```

__bcsetting__

```XML
<meta name="${1:settingName}" content="${2:value}"/>
```

__bcsettings__

```XML
<settings>

  ${1:yourSettings}

</settings>
```





