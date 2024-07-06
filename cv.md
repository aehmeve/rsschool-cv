# Dzmitry Stadnichenka
## Contact information:
* Discord: aehmeve
* Telegram: @aehmeve
* Instagram: aehmeve

## Brief Self-Introduction:
Previously worked as a CAD designer.
Nowadays my main goal is to become fullstack developer. Currently focusing
on frontend development skills and technologies such as JavaScript,
React, TypeScript, Sass, Vite.<br>Also learning PHP and MySQL with a 
snail's pace for now.
Always open to new interesting coding challenges. Easy to work with.
In free time prefer to read books, learn new languages.
## Skills:
- HTML
- CSS
- JavaScript
- Sass
- MySQL
- Git
- GitHub
- Vite
## Languages and Education:
Education: BSU(Baranovichy State University) graduate. Machine Building Technology.
Languages:
- Russian ー native
- English ー upper-intermediate
- Japanese ー N3

## Code Example:
`
function whoWouldWin(mon1, mon2) {
  let mon1FullHP = mon1.hitpoints * mon1.number;
  let mon2FullHP = mon2.hitpoints * mon2.number;
              
  while (mon1.number > 0 & mon2.number > 0) {
    const mon1Attack = mon1.number * mon1.damage;
    mon2FullHP -= mon1Attack;
    mon2.number = Math.ceil(mon2FullHP / mon2.hitpoints);
    if (mon2.number < 0) break;
    const mon2Attack = mon2.number * mon2.damage;
    mon1FullHP -= mon2Attack;
    mon1.number = Math.ceil(mon1FullHP / mon1.hitpoints);
  }
              
  const result =
    mon1.number > 0
      ? `${mon1.number} ${mon1.type}(s) won`
      : `${mon2.number} ${mon2.type}(s) won`;

    return result;
}
`
[Heroes of Might & Magic II: One-on-One (6 kyu)](https://www.codewars.com/kata/5b114e854de8651b6b000123)
## Projects:
[Coffee House (RSSchool 2023Q4 Stage #1)](https://rolling-scopes-school.github.io/aehmeve-JSFE2023Q4/coffee-house/)
