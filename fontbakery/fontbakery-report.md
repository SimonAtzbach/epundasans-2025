## FontBakery report

fontbakery version: 0.12.10





## Check results



<details><summary>[16] EpundaSans-Italic[wght].ttf</summary>
<div>
<details>
    <summary>🔥 <b>FAIL</b> Check accent of Lcaron, dcaron, lcaron, tcaron <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#"></a></summary>
    <div>







* 🔥 **FAIL** <p>Lcaron uses component uni030C.</p>
 [code: wrong-mark]



* 🔥 **FAIL** <p>lcaron uses component uni030C.</p>
 [code: wrong-mark]



* 🔥 **FAIL** <p>tcaron uses component uni030C.</p>
 [code: wrong-mark]



* ⚠️ **WARN** <p>dcaron is decomposed and therefore could not be checked. Please check manually.</p>
 [code: decomposed-outline]



</div>
</details>

<details>
    <summary>🔥 <b>FAIL</b> Ensure the font supports case swapping for all its glyphs. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.glyphset.html#"></a></summary>
    <div>







* 🔥 **FAIL** <p>The following glyphs lack their case-swapping counterparts:</p>
<table>
<thead>
<tr>
<th align="left">Glyph present in the font</th>
<th align="left">Missing case-swapping counterpart</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">U+01DF: LATIN SMALL LETTER A WITH DIAERESIS AND MACRON</td>
<td align="left">U+01DE: LATIN CAPITAL LETTER A WITH DIAERESIS AND MACRON</td>
</tr>
<tr>
<td align="left">U+1EA1: LATIN SMALL LETTER A WITH DOT BELOW</td>
<td align="left">U+1EA0: LATIN CAPITAL LETTER A WITH DOT BELOW</td>
</tr>
</tbody>
</table>
 [code: missing-case-counterparts]



</div>
</details>

<details>
    <summary>🔥 <b>FAIL</b> Combined length of family and style must not exceed 32 characters. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.name.html#"></a></summary>
    <div>







* 🔥 **FAIL** <p>Variable font instance name 'Epunda Sans Light SemiBold Italic' formed by space-separated concatenation of font family name (nameID 1) and instance subfamily nameID 263 exceeds 32 characters.</p>
<p>This has been found to cause shaping issues for some accented letters in Microsoft Word on Windows 10 and 11.</p>
 [code: instance-too-long]



* 🔥 **FAIL** <p>Variable font instance name 'Epunda Sans Light SemiBold Italic' formed by space-separated concatenation of font family name (nameID 1) and instance subfamily nameID 263 exceeds 32 characters.</p>
<p>This has been found to cause shaping issues for some accented letters in Microsoft Word on Windows 10 and 11.</p>
 [code: instance-too-long]



* 🔥 **FAIL** <p>Variable font instance name 'Epunda Sans Light ExtraBold Italic' formed by space-separated concatenation of font family name (nameID 1) and instance subfamily nameID 267 exceeds 32 characters.</p>
<p>This has been found to cause shaping issues for some accented letters in Microsoft Word on Windows 10 and 11.</p>
 [code: instance-too-long]



* 🔥 **FAIL** <p>Variable font instance name 'Epunda Sans Light ExtraBold Italic' formed by space-separated concatenation of font family name (nameID 1) and instance subfamily nameID 267 exceeds 32 characters.</p>
<p>This has been found to cause shaping issues for some accented letters in Microsoft Word on Windows 10 and 11.</p>
 [code: instance-too-long]



</div>
</details>

<details>
    <summary>🔥 <b>FAIL</b> Ensure dotted circle glyph is present and can attach marks. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/shaping.html#"></a></summary>
    <div>







* 🔥 **FAIL** <p>The following glyphs could not be attached to the dotted circle glyph:</p>
<pre><code>- acutecomb

- dotbelowcomb

- gravecomb

- tildecomb

- uni0302

- uni0304

- uni0306

- uni0307

- uni0308

- uni030A

- uni030B

- uni030C

- uni0312

- uni0326

- uni0327

- uni0328

- uni032D

- uni0331

- uni0335
</code></pre>
 [code: unattached-dotted-circle-marks]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Check math signs have the same width. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>The most common width is 600 among a set of 9 math glyphs.
The following math glyphs have a different width, though:</p>
<p>Width = 601:
divide, minus, plusminus</p>
<p>Width = 558:
approxequal</p>
 [code: width-outliers]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Does the font contain a soft hyphen? <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.glyphset.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>This font has a 'Soft Hyphen' character.</p>
 [code: softhyphen]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Check font contains no unreachable glyphs <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.glyphset.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>The following glyphs could not be reached by codepoint or substitution rules:</p>
<pre><code>- Dcroat.001

- uni030C.alt
</code></pre>
 [code: unreachable-glyphs]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Validate size, and resolution of article images, and ensure article page has minimum length and includes visual assets. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.article.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>Family metadata at fonts/variable does not have an article.</p>
 [code: lacks-article]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Check for codepoints not covered by METADATA subsets. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.subsets.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>The following codepoints supported by the font are not covered by
