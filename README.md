# Create the full HTML profile code with a space background

space_background_url = "https://images.unsplash.com/photo-1446776811953-b23d57bd21aa"

# Complete HTML with space background
space_background_html = f"""
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Shravan S Profile - Space Background</title>
  <style>
    body {{
      background-image: url('{space_background_url}');
      background-size: cover;
      background-position: center;
      color: white;
      font-family: Arial, sans-serif;
      padding: 20px;
    }}
    a {{
      color: lightblue;
    }}
  </style>
</head>
<body>
<h1 align="center">Hi 👋, I'm Shravan S</h1>
<h3 align="center">A passionate programmer exploring AI, ML, and DevOps</h3>

<p align="center">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=500&size=22&pause=1000&center=true&vCenter=true&width=435&lines=Passionate+about+AI+%26+Cloud;DevOps+Enthusiast;Lifelong+learner+%26+problem+solver" alt="Typing SVG" />
</p>

<hr>

<h2>🚀 About Me</h2>
<ul>
  <li>🔭 I’m currently learning <strong>Python (noob to pro)</strong> and <strong>DevOps tools</strong></li>
  <li>👯 I’m looking to collaborate with <strong>developers to grow and improve</strong></li>
  <li>📫 How to reach me: <a href="https://instagram.com/the_royal_ceo">IG: @the_royal_ceo</a></li>
  <li>🌍 Based in: <strong>Bengaluru, India</strong></li>
  <li>💬 Pronouns: <strong>He/Him</strong></li>
  <li>🧠 Fun fact: <em>"Is it necessary to have one?"</em> 😄</li>
  <li>💡 Motto: <em>"Stay motivated. Nothing is unsolvable."</em></li>
</ul>

<h2>🧰 Tech Stack</h2>
<p align="center">
  <img src="https://skillicons.dev/icons?i=python,postgres,git,github,gitlab,docker,linux,jenkins,kubernetes,aws,azure,go" />
</p>

<h2>📚 Tips for Learning</h2>
<ul>
  <li>📘 Prefer <strong>reading-based learning</strong>? Try <a href="https://www.w3schools.com">W3Schools</a></li>
  <li>🎥 Prefer <strong>hands-on or video tutorials</strong>? Try <a href="https://youtube.com">YouTube</a></li>
  <li>📄 Prefer <strong>documentation</strong>? Try <a href="https://www.geeksforgeeks.org/">GeeksforGeeks</a></li>
</ul>

<h2>📌 Pinned Projects</h2>
<ul>
  <li>🔹 <strong>MiniProject</strong> – Sign Language Translator (Python)</li>
  <li>🔹 <strong>DevOps-Projects</strong> – Exploring Jenkins, CI/CD (JavaScript)</li>
  <li>🔹 <strong>Cloud Deployment Demo</strong> – Hosted using Jupyter (Jupyter Notebook)</li>
  <li>🔹 <strong>Testing Jenkins</strong> – Demo setup for Jenkins testing (Python)</li>
</ul>
<p>Explore all at: <a href="https://github.com/TeamWork28?tab=repositories">GitHub Repos »</a></p>

<h2>🌐 Connect with Me</h2>
<p>
  <a href="mailto:shravansen.sk@gmail.com"><img src="https://img.shields.io/badge/Email-shravansen.sk@gmail.com-blue?style=flat&logo=gmail"></a>
  <a href="https://linkedin.com/in/shravan-s-07a4a7154"><img src="https://img.shields.io/badge/LinkedIn-Shravan-blue?style=flat&logo=linkedin"></a>
  <a href="https://twitter.com/shravanrockz70"><img src="https://img.shields.io/badge/Twitter-@shravanrockz70-blue?style=flat&logo=twitter"></a>
</p>
</body>
</html>
"""

# Save the file
space_file_path = "/mnt/data/Shravan_Profile_Space_Background.html"
with open(space_file_path, "w") as f:
    f.write(space_background_html)

space_file_path  # Return the path to the space background version
