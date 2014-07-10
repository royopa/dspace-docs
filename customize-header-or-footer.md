#Customize header or footer (Manakin)

###Arquivos:

[dspace-src]/xmlui/themes/[theme-dir]/template.xsl (Custom theme's stylesheet – may be named differently for custom themes)

[dspace-src]/xmlui/themes/dri2xhtml/structural.xsl (Page structure stylesheet for Class, Kubrick, Reference & dri2xhtml based themes)

[dspace-src]/xmlui/themes/dri2xhtml-alt/core/page-structure.xsl (Page structure stylesheet for Mirage & dri2xhtml-alt based themes)

####Instruções:

Você precisa criar um novo tema caso ainda não tenha criado.

Para modificar o header, localize o tmeplate chamado "buildHeader" dentro dentro do XSLT de seu 
tema (veja a lista sobre a localização dos arquivos).

Copie esse template em seu arquivo de tema local 'template.xsl' (ou o nome que você deu para o stylesheet do seu tema) e
modifique o XSLT conforme a sua necessidade.

```xsl
<xsl:template name="buildHeader">
....
</xsl:template>
```

Para modificar o footer, localize o template chamado "buildFooter" dentro do XSLT de seu tema 
(veja a lista sobre a localização dos arquivos).

Copie esse template em seu arquivo de tema local 'template.xsl' (ou o nome que você deu para o stylesheet do seu tema) e
modifique o XSLT conforme a sua necessidade.

```xsl
<xsl:template name="buildFooter">
....
</xsl:template>
```
