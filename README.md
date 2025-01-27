![Linkedin background fav](https://github.com/user-attachments/assets/2dd1fd56-8d6d-4671-a3a7-21515c8a9115)
<h4 ><samp>  Hi 👋, I'm a Systems Engineering student with experience in software development and data science. Passionate about solving complex problems through technology and data analysis, I specialize in process optimization and thrive in collaborative environments. As the leader of the AWS User Group La Paz, I promote teamwork, cloud technology learning, and the development of collaborative skills within the community. </samp></h4>

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
                "degree": "Systems Engineering",
                "status": "Student"
            }
        ]

    def get_skills(self):
        return {
            "programming_languages": [
                "Python", "Java", "C++", "JavaScript", "Go", "Dart", "R"
            ],
            "web_development": [
                "HTML", "CSS", "PHP", "Django", "Flask", "Spring"
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
                "name": "Digital Platform for Parking Rental and Reservation",
                "achievement": "1st place in FUNCTEC 2024"
            },
            {
                "name": "Web Application for Route Optimization in Mi Teleférico",
                "achievement": "2nd place in FUNCTEC 2024"
            }
        ]

    def __str__(self):
        return f"{self.name}, student of {self.education[0]['degree']} at {self.education[0]['institution']}."
```

