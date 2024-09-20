## FontBakery report

fontbakery version: 0.12.10





## Check results



<details><summary>[21] Parkinsans[wght].ttf</summary>
<div>
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
<td align="left">U+018F: LATIN CAPITAL LETTER SCHWA</td>
<td align="left">U+0259: LATIN SMALL LETTER SCHWA</td>
</tr>
</tbody>
</table>
 [code: missing-case-counterparts]



</div>
</details>

<details>
    <summary>🔥 <b>FAIL</b> Checking Vertical Metric Linegaps. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.metrics.html#"></a></summary>
    <div>







* 🔥 **FAIL** <p>OS/2 sTypoLineGap is not equal to 0.</p>
<p><em>Overridden</em>: This check was originally a WARN but was
overridden by the universal profile:
For Google Fonts, all messages from this check are considered FAILs.</p>
 [code: OS/2]



</div>
</details>

<details>
    <summary>🔥 <b>FAIL</b> Name table records must not have trailing spaces. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#"></a></summary>
    <div>







* 🔥 **FAIL** <p>Name table record with key = (3, 1, 1033, 9) has trailing spaces that must be removed: 'Typeface d[...]sign LTD. '</p>
 [code: trailing-space]



</div>
</details>

<details>
    <summary>🔥 <b>FAIL</b> Checking OS/2 Metrics match hhea Metrics. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.metrics.html#"></a></summary>
    <div>







* 🔥 **FAIL** <p>OS/2 sTypoLineGap (100) and hhea lineGap (0) must be equal.</p>
 [code: lineGap]



</div>
</details>

<details>
    <summary>🔥 <b>FAIL</b> Font contains glyphs for whitespace characters? <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.glyphset.html#"></a></summary>
    <div>







* 🔥 **FAIL** <p>Whitespace glyph missing for codepoint 0x00A0.</p>
 [code: missing-whitespace-glyph-0x00A0]



</div>
</details>

<details>
    <summary>🔥 <b>FAIL</b> Shapes languages in all GF glyphsets. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.glyphset.html#"></a></summary>
    <div>







* 🔥 **FAIL** <p>GF_Latin_Core glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">FAIL messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">ca_Latn (Catalan)</td>
<td align="left">Some mark glyphs were missing: ◌̀, ◌́, ◌̈, ◌̧</td>
</tr>
</tbody>
</table>
 [code: failed-language-shaping]



* 🔥 **FAIL** <p>GF_Latin_Core glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">FAIL messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">cs_Latn (Czech)</td>
<td align="left">Some mark glyphs were missing: ◌́, ◌̊, ◌̌</td>
</tr>
</tbody>
</table>
 [code: failed-language-shaping]



* 🔥 **FAIL** <p>GF_Latin_Core glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">FAIL messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">cy_Latn (Welsh)</td>
<td align="left">Some mark glyphs were missing: ◌̀, ◌́, ◌̂, ◌̈</td>
</tr>
</tbody>
</table>
 [code: failed-language-shaping]



* 🔥 **FAIL** <p>GF_Latin_Core glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">FAIL messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">da_Latn (Danish)</td>
<td align="left">Some mark glyphs were missing: ◌́, ◌̊</td>
</tr>
</tbody>
</table>
 [code: failed-language-shaping]



* 🔥 **FAIL** <p>GF_Latin_Core glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">FAIL messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">de_Latn (German)</td>
<td align="left">Some base glyphs were missing: ẞ</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Some mark glyphs were missing: ◌̀, ◌́, ◌̈</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper produced a .notdef</td>
</tr>
</tbody>
</table>
 [code: failed-language-shaping]



* 🔥 **FAIL** <p>GF_Latin_Core glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">FAIL messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">en_Latn (English)</td>
<td align="left">Some mark glyphs were missing: ◌̀, ◌́, ◌̂, ◌̃, ◌̈, ◌̧</td>
</tr>
</tbody>
</table>
 [code: failed-language-shaping]



* 🔥 **FAIL** <p>GF_Latin_Core glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">FAIL messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">es_Latn (Spanish)</td>
<td align="left">Some mark glyphs were missing: ◌́, ◌̃, ◌̈</td>
</tr>
</tbody>
</table>
 [code: failed-language-shaping]



* 🔥 **FAIL** <p>GF_Latin_Core glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">FAIL messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">fi_Latn (Finnish)</td>
<td align="left">Some mark glyphs were missing: ◌̃, ◌̈, ◌̊, ◌̌</td>
</tr>
</tbody>
</table>
 [code: failed-language-shaping]



