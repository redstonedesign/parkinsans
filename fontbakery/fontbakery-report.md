## FontBakery report

fontbakery version: 0.12.10





## Check results



<details><summary>[9] Parkinsans-SemiBold.ttf</summary>
<div>
<details>
    <summary>⚠️ <b>WARN</b> Check if each glyph has the recommended amount of contours. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.</p>
<p>The following glyphs do not have the recommended number of contours:</p>
<pre><code>- Glyph name: liter	Contours detected: 1	Expected: 2

- Glyph name: fi	Contours detected: 2	Expected: 3
</code></pre>
 [code: contour-count]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Validate size, and resolution of article images, and ensure article page has minimum length and includes visual assets. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.article.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>Family metadata at fonts/ttf does not have an article.</p>
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
<li>U+0302 COMBINING CIRCUMFLEX ACCENT: try adding one of: math, cherokee, tifinagh, coptic</li>
<li>U+0306 COMBINING BREVE: try adding one of: tifinagh, old-permic</li>
<li>U+0307 COMBINING DOT ABOVE: try adding one of: tai-le, old-permic, coptic, tifinagh, syriac, hebrew, canadian-aboriginal, todhri, malayalam, duployan, math</li>
<li>U+030A COMBINING RING ABOVE: try adding one of: duployan, syriac</li>
<li>U+030B COMBINING DOUBLE ACUTE ACCENT: try adding one of: osage, cherokee</li>
<li>U+030C COMBINING CARON: try adding one of: tai-le, cherokee</li>
<li>U+0326 COMBINING COMMA BELOW: try adding math</li>
<li>U+0327 COMBINING CEDILLA: try adding math</li>
<li>U+0328 COMBINING OGONEK: not included in any glyphset definition</li>
<li>U+03C0 GREEK SMALL LETTER PI: try adding one of: greek, yi, math</li>
<li>U+1EBC LATIN CAPITAL LETTER E WITH TILDE: try adding vietnamese</li>
<li>U+1EBD LATIN SMALL LETTER E WITH TILDE: try adding vietnamese</li>
<li>U+2021 DOUBLE DAGGER: try adding adlam</li>
<li>U+2030 PER MILLE SIGN: try adding adlam</li>
<li>U+2126 OHM SIGN: try adding math</li>
<li>U+212E ESTIMATED SYMBOL: try adding math</li>
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
<li>U+25CA LOZENGE: try adding one of: math, symbols</li>
<li>U+25CC DOTTED CIRCLE: try adding one of: sinhala, devanagari, saurashtra, duployan, hanifi-rohingya, kannada, tirhuta, soyombo, tai-le, chakma, psalter-pahlavi, sharada, limbu, balinese, cham, rejang, music, coptic, tagalog, tifinagh, elbasan, hebrew, kaithi, armenian, modi, marchen, kayah-li, thaana, lao, siddham, masaram-gondi, nko, warang-citi, syloti-nagri, telugu, new-tai-lue, lepcha, oriya, adlam, grantha, bhaiksuki, osage, buhid, yi, dogra, javanese, gurmukhi, symbols, mongolian, canadian-aboriginal, math, hanunoo, phags-pa, tibetan, thai, caucasian-albanian, gujarati, bassa-vah, takri, batak, zanabazar-square, pahawh-hmong, tai-viet, tagbanwa, tamil, khojki, miao, sogdian, old-permic, manichaean, khudawadi, mende-kikakui, mandaic, kharoshthi, brahmi, wancho, mahajani, ahom, syriac, meetei-mayek, gunjala-gondi, buginese, malayalam, tai-tham, bengali, sundanese, khmer, myanmar, newa</li>
<li>U+FB01 LATIN SMALL LIGATURE FI: not included in any glyphset definition</li>
<li>U+FB02 LATIN SMALL LIGATURE FL: not included in any glyphset definition</li>
</ul>
<p>Or you can add the above codepoints to one of the subsets supported by the font: <code>latin</code>, <code>latin-ext</code></p>
 [code: unreachable-subsetting]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Ensure soft_dotted characters lose their dot when combined with marks that replace the dot. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/shaping.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>The dot of soft dotted characters used in orthographies <em>must</em> disappear in the following strings: i̊ i̋ j̀ j́ j̃ j̄ j̈ į̀ į́ į̂ į̃ į̄ į̌</p>
<p>The dot of soft dotted characters <em>should</em> disappear in other cases, for example: i̇ ǐ i̦̇ i̦̊ i̦̋ ǐ̦ i̧̇ i̧̊ i̧̋ ǐ̧ ĵ j̆ j̇ j̊ j̋ ǰ j̦̀ j̦́ ĵ̦ j̦̃</p>
<p>Your font fully covers the following languages that require the soft-dotted feature: Lithuanian (Latn, 2,357,094 speakers), Dutch (Latn, 31,709,104 speakers).</p>
<p>Your font does <em>not</em> cover the following languages that require the soft-dotted feature: Dii (Latn, 71,000 speakers), Zapotec (Latn, 490,000 speakers), Mundani (Latn, 34,000 speakers), Igbo (Latn, 27,823,640 speakers), Belarusian (Cyrl, 10,064,517 speakers), Cicipu (Latn, 44,000 speakers), Gulay (Latn, 250,478 speakers), Sar (Latn, 500,000 speakers), Ejagham (Latn, 120,000 speakers), Ma’di (Latn, 584,000 speakers), Vute (Latn, 21,000 speakers), Dan (Latn, 1,099,244 speakers), Nateni (Latn, 100,000 speakers), Ijo, Southeast (Latn, 2,471,000 speakers), Ngbaka (Latn, 1,020,000 speakers), Heiltsuk (Latn, 300 speakers), Koonzime (Latn, 40,000 speakers), Lugbara (Latn, 2,200,000 speakers), Makaa (Latn, 221,000 speakers), Mango (Latn, 77,000 speakers), Navajo (Latn, 166,319 speakers), Han (Latn, 6 speakers), Kom (Latn, 360,685 speakers), Bete-Bendi (Latn, 100,000 speakers), Ekpeye (Latn, 226,000 speakers), Teke-Ebo (Latn, 260,000 speakers), Kaska (Latn, 125 speakers), Aghem (Latn, 38,843 speakers), Kpelle, Guinea (Latn, 622,000 speakers), South Central Banda (Latn, 244,000 speakers), Basaa (Latn, 332,940 speakers), Fur (Latn, 1,230,163 speakers), Ukrainian (Cyrl, 29,273,587 speakers), Avokaya (Latn, 100,000 speakers), Bafut (Latn, 158,146 speakers), Mfumte (Latn, 79,000 speakers), Nzakara (Latn, 50,000 speakers), Southern Kisi (Latn, 360,000 speakers), Ebira (Latn, 2,200,000 speakers), Yala (Latn, 200,000 speakers).</p>
 [code: soft-dotted]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Are there any misaligned on-curve points? <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/outline.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>The following glyphs have on-curve points which have potentially incorrect y coordinates:</p>
<pre><code>* Iogonek (U+012E): X=281.0,Y=1.0 (should be at baseline 0?)

* Q (U+0051): X=694.0,Y=2.0 (should be at baseline 0?)

* Uogonek (U+0172): X=423.0,Y=1.0 (should be at baseline 0?)

* Uogonek (U+0172): X=265.0,Y=2.0 (should be at baseline 0?)

* acircumflex (U+00E2): X=190.0,Y=696.0 (should be at cap-height 698?)

* acircumflex (U+00E2): X=487.0,Y=696.0 (should be at cap-height 698?)

* ecircumflex (U+00EA): X=165.0,Y=696.0 (should be at cap-height 698?)

* ecircumflex (U+00EA): X=462.0,Y=696.0 (should be at cap-height 698?)

* g (U+0067): X=468.0,Y=2.0 (should be at baseline 0?)

* gbreve (U+011F): X=468.0,Y=2.0 (should be at baseline 0?)

* uni0123 (U+0123): X=468.0,Y=2.0 (should be at baseline 0?)

* gdotaccent (U+0121): X=468.0,Y=2.0 (should be at baseline 0?)

* icircumflex (U+00EE): X=-3.0,Y=696.0 (should be at cap-height 698?)

* icircumflex (U+00EE): X=294.0,Y=696.0 (should be at cap-height 698?)

* ldot (U+0140): X=263.5,Y=-2.0 (should be at baseline 0?)

* lslash (U+0142): X=269.5,Y=-2.0 (should be at baseline 0?)

* otilde (U+00F5): X=392.0,Y=699.0 (should be at cap-height 698?)

* scaron (U+0161): X=272.0,Y=696.0 (should be at cap-height 698?)

* ucircumflex (U+00FB): X=182.0,Y=696.0 (should be at cap-height 698?)

* ucircumflex (U+00FB): X=479.0,Y=696.0 (should be at cap-height 698?)

* wcircumflex (U+0175): X=274.0,Y=696.0 (should be at cap-height 698?)

* wcircumflex (U+0175): X=571.0,Y=696.0 (should be at cap-height 698?)

* ycircumflex (U+0177): X=164.0,Y=696.0 (should be at cap-height 698?)

* ycircumflex (U+0177): X=461.0,Y=696.0 (should be at cap-height 698?)

* fi (U+FB01): X=136.0,Y=699.5 (should be at cap-height 698?)

* fl (U+FB02): X=113.5,Y=699.5 (should be at cap-height 698?)

* question (U+003F): X=150.5,Y=699.5 (should be at cap-height 698?)

* question (U+003F): X=379.5,Y=697.5 (should be at cap-height 698?)

* uni2206 (U+2206): X=300.0,Y=700.0 (should be at cap-height 698?)

