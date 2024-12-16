# Tech-website-using-only-HTML
This a basic html program which generates the structure of a website 
login page 


<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
</head>
<body>
    <h1> LOGIN </h1>
    <form action="form.html">
        <label for="'">username: </label><input type="text" name="" id=""><br><br>
        <label for="">Password </label><input type="password" name="" id=""><br><br>
        <input type="checkbox" name="" id=""> <label for=""> show password</label>
        <button><a href="website.html">submit</a></button>
        <input type="button" value="Cancel">

    </form>
</body>
</html>



SIGN UP PAGE

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
</head>
<body>

        <legend>Student_Details</legend>
        <fieldset>
            <legend>Personal</legend>
            <table>
                <tr>
                    <td><label for="a">FIRST_NAME</label></td>
                    <td><input type="text" id="a" placeholder="Enter Your First Name"></td>
                </tr>
                <tr>
                    <td><label for="b">LAST_NAME</label></td>
                    <td><input type="text" id="b" placeholder="Enter Your Last Name"></td>
                </tr>
                <tr>
                    <td><label for="c">FATHER'S_NAME</label></td>
                    <td><input type="text" id="c" placeholder="Enter Your Fathers Name"></td>
                </tr>
                <tr>
                    <td><label for="d">MOTHER'S_NAME</label></td>
                    <td><input type="text" id="d" placeholder="Enter Your Mothers Name"></td>
                </tr>
            </table>
        </fieldset>
        <fieldset>
            <legend> contact</legend>
            <table>
                <tr>
                    <td><label for="a"> Mobile Number</label></td>
                    <td><input type="text" id="a" ></td>
                </tr>
                <tr>
                    <td><label for="t">Gmail</label></td>
                    <td><input type="text" id="t"></td>
                </tr>
                <tr>
                    <td><label for="r">Address</label></td>
                    <td><input type="text"  id="r"></td>
                </tr>
                <tr>
                    <td><input type="text"></td>
                    <td><input type=""></td>
                </tr>
                <tr>
                    <td colspan="1"><input type="text"></td>
                    <td><!--input type="text">--></td>
                </tr>
                <tr>
                    <td><label for="i" >PIN</label></td>
                    <td><input type="text" id="i"></td>
                </tr>
                <tr>
                    <td><label for="i">Country</label></td>
                    <td>
                        <select>
                            <hidden>--CHOOSE_HERE--</hidden>
                            <option>India</option>
                            <option>China</option>
                            <option>USA</option>
                            <option>UK</option>
                            <option>UAE</option>
                        </select>
                    </td>
                </tr>
                <tr>
                    <td><label >State</label></td>
                    <td> 
                        <select>
                            <option>--CHOOSE_HERE--</option>
                            <option>kerala</option>
                            <option>maharashtra</option>
                            <option>Andrapradesh</option>
                            <option>Newyork</option>
                            <option>Washinton</option>
                            <option>chicago</option>

                        </select>
                    </td>
                </tr>
                <tr>
                    <td><label>District</label></td>
                    <td>
                    <select> 
                        <option>--CHOOSE_HERE--</option>
                        <option>Thrissur></option>
                        <option>kochi</option>
                        <option>Anathapuram</option>
                        <option>Kollam</option>
                    </select>
                    </td>
                </tr>
            </table>
        </fieldset>
    <fieldset>
        <legend>Educational Qualiification</legend>
        <h5>Higher Qulification</h5>
        Choosse your Domain:
        <input type="radio" name="domain" id="dev"><lebel for="dev">B.tech</lebel>
        <input type="radio" name="domain" id="test"><lebel for="test">M.tech</lebel>
        <input type="radio" name="domain" id="devops"><lebel for="devops">MCA</lebel>
        <input type="radio" name="domain" id="tech"><lebel for="tech">BCA</lebel>
        <input type="radio" name="domain" id="tech"><lebel for="tech">BSC</lebel>
        <input type="radio" name="domain" id="tech"><lebel for="tech">B.com</lebel>
        <input type="radio" name="domain" id="tech"><lebel for="tech">Other</lebel><br>
        <label >If other</label><input type="">
        <h5><Details></Details></h5>
        Choosse your Branch:
        <input type="radio" name="domain" id="dev"><lebel for="dev">CS</lebel>
        <input type="radio" name="domain" id="test"><lebel for="test">AI</lebel>
        <input type="radio" name="domain" id="devops"><lebel for="devops">EEE</lebel>
        <input type="radio" name="domain" id="tech"><lebel for="tech">CE</lebel>
        <input type="radio" name="domain" id="tech"><lebel for="tech">CY</lebel>
        <input type="radio" name="domain" id="tech"><lebel for="tech">ECE</lebel>
        <input type="radio" name="domain" id="tech"><lebel for="tech">Other</lebel><br>
        <label >If other</label><input type=""><br><br>
        <label for="o">University</label>
        <input type="text" placeholder="enter your University">
       <br><br>
        <label for="o">College Name</label>
        <input type="text" placeholder="enter your College Name"><br><br>
        <label for="o">Skills</label>
        <select>
            <option>--CHOOSE_HERE--</option>
                        <option>programming</option>
                        <option>Network</option>
                        <option>AI</option>
                        <option>DS</option>
                        <option>ML</option>
                        <option>CY</option>
                        <option>DA</option>
                        <option>SQL</option>
                        <option>Web</option><br>
                     <br><br>
