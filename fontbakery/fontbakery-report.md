## FontBakery report

fontbakery version: 0.12.10





## Check results



<details><summary>[12] Parkinsans-Bold.ttf</summary>
<div>
<details>
    <summary>⚠️ <b>WARN</b> Does GPOS table have kerning information? This check skips monospaced fonts as defined by post.isFixedPitch value <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/opentype.gpos.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>GPOS table lacks kerning information.</p>
 [code: lacks-kern-info]



</div>
</details>

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
    <summary>⚠️ <b>WARN</b> Check math signs have the same width. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>The most common width is 505 among a set of 2 math glyphs.
The following math glyphs have a different width, though:</p>
<p>Width = 589:
plus</p>
<p>Width = 524:
less</p>
<p>Width = 661:
equal</p>
<p>Width = 519:
greater</p>
<p>Width = 748:
logicalnot</p>
<p>Width = 590:
plusminus</p>
<p>Width = 609:
multiply</p>
<p>Width = 581:
divide</p>
<p>Width = 525:
minus</p>
<p>Width = 674:
approxequal</p>
<p>Width = 656:
notequal</p>
 [code: width-outliers]



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
<li>U+0302 COMBINING CIRCUMFLEX ACCENT: try adding one of: cherokee, tifinagh, math, coptic</li>
<li>U+0306 COMBINING BREVE: try adding one of: old-permic, tifinagh</li>
<li>U+0307 COMBINING DOT ABOVE: try adding one of: malayalam, tifinagh, math, coptic, syriac, todhri, duployan, canadian-aboriginal, hebrew, old-permic, tai-le</li>
<li>U+030A COMBINING RING ABOVE: try adding one of: duployan, syriac</li>
<li>U+030B COMBINING DOUBLE ACUTE ACCENT: try adding one of: cherokee, osage</li>
<li>U+030C COMBINING CARON: try adding one of: cherokee, tai-le</li>
<li>U+0326 COMBINING COMMA BELOW: try adding math</li>
<li>U+0327 COMBINING CEDILLA: try adding math</li>
<li>U+0328 COMBINING OGONEK: not included in any glyphset definition</li>
<li>U+03C0 GREEK SMALL LETTER PI: try adding one of: yi, math, greek</li>
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
<li>U+25CA LOZENGE: try adding one of: symbols, math</li>
<li>U+FB01 LATIN SMALL LIGATURE FI: not included in any glyphset definition</li>
<li>U+FB02 LATIN SMALL LIGATURE FL: not included in any glyphset definition</li>
</ul>
<p>Or you can add the above codepoints to one of the subsets supported by the font: <code>latin</code>, <code>latin-ext</code></p>
 [code: unreachable-subsetting]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Ensure dotted circle glyph is present and can attach marks. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/shaping.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>No dotted circle glyph present</p>
 [code: missing-dotted-circle]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Ensure soft_dotted characters lose their dot when combined with marks that replace the dot. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/shaping.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>The dot of soft dotted characters used in orthographies <em>must</em> disappear in the following strings: i̊ i̋ j̀ j́ j̃ j̄ j̈ į̀ į́ į̂ į̃ į̄ į̌</p>
<p>The dot of soft dotted characters <em>should</em> disappear in other cases, for example: i̇ ǐ i̦̇ i̦̊ i̦̋ ǐ̦ i̧̇ i̧̊ i̧̋ ǐ̧ ĵ j̆ j̇ j̊ j̋ ǰ j̦̀ j̦́ ĵ̦ j̦̃</p>
<p>Your font fully covers the following languages that require the soft-dotted feature: Lithuanian (Latn, 2,357,094 speakers), Dutch (Latn, 31,709,104 speakers).</p>
<p>Your font does <em>not</em> cover the following languages that require the soft-dotted feature: Ejagham (Latn, 120,000 speakers), Zapotec (Latn, 490,000 speakers), Nzakara (Latn, 50,000 speakers), Kaska (Latn, 125 speakers), Mundani (Latn, 34,000 speakers), Sar (Latn, 500,000 speakers), Bafut (Latn, 158,146 speakers), Dii (Latn, 71,000 speakers), Lugbara (Latn, 2,200,000 speakers), Yala (Latn, 200,000 speakers), Koonzime (Latn, 40,000 speakers), Ma’di (Latn, 584,000 speakers), Ebira (Latn, 2,200,000 speakers), Fur (Latn, 1,230,163 speakers), Aghem (Latn, 38,843 speakers), Ukrainian (Cyrl, 29,273,587 speakers), Vute (Latn, 21,000 speakers), Han (Latn, 6 speakers), Basaa (Latn, 332,940 speakers), Ijo, Southeast (Latn, 2,471,000 speakers), Kom (Latn, 360,685 speakers), Dan (Latn, 1,099,244 speakers), Belarusian (Cyrl, 10,064,517 speakers), Igbo (Latn, 27,823,640 speakers), Avokaya (Latn, 100,000 speakers), Gulay (Latn, 250,478 speakers), Mfumte (Latn, 79,000 speakers), South Central Banda (Latn, 244,000 speakers), Bete-Bendi (Latn, 100,000 speakers), Heiltsuk (Latn, 300 speakers), Kpelle, Guinea (Latn, 622,000 speakers), Ngbaka (Latn, 1,020,000 speakers), Teke-Ebo (Latn, 260,000 speakers), Mango (Latn, 77,000 speakers), Makaa (Latn, 221,000 speakers), Nateni (Latn, 100,000 speakers), Navajo (Latn, 166,319 speakers), Cicipu (Latn, 44,000 speakers), Southern Kisi (Latn, 360,000 speakers), Ekpeye (Latn, 226,000 speakers).</p>
 [code: soft-dotted]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Are there any misaligned on-curve points? <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/outline.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>The following glyphs have on-curve points which have potentially incorrect y coordinates:</p>
<pre><code>* Oslash (U+00D8): X=130.0,Y=1.0 (should be at baseline 0?)

* Oslash (U+00D8): X=20.0,Y=1.0 (should be at baseline 0?)

* Q (U+0051): X=464.0,Y=-1.0 (should be at baseline 0?)

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
<pre><code>* Uogonek (U+0172) contains a short segment B&lt;&lt;326.0,-85.0&gt;-&lt;326.0,-97.0&gt;-&lt;336.5,-104.5&gt;&gt;

* ae (U+00E6) contains a short segment B&lt;&lt;730.0,199.0&gt;-&lt;720.0,199.0&gt;-&lt;711.0,199.0&gt;&gt;

* ae (U+00E6) contains a short segment B&lt;&lt;711.0,199.0&gt;-&lt;702.0,199.0&gt;-&lt;693.0,200.0&gt;&gt;

* aeacute (U+01FD) contains a short segment B&lt;&lt;730.0,199.0&gt;-&lt;720.0,199.0&gt;-&lt;711.0,199.0&gt;&gt;

* aeacute (U+01FD) contains a short segment B&lt;&lt;711.0,199.0&gt;-&lt;702.0,199.0&gt;-&lt;693.0,200.0&gt;&gt;

* eogonek (U+0119) contains a short segment B&lt;&lt;242.0,205.0&gt;-&lt;232.0,205.0&gt;-&lt;224.0,205.0&gt;&gt;

* f (U+0066) contains a short segment L&lt;&lt;74.0,561.0&gt;--&lt;74.0,566.0&gt;&gt;

* oe (U+0153) contains a short segment B&lt;&lt;660.0,199.0&gt;-&lt;650.0,199.0&gt;-&lt;641.0,199.0&gt;&gt;

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

* u (U+0075): L&lt;&lt;433.0,96.0&gt;--&lt;433.0,124.0&gt;&gt;/B&lt;&lt;433.0,124.0&gt;-&lt;418.0,63.0&gt;-&lt;373.5,28.0&gt;&gt; = 13.81502534126161

* uacute (U+00FA): L&lt;&lt;433.0,96.0&gt;--&lt;433.0,124.0&gt;&gt;/B&lt;&lt;433.0,124.0&gt;-&lt;418.0,63.0&gt;-&lt;373.5,28.0&gt;&gt; = 13.81502534126161

* ubreve (U+016D): L&lt;&lt;433.0,96.0&gt;--&lt;433.0,124.0&gt;&gt;/B&lt;&lt;433.0,124.0&gt;-&lt;418.0,63.0&gt;-&lt;373.5,28.0&gt;&gt; = 13.81502534126161

* ucircumflex (U+00FB): L&lt;&lt;433.0,96.0&gt;--&lt;433.0,124.0&gt;&gt;/B&lt;&lt;433.0,124.0&gt;-&lt;418.0,63.0&gt;-&lt;373.5,28.0&gt;&gt; = 13.81502534126161

* udieresis (U+00FC): L&lt;&lt;433.0,96.0&gt;--&lt;433.0,124.0&gt;&gt;/B&lt;&lt;433.0,124.0&gt;-&lt;418.0,63.0&gt;-&lt;373.5,28.0&gt;&gt; = 13.81502534126161

* ugrave (U+00F9): L&lt;&lt;433.0,96.0&gt;--&lt;433.0,124.0&gt;&gt;/B&lt;&lt;433.0,124.0&gt;-&lt;418.0,63.0&gt;-&lt;373.5,28.0&gt;&gt; = 13.81502534126161

* uhungarumlaut (U+0171): L&lt;&lt;433.0,96.0&gt;--&lt;433.0,124.0&gt;&gt;/B&lt;&lt;433.0,124.0&gt;-&lt;418.0,63.0&gt;-&lt;373.5,28.0&gt;&gt; = 13.81502534126161

* umacron (U+016B): L&lt;&lt;433.0,96.0&gt;--&lt;433.0,124.0&gt;&gt;/B&lt;&lt;433.0,124.0&gt;-&lt;418.0,63.0&gt;-&lt;373.5,28.0&gt;&gt; = 13.81502534126161

* uni0157 (U+0157): L&lt;&lt;252.0,561.0&gt;--&lt;252.0,420.0&gt;&gt;/B&lt;&lt;252.0,420.0&gt;-&lt;269.0,488.0&gt;-&lt;314.0,527.0&gt;&gt; = 14.036243467926457

* uni0163 (U+0163): B&lt;&lt;275.0,579.0&gt;-&lt;260.0,565.0&gt;-&lt;237.0,561.0&gt;&gt;/L&lt;&lt;237.0,561.0&gt;--&lt;404.0,561.0&gt;&gt; = 9.865806943084365

* uni021B (U+021B): B&lt;&lt;275.0,579.0&gt;-&lt;260.0,565.0&gt;-&lt;237.0,561.0&gt;&gt;/L&lt;&lt;237.0,561.0&gt;--&lt;404.0,561.0&gt;&gt; = 9.865806943084365

* uni1EF9 (U+1EF9): L&lt;&lt;418.0,32.0&gt;--&lt;418.0,135.0&gt;&gt;/B&lt;&lt;418.0,135.0&gt;-&lt;406.0,78.0&gt;-&lt;365.0,41.0&gt;&gt; = 11.888658039627968

