---
layout: page
navigation_source: api_nav
improve_this_button: false
---
<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [@rushstack/localization-plugin](./localization-plugin.md) &gt; [ILocalizedData](./localization-plugin.ilocalizeddata.md)

## ILocalizedData interface


<b>Signature:</b>

```typescript
export interface ILocalizedData 
```

## Properties

|  Property | Type | Description |
|  --- | --- | --- |
|  [defaultLocale](./localization-plugin.ilocalizeddata.defaultlocale.md) | <code>IDefaultLocaleOptions</code> | Options for the locale used in the source localized data files. |
|  [normalizeResxNewlines](./localization-plugin.ilocalizeddata.normalizeresxnewlines.md) | <code>'lf' &#124; 'crlf'</code> | Normalize newlines in RESX files to either CRLF (Windows-style) or LF ('nix style) |
|  [passthroughLocale](./localization-plugin.ilocalizeddata.passthroughlocale.md) | <code>IPassthroughLocaleOptions</code> | Options around including a passthrough locale. |
|  [pseudolocales](./localization-plugin.ilocalizeddata.pseudolocales.md) | <code>IPseudolocalesOptions</code> | Options for pseudo-localization. |
|  [resolveMissingTranslatedStrings](./localization-plugin.ilocalizeddata.resolvemissingtranslatedstrings.md) | <code>(locales: string[], filePath: string) =&gt; IResolvedMissingTranslations</code> | Use this paramter to specify a function used to load translations missing from the [ILocalizedData.translatedStrings](./localization-plugin.ilocalizeddata.translatedstrings.md) parameter. |
|  [translatedStrings](./localization-plugin.ilocalizeddata.translatedstrings.md) | <code>ILocalizedStrings</code> | Use this parameter to specify the translated data. |