* uni2206 (U+2206): X=415.0,Y=700.0 (should be at cap-height 698?)

* product (U+220F): X=26.0,Y=699.0 (should be at cap-height 698?)

* product (U+220F): X=718.0,Y=699.0 (should be at cap-height 698?)

* partialdiff (U+2202): X=449.5,Y=698.5 (should be at cap-height 698?)

* asciicircum (U+005E): X=272.0,Y=700.0 (should be at cap-height 698?)

* asciicircum (U+005E): X=409.0,Y=700.0 (should be at cap-height 698?)

* circumflex (U+02C6): X=10.0,Y=696.0 (should be at cap-height 698?)

* circumflex (U+02C6): X=307.0,Y=696.0 (should be at cap-height 698?)

* uni20B9 (U+20B9): X=42.0,Y=699.0 (should be at cap-height 698?)

* uni20B9 (U+20B9): X=579.0,Y=699.0 (should be at cap-height 698?)

* uni0302 (U+0302): X=10.0,Y=696.0 (should be at cap-height 698?)

* uni0302 (U+0302): X=307.0,Y=696.0 (should be at cap-height 698?)
</code></pre>
 [code: found-misalignments]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Are any segments inordinately short? <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/outline.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>The following glyphs have segments which seem very short:</p>
<pre><code>* germandbls (U+00DF) contains a short segment B&lt;&lt;435.0,392.0&gt;-&lt;435.0,382.0&gt;-&lt;442.5,373.0&gt;&gt;

* uni0163 (U+0163) contains a short segment B&lt;&lt;280.0,-8.0&gt;-&lt;274.0,-8.0&gt;-&lt;269.0,-7.0&gt;&gt;

* yen (U+00A5) contains a short segment L&lt;&lt;248.0,235.0&gt;--&lt;248.0,243.0&gt;&gt;

* yen (U+00A5) contains a short segment L&lt;&lt;390.0,243.0&gt;--&lt;390.0,235.0&gt;&gt;

* ampersand (U+0026) contains a short segment B&lt;&lt;514.0,261.0&gt;-&lt;517.0,265.0&gt;-&lt;519.0,270.0&gt;&gt;

* uni1E9E (U+1E9E) contains a short segment B&lt;&lt;435.0,392.0&gt;-&lt;435.0,382.0&gt;-&lt;442.5,373.0&gt;&gt;
</code></pre>
 [code: found-short-segments]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Do outlines contain any jaggy segments? <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/outline.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>The following glyphs have jaggy segments:</p>
<pre><code>* t (U+0074): B&lt;&lt;238.0,581.5&gt;-&lt;222.0,560.0&gt;-&lt;195.0,554.0&gt;&gt;/L&lt;&lt;195.0,554.0&gt;--&lt;376.0,554.0&gt;&gt; = 12.528807709151492

* tcaron (U+0165): B&lt;&lt;238.0,581.5&gt;-&lt;222.0,560.0&gt;-&lt;195.0,554.0&gt;&gt;/L&lt;&lt;195.0,554.0&gt;--&lt;376.0,554.0&gt;&gt; = 12.528807709151492

* uni0163 (U+0163): B&lt;&lt;238.0,581.5&gt;-&lt;222.0,560.0&gt;-&lt;195.0,554.0&gt;&gt;/L&lt;&lt;195.0,554.0&gt;--&lt;376.0,554.0&gt;&gt; = 12.528807709151492

* uni021B (U+021B): B&lt;&lt;238.0,581.5&gt;-&lt;222.0,560.0&gt;-&lt;195.0,554.0&gt;&gt;/L&lt;&lt;195.0,554.0&gt;--&lt;376.0,554.0&gt;&gt; = 12.528807709151492
</code></pre>
 [code: found-jaggy-segments]



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
    <summary>⚠️ <b>WARN</b> Checking OS/2 achVendID. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.os2.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>OS/2 VendorID value 'NONE' is not yet recognized. If you registered it recently, then it's safe to ignore this warning message. Otherwise, you should set it to your own unique 4 character code, and register it with Microsoft at <a href="https://www.microsoft.com/typography/links/vendorlist.aspx">https://www.microsoft.com/typography/links/vendorlist.aspx</a></p>
 [code: unknown]



</div>
</details>
</div>
</details>

<details><summary>[9] Parkinsans-Bold.ttf</summary>
<div>
<details>
    <summary>⚠️ <b>WARN</b> Check if each glyph has the recommended amount of contours. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.</p>
<p>The following glyphs do not have the recommended number of contours:</p>
<pre><code>- Glyph name: uni0127	Contours detected: 2	Expected: 1

- Glyph name: liter	Contours detected: 1	Expected: 2

- Glyph name: fi	Contours detected: 2	Expected: 3
</code></pre>
 [code: contour-count]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Validate size, and resolution of article images, and ensure article page has minimum length and includes visual assets. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.article.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>Family metadata at fonts/ttf does not have an article.</p>
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
<li>U+0302 COMBINING CIRCUMFLEX ACCENT: try adding one of: math, cherokee, tifinagh, coptic</li>
<li>U+0306 COMBINING BREVE: try adding one of: tifinagh, old-permic</li>
<li>U+0307 COMBINING DOT ABOVE: try adding one of: tai-le, old-permic, coptic, tifinagh, syriac, hebrew, canadian-aboriginal, todhri, malayalam, duployan, math</li>
<li>U+030A COMBINING RING ABOVE: try adding one of: duployan, syriac</li>
<li>U+030B COMBINING DOUBLE ACUTE ACCENT: try adding one of: osage, cherokee</li>
<li>U+030C COMBINING CARON: try adding one of: tai-le, cherokee</li>
<li>U+0326 COMBINING COMMA BELOW: try adding math</li>
<li>U+0327 COMBINING CEDILLA: try adding math</li>
<li>U+0328 COMBINING OGONEK: not included in any glyphset definition</li>
<li>U+03C0 GREEK SMALL LETTER PI: try adding one of: greek, yi, math</li>
<li>U+1EBC LATIN CAPITAL LETTER E WITH TILDE: try adding vietnamese</li>
<li>U+1EBD LATIN SMALL LETTER E WITH TILDE: try adding vietnamese</li>
<li>U+2021 DOUBLE DAGGER: try adding adlam</li>
<li>U+2030 PER MILLE SIGN: try adding adlam</li>
<li>U+2126 OHM SIGN: try adding math</li>
<li>U+212E ESTIMATED SYMBOL: try adding math</li>
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
<li>U+25CA LOZENGE: try adding one of: math, symbols</li>
<li>U+25CC DOTTED CIRCLE: try adding one of: sinhala, devanagari, saurashtra, duployan, hanifi-rohingya, kannada, tirhuta, soyombo, tai-le, chakma, psalter-pahlavi, sharada, limbu, balinese, cham, rejang, music, coptic, tagalog, tifinagh, elbasan, hebrew, kaithi, armenian, modi, marchen, kayah-li, thaana, lao, siddham, masaram-gondi, nko, warang-citi, syloti-nagri, telugu, new-tai-lue, lepcha, oriya, adlam, grantha, bhaiksuki, osage, buhid, yi, dogra, javanese, gurmukhi, symbols, mongolian, canadian-aboriginal, math, hanunoo, phags-pa, tibetan, thai, caucasian-albanian, gujarati, bassa-vah, takri, batak, zanabazar-square, pahawh-hmong, tai-viet, tagbanwa, tamil, khojki, miao, sogdian, old-permic, manichaean, khudawadi, mende-kikakui, mandaic, kharoshthi, brahmi, wancho, mahajani, ahom, syriac, meetei-mayek, gunjala-gondi, buginese, malayalam, tai-tham, bengali, sundanese, khmer, myanmar, newa</li>
<li>U+FB01 LATIN SMALL LIGATURE FI: not included in any glyphset definition</li>
<li>U+FB02 LATIN SMALL LIGATURE FL: not included in any glyphset definition</li>
</ul>
<p>Or you can add the above codepoints to one of the subsets supported by the font: <code>latin</code>, <code>latin-ext</code></p>
 [code: unreachable-subsetting]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Ensure soft_dotted characters lose their dot when combined with marks that replace the dot. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/shaping.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>The dot of soft dotted characters used in orthographies <em>must</em> disappear in the following strings: i̊ i̋ j̀ j́ j̃ j̄ j̈ į̀ į́ į̂ į̃ į̄ į̌</p>
