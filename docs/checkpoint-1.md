# Step 8: Checkpoint 1

We've learned a lot, let's have an intermediate project to put the skills we've learned so far to the test. This assignment is considerably harder than the previous steps, and should take much longer.

Create a new file called `Game.java`. Create a static main function in there similar to the one in `Main.java`.

Within this main function, write a program which will be a text engine player vs bot game. Here's how.

1) Define the variables. You'll need a health, damage, and defense stat for both the player and the enemy/opponent. There'll be other variables necessary later on as well.

2) Until either you or the enemy is dead, repeat rounds over and over again. Each round has the following:

- First, print `beginning round i` where i is the round # (starts at 1)
- Next, the player performs an action by typing the first letter of their desired action. If the letter typed is invalid, print that and wait for a new action.
- Print the selected action to the console.
- Perform the action. Here are the actions:
  - Attack: Deal damage to the enemy
  - Strengthen: Increase your damage by 10%
  - Weaken: Decrease your enemy's defense and damage by 10%. Only has a 50% chance of working
  - Heal: Heal to full health. This can only be done once. If tried again, the ability fails and the turn is skipped saying that `the ability failed`.

- If the opponent is dead, write a game over message and stop the program. Print the player's remaining health.

- Select a random action for the opponent to perform. Here are their actions:
  - Attack (60%): Deal damage to the player
  - Harden (20%): Increase defense by 5
  - Poison (20%): Deal damage / 2 to the player for the next 6 turns. Player defense does not apply. If the player is already poisoned, the bot should only try to Attack and Harden with the renormalized probabilities.

- If the player is dead, write a you win message and stop the program. Print the opponent's remaining health

- Print the player's health, damage, defense, and poison status. Print the opponent's health.