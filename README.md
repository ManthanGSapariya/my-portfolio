<!DOCTYPE html>
<html lang="en">

<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>WebDevProject</title>
  <meta name="description" content="A personal portfolio showcasing my projects and skills as a web developer." />
  <meta name="keywords" content="web development, portfolio, projects, skills, resume, contact" />
  <meta name="author" content="Your Name" />
  <style>
    *, *::before, *::after {
      box-sizing: border-box;
    }

    body {
      font-family: 'Segoe UI', Arial, sans-serif;
      margin: 0;
      padding: 0;
      background: linear-gradient(135deg, #f4f4f4 60%, #e0e7ff 100%);
      color: #222;
      min-height: 100vh;
    }

    header {
      background: linear-gradient(90deg, #222 60%, #3a3a3a 100%);
      color: #fff;
      padding: 32px 0 16px 0;
      text-align: center;
      box-shadow: 0 2px 8px rgba(0, 0, 0, 0.08);
      letter-spacing: 1px;
    }

    nav ul {
      list-style: none;
      padding: 0;
      margin: 16px 0 0 0;
      display: flex;
      flex-wrap: wrap;
      justify-content: center;
      gap: 20px;
    }

    nav ul li a {
      color: #fff;
      text-decoration: none;
      font-weight: 600;
      padding: 10px 18px;
      border-radius: 6px;
      transition: background 0.2s, color 0.2s, box-shadow 0.2s;
      font-size: 1rem;
    }

    nav ul li a:hover,
    nav ul li a:focus {
      background: #4f46e5;
      color: #fff;
      box-shadow: 0 2px 8px rgba(79, 70, 229, 0.15);
      outline: none;
    }

    main {
      width: 100%;
      max-width: 960px;
      margin: 48px auto;
      background: #fff;
      padding: 40px 20px;
      border-radius: 12px;
      box-shadow: 0 4px 24px rgba(0, 0, 0, 0.10);
    }

    h1 {
      margin-bottom: 14px;
      font-size: 2.3rem;
      font-weight: 700;
      letter-spacing: 1px;
    }

    section h2 {
      color: #4f46e5;
      font-size: 1.4rem;
      margin-top: 32px;
      margin-bottom: 12px;
      font-weight: 600;
      letter-spacing: 0.5px;
    }

    .project-card, .blog-post, .contact-box {
      width: 100%;
      max-width: 290px;
      margin: 0 auto;
    }

    .flex-wrap {
      display: flex;
      flex-wrap: wrap;
      justify-content: center;
      gap: 1.5rem;
    }

    input, textarea, button {
      font-size: 1rem;
    }

    @media (max-width: 768px) {
      nav ul {
        gap: 12px;
        flex-direction: column;
        align-items: center;
      }

      header {
        padding: 20px 0 10px 0;
      }

      h1 {
        font-size: 1.8rem;
      }

      section h2 {
        font-size: 1.2rem;
      }

      main {
        padding: 20px 12px;
      }

      .project-card, .blog-post, .contact-box {
        width: 100%;
        max-width: 100%;
      }
    }

    @media (max-width: 480px) {
      h1 {
        font-size: 1.5rem;
      }

      section h2 {
        font-size: 1rem;
      }
    }
  </style>
</head>
<body>
    <header>
        <h1>My Personal Portfolio</h1>
        <nav>
            <ul>
                <li><a href="#home">Home</a></li>
                <li><a href="#about">About Me</a></li>
                <li><a href="#projects">Projects</a></li>
                <li><a href="#skills">Skills</a></li>
                <li><a href="#resume">Resume</a></li>
                <li><a href="#blog">Blog</a></li>
                <li><a href="#contact">Contact</a></li>
            </ul>
        </nav>

    </header>
    <main>
        <section>
            <h2>Welcome!</h2>
            <p>This is the homepage of my personal portfolio. Explore the sections above to learn more about me, my
                work, and how to get in touch.</p>
        </section>
        <section id="intro"
            style="display: flex; align-items: center; justify-content: center; flex-direction: column; padding: 2rem 0;">
            <img src="Profilephoto.jpeg" alt="Professional Photo"
                style="width: 150px; height: 150px; border-radius: 50%; box-shadow: 0 2px 8px rgba(0,0,0,0.15); margin-bottom: 1rem;">
            <h2 style="animation: fadeInDown 1s;">Hi, I'm Manthan Sapariya!</h2>
            <p style="animation: fadeInUp 1.5s;">A passionate web developer eager to build amazing digital experiences.
            </p>
            <a href="#about"
                style="margin-top: 1.5rem; padding: 0.75rem 1.5rem; background: #0078d7; color: #fff; border-radius: 25px; text-decoration: none; font-weight: bold; animation: fadeInUp 2s;">Scroll
                down to know more about me!</a>
            <style>
                @keyframes fadeInDown {
                    from {
                        opacity: 0;
                        transform: translateY(-30px);
                    }

                    to {
                        opacity: 1;
                        transform: translateY(0);
                    }
                }

                @keyframes fadeInUp {
                    from {
                        opacity: 0;
                        transform: translateY(30px);
                    }

                    to {
                        opacity: 1;
                        transform: translateY(0);
                    }
                }
            </style>
        </section>
        <section id="about" style="margin-top:2.5rem;"></section>
            <h2>About Me</h2>
            <div style="display: flex; flex-wrap: wrap; align-items: center; gap: 2rem;">
                <div style="flex: 0 0 160px; text-align: center;">
                    <img src="Profilephoto.jpeg" alt="Formal Photo" style="width: 140px; height: 140px; border-radius: 50%; box-shadow: 0 2px 8px rgba(0,0,0,0.12); margin-bottom: 0.5rem;">
                </div>
                <div style="flex: 1 1 300px;">
                    <p>
                        I am a BCA under-graduate from KES Shroff College with a strong focus on Web Development, Java, Operating Systems, and Data Structures. My goal is to become a skilled full-stack developer, building robust and scalable web applications.
                    </p>
                    <ul style="margin: 1rem 0 0 1rem; padding: 0;">
                        <li><strong>Education:</strong> BCA, KES Shroff College</li>
                        <li><strong>Focus Areas:</strong> Web Development, Java, OS, Data Structures</li>
                        <li><strong>Career Goal:</strong> Aspiring Full-Stack Developer</li>
                    </ul>
                </div>
            </div>
        </section>
        <section id="journey" style="margin-top: 2.5rem;">
            <h2>My Journey</h2>
            <p style="margin-bottom: 1.5rem;">From a curious student to a passionate developer, here's a glimpse of my
                journey so far.</p>
            
        <div style="margin-top: 2rem;">
  <h3 style="color: #6366f1; font-size: 1.1rem; margin-bottom: 0.7rem;">My Journey</h3>
  <div style="position: relative; padding-left: 30px;">
    <div style="border-left: 3px solid #6366f1; height: 100%; position: absolute; left: 10px; top: 0;"></div>

    <!-- 2024 -->
    <div style="margin-bottom: 1.5rem; position: relative;">
      <span style="position: absolute; left: -7px; top: 2px; width: 16px; height: 16px; background: #6366f1; border-radius: 50%;"></span>
      <div style="margin-left: 16px;">
        <strong>2024</strong><br>
        Completed Higher Secondary Education with a specialization in Computer Science.
      </div>
    </div>

    <!-- 2024 -->
    <div style="margin-bottom: 1.5rem; position: relative;">
      <span style="position: absolute; left: -7px; top: 2px; width: 16px; height: 16px; background: #6366f1; border-radius: 50%;"></span>
      <div style="margin-left: 16px;">
        <strong>2024</strong><br>
        Enrolled in Bachelor of Computer Applications (BCA) at KES Shroff College, Kandivali East.
      </div>
    </div>

    <!-- 2025 -->
    <div style="margin-bottom: 1.5rem; position: relative;">
      <span style="position: absolute; left: -7px; top: 2px; width: 16px; height: 16px; background: #6366f1; border-radius: 50%;"></span>
      <div style="margin-left: 16px;">
        <strong>2025</strong><br>
        Began self-learning Web Development, designed UI components, and started building personal projects.
      </div>
    </div>


    <!-- 2025 -->
    <div style="margin-bottom: 1.5rem; position: relative;">
      <span style="position: absolute; left: -7px; top: 2px; width: 16px; height: 16px; background: #6366f1; border-radius: 50%;"></span>
      <div style="margin-left: 16px;">
        <strong>2025</strong><br>
        Preparing for internships, refining project work, and building an online personal brand.
      </div>
    </div>

    <!-- Now -->
    <div style="position: relative;">
      <span style="position: absolute; left: -7px; top: 2px; width: 16px; height: 16px; background: #6366f1; border-radius: 50%;"></span>
      <div style="margin-left: 16px;">
        <strong>Now</strong><br>
        Deep diving into backend development, continuously learning, and aiming to become a skilled full-stack developer.
      </div>
    </div>
  </div>
</div>


        <!-- Projects Section: Placeholder Projects -->
<section id="portfolio" style="margin-top: 2.5rem;">
  <h2>Projects</h2>
  <p style="margin-bottom: 2rem; font-size: 1rem; color: #555;">
    I'm currently working on building my first real-world projects. Here are a few ideas I'm planning and some updates on what's coming soon.
  </p>
  <div style="display: flex; flex-wrap: wrap; gap: 2rem; justify-content: center;">
    <!-- Coming Soon Project 1 -->
    <div style="background: #f8fafc; border-radius: 10px; box-shadow: 0 2px 12px rgba(79,70,229,0.07); width: 290px; padding: 1.5rem; display: flex; flex-direction: column; align-items: center;">
      <h3 style="color:#4f46e5; font-size: 1.2rem; margin-bottom: 0.8rem;">Portfolio Website</h3>
      <p style="font-size: 0.97rem; margin-bottom: 0.7rem; text-align: center;">Currently building a fully responsive personal portfolio using HTML, CSS, and JavaScript. This will showcase my web development skills and journey.</p>
      <span style="font-size: 0.85rem; color: #888;">Status: In Progress</span>
    </div>

    <!-- Coming Soon Project 2 -->
    <div style="background: #f8fafc; border-radius: 10px; box-shadow: 0 2px 12px rgba(79,70,229,0.07); width: 290px; padding: 1.5rem; display: flex; flex-direction: column; align-items: center;">
      <h3 style="color:#4f46e5; font-size: 1.2rem; margin-bottom: 0.8rem;">To-Do List App</h3>
      <p style="font-size: 0.97rem; margin-bottom: 0.7rem; text-align: center;">Planning a simple yet effective to-do list web application using JavaScript DOM manipulation and CSS transitions.</p>
      <span style="font-size: 0.85rem; color: #888;">Status: Planned</span>
    </div>

    <!-- Coming Soon Project 3 -->
    <div style="background: #f8fafc; border-radius: 10px; box-shadow: 0 2px 12px rgba(79,70,229,0.07); width: 290px; padding: 1.5rem; display: flex; flex-direction: column; align-items: center;">
      <h3 style="color:#4f46e5; font-size: 1.2rem; margin-bottom: 0.8rem;">Calculator App</h3>
      <p style="font-size: 0.97rem; margin-bottom: 0.7rem; text-align: center;">Coming soon: A basic calculator built with HTML, CSS, and vanilla JavaScript as part of my JavaScript practice journey.</p>
      <span style="font-size: 0.85rem; color: #888;">Status: Upcoming</span>
    </div>
  </div>
</section>

       <!-- Updated Skills Section with Icons -->
<section id="skills" style="margin-top: 2.5rem;">
  <h2>Skills</h2>
  <div style="display: flex; flex-wrap: wrap; gap: 2.5rem;">
    <!-- Web Development -->
    <div style="flex: 1 1 240px;">
      <h3 style="font-size: 1.1rem; color: #4f46e5;">🌐 Web Development</h3>
      <ul style="list-style: none; padding: 0; margin: 0;">
        <li><img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/html5/html5-original.svg" width="20" style="vertical-align:middle; margin-right:8px;">HTML
          <div style="background:#e0e7ff;height:8px;border-radius:4px;margin:4px 0 12px 0;">
            <div style="width:90%;background:#f97316;height:8px;border-radius:4px;"></div>
          </div>
        </li>
        <li><img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/css3/css3-original.svg" width="20" style="vertical-align:middle; margin-right:8px;">CSS
          <div style="background:#e0e7ff;height:8px;border-radius:4px;margin:4px 0 12px 0;">
            <div style="width:80%;background:#2563eb;height:8px;border-radius:4px;"></div>
          </div>
        </li>
        <li><img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/javascript/javascript-original.svg" width="20" style="vertical-align:middle; margin-right:8px;">JavaScript
          <div style="background:#e0e7ff;height:8px;border-radius:4px;margin:4px 0 12px 0;">
            <div style="width:75%;background:#facc15;height:8px;border-radius:4px;"></div>
          </div>
        </li>
        <li><img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/bootstrap/bootstrap-original.svg" width="20" style="vertical-align:middle; margin-right:8px;">Bootstrap
          <div style="background:#e0e7ff;height:8px;border-radius:4px;margin:4px 0 12px 0;">
            <div style="width:80%;background:#7952b3;height:8px;border-radius:4px;"></div>
          </div>
        </li>
      </ul>
    </div>

    <!-- Programming Languages -->
    <div style="flex: 1 1 240px;">
      <h3 style="font-size: 1.1rem; color: #4f46e5;">💻 Programming</h3>
      <ul style="list-style: none; padding: 0; margin: 0;">
        <li><img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/c/c-original.svg" width="20" style="vertical-align:middle; margin-right:8px;">C
          <div style="background:#e0e7ff;height:8px;border-radius:4px;margin:4px 0 12px 0;">
            <div style="width:80%;background:#0ea5e9;height:8px;border-radius:4px;"></div>
          </div>
        </li>
        <li><img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/java/java-original.svg" width="20" style="vertical-align:middle; margin-right:8px;">Java
          <div style="background:#e0e7ff;height:8px;border-radius:4px;margin:4px 0 12px 0;">
            <div style="width:70%;background:#ea580c;height:8px;border-radius:4px;"></div>
          </div>
        </li>
      </ul>
    </div>

    <!-- Tools and Software -->
    <div style="flex: 1 1 240px;">
      <h3 style="font-size: 1.1rem; color: #4f46e5;">🛠️ Tools & Software</h3>
      <ul style="list-style: none; padding: 0; margin: 0;">
        <li><img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/vscode/vscode-original.svg" width="20" style="vertical-align:middle; margin-right:8px;">VS Code
          <div style="background:#e0e7ff;height:8px;border-radius:4px;margin:4px 0 12px 0;">
            <div style="width:90%;background:#3b82f6;height:8px;border-radius:4px;"></div>
          </div>
        </li>
        <li><img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/git/git-original.svg" width="20" style="vertical-align:middle; margin-right:8px;">Git
          <div style="background:#e0e7ff;height:8px;border-radius:4px;margin:4px 0 12px 0;">
            <div style="width:70%;background:#ef4444;height:8px;border-radius:4px;"></div>
          </div>
        </li>
        <li><img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/photoshop/photoshop-plain.svg" width="20" style="vertical-align:middle; margin-right:8px;">Adobe Photoshop
          <div style="background:#e0e7ff;height:8px;border-radius:4px;margin:4px 0 12px 0;">
            <div style="width:70%;background:#0ea5e9;height:8px;border-radius:4px;"></div>
          </div>
        </li>
      </ul>
    </div>

    <!-- Certifications -->
    <div style="flex: 1 1 240px;">
      <h3 style="font-size: 1.1rem; color: #4f46e5;">📜 Certifications</h3>
      <ul style="list-style: none; padding: 0; margin: 0;">
        <li>Course on Computer Concepts (CCC) – 75%</li>
        <li>Advanced Excel – 95%</li>
        <li>GST in Tally ERP – 100%</li>
        <li>Advanced Tally Prime – 100%</li>
        <li>MS Office Suite – 72%</li>
        <li>LibreOffice Suite – 72%</li>
        <li>Accounting Fundamentals – 72%</li>
        <li>Graphic Designing – 72%</li>
        <li>Corporate Email Services – 72%</li>
      </ul>
    </div>
  </div>
</section>

<!-- Resume Section -->
<section id="resume" style="margin-top:2.5rem;">
  <h2>Resume</h2>
  <a href="Manthan_Sapariya_Resume.pdf" download style="display:inline-block; background:#4f46e5; color:#fff; font-weight:600; padding:0.85rem 2rem; border-radius:30px; text-decoration:none; font-size:1.1rem; margin-bottom:2rem; box-shadow:0 2px 8px rgba(79,70,229,0.13); transition:background 0.2s;">
    📄 Download My Resume
  </a>
  <div style="margin-top:2rem; display:flex; flex-wrap:wrap; gap:2.5rem;">

    <!-- Education -->
    <div style="flex:1 1 260px;">
      <h3 style="color:#4f46e5; font-size:1.15rem; margin-bottom:0.7rem;">🎓 Education</h3>
      <ul style="list-style:none; padding:0; margin:0;">
        <li style="margin-bottom:1.2rem;">
          <strong>Bachelor of Computer Applications (BCA)</strong><br>
          KES Shroff College, Kandivali East, Mumbai<br>
          <span style="color:#6366f1; font-size:0.97rem;">Currently in 2nd Semester<br>SGPA in 1st Semester: 7.01</span>
        </li>
      </ul>
    </div>

    <!-- Projects / Academic Work -->
    <div style="flex:1 1 260px;">
      <h3 style="color:#4f46e5; font-size:1.15rem; margin-bottom:0.7rem;">📘 Academic Highlights</h3>
      <ul style="list-style:none; padding:0; margin:0;">
        <li style="margin-bottom:1.2rem;">
          <strong>DLLE Participation</strong><br>
          Mumbai University DLLE – First Term Activities<br>
          <span style="font-size:0.97rem;">Actively involved in social outreach and skill development under DLLE.</span>
        </li>
        <li>
          <strong>Web Development Portfolio</strong><br>
          Self-initiated project to design and build a personal professional portfolio site.
        </li>
      </ul>
    </div>

    <!-- Key Skills -->
    <div style="flex:1 1 260px;">
      <h3 style="color:#4f46e5; font-size:1.15rem; margin-bottom:0.7rem;">🛠️ Key Skills</h3>
      <ul style="list-style:none; padding:0; margin:0;">
        <li>HTML, CSS, JavaScript, Java, C</li>
        <li>Bootstrap, Git, VS Code</li>
        <li>Advanced Excel, Photoshop</li>
        <li>MS Office, LibreOffice, Tally ERP, Tally Prime</li>
        <li>Computer Concepts (CCC), Graphic Designing</li>
        <li>Corporate Email Services, Accounting Fundamentals</li>
      </ul>
    </div>
  </div>
</section>

        <section id="blog" style="margin-top:2.5rem;">
  <h2>Blog</h2>
  <p>Sharing my journey, tutorials, and insights in web development.</p>

  <!-- Featured Post -->
  <div style="background:#f1f5ff; border-radius:10px; box-shadow:0 2px 8px rgba(79,70,229,0.08); padding:1.5rem; margin-bottom:2rem;">
    <h3 style="color:#4f46e5; margin-top:0;">
      Featured: 
      <a href="#" style="color:#4f46e5; text-decoration:underline;">How I Built My Portfolio Website</a>
    </h3>
    <p style="margin:0.7rem 0;">
      A step-by-step breakdown of designing, coding, and deploying my personal portfolio using HTML, CSS, and JavaScript.
    </p>
    <div style="font-size:0.95rem; color:#6366f1;">
      <span style="margin-right:1.2rem;">#portfolio</span>
      <span style="margin-right:1.2rem;">#tutorial</span>
      <span>#webdev</span>
    </div>
  </div>

  <!-- Blog Posts List -->
  <div style="display:flex; flex-wrap:wrap; gap:2rem;">
    <!-- Blog Post 1 -->
    <article style="background:#f8fafc; border-radius:8px; box-shadow:0 1px 6px rgba(0,0,0,0.06); padding:1.2rem; flex:1 1 260px; min-width:240px;">
      <h4 style="margin-top:0; color:#4f46e5;">
        <a href="#" style="color:#4f46e5; text-decoration:none;">Mastering JavaScript: My Top 5 Tips</a>
      </h4>
      <p style="font-size:0.97rem;">Practical advice and clean code snippets that helped me understand and write better JavaScript as a beginner.</p>
      <div style="font-size:0.92rem; color:#6366f1;">
        <span>#javascript</span> <span>#codingtips</span>
      </div>
    </article>

    <!-- Blog Post 2 -->
    <article style="background:#f8fafc; border-radius:8px; box-shadow:0 1px 6px rgba(0,0,0,0.06); padding:1.2rem; flex:1 1 260px; min-width:240px;">
      <h4 style="margin-top:0; color:#4f46e5;">
        <a href="#" style="color:#4f46e5; text-decoration:none;">Responsive Design: My Favorite CSS Techniques</a>
      </h4>
      <p style="font-size:0.97rem;">A collection of CSS tricks I use to ensure websites look clean and functional across all devices.</p>
      <div style="font-size:0.92rem; color:#6366f1;">
        <span>#css</span> <span>#responsive</span>
      </div>
    </article>

    <!-- Blog Post 3 -->
    <article style="background:#f8fafc; border-radius:8px; box-shadow:0 1px 6px rgba(0,0,0,0.06); padding:1.2rem; flex:1 1 260px; min-width:240px;">
      <h4 style="margin-top:0; color:#4f46e5;">
        <a href="#" style="color:#4f46e5; text-decoration:none;">From Curiosity to Code: My Web Dev Journey</a>
      </h4>
      <p style="font-size:0.97rem;">My transition from a curious student to a dedicated web developer — and what I learned along the way.</p>
      <div style="font-size:0.92rem; color:#6366f1;">
        <span>#career</span> <span>#journey</span>
      </div>
    </article>
  </div>
</section>

            <!-- Categories/Tags -->
            <div style="margin-top:2rem;">
                <h3 style="font-size:1.05rem; color:#6366f1; margin-bottom:0.5rem;">Categories</h3>
                <span
                    style="display:inline-block; background:#e0e7ff; color:#4f46e5; border-radius:16px; padding:0.3rem 1rem; margin-right:0.7rem; font-size:0.97rem;">Tutorials</span>
                <span
                    style="display:inline-block; background:#e0e7ff; color:#4f46e5; border-radius:16px; padding:0.3rem 1rem; margin-right:0.7rem; font-size:0.97rem;">Project
                    Breakdown</span>
                <span
                    style="display:inline-block; background:#e0e7ff; color:#4f46e5; border-radius:16px; padding:0.3rem 1rem; margin-right:0.7rem; font-size:0.97rem;">Tips</span>
                <span
                    style="display:inline-block; background:#e0e7ff; color:#4f46e5; border-radius:16px; padding:0.3rem 1rem; font-size:0.97rem;">Career</span>
            </div>
        </section>
        <section id="contact" style="margin-top:2.5rem;"></section>
        <h2>Contact</h2>
        <div style="display: flex; flex-wrap: wrap; gap: 2.5rem;">
            <!-- Contact Form -->
            <form action="mailto:your.email@example.com" method="POST" enctype="text/plain"
                style="flex:1 1 320px; background:#f8fafc; border-radius:10px; box-shadow:0 2px 12px rgba(79,70,229,0.07); padding:2rem; min-width:260px;">
                <h3 style="color:#4f46e5; margin-top:0;">Send me a message</h3>
                <label for="name" style="display:block; margin-bottom:0.5rem; font-weight:600;">Name</label>
                <input type="text" id="name" name="name" required
                    style="width:100%; padding:0.6rem; margin-bottom:1rem; border-radius:6px; border:1px solid #e0e7ff;">
                <label for="email" style="display:block; margin-bottom:0.5rem; font-weight:600;">Email</label>
                <input type="email" id="email" name="email" required
                    style="width:100%; padding:0.6rem; margin-bottom:1rem; border-radius:6px; border:1px solid #e0e7ff;">
                <label for="message" style="display:block; margin-bottom:0.5rem; font-weight:600;">Message</label>
                <textarea id="message" name="message" rows="5" required
                    style="width:100%; padding:0.6rem; margin-bottom:1.2rem; border-radius:6px; border:1px solid #e0e7ff;"></textarea>
                <button type="submit"
                    style="background:#4f46e5; color:#fff; font-weight:600; padding:0.7rem 2rem; border:none; border-radius:25px; font-size:1rem; cursor:pointer; transition:background 0.2s;">Send</button>
            </form>
            <!-- Contact Info & Socials -->
            <div style="flex:1 1 260px; min-width:220px;">
                <h3 style="color:#4f46e5; margin-top:0;">Connect with me</h3>
                <ul style="list-style:none; padding:0; margin:0 0 1.5rem 0; font-size:1.05rem;">
                    <li style="margin-bottom:0.7rem;">
                        <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/google/google-original.svg"
                            alt="Email" style="width:22px;vertical-align:middle;margin-right:8px;">
                        <a href="mailto:manthansapariyag@gmail.com"
                            style="color:#222; text-decoration:none;">manthansapariyag@gmail.com</a>
                    </li>
                    <li style="margin-bottom:0.7rem;">
                        <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/linkedin/linkedin-original.svg"
                            alt="LinkedIn" style="width:22px;vertical-align:middle;margin-right:8px;">
                        <a href="https://www.linkedin.com/in/manthan-sapariya-03454033b/" target="_blank"
                            style="color:#222; text-decoration:none;">LinkedIn</a>
                    </li>
                    <li style="margin-bottom:0.7rem;">
                        <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/github/github-original.svg"
                            alt="GitHub" style="width:22px;vertical-align:middle;margin-right:8px;">
                        <a href="https://github.com/ManthanGSapariya" target="_blank"
                            style="color:#222; text-decoration:none;">GitHub</a>
                    </li>
                    <!-- Optional: Phone -->
                    <li>
                        <img src="https://cdn.jsdelivr.net/gh/twitter/twemoji@latest/assets/svg/1f4de.svg" alt="Phone"
                            style="width:22px;vertical-align:middle;margin-right:8px;">
                        <a href="tel:+1234567890" style="color:#222; text-decoration:none;">+1 (234) 567-890</a>
                    </li>
                </ul>
                <!-- Social Media Icons -->
                <div style="display:flex; gap:1rem; margin-bottom:1.5rem;">
                    <a href="https:</div>//twitter.com/yourusername" target="_blank" title="Twitter">
                        <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/twitter/twitter-original.svg"
                            alt="Twitter" style="width:28px;">
                    </a>
                    <a href="https://facebook.com/yourusername" target="_blank" title="Facebook">
                        <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/facebook/facebook-original.svg"
                            alt="Facebook" style="width:28px;">
                    </a>
                    <a href="https://instagram.com/yourusername" target="_blank" title="Instagram">
                        <img src="https://cdn.jsdelivr.net/npm/simple-icons@v11/icons/instagram.svg"
                            alt="Instagram" style="width:28px; filter: invert(34%) sepia(98%) saturate(7497%) hue-rotate(316deg) brightness(97%) contrast(101%);">
                    </a>
                </div>
                <!-- Google Maps Embed (optional) -->
                <div style="border-radius:10px; overflow:hidden; box-shadow:0 1px 6px rgba(0,0,0,0.07);">
                    <iframe
                        src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d3153.019123456789!2d-122.41941568468123!3d37.7749297797597!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x8085809c5b0e6b1b%3A0x4a0b0b0b0b0b0b0b!2sSan+Francisco%2C+CA!5e0!3m2!1sen!2sus!4v1680000000000!5m2!1sen!2sus"
                        width="100%" height="160" style="border:0;" allowfullscreen="" loading="lazy"
                        referrerpolicy="no-referrer-when-downgrade" title="Location"></iframe>
                </div>
    
            </div>
        </div>
        </section>
