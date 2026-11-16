# Multi-color-Text-CSS
Want to create beautiful multi-color text using HTML and CSS? 🌈 In this short tutorial, I'll show you how to create colourful gradient text using simple HTML and CSS without JavaScript.

Learn how to apply CSS gradient effects to text and make your website look more attractive with this beginner-friendly coding tutorial.

# HTML Program : -
      <!DOCTYPE html>
      <html lang="en">
      <head>
          <meta charset="UTF-8">
          <meta http-equiv="X-UA-Compatible" content="IE=edge">
          <meta name="viewport" content="width=device-width, initial-scale=1.0">
          <link rel="stylesheet" href="style.css">
       <title>Multi Color Text with css3</title>
    </head>
    <body>
       <div class="container">
         <h1>Multi Color Text with css3</h1>
       </div>
     </body>
    </html>

# CSS Program : -
    :root {
       --color-1: #186cb8;
       --color-2: #2a9a9f;
       --color-3: #f98d00;
       --color-4: #e83611;
       --color-5: #f1b211;
     }

    * {
        box-sizing: border-box;
    }

      body 
     {
        background-color: #e1e1e1;
     }

    .container {
       line-height: 1;
       display: grid;
       min-height: calc(100vh - 16px);
    }

    h1 {
       color: transparent;
       font-family: sans-serif;
       font-size: 15vw;
       font-weight: 900;
       text-align: center;
       width: min-content; 
       margin: auto;
       text-transform: uppercase;
       background: linear-gradient(
        220deg, var(--color-1) 19%,
        transparent 19%, transparent 20%,
        var(--color-2) 20%, var(--color-2) 39%,
        transparent 39%, transparent 40%,
        var(--color-3) 40%, var(--color-3) 59%,
        transparent 59%,transparent 60%,
        var(--color-4) 60%, var(--color-4) 79%,
        transparent 79%, transparent 80%, 
        var(--color-5) 80%
       );
       -webkit-background-clip: text;

       }

        @media screen and (min-width: 768px) {
       h1 {
        font-size: 10vw;
      }
    }


🔥 In This Video:

✅ How to Create Multi-Color Text Using CSS

✅ Colourful Gradient Text Effect

✅ HTML and CSS Coding Tutorial

✅ CSS Linear Gradient Text Effect

✅ Simple and Easy CSS Tricks

✅ Creative Text Effects for Websites

💻 Technologies: HTML5 & CSS3
🎯 Level: Beginner Friendly
📅 Tutorial: 2026

🔗 Learn More: Follow Amith Thoughts for more HTML, CSS, JavaScript, web development, coding tutorials, and computer tips.

👍 Like, Share & Subscribe to Amith Thoughts for more interesting coding tricks and technology tutorials.

🔔 Amith Thoughts – Learn Technology for Free!
