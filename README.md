# resume
making resume using hml and css
// html code
<html lang="en">
 
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport"
          content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="resumee.css">
</head>
 
<body>
    <div class="full">
        <div class="left">
            <div class="image">
                <img src=
"C:\Users\saurav\Desktop\sourav\PHOTO GAURAV FORM"
                     alt="gfg-logo"
                     style="width:100px;height:100px;">
            </div>
            <div class="Contact">
                <h2>Contact</h2>
                 
 
<p><b>Email id:</b>gauravshiromani@gmail.com</p>
 
 
 
                 
 
<p><b>Mobile no :</b>8591081463</p>
 
 
            </div>
            <div class="Skills">
                <h2>Skills</h2>
                <ul>
                    <li><b>Programming Languages :
                       Java, C/C++</b></li>
                    <li><b>Frontend : HTML5, CSS3,
                      </b></li>
                    <li><b>Backend : MySql</b></li>
                </ul>
            </div>
            <div class="Language">
                <h2>Language</h2>
                <ul>
                    <li>English</li>
                    <li>Hindi</li>
                </ul>
            </div>
            <div class="Hobbies">
                <h2>Hobbies</h2>
                <ul>
                    <li>Playing Basketball</li>
                    <li>Swimming</li>
                </ul>
            </div>
        </div>
        <div class="right">
            <div class="name">
                
 
 
 
            </div>
            <div class="Summary">
                <h2>Summary</h2>
                 
 
<p>To secure a challenging position in a
                  reputable organization
                    to expand my learning knowledge and skill
                </p>
 
 
 
            <br>
            
               
            <div class="Education">
                <h2>Education</h2>
                <table>
                    <tr>
                        <th>University/college  </th>
                        <th>Passing year  </th>
                        <th>percentage</th>
                    </tr>
                    <tr>
                        <td>kv2(12)</td>
                        <td>2019</td>
                        <td>61.8</td>
                    </tr>
                    <tr>
                        <td>kv2(10)</td>
                        <td>2017</td>
                        <td>86</td>
                    </tr>
                </table>
            </div>
            <div class="project">
                <ul>
                    <li>
                        <h2>Project1</h2>
                         
 
<p>This project is based on html
                          & used React</p>
 
 
 
                    </li>
                    <li>
                        <h2>Project2</h2>
                         
 
<p>This project is based on html
                          & used React</p>
 
 
 
                    </li>
                </ul>
            </div>
        </div>
    </div>
</body>
 
</html>

// css code 
 {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}
body {
    background-color: rgb(253, 254, 255);
    display: flex;
    justify-content: center;
    align-items: center;
}
.full {
    width: 50%;
    max-width: 1000px;
    min-height: 100px;
    background-color: rgb(245, 239, 231);
    margin: 0px;
    display: grid;
    grid-template-columns: 2fr 4fr;
}
.left {
    position: initial;
    background-color: rgb(126, 219, 231);
    padding: 20px;
 
}
.right {
    position: initial;
    background-color: rgb(162, 202, 206);
    padding: 20px;
 
}
.image, .Contact, .Skills, .Language, .Hobbies, .title,
.Summary, .Experience, .Education, .project {
    margin-bottom: 30px;
}
.h2 {
    background-color: rgb(4, 96, 150);
}