any subsets defined in the font's metadata file, and will never
be served. You can solve this by either manually adding additional
subset declarations to METADATA.pb, or by editing the glyphset
definitions.</p>
<ul>
<li>U+02D8 BREVE: try adding one of: yi, canadian-aboriginal</li>
<li>U+02D9 DOT ABOVE: try adding one of: yi, canadian-aboriginal</li>
<li>U+02DB OGONEK: try adding one of: yi, canadian-aboriginal</li>
<li>U+0302 COMBINING CIRCUMFLEX ACCENT: try adding one of: tifinagh, math, cherokee, coptic</li>
<li>U+0306 COMBINING BREVE: try adding one of: tifinagh, old-permic</li>
<li>U+0307 COMBINING DOT ABOVE: try adding one of: duployan, syriac, todhri, malayalam, tai-le, tifinagh, hebrew, coptic, old-permic, math, canadian-aboriginal</li>
<li>U+030A COMBINING RING ABOVE: try adding one of: duployan, syriac</li>
<li>U+030B COMBINING DOUBLE ACUTE ACCENT: try adding one of: cherokee, osage</li>
<li>U+030C COMBINING CARON: try adding one of: cherokee, tai-le</li>
<li>U+0312 COMBINING TURNED COMMA ABOVE: try adding math</li>
<li>U+0326 COMBINING COMMA BELOW: try adding math</li>
<li>U+0327 COMBINING CEDILLA: try adding math</li>
<li>U+0328 COMBINING OGONEK: not included in any glyphset definition</li>
<li>U+032D COMBINING CIRCUMFLEX ACCENT BELOW: try adding one of: syriac, sunuwar</li>
<li>U+0331 COMBINING MACRON BELOW: try adding one of: syriac, sunuwar, gothic, caucasian-albanian, cherokee, tifinagh, thai</li>
<li>U+0335 COMBINING SHORT STROKE OVERLAY: not included in any glyphset definition</li>
<li>U+03A9 GREEK CAPITAL LETTER OMEGA: try adding one of: elbasan, math, greek</li>
<li>U+03C0 GREEK SMALL LETTER PI: try adding one of: yi, math, greek</li>
<li>U+0E3F THAI CURRENCY SYMBOL BAHT: try adding thai</li>
<li>U+1EA1 LATIN SMALL LETTER A WITH DOT BELOW: try adding vietnamese</li>
<li>U+1EAC LATIN CAPITAL LETTER A WITH CIRCUMFLEX AND DOT BELOW: try adding vietnamese</li>
<li>U+1EAD LATIN SMALL LETTER A WITH CIRCUMFLEX AND DOT BELOW: try adding vietnamese</li>
<li>U+1EB8 LATIN CAPITAL LETTER E WITH DOT BELOW: try adding vietnamese</li>
<li>U+1EB9 LATIN SMALL LETTER E WITH DOT BELOW: try adding vietnamese</li>
<li>U+1EBC LATIN CAPITAL LETTER E WITH TILDE: try adding vietnamese</li>
<li>U+1EBD LATIN SMALL LETTER E WITH TILDE: try adding vietnamese</li>
<li>U+1EC6 LATIN CAPITAL LETTER E WITH CIRCUMFLEX AND DOT BELOW: try adding vietnamese</li>
<li>U+1EC7 LATIN SMALL LETTER E WITH CIRCUMFLEX AND DOT BELOW: try adding vietnamese</li>
<li>U+1ECA LATIN CAPITAL LETTER I WITH DOT BELOW: try adding vietnamese</li>
<li>U+1ECB LATIN SMALL LETTER I WITH DOT BELOW: try adding vietnamese</li>
<li>U+1ECC LATIN CAPITAL LETTER O WITH DOT BELOW: try adding vietnamese</li>
<li>U+1ECD LATIN SMALL LETTER O WITH DOT BELOW: try adding vietnamese</li>
<li>U+1ED8 LATIN CAPITAL LETTER O WITH CIRCUMFLEX AND DOT BELOW: try adding vietnamese</li>
<li>U+1ED9 LATIN SMALL LETTER O WITH CIRCUMFLEX AND DOT BELOW: try adding vietnamese</li>
<li>U+1EE4 LATIN CAPITAL LETTER U WITH DOT BELOW: try adding vietnamese</li>
<li>U+1EE5 LATIN SMALL LETTER U WITH DOT BELOW: try adding vietnamese</li>
<li>U+2000 EN QUAD: try adding symbols2</li>
<li>U+2001 EM QUAD: try adding symbols2</li>
<li>U+2003 EM SPACE: try adding nushu</li>
<li>U+2004 THREE-PER-EM SPACE: try adding symbols2</li>
<li>U+2005 FOUR-PER-EM SPACE: try adding symbols2</li>
<li>U+2006 SIX-PER-EM SPACE: try adding symbols2</li>
<li>U+2007 FIGURE SPACE: try adding symbols2</li>
<li>U+2008 PUNCTUATION SPACE: try adding symbols2</li>
<li>U+200A HAIR SPACE: try adding symbols2</li>
<li>U+200C ZERO WIDTH NON-JOINER: try adding one of: pahawh-hmong, saurashtra, tagalog, arabic, zanabazar-square, tirhuta, sundanese, takri, grantha, warang-citi, yi, gunjala-gondi, thaana, modi, mongolian, cham, psalter-pahlavi, bengali, kayah-li, meetei-mayek, lao, kharoshthi, hatran, newa, rejang, dogra, sogdian, thai, bhaiksuki, masaram-gondi, new-tai-lue, buhid, duployan, kannada, lepcha, batak, nko, limbu, khudawadi, balinese, sharada, malayalam, syriac, mandaic, tai-viet, javanese, devanagari, hanunoo, mahajani, gurmukhi, sinhala, brahmi, khmer, syloti-nagri, tamil, myanmar, buginese, hanifi-rohingya, tagbanwa, telugu, phags-pa, avestan, manichaean, oriya, chakma, hebrew, tai-tham, tibetan, tifinagh, gujarati, tai-le, kaithi, siddham, khojki</li>
<li>U+200D ZERO WIDTH JOINER: try adding one of: pahawh-hmong, saurashtra, tagalog, arabic, zanabazar-square, tirhuta, sundanese, takri, grantha, warang-citi, yi, gunjala-gondi, thaana, modi, mongolian, cham, psalter-pahlavi, bengali, kayah-li, meetei-mayek, old-hungarian, lao, kharoshthi, newa, rejang, dogra, sogdian, thai, bhaiksuki, masaram-gondi, new-tai-lue, buhid, duployan, kannada, lepcha, batak, nko, limbu, khudawadi, balinese, sharada, malayalam, syriac, mandaic, tai-viet, javanese, devanagari, hanunoo, mahajani, gurmukhi, sinhala, brahmi, khmer, syloti-nagri, tamil, myanmar, buginese, hanifi-rohingya, tagbanwa, telugu, phags-pa, avestan, manichaean, oriya, chakma, hebrew, tai-tham, tibetan, tifinagh, gujarati, tai-le, kaithi, siddham, khojki</li>
<li>U+200E LEFT-TO-RIGHT MARK: try adding one of: syriac, nko, arabic, phags-pa, hebrew, thaana</li>
<li>U+200F RIGHT-TO-LEFT MARK: try adding one of: syriac, nko, phags-pa, hebrew, thaana</li>
<li>U+2021 DOUBLE DAGGER: try adding adlam</li>
<li>U+202F NARROW NO-BREAK SPACE: try adding one of: yi, phags-pa, mongolian</li>
<li>U+2030 PER MILLE SIGN: try adding adlam</li>
<li>U+205F MEDIUM MATHEMATICAL SPACE: try adding math</li>
<li>U+2070 SUPERSCRIPT ZERO: try adding math</li>
<li>U+2074 SUPERSCRIPT FOUR: try adding math</li>
<li>U+2075 SUPERSCRIPT FIVE: try adding math</li>
<li>U+2076 SUPERSCRIPT SIX: try adding math</li>
<li>U+2077 SUPERSCRIPT SEVEN: try adding math</li>
<li>U+2078 SUPERSCRIPT EIGHT: try adding math</li>
<li>U+2079 SUPERSCRIPT NINE: try adding math</li>
<li>U+2080 SUBSCRIPT ZERO: try adding math</li>
<li>U+2081 SUBSCRIPT ONE: try adding math</li>
<li>U+2082 SUBSCRIPT TWO: try adding math</li>
<li>U+2083 SUBSCRIPT THREE: try adding math</li>
<li>U+2084 SUBSCRIPT FOUR: try adding math</li>
<li>U+2085 SUBSCRIPT FIVE: try adding math</li>
<li>U+2086 SUBSCRIPT SIX: try adding math</li>
<li>U+2087 SUBSCRIPT SEVEN: try adding math</li>
<li>U+2088 SUBSCRIPT EIGHT: try adding math</li>
<li>U+2089 SUBSCRIPT NINE: try adding math</li>
<li>U+215B VULGAR FRACTION ONE EIGHTH: try adding symbols</li>
<li>U+215C VULGAR FRACTION THREE EIGHTHS: try adding symbols</li>
<li>U+215D VULGAR FRACTION FIVE EIGHTHS: try adding symbols</li>
<li>U+215E VULGAR FRACTION SEVEN EIGHTHS: try adding symbols</li>
<li>U+2190 LEFTWARDS ARROW: try adding one of: symbols, math</li>
<li>U+2192 RIGHTWARDS ARROW: try adding one of: symbols, math</li>
<li>U+2194 LEFT RIGHT ARROW: try adding one of: symbols, math</li>
<li>U+2195 UP DOWN ARROW: try adding one of: symbols, math</li>
<li>U+2196 NORTH WEST ARROW: try adding one of: symbols, math</li>
<li>U+2197 NORTH EAST ARROW: try adding one of: symbols, math</li>
<li>U+2198 SOUTH EAST ARROW: try adding one of: symbols, math</li>
<li>U+2199 SOUTH WEST ARROW: try adding one of: symbols, math</li>
<li>U+2202 PARTIAL DIFFERENTIAL: try adding math</li>
<li>U+2206 INCREMENT: try adding math</li>
<li>U+220F N-ARY PRODUCT: try adding math</li>
<li>U+2211 N-ARY SUMMATION: try adding math</li>
<li>U+2219 BULLET OPERATOR: try adding one of: tai-tham, yi, symbols, math</li>
<li>U+221A SQUARE ROOT: try adding math</li>
<li>U+221E INFINITY: try adding math</li>
<li>U+222B INTEGRAL: try adding math</li>
<li>U+2248 ALMOST EQUAL TO: try adding math</li>
<li>U+2260 NOT EQUAL TO: try adding math</li>
<li>U+2264 LESS-THAN OR EQUAL TO: try adding math</li>
<li>U+2265 GREATER-THAN OR EQUAL TO: try adding math</li>
<li>U+25CA LOZENGE: try adding one of: symbols, math</li>
<li>U+25CC DOTTED CIRCLE: try adding one of: pahawh-hmong, yi, mende-kikakui, miao, thaana, cham, psalter-pahlavi, newa, coptic, soyombo, thai, siddham, new-tai-lue, kannada, duployan, sharada, balinese, javanese, brahmi, buginese, caucasian-albanian, hebrew, elbasan, kaithi, saurashtra, zanabazar-square, mongolian, bengali, kayah-li, sogdian, buhid, syriac, limbu, malayalam, canadian-aboriginal, syloti-nagri, hanunoo, sinhala, music, hanifi-rohingya, phags-pa, tibetan, manichaean, tifinagh, tai-le, telugu, tirhuta, grantha, gunjala-gondi, modi, lao, kharoshthi, rejang, ahom, bhaiksuki, masaram-gondi, wancho, batak, khudawadi, mandaic, armenian, gurmukhi, tamil, myanmar, oriya, gujarati, takri, sundanese, marchen, tagalog, warang-citi, meetei-mayek, adlam, dogra, math, bassa-vah, lepcha, tai-tham, nko, tai-viet, mahajani, devanagari, khmer, old-permic, symbols, tagbanwa, chakma, osage, khojki</li>
<li>U+3000 IDEOGRAPHIC SPACE: try adding one of: phags-pa, yi, chinese-simplified, nushu, chinese-traditional, chinese-hongkong, japanese</li>
<li>U+FB01 LATIN SMALL LIGATURE FI: not included in any glyphset definition</li>
<li>U+FB02 LATIN SMALL LIGATURE FL: not included in any glyphset definition</li>
<li>U+FF01 FULLWIDTH EXCLAMATION MARK: try adding one of: yi, chinese-simplified, japanese</li>
<li>U+FF02 FULLWIDTH QUOTATION MARK: try adding one of: yi, chinese-simplified, japanese</li>
<li>U+FF03 FULLWIDTH NUMBER SIGN: try adding one of: chinese-simplified, japanese</li>
<li>U+FF05 FULLWIDTH PERCENT SIGN: try adding one of: chinese-simplified, japanese</li>
<li>U+FF06 FULLWIDTH AMPERSAND: try adding one of: chinese-simplified, japanese</li>
<li>U+FF07 FULLWIDTH APOSTROPHE: try adding one of: chinese-simplified, japanese</li>
<li>U+FF08 FULLWIDTH LEFT PARENTHESIS: try adding one of: yi, chinese-simplified, japanese</li>
<li>U+FF09 FULLWIDTH RIGHT PARENTHESIS: try adding one of: yi, chinese-simplified, japanese</li>
<li>U+FF0A FULLWIDTH ASTERISK: try adding one of: chinese-simplified, japanese</li>
<li>U+FF0C FULLWIDTH COMMA: try adding one of: yi, chinese-simplified, japanese</li>
<li>U+FF0D FULLWIDTH HYPHEN-MINUS: try adding one of: chinese-simplified, japanese</li>
<li>U+FF0E FULLWIDTH FULL STOP: try adding one of: yi, chinese-simplified, japanese</li>
<li>U+FF0F FULLWIDTH SOLIDUS: try adding one of: yi, chinese-simplified, japanese</li>
<li>U+FF1A FULLWIDTH COLON: try adding one of: yi, chinese-simplified, japanese</li>
<li>U+FF1B FULLWIDTH SEMICOLON: try adding one of: yi, chinese-simplified, japanese</li>
<li>U+FF1F FULLWIDTH QUESTION MARK: try adding one of: yi, chinese-simplified, japanese</li>
<li>U+FF20 FULLWIDTH COMMERCIAL AT: try adding one of: chinese-simplified, japanese</li>
<li>U+FF3B FULLWIDTH LEFT SQUARE BRACKET: try adding one of: yi, chinese-simplified, japanese</li>
<li>U+FF3C FULLWIDTH REVERSE SOLIDUS: try adding one of: chinese-simplified, japanese</li>
<li>U+FF3D FULLWIDTH RIGHT SQUARE BRACKET: try adding one of: yi, chinese-simplified, japanese</li>
<li>U+FF3F FULLWIDTH LOW LINE: try adding one of: chinese-simplified, japanese</li>
<li>U+FF5B FULLWIDTH LEFT CURLY BRACKET: try adding one of: yi, chinese-simplified, math, japanese</li>
<li>U+FF5D FULLWIDTH RIGHT CURLY BRACKET: try adding one of: yi, chinese-simplified, math, japanese</li>
</ul>
<p>Or you can add the above codepoints to one of the subsets supported by the font: <code>cyrillic-ext</code>, <code>latin</code>, <code>latin-ext</code></p>
 [code: unreachable-subsetting]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Ensure soft_dotted characters lose their dot when combined with marks that replace the dot. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/shaping.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>The dot of soft dotted characters used in orthographies <em>must</em> disappear in the following strings: į̀ į́ į̂ į̃ į̄ į̌ ị̀ ị́ ị̂ ị̃ ị̄</p>
