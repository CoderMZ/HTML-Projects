# Code Examples V(0.2)
On these HTML Files, I have finally used some base CSS things.
I have made 4 individual HTML files, which 3 of are linked to by the Index.html file.
So the goal was to make a business page, which links to different aspects of the Company.
It does work, but the CSS coding isn't done yet and it is all in the same file (HTML + CSS).
## Index.html
```html
<!DOCTYPE html>
<html>
    <head>
        <style type="text/css">
        button.buttonsgalore:hover {
            background: rgb(36,0,0);
            background: linear-gradient(0deg, rgba(36,0,0,1) 0%, rgba(200,0,255,1) 100%);
        }
        button.buttonsgalore {
             border: 20px;
             padding: 10px;
             width: 250px;
             height: 100px;
             margin: 10px;
             margin-top: 0px;
             margin-bottom: 0px;
             background: rgb(36,0,0);
             background: linear-gradient( 0deg, rgba(36,0,0,1) 0%, rgba(244,0,255,1) 100%);
             box-shadow: 10px 10px 15px silver; 
             font-size: 20px;
             color: white;
             border-radius: 20px;
             cursor: pointer;
        }
        div.Text_Wrapper{

            width: fit-content;
            height: fit-content;
            display: block;
            font-size: x-large;
            font-family: Arial, Helvetica, sans-serif;
            border: 2.5px solid violet;
            margin: 10px;
            padding: 5px;
            text-align: center;
        }
        .wrapper{
            display: flex;
            flex-direction: row;
            flex-wrap: wrap;
            justify-content: center;
        }
        </style>
        <title>Main Page</title>
    </head>
    <body>
        <div class="Text_Wrapper">
            <div>Sie befinden sich auf der Hauptwebseite. </div>
            <div>Falls sie auf eine weitere Seite gehen wollen dann drücken sie einen der untenstehenden Links.</div>
        </div>
        <div class="wrapper">
            <div class="btn1">
                <a href="Geschaeftsmodell.html">
                    <button class="buttonsgalore">Das Geschäftsmodell</button>
                </a>
            </div>
            <div class="btn2">
                <a href="Grund_fuer_einkauf.html">
                    <button class="buttonsgalore">Wieso bei uns?</button>
                </a>
            </div>
            <div class="btn3">
                <a href="">
                    <button class="buttonsgalore">Kontakt</button>
                </a>
            </div>
            <div class="btn4">
                <a href="">
                    <button class="buttonsgalore">Rechtliches</button>
                </a>
            </div>
        </div>
    </body>
</html>
```
