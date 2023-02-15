### Hi there 👋

🔭 I’m currently working on Something Really Cool \
🌱 I’m currently learning NextJs, Docker ,Pytorch


``` python
from typing import List

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
    def get_interests(self) -> str:
        return " | ".join(self.interests)

    def get_skills(self) -> str:
        return " | ".join(self.skills)

    def __repr__(self):
        return f"<h1>{self.author}</h1><p>{self.description}</p><p>{self.location}</p><p>Interests: {self.get_interests()}</p><p>Skills: {self.get_skills()}</p><a href='{self.github}' target='_blank'>Check out my code on GitHub</a>"


Who()

```

<h1>Eswar Divi</h1><p>🐍 Pythonista | 🔓 Open-source evangelist | 🐬 Deep Learning | 💡 Innovator</p><p>🌎 Anytown, SomeWhere</p><p>Interests: 📈 Data science | 🤖 Machine learning | 🎨 Creative coding | 🎮 Game development</p><p>Skills: 🐍 Python | ☕ Java | 🔥 Firebase | 🚀 Scala | 🐘 PostgreSQL | 🍃 MongoDB</p><a href='https://github.com/EswarDivi' target='_blank'>Check out my code on GitHub</a>