<p>The dot of soft dotted characters <em>should</em> disappear in other cases, for example: į̆ į̇ į̈ į̊ į̋ į̒ į̣̀ į̣́ į̣̂ į̣̃ į̣̄ į̣̆ į̣̇ į̣̈ į̣̊ į̣̋ į̣̌ į̣̒ į̦̀ į̦́</p>
<p>Your font fully covers the following languages that require the soft-dotted feature: Lithuanian (Latn, 2,357,094 speakers), Han (Latn, 6 speakers), Navajo (Latn, 166,319 speakers), Dutch (Latn, 31,709,104 speakers), Kaska (Latn, 125 speakers).</p>
<p>Your font does <em>not</em> cover the following languages that require the soft-dotted feature: Ejagham (Latn, 120,000 speakers), Ngbaka (Latn, 1,020,000 speakers), Basaa (Latn, 332,940 speakers), Nzakara (Latn, 50,000 speakers), Mundani (Latn, 34,000 speakers), Gulay (Latn, 250,478 speakers), Makaa (Latn, 221,000 speakers), Vute (Latn, 21,000 speakers), Fur (Latn, 1,230,163 speakers), Mango (Latn, 77,000 speakers), Teke-Ebo (Latn, 260,000 speakers), Zapotec (Latn, 490,000 speakers), Heiltsuk (Latn, 300 speakers), Ebira (Latn, 2,200,000 speakers), Dii (Latn, 71,000 speakers), Aghem (Latn, 38,843 speakers), Igbo (Latn, 27,823,640 speakers), Koonzime (Latn, 40,000 speakers), Cicipu (Latn, 44,000 speakers), Ma’di (Latn, 584,000 speakers), Avokaya (Latn, 100,000 speakers), Ekpeye (Latn, 226,000 speakers), Belarusian (Cyrl, 10,064,517 speakers), Ukrainian (Cyrl, 29,273,587 speakers), Nateni (Latn, 100,000 speakers), Dan (Latn, 1,099,244 speakers), Bete-Bendi (Latn, 100,000 speakers), Kom (Latn, 360,685 speakers), Ijo, Southeast (Latn, 2,471,000 speakers), Yala (Latn, 200,000 speakers), South Central Banda (Latn, 244,000 speakers), Lugbara (Latn, 2,200,000 speakers), Bafut (Latn, 158,146 speakers), Kpelle, Guinea (Latn, 622,000 speakers), Southern Kisi (Latn, 360,000 speakers), Mfumte (Latn, 79,000 speakers), Sar (Latn, 500,000 speakers).</p>
 [code: soft-dotted]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Check the direction of the outermost contour in each glyph <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/outline.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>The following glyphs have a counter-clockwise outer contour:</p>