<h5>Choosse your main Programming Language:</h5>
<input type="radio" name="domain" id="dev"><lebel for="dev">Python</lebel>
<input type="radio" name="domain" id="test"><lebel for="test">java</lebel>
<input type="radio" name="domain" id="devops"><lebel for="devops">SQL</lebel>
<input type="radio" name="domain" id="tech"><lebel for="tech">HTML</lebel>
<input type="radio" name="domain" id="tech"><lebel for="tech">PHP</lebel>
<input type="radio" name="domain" id="tech"><lebel for="tech">MERN</lebel>
<input type="radio" name="domain" id="tech"><lebel for="tech">PEARL</lebel><br>

        </select>

    </fieldset>
    <fieldset>
        <legend>Placement</legend>
        <h4>Designation</h4><br>
        <input type="radio" name="domain" id="dev"><lebel for="dev">Developer</lebel>
        <input type="radio" name="domain" id="test"><lebel for="test">Engineer</lebel>
        <input type="radio" name="domain" id="devops"><lebel for="devops">Backend Developer</lebel>
        <input type="radio" name="domain" id="tech"><lebel for="tech">frontend Developer </lebel>
        <input type="radio" name="domain" id="tech"><lebel for="tech">Technical support</lebel>
        <input type="radio" name="domain" id="tech"><lebel for="tech">NON Tech</lebel>
        <input type="radio" name="domain" id="tech"><lebel for="tech">Testing</lebel><br><br>
        <h4>preferred Location</h4><br>
        <input type="radio" name="domain" id="dev"><lebel for="dev">Delhi</lebel>
        <input type="radio" name="domain" id="test"><lebel for="test">Kochi</lebel>
        <input type="radio" name="domain" id="devops"><lebel for="devops">Pune</lebel>
        <input type="radio" name="domain" id="tech"><lebel for="tech">Goa </lebel>
        <input type="radio" name="domain" id="tech"><lebel for="tech">Munbai</lebel>
        <input type="radio" name="domain" id="tech"><lebel for="tech">Chennai</lebel>
        <input type="radio" name="domain" id="tech"><lebel for="tech">Hydrabad</lebel><br><br>
        <h5>Expected Salary</h5>
        <input type="radio" name="domain" id="dev"><lebel for="dev"> less than 3 LPA</lebel>
        <input type="radio" name="domain" id="dev"><lebel for="dev">3-6 LPA</lebel>
        <input type="radio" name="domain" id="dev"><lebel for="dev">6-10 LPA</lebel>
        <label>Upload Resume</label><input type="image">

    </fieldset>
    <fieldset>
        <legend>Accounts</legend>
        <table>
            <tr>
                <td><lebel for="dev">Set User Name</lebel></td>
        <td>  <input id="dev" > </td>
            </tr>
            <tr>
                <td> <lebel for="dev">Set Password</lebel></td>
                <td><input type="password" id="dev"> </td>
            </tr>
        </table>
    </fieldset><h1>
        <input type="radio" name="domain" id="dev"><lebel for="dev">Agree T & C</lebel>
        <a href="login.html" target=""_blank><input type="submit" value="login page" ></a>
        <input type="button" value="Cancel"></h1>

</body>
</html>



WEBSITE 
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
</head>
<body>
    <h1 align="center"> Welcome to the Tech World</h1>
    <img src="data:image/png;base64,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" height="60 px" width="70px"></img>
