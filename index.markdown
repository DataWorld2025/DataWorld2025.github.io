<!-- Year Filter -->
<label for="year-select"><strong>Select Year:</strong></label>
<select id="year-select">
  <option value="2019">2019</option>
  <option value="2020">2020</option>
</select>

<!-- Embedded Folium Map -->
<figure>
  <iframe id="map-frame" src="{{ site.baseurl }}/assets/intermaptest.html" width="100%" height="700px"></iframe>
  <figcaption>Interactive Map by Year</figcaption>
</figure>

<!-- JavaScript Layer Toggle -->
<script>
document.getElementById('year-select').addEventListener('change', function () {
  const year = this.value;
  const iframe = document.getElementById('map-frame');
  if (!iframe) return;

  const iframeDoc = iframe.contentDocument || iframe.contentWindow.document;

  iframeDoc.querySelectorAll('.leaflet-control-layers-overlays input').forEach((input) => {
    const label = input.nextSibling.textContent.trim();
    input.checked = (label === year);
    input.dispatchEvent(new Event('click'));
  });
});
</script>
