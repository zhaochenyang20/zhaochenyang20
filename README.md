<!-- [![Top Langs](https://github-readme-stats.vercel.app/api/top-langs/?username=zhaochenyang20&layout=compact)](https://github.com/Christmas/github-readme-stats)

[![Anurag's github stats](https://github-readme-stats.vercel.app/api?username=zhaochenyang20)](https://github.com/anuraghazra/github-readme-stats)
 -->
 
```python
class Eren:
    def __init__(self, UUID: uuid.UUID) -> None:
        self.UUID = UUID
        self.gender = Demiboy()
        self.pronouns = {"Eren", "Chenyang"}
        self.code = ["Python", "Linux"]
        self.OS = ("MacOS", "Linux")

    def career(self, year: int) -> str:
        self.career = ["Student", "NLP researcher"]
        now: int = time.localtime()[0]
        if year < now:
            return f"I was a {self.career[0]}."
        elif year == now:
            return f"I am a {self.career[1]} now."
        else:
            return "Maybe I'll become a Writer in the future!"
    
    def hobby(self, index: int = random.randint(0, 69)) -> str:
        self.interests = [
            "Science Fiction", "Machine Learning",
            "Running", "Astronomy",
            "Software Defined Radio", "Japanese",
        ]  # And More
        return self.interests[index % len(self.interests)]

world = Universe.World()
ME = Eren(uuid.uuid5(world.UUID, "Eren Zhao"))
```

# See More At

**[my about](https://zhaochenyang20.github.io/about/)**

**[my CV](https://chenyangzhao.vercel.app/about)**

**[my literatures](https://zhaochenyang20.vercel.app/)**


