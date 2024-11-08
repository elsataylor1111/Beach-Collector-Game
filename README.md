Beach Collector Game

Welcome to Beach Collector, a fast-paced beach adventure! Dive into a sunny beach setting as the main character. Your mission is to collect beach treasures—like colorful fish and seashells—while dodging dangerous bombs that track your every move. For every beach-related object you collect, you earn points and hear a cheerful success sound. But beware! Hitting a bomb will make you lose one of your three lives, accompanied by a sharp warning sound. Run out of lives, and it’s game over. As you play, the challenge ramps up: more items fly in, and you’ll need quicker reflexes to avoid the bombs. How many treasures can you collect before the beach gets too chaotic?

General Information 

Since Beach Collector is an artistic game, the creative challenge  invites players to engage in an immersive experience as players experience a balance between beauty and chaos as they collect beach items while avoiding bombs. The game symbolizes navigating growing complexities in a relaxing environment, inviting players to adapt, focus, and stay in the flow amid rising challenges. 

The purpose of my game is to create an engaging artistic experience where players have fun playing a beach related game and have to balance enjoyment and focus. 

I chose this as my game because I wanted to capture and share the joy of being at the beach, as being at the beach as many positive memories. 

Technologies Used
- MakeCode Arcade

Features 
- Different objects fly into the screen at random locations and times
- Your score increases or decreases depending on what object you collect
- A sound is played when you collect objects

Screenshot
<img width="1289" alt="Screenshot 2024-11-08 at 9 03 22 pm" src="https://github.com/user-attachments/assets/686078ce-5b32-4e27-9530-e1dfb0062419">

Setup

Once the game as loaded, objects will start spawning into the screen and that is when the game is ready to be played. Once you open up the game you have to be read and objects will start spwaning almost instantly.

Usage

The game is played online using your arrow keys to control the character. Or if you are playing with the physical Microsoft game kit, then you will use the controllers on the left. 

on_on_overlap(sprite, otherSprite):
    sprites.destroy(otherSprite)

music.play(music.melody_playable(music.ba_ding),
        music.PlaybackMode.IN_BACKGROUND)

shell.set_position(randint(0, scene.screen_width()),
        randint(0, scene.screen_height()))
    shell.set_velocity(0, 50)
    shell.set_bounce_on_wall(True)

Project Status

Complete

Room for Improvement
- As I changed my coding and added more features, my original code began to glitch. This could be fixed and improved however I was unable to figure out how to do this without removing the features I was adding.
- Have the background move around to add more effects.
- Bombs to spawn from random locations.
- Character to start from the middle of the screen and seemingly move around (this was one of the glitches I came across when I added other codes into my game).

Acknowledgements
- This project was inspired by the beach and the fruit ninja game from my childhood. 
- This project was based on the week 5 tutorial. https://canvas.uts.edu.au/courses/33108/pages/week-05?module_item_id=1822515
