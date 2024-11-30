<!Doctype html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport"content="width=device-width,initial -scale=1.0">
    <title> Weather application</title>
    <h3>Welcome to our Wearther application</h3>
            <style>
                button{
                    color: white;
                    background-color: rgb(109,10,56);
                    border-radius: 3px;
                    height: 30px;
                    width: 80px;
                    border: none;
                    cursor: pointer;
                }
                .enter{
                    padding-top: 5;
                    background-color: white;
                    border-radius: 4px;
                    height: 80px;
                    width: 700px;
                    border: 4px;
                

                }
                h3{
                    margin-right: 80px;
                    text-align:center;
                    text-decoration: underline;
            color: darkolivegreen;
                }
                .names{
                    color: rgb(109,10,56);
                    font-weight: 15px;
                    block-size: auto;
                }
                body{
                    
                    background-color: rgb(138,128,128);
                    border-radius: 10px;
                    padding: 10px;
                    
                    
                    border: 10px;
                    margin-top: auto;
                    
                    align-items: center;
                    
                }
                h1{
                
                    text-align: center;
                    margin-right: 50px;
                }
    
                
                .day{
                    color: rgb(109,10,56);
                    display: inline-block;
                    margin-left: 6px;
                }
                .highlight{
                    color: rgb(109,10,56);
                    font-weight: bold;
                }
                button:hover{
                    background-color: blue;

                }
                .degrees{
                      display:flex ;
                      color: rgb(109,10,56);
                      font-weight: bold;
                }
                .degrees p{
                    margin: 0 10px;
                }
                p{
                    text-align: left;
                }
                .fade{
                    color:  rgb(109,10,56,0.5);
                }
                .links{
                
                
                font-weight: bold;
                    color: rgb(109,10,56,0.5);
                }
                .temperature{
                    font-size: 50px;
                    font-weight: bold;
                }
                .degrees-symbol{
                    font-size: 16px;
                }
                .heading{
                    margin: 0;
                }
                .heading-wrapper{
                    display: flex;
                    justify-content: space-between;
                    align-items: center;
                    padding: 10px;
                }
                footer{
                    
                      color: rgba(15, 11, 34, 0.4);

                }
            </style>
        
        <body>
        <h1>
            <input type="Enter"placeholder="Enter city name"class="ener">
            <button>
                search
            </button>
            <div class="heading-wrapper">
                <h2 class="heading">Paris</h2>
                <span class="temperature">🌦12°c</span>
            </div>
            <p>
                Tuesday 07:45,scattered clouds<br>
                Humidity:<span class="highlight">66</span>,wind speed:4.3
            </p><br>
            <table>
                <tr>
                    <th><div class="day"></div><span>Mon</span></th>
                    <th><div class="day"></div><span>Tue</span></th>
                    <th><div class="day"></div><span>Wed</span></th>
                    <th><div class="day"></div><span>Thur</span></th>
                    <th><div class="day"></div><span>Fri</span></th>
                    <th><div class="day"></div><span>Sat</span></th>
                    <th><div class="day"></div><span>Sun</span></th>
                </tr>
                <tr>
                    <td>🌦<div class="degrees">
                        <p>15°</p>
                        <p classs="fade">19°</p>
                        </div>
                    </td>
                    <td>🌦<div class="degrees">
                        <p>15°</p>
                        <p classs="fade">19°</p>
                        </div>
                    </td>
                    <td>🌦<div class="degrees">
                        <p>15°</p>
                        <p classs="fade">19°</p>
                        </div>
                    </td>
                    <td>🌦<div class="degrees">
                        <p>15°</p>
                        <p classs="fade">19°</p>
                        </div>
                    </td>
                    <td>🌦<div class="degrees">
                        <p>15°</p>
                        <p classs="fade">19°</p>
                        </div>
                    </td>
                    <td>🌦<div class="degrees">
                        <p>15°</p>
                        <p classs="fade">19°</p>
                        </div>
                    </td>
                    <td>🌦<div class="degrees">
                        <p>15°</p>
                        <p classs="fade">19°</p>
                        </div>
                    </td>
                </tr>

            </table>
           <footer>
            <p> 
                coded by <a href="http://github.com/Munoko"><span class="links">Munoko Isaiah</span></a>
                and is on<a href="http://github.com/"><span class="links">Github</span></a>
                and<a href="http://www.netlify.com/"><span class="links">hosted by Netlify.<br></span></a>
                The design was done uding
                <a href="Figma.com"><span class="links">Figma</span></a>
            </p>
           </footer>
        </h1>
    </body>
    </head>
    </html># CIS-221-CAT-2