* uogonek (U+0173): L&lt;&lt;433.0,96.0&gt;--&lt;433.0,124.0&gt;&gt;/B&lt;&lt;433.0,124.0&gt;-&lt;418.0,63.0&gt;-&lt;373.5,28.0&gt;&gt; = 13.81502534126161

* uring (U+016F): L&lt;&lt;433.0,96.0&gt;--&lt;433.0,124.0&gt;&gt;/B&lt;&lt;433.0,124.0&gt;-&lt;418.0,63.0&gt;-&lt;373.5,28.0&gt;&gt; = 13.81502534126161

* utilde (U+0169): L&lt;&lt;433.0,96.0&gt;--&lt;433.0,124.0&gt;&gt;/B&lt;&lt;433.0,124.0&gt;-&lt;418.0,63.0&gt;-&lt;373.5,28.0&gt;&gt; = 13.81502534126161

* y (U+0079): L&lt;&lt;418.0,32.0&gt;--&lt;418.0,135.0&gt;&gt;/B&lt;&lt;418.0,135.0&gt;-&lt;406.0,78.0&gt;-&lt;365.0,41.0&gt;&gt; = 11.888658039627968

* yacute (U+00FD): L&lt;&lt;418.0,32.0&gt;--&lt;418.0,135.0&gt;&gt;/B&lt;&lt;418.0,135.0&gt;-&lt;406.0,78.0&gt;-&lt;365.0,41.0&gt;&gt; = 11.888658039627968

* ycircumflex (U+0177): L&lt;&lt;418.0,32.0&gt;--&lt;418.0,135.0&gt;&gt;/B&lt;&lt;418.0,135.0&gt;-&lt;406.0,78.0&gt;-&lt;365.0,41.0&gt;&gt; = 11.888658039627968

* ydieresis (U+00FF): L&lt;&lt;418.0,32.0&gt;--&lt;418.0,135.0&gt;&gt;/B&lt;&lt;418.0,135.0&gt;-&lt;406.0,78.0&gt;-&lt;365.0,41.0&gt;&gt; = 11.888658039627968

* ygrave (U+1EF3): L&lt;&lt;418.0,32.0&gt;--&lt;418.0,135.0&gt;&gt;/B&lt;&lt;418.0,135.0&gt;-&lt;406.0,78.0&gt;-&lt;365.0,41.0&gt;&gt; = 11.888658039627968
</code></pre>
 [code: found-jaggy-segments]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Do outlines contain any semi-vertical or semi-horizontal lines? <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/outline.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>The following glyphs have semi-vertical/semi-horizontal lines:</p>
<pre><code>* trademark (U+2122): L&lt;&lt;112.0,355.0&gt;--&lt;113.0,592.0&gt;&gt;
</code></pre>
 [code: found-semi-vertical]



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

<details><summary>[14] Parkinsans-Semibold.ttf</summary>
<div>
<details>
    <summary>🔥 <b>FAIL</b> Check font names are correct <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.name.html#"></a></summary>
    <div>







* 🔥 **FAIL** <p>Font names are incorrect:</p>
<table>
<thead>
<tr>
<th align="left">nameID</th>
<th align="left">current</th>
<th align="left">expected</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">Family Name</td>
<td align="left">Parkinsans Semibold</td>
<td align="left">Parkinsans Semibold</td>
</tr>
<tr>
<td align="left">Subfamily Name</td>
<td align="left">Regular</td>
<td align="left">Regular</td>
</tr>
<tr>
<td align="left">Full Name</td>
<td align="left"><strong>Parkinsans Semibold</strong></td>
<td align="left"><strong>Parkinsans Semibold Regular</strong></td>
</tr>
<tr>
<td align="left">Postscript Name</td>
<td align="left">ParkinsansSemibold-Regular</td>
<td align="left">ParkinsansSemibold-Regular</td>
</tr>
<tr>
<td align="left">Typographic Family Name</td>
<td align="left"><strong>Parkinsans</strong></td>
<td align="left"><strong>N/A</strong></td>
</tr>
<tr>
<td align="left">Typographic Subfamily Name</td>
<td align="left"><strong>Semibold</strong></td>
<td align="left"><strong>N/A</strong></td>
</tr>
</tbody>
</table>
 [code: bad-names]



* ⚠️ **WARN** <p>Regular missing from full name</p>
 [code: lacks-regular]



</div>
</details>

<details>
    <summary>🔥 <b>FAIL</b> Check the OS/2 usWeightClass is appropriate for the font's best SubFamily name. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.os2.html#"></a></summary>
    <div>







* 🔥 **FAIL** <p>Best SubFamily name is 'Semibold'. Expected OS/2 usWeightClass is 400, got 592.</p>
 [code: bad-value]



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
    <summary>⚠️ <b>WARN</b> Check math signs have the same width. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>The most common width is 557 among a set of 2 math glyphs.
The following math glyphs have a different width, though:</p>
<p>Width = 656:
plus</p>
<p>Width = 571:
less</p>
<p>Width = 722:
equal</p>
<p>Width = 695:
logicalnot</p>
<p>Width = 658:
plusminus</p>
<p>Width = 657:
multiply</p>
<p>Width = 634:
divide</p>
<p>Width = 609:
approxequal</p>
<p>Width = 707:
notequal</p>
<p>Width = 529:
greaterequal, lessequal</p>
 [code: width-outliers]



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
<li>U+0302 COMBINING CIRCUMFLEX ACCENT: try adding one of: cherokee, tifinagh, math, coptic</li>
<li>U+0306 COMBINING BREVE: try adding one of: old-permic, tifinagh</li>
<li>U+0307 COMBINING DOT ABOVE: try adding one of: malayalam, tifinagh, math, coptic, syriac, todhri, duployan, canadian-aboriginal, hebrew, old-permic, tai-le</li>
<li>U+030A COMBINING RING ABOVE: try adding one of: duployan, syriac</li>
<li>U+030B COMBINING DOUBLE ACUTE ACCENT: try adding one of: cherokee, osage</li>
<li>U+030C COMBINING CARON: try adding one of: cherokee, tai-le</li>
<li>U+0326 COMBINING COMMA BELOW: try adding math</li>
<li>U+0327 COMBINING CEDILLA: try adding math</li>
<li>U+0328 COMBINING OGONEK: not included in any glyphset definition</li>
<li>U+03C0 GREEK SMALL LETTER PI: try adding one of: yi, math, greek</li>
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
<li>U+25CA LOZENGE: try adding one of: symbols, math</li>
<li>U+FB01 LATIN SMALL LIGATURE FI: not included in any glyphset definition</li>
<li>U+FB02 LATIN SMALL LIGATURE FL: not included in any glyphset definition</li>
</ul>
<p>Or you can add the above codepoints to one of the subsets supported by the font: <code>latin</code>, <code>latin-ext</code></p>
 [code: unreachable-subsetting]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Ensure dotted circle glyph is present and can attach marks. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/shaping.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>No dotted circle glyph present</p>
 [code: missing-dotted-circle]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Ensure soft_dotted characters lose their dot when combined with marks that replace the dot. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/shaping.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>The dot of soft dotted characters used in orthographies <em>must</em> disappear in the following strings: i̊ i̋ j̀ j́ j̃ j̄ j̈ į̀ į́ į̂ į̃ į̄ į̌</p>
<p>The dot of soft dotted characters <em>should</em> disappear in other cases, for example: i̇ ǐ i̦̇ i̦̊ i̦̋ ǐ̦ i̧̇ i̧̊ i̧̋ ǐ̧ ĵ j̆ j̇ j̊ j̋ ǰ j̦̀ j̦́ ĵ̦ j̦̃</p>
<p>Your font fully covers the following languages that require the soft-dotted feature: Lithuanian (Latn, 2,357,094 speakers), Dutch (Latn, 31,709,104 speakers).</p>
<p>Your font does <em>not</em> cover the following languages that require the soft-dotted feature: Ejagham (Latn, 120,000 speakers), Zapotec (Latn, 490,000 speakers), Nzakara (Latn, 50,000 speakers), Kaska (Latn, 125 speakers), Mundani (Latn, 34,000 speakers), Sar (Latn, 500,000 speakers), Bafut (Latn, 158,146 speakers), Dii (Latn, 71,000 speakers), Lugbara (Latn, 2,200,000 speakers), Yala (Latn, 200,000 speakers), Koonzime (Latn, 40,000 speakers), Ma’di (Latn, 584,000 speakers), Ebira (Latn, 2,200,000 speakers), Fur (Latn, 1,230,163 speakers), Aghem (Latn, 38,843 speakers), Ukrainian (Cyrl, 29,273,587 speakers), Vute (Latn, 21,000 speakers), Han (Latn, 6 speakers), Basaa (Latn, 332,940 speakers), Ijo, Southeast (Latn, 2,471,000 speakers), Kom (Latn, 360,685 speakers), Dan (Latn, 1,099,244 speakers), Belarusian (Cyrl, 10,064,517 speakers), Igbo (Latn, 27,823,640 speakers), Avokaya (Latn, 100,000 speakers), Gulay (Latn, 250,478 speakers), Mfumte (Latn, 79,000 speakers), South Central Banda (Latn, 244,000 speakers), Bete-Bendi (Latn, 100,000 speakers), Heiltsuk (Latn, 300 speakers), Kpelle, Guinea (Latn, 622,000 speakers), Ngbaka (Latn, 1,020,000 speakers), Teke-Ebo (Latn, 260,000 speakers), Mango (Latn, 77,000 speakers), Makaa (Latn, 221,000 speakers), Nateni (Latn, 100,000 speakers), Navajo (Latn, 166,319 speakers), Cicipu (Latn, 44,000 speakers), Southern Kisi (Latn, 360,000 speakers), Ekpeye (Latn, 226,000 speakers).</p>
 [code: soft-dotted]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Are there any misaligned on-curve points? <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/outline.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>The following glyphs have on-curve points which have potentially incorrect y coordinates:</p>
<pre><code>* Iogonek (U+012E): X=290.0,Y=1.0 (should be at baseline 0?)

* Q (U+0051): X=478.0,Y=2.0 (should be at baseline 0?)

* Uogonek (U+0172): X=426.0,Y=1.0 (should be at baseline 0?)

* W (U+0057): X=208.0,Y=-1.0 (should be at baseline 0?)

* Wacute (U+1E82): X=208.0,Y=-1.0 (should be at baseline 0?)

* Wcircumflex (U+0174): X=208.0,Y=-1.0 (should be at baseline 0?)

* Wdieresis (U+1E84): X=208.0,Y=-1.0 (should be at baseline 0?)

* Wgrave (U+1E80): X=208.0,Y=-1.0 (should be at baseline 0?)

* aacute (U+00E1): X=451.0,Y=698.0 (should be at cap-height 700?)

* aacute (U+00E1): X=217.0,Y=701.0 (should be at cap-height 700?)

