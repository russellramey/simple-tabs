## Synopsis

Simple lightwight HTML/jQuery tabbed content. Quickly create tabbed content containers with a simple and lightweight jquery function and basic html mark up.


## Markup

1) Create a container:
```html
<div class="simple-tabs">
	-- content will go here --
</div>
```

2) Create the tab navigation:
```html
<ul class="simple-tab--nav">
    <li class="active"><a href="#">Tab One</a></li>
    <li><a href="#">Tab Two</a></li>
    <li><a href="#">Tab Three</a></li>
</ul>
```

3) Create the tabs:
```html
<ul class="simple-tab--panels">
    <li class="simple-tab--panel active">
        <h2>Tab 1</h2>
        <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Ut mollis felis lectus, eu molestie metus dictum in. Morbi a nulla id orci vehicula viverra. Aenean arcu nulla, convallis et quam vitae, vestibulum tempor lorem.</p>
    </li>
    <li class="simple-tab--panel">
        <h2>Tab 2</h2>
        <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Ut mollis felis lectus, eu molestie metus dictum in. Morbi a nulla id orci vehicula viverra. Aenean arcu nulla, convallis et quam vitae, vestibulum tempor lorem.</p>
    </li>
    <li class="simple-tab--panel">
        <h2>Tab 3</h2>
        <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Ut mollis felis lectus, eu molestie metus dictum in. Morbi a nulla id orci vehicula viverra. Aenean arcu nulla, convallis et quam vitae, vestibulum tempor lorem.</p>
    </li>
</ul>
```


# JS

1) Include the Javascript funciton after your jQuery call

2) Enable the function in you projects JS:
```javascript
$('.simple-tabs').simple_tabs();
```



## Demo
See the basic functionality [here](http://russellramey.me/examples/simple-tabs).