```python 
class MAGICXcmd:

    def __init__(self):
        self.name = "Misha Gusev"
        self.role = "Junior Python-developer"
        self.languages = ["ru_RU", "en_US"]
        self.code = ["Pascal", "Python", "HTML", "CSS"]
        self.tools = ["Git"]
        self.os = ["Windows", "Linux"]
        self.learning = ["Django", "DRF", "Docker", "SQL", "SQLite", "MySQL", "PostgreSQL"]

    def social_links(self):
        self.website = "https://magicxcmd.github.io/"
        self.vk = "https://vk.com/haxgun"
        self.telegram = "https://t.me/haxgun"


    def say_hi(self):
        print("Hi! I hope you find something useful among these things :)")


me = MAGICXcmd()
me.say_hi()
```
