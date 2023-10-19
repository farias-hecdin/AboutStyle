<script>
  import imageA from "../assets/media/images/shoe.jpg"
</script>

<!-- Cards ---------------------------------------------------------- -->
<h3 id="CARDS">Cards</h3>
<div class="d:flex f:col g:2">

  <!-- Style A -->
  <article>
    <div>
      <img src={imageA} alt="#">
      <header>
        <p>Fusce non lacus ut</p>
        <p>$103.54</p>
      </header>
      <dl>
        <dt>Vulputate</dt>
        <dd>Sed ornare turpis leo, sit amet hendrerit.</dd>
      </dl>
      <footer>
        <button class="--ghost">Button</button>
        <button>Button</button>
      </footer>
    </div>
  </article>

  <!-- Style B -->
  <article class="--inline">
    <img src={imageA} alt="#">
    <div>
      <header>
        <p>Nulla lectus erat, eleifend a elit</p>
        <p>Etiam porttitor</p>
      </header>
      <dl>
        <dt>Vulputate</dt>
        <dd>Sed ornare turpis leo, sit amet hendrerit leosit amet.</dd>
      </dl>
      <footer>
        <button class="--ghost">Button</button>
        <button>Button</button>
      </footer>
    </div>
  </article>

</div>