* agrave (U+00E0): X=451.0,Y=701.0 (should be at cap-height 700?)

* agrave (U+00E0): X=217.0,Y=698.0 (should be at cap-height 700?)

* atilde (U+00E3): X=407.0,Y=699.0 (should be at cap-height 700?)

* aeacute (U+01FD): X=692.0,Y=698.0 (should be at cap-height 700?)

* aeacute (U+01FD): X=458.0,Y=701.0 (should be at cap-height 700?)

* cacute (U+0107): X=177.0,Y=701.0 (should be at cap-height 700?)

* cacute (U+0107): X=411.0,Y=698.0 (should be at cap-height 700?)

* eacute (U+00E9): X=424.0,Y=698.0 (should be at cap-height 700?)

* eacute (U+00E9): X=190.0,Y=701.0 (should be at cap-height 700?)

* egrave (U+00E8): X=424.0,Y=701.0 (should be at cap-height 700?)

* egrave (U+00E8): X=190.0,Y=698.0 (should be at cap-height 700?)

* uni1EBD (U+1EBD): X=380.0,Y=699.0 (should be at cap-height 700?)

* f (U+0066): X=114.5,Y=701.5 (should be at cap-height 700?)

* iacute (U+00ED): X=263.0,Y=698.0 (should be at cap-height 700?)

* iacute (U+00ED): X=29.0,Y=701.0 (should be at cap-height 700?)

* igrave (U+00EC): X=263.0,Y=701.0 (should be at cap-height 700?)

* igrave (U+00EC): X=29.0,Y=698.0 (should be at cap-height 700?)

* itilde (U+0129): X=219.0,Y=699.0 (should be at cap-height 700?)

* ldot (U+0140): X=271.0,Y=-2.0 (should be at baseline 0?)

* lslash (U+0142): X=279.5,Y=-2.0 (should be at baseline 0?)

* nacute (U+0144): X=445.0,Y=698.0 (should be at cap-height 700?)

* nacute (U+0144): X=211.0,Y=701.0 (should be at cap-height 700?)

* ntilde (U+00F1): X=401.0,Y=699.0 (should be at cap-height 700?)

* racute (U+0155): X=364.0,Y=698.0 (should be at cap-height 700?)

* racute (U+0155): X=130.0,Y=701.0 (should be at cap-height 700?)

* scaron (U+0161): X=277.0,Y=701.0 (should be at cap-height 700?)

* uni0163 (U+0163): X=348.0,Y=1.5 (should be at baseline 0?)

* uacute (U+00FA): X=445.0,Y=698.0 (should be at cap-height 700?)

* uacute (U+00FA): X=211.0,Y=701.0 (should be at cap-height 700?)

* ugrave (U+00F9): X=445.0,Y=701.0 (should be at cap-height 700?)

* ugrave (U+00F9): X=211.0,Y=698.0 (should be at cap-height 700?)

* utilde (U+0169): X=401.0,Y=699.0 (should be at cap-height 700?)

* wacute (U+1E83): X=578.0,Y=698.0 (should be at cap-height 700?)

* wacute (U+1E83): X=344.0,Y=701.0 (should be at cap-height 700?)

* wgrave (U+1E81): X=512.0,Y=701.0 (should be at cap-height 700?)

* wgrave (U+1E81): X=278.0,Y=698.0 (should be at cap-height 700?)

* yacute (U+00FD): X=426.0,Y=698.0 (should be at cap-height 700?)

* yacute (U+00FD): X=192.0,Y=701.0 (should be at cap-height 700?)

* ygrave (U+1EF3): X=426.0,Y=701.0 (should be at cap-height 700?)

* ygrave (U+1EF3): X=192.0,Y=698.0 (should be at cap-height 700?)

* uni1EF9 (U+1EF9): X=382.0,Y=699.0 (should be at cap-height 700?)

* zacute (U+017A): X=358.0,Y=698.0 (should be at cap-height 700?)

* zacute (U+017A): X=124.0,Y=701.0 (should be at cap-height 700?)

* fi (U+FB01): X=136.5,Y=701.5 (should be at cap-height 700?)

* fl (U+FB02): X=114.5,Y=701.5 (should be at cap-height 700?)

* uni2206 (U+2206): X=299.0,Y=701.0 (should be at cap-height 700?)

* uni2206 (U+2206): X=423.0,Y=701.0 (should be at cap-height 700?)

* partialdiff (U+2202): X=454.0,Y=698.5 (should be at cap-height 700?)

* asciicircum (U+005E): X=272.0,Y=701.0 (should be at cap-height 700?)

* asciicircum (U+005E): X=420.0,Y=701.0 (should be at cap-height 700?)

* acute (U+00B4): X=244.0,Y=698.0 (should be at cap-height 700?)

* acute (U+00B4): X=10.0,Y=701.0 (should be at cap-height 700?)

* grave (U+0060): X=244.0,Y=701.0 (should be at cap-height 700?)

* grave (U+0060): X=10.0,Y=698.0 (should be at cap-height 700?)

* tilde (U+02DC): X=262.0,Y=699.0 (should be at cap-height 700?)

* uni0300 (U+0300): X=244.0,Y=701.0 (should be at cap-height 700?)

* uni0300 (U+0300): X=10.0,Y=698.0 (should be at cap-height 700?)

* uni0301 (U+0301): X=244.0,Y=698.0 (should be at cap-height 700?)

* uni0301 (U+0301): X=10.0,Y=701.0 (should be at cap-height 700?)

* uni0303 (U+0303): X=262.0,Y=699.0 (should be at cap-height 700?)
</code></pre>
 [code: found-misalignments]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Are any segments inordinately short? <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/outline.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>The following glyphs have segments which seem very short:</p>
<pre><code>* ae (U+00E6) contains a short segment B&lt;&lt;691.0,201.5&gt;-&lt;674.0,202.0&gt;-&lt;669.0,203.0&gt;&gt;

* aeacute (U+01FD) contains a short segment B&lt;&lt;691.0,201.5&gt;-&lt;674.0,202.0&gt;-&lt;669.0,203.0&gt;&gt;

* germandbls (U+00DF) contains a short segment B&lt;&lt;450.0,393.0&gt;-&lt;450.0,383.0&gt;-&lt;457.0,374.5&gt;&gt;

* uni0163 (U+0163) contains a short segment B&lt;&lt;288.0,-8.0&gt;-&lt;283.0,-8.0&gt;-&lt;278.0,-7.0&gt;&gt;

* parenleft (U+0028) contains a short segment L&lt;&lt;469.0,920.0&gt;--&lt;469.0,906.0&gt;&gt;

* parenright (U+0029) contains a short segment L&lt;&lt;26.0,-201.0&gt;--&lt;26.0,-187.0&gt;&gt;

* integral (U+222B) contains a short segment L&lt;&lt;321.0,808.0&gt;--&lt;305.0,808.0&gt;&gt;

* ampersand (U+0026) contains a short segment B&lt;&lt;515.0,267.0&gt;-&lt;519.0,274.0&gt;-&lt;523.0,281.0&gt;&gt;

* paragraph (U+00B6) contains a short segment L&lt;&lt;288.0,276.0&gt;--&lt;268.0,276.0&gt;&gt;

* uni1E9E (U+1E9E) contains a short segment B&lt;&lt;450.0,393.0&gt;-&lt;450.0,383.0&gt;-&lt;457.0,374.5&gt;&gt;
</code></pre>
 [code: found-short-segments]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Do outlines contain any jaggy segments? <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/outline.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>The following glyphs have jaggy segments:</p>
<pre><code>* t (U+0074): B&lt;&lt;247.5,584.0&gt;-&lt;231.0,561.0&gt;-&lt;203.0,556.0&gt;&gt;/L&lt;&lt;203.0,556.0&gt;--&lt;381.0,556.0&gt;&gt; = 10.124671655397806

* tcaron (U+0165): B&lt;&lt;247.5,584.0&gt;-&lt;231.0,561.0&gt;-&lt;203.0,556.0&gt;&gt;/L&lt;&lt;203.0,556.0&gt;--&lt;381.0,556.0&gt;&gt; = 10.124671655397806

* u (U+0075): L&lt;&lt;447.0,79.0&gt;--&lt;447.0,117.0&gt;&gt;/B&lt;&lt;447.0,117.0&gt;-&lt;434.0,64.0&gt;-&lt;386.0,28.5&gt;&gt; = 13.78159723565362

* uacute (U+00FA): L&lt;&lt;447.0,79.0&gt;--&lt;447.0,117.0&gt;&gt;/B&lt;&lt;447.0,117.0&gt;-&lt;434.0,64.0&gt;-&lt;386.0,28.5&gt;&gt; = 13.78159723565362

* ubreve (U+016D): L&lt;&lt;447.0,79.0&gt;--&lt;447.0,117.0&gt;&gt;/B&lt;&lt;447.0,117.0&gt;-&lt;434.0,64.0&gt;-&lt;386.0,28.5&gt;&gt; = 13.78159723565362

* ucircumflex (U+00FB): L&lt;&lt;447.0,79.0&gt;--&lt;447.0,117.0&gt;&gt;/B&lt;&lt;447.0,117.0&gt;-&lt;434.0,64.0&gt;-&lt;386.0,28.5&gt;&gt; = 13.78159723565362

* udieresis (U+00FC): L&lt;&lt;447.0,79.0&gt;--&lt;447.0,117.0&gt;&gt;/B&lt;&lt;447.0,117.0&gt;-&lt;434.0,64.0&gt;-&lt;386.0,28.5&gt;&gt; = 13.78159723565362

* ugrave (U+00F9): L&lt;&lt;447.0,79.0&gt;--&lt;447.0,117.0&gt;&gt;/B&lt;&lt;447.0,117.0&gt;-&lt;434.0,64.0&gt;-&lt;386.0,28.5&gt;&gt; = 13.78159723565362

* uhungarumlaut (U+0171): L&lt;&lt;447.0,79.0&gt;--&lt;447.0,117.0&gt;&gt;/B&lt;&lt;447.0,117.0&gt;-&lt;434.0,64.0&gt;-&lt;386.0,28.5&gt;&gt; = 13.78159723565362

* umacron (U+016B): L&lt;&lt;447.0,79.0&gt;--&lt;447.0,117.0&gt;&gt;/B&lt;&lt;447.0,117.0&gt;-&lt;434.0,64.0&gt;-&lt;386.0,28.5&gt;&gt; = 13.78159723565362

* uni0163 (U+0163): B&lt;&lt;247.5,584.0&gt;-&lt;231.0,561.0&gt;-&lt;203.0,556.0&gt;&gt;/L&lt;&lt;203.0,556.0&gt;--&lt;382.0,556.0&gt;&gt; = 10.124671655397806

* uni021B (U+021B): B&lt;&lt;247.5,584.0&gt;-&lt;231.0,561.0&gt;-&lt;203.0,556.0&gt;&gt;/L&lt;&lt;203.0,556.0&gt;--&lt;381.0,556.0&gt;&gt; = 10.124671655397806

