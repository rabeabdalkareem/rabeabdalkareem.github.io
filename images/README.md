Drop your real images here and update the corresponding <img>/placeholder
in the HTML:

- profile.jpg           -> your headshot, used on index.html (Fig. 1)
- research-overview.jpg -> a diagram/photo summarizing your research (Fig. 2)
- pub-01.jpg ... pub-05.jpg -> a small figure/screenshot from each paper

Each placeholder block in the HTML currently looks like:

  <div class="figure-placeholder">
    <span class="ph-label">Replace with headshot ...</span>
  </div>

Replace it with:

  <img src="images/profile.jpg" alt="Jordan A. Whit">

(keep it inside the existing .figure-frame wrapper so the border/caption
styling still applies).
