Tutorial
--------
The height and width properties are used to set the height and width of an element. The height and width can be set to auto, which lets the browser calculate it's height and width values or can be specified with units such as px and rem. The max-width or max-height property is used to set the maximum width of an element. The min-width or min-height property are used to set the minimum width of an element.

[[https://github.com/ronreiter/interactive-tutorials]]

Exercise
--------

This page does not have an exercise yet. You are welcome to contribute one by sending me a pull request:

[[https://github.com/ronreiter/interactive-tutorials]]


Tutorial Code
-------------

    <!DOCTYPE html>
    <html>
        <head>
        <title> Hello World </title>
        <style>
        div {
        height: 300px;
        width: 400px;
        background-color: lightblue;
        font-size: 35px;
       }
        </head>
        </style>
        <body>
        <div> Hello, world!</div>
        </body>
    </html>
    
Expected Output
---------------

Create an element that has a height of 400px and a width of 300px with a background-color of green. Then create a different element with a width of auto and a height of 200px with a 2px solid black border. Put all the additions of your element in the style portion of the page.

Solution
--------

    <!DOCTYPE html>
    <html>
        <head>
        <style>
            <title>Hello, World!</title>
        .e1 {
        height: 400px;
        width: 300px;
        background-color: green;
        }
        .e2 {
        height: 200px;
        width: auto;
        border: 2px solid black;
        }
        </head>
        </style>
        <body>
        <div class="e1">Hello, world! </div>
        <div class="e2"> Hello, world! </div>
        </body>
    </html>
