# Personal Portfolio 💻

This is a simple HTML and CSS project for a personal portfolio website. The portfolio showcases my skills, technologies I am proficient in, and a highlighted project. Additionally, it includes a contact form for visitors to get in touch with me.

## Features

**Header Section:** Introduction and links to my GitHub and LinkedIn profiles.

## Technologies Section:

A table listing front-end technologies and databases I am familiar with.
Highlighted Project: Details about a featured project, "Social Snakes", including a brief description.
Contact Form: A form where visitors can enter their name and a message to contact me.

## Code Structure

**HTML Elements:** Organized into sections with appropriate headings (`<h1>, <h2>, <h3>`), paragraphs (`<p>`), lists (`<ul>, <li>`), links (`<a>`), form inputs (`<input>, <textarea>`), and buttons (`<button>`).

**CSS Styles:** Defined within a `<style>` tag in the `<head>` section for basic styling:
Table Styling: Adjusted width, padding, and alignment to ensure the table is displayed correctly.

**Container Styling:** Minor adjustments to form elements to align the contact form nicely.

## How to Use

**View the Portfolio:** Open the index.html file in a web browser to view the portfolio.
Contact Me: Use the contact form to send a message. (Note: This form is static and does not include backend functionality for actually sending messages.)

## Contact
For any inquiries or further information, feel free to reach out via email at **meriquelmece@gmail.com.**


```html
<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Portafolio Personal</title>

    <style>
        .container textarea {
            display: flex;
            align-items: center;
            margin-right: 10px;
        }


        table {
            width: 30%;
            border-collapse: collapse;
        }

        th,
        td {
            width: 30%;
            vertical-align: top;
            padding: 5px;
        }

        th {
            text-align: left;
            padding-bottom: 0;


        }

        td {
            padding-top: 0px;
        }
    </style>

</head>

<body>
    <h1>!Hola¡ Soy Macarena Riquelme</h1>

    <div>
        <a href="https://github.com/mriquelmec">·Mi GitHub</a>
        <br>
        <a href="https://linkedin.com/macarenariquelmec">·Mi Linkedin</a>
    </div>
    <h2>Tecnologías que conozco</h2>

    <table border="0">
        <tr>
            <th>Front end</th>
            <th>Base de Datos</th>
        </tr>
        <tr>
            <td>
                <ul>
                    <li>Python</li>
                    <li>JavaScript</li>
                    <li>HTML5</li>
                    <li>CSS3</li>
                    <li>Bootstrap</li>
                    <li>React</li>
                </ul>
            </td>
            <td>
                <ul>
                    <li>Django</li>
                    <li>Express</li>
                    <li>MySQL</li>
                    <li>Flask</li>
                    <li>MongoDB</li>
                </ul>
            </td>
        </tr>
    </table>


    <div>
        <h2>Proyecto Destacado</h2>
        <h3>Social Snakes</h3>
        <p>Una aplicación de Redes Sociales hecha en Python- !Échale un vistazo al código!</p>
    </div>


    <div>
        <h2>Contáctame</h2>
        <label for="name">Nombre </label>
        <input type="text" id="name" data-name="Nombre" Value="">
    </div>
    <br>
    <div class="container">
        <label for="mensaje">Mensaje</label>
        <textarea data-name="mensaje" id="mensaje"></textarea>
    </div>
    <br>

    <button>Enviar Mensaje</button>
    <p>Email: meriquelmece@gmail.com</p>
    <p>Conceptos del Portafolio: AJAX, OOP, REST</p>


</body>

</html>
```

### *Project - Reference image*

![Reference image](/img/Portfolio-example-img.png)

