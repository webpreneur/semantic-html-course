# The `<strong>` element

## Examples


Here, the word "chapter" and the actual chapter number are mere boilerplate, and the actual name of the chapter is marked up with strong:

```html
<h1>Chapter 1: <strong>The Praxis</strong></h1>
```


In this example, the heading is really "Flowers, Bees, and Honey", but the author has added a light-hearted addition to the heading. The strong element is thus used to mark up the first part to distinguish it from the latter part.

```html
<h1><strong>Flowers, Bees, and Honey</strong> and other things I don't understand</h1>
```

The relative level of importance of a piece of content is given by its number of ancestor strong elements; each strong element increases the importance of its contents.

```html
<p>
<strong><strong>This text</strong></strong> is more important than <strong>this text</strong>
</p>
```