# HTML Advanced - Task 0: Create the HTML skeleton

## 📝 Overview
This task marks the beginning of the `html_advanced` project. The objective is to set up the most fundamental HTML5 boilerplate, defining the document type and the root `<html>` element with appropriate language and text direction attributes.

## 📁 Repository Structure
* **GitHub repository:** `holbertonschool-web_front_end`
* **Directory:** `html_advanced`
* **File:** `0-index.html`

## 🎯 Objectives & Requirements
* Define the HTML5 doctype statement (`<!DOCTYPE html>`).
* Create the root `<html>` element.
* Set the language attribute (`lang="en"`).
* Set the text direction attribute (`dir="ltr"`).
* Maintain a clean, empty body structure inside the root element for initial validation.

## 📄 File Content (`0-index.html`)
```html
<!DOCTYPE html>
<html lang="en" dir="ltr">
</html>



# HTML Advanced - Task 1: Structure Your Webpage

## 📝 Overview
This task focuses on defining the foundational structure of an HTML5 document. Building upon the base HTML root tag, this step introduces the `<head>` and `<body>` tags in their strict structural hierarchy to ensure a valid webpage skeleton.

## 📁 Repository Structure
* **GitHub repository:** `holbertonschool-web_front_end`
* **Directory:** `html_advanced`
* **File:** `1-index.html`

## 🎯 Objectives & Requirements
* Duplicate the content of `0-index.html` into `1-index.html`.
* Establish the `<head>` and `<body>` tags within the `<html>` root element.
* Maintain the strict element ordering: `<head>` followed by `<body>`.
* Set text direction attributes (`dir="ltr"`) and language specifications (`lang="en"`).

## 📄 File Content (`1-index.html`)
```html
<!DOCTYPE html>
<html lang="en" dir="ltr">
  <head>
  </head>
  <body>
  </body>
</html>



# HTML Advanced - Task 2: The head - meta charset, viewport, title, description, favicons

## 📝 Overview
This task enhances the document header (`<head>`) by adding essential metadata for character encoding, responsiveness across mobile screens, search engine optimization (SEO), and custom site branding (favicons).

## 📁 Repository Structure
* **GitHub repository:** `holbertonschool-web_front_end`
* **Directory:** `html_advanced`
* **File:** `2-index.html`

## 🎯 Objectives & Requirements
* Copy the content of `1-index.html` into `2-index.html`.
* Define character set encoding using `<meta charset="utf-8">`.
* Add viewport configurations for responsive web design (`width=device-width, initial-scale=1.0, viewport-fit=cover`).
* Set the page title to `Homepage - Techium`.
* Include a meta description for SEO: `Techium is a digital agency`.
* Link `favicon.ico` and `favicon.png` icons in the root directory.

## 📄 File Content (`2-index.html`)
```html
<!DOCTYPE html>
<html lang="en" dir="ltr">
  <head>
    <meta charset="utf-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0, viewport-fit=cover">
    <title>Homepage - Techium</title>
    <meta name="description" content="Techium is a digital agency">
    <link rel="icon" type="image/x-icon" href="./favicon.ico">
    <link rel="icon" type="image/png" href="./favicon.png">
  </head>
  <body>
  </body>
 </html>



# HTML Advanced - Task 3: Simple header, main, footer

## 📝 Overview
This task introduces basic HTML5 semantic page architecture by integrating the core structural layout elements (`<header>`, `<main>`, and `<footer>`) within the `<body>` of the document. Using semantic elements improves accessibility, SEO, and document readability.

## 📁 Repository Structure
* **GitHub repository:** `holbertonschool-web_front_end`
* **Directory:** `html_advanced`
* **File:** `3-index.html`

## 🎯 Objectives & Requirements
* Copy the content of `2-index.html` into `3-index.html`.
* Create a `<header>` tag inside `<body>` with the text `Header`.
* Create a `<main>` tag directly after `<header>` with the text `Main content`.
* Create a `<footer>` tag directly after `<main>` with the text `Footer`.

## 📄 File Content (`3-index.html`)
```html
<!DOCTYPE html>
<html lang="en" dir="ltr">
  <head>
    <meta charset="utf-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0, viewport-fit=cover">
    <title>Homepage - Techium</title>
    <meta name="description" content="Techium is a digital agency">
    <link rel="icon" type="image/x-icon" href="./favicon.ico">
    <link rel="icon" type="image/png" href="./favicon.png">
  </head>
  <body>
    <header>
      Header
    </header>
    <main>
      Main content
    </main>
    <footer>
      Footer
    </footer>
  </body>
