
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My Portfolio</title>
    <style>
        html{
            scroll-padding-top: 70px;
        }
        body {
            font-family: 'Times New Roman', Times, serif;
            margin: 0;
            padding: 0;
            background-image: url("https://st4.depositphotos.com/25635058/38892/i/450/depositphotos_388926016-stock-photo-workplace-table-minimalist-style-computer.jpg");
            background-size: cover;
            background-repeat: no-repeat;
            background-position: center;
            color: white;
        }
        a {
            text-decoration: none;
            color: inherit;
        }
        header {
            position: fixed;
            background-color: #333;
            padding: 10px 10px;
            text-align: center;
            top: 0;
            width: 100%;
        }
        header nav a {
            margin: 0 15px;
            color: white;
            font-size: 18px;
            padding: 10px;
        }
        header nav a:hover {
            background-color: #575757;
            border-radius: 5px;
        }
        .navbar{
            display: flex;
            justify-content: space-between;
            align-items: center;
        }
        .brand-name{
            font-size: 1.5rem;
            font-weight: bold;
            color: white;
            margin-left: 10px;
        }
        }
        .container1 {
            position: fixed;
            top: 60%;
            right: 0;
            transform: translateY(-50%);
            display: flex;
            flex-direction: column;
            align-items: center;
            padding: 10px 50px;
        }
        .container2{
            text-align: left;
            display: flex;
            flex-direction: column;
            padding: 10px 50px;
            width: 100%;
            background-color: rgba(0, 0, 0, 0.6);
            border-radius: 10px;
        }
        #font{
            font-family: 'Times New Roman', Times, serif;
            font-size: large;
            padding: 10px;
        }
        .ls{
            background-color: white;
            border-radius: 10px;
            border-style: none;
            padding: 10px;
            width:100%;
        }
        .container {
            max-width: 1000px;
            margin: 20px auto;
            padding: 20px;
            background-color: rgba(0, 0, 0, 0.6);
            border-radius: 10px;
        }
        .name {
            padding: 10px;
            font-size: 2rem;
            font-style: italic;
            text-align: center;
        }
        .name2 {
            margin-top: 10%;
            padding: 10px 200px;
            font-size: 3rem;
            font-style: italic;
            text-align: left;
            color: black;
        }
        .name1 {
            padding: 10px ;
            margin-top: 10px;
            color: black;
            font-size: 4rem;
            font-style: italic;
            text-align: center;
        }
        .about {
            font-size: 1.2rem;
            line-height: 1.6;
        }
        .button {
            background-color: beige;
            border: none;
            border-radius: 20px;
            padding: 10px 20px;
            cursor: pointer;
        }
        .button:hover {
            background-color: #f0e68c;
        }

        footer {
            background-color: #333;
            color: white;
            text-align: center;
            padding: 10px 0;
            position: relative;
            bottom: 0;
            width: 100%;
        }
       
        .projects {
            display: flex;
            justify-content: space-between;
            gap: 20px;
        }
        .cert1 {
            width: 100%;
            display: flex;
            flex-wrap:wrap;
            justify-content: flex-start;
            gap: 20px;
        }
        .proj {
            background-color: rgba(0, 0, 0, 0.6);
            padding: 15px;
            border-radius: 10px;
            width: 48%; 
            box-sizing: border-box;
        }
        .proj:hover{
            background-color: #575757;
        }
        .ul1{
            color: white;
            list-style-type: disc;
        }
        .proj ul {
            list-style-type: none;
            padding-left: 0;
        }

        .proj li {
            margin-bottom: 5px;
        }
       
        .b{
            font-size: larger;
            padding: 10px;
        }
        
        .certificate{
            justify-content: space-between;
        }
        
        .cert{
            
            padding: 8px;
            border-radius: 10px;
            box-sizing: border-box;
        }
        .container2:hover{
            background-color: #575757;
        }
        .img {
            height: 50px;
            width: 50px;
            margin: 10px 0;
            padding: 1px;
            border-radius: 50%;
            transition: transform 0.3s ease;
        }
        .img:hover {
            transform: scale(1.1);
        }
        .img1 {
            height: 80px;
            width: 80px;
            margin: 10px 0;
            padding: 5px;
            border-radius: 50%;
            transition: transform 0.3s ease;
        }
        .img1:hover {
            transform: scale(1.1);
        }
        .container1 a {
            display: block;
        }
        .logo{
            display: flex;
            flex-direction: row;
            max-width: 100%;
            padding: 5px 190px;
            justify-content: center;
            gap: 40px;
        }
        #homeimg{
            border-radius: 30px;
        }
        .container:hover{
            background-color: #078638;
        }
        .ls {
            padding: 10px;
            font-size: 1rem;
            border: 1px solid #ccc;
            border-radius: 5px;
            width: 100%;
            box-sizing: border-box;
            max-height: 500px;
        }
        textarea.ls {
            width: 100%;            
            box-sizing: border-box; 
            padding: 10px;         
            font-size: 1rem;       
            border: 1px solid #ccc; 
            border-radius: 4px;     
            resize: vertical;
        }
        .submit-btn {
            padding: 10px 20px;
            font-size: 1rem;
            border: none;
            border-radius: 4px;
            background-color: #4CAF50;
            color: white;
            cursor: pointer;
            transition: background-color 0.3s ease;
        }
        .submit-btn:hover {
            background-color: #45a049;
        }
        .cen{
            padding: 10px;
            align-items: center;
        }
    </style>