<p>The dot of soft dotted characters <em>should</em> disappear in other cases, for example: i̇ ǐ i̦̇ i̦̊ i̦̋ ǐ̦ i̧̇ i̧̊ i̧̋ ǐ̧ ĵ j̆ j̇ j̊ j̋ ǰ j̦̀ j̦́ ĵ̦ j̦̃</p>
<p>Your font fully covers the following languages that require the soft-dotted feature: Lithuanian (Latn, 2,357,094 speakers), Dutch (Latn, 31,709,104 speakers).</p>
<p>Your font does <em>not</em> cover the following languages that require the soft-dotted feature: Dii (Latn, 71,000 speakers), Zapotec (Latn, 490,000 speakers), Mundani (Latn, 34,000 speakers), Igbo (Latn, 27,823,640 speakers), Belarusian (Cyrl, 10,064,517 speakers), Cicipu (Latn, 44,000 speakers), Gulay (Latn, 250,478 speakers), Sar (Latn, 500,000 speakers), Ejagham (Latn, 120,000 speakers), Ma’di (Latn, 584,000 speakers), Vute (Latn, 21,000 speakers), Dan (Latn, 1,099,244 speakers), Nateni (Latn, 100,000 speakers), Ijo, Southeast (Latn, 2,471,000 speakers), Ngbaka (Latn, 1,020,000 speakers), Heiltsuk (Latn, 300 speakers), Koonzime (Latn, 40,000 speakers), Lugbara (Latn, 2,200,000 speakers), Makaa (Latn, 221,000 speakers), Mango (Latn, 77,000 speakers), Navajo (Latn, 166,319 speakers), Han (Latn, 6 speakers), Kom (Latn, 360,685 speakers), Bete-Bendi (Latn, 100,000 speakers), Ekpeye (Latn, 226,000 speakers), Teke-Ebo (Latn, 260,000 speakers), Kaska (Latn, 125 speakers), Aghem (Latn, 38,843 speakers), Kpelle, Guinea (Latn, 622,000 speakers), South Central Banda (Latn, 244,000 speakers), Basaa (Latn, 332,940 speakers), Fur (Latn, 1,230,163 speakers), Ukrainian (Cyrl, 29,273,587 speakers), Avokaya (Latn, 100,000 speakers), Bafut (Latn, 158,146 speakers), Mfumte (Latn, 79,000 speakers), Nzakara (Latn, 50,000 speakers), Southern Kisi (Latn, 360,000 speakers), Ebira (Latn, 2,200,000 speakers), Yala (Latn, 200,000 speakers).</p>
 [code: soft-dotted]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Are there any misaligned on-curve points? <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/outline.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>The following glyphs have on-curve points which have potentially incorrect y coordinates:</p>
<pre><code>* Q (U+0051): X=473.0,Y=1.0 (should be at baseline 0?)

* Uogonek (U+0172): X=432.0,Y=2.0 (should be at baseline 0?)

* uni0123 (U+0123): X=243.0,Y=703.0 (should be at cap-height 702?)

* ldot (U+0140): X=283.0,Y=-2.0 (should be at baseline 0?)

* lslash (U+0142): X=295.5,Y=-2.0 (should be at baseline 0?)

* t (U+0074): X=358.0,Y=1.0 (should be at baseline 0?)

* tcaron (U+0165): X=358.0,Y=1.0 (should be at baseline 0?)

* tcaron (U+0165): X=387.0,Y=703.0 (should be at cap-height 702?)

* uni0163 (U+0163): X=358.0,Y=1.0 (should be at baseline 0?)

* uni021B (U+021B): X=358.0,Y=1.0 (should be at baseline 0?)

* greaterequal (U+2265): X=532.0,Y=2.0 (should be at baseline 0?)

* greaterequal (U+2265): X=135.0,Y=2.0 (should be at baseline 0?)

* lessequal (U+2264): X=547.0,Y=2.0 (should be at baseline 0?)

* lessequal (U+2264): X=150.0,Y=2.0 (should be at baseline 0?)

* uni2206 (U+2206): X=298.0,Y=703.0 (should be at cap-height 702?)

* uni2206 (U+2206): X=436.0,Y=703.0 (should be at cap-height 702?)

* asciicircum (U+005E): X=272.0,Y=703.0 (should be at cap-height 702?)

* asciicircum (U+005E): X=436.0,Y=703.0 (should be at cap-height 702?)

* uni20BA (U+20BA): X=270.5,Y=-0.5 (should be at baseline 0?)
</code></pre>
 [code: found-misalignments]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Are any segments inordinately short? <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/outline.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>The following glyphs have segments which seem very short:</p>
<pre><code>* Ccedilla (U+00C7) contains a short segment B&lt;&lt;442.0,-148.0&gt;-&lt;442.0,-133.0&gt;-&lt;431.5,-127.0&gt;&gt;

* oe (U+0153) contains a short segment B&lt;&lt;645.0,200.5&gt;-&lt;631.0,201.0&gt;-&lt;625.0,202.0&gt;&gt;

* germandbls (U+00DF) contains a short segment B&lt;&lt;473.0,394.0&gt;-&lt;473.0,385.0&gt;-&lt;479.5,377.0&gt;&gt;

* uni0163 (U+0163) contains a short segment B&lt;&lt;300.0,-7.0&gt;-&lt;295.0,-7.0&gt;-&lt;291.0,-7.0&gt;&gt;

* fi (U+FB01) contains a short segment L&lt;&lt;100.0,558.0&gt;--&lt;100.0,574.0&gt;&gt;

* integral (U+222B) contains a short segment L&lt;&lt;327.0,799.0&gt;--&lt;311.0,799.0&gt;&gt;

* uni1E9E (U+1E9E) contains a short segment B&lt;&lt;473.0,394.0&gt;-&lt;473.0,385.0&gt;-&lt;479.5,377.0&gt;&gt;
</code></pre>
 [code: found-short-segments]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Do outlines contain any jaggy segments? <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/outline.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>The following glyphs have jaggy segments:</p>
<pre><code>* t (U+0074): B&lt;&lt;263.0,587.5&gt;-&lt;247.0,563.0&gt;-&lt;216.0,558.0&gt;&gt;/L&lt;&lt;216.0,558.0&gt;--&lt;390.0,558.0&gt;&gt; = 9.162347045721706

* tcaron (U+0165): B&lt;&lt;263.0,587.5&gt;-&lt;247.0,563.0&gt;-&lt;216.0,558.0&gt;&gt;/L&lt;&lt;216.0,558.0&gt;--&lt;390.0,558.0&gt;&gt; = 9.162347045721706

* uni0127 (U+0127): B&lt;&lt;283.5,519.0&gt;-&lt;321.0,551.0&gt;-&lt;368.0,561.0&gt;&gt;/L&lt;&lt;368.0,561.0&gt;--&lt;231.0,561.0&gt;&gt; = 12.01147838636543

* uni0163 (U+0163): B&lt;&lt;263.0,587.5&gt;-&lt;247.0,563.0&gt;-&lt;216.0,558.0&gt;&gt;/L&lt;&lt;216.0,558.0&gt;--&lt;390.0,558.0&gt;&gt; = 9.162347045721706

* uni021B (U+021B): B&lt;&lt;263.0,587.5&gt;-&lt;247.0,563.0&gt;-&lt;216.0,558.0&gt;&gt;/L&lt;&lt;216.0,558.0&gt;--&lt;390.0,558.0&gt;&gt; = 9.162347045721706

* uogonek (U+0173): L&lt;&lt;442.0,85.0&gt;--&lt;442.0,120.0&gt;&gt;/B&lt;&lt;442.0,120.0&gt;-&lt;428.0,63.0&gt;-&lt;381.5,28.0&gt;&gt; = 13.799485396019362
</code></pre>
 [code: found-jaggy-segments]



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
    <summary>⚠️ <b>WARN</b> Checking OS/2 achVendID. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.os2.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>OS/2 VendorID value 'NONE' is not yet recognized. If you registered it recently, then it's safe to ignore this warning message. Otherwise, you should set it to your own unique 4 character code, and register it with Microsoft at <a href="https://www.microsoft.com/typography/links/vendorlist.aspx">https://www.microsoft.com/typography/links/vendorlist.aspx</a></p>
 [code: unknown]



</div>
</details>
</div>
</details>

<details><summary>[9] Parkinsans-Medium.ttf</summary>
<div>
<details>
    <summary>⚠️ <b>WARN</b> Check if each glyph has the recommended amount of contours. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.</p>
<p>The following glyphs do not have the recommended number of contours:</p>
<pre><code>- Glyph name: liter	Contours detected: 1	Expected: 2

- Glyph name: fi	Contours detected: 2	Expected: 3
</code></pre>
 [code: contour-count]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Validate size, and resolution of article images, and ensure article page has minimum length and includes visual assets. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.article.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>Family metadata at fonts/ttf does not have an article.</p>
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
<li>U+0302 COMBINING CIRCUMFLEX ACCENT: try adding one of: math, cherokee, tifinagh, coptic</li>
<li>U+0306 COMBINING BREVE: try adding one of: tifinagh, old-permic</li>
<li>U+0307 COMBINING DOT ABOVE: try adding one of: tai-le, old-permic, coptic, tifinagh, syriac, hebrew, canadian-aboriginal, todhri, malayalam, duployan, math</li>
<li>U+030A COMBINING RING ABOVE: try adding one of: duployan, syriac</li>
<li>U+030B COMBINING DOUBLE ACUTE ACCENT: try adding one of: osage, cherokee</li>
<li>U+030C COMBINING CARON: try adding one of: tai-le, cherokee</li>
<li>U+0326 COMBINING COMMA BELOW: try adding math</li>
<li>U+0327 COMBINING CEDILLA: try adding math</li>
<li>U+0328 COMBINING OGONEK: not included in any glyphset definition</li>
<li>U+03C0 GREEK SMALL LETTER PI: try adding one of: greek, yi, math</li>
<li>U+1EBC LATIN CAPITAL LETTER E WITH TILDE: try adding vietnamese</li>
<li>U+1EBD LATIN SMALL LETTER E WITH TILDE: try adding vietnamese</li>
<li>U+2021 DOUBLE DAGGER: try adding adlam</li>
<li>U+2030 PER MILLE SIGN: try adding adlam</li>
<li>U+2126 OHM SIGN: try adding math</li>
<li>U+212E ESTIMATED SYMBOL: try adding math</li>
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
<li>U+25CA LOZENGE: try adding one of: math, symbols</li>
<li>U+25CC DOTTED CIRCLE: try adding one of: sinhala, devanagari, saurashtra, duployan, hanifi-rohingya, kannada, tirhuta, soyombo, tai-le, chakma, psalter-pahlavi, sharada, limbu, balinese, cham, rejang, music, coptic, tagalog, tifinagh, elbasan, hebrew, kaithi, armenian, modi, marchen, kayah-li, thaana, lao, siddham, masaram-gondi, nko, warang-citi, syloti-nagri, telugu, new-tai-lue, lepcha, oriya, adlam, grantha, bhaiksuki, osage, buhid, yi, dogra, javanese, gurmukhi, symbols, mongolian, canadian-aboriginal, math, hanunoo, phags-pa, tibetan, thai, caucasian-albanian, gujarati, bassa-vah, takri, batak, zanabazar-square, pahawh-hmong, tai-viet, tagbanwa, tamil, khojki, miao, sogdian, old-permic, manichaean, khudawadi, mende-kikakui, mandaic, kharoshthi, brahmi, wancho, mahajani, ahom, syriac, meetei-mayek, gunjala-gondi, buginese, malayalam, tai-tham, bengali, sundanese, khmer, myanmar, newa</li>
<li>U+FB01 LATIN SMALL LIGATURE FI: not included in any glyphset definition</li>
<li>U+FB02 LATIN SMALL LIGATURE FL: not included in any glyphset definition</li>
</ul>
<p>Or you can add the above codepoints to one of the subsets supported by the font: <code>latin</code>, <code>latin-ext</code></p>
 [code: unreachable-subsetting]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Ensure soft_dotted characters lose their dot when combined with marks that replace the dot. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/shaping.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>The dot of soft dotted characters used in orthographies <em>must</em> disappear in the following strings: i̊ i̋ j̀ j́ j̃ j̄ j̈ į̀ į́ į̂ į̃ į̄ į̌</p>
