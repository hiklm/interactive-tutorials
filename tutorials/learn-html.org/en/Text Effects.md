Tutorial
--------


Text-overflow can be used to hide an over flowing amount of text to make a section seem more clean. Two types of text-overflow are "clip" and "ellipsis," which cuts off text when over flowing out of a box. It'd be written in the style section like:

[[https://github.com/ronreiter/interactive-tutorials]]
<style> <br>
    h1.clip {<br>
        white-space: nowrap;<br>
        width: 100px;<br>
        border: 1px solid black;<br>
        overflow: hidden;<br>
        text-overflow: clip;<br>
    }<br>
    h1.ellipsis {<br>
        white-space: nowrap;<br>
        width: 100px;<br>
        border: 1px solid black;<br>
        overflow: hidden;<br>
        text-overflow: ellipsis;<br>
        }<br>
    </style><br>

Exercise
--------



[[https://github.com/ronreiter/interactive-tutorials]]
In this exercise, try to change text-overflow from clip to ellipsis.

Tutorial Code
-------------

    <!DOCTYPE html>
    <html>
        <head>
        <style>
        h1 {
            white-space: nowrap;
            width: 100px;
            border: 1px solid black;
            overflow: hidden;
            text-overflow: clip;
        }
        </style>
        </head>
        <body>
        <h1> lmao I'm gonna eat a sandwhich :D </h1>
        </body>
    </html>
    
Expected Output
---------------

    <!DOCTYPE html>
    <html>
        <head>
            <style>
        h1 {
            white-space: nowrap;
            width: 100px;
            border: 1px solid black;
            overflow: hidden;
            text-overflow: ellipsis;
        }
        </style>
        </head>
        <body>
        <h1> lmao I'm gonna eat a sandwhich :D </h1>
        </body>
    </html>

Solution
--------

    <!DOCTYPE html>
    <html>
        <head>
            <style>
        h1 {
            white-space: nowrap;
            width: 100px;
            border: 1px solid black;
            overflow: hidden;
            text-overflow: ellipsis;
        }
        </style>
        </head>
        <body>
        <h1> lmao I'm gonna eat a sandwhich :D </h1>
        </body>
    </html>
