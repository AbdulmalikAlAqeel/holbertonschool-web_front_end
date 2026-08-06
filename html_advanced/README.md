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