<pre><code>* bracketleft (U+005B) has a counter-clockwise outer contour

* bracketright (U+005D) has a counter-clockwise outer contour

* exclam (U+0021) has a counter-clockwise outer contour

* exclamdown (U+00A1) has a counter-clockwise outer contour

* guillemotleft (U+00AB) has a counter-clockwise outer contour

* guillemotleft (U+00AB) has a counter-clockwise outer contour

* guillemotright (U+00BB) has a counter-clockwise outer contour

* guillemotright (U+00BB) has a counter-clockwise outer contour

* guilsinglleft (U+2039) has a counter-clockwise outer contour

* guilsinglright (U+203A) has a counter-clockwise outer contour

* uniFF01 (U+FF01) has a counter-clockwise outer contour

* uniFF3B (U+FF3B) has a counter-clockwise outer contour

* uniFF3D (U+FF3D) has a counter-clockwise outer contour
</code></pre>
 [code: ccw-outer-contour]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Is there kerning info for non-ligated sequences? <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.gpos.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>GPOS table lacks kerning info for the following non-ligated sequences:</p>
<pre><code>- f + i

- f + l
</code></pre>
 [code: lacks-kern-info]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Are there caret positions declared for every ligature? <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.gdef.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>This font lacks caret position values for ligature glyphs on its GDEF table.</p>
 [code: lacks-caret-pos]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Ensure variable fonts include an avar table. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.varfont.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>This variable font does not have an avar table.</p>
 [code: missing-avar]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.meta.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>This font file does not have a 'meta' table.</p>
 [code: lacks-meta-table]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Checking OS/2 achVendID. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.os2.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>OS/2 VendorID value 'NONE' is not yet recognized. If you registered it recently, then it's safe to ignore this warning message. Otherwise, you should set it to your own unique 4 character code, and register it with Microsoft at <a href="https://www.microsoft.com/typography/links/vendorlist.aspx">https://www.microsoft.com/typography/links/vendorlist.aspx</a></p>
 [code: unknown]



