<h1><p align="center">Quotations</p></h1> 

* In this chapter we will go through the `<blockquote>`, `<q>`, `<abbr>`, `<address>`, 
`<cite>`, and `<bdo>` HTML elements.

## 1. `<blockquote>` 

* The HTML `<blockquote>` element defines a section that is quoted from another source.
* Browsers usually indent `<blockquote>` elements.	

```HTML
Example:

<p>Browsers usually indent blockquote elements.</p>

<blockquote cite="http://www.worldwildlife.org/who/index.html">
For nearly 60 years, WWF has been protecting the future of nature. The world's 
leading conservation organization, WWF works in 100 countries and is supported by more 
than one million members in the United States and close to five million globally.
</blockquote>
```

## 2. `<q>`

* The HTML `<q>` tag defines a short quotation.
* Browsers normally insert quotation marks around the quotation.	

```HTML
Example:

<p>WWF's goal is to: <q>Build a future where people live in harmony</q> with nature.</p>
```

## 3. `<abbr>`

* The HTML <abbr> tag defines an abbreviation or an acronym, like "HTML", "CSS", "Mr.", 
"Dr.", "ASAP", "ATM".


```HTML
Example:

<p>The <abbr title="World Health Organization">WHO</abbr> was founded in 1948.</p>

<p>Marking up abbreviations can give useful information to browsers, translation systems and search-engines.</p>
```

## 4. `<address>`

* The HTML `<address>` tag defines the contact information for the author/owner of a 
document or an article.

* The contact information can be an email address, URL, physical address, phone number, 
social media handle, etc.

* The text in the `<address>` element usually renders in italic, and browsers will always 
add a line break before and after the `<address>` element.


```HTML
Example:

<address>
Written by John Doe.<br> 
Visit us at:<br>
Example.com<br>
Box 564, Disneyland<br>
USA
</address>
```

## 5. `<cite>`

* The HTML `<cite>` tag defines the title of a creative work (e.g. a book, a poem, a song, 
a movie, a painting, a sculpture, etc.).

* Note: A person's name is not the title of a work.

* The text in the `<cite>` element usually renders in italic.	


```HTML
Example:

<img src="img_the_scream.jpg" width="220" height="277" alt="The Scream">
<p><cite>The Scream</cite> by Edvard Munch. Painted in 1893.</p>
```	

## 6. `<bdo>`

* BDO stands for Bi-Directional Override.

* The HTML `<bdo>` tag is used to override the current text direction:

```HTML
Example:

<p>If your browser supports bi-directional override (bdo), the next line will be written 
from right to left (rtl):</p>

<bdo dir="rtl">This line will be written from right to left</bdo>
```

> Please inbox **[me](https://www.facebook.com/shoriot)**, if you've any questions.