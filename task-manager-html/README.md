# Task Manager with HTML

In this lesson we will learn to build a simple task manager application using just the HTML.

## What we will build?
- Home Page (Header, List of tasks, Footer)
- Task Details Page
- Create Task Page
- Projects Page
- Project Details Page
- Create Project Page
- Users Page
- User Details Page
- Create User Page

## What is a website?
A website is a collection of interconnected web pages hosted on a web server and accessed via the internet using a unique address called a URL.

### How websites work?

- **Web Server**: A powerful computer connected to the internet that stores all the website's files (images, text, and code).
- **Web Browser**: An application like **Chrome**, **Safari**, or **Firefox** that you use to access the internet. This application renders your website.
- **The Request**: When you type a website's address (URL) into your browser, it sends a request to the server, which then delivers the requested web pages to your screen.
- **Web Pages**: A web page is a single document that can be displayed in a web browser. It can contain text, images, videos, and other multimedia elements.

## What is HTML?
HTML stands for **HyperText Markup Language**. It is the standard code used to structure a web page and its content. Think of it as the skeleton of a website.

### How HTML works?

- **Elements**: HTML uses "tags" to label different types of content called Elements.
- **Tags**: Tags usually come in pairs, like an opening tag and a closing tag. (Example: `<h1></h1>`).
- **Browsers**: Web browsers read this code and turn it into the visual pages you see.
- **Attributes**: HTML elements can have attributes that provide additional information about the element. (Example: `<a href="https://www.example.com">Link</a>`).
- **HTML Document**: An HTML document is a file that contains HTML code. It usually has a `.html` or `.htm` file extension.
- **HTML Document Structure**: To create a web page, we usually combine different HTML elements together.

Example of a HTML document structure:
```html
<!DOCTYPE html>
<html>
<head>
    <title>Task Manager</title>
</head>
<body>

</body>
</html>
```

### HTML Elements we will use in this project

- `html`: The root element that wraps the entire HTML document.
- `head`: Contains meta-information about the document, such as the title and links to stylesheets or scripts.
- `title`: Specifies the title of the document, which appears in the browser's title bar or tab.
- `link`: Used to link external resources, such as stylesheets. We will use this element in our **task-manager-html-css** project to link the CSS file to our HTML document.
- `script`: Used to include JavaScript code or link to external JavaScript files. We will use this element in our **task-manager-html-css-bootstrap-javascript** project to link the JavaScript file to our HTML document.
- `style`: Used to define internal CSS styles for the document. We will use this element in our **task-manager-html-css** project to add custom styles to our HTML document.
- `body`: Contains the content of the document that is displayed in the browser.
- `h1-h6`: Used to create headings.
- `p`: Used to create paragraphs.
- `br`: Used to create line breaks.
- `hr`: Used to create horizontal lines.
- `div`: Used to create a container for other elements.
- `span`: Used to group inline elements.
- `ul` and `ol`: Used to create unordered and ordered lists.
- `li`: Used to create list items within `ul` or `ol`.
- `a`: Used to create hyperlinks.
- `img`: Used to embed images.
- `table`, `thead`, `tbody`, `tr`, `th`, `td`: Used to create tables and their components.
- `b` and `strong`: Used to make text bold.
- `i` and `em`: Used to italicize text.
- `pre`: Used to display preformatted text.
- `form`: Used to create forms for user input.
- `label`: Used to define labels for form elements.
- `input`: Used to create input fields for user data.
- `textarea`: Used to create multi-line text input fields.
- `select` and `option`: Used to create dropdown lists.
- `checkbox`: Used to create checkboxes for user selection.
- `radio`: Used to create radio buttons for user selection.
- `button`: Used to create clickable buttons.

### What is semantic HTML?
Semantic HTML refers to the use of HTML tags that have a clear meaning and purpose, both for developers and browsers. It helps improve accessibility, SEO (Search Engine Optimization), and code readability.

#### Examples of semantic HTML elements:
- `header`: Represents the introductory content or a set of navigational links.
- `nav`: Represents a section of navigation links.
- `main`: Represents the main content of the document.
- `section`: Represents a standalone section of content.
- `article`: Represents a self-contained piece of content that could be distributed independently.
- `footer`: Represents the footer of a document or section, typically containing metadata or navigational links.

## Whats is Accessibility in HTML?
Accessibility in HTML refers to the practice of designing and developing web content that can be easily accessed and used by people with disabilities. This includes individuals with visual, auditory, motor, or cognitive impairments. The goal of accessibility is to ensure that all users, regardless of their abilities, can perceive, understand, navigate, and interact with web content effectively.

## Project Structure
Now that we have a basic understanding of HTML, let's create the project structure for our task manager application. The project will have the following structure:

```
task-manager-html
	├── index.html - Home Page
	├── task-details.html - Task Details Page
	├── create-task.html - Create Task Page
	├── projects.html - Projects Page
	├── project-details.html - Project Details Page
	├── create-project.html - Create Project Page
	├── users.html - Users Page
	├── user-details.html - User Details Page
	└── create-user.html - Create User Page
```

## Additional Resources
> To learn more about HTML, visit the [HTML Reference](https://www.w3schools.com/tags/default.asp) on W3Schools.