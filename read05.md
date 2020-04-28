# Introducing CSS

#### definition : CSS allows you to create rules that specify how the content of an element should appear. For example, you can specify that the background of the page is cream, all paragraphs should appear in gray using the Arial typeface, or that all level one headings should be in a blue, italic, Times typeface.

#### Understanding CSS: Thinking Inside the Box : The key to understanding how CSS works is to imagine that there is an invisible box around every HTML element.

#### Here you can see a simple web page that is styled using CSS :
`<!DOCTYPE html>`
`<html>`
`<head>`
`<title>Introducing CSS</title>`
`<link href="css/example.css" type="text/css"`
`rel="stylesheet" />`
`</head>`
`<body>`
`<h1>From Garden to Plate</h1>`
`<p>A <i>potager</i> is a French term for an`
`ornamental vegetable or kitchen garden ... </p>`
`<h2>What to Plant</h2>`
`<p>Plants are chosen as much for their functionality`
`as for their color and form ... </p>`
`</body>`
`</html>`
`body {`
`font-family: Arial, Verdana, sans-serif;}`
`h1, h2 {`
`color: #ee3e80;}`
`p {`
`color: #665544;}`

#### You can style your code with CSS from different sources :
       1. Using External CSS : The <link> element can be used in an HTML document to tell the browser where to find the CSS file used to style the page.
       2. Using Internal CSS : You can also include CSS rules within an HTML page by placing them inside a <style> element, which usually sits inside the <head> element of the page.

#### CSS Selectors : There are many different types of CSS selector that allow you to target rules to specific elements in an HTML document.

![Examples for some selectors](https://i.pinimg.com/originals/0a/6b/80/0a6b80d7c9c33f6f6f885216a766ebb5.png)

## Ok lets talk about the color design :

#### "Color can really bring your pages to life."

#### The color property allows you to specify the color of text inside an element. You can specify any color in CSS in one of three ways:
     1. rgb values : These express colors in terms of how much red, green and blue are used to make it up. For example: rgb(100,100,90)
     2. hex codes : These are six-digit codes that represent the amount of red, green and blue in a color, preceded by a pound or hash # sign. For example: #ee3e80
     3. color names :There are 147 predefined color names that are recognized by browsers. For example: DarkCyan.

#### Here is a [link](https://htmlcolorcodes.com/color-chart/) that can help you pick a color for your site .

this information refrenced by : HTML & CSS Design and Build Websites By Jon Duckett .






