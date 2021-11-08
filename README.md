### My life cycle


```C
#include "../kitchen/coffee.h"
#include "Me.h"

Me me = Me("MCruces-fz");
Coffee coffee = Coffee();

while (me.is_alive()) {
  if (coffee.is_empty()) {
    coffee.refill();
  } else {
    me.drink(coffee);
    me.write_code();
  }
}
```
[![Top Langs](https://github-readme-stats.vercel.app/api/top-langs/?username=MCruces-fz&layout=compact&langs_count=10&theme=dracula)](https://github.com/anuraghazra/github-readme-stats)

<!--
**MCruces-fz/MCruces-fz** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
