## FontBakery report

fontbakery version: 0.10.4

<details><summary><b>[1] Experimental checks</b></summary><div><details><summary>🔥 <b>FAIL:</b> Shapes languages in all GF glyphsets. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/glyphsets/shape_languages">com.google.fonts/check/glyphsets/shape_languages</a>)</summary><div>


* 🔥 **FAIL** GF_Latin_Core glyphset:

| Language | FAIL messages |
| :--- | :--- |
| br_Latn (Breton) | Some base glyphs were missing: CʼH, cʼh |
|  ^  | Shaper produced a .notdef |
| haw_Latn (Hawaiian) | Some base glyphs were missing: ʻ |
|  ^  | Shaper produced a .notdef |
| mh_Latn (Marshallese) | Some base glyphs were missing: Ḷ, ḷ, Ṃ, ṃ, Ṇ, ṇ, Ọ, ọ |
|  ^  | Some mark glyphs were missing: ◌̣ |
|  ^  | Shaper produced a .notdef |
| qu_Latn (Quechua) | Some base glyphs were missing: CHʼ, Kʼ, Pʼ, Qʼ, Tʼ, chʼ, kʼ, pʼ, qʼ, tʼ |
|  ^  | Shaper produced a .notdef |
| scn_Latn (Sicilian) | Some base glyphs were missing: Ḍ, ḍ |
|  ^  | Shaper produced a .notdef |
| teo_Latn (Teso) | Some base glyphs were missing: Ɔ, Ɛ, Ɨ, Ʉ, ɔ, ɛ, ɨ, ʉ, ᵃ, ᵉ, ᵋ, ᵒ, ᵓ, ᵘ, ᶤ, ᶶ, ⁱ |
|  ^  | Shaper produced a .notdef |

 [code: failed-language-shaping]
* ⚠ **WARN** GF_Latin_Core glyphset:

| Language | FAIL messages |
| :--- | :--- |
| lg_Latn (Ganda) | No variant glyphs were found for Eng |
| dyo_Latn (Jola-Fonyi) | No variant glyphs were found for Eng |
| ny_Latn (Nyanja) | No variant glyphs were found for Eng |
| wo_Latn (Wolof) | No variant glyphs were found for Eng |

 [code: warning-language-shaping]
