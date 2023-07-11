Crée une liste de notes et de durées pour composer une mélodie.

Tu peux alors utiliser une boucle pour `jouer` le morceau une note à la fois :

--- code ---
---
language: python
filename: sound_machine.py
line_numbers: false
---
RYTHME = 0.4

liten_mus = [ ['d5', RYTHME / 2], ['d#5', RYTHME / 2], ['f5', RYTHME], ['d6', RYTHME], ['a#5', RYTHME], ['d5', RYTHME],  
              ['f5', RYTHME], ['d#5', RYTHME], ['d#5', RYTHME], ['c5', RYTHME / 2],['d5', RYTHME / 2], ['d#5', RYTHME], 
              ['c6', RYTHME], ['a5', RYTHME], ['d5', RYTHME], ['g5', RYTHME], ['f5', RYTHME], ['f5', RYTHME], ['d5', RYTHME / 2],
              ['d#5', RYTHME / 2], ['f5', RYTHME], ['g5', RYTHME], ['a5', RYTHME], ['a#5', RYTHME], ['a5', RYTHME], ['g5', RYTHME],
              ['g5', RYTHME], ['', RYTHME / 2], ['a#5', RYTHME / 2], ['c6', RYTHME / 2], ['d6', RYTHME / 2], ['c6', RYTHME / 2],
              ['a#5', RYTHME / 2], ['a5', RYTHME / 2], ['g5', RYTHME / 2], ['a5', RYTHME / 2], ['a#5', RYTHME / 2], ['c6', RYTHME],
              ['f5', RYTHME], ['f5', RYTHME], ['f5', RYTHME / 2], ['d#5', RYTHME / 2], ['d5', RYTHME], ['f5', RYTHME], ['d6', RYTHME],
              ['d6', RYTHME / 2], ['c6', RYTHME / 2], ['b5', RYTHME], ['g5', RYTHME], ['g5', RYTHME], ['c6', RYTHME / 2],
              ['a#5', RYTHME / 2], ['a5', RYTHME], ['f5', RYTHME], ['d6', RYTHME], ['a5', RYTHME], ['a#5', RYTHME * 1.5] ]

for note in liten_mus:
    haut_parleur.play(note) 

--- /code ---