# 06-Zombie-Runner
In this section we create a First Person Shooter with a zombie theme. We cover raycasting for shooting and the core mechanics you'd expect in an FPS. This repo is part of our Complete Unity C# Developer 3D course (http://gdev.tv/cu2github). (Ref: ZR_CU2)

# Complete Unity Developer 3D - Zombie Runner

This is the [Complete Unity Developer 3D](http://gdev.tv/cu2github) - one of the most successful e-learning courses on the internet! Completely re-worked from scratch with brand-new projects and our latest teaching techniques. You will benefit from the fact we have already taught half a million students game development, many shipping commercial games as a result.

You're welcome to download, fork or do whatever else legal with all the files! The real value is in our huge, high-quality online tutorials that accompany this repo. You can check out the course here: [Complete Unity Developer 3D](http://gdev.tv/cu2github)

## In This Section

In this section we create a First Person Shooter with a zombie theme. We cover raycasting for shooting and the core mechanics you'd expect in an FPS. This repo is part of our Complete Unity C# Developer 3D course (http://gdev.tv/cu2github). (Ref: ZR_CU2)

## How To Build / Compile

## Lecture List

Here are the lectures of the course for this section.


### 1 Welcome To Zombie Runner ###

**In this video (objectives)...**

1. Overview of this section.
2. Demo of the game prototype.

**After watching (learning outcomes)...**

Ready and raring to start this section.


### 2 Zombie Runner Game Design ###

**In this video (objectives)...**

1. Discussion of the game overview screen and core features.
2. Reminder that we're using Unity 2019.1.

**After watching (learning outcomes)...**

Super clear on the game we are making and the feature priorities.

### 3 Adding First Person Controller ###

**In this video (objectives)...**

1. Download Unity Standard Assets.
2. Implement the First Person Controller with RigidBody.

**After watching (learning outcomes)...**

Get and add the First Person Controller to our scene.

### 4 Make A Prototyping Sandbox ###

**In this video (objectives)...**

1. Use Unity's simple prototyping geometry to make a simple level.
2. Make sure there are different obstacles to test the expected functionality in the game.

**After watching (learning outcomes)...**

Create a simple sandbox level for prototyping.

### 5 Using NavMeshAgent For AI ###

**In this video (objectives)...**

1. Add a placeholder enemy with NavMeshAgent component.
2. Bake our NavMesh.
3. Create EnemyAI.cs and add logic to move the enemy towards the player.

**After watching (learning outcomes)...**

Use the NavMeshAgent component to drive the enemy towards the player.


### 6 Getting Stuck & Jittering ###

**In this video (objectives)...**

1. Fix jitter by removing head bob.
2. Stop player getting stuck on walls by adding a physics material.

**After watching (learning outcomes)...**

Fix some issues with our first person controller.


### 7 Enemy AI - Chase Range ###

**In this video (objectives)...**

1. Make the enemy and player more obvious in their positions.
2. Create logic that tells the enemy to move to the target if the target is within the chase range.

**After watching (learning outcomes)...**

Move the enemy to the target if the target is within range.


### 8 Using OnDrawGizmosSelected() ###

**In this video (objectives)...**

1. Use the Unity docs to figure out how to draw a gizmo which shows the chase range of our enemies.

**After watching (learning outcomes)...**

Use gizmos to visualise chase range.


### 9 Enemy AI - Attack If Provoked ###

**In this video (objectives)...**

1. Structure our EnemyAI class so we have logic for the enemy being provoked.
2. Use the nav mesh stopping distance as part of our conditions for attacking or not.

**After watching (learning outcomes)...**

Add to our enemy AI, causing it to attack if provoked.


### 10 Give That Player A Gun ###

**In this video (objectives)...**

1. Import a weapon and attach it to the player.
2. Add a reticle the the UI canvas.

**After watching (learning outcomes)...**

Give the player a weapon asset.


### 11 Introduction To Raycasting ###

**In this video (objectives)...**

1. Overview of how Raycasting works.
2. Add a ray that is cast when the player clicks their shoots (clicks their mouse button).
3. Print to the console the thing that we hit.

**After watching (learning outcomes)...**

Implement raycasting so we can shoot an invisible laser beam.
