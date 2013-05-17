TYPO3 Neos Lelesys Faq Plugin
======================

This plugin adds faq to TYPO3 Neos websites.

Quick start
-----------

* include the plugin's TypoScript definitions to your own one's (located in, for example, `Packages/Sites/Your.Site/Resources/Private/TypoScripts/Library/ContentElements.ts2`, with:

```
include: resource://Lelesys.Plugin.Faq/Private/TypoScripts/Library/NodeTypes.ts2
```

* include the plugin's Stylesheet to your own one's where you add other stylesheets of the site.

```
<link href="{f:uri.resource(path: 'resource://Lelesys.Plugin.Faq/Public/Stylesheets/Faq.css')}" rel="stylesheet" media="screen">
```

* add the plugin content element "Lelesys-Faq" to the position of your choice.



Note: This will add a simple Faq Plugin to your site.

If u want a Faq with toogle effect than u just have to add javascript to your own one's where you add other javascripts of the site.

```
<script src="{f:uri.resource(path: 'resource://Lelesys.Plugin.Faq/Public/JavaScript/Faq.js')}"></script>
```