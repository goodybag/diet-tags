# Diet Tags

![http://storage.j0.hn/diet-tags.png](http://storage.j0.hn/diet-tags.png)

__Usage:__

package.json

```javascript
"dependencies": {
  "diet-tags": "goodybag/diet-tags"
}
```

```less
@import "./node_modules/diet-tags/index.less"

@img-base-url: '../dist/img';
@diet-tag-size: 20px;
#components > .diet-tags( @img-base-url, @diet-tag-size );
```

```html
<span class="diet-tag diet-tag-gluten-free"></span>
<span class="diet-tag diet-tag-vegan"></span>
<span class="diet-tag diet-tag-vegetarian"></span>
<span class="diet-tag diet-tag-kosher"></span>
<span class="diet-tag diet-tag-halal"></span>
<span class="diet-tag diet-tag-dairy-free"></span>
<span class="diet-tag diet-tag-nuts"></span>
<span class="diet-tag diet-tag-spicy"></span>
```

In a build step, copy the files from `diet-tags/img` to a public directory (preferably one that is ignored from vcs).

## API

#### `.diet-tags( @diet-tags-url, @diet-tag-size )`

__Params__

* `@diet-tags-url` - The path where the diet tags images are stored
* `@diet-tag-size` - The size of the icons