* uni1EF9 (U+1EF9): L&lt;&lt;434.0,11.0&gt;--&lt;434.0,128.0&gt;&gt;/B&lt;&lt;434.0,128.0&gt;-&lt;426.0,94.0&gt;-&lt;402.0,66.0&gt;&gt; = 13.240519915187184

* uogonek (U+0173): L&lt;&lt;447.0,79.0&gt;--&lt;447.0,117.0&gt;&gt;/B&lt;&lt;447.0,117.0&gt;-&lt;434.0,64.0&gt;-&lt;386.0,28.5&gt;&gt; = 13.78159723565362

* uring (U+016F): L&lt;&lt;447.0,79.0&gt;--&lt;447.0,117.0&gt;&gt;/B&lt;&lt;447.0,117.0&gt;-&lt;434.0,64.0&gt;-&lt;386.0,28.5&gt;&gt; = 13.78159723565362

* utilde (U+0169): L&lt;&lt;447.0,79.0&gt;--&lt;447.0,117.0&gt;&gt;/B&lt;&lt;447.0,117.0&gt;-&lt;434.0,64.0&gt;-&lt;386.0,28.5&gt;&gt; = 13.78159723565362

* y (U+0079): L&lt;&lt;434.0,11.0&gt;--&lt;434.0,128.0&gt;&gt;/B&lt;&lt;434.0,128.0&gt;-&lt;426.0,94.0&gt;-&lt;402.0,66.0&gt;&gt; = 13.240519915187184

* yacute (U+00FD): L&lt;&lt;434.0,11.0&gt;--&lt;434.0,128.0&gt;&gt;/B&lt;&lt;434.0,128.0&gt;-&lt;426.0,94.0&gt;-&lt;402.0,66.0&gt;&gt; = 13.240519915187184

* ycircumflex (U+0177): L&lt;&lt;434.0,11.0&gt;--&lt;434.0,128.0&gt;&gt;/B&lt;&lt;434.0,128.0&gt;-&lt;426.0,94.0&gt;-&lt;402.0,66.0&gt;&gt; = 13.240519915187184

* ydieresis (U+00FF): L&lt;&lt;434.0,11.0&gt;--&lt;434.0,128.0&gt;&gt;/B&lt;&lt;434.0,128.0&gt;-&lt;426.0,94.0&gt;-&lt;402.0,66.0&gt;&gt; = 13.240519915187184

* ygrave (U+1EF3): L&lt;&lt;434.0,11.0&gt;--&lt;434.0,128.0&gt;&gt;/B&lt;&lt;434.0,128.0&gt;-&lt;426.0,94.0&gt;-&lt;402.0,66.0&gt;&gt; = 13.240519915187184
</code></pre>
 [code: found-jaggy-segments]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Do outlines contain any semi-vertical or semi-horizontal lines? <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/outline.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>The following glyphs have semi-vertical/semi-horizontal lines:</p>
<pre><code>* W (U+0057): L&lt;&lt;388.0,0.0&gt;--&lt;208.0,-1.0&gt;&gt;

* Wacute (U+1E82): L&lt;&lt;388.0,0.0&gt;--&lt;208.0,-1.0&gt;&gt;

* Wcircumflex (U+0174): L&lt;&lt;388.0,0.0&gt;--&lt;208.0,-1.0&gt;&gt;

* Wdieresis (U+1E84): L&lt;&lt;388.0,0.0&gt;--&lt;208.0,-1.0&gt;&gt;

* Wgrave (U+1E80): L&lt;&lt;388.0,0.0&gt;--&lt;208.0,-1.0&gt;&gt;

* trademark (U+2122): L&lt;&lt;106.0,349.0&gt;--&lt;108.0,611.0&gt;&gt;

* trademark (U+2122): L&lt;&lt;218.0,611.0&gt;--&lt;219.0,349.0&gt;&gt;

* yen (U+00A5): L&lt;&lt;212.0,310.0&gt;--&lt;48.0,311.0&gt;&gt;

* yen (U+00A5): L&lt;&lt;601.0,311.0&gt;--&lt;438.0,310.0&gt;&gt;
</code></pre>
 [code: found-semi-vertical]



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

<details><summary>[12] Parkinsans-Medium.ttf</summary>
<div>
<details>
    <summary>⚠️ <b>WARN</b> Does GPOS table have kerning information? This check skips monospaced fonts as defined by post.isFixedPitch value <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/opentype.gpos.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>GPOS table lacks kerning information.</p>
 [code: lacks-kern-info]



</div>
</details>

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
    <summary>⚠️ <b>WARN</b> Check math signs have the same width. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>The most common width is 549 among a set of 2 math glyphs.
The following math glyphs have a different width, though:</p>
<p>Width = 714:
plus</p>
<p>Width = 612:
less</p>
<p>Width = 774:
equal</p>
<p>Width = 590:
greater</p>
<p>Width = 649:
logicalnot</p>
<p>Width = 717:
plusminus</p>
<p>Width = 699:
multiply</p>
<p>Width = 679:
divide</p>
<p>Width = 585:
minus</p>
<p>Width = 553:
approxequal</p>
<p>Width = 752:
notequal</p>
 [code: width-outliers]



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
<li>U+0302 COMBINING CIRCUMFLEX ACCENT: try adding one of: cherokee, tifinagh, math, coptic</li>
<li>U+0306 COMBINING BREVE: try adding one of: old-permic, tifinagh</li>
<li>U+0307 COMBINING DOT ABOVE: try adding one of: malayalam, tifinagh, math, coptic, syriac, todhri, duployan, canadian-aboriginal, hebrew, old-permic, tai-le</li>
<li>U+030A COMBINING RING ABOVE: try adding one of: duployan, syriac</li>
<li>U+030B COMBINING DOUBLE ACUTE ACCENT: try adding one of: cherokee, osage</li>
<li>U+030C COMBINING CARON: try adding one of: cherokee, tai-le</li>
<li>U+0326 COMBINING COMMA BELOW: try adding math</li>
<li>U+0327 COMBINING CEDILLA: try adding math</li>
<li>U+0328 COMBINING OGONEK: not included in any glyphset definition</li>
<li>U+03C0 GREEK SMALL LETTER PI: try adding one of: yi, math, greek</li>
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
<li>U+25CA LOZENGE: try adding one of: symbols, math</li>
<li>U+FB01 LATIN SMALL LIGATURE FI: not included in any glyphset definition</li>
<li>U+FB02 LATIN SMALL LIGATURE FL: not included in any glyphset definition</li>
</ul>
<p>Or you can add the above codepoints to one of the subsets supported by the font: <code>latin</code>, <code>latin-ext</code></p>
 [code: unreachable-subsetting]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Ensure dotted circle glyph is present and can attach marks. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/shaping.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>No dotted circle glyph present</p>
 [code: missing-dotted-circle]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Ensure soft_dotted characters lose their dot when combined with marks that replace the dot. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/shaping.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>The dot of soft dotted characters used in orthographies <em>must</em> disappear in the following strings: i̊ i̋ j̀ j́ j̃ j̄ j̈ į̀ į́ į̂ į̃ į̄ į̌</p>
<p>The dot of soft dotted characters <em>should</em> disappear in other cases, for example: i̇ ǐ i̦̇ i̦̊ i̦̋ ǐ̦ i̧̇ i̧̊ i̧̋ ǐ̧ ĵ j̆ j̇ j̊ j̋ ǰ j̦̀ j̦́ ĵ̦ j̦̃</p>
<p>Your font fully covers the following languages that require the soft-dotted feature: Lithuanian (Latn, 2,357,094 speakers), Dutch (Latn, 31,709,104 speakers).</p>
<p>Your font does <em>not</em> cover the following languages that require the soft-dotted feature: Ejagham (Latn, 120,000 speakers), Zapotec (Latn, 490,000 speakers), Nzakara (Latn, 50,000 speakers), Kaska (Latn, 125 speakers), Mundani (Latn, 34,000 speakers), Sar (Latn, 500,000 speakers), Bafut (Latn, 158,146 speakers), Dii (Latn, 71,000 speakers), Lugbara (Latn, 2,200,000 speakers), Yala (Latn, 200,000 speakers), Koonzime (Latn, 40,000 speakers), Ma’di (Latn, 584,000 speakers), Ebira (Latn, 2,200,000 speakers), Fur (Latn, 1,230,163 speakers), Aghem (Latn, 38,843 speakers), Ukrainian (Cyrl, 29,273,587 speakers), Vute (Latn, 21,000 speakers), Han (Latn, 6 speakers), Basaa (Latn, 332,940 speakers), Ijo, Southeast (Latn, 2,471,000 speakers), Kom (Latn, 360,685 speakers), Dan (Latn, 1,099,244 speakers), Belarusian (Cyrl, 10,064,517 speakers), Igbo (Latn, 27,823,640 speakers), Avokaya (Latn, 100,000 speakers), Gulay (Latn, 250,478 speakers), Mfumte (Latn, 79,000 speakers), South Central Banda (Latn, 244,000 speakers), Bete-Bendi (Latn, 100,000 speakers), Heiltsuk (Latn, 300 speakers), Kpelle, Guinea (Latn, 622,000 speakers), Ngbaka (Latn, 1,020,000 speakers), Teke-Ebo (Latn, 260,000 speakers), Mango (Latn, 77,000 speakers), Makaa (Latn, 221,000 speakers), Nateni (Latn, 100,000 speakers), Navajo (Latn, 166,319 speakers), Cicipu (Latn, 44,000 speakers), Southern Kisi (Latn, 360,000 speakers), Ekpeye (Latn, 226,000 speakers).</p>
 [code: soft-dotted]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Are there any misaligned on-curve points? <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/outline.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>The following glyphs have on-curve points which have potentially incorrect y coordinates:</p>
<pre><code>* Iogonek (U+012E): X=258.0,Y=1.0 (should be at baseline 0?)

* W (U+0057): X=216.0,Y=-1.0 (should be at baseline 0?)

* Wacute (U+1E82): X=216.0,Y=-1.0 (should be at baseline 0?)

* Wcircumflex (U+0174): X=216.0,Y=-1.0 (should be at baseline 0?)

* Wdieresis (U+1E84): X=216.0,Y=-1.0 (should be at baseline 0?)

* Wgrave (U+1E80): X=216.0,Y=-1.0 (should be at baseline 0?)

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

* fi (U+FB01): X=408.0,Y=697.0 (should be at cap-height 695?)

* fi (U+FB01): X=553.0,Y=697.0 (should be at cap-height 695?)

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

* parenleft (U+0028) contains a short segment L&lt;&lt;465.0,934.0&gt;--&lt;465.0,923.0&gt;&gt;

* parenright (U+0029) contains a short segment L&lt;&lt;47.0,-186.0&gt;--&lt;47.0,-175.0&gt;&gt;

* florin (U+0192) contains a short segment L&lt;&lt;-46.0,-123.0&gt;--&lt;-30.0,-123.0&gt;&gt;