<hr color="black">
<h1 align="center"> Gallery</h1>
<img src="https://i0.wp.com/www.techquintal.com/wp-content/uploads/2017/01/Modern-Technology.jpg?fit=1024%2C576&ssl=1"height="200px" width="300px">
<img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcRAU3e5xiEUmtCmtK48BMmOPEI1rzKgg7uDqQ&s"height="200px" width="300px">
<img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcQp3GnoHIbJ3H-gQV5xB7DPddpJIpD5cYRdeg&s"height="200px" width="300px">
<img src="https://www.how2shout.com/wp-content/uploads/2021/09/modern-technology-is-impacting-our-daily-life.png"height="200px" width="252px">
<img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcT-8ImgO1FXggjRk79d7YgKCbEGCWdFSkb_KSxL_3bYVEze3M0B5z03ghU6VTpDXP3RQcM&usqp=CAU"height="200px" width="300px">
<img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcQ3-TW2T5Ol8VMjpYuWY_ot-KciBrqn6FSUXg&s"height="200px" width="300px">
<img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcRAwmspC4pOhTuINBe7aZiVdgc-TG4p841XSg&s"height="200px" width="300px">
<img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcQb_WvJuKGYQQnN5eG81l8cmC6AQr8mNH-eXw&s"height="200px" width="252px">
<img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcTpeY6N0Ed_y4KyVV0K0MpV7YiA3hSZQp0JaA&s"height="200px" width="300px">
<img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcQ8rbgqHgGoK_E9Mw3d8uxKIuZbsxxQs0Cyfw&s"height="200px" width="300px">
<img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcS0eMa-aEv4DES3fLFYaW6Z04feNPKlSM_0IQ&s"height="200px" width="300px">
<img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcSQ0FLcrTp8lZ63ZvFJNPscKDgOlrPJZPX52w&s"height="200px" width="252px">
<img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcTEv7x1rwwX4Pmh79z1gxTZiqG47wmBNpUnUA&s"height="200px" width="300px">
<img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcREazRKTfdZmgy6GlZom6Ijj5HIOQnTSgN0SQ&s"height="200px" width="300px">
<img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcQ2KzaG6CxIS7aqOhT4PdNNFWbYRtUQ38aYyw&s"height="200px" width="300px">
<img src="https://image.slidesharecdn.com/moderntechnology-161104124828/85/Modern-technology-2-320.jpg"height="200px" width="252px"> 
<hr>
<h1  Align="center"> ABOUT</h1>
<p align="justify">The study of computers and society began in the aftermath of World War II, with the diffusion of com
    puters in government and private enterprise, and has flourished since with the rapid advance and convergence of c
    omputing and telecommunications. Since the early 1990s, the explosive growth of the Internet and World Wide Web made in
    formation and communication technologies (ICTs) an aspect of everyday life in advanced industrial societies, and spawned increased soci
    al and humanistic study of their social impacts. Social and behavioral scientists have criticized prominent utopian and dystopian pers
    pectives on the social ‘impacts’ of ICTs 
    on influence, democracy, community, and the economy as overly deterministic. They have also developed a number of useful perspectives on the social shaping of technologie
    s and their societal consequences, including approaches to research that place computers and telecommunications within frameworks focused on the study of technology and so
    ciety, ICT strategies, and the information society. A new perspective on tele-access, which focuses on the study of how technical and social
     choices shape access to information, people, services, and technology, provides one means to integrate the study of all ICTs across socia
     l issues and levels of analysis, from the individual and household to an increasingly networked world.
     Early discussion of computers and telecommunications reflected this concern that modern technology is becoming an unstoppable force which would support increasingly centralized control in organizations and society. Many observers of the social impacts of more recent advances in ICTs argue the opposite—that the convergence of computing and networking has decentralized control over the technology and placed more control in the hands of users (de Sola Pool 1983). Nevertheless, many others continue to argue that ICT innovations are empowering a new elite of experts, who have the skills and knowledge to control networks in organizations and society.
     Technology concerns more than just equipment. It also encompasses the knowledge that is essential to its use (MacKenzie and Wajcman 
     1985, p. 3). The control of technology is, therefore, bound up with issues of who has access to the skills, equipment, and know-how 
     essential to design, implement, and employ technology. Changes in technology can, therefore, restrict access to all these resources. 
     For instance, early mainframe computers depended on programmers with knowledge of specialized programming languages. But technological 
     change can equally expand access, for example, by the way simple graphical user interfaces with the Web have made access to information 
     stored on millions of computers available to users round the world at the click of a mouse button. Likewise, social choices, such as the 
     decision to learn a new human or computer language, affect access to technology, jobs, and people. The ways in which technical and social 
     choices shape access to ICTs has been central to th
     e technological perspective, but was often lost in a body of work covering myriad concerns at all levels of analysis and across all techn
     ology.</p>
     <h1 align="center">VIDEOS</h1>
     <video src="https://cdn.pixabay.com/video/2016/09/13/5074-182666828_large.mp4"controls height="300px width=250px"></video>
     <video SRC="https://media.istockphoto.com/id/1360048537/video/futuristic-animated-concept-big-data-center-chief-technology-officer-using-laptop-standing-in.mp4?s=mp4-640x640-is&k=20&c=qfseEZiJxfYc26fY6oD2hRZp4stCUQAHBxFgbPJCrKc="controls height="300px width=250px"></video>