<p>The dot of soft dotted characters <em>should</em> disappear in other cases, for example: i̇ ǐ i̦̇ i̦̊ i̦̋ ǐ̦ i̧̇ i̧̊ i̧̋ ǐ̧ ĵ j̆ j̇ j̊ j̋ ǰ j̦̀ j̦́ ĵ̦ j̦̃</p>
<p>Your font fully covers the following languages that require the soft-dotted feature: Lithuanian (Latn, 2,357,094 speakers), Dutch (Latn, 31,709,104 speakers).</p>
<p>Your font does <em>not</em> cover the following languages that require the soft-dotted feature: Dii (Latn, 71,000 speakers), Zapotec (Latn, 490,000 speakers), Mundani (Latn, 34,000 speakers), Igbo (Latn, 27,823,640 speakers), Belarusian (Cyrl, 10,064,517 speakers), Cicipu (Latn, 44,000 speakers), Gulay (Latn, 250,478 speakers), Sar (Latn, 500,000 speakers), Ejagham (Latn, 120,000 speakers), Ma’di (Latn, 584,000 speakers), Vute (Latn, 21,000 speakers), Dan (Latn, 1,099,244 speakers), Nateni (Latn, 100,000 speakers), Ijo, Southeast (Latn, 2,471,000 speakers), Ngbaka (Latn, 1,020,000 speakers), Heiltsuk (Latn, 300 speakers), Koonzime (Latn, 40,000 speakers), Lugbara (Latn, 2,200,000 speakers), Makaa (Latn, 221,000 speakers), Mango (Latn, 77,000 speakers), Navajo (Latn, 166,319 speakers), Han (Latn, 6 speakers), Kom (Latn, 360,685 speakers), Bete-Bendi (Latn, 100,000 speakers), Ekpeye (Latn, 226,000 speakers), Teke-Ebo (Latn, 260,000 speakers), Kaska (Latn, 125 speakers), Aghem (Latn, 38,843 speakers), Kpelle, Guinea (Latn, 622,000 speakers), South Central Banda (Latn, 244,000 speakers), Basaa (Latn, 332,940 speakers), Fur (Latn, 1,230,163 speakers), Ukrainian (Cyrl, 29,273,587 speakers), Avokaya (Latn, 100,000 speakers), Bafut (Latn, 158,146 speakers), Mfumte (Latn, 79,000 speakers), Nzakara (Latn, 50,000 speakers), Southern Kisi (Latn, 360,000 speakers), Ebira (Latn, 2,200,000 speakers), Yala (Latn, 200,000 speakers).</p>
 [code: soft-dotted]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Are there any misaligned on-curve points? <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/outline.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>The following glyphs have on-curve points which have potentially incorrect y coordinates:</p>
<pre><code>* Iogonek (U+012E): X=258.0,Y=1.0 (should be at baseline 0?)

* atilde (U+00E3): X=215.0,Y=696.0 (should be at cap-height 695?)

* uni1EBD (U+1EBD): X=192.0,Y=696.0 (should be at cap-height 695?)

* iogonek (U+012F): X=192.0,Y=1.0 (should be at baseline 0?)

* itilde (U+0129): X=8.0,Y=696.0 (should be at cap-height 695?)

* ldot (U+0140): X=244.5,Y=-2.0 (should be at baseline 0?)

* lslash (U+0142): X=244.5,Y=-2.0 (should be at baseline 0?)

* ntilde (U+00F1): X=201.0,Y=696.0 (should be at cap-height 695?)

* obreve (U+014F): X=319.0,Y=693.0 (should be at cap-height 695?)

* utilde (U+0169): X=201.0,Y=696.0 (should be at cap-height 695?)

* uni1EF9 (U+1EF9): X=183.0,Y=696.0 (should be at cap-height 695?)

* braceleft (U+007B): X=212.5,Y=694.0 (should be at cap-height 695?)

* braceright (U+007D): X=304.0,Y=694.0 (should be at cap-height 695?)

* uni2206 (U+2206): X=301.0,Y=696.0 (should be at cap-height 695?)

* uni2206 (U+2206): X=395.0,Y=696.0 (should be at cap-height 695?)

* product (U+220F): X=31.0,Y=696.0 (should be at cap-height 695?)

* product (U+220F): X=710.0,Y=696.0 (should be at cap-height 695?)

* uni00B5 (U+00B5): X=235.0,Y=0.5 (should be at baseline 0?)

* asciicircum (U+005E): X=273.0,Y=696.0 (should be at cap-height 695?)

* asciicircum (U+005E): X=381.0,Y=696.0 (should be at cap-height 695?)

* tilde (U+02DC): X=49.0,Y=696.0 (should be at cap-height 695?)

* uni20B9 (U+20B9): X=46.0,Y=696.0 (should be at cap-height 695?)

* uni20B9 (U+20B9): X=590.0,Y=696.0 (should be at cap-height 695?)

* uni0303 (U+0303): X=49.0,Y=696.0 (should be at cap-height 695?)
</code></pre>
 [code: found-misalignments]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Are any segments inordinately short? <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/outline.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>The following glyphs have segments which seem very short:</p>
<pre><code>* ae (U+00E6) contains a short segment B&lt;&lt;661.5,204.5&gt;-&lt;650.0,205.0&gt;-&lt;649.0,205.0&gt;&gt;

* aeacute (U+01FD) contains a short segment B&lt;&lt;661.5,204.5&gt;-&lt;650.0,205.0&gt;-&lt;649.0,205.0&gt;&gt;

* e (U+0065) contains a short segment B&lt;&lt;171.5,204.5&gt;-&lt;160.0,205.0&gt;-&lt;159.0,205.0&gt;&gt;

* eacute (U+00E9) contains a short segment B&lt;&lt;171.5,204.5&gt;-&lt;160.0,205.0&gt;-&lt;159.0,205.0&gt;&gt;

* ebreve (U+0115) contains a short segment B&lt;&lt;171.5,204.5&gt;-&lt;160.0,205.0&gt;-&lt;159.0,205.0&gt;&gt;

* ecaron (U+011B) contains a short segment B&lt;&lt;171.5,204.5&gt;-&lt;160.0,205.0&gt;-&lt;159.0,205.0&gt;&gt;

* ecircumflex (U+00EA) contains a short segment B&lt;&lt;171.5,204.5&gt;-&lt;160.0,205.0&gt;-&lt;159.0,205.0&gt;&gt;

* edieresis (U+00EB) contains a short segment B&lt;&lt;171.5,204.5&gt;-&lt;160.0,205.0&gt;-&lt;159.0,205.0&gt;&gt;

* edotaccent (U+0117) contains a short segment B&lt;&lt;171.5,204.5&gt;-&lt;160.0,205.0&gt;-&lt;159.0,205.0&gt;&gt;

* egrave (U+00E8) contains a short segment B&lt;&lt;171.5,204.5&gt;-&lt;160.0,205.0&gt;-&lt;159.0,205.0&gt;&gt;

* emacron (U+0113) contains a short segment B&lt;&lt;171.5,204.5&gt;-&lt;160.0,205.0&gt;-&lt;159.0,205.0&gt;&gt;

* eogonek (U+0119) contains a short segment B&lt;&lt;248.0,200.0&gt;-&lt;245.0,200.0&gt;-&lt;230.0,200.0&gt;&gt;

* uni1EBD (U+1EBD) contains a short segment B&lt;&lt;171.5,204.5&gt;-&lt;160.0,205.0&gt;-&lt;159.0,205.0&gt;&gt;

* oe (U+0153) contains a short segment B&lt;&lt;640.5,204.5&gt;-&lt;629.0,205.0&gt;-&lt;628.0,205.0&gt;&gt;

* uni0163 (U+0163) contains a short segment B&lt;&lt;260.0,-8.0&gt;-&lt;254.0,-8.0&gt;-&lt;248.0,-8.0&gt;&gt;

* florin (U+0192) contains a short segment L&lt;&lt;-46.0,-123.0&gt;--&lt;-30.0,-123.0&gt;&gt;
</code></pre>
 [code: found-short-segments]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Do outlines contain any jaggy segments? <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/outline.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>The following glyphs have jaggy segments:</p>
<pre><code>* t (U+0074): B&lt;&lt;212.5,575.0&gt;-&lt;197.0,556.0&gt;-&lt;174.0,551.0&gt;&gt;/L&lt;&lt;174.0,551.0&gt;--&lt;362.0,551.0&gt;&gt; = 12.2647737278924

