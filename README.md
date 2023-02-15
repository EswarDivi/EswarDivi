### Hi there 👋

🔭 I’m currently working on Something Really Cool \
🌱 I’m currently learning NextJs, Docker ,Pytorch


``` python
from typing import List, Dict
import random

__author__ = "Eswar Divi"
__email__ = "eswar.divi.902@gmail.com"
__description__ = (
    "🐍 Pythonista | 🔓 Open-source evangelist | 🐬 Deep Learning | 💡 Innovator"
)
__location__ = "🌎 Anytown, SomeWhere"
__github__ = "https://github.com/EswarDivi"


class Who:
    def __init__(self):
        self.author = __author__
        self.email = __email__
        self.description = __description__
        self.location = __location__
        self.github = __github__
        self.interests = [
            "📈 Data science",
            "🤖 Machine learning",
            "🎨 Creative coding",
            "🎮 Game development",
        ]
        self.skills = [
            "🐍 Python",
            "☕ Java",
            "🔥 Firebase",
            "🚀 Scala",
            "🐘 PostgreSQL",
            "🍃 MongoDB",
        ]
        self.color_scheme = self.generate_color_scheme()

    def generate_color_scheme(self) -> Dict[str, str]:
        colors = ["#8ab6d6", "#332f2d", "#cc5b1e", "#dce6dc", "#3b3532"]
        random.shuffle(colors)
        return {
            "primary": colors[0],
            "secondary": colors[1],
            "accent": colors[2],
            "background": colors[3],
            "text": colors[4],
        }

    def get_interests(self) -> str:
        return " | ".join(self.interests)

    def get_skills(self) -> str:
        return " | ".join(self.skills)

    def __repr__(self):
        return f"<div style='background-color:{self.color_scheme['background']};padding:20px;border-radius:10px;box-shadow:3px 3px 10px rgba(0, 0, 0, 0.2);text-align:center;font-family:Helvetica Neue, Helvetica, Arial, sans-serif;'><h1 style='color:{self.color_scheme['primary']}'>{self.author}</h1><p style='color:{self.color_scheme['text']};font-size:18px;'>{self.description}</p><p style='color:{self.color_scheme['text']};font-size:14px;'>{self.location}</p><p style='color:{self.color_scheme['text']};font-size:14px;'>Interests: {self.get_interests()}</p><p style='color:{self.color_scheme['text']};font-size:14px;'>Skills: {self.get_skills()}</p><a href='{self.github}' target='_blank' style='background-color:{self.color_scheme['primary']};color:{self.color_scheme['text']};padding:10px 20px;border-radius:20px;text-decoration:none;margin-top:20px;display:inline-block;'>Check out my code on GitHub</a></div>"


Who()

```

<svg fill="none" viewBox="0 0 800 400" width="800" height="400" xmlns="http://www.w3.org/2000/svg">
<foreignObject width="100%" height="100%">
<div xmlns="http://www.w3.org/1999/xhtml">
<div
style='background-color:#dce6dc;padding:20px;border-radius:10px;box-shadow:3px 3px 10px rgba(0, 0, 0, 0.2);text-align:center;font-family:Helvetica Neue, Helvetica, Arial, sans-serif;'>
    <h1 style='color:#8ab6d6'>Eswar Divi</h1>
    <p style='color:#cc5b1e;font-size:18px;'>🐍 Pythonista | 🔓 Open-source evangelist | 🐬 Deep Learning | 💡 Innovator
    </p>
    <p style='color:#030303;font-size:14px;'>🌎 Anytown, SomeWhere</p>
    <p style='color:#332f2d;font-size:14px;'>Interests: 📈 Data science | 🤖 Machine learning | 🎨 Creative coding | 🎮
        Game development</p>
    <p style='color:#3b3532;font-size:14px;'>Skills: 🐍 Python | ☕ Java | 🔥 Firebase | 🚀 Scala | 🐘 PostgreSQL | 🍃
        MongoDB</p><a href='https://github.com/EswarDivi' target='_blank'
        style='background-color:#8ab6d6;color:#f2e9e4;padding:10px 20px;border-radius:20px;text-decoration:none;margin-top:20px;display:inline-block;'>Check
        out my code on GitHub</a>
</div>
</div>
</foreignObject>
</svg>


