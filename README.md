# Sheng Jargon 

![Sheng Jargon Logo](images/logo/sheng-jargon-img-logo.svg)

This is a digital *Sheng Jargon*. An app that is aimed at helping you understand words and expressions that are commonly used by sheng speakers.

The site can be navigated using the following navigation links:
```
 Home
 Jargon
 Categories
 Contact 
```

## UX

As a user I want to my *Sheng Jargon* to be easy to navigate, clearly labelled and intuitive so as to be able to have a pleasant experience while navigating the site.

This is the [Sheng Jargon Site PDF Mockup](images/screenshots/sheng-jargon-screenshot-site-layout.pdf) of how the site looks. 


## Features

### Colour palettes for this site are:

```
Background-color Hex code: #fff59d
Text color Hex code: #311b92
```

### Google Fonts

[Google Fonts](https://fonts.google.com/?query=jost&sidebar.open=true&selection.family=Josefin+Sans|Jost:wght@500)

```
Fonts Families:
    - Josefin Sans
    - Jost
```

#### General Page Layout

Each page is divided into four parts:
```
 nav
     Home
     Jargon
     Categories
     Contact
 
 header
     Paragraph

 main
     content

 footer
     copyright
```

### Existing Features


#### Home Page

Feature 1 (Quick Word Search) &mdash; *allows the user to enter a simple quick word search.*

```
 <form>
    <fieldset>
        <legend>Quick Word Search Form</legend>
            <div class="row">
                <div class="input-field col s12">
                    <input id="quick-word-search" type="text" class="validate">
                    <label for="quick-word-search">Quick Word Search</label>
                    <span class="helper-text" data-error="wrong" data-success="right">One Word or an expression</span>
                </div>
                </div>
                    <a class="waves-effect waves-light btn deep-purple darken-4">Search</a>
    </fieldset>
</form> 
```

Feature 2 (Advanced Word Search) &mdash; *allows the user to add more options in their word search.*

```
<form>
    <fieldset>
        <legend>Advanced Word Search Form</legend>
            <div class="row">
                <div class="input-field col s12 m6 l4 xl3">
                    <select>
                        <option value="" disabled selected>Choose your option</option>
                        <option value="adverb">Adjective</option>
                        <option value="adjective">Adverb</option>
                        <option value="determiner">Conjunction</option>
                        <option value="conjunction">Determiner</option>
                        <option value="noun">Interjection</option>
                        <option value="interjection">Noun</option>
                        <option value="pronoun">Preposition</option>
                        <option value="preposition">Pronoun</option>
                        <option value="verb">Verb</option>
                    </select>
                    <label>Part Of Speech</label>
                </div>
                <div class="input-field col s12 m6 l4 xl3 offset-xl1">
                    <select>
                        <option value="" disabled selected>Choose your option</option>
                        <option value="meaning">Meaning</option>
                        <option value="definition">Definition</option>
                    </select>
                    <label>Meaning or Definition</label>
                </div>
                <div class="input-field col s12 m6 l4 xl3 offset-xl1">
                    <select>
                        <option value="" disabled selected>Choose your option</option>
                        <option value="synonym">Synonym</option>
                        <option value="2">Antonym</option>
                    </select>
                    <label>Synonym or Antonym</label>
                </div>
                </div>
                <div class="row">
                    <div class="input-field col s12">
                        <input id="advanced-word-search" type="text" class="validate">
                        <label for="advanced-word-search">Advanced Word Search</label>
                        <span class="helper-text" data-error="wrong" data-success="right">One Word
                                                or an expression</span>
                </div>
            </div>
        <a class="waves-effect waves-light btn deep-purple darken-4">Search<a>
    </fieldset>
</form>
```

#### Jargon Page

Feature 3 (Word Jargon) &mdash; *allows the user to view the words in the jargon and also add, edit and delete.*
```
 Word
 Definition
 Meaning
 Synonyms
 Part Of Speech
 Alphabet
 Date Added
```

Feature 4 (Expression Jargon) &mdash; *allows the user to view the expressions in the jargon and also add, edit and delete.*
```
 Expression
 Definition
 Meaning
 Synonyms
 Part Of Speech
 Alphabet
 Date Added
```

Feature 5 (Browse Jargon by Alphabet) &mdash; *allows the user to browse through the words and expressions by selecting an alphabet.*
```
 Browse by Alphabet

     Aa Bb Cc Dd Ee Ff Gg Hh Ii Jj Kk Ll Mm Nn Oo Pp Qq Rr Ss Tt Uu Vv Ww Xx Yy Zz
```

#### Categories Page

Feature 6 (Categories) &mdash; *allows the user to manage the categories.*

```
 Word or 
 
     Word
     Expression

 Meaning of Word or Expression

 Definition or Word or Expression

 Synonyms of the word or expression

 Part of Speech

     Adjective
     Adverb
     Conjunction
     Determiner
     Interjection
     Noun
     Preposition
     Pronoun
     Verb
```

#### Contact Page

Feature 7 (Contact Form) &mdash; *allows the user to send feedback and/or a message to the App meaintenance team.*

```
<form>
    <fieldset>
        <legend>Contact Information</legend>
                    <input id="first_name" type="text" class="validate">
                    <label for="first_name">First Name</label> 
                    <input id="last_name" type="text" class="validate">
                    <label for="last_name">Last Name</label>
            <br>
            <div class="row">
                <div class="input-field col s12">
                    <input id="email" type="email" class="validate">
                    <label for="email">Email</label>
                    <span class="helper-text" data-error="wrong" data-success="right">
                                        We'll never share your email with anyone else.</span>
                </div>
            </div>
            <br>
            <div class="row">
                <div class="input-field col s12">
                    <textarea id="input-your-message" class="materialize-textarea" data-length="120"></textarea>
                    <label for="textarea2">Message</label>
                </div>
            </div>
            <br>
            <a class="waves-effect waves-light btn deep-purple darken-4">Submit</a>
    </fieldset>
</form>
```

### Features Left to Implement

```
 Forms
 Analytics
 Words
 Expressions
```

## Technologies Used in this Build

- [Materialize](https://materializecss.com/getting-started.html) &mdash; The Front-End web Framework used

- [Google Fonts](https://fonts.google.com/?query=jost&sidebar.open=true&selection.family=Josefin+Sans|Jost:wght@500) &mdash; The Font Families used

- [Heroku](https://www.heroku.com/) &mdash; Application Deployment

- [Python](https://www.python.org/downloads/) &mdash; Programming Language

- [Flask](https://flask.palletsprojects.com/en/1.1.x/) &mdash; Microframework written in Python

- [Stack Overflow](https://stackoverflow.com/) &mdash; Troubleshooting

- [MongoDB Atlas](https://www.mongodb.com/cloud/atlas) &mdash; Back-End NoSQL Database

- [Visual Studio Code](https://code.visualstudio.com/) &mdash; Editor used

## Testing

- [Testing Flask Applications](https://flask.palletsprojects.com/en/1.1.x/testing/#:~:text=Flask%20provides%20a%20way%20to,with%20your%20favourite%20testing%20solution.) &mdash; Used for testing

- [CSS Validator](http://www.css-validator.org/) &mdash; Validating CSS files

- Automated browser Testing [Google Lighthouse ext](https://developers.google.com/web/tools/lighthouse#devtools) 

- Testing was also conducted manually whereby friends and family browsed clicked the link sent and navigated through the site on various devices and gave their feedback in the process of making this site. 

- [Materialize Media Queries](https://materializecss.com/grid.html) allows me to stack the content into a single column on smaller devices such as smartphones; single and double columns on tablets and single, double or more columns on larger devices.

One bug that I have encountered in my testing  is... in my... file. [ bug]()

## Deployment

In order to deploy the application to heroku [Heroku](https://www.heroku.com/) read the following guidelines on how to [Deploy Python Flask App on Heroku](https://www.geeksforgeeks.org/deploy-python-flask-app-on-heroku/).

In order to deploy your site to [GitHub](https://github.com/) read the following guidelines on [Getting Started with GitHub Pages](https://guides.github.com/features/pages/). 

## Credits

### Content


- Below are examples of *Flask Applications* used as inspiration for my project 
* [Flask Mongo Task Manager](https://github.com/Code-Institute-Solutions/flask-mongo-task-manager) 
* [Flask Blog](https://github.com/CoreyMSchafer/code_snippets/tree/master/Python/Flask_Blog)
* [Flask Tutorial](https://github.com/pallets/flask/tree/1.1.2/examples/tutorial)


### Media

The image placeholder slides used in this project are in the SVG format and were drawn by myself using adobe Xd. Equally the logo is also in SVG format and was designed by myself using Adobe Illustrator. 

### Acknowledgements

My biggest inspiration with this project is to create a platform that the user can be able to look up the meanings and definitions of certain words and expressions used by sheng speakers. 