* paragraph (U+00B6) contains a short segment L&lt;&lt;286.0,282.0&gt;--&lt;272.0,282.0&gt;&gt;

* uni20B9 (U+20B9) contains a short segment B&lt;&lt;367.0,524.0&gt;-&lt;367.0,531.0&gt;-&lt;367.0,538.0&gt;&gt;

* uni20B9 (U+20B9) contains a short segment B&lt;&lt;474.0,538.0&gt;-&lt;474.0,530.0&gt;-&lt;474.0,524.0&gt;&gt;
</code></pre>
 [code: found-short-segments]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Do outlines contain any jaggy segments? <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/outline.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>The following glyphs have jaggy segments:</p>
<pre><code>* G (U+0047): L&lt;&lt;635.0,0.0&gt;--&lt;635.0,164.0&gt;&gt;/B&lt;&lt;635.0,164.0&gt;-&lt;632.0,149.0&gt;-&lt;615.0,121.0&gt;&gt; = 11.309932474020195

* Gbreve (U+011E): L&lt;&lt;635.0,0.0&gt;--&lt;635.0,164.0&gt;&gt;/B&lt;&lt;635.0,164.0&gt;-&lt;632.0,149.0&gt;-&lt;615.0,121.0&gt;&gt; = 11.309932474020195

* Gdotaccent (U+0120): L&lt;&lt;635.0,0.0&gt;--&lt;635.0,164.0&gt;&gt;/B&lt;&lt;635.0,164.0&gt;-&lt;632.0,149.0&gt;-&lt;615.0,121.0&gt;&gt; = 11.309932474020195

* t (U+0074): B&lt;&lt;212.5,575.0&gt;-&lt;197.0,556.0&gt;-&lt;174.0,551.0&gt;&gt;/L&lt;&lt;174.0,551.0&gt;--&lt;362.0,551.0&gt;&gt; = 12.2647737278924

* tcaron (U+0165): B&lt;&lt;212.5,575.0&gt;-&lt;197.0,556.0&gt;-&lt;174.0,551.0&gt;&gt;/L&lt;&lt;174.0,551.0&gt;--&lt;362.0,551.0&gt;&gt; = 12.2647737278924

* uni0122 (U+0122): L&lt;&lt;635.0,0.0&gt;--&lt;635.0,164.0&gt;&gt;/B&lt;&lt;635.0,164.0&gt;-&lt;632.0,149.0&gt;-&lt;615.0,121.0&gt;&gt; = 11.309932474020195

* uni0163 (U+0163): B&lt;&lt;212.5,575.0&gt;-&lt;197.0,556.0&gt;-&lt;174.0,551.0&gt;&gt;/L&lt;&lt;174.0,551.0&gt;--&lt;362.0,551.0&gt;&gt; = 12.2647737278924

* uni021B (U+021B): B&lt;&lt;212.5,575.0&gt;-&lt;197.0,556.0&gt;-&lt;174.0,551.0&gt;&gt;/L&lt;&lt;174.0,551.0&gt;--&lt;362.0,551.0&gt;&gt; = 12.2647737278924
</code></pre>
 [code: found-jaggy-segments]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Do outlines contain any semi-vertical or semi-horizontal lines? <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/outline.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>The following glyphs have semi-vertical/semi-horizontal lines:</p>
<pre><code>* W (U+0057): L&lt;&lt;344.0,0.0&gt;--&lt;216.0,-1.0&gt;&gt;

* Wacute (U+1E82): L&lt;&lt;344.0,0.0&gt;--&lt;216.0,-1.0&gt;&gt;

* Wcircumflex (U+0174): L&lt;&lt;344.0,0.0&gt;--&lt;216.0,-1.0&gt;&gt;

* Wdieresis (U+1E84): L&lt;&lt;344.0,0.0&gt;--&lt;216.0,-1.0&gt;&gt;

* Wgrave (U+1E80): L&lt;&lt;344.0,0.0&gt;--&lt;216.0,-1.0&gt;&gt;

* trademark (U+2122): L&lt;&lt;101.0,343.0&gt;--&lt;103.0,627.0&gt;&gt;

* trademark (U+2122): L&lt;&lt;190.0,627.0&gt;--&lt;191.0,343.0&gt;&gt;

* trademark (U+2122): L&lt;&lt;668.0,343.0&gt;--&lt;666.0,581.0&gt;&gt;
</code></pre>
 [code: found-semi-vertical]



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

<details><summary>[13] Parkinsans-Regular.ttf</summary>
<div>
<details>
    <summary>🔥 <b>FAIL</b> Check the OS/2 usWeightClass is appropriate for the font's best SubFamily name. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.os2.html#"></a></summary>
    <div>







* 🔥 **FAIL** <p>Best SubFamily name is 'Regular'. Expected OS/2 usWeightClass is 400, got 395.</p>
 [code: bad-value]



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
    <summary>⚠️ <b>WARN</b> Check math signs have the same width. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>The most common width is 511 among a set of 2 math glyphs.
The following math glyphs have a different width, though:</p>
<p>Width = 683:
plus</p>
<p>Width = 556:
less</p>
<p>Width = 723:
equal</p>
<p>Width = 539:
greater</p>
<p>Width = 650:
logicalnot</p>
<p>Width = 686:
plusminus</p>
<p>Width = 643:
multiply</p>
<p>Width = 657:
divide</p>
<p>Width = 551:
minus</p>
<p>Width = 519:
approxequal</p>
<p>Width = 706:
notequal</p>
 [code: width-outliers]



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
<li>U+0302 COMBINING CIRCUMFLEX ACCENT: try adding one of: cherokee, tifinagh, math, coptic</li>
<li>U+0306 COMBINING BREVE: try adding one of: old-permic, tifinagh</li>
<li>U+0307 COMBINING DOT ABOVE: try adding one of: malayalam, tifinagh, math, coptic, syriac, todhri, duployan, canadian-aboriginal, hebrew, old-permic, tai-le</li>
<li>U+030A COMBINING RING ABOVE: try adding one of: duployan, syriac</li>
<li>U+030B COMBINING DOUBLE ACUTE ACCENT: try adding one of: cherokee, osage</li>
<li>U+030C COMBINING CARON: try adding one of: cherokee, tai-le</li>
<li>U+0326 COMBINING COMMA BELOW: try adding math</li>
<li>U+0327 COMBINING CEDILLA: try adding math</li>
<li>U+0328 COMBINING OGONEK: not included in any glyphset definition</li>
<li>U+03C0 GREEK SMALL LETTER PI: try adding one of: yi, math, greek</li>
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
<li>U+25CA LOZENGE: try adding one of: symbols, math</li>
<li>U+FB01 LATIN SMALL LIGATURE FI: not included in any glyphset definition</li>
<li>U+FB02 LATIN SMALL LIGATURE FL: not included in any glyphset definition</li>
</ul>
<p>Or you can add the above codepoints to one of the subsets supported by the font: <code>latin</code>, <code>latin-ext</code></p>
 [code: unreachable-subsetting]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Ensure dotted circle glyph is present and can attach marks. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/shaping.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>No dotted circle glyph present</p>
 [code: missing-dotted-circle]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Ensure soft_dotted characters lose their dot when combined with marks that replace the dot. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/shaping.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>The dot of soft dotted characters used in orthographies <em>must</em> disappear in the following strings: i̊ i̋ j̀ j́ j̃ j̄ j̈ į̀ į́ į̂ į̃ į̄ į̌</p>
<p>The dot of soft dotted characters <em>should</em> disappear in other cases, for example: i̇ ǐ i̦̇ i̦̊ i̦̋ ǐ̦ i̧̇ i̧̊ i̧̋ ǐ̧ ĵ j̆ j̇ j̊ j̋ ǰ j̦̀ j̦́ ĵ̦ j̦̃</p>
<p>Your font fully covers the following languages that require the soft-dotted feature: Lithuanian (Latn, 2,357,094 speakers), Dutch (Latn, 31,709,104 speakers).</p>
<p>Your font does <em>not</em> cover the following languages that require the soft-dotted feature: Ejagham (Latn, 120,000 speakers), Zapotec (Latn, 490,000 speakers), Nzakara (Latn, 50,000 speakers), Kaska (Latn, 125 speakers), Mundani (Latn, 34,000 speakers), Sar (Latn, 500,000 speakers), Bafut (Latn, 158,146 speakers), Dii (Latn, 71,000 speakers), Lugbara (Latn, 2,200,000 speakers), Yala (Latn, 200,000 speakers), Koonzime (Latn, 40,000 speakers), Ma’di (Latn, 584,000 speakers), Ebira (Latn, 2,200,000 speakers), Fur (Latn, 1,230,163 speakers), Aghem (Latn, 38,843 speakers), Ukrainian (Cyrl, 29,273,587 speakers), Vute (Latn, 21,000 speakers), Han (Latn, 6 speakers), Basaa (Latn, 332,940 speakers), Ijo, Southeast (Latn, 2,471,000 speakers), Kom (Latn, 360,685 speakers), Dan (Latn, 1,099,244 speakers), Belarusian (Cyrl, 10,064,517 speakers), Igbo (Latn, 27,823,640 speakers), Avokaya (Latn, 100,000 speakers), Gulay (Latn, 250,478 speakers), Mfumte (Latn, 79,000 speakers), South Central Banda (Latn, 244,000 speakers), Bete-Bendi (Latn, 100,000 speakers), Heiltsuk (Latn, 300 speakers), Kpelle, Guinea (Latn, 622,000 speakers), Ngbaka (Latn, 1,020,000 speakers), Teke-Ebo (Latn, 260,000 speakers), Mango (Latn, 77,000 speakers), Makaa (Latn, 221,000 speakers), Nateni (Latn, 100,000 speakers), Navajo (Latn, 166,319 speakers), Cicipu (Latn, 44,000 speakers), Southern Kisi (Latn, 360,000 speakers), Ekpeye (Latn, 226,000 speakers).</p>
 [code: soft-dotted]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Are there any misaligned on-curve points? <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/outline.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>The following glyphs have on-curve points which have potentially incorrect y coordinates:</p>
<pre><code>* .notdef: X=84.0,Y=690.0 (should be at cap-height 692?)

* .notdef: X=229.0,Y=690.0 (should be at cap-height 692?)

* Iogonek (U+012E): X=229.0,Y=1.0 (should be at baseline 0?)

* Scedilla (U+015E): X=275.0,Y=2.0 (should be at baseline 0?)

* Scedilla (U+015E): X=336.0,Y=2.0 (should be at baseline 0?)

* W (U+0057): X=218.0,Y=-1.0 (should be at baseline 0?)

* Wacute (U+1E82): X=218.0,Y=-1.0 (should be at baseline 0?)

* Wcircumflex (U+0174): X=218.0,Y=-1.0 (should be at baseline 0?)

* Wdieresis (U+1E84): X=218.0,Y=-1.0 (should be at baseline 0?)

