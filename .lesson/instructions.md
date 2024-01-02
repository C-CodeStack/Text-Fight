# Text Fight

Create a text based fighting game that matches the following criteria

1. log "Welcome to text fight where you go toe to toe with a monster"
2. ask "What is the heroes name?"
3. log "??? is a great name for a hero"

for step three you will have to use a technique like this
console.log(nameVariable + " is a great name for a hero")

4. generate and save a random number between 300 and 500 for the heros health and 350 - 600 for the monsters health

use this function
```javascript
function roll(min, max) { 
    return Math.round(Math.random() * (max - min) + min)
}
```

5. log "`hero name` hitpoints is ___"
6. log "`monster name` hitpoints is ___"
7. ask "Would you like to attempt to (a)ttack or (d)efend?"
8. you roll 0-50 and the monster rolls 0-50

`If` attack 

  `If` your attack is `greater than` the monsters defense then the monsters hitpoints drop whatever your roll was and you log "Hit"

  `If` your attack is `less than` the monsters defense then the monster gains whatever his roll was as health. Log "Missed"

`If` defend

  `If` your defense is `greater than` the monsters attack then you gain whatever your roll was as health. Log "Blocked"

  `If` your defense is `less than` the monster attack then your hitpoints drop whatever the monsters roll was and you log "Failed"

9. log  "nameVariable life = hero hip points"
10. log "monster life = monster health"

11. Check to see if either players hitpoints has fallen below 1(dead)

Repeat step 7-11 until someone is dead

12. If player died log "The monster killed you, you lose!"
13. If the monster died log "You killed th emonster, you win!"