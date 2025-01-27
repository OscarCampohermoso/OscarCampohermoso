
![225813708-98b745f2-7d22-48cf-9150-083f1b00d6c9](https://github.com/user-attachments/assets/2904e2ad-7022-4cca-a529-17406e52c6da)

Hi, I'm a **Systems Engineering student** with experience in software development and data science. Passionate about solving complex problems through technology and data analysis, I specialize in process optimization and thrive in collaborative environments. As the leader of the AWS User Group La Paz, I promote teamwork, cloud technology learning, and the development of collaborative skills within the community.

---

```python
class Me:
    def __init__(self):
        self.name = "Oscar Campohermoso Berdeja"
        self.education = self.get_education()
        self.skills = self.get_skills()
        self.projects = self.get_projects()

    def get_education(self):
        return [
            {
                "institution": "Universidad Católica Boliviana",
                "degree": "Ingeniería de Sistemas",
                "status": "Estudiante"
            }
        ]

    def get_skills(self):
        return {
            "programming_languages": [
                "Python", "Java", "C++", "JavaScript", "Go", "Dart", "R"
            ],
            "web_development": [
                "HTML", "CSS", "PHP", "Django", "Flask"
            ],
            "data_science": [
                "Pandas", "NumPy", "Scikit-Learn", "Matplotlib", "Seaborn"
            ],
            "tools": [
                "Git", "SQL", "Jupyter Notebook", "PostgreSQL", "MongoDB", "Linux"
            ]
        }

    def get_projects(self):
        return [
            {
                "name": "Plataforma Digital para Alquiler y Reserva de Parqueos",
                "achievement": "1er lugar en FUNCTEC 2024"
            },
            {
                "name": "Aplicación Web para Optimización de Rutas en Mi Teleférico",
                "achievement": "2do lugar en FUNCTEC 2024"
            }
        ]

    def __str__(self):
        return f"{self.name}, estudiante de {self.education[0]['degree']} en {self.education[0]['institution']}."
```

---