</div></details><br></div></details><details><summary><b>[10] NotoSansKannada[wdth,wght].ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Noto fonts must have an ARTICLE.en_us.html file (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/description/noto_has_article">com.google.fonts/check/description/noto_has_article</a>)</summary><div>


* 🔥 **FAIL** This is a Noto font but it lacks an ARTICLE.en_us.html file [code: missing-article]
</div></details><details><summary>🔥 <b>FAIL:</b> Check that legacy accents aren't used in composite glyphs. (derived from com.google.fonts/check/legacy_accents) (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/legacy_accents">com.google.fonts/check/legacy_accents</a>)</summary><div>


* 🔥 **FAIL** Glyph "Aacute" has a legacy accent component (acute). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "Abreve" has a legacy accent component (breve). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "Acircumflex" has a legacy accent component (circumflex). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "Adieresis" has a legacy accent component (dieresis). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "Agrave" has a legacy accent component (grave). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "Aogonek" has a legacy accent component (ogonek). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "Aring" has a legacy accent component (ring). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "Atilde" has a legacy accent component (tilde). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "Cacute" has a legacy accent component (acute). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "Ccaron" has a legacy accent component (caron). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "Ccedilla" has a legacy accent component (cedilla). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "Cdotaccent" has a legacy accent component (dotaccent). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "Dcaron" has a legacy accent component (caron). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "Eacute" has a legacy accent component (acute). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "Ecaron" has a legacy accent component (caron). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "Ecircumflex" has a legacy accent component (circumflex). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "Edieresis" has a legacy accent component (dieresis). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "Edotaccent" has a legacy accent component (dotaccent). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "Egrave" has a legacy accent component (grave). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "Eogonek" has a legacy accent component (ogonek). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "Gbreve" has a legacy accent component (breve). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "Gdotaccent" has a legacy accent component (dotaccent). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "Iacute" has a legacy accent component (acute). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "Icircumflex" has a legacy accent component (circumflex). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "Idieresis" has a legacy accent component (dieresis). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "Idotaccent" has a legacy accent component (dotaccent). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "Igrave" has a legacy accent component (grave). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "Iogonek" has a legacy accent component (ogonek). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "Lacute" has a legacy accent component (acute). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "Nacute" has a legacy accent component (acute). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "Ncaron" has a legacy accent component (caron). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "Ntilde" has a legacy accent component (tilde). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "Oacute" has a legacy accent component (acute). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "Ocircumflex" has a legacy accent component (circumflex). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "Odieresis" has a legacy accent component (dieresis). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "Ograve" has a legacy accent component (grave). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "Ohungarumlaut" has a legacy accent component (hungarumlaut). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "Otilde" has a legacy accent component (tilde). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "Racute" has a legacy accent component (acute). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "Rcaron" has a legacy accent component (caron). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "Sacute" has a legacy accent component (acute). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "Scaron" has a legacy accent component (caron). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "Scedilla" has a legacy accent component (cedilla). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "Tcaron" has a legacy accent component (caron). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "Uacute" has a legacy accent component (acute). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "Ubreve" has a legacy accent component (breve). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "Ucircumflex" has a legacy accent component (circumflex). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "Udieresis" has a legacy accent component (dieresis). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "Ugrave" has a legacy accent component (grave). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "Uhungarumlaut" has a legacy accent component (hungarumlaut). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "Uring" has a legacy accent component (ring). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "Wacute" has a legacy accent component (acute). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "Wcircumflex" has a legacy accent component (circumflex). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "Wdieresis" has a legacy accent component (dieresis). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "Wgrave" has a legacy accent component (grave). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "Yacute" has a legacy accent component (acute). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "Ycircumflex" has a legacy accent component (circumflex). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "Ydieresis" has a legacy accent component (dieresis). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "Ygrave" has a legacy accent component (grave). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "Zacute" has a legacy accent component (acute). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "Zcaron" has a legacy accent component (caron). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "Zdotaccent" has a legacy accent component (dotaccent). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "aacute" has a legacy accent component (acute). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "abreve" has a legacy accent component (breve). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "acircumflex" has a legacy accent component (circumflex). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "acutecomb" has a legacy accent component (acute). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "adieresis" has a legacy accent component (dieresis). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "agrave" has a legacy accent component (grave). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "aogonek" has a legacy accent component (ogonek). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "aring" has a legacy accent component (ring). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "atilde" has a legacy accent component (tilde). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "uni0306" has a legacy accent component (breve). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "cacute" has a legacy accent component (acute). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "uni030C" has a legacy accent component (caron). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "ccaron" has a legacy accent component (caron). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "ccedilla" has a legacy accent component (cedilla). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "cdotaccent" has a legacy accent component (dotaccent). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "uni0327" has a legacy accent component (cedilla). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "uni0302" has a legacy accent component (circumflex). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "uni0308" has a legacy accent component (dieresis). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "uni0307" has a legacy accent component (dotaccent). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "eacute" has a legacy accent component (acute). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "ecaron" has a legacy accent component (caron). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "ecircumflex" has a legacy accent component (circumflex). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "edieresis" has a legacy accent component (dieresis). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "edotaccent" has a legacy accent component (dotaccent). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "egrave" has a legacy accent component (grave). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "gbreve" has a legacy accent component (breve). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "gdotaccent" has a legacy accent component (dotaccent). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "gravecomb" has a legacy accent component (grave). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "uni030B" has a legacy accent component (hungarumlaut). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "iacute" has a legacy accent component (acute). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "icircumflex" has a legacy accent component (circumflex). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "idieresis" has a legacy accent component (dieresis). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "igrave" has a legacy accent component (grave). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "iogonek" has a legacy accent component (ogonek). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "lacute" has a legacy accent component (acute). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "nacute" has a legacy accent component (acute). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "ncaron" has a legacy accent component (caron). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "ntilde" has a legacy accent component (tilde). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "oacute" has a legacy accent component (acute). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "ocircumflex" has a legacy accent component (circumflex). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "odieresis" has a legacy accent component (dieresis). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "uni0328" has a legacy accent component (ogonek). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "ograve" has a legacy accent component (grave). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "ohungarumlaut" has a legacy accent component (hungarumlaut). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "otilde" has a legacy accent component (tilde). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "racute" has a legacy accent component (acute). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "rcaron" has a legacy accent component (caron). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "uni030A" has a legacy accent component (ring). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "sacute" has a legacy accent component (acute). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "scaron" has a legacy accent component (caron). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "scedilla" has a legacy accent component (cedilla). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "tildecomb" has a legacy accent component (tilde). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "uacute" has a legacy accent component (acute). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "ubreve" has a legacy accent component (breve). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "ucircumflex" has a legacy accent component (circumflex). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "udieresis" has a legacy accent component (dieresis). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "ugrave" has a legacy accent component (grave). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "uhungarumlaut" has a legacy accent component (hungarumlaut). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "uogonek" has a legacy accent component (ogonek). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "uring" has a legacy accent component (ring). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "wacute" has a legacy accent component (acute). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "wcircumflex" has a legacy accent component (circumflex). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "wdieresis" has a legacy accent component (dieresis). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "wgrave" has a legacy accent component (grave). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "yacute" has a legacy accent component (acute). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "ycircumflex" has a legacy accent component (circumflex). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "ydieresis" has a legacy accent component (dieresis). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "ygrave" has a legacy accent component (grave). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "zacute" has a legacy accent component (acute). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "zcaron" has a legacy accent component (caron). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "zdotaccent" has a legacy accent component (dotaccent). It needs to be replaced by a combining mark. [code: legacy-accents-component]
</div></details><details><summary>⚠ <b>WARN:</b> Check for codepoints not covered by METADATA subsets. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/metadata/unreachable_subsetting">com.google.fonts/check/metadata/unreachable_subsetting</a>)</summary><div>


* ⚠ **WARN** The following codepoints supported by the font are not covered by
    any subsets defined in the font's metadata file, and will never
    be served. You can solve this by either manually adding additional
    subset declarations to METADATA.pb, or by editing the glyphset
    definitions.

 * U+02C7 CARON: try adding one of: tifinagh, yi, canadian-aboriginal
 * U+02C9 MODIFIER LETTER MACRON: not included in any glyphset definition
 * U+02D8 BREVE: try adding one of: yi, canadian-aboriginal
 * U+02D9 DOT ABOVE: try adding one of: yi, canadian-aboriginal
 * U+02DB OGONEK: try adding one of: yi, canadian-aboriginal
 * U+02DD DOUBLE ACUTE ACCENT: not included in any glyphset definition
 * U+0302 COMBINING CIRCUMFLEX ACCENT: try adding one of: math, tifinagh, cherokee, coptic
 * U+0306 COMBINING BREVE: try adding one of: tifinagh, old-permic
 * U+0307 COMBINING DOT ABOVE: try adding one of: tai-le, tifinagh, syriac, old-permic, malayalam, coptic, math, canadian-aboriginal
 * U+030A COMBINING RING ABOVE: try adding syriac
 * U+030B COMBINING DOUBLE ACUTE ACCENT: try adding one of: cherokee, osage
 * U+030C COMBINING CARON: try adding one of: tai-le, cherokee
 * U+0312 COMBINING TURNED COMMA ABOVE: not included in any glyphset definition
 * U+0326 COMBINING COMMA BELOW: not included in any glyphset definition
 * U+0327 COMBINING CEDILLA: not included in any glyphset definition
 * U+0328 COMBINING OGONEK: not included in any glyphset definition
 * U+0951 DEVANAGARI STRESS SIGN UDATTA: try adding one of: grantha, telugu, sharada, devanagari, tirhuta
 * U+0952 DEVANAGARI STRESS SIGN ANUDATTA: try adding one of: telugu, tirhuta, grantha, devanagari
 * U+0CF3 KANNADA SIGN COMBINING ANUSVARA ABOVE RIGHT: not included in any glyphset definition
 * U+1CD0 VEDIC TONE KARSHANA: try adding one of: grantha, devanagari
 * U+1CD2 VEDIC TONE PRENKHA: try adding one of: grantha, devanagari
 * U+1CDA VEDIC TONE DOUBLE SVARITA: try adding one of: telugu, devanagari
 * U+1CF2 VEDIC SIGN ARDHAVISARGA: try adding one of: tirhuta, nandinagari, grantha, devanagari
 * U+1CF4 VEDIC TONE CANDRA ABOVE: try adding one of: grantha, devanagari
 * U+1CF5 VEDIC SIGN JIHVAMULIYA: try adding devanagari
 * U+2010 HYPHEN: try adding one of: lisu, yi, coptic, kaithi, sora-sompeng, syloti-nagri, kayah-li, kharoshthi, sundanese, cham
 * U+A830 NORTH INDIC FRACTION ONE QUARTER: try adding one of: modi, takri, gurmukhi, gujarati, kaithi, mahajani, khudawadi, tirhuta, devanagari, khojki, nandinagari
 * U+A831 NORTH INDIC FRACTION ONE HALF: try adding one of: modi, takri, gurmukhi, gujarati, kaithi, mahajani, khudawadi, tirhuta, devanagari, khojki, nandinagari
 * U+A832 NORTH INDIC FRACTION THREE QUARTERS: try adding one of: modi, takri, gurmukhi, gujarati, kaithi, mahajani, khudawadi, tirhuta, devanagari, khojki, nandinagari
 * U+A833 NORTH INDIC FRACTION ONE SIXTEENTH: try adding one of: modi, takri, gurmukhi, gujarati, kaithi, mahajani, khudawadi, tirhuta, devanagari, khojki, nandinagari
 * U+A834 NORTH INDIC FRACTION ONE EIGHTH: try adding one of: modi, takri, gurmukhi, gujarati, kaithi, mahajani, khudawadi, tirhuta, devanagari, khojki, nandinagari
 * U+A835 NORTH INDIC FRACTION THREE SIXTEENTHS: try adding one of: modi, takri, gurmukhi, gujarati, kaithi, mahajani, khudawadi, tirhuta, devanagari, khojki, nandinagari

Or you can add the above codepoints to one of the subsets supported by the font: `kannada`, `latin`, `latin-ext` [code: unreachable-subsetting]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

	- aivowelsignUIknda

	- backslash.UIknda

	- bar.UIknda

	- basubscriptaltUIknda

	- basubscriptrightUIknda

	- bharasubscriptaltUIknda

	- bhasubscriptaltUIknda

	- bhasubscriptrightUIknda

	- braceleft.UIknda

	- braceright.UIknda

	- bracketleft.UIknda

	- bracketright.UIknda

	- casubscriptaltUIknda

	- casubscriptrightUIknda

	- chasubscriptaltUIknda

	- chasubscriptrightUIknda

	- darasubscriptaltUIknda

	- dasubscriptaltUIknda

	- dasubscriptrightUIknda

	- ddarasubscriptaltUIknda

	- ddasubscriptaltUIknda

	- ddasubscriptrightUIknda

	- ddhasubscriptaltUIknda

	- ddhasubscriptrightUIknda

	- dhasubscriptaltUIknda

	- dhasubscriptrightUIknda

	- fasubscriptaltUIknda

	- fasubscriptrightUIknda

	- garasubscriptaltUIknda

	- gasubscriptaltUIknda

	- gasubscriptrightUIknda

	- ghasubscriptaltUIknda

	- ghasubscriptrightUIknda

	- hasubscriptaltUIknda

	- hasubscriptrightUIknda

	- januktasubscriptaltUIknda

	- januktasubscriptrightUIknda

	- janyaUIknda

	- janyanocrestUIknda

	- janyaviramaUIknda

	- janyevowelUIknda

	- janyivowelUIknda

	- jasubscriptaltUIknda

	- jasubscriptrightUIknda

	- jhasubscriptaltUIknda

	- jhasubscriptrightUIknda

	- karasubscriptaltUIknda

	- kassaUIknda

	- kassanocrestUIknda

	- kassaviramaUIknda

	- kassevowelUIknda

	- kassivowelUIknda

	- kasubscriptaltUIknda

	- kasubscriptrightUIknda

	- khasubscriptaltUIknda

	- khasubscriptrightUIknda

	- lasubscriptaltUIknda

	- lasubscriptrightUIknda

	- llasubscriptaltUIknda

	- llasubscriptrightUIknda

	- llvocalicvowelsignaltUIknda

	- lvocalicvowelsignaltUIknda

	- masubscriptaltUIknda

	- masubscriptlengthmarkUIknda

	- masubscriptlengthmarkaltUIknda

	- masubscriptrightUIknda

	- masubscriptrvocalicUIknda

	- masubscriptrvocalicaltUIknda

	- mayasubscriptUIknda

	- mayasubscriptaltUIknda

	- nasubscriptaltUIknda

	- nasubscriptrightUIknda

	- ngasubscriptaltUIknda

	- ngasubscriptrightUIknda

	- nnasubscriptaltUIknda

	- nnasubscriptrightUIknda

	- nyasubscriptaltUIknda

	- nyasubscriptrightUIknda

	- parasubscriptaltUIknda

	- parenleft.UIknda

	- parenright.UIknda

	- pasubscriptaltUIknda

	- pasubscriptrightUIknda

	- phanuktasubscriptaltUIknda

	- phanuktasubscriptrightUIknda

	- phasubscriptaltUIknda

	- phasubscriptrightUIknda

	- question

	- rasubscriptlengthmarkUIknda

	- rasubscriptlengthmarkaltUIknda

	- rasubscriptrightUIknda

	- rrasubscriptaltUIknda

	- rrasubscriptrightUIknda

	- rrvocalicvowelsignUIknda

	- rrvocalicvowelsignaltUIknda

	- rvocalicvowelsignUIknda

	- sasubscriptaltUIknda

	- sasubscriptrightUIknda

	- shasubscriptaltUIknda

	- shasubscriptrightUIknda

	- slash.UIknda

	- ssasubscriptaltUIknda

	- ssasubscriptrightUIknda

	- tarasubscriptUIknda

	- tarasubscriptaltUIknda

	- tasubscriptUIknda

	- tasubscriptaltUIknda

	- tasubscriptlengthmarkUIknda

	- tasubscriptlengthmarkaltUIknda

	- tasubscriptrightUIknda

	- tasubscriptrvocalicUIknda

	- tasubscriptrvocalicaltUIknda

	- tayasubscriptUIknda

	- tayasubscriptaltUIknda

	- thasubscriptaltUIknda

	- thasubscriptrightUIknda

	- ttarasubscriptaltUIknda

	- ttasubscriptaltUIknda

	- ttasubscriptrightUIknda

	- tthasubscriptaltUIknda

	- tthasubscriptrightUIknda

	- vasubscriptaltUIknda

	- vasubscriptrightUIknda

	- yasubscriptUIknda

	- yasubscriptrightUIknda
 [code: unreachable-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Does the font contain a soft hyphen? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/soft_hyphen">com.google.fonts/check/soft_hyphen</a>)</summary><div>


* ⚠ **WARN** This font has a 'Soft Hyphen' character. [code: softhyphen]
</div></details><details><summary>⚠ <b>WARN:</b> Check glyphs in mark glyph class are non-spacing. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_spacing_marks">com.google.fonts/check/gdef_spacing_marks</a>)</summary><div>


* ⚠ **WARN** The following spacing glyphs may be in the GDEF mark glyph class by mistake:
	 aavowelsignaltknda (unencoded), aavowelsignknda (U+0CBE), anusvaraaboverightknda (U+0CF3), auvowelsignknda (U+0CCC), basubscriptUIknda (unencoded), basubscriptaltUIknda (unencoded), basubscriptaltknda (unencoded), basubscriptknda (unencoded), basubscriptrightUIknda (unencoded), basubscriptrightknda (unencoded), baviramaknda (unencoded), bharasubscriptaltknda (unencoded), bharasubscriptknda (unencoded), bhasubscriptUIknda (unencoded), bhasubscriptaltUIknda (unencoded), bhasubscriptaltknda (unencoded), bhasubscriptknda (unencoded), bhasubscriptrightUIknda (unencoded), bhasubscriptrightknda (unencoded), casubscriptaltknda (unencoded), casubscriptknda (unencoded), chasubscriptaltknda (unencoded), chasubscriptknda (unencoded), darasubscriptaltknda (unencoded), darasubscriptknda (unencoded), dasubscriptaltknda (unencoded), dasubscriptknda (unencoded), ddarasubscriptaltknda (unencoded), ddarasubscriptknda (unencoded), ddasubscriptaltknda (unencoded), ddasubscriptknda (unencoded), ddhasubscriptaltknda (unencoded), ddhasubscriptknda (unencoded), dhasubscriptaltknda (unencoded), dhasubscriptknda (unencoded), evowelsignaltknda (unencoded), fasubscriptaltknda (unencoded), fasubscriptknda (unencoded), garasubscriptaltknda (unencoded), garasubscriptknda (unencoded), gasubscriptaltknda (unencoded), gasubscriptknda (unencoded), ghasubscriptaltknda (unencoded), ghasubscriptknda (unencoded), hasubscriptaltknda (unencoded), hasubscriptknda (unencoded), iivowelsignknda (U+0CC0), ivowelsignknda (U+0CBF), januktasubscriptaltknda (unencoded), januktasubscriptknda (unencoded), jasubscriptaltknda (unencoded), jasubscriptknda (unencoded), jhasubscriptaltknda (unencoded), jhasubscriptknda (unencoded), karasubscriptaltknda (unencoded), karasubscriptknda (unencoded), kasubscriptaltknda (unencoded), kasubscriptknda (unencoded), khasubscriptaltknda (unencoded), khasubscriptknda (unencoded), lasubscriptaltknda (unencoded), lasubscriptknda (unencoded), lengthmarkknda (U+0CD5), llasubscriptaltknda (unencoded), llasubscriptknda (unencoded), masubscriptaltknda (unencoded), masubscriptknda (unencoded), mayasubscriptaltknda (unencoded), mayasubscriptknda (unencoded), nasubscriptUIknda (unencoded), nasubscriptaltUIknda (unencoded), nasubscriptaltknda (unencoded), nasubscriptknda (unencoded), nasubscriptrightUIknda (unencoded), nasubscriptrightknda (unencoded), ngasubscriptaltknda (unencoded), ngasubscriptknda (unencoded), nnasubscriptUIknda (unencoded), nnasubscriptaltUIknda (unencoded), nnasubscriptaltknda (unencoded), nnasubscriptknda (unencoded), nnasubscriptrightUIknda (unencoded), nnasubscriptrightknda (unencoded), nyasubscriptaltknda (unencoded), nyasubscriptknda (unencoded), parasubscriptaltknda (unencoded), parasubscriptknda (unencoded), pasubscriptaltknda (unencoded), pasubscriptknda (unencoded), phanuktasubscriptaltknda (unencoded), phanuktasubscriptknda (unencoded), phasubscriptaltknda (unencoded), phasubscriptknda (unencoded), rasubscriptaltknda (unencoded), rasubscriptknda (unencoded), rrasubscriptaltknda (unencoded), rrasubscriptknda (unencoded), sasubscriptUIknda (unencoded), sasubscriptaltknda (unencoded), sasubscriptknda (unencoded), shasubscriptaltknda (unencoded), shasubscriptknda (unencoded), ssasubscriptUIknda (unencoded), ssasubscriptaltUIknda (unencoded), ssasubscriptaltknda (unencoded), ssasubscriptknda (unencoded), ssasubscriptrightUIknda (unencoded), ssasubscriptrightknda (unencoded), tarasubscriptaltknda (unencoded), tarasubscriptknda (unencoded), tasubscriptaltknda (unencoded), tasubscriptknda (unencoded), tayasubscriptaltknda (unencoded), tayasubscriptknda (unencoded), thasubscriptaltknda (unencoded), thasubscriptknda (unencoded), ttarasubscriptaltknda (unencoded), ttarasubscriptknda (unencoded), ttasubscriptaltknda (unencoded), ttasubscriptknda (unencoded), tthasubscriptaltknda (unencoded), tthasubscriptknda (unencoded), uuvowelsignalt2knda (unencoded), uuvowelsignaltknda (unencoded), uuvowelsignknda (U+0CC2), uuvowelsignlaknda (unencoded), uvowelsignalt2knda (unencoded), uvowelsignaltknda (unencoded), uvowelsignknda (U+0CC1), uvowelsignlaknda (unencoded), vasubscriptaltknda (unencoded), vasubscriptknda (unencoded), visargaknda (U+0C83), yasubscriptaltknda (unencoded) and yasubscriptknda (unencoded) [code: spacing-mark-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check mark characters are in GDEF mark glyph class. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_mark_chars">com.google.fonts/check/gdef_mark_chars</a>)</summary><div>


* ⚠ **WARN** The following mark characters could be in the GDEF mark glyph class:
	 llvocalicvowelsignknda (U+0CE3), lvocalicvowelsignknda (U+0CE2) and viramaknda (U+0CCD) [code: mark-chars]
</div></details><details><summary>⚠ <b>WARN:</b> Check GDEF mark glyph class doesn't have characters that are not marks. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_non_mark_chars">com.google.fonts/check/gdef_non_mark_chars</a>)</summary><div>


* ⚠ **WARN** The following non-mark characters should not be in the GDEF mark glyph class:
	 U+0C83, U+0CBE, U+0CC0, U+0CC1, U+0CC2, U+0CC8, U+0CCA, U+0CCB, U+0CD5 and U+0CF3 [code: non-mark-chars]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure soft_dotted characters lose their dot when combined with marks that replace the dot. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Shaping Checks>.html#com.google.fonts/check/soft_dotted">com.google.fonts/check/soft_dotted</a>)</summary><div>


* ⚠ **WARN** The dot of soft dotted characters used in orthographies _must_ disappear in the following strings: į̀ į́ į̂ į̃ į̄ į̌

The dot of soft dotted characters _should_ disappear in other cases, for example: į̆ į̇ į̈ į̊ į̋ į̒ į̦̀ į̦́ į̦̂ į̦̃ į̦̄ į̦̆ į̦̇ į̦̈ į̦̊ į̦̋ į̦̌ į̦̒ į̧̀ į̧́

Your font fully covers the following languages that require the soft-dotted feature: Lithuanian (Latn, 2,357,094 speakers), Dutch (Latn, 31,709,104 speakers). 

Your font does *not* cover the following languages that require the soft-dotted feature: Nateni (Latn, 100,000 speakers), Ma’di (Latn, 584,000 speakers), Lugbara (Latn, 2,200,000 speakers), Dan (Latn, 1,099,244 speakers), Ebira (Latn, 2,200,000 speakers), Kom (Latn, 360,685 speakers), Ukrainian (Cyrl, 29,273,587 speakers), Navajo (Latn, 166,319 speakers), Ejagham (Latn, 120,000 speakers), Avokaya (Latn, 100,000 speakers), Aghem (Latn, 38,843 speakers), Koonzime (Latn, 40,000 speakers), Igbo (Latn, 27,823,640 speakers), Basaa (Latn, 332,940 speakers), Belarusian (Cyrl, 10,064,517 speakers). [code: soft-dotted]
</div></details><br></div></details>

### Summary

| 💔 ERROR | 🔥 FAIL | ⚠ WARN | 💤 SKIP | ℹ INFO | 🍞 PASS | 🔎 DEBUG |
|:-----:|:----:|:----:|:----:|:----:|:----:|:----:|
| 0 | 3 | 8 | 101 | 8 | 135 | 0 |
| 0% | 1% | 3% | 40% | 3% | 53% | 0% |

**Note:** The following loglevels were omitted in this report:
* **SKIP**
* **INFO**
* **PASS**
* **DEBUG**
