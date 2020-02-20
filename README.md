# Intro to Video Game Making

It's easy to look at computer code and say "what is that?! Nope, nope, nope, nope, NOPE."

<img src="https://i.imgur.com/YEDF7VK.png" width="960">

This is what I spend all of my time doing. What am I even doing with my life?

But it doesn't have to be! Let's break it down step-by-step. Matt and I will be using the Unity game engine here today, so we'll naturally be talking about a lot of the specifics of the Unity, but the general principles apply to pretty much anything you might want to make a game in.

By the way, if you want the project files here, they're all on a website known as Github, where you can download it, follow along, mess with it, do whatever. If you're reading this file, you might already be here.

## Part 0 - Empty Unity Project

When you first open up a blank Unity project, it'll look something like this. Note that Unity lets you pick between 2D and 3D when you start a new project. It doesn't *really* matter, but I'll be going with 3D here.

<img src="https://i.imgur.com/i6urpfI.png" width="960">

Not too bad, right? That's it. That's Step Zero. The first one's free.

## Part 1 - Setting Some Stuff Up

If I could have figured out a way to alliterate that entire title, I would have.

We'll start adding some things to the world. Go to the menu at the top of the Unity editor, go to Game Object, 3D Object, Plane. That's going to create a new object in the game world, which is going to be the floor. Cool. If you click on it, some interesting things start to happen. You can see all of its properties in the Inspector over on the side of the screen, which we won't worry about right now.

Let's add something else. GameObject, 3D, but this time pick a Capsule. If you're not familiar with capsules, they're basically pill shapes. They're kinda like cylinders, but they have rounded ends. Anyway, that's the Player.

The first thing you'll probably notice is that our Player is sinking through the floor a little. That's okay. You can move it out of the floor by clicking on the little green arrow in the middle of it (the "transformation axes," if you like technical words) and dragging it upwards.

<img src="https://i.imgur.com/CuQ1DC8.png" width="960">

Awesome.