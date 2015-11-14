# &lt;love-heart&gt; v0.4.0

Pulsing love heart web component

![love](https://raw.github.com/janantala/love-heart/master/img/love.gif)
```html
Made with <love-heart></love-heart> by me
```

## Dependencies

Element dependencies are managed via [Bower](http://bower.io/). You can
install that via:

    npm install -g bower

Then, go ahead and download the element's dependencies:

    bower install

## Demo
[Check it live!](http://janantala.github.io/love-heart/)

## Usage

1. Install love heart component:

  ```sh
  $ bower install love-heart
  ```

2. Import Custom Element:

	```html
	<link rel="import" href="bower_components/love-heart/love-heart.html">
	```

3. Start using it!

	```html
	<love-heart></love-heart>
	```

## Apply your own CSS:

```css
.blue { color: blue; }
.big { font-size: 3.4em; }
```

```html
Made with <love-heart class="blue"></love-heart> by me
Made with <love-heart class="big"></love-heart> by me
```

## Fallback

You can add love-heart component fallback which is visible before page load is complete:

```html
Made with <love-heart>love</love-heart> by Jan Antala
```
## Development

In order to run it locally you'll need to fetch some dependencies and a basic server setup.

    npm install -g bower polyserve

Install local dependencies
    
    bower install

And you can run it via:

    polyserve

Once running, you can preview your element at
`http://localhost:8080/components/love-heart/`, where `love-heart` is the name of the directory containing it.

## Contributing

1. Fork it!
2. Create your feature branch: `git checkout -b my-new-feature`
3. Commit your changes: `git commit -m 'Add some feature'`
4. Push to the branch: `git push origin my-new-feature`
5. Submit a pull request :D

# License

The MIT License

Copyright (c) 2015 [Jan Antala](http://www.janantala.com)
