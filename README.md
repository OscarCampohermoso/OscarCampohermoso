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

## 📊 GitHub Stats
![Oscar's GitHub stats](https://github-readme-stats.vercel.app/api?username=OscarCampohermoso&show_icons=true&theme=default)
![Top Langs](https://github-readme-stats.vercel.app/api/top-langs/?username=OscarCampohermoso&layout=compact&theme=default)