<hr>
<h1>AUDIOS</h1>
<audio src="https://pixabay.com/music/beats-vlog-music-beat-trailer-showreel-promo-background-intro-theme-274290/" controls></audio>
<iframe src="https://en.wikipedia.org/wiki/Technology" height="600px" width="95%"></iframe>
<hr>
<h1 align="center">LIST</h1>
<p> list of MODERN Technology</p>
<ul>
    <li>AI</li>
    <li>DS</li>
    <ul>
        <li>ML</li>
        <li>ROBOTICS</li>
        <li>CYBER SECURITY</li>
        <li>HACKING</li>
    </ul>
    <li>BLOCKCHAIN</li>
    <li>IOT</li>
    <li>TRASPORT</li>
    <li>CC</li>
    <li>MOBILE</li>
    <li>SMART</li>
</ul>
    <li>VI</li>
    <li>HEALTH Technology</li>
    <li>5G</li>
    <li>6G</li>
    <li>AUTOMATION</li>
    <li>BUSINESS Technology</li>
    <li>NS</li>
    <li>INTERNET</li>
</ul>
     <table border="1">
        <tr>
            <td>iugig</td>
            <td>iugig</td>
            <td>iugig</td>
            <td>iugig</td>
            <td>iugig</td>
            <td>iugig</td>
            <td>iugig</td>
            <td>iugig</td>
        </tr>
        <tr>
            <td>kjrfjehf</td>
            <td>kjrfjehf</td>
            <td>kjrfjehf</td>
            <td>kjrfjehf</td>
            <td>kjrfjehf</td>
            <td>kjrfjehf</td>
            <td>kjrfjehf</td>
            <td>kjrfjehf</td>
        </tr>
        <tr>
            <td>thara charly</td>
            <td>thara charly</td>
            <td>thara charly</td>
            <td>thara charly</td>
            <td>thara charly</td>
            <td>thara charly</td>
            <td>thara charly</td>
            <td>thara charly</td>
        </tr>
        <tr>
            <td>hiii</td>  
            <td>hiii</td>
            <td>hiii</td>
            <td>hiii</td>
            <td>hiii</td>
            <td>hiii</td>
            <td>hiii</td>
            <td>hiii</td>

        </tr>
        <tr>
            <td>hgfh,fbf</td>  
            <td>efjhgg</td>
            <td>jrhf</td>
            <td>hjkgk</td>
            <td>jhfr,</td>
            <td>hjrkghrg</td>
            <td>hirg.krjhgi</td>
            <td>iurf</td>

        </tr>
        <tr>
            <td>oooo</td>  
            <td>hhjgfi</td>
            <td>fhg</td>
            <td>hfgfef</td>
            <td>fghrebf</td>
            <td>ukyfgbhbf</td>
            <td>jhfjbf</td>
            <td>eghejf</td>
        </tr>
        <tr>
            <td>yyyy</td>  
            <td>yghjbn</td>
            <td>hkjhef</td>
            <td>yghjbn</td>
            <td>yghbn</td>
            <td>yghejb</td>
            <td>euliyeghjfb</td>
            <td>pUUbMtRfG</td>

        </tr>
     </table>
     <h1 align="center">Thankyou</h1>
    </body>
</html>