</div>
</details>
</div>
</details>

<details><summary>[10] EpundaSans[wght].ttf</summary>
<div>
<details>
    <summary>⚠️ <b>WARN</b> Check accent of Lcaron, dcaron, lcaron, tcaron <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#"></a></summary>
    <div>









* ⚠️ **WARN** <p>dcaron is decomposed and therefore could not be checked. Please check manually.</p>
 [code: decomposed-outline]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Does the font contain a soft hyphen? <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.glyphset.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>This font has a 'Soft Hyphen' character.</p>
 [code: softhyphen]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Validate size, and resolution of article images, and ensure article page has minimum length and includes visual assets. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.article.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>Family metadata at fonts/variable does not have an article.</p>
 [code: lacks-article]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Check for codepoints not covered by METADATA subsets. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.subsets.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>The following codepoints supported by the font are not covered by
any subsets defined in the font's metadata file, and will never
be served. You can solve this by either manually adding additional
subset declarations to METADATA.pb, or by editing the glyphset
definitions.</p>
<ul>
<li>U+02D8 BREVE: try adding one of: yi, canadian-aboriginal</li>
<li>U+02D9 DOT ABOVE: try adding one of: yi, canadian-aboriginal</li>
<li>U+02DB OGONEK: try adding one of: yi, canadian-aboriginal</li>
<li>U+0302 COMBINING CIRCUMFLEX ACCENT: try adding one of: tifinagh, math, cherokee, coptic</li>
<li>U+0306 COMBINING BREVE: try adding one of: tifinagh, old-permic</li>
<li>U+0307 COMBINING DOT ABOVE: try adding one of: duployan, syriac, todhri, malayalam, tai-le, tifinagh, hebrew, coptic, old-permic, math, canadian-aboriginal</li>
<li>U+030A COMBINING RING ABOVE: try adding one of: duployan, syriac</li>
<li>U+030B COMBINING DOUBLE ACUTE ACCENT: try adding one of: cherokee, osage</li>
<li>U+030C COMBINING CARON: try adding one of: cherokee, tai-le</li>
<li>U+0312 COMBINING TURNED COMMA ABOVE: try adding math</li>
<li>U+0326 COMBINING COMMA BELOW: try adding math</li>
<li>U+0327 COMBINING CEDILLA: try adding math</li>
<li>U+0328 COMBINING OGONEK: not included in any glyphset definition</li>
<li>U+032D COMBINING CIRCUMFLEX ACCENT BELOW: try adding one of: syriac, sunuwar</li>
<li>U+0331 COMBINING MACRON BELOW: try adding one of: syriac, sunuwar, gothic, caucasian-albanian, cherokee, tifinagh, thai</li>
<li>U+0335 COMBINING SHORT STROKE OVERLAY: not included in any glyphset definition</li>
<li>U+03A9 GREEK CAPITAL LETTER OMEGA: try adding one of: elbasan, math, greek</li>
<li>U+03C0 GREEK SMALL LETTER PI: try adding one of: yi, math, greek</li>
<li>U+1EA0 LATIN CAPITAL LETTER A WITH DOT BELOW: try adding vietnamese</li>
<li>U+1EA1 LATIN SMALL LETTER A WITH DOT BELOW: try adding vietnamese</li>
<li>U+1EAC LATIN CAPITAL LETTER A WITH CIRCUMFLEX AND DOT BELOW: try adding vietnamese</li>
<li>U+1EAD LATIN SMALL LETTER A WITH CIRCUMFLEX AND DOT BELOW: try adding vietnamese</li>
<li>U+1EB8 LATIN CAPITAL LETTER E WITH DOT BELOW: try adding vietnamese</li>
<li>U+1EB9 LATIN SMALL LETTER E WITH DOT BELOW: try adding vietnamese</li>
<li>U+1EBC LATIN CAPITAL LETTER E WITH TILDE: try adding vietnamese</li>
<li>U+1EBD LATIN SMALL LETTER E WITH TILDE: try adding vietnamese</li>
<li>U+1EC6 LATIN CAPITAL LETTER E WITH CIRCUMFLEX AND DOT BELOW: try adding vietnamese</li>
<li>U+1EC7 LATIN SMALL LETTER E WITH CIRCUMFLEX AND DOT BELOW: try adding vietnamese</li>
<li>U+1ECA LATIN CAPITAL LETTER I WITH DOT BELOW: try adding vietnamese</li>
<li>U+1ECB LATIN SMALL LETTER I WITH DOT BELOW: try adding vietnamese</li>
<li>U+1ECC LATIN CAPITAL LETTER O WITH DOT BELOW: try adding vietnamese</li>
<li>U+1ECD LATIN SMALL LETTER O WITH DOT BELOW: try adding vietnamese</li>
<li>U+1ED8 LATIN CAPITAL LETTER O WITH CIRCUMFLEX AND DOT BELOW: try adding vietnamese</li>
<li>U+1ED9 LATIN SMALL LETTER O WITH CIRCUMFLEX AND DOT BELOW: try adding vietnamese</li>
<li>U+1EE4 LATIN CAPITAL LETTER U WITH DOT BELOW: try adding vietnamese</li>
<li>U+1EE5 LATIN SMALL LETTER U WITH DOT BELOW: try adding vietnamese</li>
<li>U+2000 EN QUAD: try adding symbols2</li>
<li>U+2001 EM QUAD: try adding symbols2</li>
<li>U+2003 EM SPACE: try adding nushu</li>
<li>U+2004 THREE-PER-EM SPACE: try adding symbols2</li>
<li>U+2005 FOUR-PER-EM SPACE: try adding symbols2</li>
<li>U+2006 SIX-PER-EM SPACE: try adding symbols2</li>
<li>U+2007 FIGURE SPACE: try adding symbols2</li>
<li>U+2008 PUNCTUATION SPACE: try adding symbols2</li>
<li>U+200A HAIR SPACE: try adding symbols2</li>
<li>U+200C ZERO WIDTH NON-JOINER: try adding one of: pahawh-hmong, saurashtra, tagalog, arabic, zanabazar-square, tirhuta, sundanese, takri, grantha, warang-citi, yi, gunjala-gondi, thaana, modi, mongolian, cham, psalter-pahlavi, bengali, kayah-li, meetei-mayek, lao, kharoshthi, hatran, newa, rejang, dogra, sogdian, thai, bhaiksuki, masaram-gondi, new-tai-lue, buhid, duployan, kannada, lepcha, batak, nko, limbu, khudawadi, balinese, sharada, malayalam, syriac, mandaic, tai-viet, javanese, devanagari, hanunoo, mahajani, gurmukhi, sinhala, brahmi, khmer, syloti-nagri, tamil, myanmar, buginese, hanifi-rohingya, tagbanwa, telugu, phags-pa, avestan, manichaean, oriya, chakma, hebrew, tai-tham, tibetan, tifinagh, gujarati, tai-le, kaithi, siddham, khojki</li>
<li>U+200D ZERO WIDTH JOINER: try adding one of: pahawh-hmong, saurashtra, tagalog, arabic, zanabazar-square, tirhuta, sundanese, takri, grantha, warang-citi, yi, gunjala-gondi, thaana, modi, mongolian, cham, psalter-pahlavi, bengali, kayah-li, meetei-mayek, old-hungarian, lao, kharoshthi, newa, rejang, dogra, sogdian, thai, bhaiksuki, masaram-gondi, new-tai-lue, buhid, duployan, kannada, lepcha, batak, nko, limbu, khudawadi, balinese, sharada, malayalam, syriac, mandaic, tai-viet, javanese, devanagari, hanunoo, mahajani, gurmukhi, sinhala, brahmi, khmer, syloti-nagri, tamil, myanmar, buginese, hanifi-rohingya, tagbanwa, telugu, phags-pa, avestan, manichaean, oriya, chakma, hebrew, tai-tham, tibetan, tifinagh, gujarati, tai-le, kaithi, siddham, khojki</li>
<li>U+200E LEFT-TO-RIGHT MARK: try adding one of: syriac, nko, arabic, phags-pa, hebrew, thaana</li>
<li>U+200F RIGHT-TO-LEFT MARK: try adding one of: syriac, nko, phags-pa, hebrew, thaana</li>
<li>U+2021 DOUBLE DAGGER: try adding adlam</li>
<li>U+202F NARROW NO-BREAK SPACE: try adding one of: yi, phags-pa, mongolian</li>
<li>U+2030 PER MILLE SIGN: try adding adlam</li>
<li>U+205F MEDIUM MATHEMATICAL SPACE: try adding math</li>
<li>U+2070 SUPERSCRIPT ZERO: try adding math</li>
<li>U+2074 SUPERSCRIPT FOUR: try adding math</li>
<li>U+2075 SUPERSCRIPT FIVE: try adding math</li>
<li>U+2076 SUPERSCRIPT SIX: try adding math</li>
<li>U+2077 SUPERSCRIPT SEVEN: try adding math</li>
<li>U+2078 SUPERSCRIPT EIGHT: try adding math</li>
<li>U+2079 SUPERSCRIPT NINE: try adding math</li>
<li>U+2080 SUBSCRIPT ZERO: try adding math</li>
<li>U+2081 SUBSCRIPT ONE: try adding math</li>
<li>U+2082 SUBSCRIPT TWO: try adding math</li>
<li>U+2083 SUBSCRIPT THREE: try adding math</li>
<li>U+2084 SUBSCRIPT FOUR: try adding math</li>
<li>U+2085 SUBSCRIPT FIVE: try adding math</li>
<li>U+2086 SUBSCRIPT SIX: try adding math</li>
<li>U+2087 SUBSCRIPT SEVEN: try adding math</li>
<li>U+2088 SUBSCRIPT EIGHT: try adding math</li>
<li>U+2089 SUBSCRIPT NINE: try adding math</li>
<li>U+215B VULGAR FRACTION ONE EIGHTH: try adding symbols</li>
<li>U+215C VULGAR FRACTION THREE EIGHTHS: try adding symbols</li>
<li>U+215D VULGAR FRACTION FIVE EIGHTHS: try adding symbols</li>
<li>U+215E VULGAR FRACTION SEVEN EIGHTHS: try adding symbols</li>
<li>U+2190 LEFTWARDS ARROW: try adding one of: symbols, math</li>
<li>U+2192 RIGHTWARDS ARROW: try adding one of: symbols, math</li>
<li>U+2194 LEFT RIGHT ARROW: try adding one of: symbols, math</li>
<li>U+2195 UP DOWN ARROW: try adding one of: symbols, math</li>
<li>U+2196 NORTH WEST ARROW: try adding one of: symbols, math</li>
<li>U+2197 NORTH EAST ARROW: try adding one of: symbols, math</li>
<li>U+2198 SOUTH EAST ARROW: try adding one of: symbols, math</li>
<li>U+2199 SOUTH WEST ARROW: try adding one of: symbols, math</li>
<li>U+2202 PARTIAL DIFFERENTIAL: try adding math</li>
<li>U+2206 INCREMENT: try adding math</li>
<li>U+220F N-ARY PRODUCT: try adding math</li>
<li>U+2211 N-ARY SUMMATION: try adding math</li>
<li>U+2219 BULLET OPERATOR: try adding one of: tai-tham, yi, symbols, math</li>
<li>U+221A SQUARE ROOT: try adding math</li>
<li>U+221E INFINITY: try adding math</li>
<li>U+222B INTEGRAL: try adding math</li>
<li>U+2248 ALMOST EQUAL TO: try adding math</li>
<li>U+2260 NOT EQUAL TO: try adding math</li>
<li>U+2264 LESS-THAN OR EQUAL TO: try adding math</li>
<li>U+2265 GREATER-THAN OR EQUAL TO: try adding math</li>
<li>U+25CA LOZENGE: try adding one of: symbols, math</li>
<li>U+25CC DOTTED CIRCLE: try adding one of: pahawh-hmong, yi, mende-kikakui, miao, thaana, cham, psalter-pahlavi, newa, coptic, soyombo, thai, siddham, new-tai-lue, kannada, duployan, sharada, balinese, javanese, brahmi, buginese, caucasian-albanian, hebrew, elbasan, kaithi, saurashtra, zanabazar-square, mongolian, bengali, kayah-li, sogdian, buhid, syriac, limbu, malayalam, canadian-aboriginal, syloti-nagri, hanunoo, sinhala, music, hanifi-rohingya, phags-pa, tibetan, manichaean, tifinagh, tai-le, telugu, tirhuta, grantha, gunjala-gondi, modi, lao, kharoshthi, rejang, ahom, bhaiksuki, masaram-gondi, wancho, batak, khudawadi, mandaic, armenian, gurmukhi, tamil, myanmar, oriya, gujarati, takri, sundanese, marchen, tagalog, warang-citi, meetei-mayek, adlam, dogra, math, bassa-vah, lepcha, tai-tham, nko, tai-viet, mahajani, devanagari, khmer, old-permic, symbols, tagbanwa, chakma, osage, khojki</li>
<li>U+3000 IDEOGRAPHIC SPACE: try adding one of: phags-pa, yi, chinese-simplified, nushu, chinese-traditional, chinese-hongkong, japanese</li>
<li>U+FB01 LATIN SMALL LIGATURE FI: not included in any glyphset definition</li>
<li>U+FB02 LATIN SMALL LIGATURE FL: not included in any glyphset definition</li>
<li>U+FF01 FULLWIDTH EXCLAMATION MARK: try adding one of: yi, chinese-simplified, japanese</li>
<li>U+FF02 FULLWIDTH QUOTATION MARK: try adding one of: yi, chinese-simplified, japanese</li>
<li>U+FF03 FULLWIDTH NUMBER SIGN: try adding one of: chinese-simplified, japanese</li>
<li>U+FF05 FULLWIDTH PERCENT SIGN: try adding one of: chinese-simplified, japanese</li>
<li>U+FF06 FULLWIDTH AMPERSAND: try adding one of: chinese-simplified, japanese</li>
<li>U+FF07 FULLWIDTH APOSTROPHE: try adding one of: chinese-simplified, japanese</li>
<li>U+FF08 FULLWIDTH LEFT PARENTHESIS: try adding one of: yi, chinese-simplified, japanese</li>
<li>U+FF09 FULLWIDTH RIGHT PARENTHESIS: try adding one of: yi, chinese-simplified, japanese</li>
<li>U+FF0A FULLWIDTH ASTERISK: try adding one of: chinese-simplified, japanese</li>
<li>U+FF0C FULLWIDTH COMMA: try adding one of: yi, chinese-simplified, japanese</li>
<li>U+FF0D FULLWIDTH HYPHEN-MINUS: try adding one of: chinese-simplified, japanese</li>
<li>U+FF0E FULLWIDTH FULL STOP: try adding one of: yi, chinese-simplified, japanese</li>
<li>U+FF0F FULLWIDTH SOLIDUS: try adding one of: yi, chinese-simplified, japanese</li>
<li>U+FF1A FULLWIDTH COLON: try adding one of: yi, chinese-simplified, japanese</li>
<li>U+FF1B FULLWIDTH SEMICOLON: try adding one of: yi, chinese-simplified, japanese</li>
<li>U+FF1F FULLWIDTH QUESTION MARK: try adding one of: yi, chinese-simplified, japanese</li>
<li>U+FF20 FULLWIDTH COMMERCIAL AT: try adding one of: chinese-simplified, japanese</li>
<li>U+FF3B FULLWIDTH LEFT SQUARE BRACKET: try adding one of: yi, chinese-simplified, japanese</li>
<li>U+FF3C FULLWIDTH REVERSE SOLIDUS: try adding one of: chinese-simplified, japanese</li>
<li>U+FF3D FULLWIDTH RIGHT SQUARE BRACKET: try adding one of: yi, chinese-simplified, japanese</li>
<li>U+FF3F FULLWIDTH LOW LINE: try adding one of: chinese-simplified, japanese</li>
<li>U+FF5B FULLWIDTH LEFT CURLY BRACKET: try adding one of: yi, chinese-simplified, math, japanese</li>
<li>U+FF5D FULLWIDTH RIGHT CURLY BRACKET: try adding one of: yi, chinese-simplified, math, japanese</li>
</ul>
<p>Or you can add the above codepoints to one of the subsets supported by the font: <code>cyrillic-ext</code>, <code>latin</code>, <code>latin-ext</code></p>
 [code: unreachable-subsetting]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Ensure soft_dotted characters lose their dot when combined with marks that replace the dot. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/shaping.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>The dot of soft dotted characters used in orthographies <em>must</em> disappear in the following strings: į̀ į́ į̂ į̃ į̄ į̌ ị̀ ị́ ị̂ ị̃ ị̄</p>
