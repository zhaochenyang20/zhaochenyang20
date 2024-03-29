# Eren Chenyang Zhao

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

江水、高墙、犬吠决不能阻止他们的出逃，因为他们的心中有一座灯塔，比主体思想塔更明亮，更永垂不朽，他们的心中有一座宫殿，比锦绣山太阳宫更屹立不倒。

The rivers, high walls, and barking dogs cannot stop their escape, because in their hearts, there is a lighthouse brighter and more eternal than the Tower of Juche ideology. In their hearts, there is a palace more unshakable than the Kumsusan Palace of the Sun.

# See More At

**[My Anecdote](https://zhaochenyang20.github.io/about/)**

**[my Personal Info](https://zhaochenyang20.github.io/Eren_Chenyang_Zhao/)**

<div style="display:flex;">
  <img src="https://raw.githubusercontent.com/zhaochenyang20/ivue_wallpaper/main/github_readme/1.jpg" alt="profile" width="368" />
  <img src="https://raw.githubusercontent.com/zhaochenyang20/ivue_wallpaper/main/github_readme/4.jpg" alt="profile" width="375" />
</div>

<div style="display:flex;">
  <img src="https://raw.githubusercontent.com/zhaochenyang20/ivue_wallpaper/main/github_readme/3.jpg" alt="profile" width="393" height="473" />
  <img src="https://raw.githubusercontent.com/zhaochenyang20/ivue_wallpaper/main/github_readme/2.jpg" alt="profile" width="350" />
</div>


<div style="display:flex; flex-direction:row">
  <img src="https://github-readme-stats.vercel.app/api?username=zhaochenyang20" width="743">
</div>

