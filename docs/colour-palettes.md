# Colour Palettes

We standardise three palette types — **categorical**, **sequential**, and **diverging** — with Business News brand colours.

## Brand colours (print CMYK → web HEX)
<a href="assets/web-colours.svg" download>
  <img src="assets/web-colours.svg" alt="Business News web colour palette" width="600">
</a>

<p><em>Click the palette to download the SVG file</em></p>

<div class="swatches">
  <div class="swatch">
    <div class="swatch__chip" style="background:#1987FF"></div>
    <div class="swatch__meta"><strong>BN Blue</strong><br>CMYK 90/47/0/0 → <code>#1987FF</code></div>
  </div>
  <div class="swatch">
    <div class="swatch__chip" style="background:#003D99"></div>
    <div class="swatch__meta"><strong>Dark Blue</strong><br>CMYK 100/60/0/40 → <code>#003D99</code></div>
  </div>
  <div class="swatch">
    <div class="swatch__chip" style="background:#00CC52"></div>
    <div class="swatch__meta"><strong>Green</strong><br>CMYK 100/0/60/20 → <code>#00CC52</code></div>
  </div>
  <div class="swatch">
    <div class="swatch__chip" style="background:#FF0019"></div>
    <div class="swatch__meta"><strong>Red</strong><br>CMYK 0/100/90/0 → <code>#FF0019</code></div>
  </div>
  <div class="swatch">
    <div class="swatch__chip" style="background:#E6BC00"></div>
    <div class="swatch__meta"><strong>Gold</strong><br>CMYK 0/18/100/10 → <code>#E6BC00</code></div>
  </div>
  <div class="swatch">
    <div class="swatch__chip" style="background:#7300E6"></div>
    <div class="swatch__meta"><strong>Purple</strong><br>CMYK 50/100/0/10 → <code>#7300E6</code></div>
  </div>
</div>

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