<p>The dot of soft dotted characters <em>should</em> disappear in other cases, for example: į̆ į̇ į̈ į̊ į̋ į̒ į̣̀ į̣́ į̣̂ į̣̃ į̣̄ į̣̆ į̣̇ į̣̈ į̣̊ į̣̋ į̣̌ į̣̒ į̦̀ į̦́</p>
<p>Your font fully covers the following languages that require the soft-dotted feature: Lithuanian (Latn, 2,357,094 speakers), Han (Latn, 6 speakers), Navajo (Latn, 166,319 speakers), Dutch (Latn, 31,709,104 speakers), Kaska (Latn, 125 speakers).</p>
<p>Your font does <em>not</em> cover the following languages that require the soft-dotted feature: Ejagham (Latn, 120,000 speakers), Ngbaka (Latn, 1,020,000 speakers), Basaa (Latn, 332,940 speakers), Nzakara (Latn, 50,000 speakers), Mundani (Latn, 34,000 speakers), Gulay (Latn, 250,478 speakers), Makaa (Latn, 221,000 speakers), Vute (Latn, 21,000 speakers), Fur (Latn, 1,230,163 speakers), Mango (Latn, 77,000 speakers), Teke-Ebo (Latn, 260,000 speakers), Zapotec (Latn, 490,000 speakers), Heiltsuk (Latn, 300 speakers), Ebira (Latn, 2,200,000 speakers), Dii (Latn, 71,000 speakers), Aghem (Latn, 38,843 speakers), Igbo (Latn, 27,823,640 speakers), Koonzime (Latn, 40,000 speakers), Cicipu (Latn, 44,000 speakers), Ma’di (Latn, 584,000 speakers), Avokaya (Latn, 100,000 speakers), Ekpeye (Latn, 226,000 speakers), Belarusian (Cyrl, 10,064,517 speakers), Ukrainian (Cyrl, 29,273,587 speakers), Nateni (Latn, 100,000 speakers), Dan (Latn, 1,099,244 speakers), Bete-Bendi (Latn, 100,000 speakers), Kom (Latn, 360,685 speakers), Ijo, Southeast (Latn, 2,471,000 speakers), Yala (Latn, 200,000 speakers), South Central Banda (Latn, 244,000 speakers), Lugbara (Latn, 2,200,000 speakers), Bafut (Latn, 158,146 speakers), Kpelle, Guinea (Latn, 622,000 speakers), Southern Kisi (Latn, 360,000 speakers), Mfumte (Latn, 79,000 speakers), Sar (Latn, 500,000 speakers).</p>
 [code: soft-dotted]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Is there kerning info for non-ligated sequences? <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.gpos.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>GPOS table lacks kerning info for the following non-ligated sequences:</p>
