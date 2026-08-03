## 👋 Hello, I'm Eric John P. Feliciano

---

### 🎓 About Me
- 🎮 Aspiring **Game Developer** and dedicated **BSIT student**
- 📍 Passionate about creating interactive and engaging game experiences
- 📚 Actively learning **Python**, **C#**, **Unity**, and the fundamentals of **Game Development**
- 💡 Committed to continuous improvement and building real-world projects to enhance my skills
- 🌐 Strong interest in **Game Design**, **Programming**, and **Creative Technologies**

---

### 🧠 Skills & Technologies
- **Languages**: Python, C#, SQL, Lua Script  
- **Game Engines/Frameworks**: Unity, Godot *(exploring)*  
- **Tools**: Git, GitHub, Visual Studio, Unity Hub  
- **Other**: Object-Oriented Programming, Version Control, Problem-Solving, Debugging

---

### 🔨 Projects & Learning Goals
- 🧩 Building mini-games and prototypes as portfolio projects  
- 📘 Practicing version control using Git and GitHub  
- 🚀 Working on game mechanics, player controls, and interactive UI elements  
- 🎯 Goal: To develop a full-featured indie game and publish it

---

### 📫 Get in Touch
- ✉️ Email: **quincykizuna22@yourdomain.com** **  
- 💼 LinkedIn: https://www.linkedin.com/in/eric-john-feliciano-380a84384

---

> 🌟 _“Code with purpose, build with passion.”_


CODE THIS!
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <title>Lived, Laugh, Repeat</title>

  <style>
    body {
      min-height: 100vh;
      margin: 0;
      display: grid;
      place-items: center;
      background: linear-gradient(135deg, #ffd6e7, #c8e7ff);
      color: #29243a;
      font-family: Arial, sans-serif;
      text-align: center;
      transition: background 0.5s ease;
    }

    .card {
      padding: 40px;
      border-radius: 20px;
      background: rgba(255, 255, 255, 0.75);
      box-shadow: 0 10px 30px rgba(0, 0, 0, 0.15);
    }

    h1 {
      margin-top: 0;
      font-size: clamp(2rem, 7vw, 4rem);
    }

    button {
      padding: 12px 24px;
      border: 0;
      border-radius: 999px;
      background: #29243a;
      color: white;
      font-size: 1rem;
      cursor: pointer;
    }

    button:hover {
      transform: scale(1.05);
    }
  </style>
</head>

<body>
  <main class="card">
    <h1>Lived, Laugh, Repeat</h1>
    <p id="message">Make every moment count.</p>
    <button id="repeatButton">Repeat</button>
  </main>

  <script>
    const colors = [
      ["#ffd6e7", "#c8e7ff"],
      ["#fff0b8", "#c9f7d4"],
      ["#d9c8ff", "#ffc8c8"]
    ];

    let currentColor = 0;

    document.getElementById("repeatButton").addEventListener("click", () => {
      currentColor = (currentColor + 1) % colors.length;
      const [firstColor, secondColor] = colors[currentColor];

      document.body.style.background =
        `linear-gradient(135deg, ${firstColor}, ${secondColor})`;

      document.getElementById("message").textContent =
        "Lived. Laugh. Repeat!";
    });
  </script>
</body>
</html>

