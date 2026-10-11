🤖 Bot Battle Royale (Python Arena)
The Game Concept
This is a text-based auto-battler. Each student creates a unique digital gladiator. All created characters are gathered in a single file, and the script runs a survival tournament. The fighters automatically attack each other until only one absolute champion remains.

Tournament Rules:

Fights are strictly "1 vs 1".

Opponents take turns attacking. Damage in each round is calculated randomly within a specified range.

The winner of a match stays on the arena and immediately fights the next challenger (HP does not reset between fights!).

The last bot standing wins the tournament.

Fighter Anatomy
Each character in the code is represented as a Python dictionary with the following attributes:

name: Your hero's name (e.g., "Cyborg Killer" or "Deadline Student").

hp: Health points.

attack: Damage range from minimum to maximum. Written as a tuple, e.g., (5, 20).

phrase: A catchphrase. The bot will shout it in the console upon defeating an opponent.

⚖️ Main Balance Rule (Anti-Cheat)
To keep the tournament fair, there is a strict limit: The sum of your HP and maximum attack damage must not exceed 120.

Allowed: HP 100 + Attack (5, 20). Sum is 100+20 = 120. (The "Tank" build)

Allowed: HP 80 + Attack (10, 40). Sum is 80+40 = 120. (The "Glass Cannon" build)

Forbidden: HP 100 + Attack (50, 100). Such Pull Requests will be rejected during code review!

Your Task for Today:

Fork the arena repository to your own GitHub account.

Clone it to your local machine.

Create your fighter and add it strictly to the ROSTER list (do not forget the comma at the end of your line!).

Run git add, git commit, git push, and open a Pull Request to the main repository.