</html>



# HTML Advanced - Task 4: Aside

## 📝 Overview
This task introduces the `<aside>` semantic element used to represent secondary content related to the primary section (such as sidebars, callout boxes, or supplementary notes). In this task, a new dedicated page for articles (`article.html`) is created.

## 📁 Repository Structure
* **GitHub repository:** `holbertonschool-web_front_end`
* **Directory:** `html_advanced`
* **File:** `article.html`

## 🎯 Objectives & Requirements
* Copy the content of `3-index.html` into a new file named `article.html`.
* Update the page title inside `<title>` to `Article - Techium`.
* Insert an `<aside>` element inside the `<main>` element, positioned after the main content text.
* Add the text `Aside` inside the `<aside>` tags.

## 📄 File Content (`article.html`)
```html
<!DOCTYPE html>
<html lang="en" dir="ltr">
  <head>
    <meta charset="utf-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0, viewport-fit=cover">
    <title>Article - Techium</title>
    <meta name="description" content="Techium is a digital agency">
    <link rel="icon" type="image/x-icon" href="./favicon.ico">
    <link rel="icon" type="image/png" href="./favicon.png">
  </head>
  <body>
    <header>
      Header
    </header>
    <main>
      Main content
      <aside>
        Aside
      </aside>
    </main>
    <footer>
      Footer
    </footer>
  </body>
</html>



# HTML Advanced - Task 5: Section

## 📝 Overview
This task focuses on dividing the main page content into distinct thematic groupings using the HTML5 `<section>` element. Structural sections provide logical layout architecture for different parts of the homepage (such as hero, services, about, and contact sections).

## 📁 Repository Structure
* **GitHub repository:** `holbertonschool-web_front_end`
* **Directory:** `html_advanced`
* **File:** `5-index.html`

## 🎯 Objectives & Requirements
* Copy the content of `3-index.html` into `5-index.html`.
* Remove the placeholder text inside the `<main>` element.
* Create seven `<section>` elements inside `<main>` containing the following text values in exact order:
  1. `Hero section`
  2. `Services section`
  3. `Works section`
  4. `About section`
  5. `Latest news section`
  6. `Testimonials section`
  7. `Contact section`

## 📄 File Content (`5-index.html`)
```html
<!DOCTYPE html>
<html lang="en" dir="ltr">
  <head>
    <meta charset="utf-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0, viewport-fit=cover">
    <title>Homepage - Techium</title>
    <meta name="description" content="Techium is a digital agency">
    <link rel="icon" type="image/x-icon" href="./favicon.ico">
    <link rel="icon" type="image/png" href="./favicon.png">
  </head>
  <body>
    <header>
      Header
    </header>
    <main>
      <section>Hero section</section>
      <section>Services section</section>
      <section>Works section</section>
      <section>About section</section>
      <section>Latest news section</section>
      <section>Testimonials section</section>
      <section>Contact section</section>
    </main>
    <footer>
      Footer
    </footer>
  </body>
</html>



# HTML Advanced - Task 6: Work, News, Testimonial articles

## 📝 Overview
This task incorporates the HTML5 `<article>` semantic element inside specific page sections. Articles represent self-contained, independent components of content, such as project cards, news items, or client reviews.

