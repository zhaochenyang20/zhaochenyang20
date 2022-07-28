[![Top Langs](https://github-readme-stats.vercel.app/api/top-langs/?username=zhaochenyang20&layout=compact)](https://github.com/Christmas/github-readme-stats)

[![Anurag's github stats](https://github-readme-stats.vercel.app/api?username=zhaochenyang20)](https://github.com/anuraghazra/github-readme-stats)

```python
class Eren:
    def __init__(self, UUID: uuid.UUID) -> None:
        self.UUID = UUID
        self.gender = Demiboy()
        self.pronouns = {"He", "Him"}
        self.code = ["Python", "JavaScript", "C/C++", "Linux"]
        self.OS = ("MacOS", "Linux")

    def career(self, year: int) -> str:
        self.career = ["Student", "CV Engineer"]
        now: int = time.localtime()[0]
        if year < now:
            return f"I was a {self.career[0]}."
        elif year == now:
            return f"I am a {self.career[1]} now."
        else:
            return "Maybe I'll become an Author in the future!"
    
    def hobby(self, index: int = random.randint(0, 69)) -> str:
        self.interests = [
            "Science Fiction", "Machine Learning", "Chemistry",
            "Computer Vision", "Computer Music", "Astronomy",
            "Music", "Software Defined Radio", "Japanese",
            "Running", "Not Tetris 2"
        ]  # And More
        return self.interests[index % len(self.interests)]

world = Universe.World()
ME = Eren(uuid.uuid5(world.UUID, "Eren Zhao"))
```

# See More At
**[my about](https://zhaochenyang20.github.io/about/)**
