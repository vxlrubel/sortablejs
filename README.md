### Sortable JS

## instalation

include the sortable.js file inside the head tag.

```html
<script src="./sortable.js"></script>
```

### HTML markup

```html
<div id="example">
    <div class="items" draggable="false">
        <span>United States</span> <span class="handle"><img src="./drag.png" alt="image"></span>
    </div>
    <div class="items" draggable="false">
        <span>Canada</span> <span class="handle"><img src="./drag.png" alt="image"></span>
    </div>
    <div class="items" draggable="false">
        <span>Brazil</span> <span class="handle"><img src="./drag.png" alt="image"></span>
    </div>
    <div class="items" draggable="false">
        <span>Australia</span> <span class="handle"><img src="./drag.png" alt="image"></span>
    </div>
    <div class="items" draggable="false">
        <span>Japan</span> <span class="handle"><img src="./drag.png" alt="image"></span>
    </div>
    <div class="items" draggable="false">
        <span>Germany</span> <span class="handle"><img src="./drag.png" alt="image"></span>
    </div>
    <div class="items" draggable="false">
        <span>France</span> <span class="handle"><img src="./drag.png" alt="image"></span>
    </div>
    <div class="items" draggable="false">
        <span>United Kingdom</span> <span class="handle"><img src="./drag.png" alt="image"></span>
    </div>
    <div class="items" draggable="false">
        <span>China</span> <span class="handle"><img src="./drag.png" alt="image"></span>
    </div>
    <div class="items" draggable="false">
        <span>India</span> <span class="handle"><img src="./drag.png" alt="image"></span>
    </div>
    <div class="items" draggable="false">
        <span>Russia</span> <span class="handle"><img src="./drag.png" alt="image"></span>
    </div>
    <div class="items" draggable="false">
        <span>South Africa</span> <span class="handle"><img src="./drag.png" alt="image"></span>
    </div>
    <div class="items" draggable="false">
        <span>Mexico</span> <span class="handle"><img src="./drag.png" alt="image"></span>
    </div>
    <div class="items" draggable="false">
        <span>Argentina</span> <span class="handle"><img src="./drag.png" alt="image"></span>
    </div>
    <div class="items" draggable="false">
        <span>Italy</span> <span class="handle"><img src="./drag.png" alt="image"></span>
    </div>
</div>
```

### Apply sortable

Include the javascript code above the body close tag.
```javascript   
    new Sortable(example5, {
        handle   : '.handle',
        animation: 150
    });
```


