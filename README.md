<img align="right" width="350" height="350" src="https://user-images.githubusercontent.com/45884656/173171548-21401b3a-8818-4526-9708-118e31965fb7.gif">


```python
#!/usr/bin/python
# -*- coding: utf-8 -*-


class SoftwareDeveloper(GithubUser):

    def __init__(self):
        self.name = "Raman Sehmbi"
        self.role = "Software Developer"
        self.company = "Imagia Canexia Health"
        self.language_spoken = ["pa_IN", "en_CA"]

    def saying_hello(self):
        print("Hello there 👋")


i_am = SoftwareDeveloper()
i_am.saying_hello()

```

```kotlin
package raman.github.landingpage

class Raman : GithubUser() {
    init {
        println("About Me: A living machine that turns coffee into code!")
    }
    
    val prodCodingLang = ["Python", "C#"],
    val developCodingLang = ["Kotlin", "Java", "Javascript", "HTML", "C++"]
    val askMeAbout = ["web dev", "tech", "app dev", "hiking", "workouts"],
    val technologies = {
        frameworks: {
            frontEnd: ["Angular"]
            web: ["Django"]
        }
        backEnd: {
            js: ["Node", "Express"],
        },
        mobileApp: {
            native: ["Android Development"]
        },
        devOps: ["AWS-Glue", "Docker🐳", "Nginx"],
        databases: ["mongo", "MySql", "sqlite" , "postgres"],
        misc: ["Firebase", "Socket.IO", "selenium"]
    },
    architecture: ["Serverless Architecture", "Progressive web applications", "Single page applications", "Micro-services"],
    favQuote: "It's called VSCode because its you VS your code always!"
}
```
