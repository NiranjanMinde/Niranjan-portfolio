# Niranjan-portfolio

<!DOCTYPE html>
<html lang="en">
<head>
<title> Practical No 25 </title>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <h1>Niranjan Minde - Portfolio</h1>
    <style>         body {             font-family: Arial, sans-serif;             margin: 0;             padding: 0;             background-color: #f0f0f0; /* Background color for the whole webpage */             color: #333; /* Main font color */
        }
        header {             background-color: rgba(0, 0, 0, 0.5); /* Semi-transparent background for header */
            color: #fff;             padding: 20px;             text-align: center;             animation: fadeIn 1s ease-out;
        }         nav {             background-color: rgba(0, 0, 0, 0.7); /* Semi-transparent background for navigation */             padding: 10px;             text-align: center;
        }         nav a {             color: #fff;             text-decoration: none;             padding: 10px;
        }
        section {             padding: 20px;             margin: 20px;             background-color: rgba(255, 255, 255, 0.8); /* Semi-transparent background for sections */             border-radius: 5px;
            animation: slideIn 1s ease-out;
        }         footer {             background-color: rgba(0, 0, 0, 0.5); /* Semi-transparent background for footer */
            color: #fff;             padding: 20px;             text-align: center;             animation: fadeIn 1s ease-out;
        }         table {             width: 100%;             border-collapse: collapse;
        }         th, td {             padding: 8px;             text-align: left;             border-bottom: 1px solid #ddd;
        }         th {
            background-color: #f2f2f2;
        }
        
        /* Animation Keyframes */         @keyframes slideIn {             from {                 opacity: 0;                 transform: translateY(-50px);             }             to {                 opacity: 1;                 transform: translateY(0);
            }
        }
        
        @keyframes fadeIn {
            from {                 opacity: 0;
            }             to {
                opacity: 1;
            }
        }
    </style>
</head>
<body>
    <header>
        <h1>Niranjan Minde</h1>
        <p>Computer Engineering Student</p>
    </header>
    <nav>
        <a href="#about">About</a>
        <a href="#portfolio">Portfolio</a>
        <a href="#marks">Marks</a>
        <a href="#contact">Contact</a>
    </nav>
    <marquee behavior="scroll" direction="left">Welcome to Niranjan's 
Portfolio!</marquee>
    <section id="about">
        <h2>About Me</h2>
        <p>
            Name: Niranjan Minde <br>
            Age: 19<br>
            Date Of Birth: 07/01/2005<br>
            Address: Dhayri, Pune - 411041<br>
            Mother Tongue: Marathi<br>
            Height: 6 Feet<br>
            Weight: 65 kg<br>
            Blood group: A+ <br>
            Hobbies: Playing Cricket , Reading Books, Flute Listening
        </p>
    </section>
    <section id="portfolio">
        <h2>Portfolio</h2>
        <table>
            <tr>
                <th>Subject</th>
                <th>Mark</th>
            </tr>
            <tr>
                <td>Science</td>
                <td>91</td>
            </tr>
            <tr>
                <td>Maths</td>
                <td>92</td>
            </tr>
            <tr>
                <td>Sanskrit</td>
                <td>98</td>
            </tr>
            <tr>
                <td>Marathi</td>
                <td>94</td>
            </tr>
            <tr>
                <td>English</td>
                <td>92</td>
            </tr>
            <tr>
                <td>Social Science</td>
                <td>96</td>
            </tr>
            <tr>
                <td>Total Percentage</td>
                <td>94.40%</td>
            </tr>
        </table>
    </section>
    <section id="marks">
        <h2>Education Details</h2>
        <p>
            Branch: Computer Engineering<br>
            Year: First Year Diploma
        </p>
    </section>
    <section id="contact">
        <h2>Contact Me</h2>
        <p>
            Phone Number: 9021510608<br>
            Email: niranjanminde45@gmail.com
        </p>
    </section>
    <footer>
        <p>&copy; 2024 Niranjan Minde - All Rights Reserved</p>     </footer>
</body>
</html>
