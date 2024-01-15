# How-to-create-function-in-JavaScript-
**_At the beginning of your file, import the class that you will use in the function._**

- Test Function:
- The function consists in giving the player a given number on the scoreboard

```
export function setScore(participant, objective, score) {
    try {
        return world.scoreboard.getObjective(objective).setScore(participant, score) ?? 0;
    } catch {
        return 0;
    };
};
```
- How to perform this function now?
Do: 
```
setScore(player, 'objective', score)
```