* Wgrave (U+1E80): X=218.0,Y=-1.0 (should be at baseline 0?)

* abreve (U+0103): X=270.0,Y=693.5 (should be at cap-height 692?)

* abreve (U+0103): X=407.0,Y=693.5 (should be at cap-height 692?)

* ebreve (U+0115): X=249.0,Y=693.5 (should be at cap-height 692?)

* ebreve (U+0115): X=386.0,Y=693.5 (should be at cap-height 692?)

* gbreve (U+011F): X=270.0,Y=693.5 (should be at cap-height 692?)

* gbreve (U+011F): X=407.0,Y=693.5 (should be at cap-height 692?)

* ibreve (U+012D): X=55.0,Y=693.5 (should be at cap-height 692?)

* ibreve (U+012D): X=192.0,Y=693.5 (should be at cap-height 692?)

* iogonek (U+012F): X=173.0,Y=1.0 (should be at baseline 0?)

* otilde (U+00F5): X=208.0,Y=691.0 (should be at cap-height 692?)

* germandbls (U+00DF): X=294.0,Y=694.0 (should be at cap-height 692?)

* ubreve (U+016D): X=252.0,Y=693.5 (should be at cap-height 692?)

* ubreve (U+016D): X=389.0,Y=693.5 (should be at cap-height 692?)

* uogonek (U+0173): X=563.0,Y=-1.0 (should be at baseline 0?)

* cent (U+00A2): X=346.0,Y=2.0 (should be at baseline 0?)

* florin (U+0192): X=317.0,Y=691.0 (should be at cap-height 692?)

* sterling (U+00A3): X=442.0,Y=693.5 (should be at cap-height 692?)

* uni2206 (U+2206): X=302.0,Y=693.0 (should be at cap-height 692?)

* uni2206 (U+2206): X=378.0,Y=693.0 (should be at cap-height 692?)

* section (U+00A7): X=171.0,Y=690.5 (should be at cap-height 692?)

* asciicircum (U+005E): X=272.0,Y=693.0 (should be at cap-height 692?)

* asciicircum (U+005E): X=357.0,Y=693.0 (should be at cap-height 692?)

* breve (U+02D8): X=91.0,Y=693.5 (should be at cap-height 692?)

* breve (U+02D8): X=228.0,Y=693.5 (should be at cap-height 692?)

* uni1E9E (U+1E9E): X=294.0,Y=694.0 (should be at cap-height 692?)

* uni0306 (U+0306): X=91.0,Y=693.5 (should be at cap-height 692?)

* uni0306 (U+0306): X=228.0,Y=693.5 (should be at cap-height 692?)
</code></pre>
 [code: found-misalignments]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Are any segments inordinately short? <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/outline.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>The following glyphs have segments which seem very short:</p>
<pre><code>* uni0163 (U+0163) contains a short segment B&lt;&lt;253.0,-7.0&gt;-&lt;251.0,-7.0&gt;-&lt;249.0,-7.0&gt;&gt;

* uogonek (U+0173) contains a short segment L&lt;&lt;563.0,0.0&gt;--&lt;563.0,0.0&gt;&gt;

* uogonek (U+0173) contains a short segment L&lt;&lt;563.0,0.0&gt;--&lt;563.0,-1.0&gt;&gt;

* parenleft (U+0028) contains a short segment L&lt;&lt;421.0,934.0&gt;--&lt;421.0,925.0&gt;&gt;

* parenright (U+0029) contains a short segment L&lt;&lt;49.0,-186.0&gt;--&lt;49.0,-177.0&gt;&gt;

* paragraph (U+00B6) contains a short segment L&lt;&lt;279.0,286.0&gt;--&lt;268.0,286.0&gt;&gt;

* uni20B9 (U+20B9) contains a short segment B&lt;&lt;380.0,523.0&gt;-&lt;381.0,531.0&gt;-&lt;381.0,541.0&gt;&gt;

* uni20B9 (U+20B9) contains a short segment B&lt;&lt;466.0,541.0&gt;-&lt;466.0,532.0&gt;-&lt;466.0,523.0&gt;&gt;
</code></pre>
 [code: found-short-segments]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Do outlines contain any jaggy segments? <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/outline.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>The following glyphs have jaggy segments:</p>
<pre><code>* t (U+0074): B&lt;&lt;198.5,570.5&gt;-&lt;186.0,553.0&gt;-&lt;164.0,548.0&gt;&gt;/L&lt;&lt;164.0,548.0&gt;--&lt;336.0,548.0&gt;&gt; = 12.80426606528674

* tcaron (U+0165): B&lt;&lt;198.5,570.5&gt;-&lt;186.0,553.0&gt;-&lt;164.0,548.0&gt;&gt;/L&lt;&lt;164.0,548.0&gt;--&lt;336.0,548.0&gt;&gt; = 12.80426606528674

* uni0163 (U+0163): B&lt;&lt;198.5,570.5&gt;-&lt;186.0,553.0&gt;-&lt;164.0,548.0&gt;&gt;/L&lt;&lt;164.0,548.0&gt;--&lt;336.0,548.0&gt;&gt; = 12.80426606528674

* uni021B (U+021B): B&lt;&lt;198.5,570.5&gt;-&lt;186.0,553.0&gt;-&lt;164.0,548.0&gt;&gt;/L&lt;&lt;164.0,548.0&gt;--&lt;336.0,548.0&gt;&gt; = 12.80426606528674
</code></pre>
 [code: found-jaggy-segments]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Do outlines contain any semi-vertical or semi-horizontal lines? <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/outline.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>The following glyphs have semi-vertical/semi-horizontal lines:</p>
<pre><code>* trademark (U+2122): L&lt;&lt;109.0,340.0&gt;--&lt;111.0,636.0&gt;&gt;

* trademark (U+2122): L&lt;&lt;182.0,636.0&gt;--&lt;183.0,340.0&gt;&gt;

* trademark (U+2122): L&lt;&lt;659.0,340.0&gt;--&lt;657.0,595.0&gt;&gt;
</code></pre>
 [code: found-semi-vertical]



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

<details><summary>[13] Parkinsans-Extrabold.ttf</summary>
<div>
<details>
    <summary>🔥 <b>FAIL</b> Check font names are correct <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.name.html#"></a></summary>
    <div>







* 🔥 **FAIL** <p>Font names are incorrect:</p>
<table>
<thead>
<tr>
<th align="left">nameID</th>
<th align="left">current</th>
<th align="left">expected</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">Family Name</td>
<td align="left">Parkinsans Extrabold</td>
<td align="left">Parkinsans Extrabold</td>
</tr>
<tr>
<td align="left">Subfamily Name</td>
<td align="left">Regular</td>
<td align="left">Regular</td>
</tr>
<tr>
<td align="left">Full Name</td>
<td align="left"><strong>Parkinsans Extrabold</strong></td>
<td align="left"><strong>Parkinsans Extrabold Regular</strong></td>
</tr>
<tr>
<td align="left">Postscript Name</td>
<td align="left">ParkinsansExtrabold-Regular</td>
<td align="left">ParkinsansExtrabold-Regular</td>
</tr>
<tr>
<td align="left">Typographic Family Name</td>
<td align="left"><strong>Parkinsans</strong></td>
<td align="left"><strong>N/A</strong></td>
</tr>
<tr>
<td align="left">Typographic Subfamily Name</td>
<td align="left"><strong>Extrabold</strong></td>
<td align="left"><strong>N/A</strong></td>
</tr>
</tbody>
</table>
 [code: bad-names]



* ⚠️ **WARN** <p>Regular missing from full name</p>
 [code: lacks-regular]



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
    <summary>⚠️ <b>WARN</b> Check math signs have the same width. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>The most common width is 505 among a set of 2 math glyphs.
The following math glyphs have a different width, though:</p>
<p>Width = 589:
plus</p>
<p>Width = 524:
less</p>
<p>Width = 661:
equal</p>
<p>Width = 519:
greater</p>
<p>Width = 748:
logicalnot</p>
<p>Width = 590:
plusminus</p>
<p>Width = 609:
multiply</p>
<p>Width = 581:
divide</p>
<p>Width = 525:
minus</p>
<p>Width = 674:
approxequal</p>
<p>Width = 656:
notequal</p>
 [code: width-outliers]



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
<li>U+0302 COMBINING CIRCUMFLEX ACCENT: try adding one of: cherokee, tifinagh, math, coptic</li>
<li>U+0306 COMBINING BREVE: try adding one of: old-permic, tifinagh</li>
<li>U+0307 COMBINING DOT ABOVE: try adding one of: malayalam, tifinagh, math, coptic, syriac, todhri, duployan, canadian-aboriginal, hebrew, old-permic, tai-le</li>
<li>U+030A COMBINING RING ABOVE: try adding one of: duployan, syriac</li>
<li>U+030B COMBINING DOUBLE ACUTE ACCENT: try adding one of: cherokee, osage</li>
<li>U+030C COMBINING CARON: try adding one of: cherokee, tai-le</li>
<li>U+0326 COMBINING COMMA BELOW: try adding math</li>
<li>U+0327 COMBINING CEDILLA: try adding math</li>
<li>U+0328 COMBINING OGONEK: not included in any glyphset definition</li>
<li>U+03C0 GREEK SMALL LETTER PI: try adding one of: yi, math, greek</li>
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
<li>U+25CA LOZENGE: try adding one of: symbols, math</li>
<li>U+FB01 LATIN SMALL LIGATURE FI: not included in any glyphset definition</li>
<li>U+FB02 LATIN SMALL LIGATURE FL: not included in any glyphset definition</li>
</ul>
<p>Or you can add the above codepoints to one of the subsets supported by the font: <code>latin</code>, <code>latin-ext</code></p>
 [code: unreachable-subsetting]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Ensure dotted circle glyph is present and can attach marks. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/shaping.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>No dotted circle glyph present</p>
 [code: missing-dotted-circle]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Ensure soft_dotted characters lose their dot when combined with marks that replace the dot. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/shaping.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>The dot of soft dotted characters used in orthographies <em>must</em> disappear in the following strings: i̊ i̋ j̀ j́ j̃ j̄ j̈ į̀ į́ į̂ į̃ į̄ į̌</p>
