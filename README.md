```python
┌──(bubblegum@root)-[~/]
└─$ py bubblegum.py

class Bubblegum:
    def __init__(self):
        self.name = "Bubblegum"
        self.aliases = ["Workaholic", "Code Alchemist"]
        self.skills = ["Python", "Rust", "C", "Kotlin"]
        self.current_project = "Memory, Cheats, and Anticheats on Low Level"
        self.ide = "VSCode"

    def __social__(self):
        self.github = "https://github.com/suspectedesp"
        self.pypi = "https://pypi.org/user/vortexsys/"
        self.linkedin = "Not yet"

    def __vibe__(self):
        return "Creating new ways to mod, code, and break boundaries. Living fast, thinking deeper."

    def __hobbies__(self):
        return ["Music Production", "Experimenting with Game Mods", "Learning Spanish", "Creating D&D Campaigns"]

if __name__ == "__main__":
    bubblegum = Bubblegum()
    print(f"Name: {bubblegum.name}")
    print(f"Aliases: {', '.join(bubblegum.aliases)}")
    print(f"Skills: {', '.join(bubblegum.skills)}")
    print(f"Current Project: {bubblegum.current_project}")
    print(f"Socials: GitHub: {bubblegum.github}, PyPI: {bubblegum.pypi}, LinkedIn: {bubblegum.linkedin}")
    print(f"Vibe: {bubblegum.__vibe__()}")
    print(f"Hobbies: {', '.join(bubblegum.__hobbies__())}")


 ┌──(bubblegum@root)-[~/]
 └─$
```
<img src="https://raw.githubusercontent.com/Sutil/Sutil/2b2fad3bf54522bb30c8c170591fc68ff51b69e6/github-contribution-grid-snake2.svg">
