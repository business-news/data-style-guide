# Colour Palettes

We standardise three palette types — **categorical**, **sequential**, and **diverging** — with Business News brand colours.

## Brand colours (print CMYK → web HEX)
![Business News web colour palette](assets/web-colours.svg)
<div class="swatches">
  <div class="swatch">
    <div class="swatch__chip" style="background:#0081C6"></div>
    <div class="swatch__meta"><strong>BN Blue</strong><br><code>#0081C6</code></div>
  </div>
  <div class="swatch">
    <div class="swatch__chip" style="background:#011E45"></div>
    <div class="swatch__meta"><strong>BN Dark Blue</strong><br><code>#011E45</code></div>
  </div>
  <div class="swatch">
    <div class="swatch__chip" style="background:#E8BC07"></div>
    <div class="swatch__meta"><strong>BN Gold</strong><br><code>#E8BC07</code></div>
  </div>
  <div class="swatch">
    <div class="swatch__chip" style="background:#601663"></div>
    <div class="swatch__meta"><strong>Purple</strong><br><code>#601663</code></div>
  </div>
  <div class="swatch">
    <div class="swatch__chip" style="background:#025945"></div>
    <div class="swatch__meta"><strong>Green</strong><br><code>#025945</code></div>
  </div>
  <div class="swatch">
    <div class="swatch__chip" style="background:#E33238"></div>
    <div class="swatch__meta"><strong>Red</strong><br><code>#E33238</code></div>
  </div>
</div>

<!-- Show your master palette and make it downloadable -->
<p></p>
<a href="assets/web-colours.svg" download>
  <img src="assets/web-colours.svg" alt="Business News web colour palette" width="600">
</a>
<p><em>Click the palette to download the SVG file</em></p>


!!! note
    CMYK values come from the publication style guide. Web HEX approximations are calculated from CMYK. If brand provides official RGB/HEX, prefer those.

---

## Categorical (Qualitative)
Use for **distinct, unordered** categories. Limit to **≤10** colours; group small categories as “Other”. Ensure hue separation and sufficient contrast.

**Default order:** BN Blue → Green → Gold → Purple → Red → Neutral grey.

![](assets/categorical-bars.svg)

---

## Sequential
Use for **ordered/numeric** data. Encode magnitude with lightness in a **single-hue ramp**.

**BN Blue ramp examples:** `#D6E4F0 → #97BBD6 → #4F87B6 → #003865`

![](assets/sequential-ramp.svg)

---

## Diverging
Use when data vary around a meaningful **midpoint** (0, average, target). Two hue ramps meet at a neutral centre.

**Default diverging:** Red ramp (negative) ↔ Neutral grey ↔ Blue ramp (positive).

![](assets/diverging-bar.svg)

!!! tip
    Never rely on colour alone. Pair with direct labels or markers. Check WCAG contrast (AA) for text on fills.