<p>The dot of soft dotted characters <em>should</em> disappear in other cases, for example: i̇ ǐ i̦̇ i̦̊ i̦̋ ǐ̦ i̧̇ i̧̊ i̧̋ ǐ̧ ĵ j̆ j̇ j̊ j̋ ǰ j̦̀ j̦́ ĵ̦ j̦̃</p>
<p>Your font fully covers the following languages that require the soft-dotted feature: Lithuanian (Latn, 2,357,094 speakers), Dutch (Latn, 31,709,104 speakers).</p>
<p>Your font does <em>not</em> cover the following languages that require the soft-dotted feature: Ejagham (Latn, 120,000 speakers), Zapotec (Latn, 490,000 speakers), Nzakara (Latn, 50,000 speakers), Kaska (Latn, 125 speakers), Mundani (Latn, 34,000 speakers), Sar (Latn, 500,000 speakers), Bafut (Latn, 158,146 speakers), Dii (Latn, 71,000 speakers), Lugbara (Latn, 2,200,000 speakers), Yala (Latn, 200,000 speakers), Koonzime (Latn, 40,000 speakers), Ma’di (Latn, 584,000 speakers), Ebira (Latn, 2,200,000 speakers), Fur (Latn, 1,230,163 speakers), Aghem (Latn, 38,843 speakers), Ukrainian (Cyrl, 29,273,587 speakers), Vute (Latn, 21,000 speakers), Han (Latn, 6 speakers), Basaa (Latn, 332,940 speakers), Ijo, Southeast (Latn, 2,471,000 speakers), Kom (Latn, 360,685 speakers), Dan (Latn, 1,099,244 speakers), Belarusian (Cyrl, 10,064,517 speakers), Igbo (Latn, 27,823,640 speakers), Avokaya (Latn, 100,000 speakers), Gulay (Latn, 250,478 speakers), Mfumte (Latn, 79,000 speakers), South Central Banda (Latn, 244,000 speakers), Bete-Bendi (Latn, 100,000 speakers), Heiltsuk (Latn, 300 speakers), Kpelle, Guinea (Latn, 622,000 speakers), Ngbaka (Latn, 1,020,000 speakers), Teke-Ebo (Latn, 260,000 speakers), Mango (Latn, 77,000 speakers), Makaa (Latn, 221,000 speakers), Nateni (Latn, 100,000 speakers), Navajo (Latn, 166,319 speakers), Cicipu (Latn, 44,000 speakers), Southern Kisi (Latn, 360,000 speakers), Ekpeye (Latn, 226,000 speakers).</p>
 [code: soft-dotted]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Are there any misaligned on-curve points? <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/outline.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>The following glyphs have on-curve points which have potentially incorrect y coordinates:</p>
<pre><code>* Oslash (U+00D8): X=130.0,Y=1.0 (should be at baseline 0?)

* Oslash (U+00D8): X=20.0,Y=1.0 (should be at baseline 0?)

* Q (U+0051): X=464.0,Y=-1.0 (should be at baseline 0?)

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
<pre><code>* Uogonek (U+0172) contains a short segment B&lt;&lt;326.0,-85.0&gt;-&lt;326.0,-97.0&gt;-&lt;336.5,-104.5&gt;&gt;

* ae (U+00E6) contains a short segment B&lt;&lt;730.0,199.0&gt;-&lt;720.0,199.0&gt;-&lt;711.0,199.0&gt;&gt;

* ae (U+00E6) contains a short segment B&lt;&lt;711.0,199.0&gt;-&lt;702.0,199.0&gt;-&lt;693.0,200.0&gt;&gt;

* aeacute (U+01FD) contains a short segment B&lt;&lt;730.0,199.0&gt;-&lt;720.0,199.0&gt;-&lt;711.0,199.0&gt;&gt;

* aeacute (U+01FD) contains a short segment B&lt;&lt;711.0,199.0&gt;-&lt;702.0,199.0&gt;-&lt;693.0,200.0&gt;&gt;

* eogonek (U+0119) contains a short segment B&lt;&lt;242.0,205.0&gt;-&lt;232.0,205.0&gt;-&lt;224.0,205.0&gt;&gt;

* f (U+0066) contains a short segment L&lt;&lt;74.0,561.0&gt;--&lt;74.0,566.0&gt;&gt;

* oe (U+0153) contains a short segment B&lt;&lt;660.0,199.0&gt;-&lt;650.0,199.0&gt;-&lt;641.0,199.0&gt;&gt;

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

* u (U+0075): L&lt;&lt;433.0,96.0&gt;--&lt;433.0,124.0&gt;&gt;/B&lt;&lt;433.0,124.0&gt;-&lt;418.0,63.0&gt;-&lt;373.5,28.0&gt;&gt; = 13.81502534126161

* uacute (U+00FA): L&lt;&lt;433.0,96.0&gt;--&lt;433.0,124.0&gt;&gt;/B&lt;&lt;433.0,124.0&gt;-&lt;418.0,63.0&gt;-&lt;373.5,28.0&gt;&gt; = 13.81502534126161

* ubreve (U+016D): L&lt;&lt;433.0,96.0&gt;--&lt;433.0,124.0&gt;&gt;/B&lt;&lt;433.0,124.0&gt;-&lt;418.0,63.0&gt;-&lt;373.5,28.0&gt;&gt; = 13.81502534126161

* ucircumflex (U+00FB): L&lt;&lt;433.0,96.0&gt;--&lt;433.0,124.0&gt;&gt;/B&lt;&lt;433.0,124.0&gt;-&lt;418.0,63.0&gt;-&lt;373.5,28.0&gt;&gt; = 13.81502534126161

* udieresis (U+00FC): L&lt;&lt;433.0,96.0&gt;--&lt;433.0,124.0&gt;&gt;/B&lt;&lt;433.0,124.0&gt;-&lt;418.0,63.0&gt;-&lt;373.5,28.0&gt;&gt; = 13.81502534126161

* ugrave (U+00F9): L&lt;&lt;433.0,96.0&gt;--&lt;433.0,124.0&gt;&gt;/B&lt;&lt;433.0,124.0&gt;-&lt;418.0,63.0&gt;-&lt;373.5,28.0&gt;&gt; = 13.81502534126161

* uhungarumlaut (U+0171): L&lt;&lt;433.0,96.0&gt;--&lt;433.0,124.0&gt;&gt;/B&lt;&lt;433.0,124.0&gt;-&lt;418.0,63.0&gt;-&lt;373.5,28.0&gt;&gt; = 13.81502534126161

* umacron (U+016B): L&lt;&lt;433.0,96.0&gt;--&lt;433.0,124.0&gt;&gt;/B&lt;&lt;433.0,124.0&gt;-&lt;418.0,63.0&gt;-&lt;373.5,28.0&gt;&gt; = 13.81502534126161

* uni0157 (U+0157): L&lt;&lt;252.0,561.0&gt;--&lt;252.0,420.0&gt;&gt;/B&lt;&lt;252.0,420.0&gt;-&lt;269.0,488.0&gt;-&lt;314.0,527.0&gt;&gt; = 14.036243467926457

* uni0163 (U+0163): B&lt;&lt;275.0,579.0&gt;-&lt;260.0,565.0&gt;-&lt;237.0,561.0&gt;&gt;/L&lt;&lt;237.0,561.0&gt;--&lt;404.0,561.0&gt;&gt; = 9.865806943084365

* uni021B (U+021B): B&lt;&lt;275.0,579.0&gt;-&lt;260.0,565.0&gt;-&lt;237.0,561.0&gt;&gt;/L&lt;&lt;237.0,561.0&gt;--&lt;404.0,561.0&gt;&gt; = 9.865806943084365

* uni1EF9 (U+1EF9): L&lt;&lt;418.0,32.0&gt;--&lt;418.0,135.0&gt;&gt;/B&lt;&lt;418.0,135.0&gt;-&lt;406.0,78.0&gt;-&lt;365.0,41.0&gt;&gt; = 11.888658039627968

* uogonek (U+0173): L&lt;&lt;433.0,96.0&gt;--&lt;433.0,124.0&gt;&gt;/B&lt;&lt;433.0,124.0&gt;-&lt;418.0,63.0&gt;-&lt;373.5,28.0&gt;&gt; = 13.81502534126161

* uring (U+016F): L&lt;&lt;433.0,96.0&gt;--&lt;433.0,124.0&gt;&gt;/B&lt;&lt;433.0,124.0&gt;-&lt;418.0,63.0&gt;-&lt;373.5,28.0&gt;&gt; = 13.81502534126161

* utilde (U+0169): L&lt;&lt;433.0,96.0&gt;--&lt;433.0,124.0&gt;&gt;/B&lt;&lt;433.0,124.0&gt;-&lt;418.0,63.0&gt;-&lt;373.5,28.0&gt;&gt; = 13.81502534126161

* y (U+0079): L&lt;&lt;418.0,32.0&gt;--&lt;418.0,135.0&gt;&gt;/B&lt;&lt;418.0,135.0&gt;-&lt;406.0,78.0&gt;-&lt;365.0,41.0&gt;&gt; = 11.888658039627968

* yacute (U+00FD): L&lt;&lt;418.0,32.0&gt;--&lt;418.0,135.0&gt;&gt;/B&lt;&lt;418.0,135.0&gt;-&lt;406.0,78.0&gt;-&lt;365.0,41.0&gt;&gt; = 11.888658039627968

* ycircumflex (U+0177): L&lt;&lt;418.0,32.0&gt;--&lt;418.0,135.0&gt;&gt;/B&lt;&lt;418.0,135.0&gt;-&lt;406.0,78.0&gt;-&lt;365.0,41.0&gt;&gt; = 11.888658039627968

* ydieresis (U+00FF): L&lt;&lt;418.0,32.0&gt;--&lt;418.0,135.0&gt;&gt;/B&lt;&lt;418.0,135.0&gt;-&lt;406.0,78.0&gt;-&lt;365.0,41.0&gt;&gt; = 11.888658039627968

* ygrave (U+1EF3): L&lt;&lt;418.0,32.0&gt;--&lt;418.0,135.0&gt;&gt;/B&lt;&lt;418.0,135.0&gt;-&lt;406.0,78.0&gt;-&lt;365.0,41.0&gt;&gt; = 11.888658039627968
</code></pre>
 [code: found-jaggy-segments]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Do outlines contain any semi-vertical or semi-horizontal lines? <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/outline.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>The following glyphs have semi-vertical/semi-horizontal lines:</p>
<pre><code>* trademark (U+2122): L&lt;&lt;112.0,355.0&gt;--&lt;113.0,592.0&gt;&gt;
</code></pre>
 [code: found-semi-vertical]



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

<details><summary>[12] Parkinsans-Light.ttf</summary>
<div>
<details>
    <summary>⚠️ <b>WARN</b> Does GPOS table have kerning information? This check skips monospaced fonts as defined by post.isFixedPitch value <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/opentype.gpos.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>GPOS table lacks kerning information.</p>
 [code: lacks-kern-info]