</head>
<body>

    <header>
        <div class="navbar">
            <div class="brand-name">Talluri Niveditha</div>
            <nav>
            <a href="#home">Home</a>
            <a href="#about">About</a>
            <a href="#tech">Skillset</a>
            <a href="#academia">Academia</a>
            <a href="#projects">Projects</a>
            <a href="#certifications">Certifications</a>
            <a href="#connect">Connect Here</a>
        </nav>
        </div>
    </header>
    <div id="home">
        <div class="name1"><br>
            Hello I'm Talluri Niveditha<br><br>
            <img src="https://img.freepik.com/premium-vector/woman-sits-desk-working-laptop-surrounded-by-plants-books-she-is-smiling-appears-be-focused-her-work_520881-8016.jpg" width=700 id="homeimg">
        </div>
    </div>
    <div class="container" id="about">
        <div class="name">About</div>
        <div class="about">
            <p>I'm a second-year B.Tech student specializing in Artificial Intelligence and Machine Learning (AIML) at ICFAI Foundation for
                Higher Education, Hyderabad.
            With a strong foundation in mathematics and programming, I actively engage in AI/ML projects and web development. 
            Passionate about problem-solving, I enjoy teaching math and exploring new learning opportunities. 
            My goal is to apply theoretical knowledge to real-world challenges and contribute to the evolving field of AI and ML.</p>
        </div>
    </div>
    <div class="container" id="tech">
        <div class="name">Skillset</div>
        <div class="logo">
            <a href="https://www.w3schools.com/c/index.php">
                <img class="img1" src="https://upload.wikimedia.org/wikipedia/commons/1/19/C_Logo.png">
            </a>
            <a href="https://www.python.org/">
                <img class="img1" src="data:image/png;base64,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">
            </a>
            <a href="https://www.w3schools.com/java/">
                <img class="img1" src="https://imgcdn.stablediffusionweb.com/2024/10/1/2dcc3931-b889-4beb-8804-04f1ddfb6af9.jpg">
            </a>
            <a href="https://www.w3schools.com/html/">
                <img class="img1" src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcR2lIoQzLmIHHJGhEKv5J5qz_Nv22sfw4JMUg&s">
            </a>
            <a href="https://www.w3schools.com/css/default.asp">
                <img class="img1" src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcSfj7-gq11u-a8ebYdxnDF-fIy6cBIJ-Mn2Lg&s">
            </a>
            <a href="https://www.w3schools.com/js/default.asp">
                <img class="img1" src="https://mindster.com/mindster-blogs/wp-content/uploads/2020/09/JavaScript.png">
            </a>
        </div>
    </div>
    <div class="container" id="academia">
        <div class="name">Academia</div>
        <div class="about">
            
            <ul class="ul1">
                <li>Pursuing B.Tech in Artificial Intelligence and Machine Learning in<i> ICFAI Foundation for Higher Education, Hyderabad</i><br><br>
            </li>
            <li>Completed my Intermediate at <i> HKS PU College, Hassan</i></li>
            <br>
            <li>Studied 10<sup>th</sup> class at<i> HKS International School, Hassan</i></li>
            </ul>
            
        </div>
    </div>
    <div class="container" id="projects">
        <div class="name">Projects</div>
        <div class="projects">
            <div class="proj">
                <div class="b"><b><i>Sentiment Analysis</i></b><br></div>
                This project focuses on analyzing the sentiment of people based on their reviews or comments. It helps in improving the quality of the product based on customer feedback.
                <ul>
                    <li><i>Technical Stack: </i>Python</li>
                    <li><i>Software Requirements: </i>Python IDLE 3.12 Version</li>
                </ul>
                 <form class="cen">
                    <a href="https://github.com/Nivedithatalluri/Python-Projects/blob/main/Sentiment%20Analysis.py">
                        <button type="submit" class="submit-btn">View Project</button>
                    </a>
                </form>
            </div>
            <div class="proj">
                <div class="b"><b><i>Kitchen Wastewater Management System</i></b></div>
                This project aims to recycle water from kitchen outlets like sinks. The water is collected and treated using necessary compounds to remove harsh and toxic chemicals. Later, the water is sent to a storage unit from which it can be drawn for utility purposes such as gardening or cleaning vehicles.
                <ul>
                    <li><i>Technical Stack: </i>C++</li>
                    <li><i>Software: </i>Blynk app</li>
                    <li><i>Hardware: </i>ESP8266, moisture sensors, storage tank, water level sensors</li>
                </ul>
            </div>
        </div>
    </div>
    <div class="container" id="certifications">
        <div class="name">Certificates</div>
        <div class="projects">
            <div class="container2">
             <div class="cert1">
             <div class="cert">
                <a target="_blank" href="https://ai102tablestorage.blob.core.windows.net/certificates/Talluri Niveditha.pdf"><u>AI-900: Microsoft Azure AI Fundamentals </u></a>
            </div>
            <div class="cert">
                <a target="_blank" href="https://fsp-assessment-certificates.s3.ap-southeast-1.amazonaws.com/%27/s3/buckets/fsp-assessment-certificates%27/Niveditha%2BTalluri_7f2eq9pgcg.pdf.pdf"><u>NASSCOM Acquring Data</u></a>
            </div>
           </div>
        </div>
         <div class="container2">
            <div class="cert1">
             <div class="cert">
                <a target="_blank" href="https://fsp-assessment-certificates.s3.ap-southeast-1.amazonaws.com/%27/s3/buckets/fsp-assessment-certificates%27/TALLURI%2BNIVEDITHA_6w0c0adgqo.pdf.pdf"><u>NASSCOM Data Processing and Visualisation</u></a>
            </div>
           
            <div class="cert">
                <a target="_blank" href="https://fsp-assessment-certificates.s3-ap-southeast-1.amazonaws.com/TalluriNiveditha-125491393.pdf"><u>NASSCOM Exploratory Data Analysis</u></a></div>
            </div>
           </div>
         </div>
        <br>
        </div>
    </div>
    <div class="container" id="connect">
        <div class="name">Connect Here</div>
        <div class="projects">
            <form class="container2">
              <h1>Talluri Niveditha</h1>
              <h2>talluriniveditha23@ifheindia.org</h2>
              <h2>+91 7411484306</h2>
              <h3>Click here to connnect on LinkedIn:</h3>
              <a target="_blank" href="https://www.linkedin.com/in/talluri-niveditha-b6a654301/">
                <h2><u>LinkedIn</u></h2>
              </a>
            </form>
            <form class="container2">
                <div id="font">Your name: </div> <input type="text" placeholder="Enter your name" class="ls">
                <div id="font">Enter your mail ID: </div><input type="text" placeholder="Enter your mail ID" class="ls">
                <div id="font"> Comments:</div> 
                <textarea placeholder="Leave comments" class="ls" rows="2"></textarea> <br>
                <form class="cen">
                    <button type="submit" class="submit-btn">Submit</button>
                </form>
            </form>
            <br>
        </div>
    </div>
    <footer>
        <p>&copy; 2025 Talluri Niveditha. All rights reserved.</p>
    </footer>
</body>
</html>
