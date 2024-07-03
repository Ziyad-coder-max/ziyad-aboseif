# ziyad-aboseif
git clone https://github.com/yourusername/personal-website.git
cd personal-website
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Ziyad S. Almokhtar Abosaif</title>
    <style>
        body { 
            font-family: 'Helvetica Neue', Arial, sans-serif; 
            line-height: 1.6; 
            margin: 0; 
            padding: 0; 
            background-color: #f4f4f9; 
            color: #333; 
        }
        header { 
            background: #007bff; 
            color: #fff; 
            padding: 2rem 0; 
            text-align: center; 
            box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1); 
        }
        header h1 { 
            margin: 0; 
            font-size: 2.5rem; 
        }
        .container { 
            padding: 2rem; 
            max-width: 900px; 
            margin: auto; 
            background: #fff; 
            box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1); 
        }
        .section { 
            margin-bottom: 2rem; 
        }
        h2 { 
            border-bottom: 2px solid #007bff; 
            padding-bottom: 0.5rem; 
            color: #007bff; 
        }
        ul { 
            list-style-type: none; 
            padding: 0; 
        }
        li { 
            margin-bottom: 0.5rem; 
        }
        a { 
            color: #007bff; 
            text-decoration: none; 
        }
        a:hover { 
            text-decoration: underline; 
        }
        footer { 
            background: #333; 
            color: #fff; 
            text-align: center; 
            padding: 1rem 0; 
            margin-top: 2rem; 
        }
        .skills-grid { 
            display: grid; 
            grid-template-columns: repeat(auto-fit, minmax(200px, 1fr)); 
            gap: 1rem; 
        }
        .skills-grid li { 
            background: #f8f9fa; 
            padding: 1rem; 
            border: 1px solid #ddd; 
            border-radius: 4px; 
            box-shadow: 0 2px 4px rgba(0, 0, 0, 0.1); 
        }
    </style>
</head>
<body>
    <header>
        <h1>Ziyad S. Almokhtar Abosaif</h1>
        <p>Birthday: 24/09/1999 | Email: <a href="mailto:ziadzziden@gmail.com">ziadzziden@gmail.com</a> | Phone: 00218930840228</p>
    </header>
    <div class="container">
        <div class="section" id="about">
            <h2>About Me</h2>
            <p>An upcoming graduate on the verge of obtaining a bachelor’s degree in Information Systems Management, well-versed in meticulous financial statement analysis. Possesses strong expertise in electronic programming, mastering multiple languages, including English and Turkish. Additionally, I hold a bachelor's degree in accounting.</p>
        </div>
        <div class="section" id="experience">
            <h2>Professional Experience</h2>
            <h3>OUT Car Gallery (FEB 2022 – DEC 2023)</h3>
            <ul>
                <li>Audited financial records to identify discrepancies and errors.</li>
                <li>Reviewed documents and transactions for accuracy and compliance.</li>
                <li>Rectified mistakes to maintain the integrity of financial data.</li>
            </ul>
            <h3>Las Avgas LTD (FEB 2022 – APR 2023)</h3>
            <ul>
                <li>Managed employee payroll and oversaw financial records.</li>
                <li>Developed strategies to optimize revenue generation.</li>
                <li>Addressed operational challenges to ensure smooth functioning.</li>
            </ul>
        </div>
        <div class="section" id="education">
            <h2>Education</h2>
            <ul>
                <li>Undergraduate bachelor student at Final International University (MIS) Management Information Systems</li>
                <li>Bachelor's degree in accounting</li>
                <li>High school diploma with a scientific focus</li>
                <li>Completed annual English language training and obtained certification in Arabic debate</li>
                <li>Enriched qualifications with computer and programming courses</li>
            </ul>
        </div>
        <div class="section" id="skills">
            <h2>Skills</h2>
            <div class="skills-grid">
                <ul>
                    <li>Strong communication skills</li>
                    <li>Adaptability</li>
                    <li>Problem solving</li>
                    <li>Collaboration</li>
                    <li>Critical thinking</li>
                </ul>
                <ul>
                    <li>Leadership</li>
                    <li>Emotional intelligence</li>
                    <li>Microsoft Office, Excel, Word, PowerPoint, Google Mail, Outlook</li>
                    <li>Programming Languages: C, C++, Python, Java</li>
                    <li>Fluent in English, Arabic, Turkish</li>
                </ul>
            </div>
        </div>
        <div class="section" id="hobbies">
            <h2>Hobbies & Interests</h2>
            <p>Chess, Public speaking, Mind games</p>
        </div>
        <div class="section" id="contact">
            <h2>Contact</h2>
            <p>Email: <a href="mailto:ziadzziden@gmail.com">ziadzziden@gmail.com</a></p>
            <p>Phone: 00218930840228</p>
        </div>
    </div>
    <footer>
        <p>&copy; 2024 Ziyad S. Almokhtar Abosaif. All rights reserved.</p>
    </footer>
</body>
</html>
git add index.html
git commit -m "Add index.html"
git push origin main