## 📁 Repository Structure
* **GitHub repository:** `holbertonschool-web_front_end`
* **Directory:** `html_advanced`
* **File:** `6-index.html`

## 🎯 Objectives & Requirements
* Copy the content of `5-index.html` into `6-index.html`.
* Inside the **Works section**, replace the text with 3 `<article>` tags containing `Work 1`, `Work 2`, and `Work 3`.
* Inside the **Latest news section**, replace the text with 3 `<article>` tags containing `Article 1`, `Article 2`, and `Article 3`.
* Inside the **Testimonials section**, replace the text with 3 `<article>` tags containing `Testimonial 1`, `Testimonial 2`, and `Testimonial 3`.

## 📄 File Content (`6-index.html`)
```html
<!DOCTYPE html>
<html lang="en" dir="ltr">
  <head>
    <meta charset="utf-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0, viewport-fit=cover">
    <title>Homepage - Techium</title>
    <meta name="description" content="Techium is a digital agency">
    <link rel="icon" type="image/x-icon" href="./favicon.ico">
    <link rel="icon" type="image/png" href="./favicon.png">
  </head>
  <body>
    <header>
      Header
    </header>
    <main>
      <section>Hero section</section>
      <section>Services section</section>
      <section>
        <article>Work 1</article>
        <article>Work 2</article>
        <article>Work 3</article>
      </section>
      <section>About section</section>
      <section>
        <article>Article 1</article>
        <article>Article 2</article>
        <article>Article 3</article>
      </section>
      <section>
        <article>Testimonial 1</article>
        <article>Testimonial 2</article>
        <article>Testimonial 3</article>
      </section>
      <section>Contact section</section>
    </main>
    <footer>
      Footer
    </footer>
  </body>
</html>



# HTML Advanced - Task 7: Navigation

## 📝 Overview
This task introduces the `<nav>` semantic element inside the site header (`<header>`). The `<nav>` element is designated for primary navigation blocks containing links to navigate across the application or website.

## 📁 Repository Structure
* **GitHub repository:** `holbertonschool-web_front_end`
* **Directory:** `html_advanced`
* **File:** `7-index.html`

## 🎯 Objectives & Requirements
* Copy the content of `6-index.html` into `7-index.html`.
* Remove the placeholder text `Header` inside the `<header>` element.
* Create an empty `<nav>` element inside the `<header>`.

## 📄 File Content (`7-index.html`)
```html
<!DOCTYPE html>
<html lang="en" dir="ltr">
  <head>
    <meta charset="utf-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0, viewport-fit=cover">
    <title>Homepage - Techium</title>
    <meta name="description" content="Techium is a digital agency">
    <link rel="icon" type="image/x-icon" href="./favicon.ico">
    <link rel="icon" type="image/png" href="./favicon.png">
  </head>
  <body>
    <header>
      <nav></nav>
    </header>
    <main>
      <section>Hero section</section>
      <section>Services section</section>
      <section>
        <article>Work 1</article>
        <article>Work 2</article>
        <article>Work 3</article>
      </section>
      <section>About section</section>
      <section>
        <article>Article 1</article>
        <article>Article 2</article>
        <article>Article 3</article>
      </section>
      <section>
        <article>Testimonial 1</article>
        <article>Testimonial 2</article>
        <article>Testimonial 3</article>
      </section>
      <section>Contact section</section>
    </main>
    <footer>
      Footer
    </footer>
  </body>
</html>



# HTML Advanced - Task 8: Level 1 headings

## 📝 Overview
This task focuses on introducing a primary level 1 heading (`<h1>`) inside the `<main>` structural element. Every proper HTML document requires an `<h1>` to define the primary topic or title of the page content for accessibility and SEO.

## 📁 Repository Structure
* **GitHub repository:** `holbertonschool-web_front_end`
* **Directory:** `html_advanced`
* **File:** `8-index.html`

