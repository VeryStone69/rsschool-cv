# Aliaksandr Koptsevich

## Contacts

- Location: Poland, Gdansk.
- Phone: +48 536 071 925 (PL), +375 29 105 1 105 (BY)
- Email: carcer2007@gmail.com
- [GitHub](https://github.com/verystone69)
- [Linkedin](https://www.linkedin.com/in/alexunder-koptsevich/)

---

## About Me

All my life I have been interested in technology, computers and gadgets. But I spent a lot of time on a job that weren't interesting. And now I want to start working in exciting and interesting field with like-minded people.
I am a sociable person, a real team player and I am very willing to learn and develop new skills. I hope that with the help of the RS school community, I will achieve my goals and help other people achieve theirs.

---

## Skills and Proficiency

- HTML5, CSS3/SASS, Bootstrap
- JavaScript
- Git
- VS Code, Brackets, WebStorm
- BEM methodology
- Figma, Photoshop

---

## Code example

**KATA (6 kyu) from CODEWARS:** You live in the city of Cartesia where all roads are laid out in a perfect grid. You arrived ten minutes too early to an appointment, so you decided to take the opportunity to go for a short walk. The city provides its citizens with a Walk Generating App on their phones -- everytime you press the button it sends you an array of one-letter strings representing directions to walk (eg. ['n', 's', 'w', 'e']). You always walk only a single block for each letter (direction) and you know it takes you one minute to traverse one city block, so create a function that will return true if the walk the app gives you will take you exactly ten minutes (you don't want to be early or late!) and will, of course, return you to your starting point. Return false otherwise.

```
function isValidWalk(walk) {
    let n = 0, w = 0, s = 0, e = 0;

    if(walk.length != 10) return false;

        for (let item of walk) {
            if(item == 'n') n++;
            if(item == 'w') w++;
            if(item == 's') s++;
            if(item == 'e') e++;
        }

    if (n == s && w == e) return true;
    else return false;
}
```

---
