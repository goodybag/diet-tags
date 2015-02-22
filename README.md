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
@diet-tags-url: '../dist/img';
@import "./node_modules/diet-tags/index.less"
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