<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
</head>
<body>
    <div>
        <h1>
            REGISTRATION FORM
        </h1>
    </div>
    <br>
    <div>
        <FORM action="https://www.youtube.com/search">
            <input type="text" placeholder="first name">
            <input type="text" placeholder="last name">
            <br> 
            <label for="gender">please select gender</label>
            <select name="gender" id="gender">
                <option value="male" selected male>male</option>
                <option value="female">female</option>
                <option value="other">other</option>
            </select>
    <br>
            <label for ="condition">do you agree all term and condition</label>
            <input type="checkbox" name="condition" id="condition">
        </FORM>
    </div>
    <button style="color:white";background-color:green>submit</button>
    <div>
        <table  border="white">
            <caption>Student information</caption>
            <tr>
                <th rowspan="6">info</th>
                <th rowspan="2">name</th>
                <th colspan="2"> address</th>
            </tr>
            <tr>
                <th>city</th>
                <th>house</th>

            </tr>
            <tr>
                <td>a</td> 
                <td>delhi</td>
                <td>1</td>
            </tr>
            <tr>
                <td>b</td>
                <td>mumbai</td>
                <td>2</td>
            </tr>
            <tr>
                <td>c</td>
                <td>kolkata</td>
                <td>3</td>
            </tr>
            <tr>
                <td>d</td>
                <td>pune</td>
                <td>
                    4
                </td>
            </tr>
        </table>
    </div>
    <div>
        <form action="/action">
            <label for="name">name</label>
            <input type="text" id="name">
            <br>
            <label for ="sex">sex:</label>
            <input type="radio" id="sex" name="s">
           
            <input type="radio" id="male" name="s">
            <label for ="male">male</label>
            <input type="radio" id="female" name="s">
            <label for ="female">female</label>
            <br>
            <label for ="country">country</label>
            <select name="country" id="country">
                <option value="select" selected>select the option</option>
                <option value="india" >india</option>
                <option value="usa">usa</option>
                <option value="nepal">nepal</option>
                <option value="buthan">buthan</option>


            </select>
            <label for ="message">massage</label>
            <textarea id="message" name="message"></textarea>
            <button>subscribe</button>


        </form>
        <div>
            <form action ="/action">
            <h1> Feedback Form</h1>
            <label for="name">name</label>
            <input type="text" id="name">
            <br>
            <label for="email">email</label>
            <input type="type" id="email">
            <br>
            <label for="message">Message</label>
            <textarea id="message"></textarea>
            <br>
            <label >Rate us our of 5:</label>
            <label for="1">1</label>
            <input type="radio" name="rate" id="1" value="1">
            <br>
            <label for="2">2</label>
            <input type="radio" name="rate" id="2" value="2">
            <br>
            <label for="3">3</label>
            <input type="radio" name="rate" id="3" value="3">
            <br>
            <label for="4">4</label>
            <input type="radio" name="rate" id="4" value="4">
            <br>
            <label for="5">5</label> 
            <input type="radio" name="rate" id="5" value="5">
            <button>send your message</button>
        </form></div>
    </div>
    <hr>
    <div>
    
    <h2>Video Display</h2>
    <video width="600" controls>
        <source src="video.mp4" type="video/mp4">
        Your browser does not support the video tag.
    </video>
    
    <h2>Image Display</h2>
    <img src="image.jpg" alt="Sample Image" width="60">

    </div>

</body>
</html># hp-project
