# challenge-week-one

# <Code Refactor>

## Description
A marketing agency wanted to refactor its current website to make it more accessible. Web accessibility is an increasingly important consideration for businesses. It ensures that people with disabilities can access a website using assistive technologies such as video captions, screen readers, and braille keyboards. Making a website accessible also positions it better in search engines like Google. It also helps companies avoid litigation that can occur when people with disabilities are unable to access their website. 

First, added alt attributes and descriptions to image elements. This was more challenging that expected, as some images are difficult to describe with specificity. For some reason, I was also unable to add the alt Attribute to the "hero" img. After images, I made sure that the title for the web page was concise and descriptive.  Here it seemed that I needed to do little refactoring as their title element was clear and concise, but I did make changes in the h1 element as inicated below. 

The primary task for the web page was to ensure that the elements follow a logical structure independent of styling and positioning when one views the structure of the HTML elements. This involved ensuring that all heading attributes fall in sequential order and also placing sematic elements in the HTML in the place of <div> elements, since the document’s many <div> elements makes it hard to read and navigate.  The following is a list of semantic elements and attributes added to the Horiseon landing page.

<header>, <img>, <main>, <article>, <aside>, <section>, <footer>, <h4>. I also Converted the h1 element from <h1>Hori<span class="seo">seo</span>n</h1> to <h1>Horiseon</h1>. I kept the <div> tag at the top of the page as neither <nav> nor <menu> worked here.

## License
MIT

---

---