* 🔥 **FAIL** <p>GF_Latin_Core glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">FAIL messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">fr_Latn (French)</td>
<td align="left">Some mark glyphs were missing: ◌̀, ◌́, ◌̂, ◌̈, ◌̧</td>
</tr>
</tbody>
</table>
 [code: failed-language-shaping]



* 🔥 **FAIL** <p>GF_Latin_Core glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">FAIL messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">hr_Latn (Croatian)</td>
<td align="left">Some mark glyphs were missing: ◌́, ◌̌</td>
</tr>
</tbody>
</table>
 [code: failed-language-shaping]



* 🔥 **FAIL** <p>GF_Latin_Core glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">FAIL messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">hu_Latn (Hungarian)</td>
<td align="left">Some mark glyphs were missing: ◌́, ◌̈, ◌̋</td>
</tr>
</tbody>
</table>
 [code: failed-language-shaping]



* 🔥 **FAIL** <p>GF_Latin_Core glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">FAIL messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">is_Latn (Icelandic)</td>
<td align="left">Some mark glyphs were missing: ◌́, ◌̈, ◌̨</td>
</tr>
</tbody>
</table>
 [code: failed-language-shaping]



* 🔥 **FAIL** <p>GF_Latin_Core glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">FAIL messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">it_Latn (Italian)</td>
<td align="left">Some mark glyphs were missing: ◌̀, ◌́, ◌̂, ◌̈</td>
</tr>
</tbody>
</table>
 [code: failed-language-shaping]



* 🔥 **FAIL** <p>GF_Latin_Core glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">FAIL messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">lt_Latn (Lithuanian)</td>
<td align="left">Some mark glyphs were missing: ◌̄, ◌̇, ◌̌, ◌̨</td>
</tr>
</tbody>
</table>
 [code: failed-language-shaping]



* 🔥 **FAIL** <p>GF_Latin_Core glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">FAIL messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">lv_Latn (Latvian)</td>
<td align="left">Some mark glyphs were missing: ◌̄, ◌̌, ◌̧</td>
</tr>
</tbody>
</table>
 [code: failed-language-shaping]



* 🔥 **FAIL** <p>GF_Latin_Core glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">FAIL messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">mt_Latn (Maltese)</td>
<td align="left">Some base glyphs were missing: GĦ, għ, Ħ, ħ</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Some mark glyphs were missing: ◌̀, ◌̂, ◌̇</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper produced a .notdef</td>
</tr>
</tbody>
</table>
 [code: failed-language-shaping]



* 🔥 **FAIL** <p>GF_Latin_Core glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">FAIL messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">nb_Latn (Norwegian Bokmål)</td>
<td align="left">Some mark glyphs were missing: ◌̀, ◌́, ◌̂, ◌̈, ◌̊</td>
</tr>
</tbody>
</table>
 [code: failed-language-shaping]



* 🔥 **FAIL** <p>GF_Latin_Core glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">FAIL messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">nl_Latn (Dutch)</td>
<td align="left">Some base glyphs were missing: ÍJ́, íj́</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Some mark glyphs were missing: ◌̀, ◌́, ◌̂, ◌̈</td>
</tr>
<tr>
<td align="left">^</td>
<td align="left">Shaper produced a .notdef</td>
</tr>
</tbody>
</table>
 [code: failed-language-shaping]



* 🔥 **FAIL** <p>GF_Latin_Core glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">FAIL messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">pl_Latn (Polish)</td>
<td align="left">Some mark glyphs were missing: ◌́, ◌̇, ◌̨</td>
</tr>
</tbody>
</table>
 [code: failed-language-shaping]



* 🔥 **FAIL** <p>GF_Latin_Core glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">FAIL messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">pt_Latn (Portuguese)</td>
<td align="left">Some mark glyphs were missing: ◌̀, ◌́, ◌̂, ◌̃, ◌̈, ◌̧</td>
</tr>
</tbody>
</table>
 [code: failed-language-shaping]



* 🔥 **FAIL** <p>GF_Latin_Core glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">FAIL messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">ro_Latn (Romanian)</td>
<td align="left">Some mark glyphs were missing: ◌̂, ◌̆, ◌̦, ◌̧</td>
</tr>
</tbody>
</table>
 [code: failed-language-shaping]



* 🔥 **FAIL** <p>GF_Latin_Core glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">FAIL messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">sk_Latn (Slovak)</td>
<td align="left">Some mark glyphs were missing: ◌́, ◌̂, ◌̈, ◌̌</td>
</tr>
</tbody>
</table>
 [code: failed-language-shaping]