## 🎯 Objectives & Requirements
* Copy the content of `7-index.html` into `8-index.html`.
* Create a level 1 heading (`<h1>`) inside the `<main>` element, positioned before all the `<section>` elements.
* Add the text `Homepage` inside the `<h1>` tags.

## 📄 File Content (`8-index.html`)
```html
<!DOCTYPE html>
<html lang="en" dir="ltr">
  <head>
    <meta charset="utf-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0, viewport-fit=cover">
    <title>Homepage - Techium</title>
    <meta name="description" content="Techium is a digital agency">
    <link rel="icon" type="image/x-icon" href="./favicon.ico">
    <link rel="icon" type="image/png" href="./favicon.png">
  </head>
  <body>
    <header>
      <nav></nav>
    </header>
    <main>
      <h1>Homepage</h1>
      <section>Hero section</section>
      <section>Services section</section>
      <section>
        <article>Work 1</article>
        <article>Work 2</article>
        <article>Work 3</article>
      </section>
      <section>About section</section>
      <section>
        <article>Article 1</article>
        <article>Article 2</article>
        <article>Article 3</article>
      </section>
      <section>
        <article>Testimonial 1</article>
        <article>Testimonial 2</article>
        <article>Testimonial 3</article>
      </section>
      <section>Contact section</section>
    </main>
    <footer>
      Footer
    </footer>
  </body>
</html>



# HTML Advanced - Task 9: Level 2 headings

## 📝 Overview
This task establishes proper structural heading hierarchy by introducing level 2 headings (`<h2>`) into each `<section>` of the document. Section headings provide semantic context and structure for search engines and screen readers.

## 📁 Repository Structure
* **GitHub repository:** `holbertonschool-web_front_end`
* **Directory:** `html_advanced`
* **File:** `9-index.html`

## 🎯 Objectives & Requirements
* Copy the content of `8-index.html` into `9-index.html`.
* Inside each `<section>`, remove placeholder text and add an `<h2>` heading with the following specified titles:
  * **Hero section:** `<h2>We help you build your brand!</h2>`
  * **Services section:** `<h2>Services</h2>`
  * **Works section:** `<h2>Works</h2>`
  * **About section:** `<h2>About Us</h2>`
  * **Latest news section:** `<h2>Latest news</h2>`
  * **Testimonials section:** `<h2>Testimonials</h2>`
  * **Contact section:** `<h2>Contact</h2>`

## 📄 File Content (`9-index.html`)
```html
<!DOCTYPE html>
<html lang="en" dir="ltr">
  <head>
    <meta charset="utf-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0, viewport-fit=cover">
    <title>Homepage - Techium</title>
    <meta name="description" content="Techium is a digital agency">
    <link rel="icon" type="image/x-icon" href="./favicon.ico">
    <link rel="icon" type="image/png" href="./favicon.png">
  </head>
  <body>
    <header>
      <nav></nav>
    </header>
    <main>
      <h1>Homepage</h1>
      <section>
        <h2>We help you build your brand!</h2>
      </section>
      <section>
        <h2>Services</h2>
      </section>
      <section>
        <h2>Works</h2>
        <article>Work 1</article>
        <article>Work 2</article>
        <article>Work 3</article>
      </section>
      <section>
        <h2>About Us</h2>
      </section>
      <section>
        <h2>Latest news</h2>
        <article>Article 1</article>
        <article>Article 2</article>
        <article>Article 3</article>
      </section>
      <section>
        <h2>Testimonials</h2>
        <article>Testimonial 1</article>
        <article>Testimonial 2</article>
        <article>Testimonial 3</article>
      </section>
      <section>
        <h2>Contact</h2>
      </section>
    </main>
    <footer>
      Footer
    </footer>
  </body>
</html>



# HTML Advanced - Task 10: Level 3 headings

## 📝 Overview
This task builds upon the document structure by integrating level 3 headings (`<h3>`) inside various sections and article elements. Subheadings enhance content readability and establish detailed sub-sections within the main architecture.