* tcaron (U+0165): B&lt;&lt;212.5,575.0&gt;-&lt;197.0,556.0&gt;-&lt;174.0,551.0&gt;&gt;/L&lt;&lt;174.0,551.0&gt;--&lt;362.0,551.0&gt;&gt; = 12.2647737278924

* uni0163 (U+0163): B&lt;&lt;212.5,575.0&gt;-&lt;197.0,556.0&gt;-&lt;174.0,551.0&gt;&gt;/L&lt;&lt;174.0,551.0&gt;--&lt;362.0,551.0&gt;&gt; = 12.2647737278924

* uni021B (U+021B): B&lt;&lt;212.5,575.0&gt;-&lt;197.0,556.0&gt;-&lt;174.0,551.0&gt;&gt;/L&lt;&lt;174.0,551.0&gt;--&lt;362.0,551.0&gt;&gt; = 12.2647737278924
</code></pre>
 [code: found-jaggy-segments]



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
    <summary>⚠️ <b>WARN</b> Checking OS/2 achVendID. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.os2.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>OS/2 VendorID value 'NONE' is not yet recognized. If you registered it recently, then it's safe to ignore this warning message. Otherwise, you should set it to your own unique 4 character code, and register it with Microsoft at <a href="https://www.microsoft.com/typography/links/vendorlist.aspx">https://www.microsoft.com/typography/links/vendorlist.aspx</a></p>
 [code: unknown]



</div>
</details>
</div>
</details>

<details><summary>[9] Parkinsans-Regular.ttf</summary>
<div>
<details>
    <summary>⚠️ <b>WARN</b> Check if each glyph has the recommended amount of contours. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.</p>
<p>The following glyphs do not have the recommended number of contours:</p>
<pre><code>- Glyph name: liter	Contours detected: 1	Expected: 2

- Glyph name: fi	Contours detected: 2	Expected: 3
</code></pre>
 [code: contour-count]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Validate size, and resolution of article images, and ensure article page has minimum length and includes visual assets. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.article.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>Family metadata at fonts/ttf does not have an article.</p>
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
<li>U+0302 COMBINING CIRCUMFLEX ACCENT: try adding one of: math, cherokee, tifinagh, coptic</li>
<li>U+0306 COMBINING BREVE: try adding one of: tifinagh, old-permic</li>
<li>U+0307 COMBINING DOT ABOVE: try adding one of: tai-le, old-permic, coptic, tifinagh, syriac, hebrew, canadian-aboriginal, todhri, malayalam, duployan, math</li>
<li>U+030A COMBINING RING ABOVE: try adding one of: duployan, syriac</li>
<li>U+030B COMBINING DOUBLE ACUTE ACCENT: try adding one of: osage, cherokee</li>
<li>U+030C COMBINING CARON: try adding one of: tai-le, cherokee</li>
<li>U+0326 COMBINING COMMA BELOW: try adding math</li>
<li>U+0327 COMBINING CEDILLA: try adding math</li>
<li>U+0328 COMBINING OGONEK: not included in any glyphset definition</li>
<li>U+03C0 GREEK SMALL LETTER PI: try adding one of: greek, yi, math</li>
<li>U+1EBC LATIN CAPITAL LETTER E WITH TILDE: try adding vietnamese</li>
<li>U+1EBD LATIN SMALL LETTER E WITH TILDE: try adding vietnamese</li>
<li>U+2021 DOUBLE DAGGER: try adding adlam</li>
<li>U+2030 PER MILLE SIGN: try adding adlam</li>
<li>U+2126 OHM SIGN: try adding math</li>
<li>U+212E ESTIMATED SYMBOL: try adding math</li>
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
<li>U+25CA LOZENGE: try adding one of: math, symbols</li>
<li>U+25CC DOTTED CIRCLE: try adding one of: sinhala, devanagari, saurashtra, duployan, hanifi-rohingya, kannada, tirhuta, soyombo, tai-le, chakma, psalter-pahlavi, sharada, limbu, balinese, cham, rejang, music, coptic, tagalog, tifinagh, elbasan, hebrew, kaithi, armenian, modi, marchen, kayah-li, thaana, lao, siddham, masaram-gondi, nko, warang-citi, syloti-nagri, telugu, new-tai-lue, lepcha, oriya, adlam, grantha, bhaiksuki, osage, buhid, yi, dogra, javanese, gurmukhi, symbols, mongolian, canadian-aboriginal, math, hanunoo, phags-pa, tibetan, thai, caucasian-albanian, gujarati, bassa-vah, takri, batak, zanabazar-square, pahawh-hmong, tai-viet, tagbanwa, tamil, khojki, miao, sogdian, old-permic, manichaean, khudawadi, mende-kikakui, mandaic, kharoshthi, brahmi, wancho, mahajani, ahom, syriac, meetei-mayek, gunjala-gondi, buginese, malayalam, tai-tham, bengali, sundanese, khmer, myanmar, newa</li>
<li>U+FB01 LATIN SMALL LIGATURE FI: not included in any glyphset definition</li>
<li>U+FB02 LATIN SMALL LIGATURE FL: not included in any glyphset definition</li>
</ul>
<p>Or you can add the above codepoints to one of the subsets supported by the font: <code>latin</code>, <code>latin-ext</code></p>
 [code: unreachable-subsetting]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Ensure soft_dotted characters lose their dot when combined with marks that replace the dot. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/shaping.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>The dot of soft dotted characters used in orthographies <em>must</em> disappear in the following strings: i̊ i̋ j̀ j́ j̃ j̄ j̈ į̀ į́ į̂ į̃ į̄ į̌</p>
<p>The dot of soft dotted characters <em>should</em> disappear in other cases, for example: i̇ ǐ i̦̇ i̦̊ i̦̋ ǐ̦ i̧̇ i̧̊ i̧̋ ǐ̧ ĵ j̆ j̇ j̊ j̋ ǰ j̦̀ j̦́ ĵ̦ j̦̃</p>
<p>Your font fully covers the following languages that require the soft-dotted feature: Lithuanian (Latn, 2,357,094 speakers), Dutch (Latn, 31,709,104 speakers).</p>
<p>Your font does <em>not</em> cover the following languages that require the soft-dotted feature: Dii (Latn, 71,000 speakers), Zapotec (Latn, 490,000 speakers), Mundani (Latn, 34,000 speakers), Igbo (Latn, 27,823,640 speakers), Belarusian (Cyrl, 10,064,517 speakers), Cicipu (Latn, 44,000 speakers), Gulay (Latn, 250,478 speakers), Sar (Latn, 500,000 speakers), Ejagham (Latn, 120,000 speakers), Ma’di (Latn, 584,000 speakers), Vute (Latn, 21,000 speakers), Dan (Latn, 1,099,244 speakers), Nateni (Latn, 100,000 speakers), Ijo, Southeast (Latn, 2,471,000 speakers), Ngbaka (Latn, 1,020,000 speakers), Heiltsuk (Latn, 300 speakers), Koonzime (Latn, 40,000 speakers), Lugbara (Latn, 2,200,000 speakers), Makaa (Latn, 221,000 speakers), Mango (Latn, 77,000 speakers), Navajo (Latn, 166,319 speakers), Han (Latn, 6 speakers), Kom (Latn, 360,685 speakers), Bete-Bendi (Latn, 100,000 speakers), Ekpeye (Latn, 226,000 speakers), Teke-Ebo (Latn, 260,000 speakers), Kaska (Latn, 125 speakers), Aghem (Latn, 38,843 speakers), Kpelle, Guinea (Latn, 622,000 speakers), South Central Banda (Latn, 244,000 speakers), Basaa (Latn, 332,940 speakers), Fur (Latn, 1,230,163 speakers), Ukrainian (Cyrl, 29,273,587 speakers), Avokaya (Latn, 100,000 speakers), Bafut (Latn, 158,146 speakers), Mfumte (Latn, 79,000 speakers), Nzakara (Latn, 50,000 speakers), Southern Kisi (Latn, 360,000 speakers), Ebira (Latn, 2,200,000 speakers), Yala (Latn, 200,000 speakers).</p>
 [code: soft-dotted]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Are there any misaligned on-curve points? <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/outline.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>The following glyphs have on-curve points which have potentially incorrect y coordinates:</p>
<pre><code>* Iogonek (U+012E): X=230.0,Y=1.0 (should be at baseline 0?)

* Scedilla (U+015E): X=275.0,Y=2.0 (should be at baseline 0?)

* Scedilla (U+015E): X=337.0,Y=2.0 (should be at baseline 0?)

* abreve (U+0103): X=270.5,Y=694.0 (should be at cap-height 693?)

* abreve (U+0103): X=407.0,Y=694.0 (should be at cap-height 693?)

* eth (U+00F0): X=553.0,Y=692.0 (should be at cap-height 693?)

* ebreve (U+0115): X=249.5,Y=694.0 (should be at cap-height 693?)

* ebreve (U+0115): X=386.0,Y=694.0 (should be at cap-height 693?)

* gbreve (U+011F): X=270.5,Y=694.0 (should be at cap-height 693?)

* gbreve (U+011F): X=407.0,Y=694.0 (should be at cap-height 693?)

* ibreve (U+012D): X=55.5,Y=694.0 (should be at cap-height 693?)

* ibreve (U+012D): X=192.0,Y=694.0 (should be at cap-height 693?)

* iogonek (U+012F): X=174.0,Y=1.0 (should be at baseline 0?)

* otilde (U+00F5): X=208.0,Y=692.0 (should be at cap-height 693?)

