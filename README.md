# XSLT Demo

Tento repozitář obsahuje ukázky práce s **XML**, **XSLT** a **XPath** na jednoduchých příkladech.

## 📄 students.xml
- Obsahuje seznam studentů (jméno, příjmení, přezdívka).
- V hlavičce je odkaz na XSL šablonu `student.xsl`.
- Při otevření v prohlížeči se dokument transformuje do HTML tabulky.

## 📄 student.xsl
- Definuje XSLT transformaci pro `students.xml`.
- Vytváří přehlednou tabulku se seznamem studentů.
- Využívá `<xsl:for-each>` pro iteraci nad elementy `<student>`.

## 📄 friendList.xml
- Obsahuje rozšířené ukázky XML struktur:
  - seznam přátel s atributy,
  - speciální symboly (&amp;, &lt;, &gt;),
  - jmenné prostory (`f:` a `h:`),
  - HTML tabulku v XML,
  - seznam knih s ukázkami XPath dotazů,
  - jednoduchou třídu se studentem.