## 📁 Repository Structure
* **GitHub repository:** `holbertonschool-web_front_end`
* **Directory:** `html_advanced`
* **File:** `10-index.html`

## 🎯 Objectives & Requirements
* Copy the content of `9-index.html` into `10-index.html`.
* Inside the **Services section**, add the following level 3 headings right after `<h2>Services</h2>`:
  * `<h3>Design & Concept</h3>`
  * `<h3>Digital Strategy</h3>`
  * `<h3>Content Strategy</h3>`
  * `<h3>UX Design</h3>`
  * `<h3>Web Development</h3>`
  * `<h3>Social Media</h3>`
* Inside the **Works section**, replace the text in each `<article>` with level 3 headings:
  1. `<h3>Interior Design</h3>`
  2. `<h3>Web Development</h3>`
  3. `<h3>Personal Brand</h3>`
* Inside the **About Us section**, add the following level 3 headings after `<h2>About Us</h2>`:
  * `<h3>Who are we</h3>`
  * `<h3>Our culture</h3>`
  * `<h3>How we work</h3>`
* Inside the **Latest news section**, replace the text in each `<article>` with level 3 headings:
  1. `<h3>Hoc loco tenere se Triarius non potuit.</h3>`
  2. `<h3>Ut alios omittam, hunc appello, quem ille unum secutus est.</h3>`
  3. `<h3>Bestiarum vero nullum iudicium puto.</h3>`

## 📄 File Content (`10-index.html`)
```html
<!DOCTYPE html>
<html lang="en" dir="ltr">
  <head>
    <meta charset="utf-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0, viewport-fit=cover">
    <title>Homepage - Techium</title>
    <meta name="description" content="Techium is a digital agency">
    <link rel="icon" type="image/x-icon" href="./favicon.ico">
    <link rel="icon" type="image/png" href="./favicon.png">
  </head>
  <body>
    <header>
      <nav></nav>
    </header>
    <main>
      <h1>Homepage</h1>
      <section>
        <h2>We help you build your brand!</h2>
      </section>
      <section>
        <h2>Services</h2>
        <h3>Design & Concept</h3>
        <h3>Digital Strategy</h3>
        <h3>Content Strategy</h3>
        <h3>UX Design</h3>
        <h3>Web Development</h3>
        <h3>Social Media</h3>
      </section>
      <section>
        <h2>Works</h2>
        <article>
          <h3>Interior Design</h3>
        </article>
        <article>
          <h3>Web Development</h3>
        </article>
        <article>
          <h3>Personal Brand</h3>
        </article>
      </section>
      <section>
        <h2>About Us</h2>
        <h3>Who are we</h3>
        <h3>Our culture</h3>
        <h3>How we work</h3>
      </section>
      <section>
        <h2>Latest news</h2>
        <article>
          <h3>Hoc loco tenere se Triarius non potuit.</h3>
        </article>
        <article>
          <h3>Ut alios omittam, hunc appello, quem ille unum secutus est.</h3>
        </article>
        <article>
          <h3>Bestiarum vero nullum iudicium puto.</h3>
        </article>
      </section>
      <section>
        <h2>Testimonials</h2>
        <article>Testimonial 1</article>
        <article>Testimonial 2</article>
        <article>Testimonial 3</article>
      </section>
      <section>
        <h2>Contact</h2>
      </section>
    </main>
    <footer>
      Footer
    </footer>
  </body>
</html>



# HTML Advanced - Task 11: Styleguide

## 📝 Overview
This task creates an independent `11-styleguide.html` document to serve as a visual reference for typographic levels. It displays all standard heading hierarchy elements from `<h1>` down to `<h6>` wrapped inside a semantic `<section>` and `<header>`.

## 📁 Repository Structure
* **GitHub repository:** `holbertonschool-web_front_end`
* **Directory:** `html_advanced`
* **File:** `11-styleguide.html`

## 🎯 Objectives & Requirements
* Copy the content of `3-index.html` into `11-styleguide.html`.
* Update the page title inside `<title>` to `Styleguide - Techium`.
* Clear any placeholder text inside `<header>`, `<main>`, and `<footer>`.
* Inside `<main>`, create a new `<section>` containing a section `<header>`.
* Place an `<h2>` heading inside this section header with text `Headings`.
* Following the section header, add headings from level 1 to 6 in order:
  * `<h1>Heading level 1</h1>`
  * `<h2>Heading level 2</h2>`
  * `<h3>Heading level 3</h3>`
  * `<h4>Heading level 4</h4>`
  * `<h5>Heading level 5</h5>`
  * `<h6>Heading level 6</h6>`

## 📄 File Content (`11-styleguide.html`)
```html
<!DOCTYPE html>
<html lang="en" dir="ltr">
  <head>
    <meta charset="utf-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0, viewport-fit=cover">
    <title>Styleguide - Techium</title>
    <meta name="description" content="Techium is a digital agency">
    <link rel="icon" type="image/x-icon" href="./favicon.ico">
    <link rel="icon" type="image/png" href="./favicon.png">
  </head>
  <body>
    <header></header>
    <main>
      <section>
        <header>
          <h2>Headings</h2>
        </header>
        <h1>Heading level 1</h1>
        <h2>Heading level 2</h2>
        <h3>Heading level 3</h3>
        <h4>Heading level 4</h4>
        <h5>Heading level 5</h5>
        <h6>Heading level 6</h6>
      </section>
    </main>
    <footer></footer>
  </body>