* germandbls (U+00DF): X=294.0,Y=694.0 (should be at cap-height 693?)

* ubreve (U+016D): X=253.5,Y=694.0 (should be at cap-height 693?)

* ubreve (U+016D): X=390.0,Y=694.0 (should be at cap-height 693?)

* cent (U+00A2): X=293.0,Y=2.0 (should be at baseline 0?)

* cent (U+00A2): X=347.0,Y=2.0 (should be at baseline 0?)

* florin (U+0192): X=317.0,Y=691.0 (should be at cap-height 693?)

* sterling (U+00A3): X=214.5,Y=695.0 (should be at cap-height 693?)

* sterling (U+00A3): X=442.5,Y=694.5 (should be at cap-height 693?)

* dotaccent (U+02D9): X=34.0,Y=693.5 (should be at cap-height 693?)

* dotaccent (U+02D9): X=109.0,Y=693.5 (should be at cap-height 693?)

* uni1E9E (U+1E9E): X=294.0,Y=694.0 (should be at cap-height 693?)

* uni0306 (U+0306): X=91.5,Y=694.0 (should be at cap-height 693?)

* uni0306 (U+0306): X=228.0,Y=694.0 (should be at cap-height 693?)
</code></pre>
 [code: found-misalignments]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Do outlines contain any jaggy segments? <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/outline.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>The following glyphs have jaggy segments:</p>
<pre><code>* t (U+0074): B&lt;&lt;199.0,571.0&gt;-&lt;186.0,553.0&gt;-&lt;164.0,549.0&gt;&gt;/L&lt;&lt;164.0,549.0&gt;--&lt;337.0,549.0&gt;&gt; = 10.304846468766044

* tcaron (U+0165): B&lt;&lt;199.0,571.0&gt;-&lt;186.0,553.0&gt;-&lt;164.0,549.0&gt;&gt;/L&lt;&lt;164.0,549.0&gt;--&lt;337.0,549.0&gt;&gt; = 10.304846468766044

* uni0163 (U+0163): B&lt;&lt;199.0,571.0&gt;-&lt;186.0,553.0&gt;-&lt;164.0,549.0&gt;&gt;/L&lt;&lt;164.0,549.0&gt;--&lt;337.0,549.0&gt;&gt; = 10.304846468766044

* uni021B (U+021B): B&lt;&lt;199.0,571.0&gt;-&lt;186.0,553.0&gt;-&lt;164.0,549.0&gt;&gt;/L&lt;&lt;164.0,549.0&gt;--&lt;337.0,549.0&gt;&gt; = 10.304846468766044
</code></pre>
 [code: found-jaggy-segments]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Do outlines contain any semi-vertical or semi-horizontal lines? <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/outline.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>The following glyphs have semi-vertical/semi-horizontal lines:</p>
<pre><code>* uni20B9 (U+20B9): L&lt;&lt;96.0,200.0&gt;--&lt;95.0,340.0&gt;&gt;
</code></pre>
 [code: found-semi-vertical]



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
    <summary>⚠️ <b>WARN</b> Checking OS/2 achVendID. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.os2.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>OS/2 VendorID value 'NONE' is not yet recognized. If you registered it recently, then it's safe to ignore this warning message. Otherwise, you should set it to your own unique 4 character code, and register it with Microsoft at <a href="https://www.microsoft.com/typography/links/vendorlist.aspx">https://www.microsoft.com/typography/links/vendorlist.aspx</a></p>
 [code: unknown]



</div>
</details>
</div>
</details>

<details><summary>[8] Parkinsans-Light.ttf</summary>
<div>
<details>
    <summary>⚠️ <b>WARN</b> Check if each glyph has the recommended amount of contours. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.</p>
<p>The following glyphs do not have the recommended number of contours:</p>
<pre><code>- Glyph name: liter	Contours detected: 1	Expected: 2

- Glyph name: fi	Contours detected: 2	Expected: 3
</code></pre>
 [code: contour-count]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Validate size, and resolution of article images, and ensure article page has minimum length and includes visual assets. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.article.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>Family metadata at fonts/ttf does not have an article.</p>
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
<li>U+0302 COMBINING CIRCUMFLEX ACCENT: try adding one of: math, cherokee, tifinagh, coptic</li>
<li>U+0306 COMBINING BREVE: try adding one of: tifinagh, old-permic</li>
<li>U+0307 COMBINING DOT ABOVE: try adding one of: tai-le, old-permic, coptic, tifinagh, syriac, hebrew, canadian-aboriginal, todhri, malayalam, duployan, math</li>
<li>U+030A COMBINING RING ABOVE: try adding one of: duployan, syriac</li>
<li>U+030B COMBINING DOUBLE ACUTE ACCENT: try adding one of: osage, cherokee</li>
<li>U+030C COMBINING CARON: try adding one of: tai-le, cherokee</li>
<li>U+0326 COMBINING COMMA BELOW: try adding math</li>
<li>U+0327 COMBINING CEDILLA: try adding math</li>
<li>U+0328 COMBINING OGONEK: not included in any glyphset definition</li>
<li>U+03C0 GREEK SMALL LETTER PI: try adding one of: greek, yi, math</li>
<li>U+1EBC LATIN CAPITAL LETTER E WITH TILDE: try adding vietnamese</li>
<li>U+1EBD LATIN SMALL LETTER E WITH TILDE: try adding vietnamese</li>
<li>U+2021 DOUBLE DAGGER: try adding adlam</li>
<li>U+2030 PER MILLE SIGN: try adding adlam</li>
<li>U+2126 OHM SIGN: try adding math</li>
<li>U+212E ESTIMATED SYMBOL: try adding math</li>
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
<li>U+25CA LOZENGE: try adding one of: math, symbols</li>
<li>U+25CC DOTTED CIRCLE: try adding one of: sinhala, devanagari, saurashtra, duployan, hanifi-rohingya, kannada, tirhuta, soyombo, tai-le, chakma, psalter-pahlavi, sharada, limbu, balinese, cham, rejang, music, coptic, tagalog, tifinagh, elbasan, hebrew, kaithi, armenian, modi, marchen, kayah-li, thaana, lao, siddham, masaram-gondi, nko, warang-citi, syloti-nagri, telugu, new-tai-lue, lepcha, oriya, adlam, grantha, bhaiksuki, osage, buhid, yi, dogra, javanese, gurmukhi, symbols, mongolian, canadian-aboriginal, math, hanunoo, phags-pa, tibetan, thai, caucasian-albanian, gujarati, bassa-vah, takri, batak, zanabazar-square, pahawh-hmong, tai-viet, tagbanwa, tamil, khojki, miao, sogdian, old-permic, manichaean, khudawadi, mende-kikakui, mandaic, kharoshthi, brahmi, wancho, mahajani, ahom, syriac, meetei-mayek, gunjala-gondi, buginese, malayalam, tai-tham, bengali, sundanese, khmer, myanmar, newa</li>
<li>U+FB01 LATIN SMALL LIGATURE FI: not included in any glyphset definition</li>
<li>U+FB02 LATIN SMALL LIGATURE FL: not included in any glyphset definition</li>
</ul>
<p>Or you can add the above codepoints to one of the subsets supported by the font: <code>latin</code>, <code>latin-ext</code></p>
 [code: unreachable-subsetting]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Ensure soft_dotted characters lose their dot when combined with marks that replace the dot. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/shaping.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>The dot of soft dotted characters used in orthographies <em>must</em> disappear in the following strings: i̊ i̋ j̀ j́ j̃ j̄ j̈ į̀ į́ į̂ į̃ į̄ į̌</p>
<p>The dot of soft dotted characters <em>should</em> disappear in other cases, for example: i̇ ǐ i̦̇ i̦̊ i̦̋ ǐ̦ i̧̇ i̧̊ i̧̋ ǐ̧ ĵ j̆ j̇ j̊ j̋ ǰ j̦̀ j̦́ ĵ̦ j̦̃</p>
<p>Your font fully covers the following languages that require the soft-dotted feature: Lithuanian (Latn, 2,357,094 speakers), Dutch (Latn, 31,709,104 speakers).</p>
<p>Your font does <em>not</em> cover the following languages that require the soft-dotted feature: Dii (Latn, 71,000 speakers), Zapotec (Latn, 490,000 speakers), Mundani (Latn, 34,000 speakers), Igbo (Latn, 27,823,640 speakers), Belarusian (Cyrl, 10,064,517 speakers), Cicipu (Latn, 44,000 speakers), Gulay (Latn, 250,478 speakers), Sar (Latn, 500,000 speakers), Ejagham (Latn, 120,000 speakers), Ma’di (Latn, 584,000 speakers), Vute (Latn, 21,000 speakers), Dan (Latn, 1,099,244 speakers), Nateni (Latn, 100,000 speakers), Ijo, Southeast (Latn, 2,471,000 speakers), Ngbaka (Latn, 1,020,000 speakers), Heiltsuk (Latn, 300 speakers), Koonzime (Latn, 40,000 speakers), Lugbara (Latn, 2,200,000 speakers), Makaa (Latn, 221,000 speakers), Mango (Latn, 77,000 speakers), Navajo (Latn, 166,319 speakers), Han (Latn, 6 speakers), Kom (Latn, 360,685 speakers), Bete-Bendi (Latn, 100,000 speakers), Ekpeye (Latn, 226,000 speakers), Teke-Ebo (Latn, 260,000 speakers), Kaska (Latn, 125 speakers), Aghem (Latn, 38,843 speakers), Kpelle, Guinea (Latn, 622,000 speakers), South Central Banda (Latn, 244,000 speakers), Basaa (Latn, 332,940 speakers), Fur (Latn, 1,230,163 speakers), Ukrainian (Cyrl, 29,273,587 speakers), Avokaya (Latn, 100,000 speakers), Bafut (Latn, 158,146 speakers), Mfumte (Latn, 79,000 speakers), Nzakara (Latn, 50,000 speakers), Southern Kisi (Latn, 360,000 speakers), Ebira (Latn, 2,200,000 speakers), Yala (Latn, 200,000 speakers).</p>
 [code: soft-dotted]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Are there any misaligned on-curve points? <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/outline.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>The following glyphs have on-curve points which have potentially incorrect y coordinates:</p>
