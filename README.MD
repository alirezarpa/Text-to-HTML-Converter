# Text to HTML converter

## Video Demo: https://youtu.be/4UfPZLqpPkY

## programming by:

- Alireza Rahimipour Anaraki

## Introduction:
Being a web framework, Django needs a convenient way to generate HTML dynamically. The most common approach relies on templates. A template contains the static parts of the desired HTML output as well as some special syntax describing how dynamic content will be inserted.A Django project can be configured with one or several template engines (or even zero if you don’t use templates). Django ships built-in backends for its own template system, creatively called the Django template language (DTL), and for the popular alternative Jinja2. Backends for other template languages may be available from third-parties.Django defines a standard API for loading and rendering templates regardless of the backend. Loading consists of finding the template for a given identifier and preprocessing it, usually compiling it to an in-memory representation. Rendering means interpolating the template with context data and returning the resulting string.
A Django template is a text document or a Python string marked-up using the Django template language. Some constructs are recognized and interpreted by the template engine. The main ones are variables and tags. A template is rendered with a context. Rendering replaces variables with their values, which are looked up in the context, and executes tags. Everything else is output as is.

The syntax of the Django template language involves four constructs.
Have you ever wondered to write just simple text in a text editor and got a html code for it something similar to text to html converter. It would be amazing that you can write an HTML code without actually writing it. Being a part of the technical field we have to learn a programming language, its syntax, its function and so on, which is not enough in this competitive era where learning one programming language is not enough. So it would be awesome to lighten the burden of at least one language where you don’t need to learn programming language and get a code for it. Yes you are getting it correct, we are talking about text to html converters. One of the simple Django projects ideas would include a text to HTML converter. You can create an interface where you can enter text or upload documents, and it gets converted to clean HTML code. This application can make your HTML coding easier and save time. I'm going to create a text to html converter using a django template, it is going to be really cool.
We are going to use django for the template and text editor, and javascript for converting the text. Let’s learn how to create your very own text to html converter. The purpose of this project is to quickly generate content and text or even create random text for frontend or even backend testing. Due to the convenience of the program, you can easily build and develop a project. On the site, after clicking the convert option, the code will be converted and you can use it on your site.

## Distinctiveness and Differences:
1. Unique Functionality: While Project 2 focused on building a traditional e-commerce site, our Text-to-HTML Converter offers a distinct and innovative functionality. It provides users with the ability to convert plain text into HTML code effortlessly, catering to content creators, bloggers, and developers who need to format text for web content.

2. Writing Models: Unlike Project 2, which centered on product listings and shopping features, our project introduces the concept of "writing models." Each writing model is tailored to a specific type of content, such as a blog post, technical documentation, or social media post. This specialization ensures that the generated HTML is optimized for the intended purpose.

3. Formatting Automation: The Text-to-HTML Converter automates the process of formatting HTML code. Users do not need to manually write HTML tags for headings, paragraphs, lists, or links. Instead, they can select the desired formatting options, and the application generates the corresponding HTML code.

## Complexity:
1. Frontend-Backend Interaction: Our project involves intricate communication between the frontend and backend. The user input is captured on the frontend, and the selected writing model and formatting options are sent to the backend. The backend then processes the input and generates the appropriate HTML code, which is sent back to the frontend for preview and copying.

2. Multiple Writing Models: Implementing multiple writing models requires designing a flexible architecture that can handle varying HTML structures. Each writing model has its own set of formatting rules and requirements, adding complexity to the codebase.

3. Real-time Preview: Enabling users to preview the HTML output in real-time involves dynamic updates on the frontend. This requires integrating JavaScript to display the formatted content as users make selections, enhancing the user experience.

4. User Customization: Allowing users to customize formatting options involves creating a user-friendly interface that dynamically adjusts based on user selections. The backend must interpret these selections and apply the appropriate formatting rules to generate accurate HTML code.

5. Integration of Writing Models: Implementing and maintaining multiple writing models necessitates a structured approach to code organization. Each model requires distinct logic and rules for HTML generation, which must be seamlessly integrated into the application's architecture.

6 Responsive Design: Our project's complexity extends to ensuring a seamless user experience across different devices and screen sizes. Implementing responsive design requires adapting the frontend layout and styles to provide optimal usability on various devices.

In summary, the Django Text-to-HTML Converter project distinguishes itself from Project 2 by offering a unique functionality focused on text-to-HTML conversion with writing models. The complexity arises from handling frontend-backend interactions, multiple writing models, real-time preview, user customization, and responsive design. These elements collectively contribute to a project that challenges traditional e-commerce structures and delivers a novel and valuable tool for content creators and developers.

## Description:
The Text to HTML Converter is a command-line tool that converts plain text files to HTML format. This tool is designed to simplify the process of converting text files to HTML, making it easy for users to create web pages or format text for web publication.

Usage
The Text to HTML Converter can be used to convert any plain text file to HTML format. To use the converter, simply run the convert.py script and provide the path to the input file. The converter will then generate an HTML file with the same name as the input file.

For example, if you have a text file called mytext.txt, you can convert it to HTML format by running the following command:

Copy code
python convert.py mytext.txt
After running this command, the converter will create a new file called mytext.html, which will contain the HTML version of your text file.

Supported Formatting
The Text to HTML Converter supports a variety of basic formatting options, including headings, paragraphs, lists, and links. These formatting options can be used to create a wide range of HTML documents, from simple blog posts to complex web pages.

To create a heading, simply start a new line with one or more # symbols, followed by the heading text. For example:

# My Heading
This will create a top-level heading in your HTML document. You can create subheadings by using more # symbols, like this:

## My Subheading
To create a paragraph, simply add your text on a new line. The converter will automatically wrap your text in <p> tags, like this:

This is a paragraph of text. It will be wrapped in <p> tags when converted to HTML.
To create a list, start a new line with either a - or * character, followed by your list item text. For example:

- List item 1
- List item 2
- List item 3
This will create an unordered list in your HTML document. You can create an ordered list by starting each line with a number, like this:

1. List item 1
2. List item 2
3. List item 3
Finally, to create a link, enclose the link text in square brackets, followed by the URL in parentheses. For example:

This is a [link](https://www.example.com/) to an external website.
Conclusion
The Text to HTML Converter is a simple but powerful tool that makes it easy to convert plain text files to HTML format. With support for basic formatting options like headings, paragraphs, lists, and links, this tool is perfect for anyone who needs to create web content quickly and easily. Whether you're a blogger, a content marketer, or a web developer, the Text to HTML Converter is a must-have tool in your arsenal.

## Quick Revision
* Create your django project folder.
* Create an app folder in the django project folder.
* Install django-ckeditor.
* Add template folder in the django folder and provide its path in django_folder > settings.py .
* Add file named as urls.py in the app folder and provide its path in django_project > urls.py.
* Create a model for Editor class in app_folder > models.py.
* Create a form for the model in app_folder > forms.py.
* Write html code for the converter in django_project > template > index.html.
* Add path of index html page in app_folder > urls.py.
* Create function for the index html page in app_folder >views.py.

## Technology stack:

-   HTML
-   JavaScript
-   CSS
-   Python – Django

### Installation-

1] Star and clone the repository to your machine.

2] To use the Text to HTML Converter, you will need to install Python 3 on your system. Once Python is installed, you can download the source code for the converter from GitHub. After downloading the source code, you can install the converter using pip, which is a package installer for Python.

3] Run the command `pip install -r requirements.txt`