</html>



# HTML Advanced - Task 12: Paragraphs

## 📝 Overview
This task integrates the paragraph element (`<p>`) throughout the document to structure detailed copy, subtitles, categories, and description blocks within sections and articles.

## 📁 Repository Structure
* **GitHub repository:** `holbertonschool-web_front_end`
* **Directory:** `html_advanced`
* **File:** `12-index.html`

## 🎯 Objectives & Requirements
* Copy the content of `10-index.html` into `12-index.html`.
* **Section Subtitles:** Add paragraphs immediately below the `<h2>` headings in the following sections:
  * **Services:** `<p>We work with you</p>`
  * **Works:** `<p>Take a look in our portfolio</p>`
  * **About Us:** `<p>Everything about us</p>`
  * **Testimonials:** `<p>We are more than a digital company</p>`
  * **Contact:** `<p>We like to know new people</p>`
* **About Us Section:** Add descriptive body paragraphs after each `<h3>` heading.
* **Latest News Section:** 
  * Add category tag paragraphs (`<p>Career</p>`, `<p>Digital Life</p>`, `<p>Social</p>`) **before** each article `<h3>`.
  * Add body content paragraphs **after** each article `<h3>`.
* **Contact Section:** Add a body description paragraph following the section subtitle.

## 📄 File Content (`12-index.html`)
```html
<!DOCTYPE html>
<html lang="en" dir="ltr">
  <head>
    <meta charset="utf-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0, viewport-fit=cover">
    <title>Homepage - Techium</title>
    <meta name="description" content="Techium is a digital agency">
    <link rel="icon" type="image/x-icon" href="./favicon.ico">
    <link rel="icon" type="image/png" href="./favicon.png">
  </head>
  <body>
    <header>
      <nav></nav>
    </header>
    <main>
      <h1>Homepage</h1>
      <section>
        <h2>We help you build your brand!</h2>
      </section>
      <section>
        <h2>Services</h2>
        <p>We work with you</p>
        <h3>Design & Concept</h3>
        <h3>Digital Strategy</h3>
        <h3>Content Strategy</h3>
        <h3>UX Design</h3>
        <h3>Web Development</h3>
        <h3>Social Media</h3>
      </section>
      <section>
        <h2>Works</h2>
        <p>Take a look in our portfolio</p>
        <article>
          <h3>Interior Design</h3>
        </article>
        <article>
          <h3>Web Development</h3>
        </article>
        <article>
          <h3>Personal Brand</h3>
        </article>
      </section>
      <section>
        <h2>About Us</h2>
        <p>Everything about us</p>
        <h3>Who are we</h3>
        <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit. Ipsum, omnis expedita! Eum, praesentium cumque accusantium rem, sit quaerat est nisi ratione, deserunt ducimus quidem iste dicta quibusdam atque maxime cum!</p>
        <h3>Our culture</h3>
        <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit. Ipsum, omnis expedita! Eum, praesentium cumque accusantium rem, sit quaerat est nisi ratione, deserunt ducimus quidem iste dicta quibusdam atque maxime cum!</p>
        <h3>How we work</h3>
        <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit. Ipsum, omnis expedita! Eum, praesentium cumque accusantium rem, sit quaerat est nisi ratione, deserunt ducimus quidem iste dicta quibusdam atque maxime cum!</p>
      </section>
      <section>
        <h2>Latest news</h2>
        <article>
          <p>Career</p>
          <h3>Hoc loco tenere se Triarius non potuit.</h3>
          <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Id Sextilius factum negabat. Quo tandem modo? At eum nihili facit; Quae contraria sunt his, malane?</p>
        </article>
        <article>
          <p>Digital Life</p>
          <h3>Ut alios omittam, hunc appello, quem ille unum secutus est.</h3>
          <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Tum mihi Piso: Quid ergo? Tum ille: Ain tandem? Non autem hoc: igitur ne illud quidem. Sed quod proximum fuit non vidit. Nos commodius agimus. An nisi populari fama?</p>
        </article>
        <article>
          <p>Social</p>
          <h3>Bestiarum vero nullum iudicium puto.</h3>
          <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Non igitur bene. Quid enim est a Chrysippo praetermissum in Stoicis? Pugnant Stoici cum Peripateticis. Prioris generis est docilitas, memoria; Apparet statim, quae sint officia, quae actiones.</p>
        </article>
      </section>
      <section>
        <h2>Testimonials</h2>
        <p>We are more than a digital company</p>
        <article>Testimonial 1</article>
        <article>Testimonial 2</article>
        <article>Testimonial 3</article>
      </section>
      <section>
        <h2>Contact</h2>
        <p>We like to know new people</p>
        <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Id Sextilius factum negabat. Quo tandem modo? At eum nihili facit; Quae contraria sunt his, malane?</p>
      </section>
    </main>
    <footer>
      Footer
    </footer>
  </body>
</html>



# HTML Advanced - Task 13: Styleguide paragraphs

## 📝 Overview
This task expands the styleguide document (`13-styleguide.html`) by introducing a dedicated paragraph section. This section serves to visually test and demonstrate subtitles and body paragraph text styling alongside headings.

## 📁 Repository Structure
* **GitHub repository:** `holbertonschool-web_front_end`
* **Directory:** `html_advanced`
* **File:** `13-styleguide.html`

## 🎯 Objectives & Requirements
* Copy the contents of `11-styleguide.html` into `13-styleguide.html`.
* Inside `<main>`, create a new `<section>` after the existing Headings section.
* Inside this new section:
  * Create a `<header>` containing an `<h2>` heading with the text `Paragraph`.
  * After the header, add an `<h2>` heading with text `Heading with a subtitle`.
  * Add a subtitle paragraph (`<p>This is my subtitle</p>`).
  * Add a second body paragraph containing the specified text block.

## 📄 File Content (`13-styleguide.html`)
```html
<!DOCTYPE html>
<html lang="en" dir="ltr">
  <head>
    <meta charset="utf-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0, viewport-fit=cover">
    <title>Styleguide - Techium</title>
    <meta name="description" content="Techium is a digital agency">
    <link rel="icon" type="image/x-icon" href="./favicon.ico">
    <link rel="icon" type="image/png" href="./favicon.png">
  </head>
  <body>
    <header></header>
    <main>
      <section>
        <header>
          <h2>Headings</h2>
        </header>
        <h1>Heading level 1</h1>
        <h2>Heading level 2</h2>
        <h3>Heading level 3</h3>
        <h4>Heading level 4</h4>
        <h5>Heading level 5</h5>
        <h6>Heading level 6</h6>
      </section>
      <section>
        <header>
          <h2>Paragraph</h2>
        </header>
        <h2>Heading with a subtitle</h2>
        <p>This is my subtitle</p>
        <p>Nunc lacinia ante nunc ac lobortis. Interdum adipiscing gravida odio porttitor sem non mi integer non faucibus ornare mi ut ante amet placerat aliquet. Volutpat eu sed ante lacinia sapien lorem accumsan varius montes viverra nibh in adipiscing blandit tempus accumsan.</p>
      </section>
    </main>
    <footer></footer>
  </body>