<pre><code>* obreve (U+014F): X=253.5,Y=688.0 (should be at cap-height 690?)

* obreve (U+014F): X=392.5,Y=688.0 (should be at cap-height 690?)

* germandbls (U+00DF): X=473.0,Y=688.0 (should be at cap-height 690?)

* t (U+0074): X=293.0,Y=0.5 (should be at baseline 0?)

* tcaron (U+0165): X=293.0,Y=0.5 (should be at baseline 0?)

* uni0163 (U+0163): X=200.0,Y=1.0 (should be at baseline 0?)

* uni0163 (U+0163): X=293.5,Y=0.5 (should be at baseline 0?)

* uni021B (U+021B): X=293.0,Y=0.5 (should be at baseline 0?)

* sterling (U+00A3): X=211.0,Y=691.5 (should be at cap-height 690?)

* sterling (U+00A3): X=437.5,Y=689.0 (should be at cap-height 690?)

* ampersand (U+0026): X=399.0,Y=688.0 (should be at cap-height 690?)

* uni1E9E (U+1E9E): X=473.0,Y=688.0 (should be at cap-height 690?)

* uni20BA (U+20BA): X=208.0,Y=-1.0 (should be at baseline 0?)

* uni0302 (U+0302): X=158.0,Y=688.0 (should be at cap-height 690?)
</code></pre>
 [code: found-misalignments]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Do outlines contain any jaggy segments? <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/outline.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>The following glyphs have jaggy segments:</p>
<pre><code>* eth (U+00F0): B&lt;&lt;432.5,524.5&gt;-&lt;480.0,496.0&gt;-&lt;511.0,443.0&gt;&gt;/B&lt;&lt;511.0,443.0&gt;-&lt;494.0,493.0&gt;-&lt;465.0,544.5&gt;&gt; = 11.545573640104445

* partialdiff (U+2202): B&lt;&lt;400.5,522.5&gt;-&lt;433.0,492.0&gt;-&lt;448.0,438.0&gt;&gt;/B&lt;&lt;448.0,438.0&gt;-&lt;446.0,508.0&gt;-&lt;430.5,566.5&gt;&gt; = 13.887533955137524

* t (U+0074): B&lt;&lt;186.0,567.0&gt;-&lt;176.0,551.0&gt;-&lt;154.0,546.0&gt;&gt;/L&lt;&lt;154.0,546.0&gt;--&lt;312.0,546.0&gt;&gt; = 12.80426606528674

* tcaron (U+0165): B&lt;&lt;186.0,567.0&gt;-&lt;176.0,551.0&gt;-&lt;154.0,546.0&gt;&gt;/L&lt;&lt;154.0,546.0&gt;--&lt;312.0,546.0&gt;&gt; = 12.80426606528674

* uni0163 (U+0163): B&lt;&lt;186.0,567.0&gt;-&lt;176.0,551.0&gt;-&lt;154.0,546.0&gt;&gt;/L&lt;&lt;154.0,546.0&gt;--&lt;312.0,546.0&gt;&gt; = 12.80426606528674

* uni021B (U+021B): B&lt;&lt;186.0,567.0&gt;-&lt;176.0,551.0&gt;-&lt;154.0,546.0&gt;&gt;/L&lt;&lt;154.0,546.0&gt;--&lt;312.0,546.0&gt;&gt; = 12.80426606528674
</code></pre>
 [code: found-jaggy-segments]



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
    <summary>⚠️ <b>WARN</b> Checking OS/2 achVendID. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.os2.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>OS/2 VendorID value 'NONE' is not yet recognized. If you registered it recently, then it's safe to ignore this warning message. Otherwise, you should set it to your own unique 4 character code, and register it with Microsoft at <a href="https://www.microsoft.com/typography/links/vendorlist.aspx">https://www.microsoft.com/typography/links/vendorlist.aspx</a></p>
 [code: unknown]



</div>
</details>
</div>
</details>

<details><summary>[9] Parkinsans-ExtraBold.ttf</summary>
<div>
<details>
    <summary>⚠️ <b>WARN</b> Check if each glyph has the recommended amount of contours. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.</p>
<p>The following glyphs do not have the recommended number of contours:</p>
<pre><code>- Glyph name: liter	Contours detected: 1	Expected: 2

- Glyph name: fi	Contours detected: 2	Expected: 3
</code></pre>
 [code: contour-count]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Validate size, and resolution of article images, and ensure article page has minimum length and includes visual assets. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.article.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>Family metadata at fonts/ttf does not have an article.</p>
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
<li>U+0302 COMBINING CIRCUMFLEX ACCENT: try adding one of: math, cherokee, tifinagh, coptic</li>
<li>U+0306 COMBINING BREVE: try adding one of: tifinagh, old-permic</li>
<li>U+0307 COMBINING DOT ABOVE: try adding one of: tai-le, old-permic, coptic, tifinagh, syriac, hebrew, canadian-aboriginal, todhri, malayalam, duployan, math</li>
<li>U+030A COMBINING RING ABOVE: try adding one of: duployan, syriac</li>
<li>U+030B COMBINING DOUBLE ACUTE ACCENT: try adding one of: osage, cherokee</li>
<li>U+030C COMBINING CARON: try adding one of: tai-le, cherokee</li>
<li>U+0326 COMBINING COMMA BELOW: try adding math</li>
<li>U+0327 COMBINING CEDILLA: try adding math</li>
<li>U+0328 COMBINING OGONEK: not included in any glyphset definition</li>
<li>U+03C0 GREEK SMALL LETTER PI: try adding one of: greek, yi, math</li>
<li>U+1EBC LATIN CAPITAL LETTER E WITH TILDE: try adding vietnamese</li>
<li>U+1EBD LATIN SMALL LETTER E WITH TILDE: try adding vietnamese</li>
<li>U+2021 DOUBLE DAGGER: try adding adlam</li>
<li>U+2030 PER MILLE SIGN: try adding adlam</li>
<li>U+2126 OHM SIGN: try adding math</li>
<li>U+212E ESTIMATED SYMBOL: try adding math</li>
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
<li>U+25CA LOZENGE: try adding one of: math, symbols</li>
<li>U+25CC DOTTED CIRCLE: try adding one of: sinhala, devanagari, saurashtra, duployan, hanifi-rohingya, kannada, tirhuta, soyombo, tai-le, chakma, psalter-pahlavi, sharada, limbu, balinese, cham, rejang, music, coptic, tagalog, tifinagh, elbasan, hebrew, kaithi, armenian, modi, marchen, kayah-li, thaana, lao, siddham, masaram-gondi, nko, warang-citi, syloti-nagri, telugu, new-tai-lue, lepcha, oriya, adlam, grantha, bhaiksuki, osage, buhid, yi, dogra, javanese, gurmukhi, symbols, mongolian, canadian-aboriginal, math, hanunoo, phags-pa, tibetan, thai, caucasian-albanian, gujarati, bassa-vah, takri, batak, zanabazar-square, pahawh-hmong, tai-viet, tagbanwa, tamil, khojki, miao, sogdian, old-permic, manichaean, khudawadi, mende-kikakui, mandaic, kharoshthi, brahmi, wancho, mahajani, ahom, syriac, meetei-mayek, gunjala-gondi, buginese, malayalam, tai-tham, bengali, sundanese, khmer, myanmar, newa</li>
<li>U+FB01 LATIN SMALL LIGATURE FI: not included in any glyphset definition</li>
<li>U+FB02 LATIN SMALL LIGATURE FL: not included in any glyphset definition</li>
</ul>
<p>Or you can add the above codepoints to one of the subsets supported by the font: <code>latin</code>, <code>latin-ext</code></p>
 [code: unreachable-subsetting]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Ensure soft_dotted characters lose their dot when combined with marks that replace the dot. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/shaping.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>The dot of soft dotted characters used in orthographies <em>must</em> disappear in the following strings: i̊ i̋ j̀ j́ j̃ j̄ j̈ į̀ į́ į̂ į̃ į̄ į̌</p>
