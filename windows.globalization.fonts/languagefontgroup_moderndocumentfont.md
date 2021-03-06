---
-api-id: P:Windows.Globalization.Fonts.LanguageFontGroup.ModernDocumentFont
-api-type: winrt property
---

<!-- Property syntax
public Windows.Globalization.Fonts.LanguageFont ModernDocumentFont { get; }
-->

# Windows.Globalization.Fonts.LanguageFontGroup.ModernDocumentFont

## -description
Gets a font that is recommended for typical document body text following modern style conventions.

## -property-value
The recommended [LanguageFont](languagefont.md).

## -remarks
The ModernDocumentFont property provides a font recommendation for typical document body text following modern style conventions. These fonts can also be used in headings or other document elements.

The font recommended for this usage case will always be a "regular" font (regular weight, normal style, normal stretch). Apps might want to apply other weight/style/stretch formatting, as may be appropriate for the app scenario.

A ModernDocumentFont recommendation is available for every supported language or script.

## -examples

## -see-also
