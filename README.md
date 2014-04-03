gravatar-img
============

Custom Element that displays a Gravatar image for an email or hash. Does not require Polymer

## Using gravatar-img

### By `email` attribute

```html
<gravatar-img email="albert.einstein.starcounter@gmail.com"></gravatar-img>
```

### By email `hash` attribute

```html
<gravatar-img hash="f018de3ef195fb11de2bd4fbbab124a1"></gravatar-img>
```

## Requirements

Using `email` attribute requires [SparkMD5](https://github.com/satazor/SparkMD5">SparkMD5) (it is defined as a Bower dependency).

Requires a browser that implements Template, Shadow DOM, Custom Elements and HTML Imports (shimmed or native).

## License

MIT
