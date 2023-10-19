<!-- Properties ----------------------------------------------------- -->
<h3 id="Properties">Properties</h3>
<button onclick="modal_dimensions.showModal()">Properties</button>

<!-- Dimensions -->
<dialog id="modal_dimensions">
  <p class="t:5"><b>Properties</b></p>
  <section class="d:grid2 g:5">
    <ol>
      <p><b>Dimensions</b></p>
      <li><code>w:{ 0 to 100 } /* width */</code></li>
      <li><code>h:{ 0 to 100 } /* height */</code></li>
      <li><code>m:{ 0 to 25 } /* margin */</code></li>
      <li><code>mt:{ 0 to 25 } /* margin-top */</code></li>
      <li><code>mb:{ 0 to 25 } /* margin-bottom */</code></li>
      <li><code>mr:{ 0 to 25 } /* margin-left */</code></li>
      <li><code>ml:{ 0 to 25 } /* margin-right */</code></li>
    </ol>
    <ol>
      <p><b>Layout</b></p>
      <li><code>d:{ block } /* display */</code></li>
      <li><code>d:{ inline } /* display */</code></li>
      <li><code>d:{ flex } /* display */</code></li>
      <li><code>d:{ grid } /* display */</code></li>
      <li><code>f:{ row } /* flex-direction */</code></li>
      <li><code>f:{ column } /* flex-direction */</code></li>
      <li><code>f:{ wrap } /* flex-wrap */</code></li>
      <li><code>f:{ order } /* order */</code></li>
    </ol>
    <ol>
      <p><b>Align and justify</b></p>
      <li><code>a:{ center } /* justify-content */</code></li>
      <li><code>a:{ start } /* justify-content */</code></li>
      <li><code>a:{ end } /* justify-content */</code></li>
      <li><code>j:{ center } /* align-items */</code></li>
      <li><code>j:{ between } /* align-items */</code></li>
      <li><code>j:{ around } /* align-items */</code></li>
    </ol>
    <ol>
      <p><b>Border</b></p>
      <li><code>b:{ solid } /* border */</code></li>
      <li><code>b:{ dashed } /* border */</code></li>
      <li><code>b:{ rounded } /* border-radius */</code></li>
      <li><code>b:{ circle } /* border-radius */</code></li>
    </ol>
    <ol>
      <p><b>None</b></p>
      <li><code>n:{ display } /* display: none; */</code></li>
      <li><code>n:{ list } /* list-style: none; */</code></li>
    </ol>
    <ol>
      <p><b>Other</b></p>
      <li><code>opacity /* opacity */</code></li>
      <li><code>hover /* :hover */</code></li>
      <li><code>s:{ this } /* outline */</code></li>
      <li><code>s:{ all } /* outline */</code></li>
    </ol>
  </section>
  <button onclick="modal_dimensions.close()">Close</button>
</dialog>

