<!-- Colors -->
<button onclick="modal_colors.showModal()">Colors</button>

<dialog id="modal_colors" class="w:90">
  <p class="t:5 t:bold"><b>Colors</b></p>
  <section>
    <p><b>Class availables</b></p>
    <ol>
      <li><code>d:{ color } /* background-color */</code></li>
      <li><code>b:{ color } /* border-color */</code></li>
      <li><code>t:{ color } /* color */</code></li>
    </ol>
    <p><b>Colors</b></p>
    <div>
      <ul class="items d:grid4 g:1">
        <li><code>white</code><div class="b:solid w:2 h:2 d:white"></div></li>
        <li><code>black</code><div class="b:solid w:2 h:2 d:black"></div></li>
        <li><code>blue</code><div class="b:solid w:2 h:2 d:blue"></div></li>
        <li><code>red</code><div class="b:solid w:2 h:2 d:red"></div></li>
        <li><code>orange</code><div class="b:solid w:2 h:2 d:orange"></div></li>
        <li><code>green</code><div class="b:solid w:2 h:2 d:green"></div></li>
        <li><code>background</code><div class="b:solid w:2 h:2 d:background"></div></li>
        <li><code>primary</code><div class="b:solid w:2 h:2 d:primary"></div></li>
        <li><code>secondary</code><div class="b:solid w:2 h:2 d:secondary"></div></li>
        <li><code>border</code><div class="b:solid w:2 h:2 d:border"></div></li>
        <li><code>highlight</code><div class="b:solid w:2 h:2 d:highlight"></div></li>
        <li><code>shadow</code><div class="b:solid w:2 h:2 d:shadow"></div></li>
        <li><code>text</code><div class="b:solid w:2 h:2 d:text"></div></li>
        <li><code>accent</code><div class="b:solid w:2 h:2 d:accent"></div></li>
        <li><code>error</code><div class="b:solid w:2 h:2 d:error"></div></li>
        <li><code>warning</code><div class="b:solid w:2 h:2 d:warning"></div></li>
        <li><code>info</code><div class="b:solid w:2 h:2 d:info"></div></li>
        <li><code>light</code><div class="b:solid w:2 h:2 d:light"></div></li>
        <li><code>dark</code><div class="b:solid w:2 h:2 d:dark"></div></li>
      </ul>
  </section>
  <div>
    <button onclick="modal_colors.close()">Close</button>
</dialog>