<p>The dot of soft dotted characters <em>should</em> disappear in other cases, for example: i̇ ǐ i̦̇ i̦̊ i̦̋ ǐ̦ i̧̇ i̧̊ i̧̋ ǐ̧ ĵ j̆ j̇ j̊ j̋ ǰ j̦̀ j̦́ ĵ̦ j̦̃</p>
<p>Your font fully covers the following languages that require the soft-dotted feature: Lithuanian (Latn, 2,357,094 speakers), Dutch (Latn, 31,709,104 speakers).</p>
<p>Your font does <em>not</em> cover the following languages that require the soft-dotted feature: Dii (Latn, 71,000 speakers), Zapotec (Latn, 490,000 speakers), Mundani (Latn, 34,000 speakers), Igbo (Latn, 27,823,640 speakers), Belarusian (Cyrl, 10,064,517 speakers), Cicipu (Latn, 44,000 speakers), Gulay (Latn, 250,478 speakers), Sar (Latn, 500,000 speakers), Ejagham (Latn, 120,000 speakers), Ma’di (Latn, 584,000 speakers), Vute (Latn, 21,000 speakers), Dan (Latn, 1,099,244 speakers), Nateni (Latn, 100,000 speakers), Ijo, Southeast (Latn, 2,471,000 speakers), Ngbaka (Latn, 1,020,000 speakers), Heiltsuk (Latn, 300 speakers), Koonzime (Latn, 40,000 speakers), Lugbara (Latn, 2,200,000 speakers), Makaa (Latn, 221,000 speakers), Mango (Latn, 77,000 speakers), Navajo (Latn, 166,319 speakers), Han (Latn, 6 speakers), Kom (Latn, 360,685 speakers), Bete-Bendi (Latn, 100,000 speakers), Ekpeye (Latn, 226,000 speakers), Teke-Ebo (Latn, 260,000 speakers), Kaska (Latn, 125 speakers), Aghem (Latn, 38,843 speakers), Kpelle, Guinea (Latn, 622,000 speakers), South Central Banda (Latn, 244,000 speakers), Basaa (Latn, 332,940 speakers), Fur (Latn, 1,230,163 speakers), Ukrainian (Cyrl, 29,273,587 speakers), Avokaya (Latn, 100,000 speakers), Bafut (Latn, 158,146 speakers), Mfumte (Latn, 79,000 speakers), Nzakara (Latn, 50,000 speakers), Southern Kisi (Latn, 360,000 speakers), Ebira (Latn, 2,200,000 speakers), Yala (Latn, 200,000 speakers).</p>
 [code: soft-dotted]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Are there any misaligned on-curve points? <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/outline.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>The following glyphs have on-curve points which have potentially incorrect y coordinates:</p>
<pre><code>* Q (U+0051): X=463.0,Y=-1.0 (should be at baseline 0?)

* uni0162 (U+0162): X=248.0,Y=2.0 (should be at baseline 0?)

* uni0162 (U+0162): X=364.0,Y=2.0 (should be at baseline 0?)

* ccedilla (U+00E7): X=250.0,Y=-2.0 (should be at baseline 0?)

* ccedilla (U+00E7): X=366.0,Y=-2.0 (should be at baseline 0?)

* eogonek (U+0119): X=192.5,Y=-2.0 (should be at baseline 0?)

* iogonek (U+012F): X=245.0,Y=-1.0 (should be at baseline 0?)

* scedilla (U+015F): X=347.0,Y=-2.0 (should be at baseline 0?)

* t (U+0074): X=374.5,Y=-0.5 (should be at baseline 0?)

* tcaron (U+0165): X=374.5,Y=-0.5 (should be at baseline 0?)

* uni0163 (U+0163): X=374.5,Y=-0.5 (should be at baseline 0?)

* uni021B (U+021B): X=374.5,Y=-0.5 (should be at baseline 0?)

* ordfeminine (U+00AA): X=304.0,Y=707.0 (should be at cap-height 705?)

* ordfeminine (U+00AA): X=450.0,Y=707.0 (should be at cap-height 705?)

* uni2206 (U+2206): X=297.0,Y=707.0 (should be at cap-height 705?)

* uni2206 (U+2206): X=456.0,Y=707.0 (should be at cap-height 705?)

* asciicircum (U+005E): X=271.0,Y=707.0 (should be at cap-height 705?)

* asciicircum (U+005E): X=464.0,Y=707.0 (should be at cap-height 705?)

* uni0127 (U+0127): X=16.0,Y=704.0 (should be at cap-height 705?)

* uni0127 (U+0127): X=56.0,Y=704.0 (should be at cap-height 705?)

* uni0127 (U+0127): X=252.0,Y=704.0 (should be at cap-height 705?)

* uni0127 (U+0127): X=312.0,Y=704.0 (should be at cap-height 705?)
</code></pre>
 [code: found-misalignments]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Are any segments inordinately short? <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/outline.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>The following glyphs have segments which seem very short:</p>
<pre><code>* oe (U+0153) contains a short segment B&lt;&lt;660.0,199.0&gt;-&lt;650.0,199.0&gt;-&lt;641.0,199.0&gt;&gt;

* oe (U+0153) contains a short segment B&lt;&lt;641.0,199.0&gt;-&lt;632.0,199.0&gt;-&lt;623.0,200.0&gt;&gt;

* germandbls (U+00DF) contains a short segment B&lt;&lt;511.0,396.0&gt;-&lt;511.0,388.0&gt;-&lt;516.5,381.0&gt;&gt;

* uni0163 (U+0163) contains a short segment B&lt;&lt;320.0,-7.0&gt;-&lt;316.0,-7.0&gt;-&lt;312.0,-7.0&gt;&gt;

* fi (U+FB01) contains a short segment L&lt;&lt;93.0,561.0&gt;--&lt;93.0,566.0&gt;&gt;

* fl (U+FB02) contains a short segment L&lt;&lt;74.0,561.0&gt;--&lt;74.0,566.0&gt;&gt;

* Euro (U+20AC) contains a short segment B&lt;&lt;74.0,333.0&gt;-&lt;74.0,343.0&gt;-&lt;74.0,354.0&gt;&gt;

* Euro (U+20AC) contains a short segment B&lt;&lt;74.0,354.0&gt;-&lt;74.0,365.0&gt;-&lt;74.0,375.0&gt;&gt;

* Euro (U+20AC) contains a short segment B&lt;&lt;275.0,375.0&gt;-&lt;274.0,365.0&gt;-&lt;274.0,354.0&gt;&gt;

* Euro (U+20AC) contains a short segment B&lt;&lt;274.0,354.0&gt;-&lt;274.0,343.0&gt;-&lt;275.0,333.0&gt;&gt;

* florin (U+0192) contains a short segment L&lt;&lt;81.0,561.0&gt;--&lt;82.0,574.0&gt;&gt;

* integral (U+222B) contains a short segment L&lt;&lt;337.0,783.0&gt;--&lt;320.0,783.0&gt;&gt;

* integral (U+222B) contains a short segment L&lt;&lt;-38.0,-121.0&gt;--&lt;-21.0,-121.0&gt;&gt;

* uni00B5 (U+00B5) contains a short segment B&lt;&lt;291.0,-5.0&gt;-&lt;281.0,-5.0&gt;-&lt;271.0,-3.0&gt;&gt;

* uni1E9E (U+1E9E) contains a short segment B&lt;&lt;511.0,396.0&gt;-&lt;511.0,388.0&gt;-&lt;516.5,381.0&gt;&gt;
</code></pre>
 [code: found-short-segments]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Do outlines contain any jaggy segments? <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/outline.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>The following glyphs have jaggy segments:</p>
<pre><code>* ordfeminine (U+00AA): L&lt;&lt;304.0,403.0&gt;--&lt;304.0,425.0&gt;&gt;/B&lt;&lt;304.0,425.0&gt;-&lt;294.0,385.0&gt;-&lt;263.0,367.0&gt;&gt; = 14.036243467926484

* r (U+0072): L&lt;&lt;252.0,561.0&gt;--&lt;252.0,420.0&gt;&gt;/B&lt;&lt;252.0,420.0&gt;-&lt;269.0,488.0&gt;-&lt;314.0,527.0&gt;&gt; = 14.036243467926457

* racute (U+0155): L&lt;&lt;252.0,561.0&gt;--&lt;252.0,420.0&gt;&gt;/B&lt;&lt;252.0,420.0&gt;-&lt;269.0,488.0&gt;-&lt;314.0,527.0&gt;&gt; = 14.036243467926457

* rcaron (U+0159): L&lt;&lt;252.0,561.0&gt;--&lt;252.0,420.0&gt;&gt;/B&lt;&lt;252.0,420.0&gt;-&lt;269.0,488.0&gt;-&lt;314.0,527.0&gt;&gt; = 14.036243467926457

* t (U+0074): B&lt;&lt;275.0,579.0&gt;-&lt;260.0,565.0&gt;-&lt;237.0,561.0&gt;&gt;/L&lt;&lt;237.0,561.0&gt;--&lt;404.0,561.0&gt;&gt; = 9.865806943084365

* tcaron (U+0165): B&lt;&lt;275.0,579.0&gt;-&lt;260.0,565.0&gt;-&lt;237.0,561.0&gt;&gt;/L&lt;&lt;237.0,561.0&gt;--&lt;404.0,561.0&gt;&gt; = 9.865806943084365

* uni0157 (U+0157): L&lt;&lt;252.0,561.0&gt;--&lt;252.0,420.0&gt;&gt;/B&lt;&lt;252.0,420.0&gt;-&lt;269.0,488.0&gt;-&lt;314.0,527.0&gt;&gt; = 14.036243467926457

* uni0163 (U+0163): B&lt;&lt;275.0,579.0&gt;-&lt;260.0,565.0&gt;-&lt;237.0,561.0&gt;&gt;/L&lt;&lt;237.0,561.0&gt;--&lt;404.0,561.0&gt;&gt; = 9.865806943084365

* uni021B (U+021B): B&lt;&lt;275.0,579.0&gt;-&lt;260.0,565.0&gt;-&lt;237.0,561.0&gt;&gt;/L&lt;&lt;237.0,561.0&gt;--&lt;404.0,561.0&gt;&gt; = 9.865806943084365

* uogonek (U+0173): L&lt;&lt;433.0,96.0&gt;--&lt;433.0,124.0&gt;&gt;/B&lt;&lt;433.0,124.0&gt;-&lt;418.0,63.0&gt;-&lt;373.5,28.0&gt;&gt; = 13.81502534126161
</code></pre>
 [code: found-jaggy-segments]



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
| 0 | 0 | 0 | 53 | 681 | 43 | 639 | 0 | 
| 0% | 0% | 0% | 4% | 48% | 3% | 45% | 0% | 



**Note:** The following loglevels were omitted in this report:


* SKIP
* INFO
* PASS
* DEBUG
