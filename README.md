# Summoners Battle
Mobile game project for my studies in Android Studio (Java).

---

It's a simple turn-based strategic game for my studies.
In this game, you sequentially select three heroes to battle against a single monster.

When we are in the hero selection phase, we choose one of the three heroes that are randomly drawn from a pool of 12 different characters at the beginning. We make these choices three times, and no previously chosen hero can be repeated.
When we click on a heroes, we can see their statistics, available attacks and spells. Therefore, it's worth taking a moment to think about the team we will assemble so that each character can collaborate with each other. This way, we can defeat the monsters and win the game.

The most challenging mechanic to implement was the speed statistic. Each hero had their own speed value, which determined how frequently they could act based on the elapsed time. As a result, fast characters would move three times while others could only move twice.

Once you defeat an opponent, you get to choose an artifact that passively increases the statistics of your heroes. This allows for further customization and strategic decision-making in improving your team's abilities. The goal of the game is to complete seven levels, and upon doing so, you win the game.

---