<pre><code>- f + i

- f + l
</code></pre>
 [code: lacks-kern-info]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Are there caret positions declared for every ligature? <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.gdef.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>This font lacks caret position values for ligature glyphs on its GDEF table.</p>
 [code: lacks-caret-pos]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Ensure variable fonts include an avar table. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.varfont.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>This variable font does not have an avar table.</p>
 [code: missing-avar]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.meta.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>This font file does not have a 'meta' table.</p>
 [code: lacks-meta-table]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Checking OS/2 achVendID. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.os2.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>OS/2 VendorID value 'NONE' is not yet recognized. If you registered it recently, then it's safe to ignore this warning message. Otherwise, you should set it to your own unique 4 character code, and register it with Microsoft at <a href="https://www.microsoft.com/typography/links/vendorlist.aspx">https://www.microsoft.com/typography/links/vendorlist.aspx</a></p>
 [code: unknown]



</div>
</details>
</div>
</details>




### Summary

| 💥 ERROR | ☠ FATAL | 🔥 FAIL | ⚠️ WARN | ⏩ SKIP | ℹ️ INFO | ✅ PASS | 🔎 DEBUG | 
| ---|---|---|---|---|---|---|---|
| 0 | 0 | 4 | 22 | 183 | 15 | 260 | 0 | 
| 0% | 0% | 1% | 5% | 38% | 3% | 54% | 0% | 



**Note:** The following loglevels were omitted in this report:


* SKIP
* INFO
* PASS
* DEBUG
