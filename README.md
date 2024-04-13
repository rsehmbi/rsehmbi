
```python3

class SoftwareDeveloper(GithubUser):

    def __init__(self):
        self.name = "Raman Sehmbi"
        self.role = "Software Developer"
        self.languages_spoken = ["pa_IN", "en_CA"]

    def get_current_work_experience(self):
        return "Currently working on safeguarding AI!"

    def get_previous_work_experience(self):
        return [
            "Imagia Canexia Health",
            "ThoughtFarmer",
        ]

    def get_skills(self):
        return {
            "languages": ["Python", "Javascript"],
            "other": ["Kotlin", "Java", "C#", "C++"],
            "frontend": ["Angular", "React"],
            "backend": ["Django", "Flask", "FASTAPI"],
            "databases: ["mongo", "MySql", "sqlite" , "postgres"],
        }

    def favQuotes(self):
        return [
            "It's called VS Code because its you VS your code always!",
            "Strive to be uncommon amongst uncommon people",
        ]    
    
    def saying_hello(self):
        print("Hello there 👋")
    

i_am = SoftwareDeveloper()
i_am.saying_hello()

```

![Visits Badge](https://badges.pufler.dev/visits/rsehmbi/rsehmbi)

### Certifications:

* [Python REST APIs With FastAPI on Real Python](https://realpython.com/certificates/5b31a000-44d3-413e-bf7d-c5ad0ee36d23/ "Python REST APIs With FastAPI on Real Python")
* [Main Functions in Python on Real Python](https://realpython.com/certificates/87b0f81c-4dcf-4226-b077-3323e5cb27ef/ "Main Functions in Python on Real Python")
