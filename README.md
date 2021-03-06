facade
======

a flexible browser mockup CSS framework. See it in action at http://facade.pascalculator.be/

# Documentation

1. Add [facade.css](https://github.com/pascalculator/facade/blob/master/css/facade.css) to you stylesheets
2. Create a block element, like a `<div>` or a `<section>`.
3. Add the `facade-minimal` class to the element
4. Add a `data-url` attribute and fill in your mock url
5. Put your mockup content inside the element

# Example code

```HTML
<link rel="stylesheet" href="css/facade.css">
...
<section class="facade-minimal" data-url="http://www.bowie-to-bowie.io"> 
    <h1>Ground control to Major Tom...</h1>
</section>
```
Which will result into

![Output example of facade layout](https://raw.githubusercontent.com/pascalculator/facade/master/img/example-of-facade.png "Output example of facade layout")

See the live result at http://facade.pascalculator.be/#example