</div>
</details>

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
<li>U+0302 COMBINING CIRCUMFLEX ACCENT: try adding one of: cherokee, tifinagh, math, coptic</li>
<li>U+0306 COMBINING BREVE: try adding one of: old-permic, tifinagh</li>
<li>U+0307 COMBINING DOT ABOVE: try adding one of: malayalam, tifinagh, math, coptic, syriac, todhri, duployan, canadian-aboriginal, hebrew, old-permic, tai-le</li>
<li>U+030A COMBINING RING ABOVE: try adding one of: duployan, syriac</li>
<li>U+030B COMBINING DOUBLE ACUTE ACCENT: try adding one of: cherokee, osage</li>
<li>U+030C COMBINING CARON: try adding one of: cherokee, tai-le</li>
<li>U+0326 COMBINING COMMA BELOW: try adding math</li>
<li>U+0327 COMBINING CEDILLA: try adding math</li>
<li>U+0328 COMBINING OGONEK: not included in any glyphset definition</li>
<li>U+03C0 GREEK SMALL LETTER PI: try adding one of: yi, math, greek</li>
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
<li>U+25CA LOZENGE: try adding one of: symbols, math</li>
<li>U+FB01 LATIN SMALL LIGATURE FI: not included in any glyphset definition</li>
<li>U+FB02 LATIN SMALL LIGATURE FL: not included in any glyphset definition</li>
</ul>
<p>Or you can add the above codepoints to one of the subsets supported by the font: <code>latin</code>, <code>latin-ext</code></p>
 [code: unreachable-subsetting]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Ensure dotted circle glyph is present and can attach marks. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/shaping.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>No dotted circle glyph present</p>
 [code: missing-dotted-circle]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Ensure soft_dotted characters lose their dot when combined with marks that replace the dot. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/shaping.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>The dot of soft dotted characters used in orthographies <em>must</em> disappear in the following strings: i̊ i̋ j̀ j́ j̃ j̄ j̈ į̀ į́ į̂ į̃ į̄ į̌</p>
<p>The dot of soft dotted characters <em>should</em> disappear in other cases, for example: i̇ ǐ i̦̇ i̦̊ i̦̋ ǐ̦ i̧̇ i̧̊ i̧̋ ǐ̧ ĵ j̆ j̇ j̊ j̋ ǰ j̦̀ j̦́ ĵ̦ j̦̃</p>
<p>Your font fully covers the following languages that require the soft-dotted feature: Lithuanian (Latn, 2,357,094 speakers), Dutch (Latn, 31,709,104 speakers).</p>
<p>Your font does <em>not</em> cover the following languages that require the soft-dotted feature: Ejagham (Latn, 120,000 speakers), Zapotec (Latn, 490,000 speakers), Nzakara (Latn, 50,000 speakers), Kaska (Latn, 125 speakers), Mundani (Latn, 34,000 speakers), Sar (Latn, 500,000 speakers), Bafut (Latn, 158,146 speakers), Dii (Latn, 71,000 speakers), Lugbara (Latn, 2,200,000 speakers), Yala (Latn, 200,000 speakers), Koonzime (Latn, 40,000 speakers), Ma’di (Latn, 584,000 speakers), Ebira (Latn, 2,200,000 speakers), Fur (Latn, 1,230,163 speakers), Aghem (Latn, 38,843 speakers), Ukrainian (Cyrl, 29,273,587 speakers), Vute (Latn, 21,000 speakers), Han (Latn, 6 speakers), Basaa (Latn, 332,940 speakers), Ijo, Southeast (Latn, 2,471,000 speakers), Kom (Latn, 360,685 speakers), Dan (Latn, 1,099,244 speakers), Belarusian (Cyrl, 10,064,517 speakers), Igbo (Latn, 27,823,640 speakers), Avokaya (Latn, 100,000 speakers), Gulay (Latn, 250,478 speakers), Mfumte (Latn, 79,000 speakers), South Central Banda (Latn, 244,000 speakers), Bete-Bendi (Latn, 100,000 speakers), Heiltsuk (Latn, 300 speakers), Kpelle, Guinea (Latn, 622,000 speakers), Ngbaka (Latn, 1,020,000 speakers), Teke-Ebo (Latn, 260,000 speakers), Mango (Latn, 77,000 speakers), Makaa (Latn, 221,000 speakers), Nateni (Latn, 100,000 speakers), Navajo (Latn, 166,319 speakers), Cicipu (Latn, 44,000 speakers), Southern Kisi (Latn, 360,000 speakers), Ekpeye (Latn, 226,000 speakers).</p>
 [code: soft-dotted]



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

* uni0163 (U+0163): X=200.0,Y=1.0 (should be at baseline 0?)

* uni0163 (U+0163): X=293.5,Y=0.5 (should be at baseline 0?)

* uni021B (U+021B): X=293.0,Y=0.5 (should be at baseline 0?)

* ucircumflex (U+00FB): X=317.0,Y=688.0 (should be at cap-height 690?)

* uogonek (U+0173): X=553.0,Y=-1.0 (should be at baseline 0?)

* wcircumflex (U+0175): X=408.0,Y=688.0 (should be at cap-height 690?)

* ycircumflex (U+0177): X=288.0,Y=688.0 (should be at cap-height 690?)

* zdotaccent (U+017C): X=188.5,Y=691.5 (should be at cap-height 690?)

* zdotaccent (U+017C): X=253.5,Y=691.5 (should be at cap-height 690?)

* sterling (U+00A3): X=211.0,Y=691.5 (should be at cap-height 690?)

* sterling (U+00A3): X=437.5,Y=689.0 (should be at cap-height 690?)

* ampersand (U+0026): X=399.0,Y=688.0 (should be at cap-height 690?)

* circumflex (U+02C6): X=158.0,Y=688.0 (should be at cap-height 690?)

* uni1E9E (U+1E9E): X=473.0,Y=688.0 (should be at cap-height 690?)

* uni20BA (U+20BA): X=208.0,Y=-1.0 (should be at baseline 0?)

* uni030C.alt: X=273.5,Y=689.0 (should be at cap-height 690?)

* uni0302 (U+0302): X=158.0,Y=688.0 (should be at cap-height 690?)
</code></pre>
 [code: found-misalignments]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Are any segments inordinately short? <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/outline.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>The following glyphs have segments which seem very short:</p>
<pre><code>* uogonek (U+0173) contains a short segment L&lt;&lt;553.0,0.0&gt;--&lt;553.0,0.0&gt;&gt;

* uogonek (U+0173) contains a short segment L&lt;&lt;553.0,0.0&gt;--&lt;553.0,-1.0&gt;&gt;

* parenleft (U+0028) contains a short segment L&lt;&lt;380.0,934.0&gt;--&lt;380.0,927.0&gt;&gt;

* parenright (U+0029) contains a short segment L&lt;&lt;50.0,-186.0&gt;--&lt;50.0,-179.0&gt;&gt;

* paragraph (U+00B6) contains a short segment L&lt;&lt;272.0,289.0&gt;--&lt;264.0,289.0&gt;&gt;

* uni20B9 (U+20B9) contains a short segment B&lt;&lt;393.0,523.0&gt;-&lt;393.0,533.0&gt;-&lt;393.0,544.0&gt;&gt;

* uni20B9 (U+20B9) contains a short segment B&lt;&lt;459.0,543.0&gt;-&lt;459.0,533.0&gt;-&lt;459.0,523.0&gt;&gt;
</code></pre>
 [code: found-short-segments]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Do outlines contain any jaggy segments? <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/outline.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>The following glyphs have jaggy segments:</p>
<pre><code>* G (U+0047): L&lt;&lt;659.0,0.0&gt;--&lt;659.0,207.0&gt;&gt;/B&lt;&lt;659.0,207.0&gt;-&lt;652.0,179.0&gt;-&lt;631.0,142.5&gt;&gt; = 14.036243467926484

* Gbreve (U+011E): L&lt;&lt;659.0,0.0&gt;--&lt;659.0,207.0&gt;&gt;/B&lt;&lt;659.0,207.0&gt;-&lt;652.0,179.0&gt;-&lt;631.0,142.5&gt;&gt; = 14.036243467926484

* Gdotaccent (U+0120): L&lt;&lt;659.0,0.0&gt;--&lt;659.0,207.0&gt;&gt;/B&lt;&lt;659.0,207.0&gt;-&lt;652.0,179.0&gt;-&lt;631.0,142.5&gt;&gt; = 14.036243467926484

* eth (U+00F0): B&lt;&lt;432.5,524.5&gt;-&lt;485.0,496.0&gt;-&lt;515.0,432.0&gt;&gt;/B&lt;&lt;515.0,432.0&gt;-&lt;500.0,492.0&gt;-&lt;472.0,544.0&gt;&gt; = 11.078591418218123

* partialdiff (U+2202): B&lt;&lt;394.0,527.5&gt;-&lt;433.0,502.0&gt;-&lt;448.0,432.0&gt;&gt;/B&lt;&lt;448.0,432.0&gt;-&lt;448.0,507.0&gt;-&lt;432.5,567.0&gt;&gt; = 12.094757077012089

* t (U+0074): B&lt;&lt;186.0,567.0&gt;-&lt;176.0,551.0&gt;-&lt;154.0,546.0&gt;&gt;/L&lt;&lt;154.0,546.0&gt;--&lt;312.0,546.0&gt;&gt; = 12.80426606528674

* tcaron (U+0165): B&lt;&lt;186.0,567.0&gt;-&lt;176.0,551.0&gt;-&lt;154.0,546.0&gt;&gt;/L&lt;&lt;154.0,546.0&gt;--&lt;312.0,546.0&gt;&gt; = 12.80426606528674

* uni0122 (U+0122): L&lt;&lt;659.0,0.0&gt;--&lt;659.0,207.0&gt;&gt;/B&lt;&lt;659.0,207.0&gt;-&lt;652.0,179.0&gt;-&lt;631.0,142.5&gt;&gt; = 14.036243467926484

* uni0163 (U+0163): B&lt;&lt;186.0,567.0&gt;-&lt;176.0,551.0&gt;-&lt;154.0,546.0&gt;&gt;/L&lt;&lt;154.0,546.0&gt;--&lt;312.0,546.0&gt;&gt; = 12.80426606528674

* uni021B (U+021B): B&lt;&lt;186.0,567.0&gt;-&lt;176.0,551.0&gt;-&lt;154.0,546.0&gt;&gt;/L&lt;&lt;154.0,546.0&gt;--&lt;312.0,546.0&gt;&gt; = 12.80426606528674
</code></pre>
 [code: found-jaggy-segments]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Do outlines contain any semi-vertical or semi-horizontal lines? <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/outline.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>The following glyphs have semi-vertical/semi-horizontal lines:</p>
<pre><code>* trademark (U+2122): L&lt;&lt;117.0,338.0&gt;--&lt;118.0,644.0&gt;&gt;

* trademark (U+2122): L&lt;&lt;174.0,644.0&gt;--&lt;175.0,338.0&gt;&gt;

* trademark (U+2122): L&lt;&lt;650.0,338.0&gt;--&lt;649.0,607.0&gt;&gt;

* yen (U+00A5): L&lt;&lt;234.0,319.0&gt;--&lt;60.0,320.0&gt;&gt;

* yen (U+00A5): L&lt;&lt;530.0,320.0&gt;--&lt;355.0,319.0&gt;&gt;
</code></pre>
 [code: found-semi-vertical]



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
| 0 | 0 | 4 | 72 | 704 | 43 | 593 | 0 | 
| 0% | 0% | 0% | 5% | 50% | 3% | 42% | 0% | 



**Note:** The following loglevels were omitted in this report:


* SKIP
* INFO
* PASS
* DEBUG
