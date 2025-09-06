<!DOCTYPE html><html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Online Brand Center - Sarkari Result Style</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      margin: 0;
      padding: 0;
      background: #f2f2f2;
    }
    header {
      background: #b30000;
      color: #fff;
      text-align: center;
      padding: 20px;
    }
    header h1 {
      margin: 0;
      font-size: 28px;
    }
    nav {
      background: #d60000;
      display: flex;
      flex-wrap: wrap;
      justify-content: center;
    }
    nav a {
      color: #fff;
      text-decoration: none;
      padding: 14px 20px;
      font-weight: bold;
    }
    nav a:hover {
      background: #a00000;
    }
    .container {
      max-width: 1100px;
      margin: auto;
      padding: 20px;
    }
    .grid {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
      gap: 20px;
    }
    .box {
      background: #fff;
      border-radius: 8px;
      box-shadow: 0 2px 6px rgba(0,0,0,0.15);
      overflow: hidden;
    }
    .box h2 {
      margin: 0;
      padding: 12px;
      font-size: 18px;
      text-align: center;
      background: #e60000;
      color: #fff;
    }
    .box ul, .box table {
      margin: 0;
      padding: 10px;
      list-style: none;
    }
    .box ul li {
      margin: 8px 0;
    }
    .box ul li a {
      color: #0066cc;
      text-decoration: none;
      font-weight: bold;
    }
    .box ul li a:hover {
      text-decoration: underline;
    }
    table {
      width: 100%;
      border-collapse: collapse;
    }
    table, th, td {
      border: 1px solid #ccc;
    }
    th, td {
      padding: 8px;
      text-align: left;
    }
    th {
      background: #f2f2f2;
    }
    footer {
      background: #333;
      color: #fff;
      text-align: center;
      padding: 15px;
      margin-top: 20px;
    }
    @media(max-width:600px){
      nav a {flex:1 0 100%; text-align:center;}
    }
  </style>
</head>
<body>
  <header>
    <h1>Online Brand Center</h1>
    <p>Sarkari Result Style Job Update Portal</p>
  </header>  <nav>
    <a href="#home">Home</a>
    <a href="#latest">Latest Jobs</a>
    <a href="#admit">Admit Card</a>
    <a href="#result">Results</a>
    <a href="#answer">Answer Key</a>
    <a href="#syllabus">Syllabus</a>
  </nav>  <div class="container">
    <div class="grid">
      <div id="latest" class="box">
        <h2>Latest Jobs</h2>
        <table>
          <tr>
            <th>Post Name</th>
            <th>Qualification</th>
            <th>Last Date</th>
            <th>Apply</th>
          </tr>
          <tr>
            <td>SSC CGL 2025</td>
            <td>Graduate</td>
            <td>30 Sept 2025</td>
            <td><a href="#">Apply Now</a></td>
          </tr>
          <tr>
            <td>UP Police Constable</td>
            <td>10th / 12th</td>
            <td>15 Oct 2025</td>
            <td><a href="#">Apply Now</a></td>
          </tr>
        </table>
      </div><div id="admit" class="box">
    <h2>Admit Card</h2>
    <ul>
      <li><a href="#">SSC GD Constable Admit Card 2025</a></li>
      <li><a href="#">Railway Group D Admit Card 2025</a></li>
    </ul>
  </div>

  <div id="result" class="box">
    <h2>Results</h2>
    <ul>
      <li><a href="#">UPSC Civil Services Result 2025</a></li>
      <li><a href="#">IBPS PO Result 2025</a></li>
    </ul>
  </div>

  <div id="answer" class="box">
    <h2>Answer Key</h2>
    <ul>
      <li><a href="#">SSC CGL Answer Key 2025</a></li>
      <li><a href="#">Railway NTPC Answer Key 2025</a></li>
    </ul>
  </div>

  <div id="syllabus" class="box">
    <h2>Syllabus</h2>
    <ul>
      <li><a href="#">SSC CHSL Syllabus 2025</a></li>
      <li><a href="#">UP Police Constable Syllabus 2025</a></li>
    </ul>
  </div>
</div>

  </div>  <footer>
    <p>&copy; 2025 Online Brand Center | All Rights Reserved</p>
  </footer>
</body>
</html>
