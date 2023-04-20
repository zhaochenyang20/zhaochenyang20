<!-- [![Top Langs](https://github-readme-stats.vercel.app/api/top-langs/?username=zhaochenyang20&layout=compact)](https://github.com/Christmas/github-readme-stats)

[![Anurag's github stats](https://github-readme-stats.vercel.app/api?username=zhaochenyang20)](https://github.com/anuraghazra/github-readme-stats)
 -->
 

<div style="display:flex;">
  <img src="https://raw.githubusercontent.com/zhaochenyang20/zhaochenyang20.github.io/master/img/profile.jpg" alt="profile" width="340" />
  <img src="https://github.com/zhaochenyang20/zhaochenyang20.github.io/blob/master/img/profile_7.jpg" alt="profile" width="300" />
</div>

<div style="display:flex; flex-direction:row">
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=zhaochenyang20" width="340">
  <img src="https://github-readme-stats.vercel.app/api?username=zhaochenyang20" width="300">
</div>
 
```python

import random
import time
import uuid

class Eren:
    def __init__(self, uuid: uuid.UUID) -> None:
        self.uuid = uuid
        self.gender = 'boy with long hair'
        self.pronouns = {'he', 'him', 'his'}
        self.skills = ['Python', 'Linux', 'NLP']
        self.os = ('MacOS', 'Linux')

    def career(self, year: int) -> str:
        current_year = time.localtime().tm_year
        if year < current_year:
            return f"In {year}, I was a student."
        elif year == current_year:
            return f"Now, I'm an NLP researcher!"
        else:
            return "Maybe in the future, I'll become a writer!"

    def hobby(self) -> str:
        interests = [
            'Science Fiction', 'Machine Learning', 'Running',
            'Astronomy', 'Software Defined Radio', 'Japanese',
            'Playing Guitar', 'Sketching', 'Cooking',
            'Hiking', 'Photography', 'Gaming'
        ]
        return random.choice(interests)

world = 'Universe'
uuid_ = uuid.uuid5(uuid.NAMESPACE_DNS, 'Eren Zhao')

me = Eren(uuid_)

print(f"Hi! I'm Eren, a {me.gender} with skills in {', '.join(me.skills)}.")
print(f"I'm interested in {me.hobby()}, and my OS of choice is {me.os[0]}.")
print(f"just contact me through zhaochenyang20@gmail.com!")


```

# See More At

**[my about](https://zhaochenyang20.github.io/about/)**

**[my CV](https://chenyangzhao.vercel.app/about)**

**[my literatures](https://zhaochenyang20.vercel.app/)**