* 🔥 **FAIL** <p>GF_Latin_Core glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">FAIL messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">sq_Latn (Albanian)</td>
<td align="left">Some mark glyphs were missing: ◌̈, ◌̧</td>
</tr>
</tbody>
</table>
 [code: failed-language-shaping]



* 🔥 **FAIL** <p>GF_Latin_Core glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">FAIL messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">sv_Latn (Swedish)</td>
<td align="left">Some mark glyphs were missing: ◌̀, ◌́, ◌̈, ◌̊</td>
</tr>
</tbody>
</table>
 [code: failed-language-shaping]



* 🔥 **FAIL** <p>GF_Latin_Core glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">FAIL messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">tr_Latn (Turkish)</td>
<td align="left">Some mark glyphs were missing: ◌̂, ◌̆, ◌̇, ◌̈, ◌̦, ◌̧</td>
</tr>
</tbody>
</table>
 [code: failed-language-shaping]



* ⚠️ **WARN** <p>GF_Latin_Core glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">WARN messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">de_Latn (German)</td>
<td align="left">Some auxiliary glyphs were missing: ẞ</td>
</tr>
</tbody>
</table>
 [code: warning-language-shaping]



* ⚠️ **WARN** <p>GF_Latin_Core glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">WARN messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">mt_Latn (Maltese)</td>
<td align="left">Some auxiliary glyphs were missing: GĦ, għ, Ħ, ħ</td>
</tr>
</tbody>
</table>
 [code: warning-language-shaping]



* ⚠️ **WARN** <p>GF_Latin_Core glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">WARN messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">nl_Latn (Dutch)</td>
<td align="left">Some auxiliary glyphs were missing: ÍJ́, íj́</td>
</tr>
</tbody>
</table>
 [code: warning-language-shaping]



</div>
</details>

<details>
    <summary>🔥 <b>FAIL</b> Check license file has good copyright string. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.license.html#"></a></summary>
    <div>







