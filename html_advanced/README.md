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