</html>



# HTML Advanced - Task 14: Span

## 📝 Overview
This task introduces the inline `<span>` element within the main page header. Using `<span>` allows wrapping small inline content or text fragments (such as logo text) to enable targeted styling and formatting without altering the block layout.

## 📁 Repository Structure
* **GitHub repository:** `holbertonschool-web_front_end`
* **Directory:** `html_advanced`
* **File:** `14-index.html`

## 🎯 Objectives & Requirements
* Copy the contents of `12-index.html` into `14-index.html`.
* Inside the primary site `<header>`, place a `<span>` element containing the text `Techium` directly **before** the `<nav>` element.

## 📄 File Content (`14-index.html`)
```html
<!DOCTYPE html>
<html lang="en" dir="ltr">
  <head>
    <meta charset="utf-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0, viewport-fit=cover">
    <title>Homepage - Techium</title>
    <meta name="description" content="Techium is a digital agency">
    <link rel="icon" type="image/x-icon" href="./favicon.ico">
    <link rel="icon" type="image/png" href="./favicon.png">
  </head>
  <body>
    <header>
      <span>Techium</span>
      <nav></nav>
    </header>
    <main>
      <h1>Homepage</h1>
      <section>
        <h2>We help you build your brand!</h2>
      </section>
      <section>
        <h2>Services</h2>
        <p>We work with you</p>
        <h3>Design & Concept</h3>
        <h3>Digital Strategy</h3>
        <h3>Content Strategy</h3>
        <h3>UX Design</h3>
        <h3>Web Development</h3>
        <h3>Social Media</h3>
      </section>
      <section>
        <h2>Works</h2>
        <p>Take a look in our portfolio</p>
        <article>
          <h3>Interior Design</h3>
        </article>
        <article>
          <h3>Web Development</h3>
        </article>
        <article>
          <h3>Personal Brand</h3>
        </article>
      </section>
      <section>
        <h2>About Us</h2>
        <p>Everything about us</p>
        <h3>Who are we</h3>
        <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit. Ipsum, omnis expedita! Eum, praesentium cumque accusantium rem, sit quaerat est nisi ratione, deserunt ducimus quidem iste dicta quibusdam atque maxime cum!</p>
        <h3>Our culture</h3>
        <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit. Ipsum, omnis expedita! Eum, praesentium cumque accusantium rem, sit quaerat est nisi ratione, deserunt ducimus quidem iste dicta quibusdam atque maxime cum!</p>
        <h3>How we work</h3>
        <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit. Ipsum, omnis expedita! Eum, praesentium cumque accusantium rem, sit quaerat est nisi ratione, deserunt ducimus quidem iste dicta quibusdam atque maxime cum!</p>
      </section>
      <section>
        <h2>Latest news</h2>
        <article>
          <p>Career</p>
          <h3>Hoc loco tenere se Triarius non potuit.</h3>
          <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Id Sextilius factum negabat. Quo tandem modo? At eum nihili facit; Quae contraria sunt his, malane?</p>
        </article>