* 🔥 **FAIL** <p>First line in license file is:</p>
<p>&quot;copyright 20** the my font project authors (<a href="https://github.com/googlefonts/googlefonts-project-template">https://github.com/googlefonts/googlefonts-project-template</a>)&quot;</p>
<p>which does not match the expected format, similar to:</p>
<p>&quot;Copyright 2022 The Familyname Project Authors (git url)&quot;</p>
 [code: bad-format]



</div>
</details>

<details>
    <summary>🔥 <b>FAIL</b> Checking OS/2 fsType does not impose restrictions. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.os2.html#"></a></summary>
    <div>







* 🔥 **FAIL** <p>In this font fsType is set to 8 meaning that:
The font may be embedded but must only be installed temporarily on other systems.</p>
<p>No such DRM restrictions can be enabled on the Google Fonts collection, so the fsType field must be set to zero (Installable Embedding) instead.</p>
 [code: drm]



</div>
</details>

<details>
    <summary>🔥 <b>FAIL</b> Check Google Fonts glyph coverage. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.glyphset.html#"></a></summary>
    <div>







* 🔥 **FAIL** <p>Missing required codepoints:</p>
<pre><code>- 0x00A0 (NO-BREAK SPACE)


- 0x0126 (LATIN CAPITAL LETTER H WITH STROKE)


- 0x0127 (LATIN SMALL LETTER H WITH STROKE)


- 0x0237 (LATIN SMALL LETTER DOTLESS J)


- 0x0300 (COMBINING GRAVE ACCENT)


- 0x0301 (COMBINING ACUTE ACCENT)


- 0x0302 (COMBINING CIRCUMFLEX ACCENT)


- 0x0303 (COMBINING TILDE)


- 0x0304 (COMBINING MACRON)


- 0x0306 (COMBINING BREVE)


- 0x0307 (COMBINING DOT ABOVE)


- 0x0308 (COMBINING DIAERESIS)


- 0x030A (COMBINING RING ABOVE)


- 0x030B (COMBINING DOUBLE ACUTE ACCENT)


- 0x030C (COMBINING CARON)


- 0x0326 (COMBINING COMMA BELOW)


- 0x0327 (COMBINING CEDILLA)


- 0x0328 (COMBINING OGONEK)


- 0x1E9E (LATIN CAPITAL LETTER SHARP S)
</code></pre>
 [code: missing-codepoints]



</div>
</details>

<details>
    <summary>🔥 <b>FAIL</b> Check font follows the Google Fonts vertical metric schema <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.vmetrics.html#"></a></summary>
    <div>







* 🔥 **FAIL** <p>OS/2.sTypoLineGap is &quot;100&quot; it should be 0</p>
 [code: bad-OS/2.sTypoLineGap]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Does GPOS table have kerning information? This check skips monospaced fonts as defined by post.isFixedPitch value <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/opentype.gpos.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>GPOS table lacks kerning information.</p>
 [code: lacks-kern-info]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Check accent of Lcaron, dcaron, lcaron, tcaron <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#"></a></summary>
    <div>









* ⚠️ **WARN** <p>Lcaron is decomposed and therefore could not be checked. Please check manually.</p>
 [code: decomposed-outline]



* ⚠️ **WARN** <p>dcaron is decomposed and therefore could not be checked. Please check manually.</p>
 [code: decomposed-outline]



* ⚠️ **WARN** <p>lcaron is decomposed and therefore could not be checked. Please check manually.</p>
 [code: decomposed-outline]



* ⚠️ **WARN** <p>tcaron is decomposed and therefore could not be checked. Please check manually.</p>
 [code: decomposed-outline]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Detect any interpolation issues in the font. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>Interpolation issues were found in the font:</p>
<pre><code>- Contour 1 start point differs in glyph 'eogonek' between location wght=475 and location wght=800

- Contour 1 in glyph 'eogonek': becomes underweight between wght=475 and wght=800.

- Contour 1 point 14 in glyph 'eogonek' has a kink between location wght=475 and location wght=800
</code></pre>
 [code: interpolation-issues]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Check math signs have the same width. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>The most common width is 476 among a set of 2 math glyphs.
The following math glyphs have a different width, though:</p>
<p>Width = 655:
plus</p>
<p>Width = 504:
less</p>
<p>Width = 676:
equal</p>
<p>Width = 492:
greater</p>
<p>Width = 651:
logicalnot</p>
<p>Width = 657:
plusminus</p>
<p>Width = 591:
multiply</p>
<p>Width = 637:
divide</p>
<p>Width = 519:
minus</p>
<p>Width = 487:
approxequal</p>
<p>Width = 664:
notequal</p>
 [code: width-outliers]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Check font contains no unreachable glyphs <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.glyphset.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>The following glyphs could not be reached by codepoint or substitution rules:</p>
<pre><code>- indianrupee

- turkishlira
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
<li>U+02C7 CARON: try adding one of: tifinagh, yi, canadian-aboriginal</li>
<li>U+02D8 BREVE: try adding one of: yi, canadian-aboriginal</li>
<li>U+02D9 DOT ABOVE: try adding one of: yi, canadian-aboriginal</li>
<li>U+02DB OGONEK: try adding one of: yi, canadian-aboriginal</li>
<li>U+02DD DOUBLE ACUTE ACCENT: not included in any glyphset definition</li>
<li>U+03C0 GREEK SMALL LETTER PI: try adding one of: yi, greek, math</li>
<li>U+1EBC LATIN CAPITAL LETTER E WITH TILDE: try adding vietnamese</li>
<li>U+1EBD LATIN SMALL LETTER E WITH TILDE: try adding vietnamese</li>
<li>U+2021 DOUBLE DAGGER: try adding adlam</li>
<li>U+2030 PER MILLE SIGN: try adding adlam</li>
<li>U+2126 OHM SIGN: not included in any glyphset definition</li>
<li>U+212E ESTIMATED SYMBOL: not included in any glyphset definition</li>
<li>U+2202 PARTIAL DIFFERENTIAL: try adding math</li>
<li>U+2206 INCREMENT: try adding math</li>
<li>U+220F N-ARY PRODUCT: try adding math</li>
<li>U+2211 N-ARY SUMMATION: try adding math</li>
<li>U+221A SQUARE ROOT: try adding math</li>
<li>U+221E INFINITY: try adding math</li>
<li>U+222B INTEGRAL: try adding math</li>
<li>U+2248 ALMOST EQUAL TO: try adding math</li>
<li>U+2260 NOT EQUAL TO: try adding math</li>
<li>U+2264 LESS-THAN OR EQUAL TO: try adding math</li>
<li>U+2265 GREATER-THAN OR EQUAL TO: try adding math</li>
<li>U+25CA LOZENGE: try adding one of: symbols, math</li>
<li>U+FB01 LATIN SMALL LIGATURE FI: not included in any glyphset definition</li>
<li>U+FB02 LATIN SMALL LIGATURE FL: not included in any glyphset definition</li>
</ul>
<p>Or you can add the above codepoints to one of the subsets supported by the font: <code>latin</code>, <code>latin-ext</code></p>
 [code: unreachable-subsetting]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Are there any misaligned on-curve points? <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/outline.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>The following glyphs have on-curve points which have potentially incorrect y coordinates:</p>
<pre><code>* Iogonek (U+012E): X=202.0,Y=1.0 (should be at baseline 0?)

* Lcaron (U+013D): X=273.5,Y=689.0 (should be at cap-height 690?)

* W (U+0057): X=220.0,Y=-1.0 (should be at baseline 0?)

* Wacute (U+1E82): X=220.0,Y=-1.0 (should be at baseline 0?)

* Wcircumflex (U+0174): X=220.0,Y=-1.0 (should be at baseline 0?)

* Wdieresis (U+1E84): X=220.0,Y=-1.0 (should be at baseline 0?)

* Wgrave (U+1E80): X=220.0,Y=-1.0 (should be at baseline 0?)

* acircumflex (U+00E2): X=338.0,Y=688.0 (should be at cap-height 690?)

* cdotaccent (U+010B): X=275.5,Y=691.5 (should be at cap-height 690?)

* cdotaccent (U+010B): X=340.5,Y=691.5 (should be at cap-height 690?)

* ecircumflex (U+00EA): X=318.0,Y=688.0 (should be at cap-height 690?)

* edotaccent (U+0117): X=285.5,Y=691.5 (should be at cap-height 690?)

* edotaccent (U+0117): X=350.5,Y=691.5 (should be at cap-height 690?)

* gdotaccent (U+0121): X=305.5,Y=691.5 (should be at cap-height 690?)

* gdotaccent (U+0121): X=370.5,Y=691.5 (should be at cap-height 690?)

* icircumflex (U+00EE): X=115.0,Y=688.0 (should be at cap-height 690?)

* iogonek (U+012F): X=155.0,Y=1.0 (should be at baseline 0?)

* obreve (U+014F): X=253.5,Y=688.0 (should be at cap-height 690?)

* obreve (U+014F): X=392.5,Y=688.0 (should be at cap-height 690?)

* germandbls (U+00DF): X=473.0,Y=688.0 (should be at cap-height 690?)

* t (U+0074): X=293.0,Y=0.5 (should be at baseline 0?)

* tcaron (U+0165): X=293.0,Y=0.5 (should be at baseline 0?)

* uni0163 (U+0163): X=293.0,Y=0.5 (should be at baseline 0?)

* uni021B (U+021B): X=293.0,Y=0.5 (should be at baseline 0?)

* ucircumflex (U+00FB): X=317.0,Y=688.0 (should be at cap-height 690?)

* uogonek (U+0173): X=553.0,Y=-1.0 (should be at baseline 0?)

* wcircumflex (U+0175): X=408.0,Y=688.0 (should be at cap-height 690?)

* ycircumflex (U+0177): X=288.0,Y=688.0 (should be at cap-height 690?)

* zdotaccent (U+017C): X=188.5,Y=691.5 (should be at cap-height 690?)

* zdotaccent (U+017C): X=253.5,Y=691.5 (should be at cap-height 690?)

* comma (U+002C): X=78.5,Y=-2.0 (should be at baseline 0?)

* semicolon (U+003B): X=111.5,Y=-2.0 (should be at baseline 0?)

* sterling (U+00A3): X=211.0,Y=691.5 (should be at cap-height 690?)

* sterling (U+00A3): X=437.5,Y=689.0 (should be at cap-height 690?)

* ampersand (U+0026): X=219.5,Y=691.0 (should be at cap-height 690?)

* ampersand (U+0026): X=399.0,Y=688.0 (should be at cap-height 690?)

* circumflex (U+02C6): X=158.0,Y=688.0 (should be at cap-height 690?)

* turkishlira: X=208.0,Y=-1.0 (should be at baseline 0?)
</code></pre>
 [code: found-misalignments]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Check the direction of the outermost contour in each glyph <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/outline.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>The following glyphs have a counter-clockwise outer contour:</p>
<pre><code>* turkishlira has a counter-clockwise outer contour

* turkishlira has a counter-clockwise outer contour

* turkishlira has a counter-clockwise outer contour
</code></pre>
 [code: ccw-outer-contour]



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
| 0 | 0 | 10 | 11 | 102 | 8 | 120 | 0 | 
| 0% | 0% | 4% | 4% | 41% | 3% | 48% | 0% | 



**Note:** The following loglevels were omitted in this report:


* SKIP
* INFO
* PASS
* DEBUG
