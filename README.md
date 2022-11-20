# Project-Illunae

![Illunae_Trailer_old](https://user-images.githubusercontent.com/3580918/202921111-7ca71f15-33b2-4dd4-8090-9ae34405ee8c.png)

A VR game built in Unity about collecting magical Crystal essences to create a unique mix of sounds to meditate with.

**Current Build for Oculus Quest 2 PCVR:**
https://drive.google.com/drive/folders/1qM3lqn2pGcM2yTFeedyoZ0PRPTofn_qk?usp=share_link

Short Trailer:

https://user-images.githubusercontent.com/3580918/202920894-9e2b73f1-3f82-482a-941a-4c1f59e941f4.mp4

**Notion Documentation:**
https://chartreuse-bar-454.notion.site/Illunae-22e2400fde9142e4a907e10d396b1e75

The notion documentation has representative images, videos, long and short description, gameplay mechanics, bug list as well as current & future contents. 

**Instructions for Playing the Game:**
-The player will be greeted with a window asking if they want to play the tutorial. Reach out and touch the tick symbol on the left to start the tutorial. 
-Follow and listen carefully to Vera, who will guide you verbally on the tutorial steps. 
-For the first interactions, the points of reference are highlighted with a yellow glowy orb, when needed.
-There are 3 portals that can be used, which require the player to hold a staff. 
-The river biome has 3, the space biome has 3 and the cavern biome has 2 crystal nodes that can be “sung” for crystal essences (voices).
-There is a holster mechanic for storing the staff, but is a little buggy in other scenes in terms of positioning.
-Currently the perimeter of the lobby and the sides of the space biome away from the asteroids are not covered fully with colliders, so players may fall from the world if they venture into such areas. There is currently no way to exit, other than ctr-alt-del killing of the application.


**Known Bugs:**

-Occasional falling through world, especially during scene loading.
-Space scene does not have invisible barriers on sides.
-Vera (tutorial) animation & position issues.
-Crystal staff appearing back on table after returning to lobby.
-Crystal singing and synth sounds stopping abruptly without fade.
-Lighting related glitches in lobby, caused by fireflies.
-Crystal staff shader issues when singing.
-Holsters can be above or below intended height.


--------------
# NYU-Capstone
Below is my devlog for Project Illunae, which I submitted my graduation project from NYU's Professional Certificate in XR Development program that I started in March 2022 and finished in Novemeber 2022.


**29 September 2022:**

Finally started the capstone project! As part of the course material, I will be working on a motion test / styleframe for my project and as such, for the first steps I wanted to create one of the possible environments that the player will be able to go on a meditative experience in and showcase the crystal mining concept.

![29Sept-RockGenerator](https://user-images.githubusercontent.com/3580918/193138225-c39a69a7-10bf-4ccb-b7df-31737911aded.png)

I used Stylized Rock Generator (https://assetstore.unity.com/packages/tools/modeling/stylized-rock-generator-223628) that came with one of the humblebundle bundles to create unique rock formations that would serve as the walls of the canyon.

I am also experimenting different visual effects that would catch the player's eye to focus on mineable crystals that will be found throughout the valley:


https://user-images.githubusercontent.com/3580918/193142301-c6d6ba9d-2162-402e-933e-604408d0794b.mp4

Overall, I feel like its a good start!

**1 October 2022:**

Today I focused on creating the floor and finding a nice water shader that works well. I also have a skybox that matches the color scheme / mood I am aiming for. Tomorrow I will have to work on bringing in more props to enhance the feel and add more crystals.



https://user-images.githubusercontent.com/3580918/193418801-31a0c065-a138-4dd2-b0e1-c2a80d822bd0.mp4

**2 October 2022:**
The sparkle animations on the crystals all started at same time so I randomized them a little. Also I utilized rock generator to create surrounding mountains for my scene. The result is not too bad:

![2Oct-Mountains](https://user-images.githubusercontent.com/3580918/193477026-8aa983aa-899f-4339-ab99-daed9a56b194.png)

Next I worked on skyboxes for something that makes the environment more immersive. I think this scene now reached enough maturity for presentation, so tomorrow I will move on to a new scene theme.

https://user-images.githubusercontent.com/3580918/193478569-ef6ad476-6093-41a2-868a-6664fda67c9a.mp4

**3 October 2022:**

Finally started on the space scene! I am utilizing the sci-fi space asset set from Synty Polygon series for its low-poly and high quality aspect for this part. I have added the planets and the sun for the overall environment and for the tiny portion of the cosmos where the scene will take place, i utilized a 5000 particle animated asteroid fx, as well as hand placed rocks & debris that randomly rotate.

![3Oct-Space1](https://user-images.githubusercontent.com/3580918/193593512-46ae26a6-704c-4279-b4b2-2bd3e0d93fd7.png)

The biggest challenge with working with open space is the openness itself, with a river or cave setting you can create the path you want the player to take through walls and mountains, but here it is more tricky. I tried a multitude of fx and ideas and finally i am settled with the warp effect that creates a light tunnel which should be enough visual cue for the player. 

![3Oct-Space2](https://user-images.githubusercontent.com/3580918/193593515-8b68f5d3-042c-4ea2-82c9-c17046c158fc.png)

In the end it will probably not be enough and I will have to place invisible colliders around to nudge the player back in the intended direction.

The current looks, before adding the crystals, crystal effects and ships for immersion:

https://user-images.githubusercontent.com/3580918/193594029-af4a992d-cae0-4aa1-bf08-2b63e13bf8f6.mp4

**11 October 2022:**

Today I switched my focus from trying to make the environment look better to actually finishing the motion tests for Assignment 22.2 and I have two videos from the space and the river scenes showcasing what I intend to do with my project:

Part1: River Scene:

https://user-images.githubusercontent.com/3580918/195109858-1dcc68e2-60c8-433a-ae4c-876a232abe28.mp4

Part2: Space Scene:

https://user-images.githubusercontent.com/3580918/195117875-3a1f78a5-f71e-459e-bfce-5c9eb307f1d4.mp4

The overarching/common theme of these scenes will be the controller-based movement through a unique biome in search of crystals that the player will be able to "mine" by singing to them at the correct pitch. 

Finally, for Assignment 22.2, I prepared and uploaded a miro board documentation:

![Assignment 22-2 Capstone Miro Board Documentation](https://user-images.githubusercontent.com/3580918/195146314-5c306851-932c-4903-af08-053c185969a1.jpg)

**13 October 2022:**

Instead of copy pasting the realistic hand avatar that we got to build for the course assignments, I decided to do a refresher on the whole hand interaction process and started again from week 13. Cubes for hands is what I got for now, but the grab interaction is working as intended.

Also, the Crystal Staff is freely floating in space when released, which is perfect for this biome.

https://user-images.githubusercontent.com/3580918/195654309-68a051af-ae89-497f-861d-647e86400eca.mp4

**Update**
After some trial and error, finally managed to get all hands rigged and tested the trigger/grab hand poses succesfully.

![13Oct-RiggedHands](https://user-images.githubusercontent.com/3580918/195680811-d0113362-0995-4a08-99e7-5b5920466e44.png)

One issue I still have to fix is that the object is being grabbed with the pointy finger mode, which should not be too difficult to fix.

**17 October 2022:**
I spent two days with the pose creator that was provided in the course, with no good results. 

![17OctGrabPoseCrystalStaff1](https://user-images.githubusercontent.com/3580918/196510609-9f43e5c4-0370-4b68-9197-5e84fa8a01ee.png)

There seems to be difficulty with aligning the rotations of the staff and the hand which cause the grab attach and the attach point of the interactable not to align correctly. I have decided to stop spending more time on this and depend on hide-hand-when-grabbed method for now. 

---
**18 October 2022**

I started working on the Lobby scene, which will have a desert/ruins biome:

![18OctLobby1](https://user-images.githubusercontent.com/3580918/196511610-07278d9a-d5a4-4dad-be38-ace8ff8efcb9.png)

I will have to find a matching skybox set and play with the lighting to make it a relaxing place.

---
**Update #1**

I used Farland Skies to create a nighttime sky with animated moon and stars for added immersion and utilized "Particle Systems: Lights" tutorial on Unity Learn (https://learn.unity.com/tutorial/particle-system-lights#) to make my fireplace cast lights on the cloth tent. I am very happy with the way how the fire plays around:

https://user-images.githubusercontent.com/3580918/196522067-7d4efe0c-abe5-497d-963d-a6c30d715c23.mp4

The Unity Learn tutorial gave me the idea to utilize fireflys to illuminate my night scene, I think this will be excellent for the immersive,relaxing environment I am after.

---
**Update #2**

It is amazing what some work with lights can do in a night scene. I added a point light source to the fireflies and turned off universal directional light completely. After tweaking radius, intensity and a few other metrics here is the result, which to me is not too bad:

https://user-images.githubusercontent.com/3580918/196526826-dd324277-5267-4f5c-8090-66c10948d393.mp4

---
**19 October 2022**

After playing around with grab interactable using the crystal staff, I was able to get rid of the jittery held object problem by changing the update method to instantenaus - now there is no more shaking or jittering of the held object.


https://user-images.githubusercontent.com/3580918/196823348-46c7b220-7ed6-4a87-a0ff-a5db98ef0a4b.mp4

---
**20 October 2022**
Thanks to Steven's help I was able to overcome the teleport bindings issue and I managed to get as far as working on the VFX for the Crystal Staff.

I actually already completed the effects during the 21st week of the course as part of the assignment, but now I am having some issues when I try to import the VFX file from that project into current one. I managed to get some of it working and also added some ambient sounds as well as a spatial firepit sound for more immersion:

https://user-images.githubusercontent.com/3580918/197088448-336edaab-d69c-460b-80e3-875a37a61f8e.mp4

---
**24 October 2022**
Two important updates in development: Inventory system in the form of a XR socket holster, as well as finally getting the audiovisual aspect of the singing mechanic done.

First video showcases the new holster system, for which I used https://www.youtube.com/watch?v=Xc5sx32cT1Q as inspiration:

https://user-images.githubusercontent.com/3580918/197531419-02de86ec-56b6-4e7d-b713-ad405faf7617.mp4

I tweaked the beacon VFX from the Synty Sci-Fi set for the animated visuals that show where the virtual holsters are. With this addition, the player will be able to take the Crystal staff, as well as any new crystals they find in the other scenes, back to the lobby.

The second and more exciting update for me is regarding the crystal singing. We tried with Steven to make this one work using the Output event Helpers (https://docs.unity3d.com/Packages/com.unity.visualeffectgraph@10.2/manual/OutputEventHandlers.html) so that when the flying notes VFX was activated, it would start singing the song. However, Steven quickly pointed out that the way the flying notes VFX is written involves already activated VFX that gets killed depending on the state of the boolean onHit, and as such, the intended outcome was not possible.

The much easier workaround which I have not thought before is simply using the XR interactable (custom MagicWand.cs) script and working with the onHoverEnter and onHoverExit, which I utilized the AudioSource.Play and AudioSource.Pause. The pause feature is also very important for me, since I do not want the singing to start from scratch every time the Crystal Staff stops pointing at the Crystal Node. 

https://user-images.githubusercontent.com/3580918/197532496-df14a290-a32b-47d1-aa64-0f00cbb82527.mp4

As can be seen the result is not perfect: There is a very abrubt cutoff the moment the hit is no longer registered and this kind of breaks the immersion. I will have to work with some coroutines to have a buffer there that will perhaps fade the song away within a second.

---
**26 October 2022**

Work continues on scene management & fade transition, as well as the portal system that will enable the players to travel to the different biomes. 

Meanwhile, I started working on some audio files for the onboarding & introduction using an animated NPC.

Here is Vera, who will greet the players and onboard them about what to do and what to expect in the lobby scene:

![Vera](https://user-images.githubusercontent.com/3580918/198085383-7d5802f7-4273-4499-b579-c7b164634bf3.png)

I have utilized the text-to-speech capabilities of the Edge browser that comes with Windows to record little voice-overs for onboarding:

Sample voiceover can be found here:
https://drive.google.com/file/d/1DjyAqtqB4p-nijWpPa3f_hLShh4Fr6Zi/view?usp=sharing

By next time I hope to have the scene management / portal teleport system in place.

---
**27 October 2022**

The issue with scenemanagement continues unfortunately. Chad has been kind enough to offer to look into it, hopefully it will be fixed soon!

I have been working with coroutines for other functionalities of the game and today I have a prototype of the Crystal absorbing mechanic:

https://user-images.githubusercontent.com/3580918/198304492-d591a177-dae4-4db5-bc78-7a34749a2666.mp4

I had to record from scene view since I am not at my home computer, however I think it looks pretty decent if I can get another coroutine to delay the new crystal from appearing. Of course I will also need a sound effect.

---
**29 October 2022**

In preparation for my 1on1 with Chad, I am focusing on the onboarding as well as the core mechanic of capturing the essences from the Crystals and bringing them to the "Synth", the sound synthisizer that the players will be able to use to create their custom meditative "sound mix".

Here is a video capture of how it looks right now:

https://user-images.githubusercontent.com/3580918/198839379-752173ed-4705-4b98-b53a-b8c74cf8b3db.mp4

---

Another update today, which is an important milestone for me! I managed to tie in the world Y position of the volume adjustment sphere which appears after a crystal's essence is absorbed, to the volume of the sound that the synth now has. 

Watch with sound on:

https://user-images.githubusercontent.com/3580918/198848474-26f95f8b-abf5-4a6b-847a-e2260cb925c6.mp4


The player is able to manipulate the sphere's Y to increase or decrease volume, which will be crucial in finding that sweet spot of mixture of sounds, which is the core mechanic mynoise.net is built on:

![mynoise example](https://user-images.githubusercontent.com/3580918/198848524-c7686217-4ef7-4150-97bf-677cb154bebb.png)

---

**31 October 2022**
I have decided to spend today to add 1 more biome before my presentation: The Caverns. It will take a while before it resembles anything immersive, however I feel like I am off to a good start:

![cavern_sneak_peak](https://user-images.githubusercontent.com/3580918/199022846-4e7b8d28-3cef-46df-bc80-164a1b7f3447.png)

---

The atmospheric so far:

https://user-images.githubusercontent.com/3580918/199063442-b3d9adc4-7602-49b8-8d7b-bbf49adff8e0.mp4

---

**1 November 2022**
Historic day, as I was able to find & fix the bug in my SceneManager which prevented progress for the last few days.

The culprit:
![image](https://user-images.githubusercontent.com/3580918/199594598-8191279e-992a-4dae-8764-4967cdb2c122.png)

The missing "!" cost me so many hours, but another good lesson learned on debugging.. 

During the time trying to figure out the SceneManager issue, I was able to do the recording for all of my voice-overs and I also recorded 8 sounds to be used as essences of Illunae crystals. Here are two samples:

Vera explaining the Amaranthine as part of the tutorial:
https://drive.google.com/file/d/1u-rx7nVWFkQY06T-O0oohAQ-sd5QfW5u/view?usp=share_link

An Illunae Essence-Voice that can be captured & used by the player:
(the sound is recorded from www.mynoise.net)
https://drive.google.com/file/d/1JAc07qUsGk_AQm099FQdajjzxDIQ2_8r/view?usp=share_link

I also tested out some different textures for the Illunae crystals and after some thought into performance vs filesize, I decided to go ahead with these 8 for the capstone:

![image](https://user-images.githubusercontent.com/3580918/199597436-806754fd-b732-43cc-a10f-01271b64fb7f.png)

Next steps involve working with the scene transitions, carrying over of crystal and the Amarantine staff across scenes and randomizing essences that can be absorbed in each scene at each visit.

---
**4 Novemnber 2022**
The holster system is carrying over the scenes, however its contents are not. It looks like instead of making children of objects on the holsters, it is using object.transform changes to carry the items and as such unless I find a way to tweak the code it will not work. 

One idea I will try for this challenge is to write code which will instantiate the crystal staff in the other scenes and auto bind it to the holster when the scene loads. 

Yesterday I finished all the crystals and their associated voices, which is now functional. The lighting setting is still not optimized and it is too dark in some parts, therefore I will have to find another way to solve this. My original idea of fireflys lighting up is not working as intended either, it is too "flickery".

![image](https://user-images.githubusercontent.com/3580918/199967240-6b29a6ac-f69d-465b-bc08-49558d30e07b.png)

---
**6 November 2022**
Another challenge is overcome, with special thanks to Steven Clark who helped me with the script for this.
The holster system I had in place unintentionally interacted with grabbable objects in the world when it was within proximity, causing issues.

To fix this problem, the interaction layer mask of the grabbable objects must be changed to "Holster" only when they are grabbed by the players hand controller, and they should revert back to default when they are released back into the world. Now, there are tons of youtube videos out there which show how to play around with the interaction layer mask in the editor, but none that talks about manipulating it through code. 

With Steven's help, the holster system works now as intended:

https://user-images.githubusercontent.com/3580918/200176468-d17cd49c-3c5d-42ab-b514-ac7d5cda7295.mp4

---
**7 November 2022**
OF TRIGGERS AND COLLIDERS

Today I finally bit the bullet and decided to take care of the colliders for the walls as well as the ground so that the player character does not walk through things anymore. I tried the option of adding rigidbodies and colliders, which unfortunately did not work. I would test it out with a generic sphere with a rigidbody, which would not pass through the floor or walls, but applying the same to a capsule collider on the player camera did not do the trick.

After trying for an hour, I gave up and decided to use the character controller component that comes ready. It worked! Well, partially: I was able to traverse on floor which was not level and walls and ground collision worked. However, the moment the Y incresed due to climbing a little hill or any kind of slope, the Y never returned to the ground.

Somehow, even though my project settings -> physics showed the correct gravity setting, with the character controller, it simply did not go down.

I searched the internet for hours for some kind of a "ground grabber" script, tried a couple of physics based character controller assets that came with the bundles I bought but no matter I did, I could not get gravity or collissions work at same time.

After about 4 hours, I gave up and said "OK, looks like we won't have continuous move, we will switch to teleport". I went into the locomotion system and while looking for the teleport provider, this is what I see:

![image](https://user-images.githubusercontent.com/3580918/200450160-6e455d37-1751-4d7c-8b82-2e11c18d4731.png)

Whole time allocated for Unity on Saturday spent because of one tickbox, it is a lesson learned that I will never forget again :)

Now I have a functioning continous move that grabs the floor and works as intended. The change with character controller also meant me changing the way triggers work with some of my colliders, which I should finish by tonight. 

Tomorrow, the tutorial system will finish and I will do the final dreaded part for the MVP: Cross scene object reference management. <shiver>

---
**9 November 2022**
  
The solution for the cross scene object reference management was Scriptable Objects. My challenge was twofold:
  
  1. The triggers I placed for the Tutorial involve a boolean which turn them off after the user triggers them first time. This was done so that Vera would help players with voiceover in events like first time staff pickup or first time a player sings to the Crystal using the staff. However, going to another scene and coming back to the Lobby reset these values and each time the player returned from another biome, tutorial would kick in again.
  
  2. The crystal essences that were absorbed in other scenes did not translate into the lobby for depositing into the sound generator Synth. 
  
To take care of this, I created a scriptable object. 
  
![scriptable objects](https://user-images.githubusercontent.com/3580918/200933797-ce933f37-0398-42fd-93fc-1ce180594713.png)

  
For the issue with tutorial, i now have the bools which flip off after first use and since the scriptable object is at the project level, it does not get affected by switching of the scenes. Once a tutorial step is done, it switched off forever.
  
Similarly for the issue with the crystals not transferring, I now have the bools which I will use to tell the Lobby scene which crystal was absorbed in the last scene and simply setenable that crystal on the staff.
  
Things are looking brighter, but I still have a lot of performance issues I need to solve in next 3 days to have a presentable product.
  
**11 November 2022**
  
Most of the scene management code is done, but a few more errors remain. Another big lesson learned was to keep the tutorial out of the main game, in a different scene, rather than trying to disable all the tutorial aspects after a player uses the portals. 
  
On the other hand, I did finish the trailer for the capstone presentation:  

https://user-images.githubusercontent.com/3580918/201397377-a51b6fbe-7ba3-4805-bb2d-15f3a3457a7f.mp4

I think it captures the essence of what to expect. I could have added a scene where many different crystals are singing and how volumes can be changed, but at this point I do not have enough time.
  
**14 November 2022**

And the last week of this journey is upon us. I finally had a working prototype that I was able to share with friends and got some invaluable feedback. This experience has taught me the importance of following the advice on creating simple, functioning minimum viable product, rather than the path I took to polish everything and try to get user experience "in the end." The feedback has been mostly positive so far and thanks to the live recording of the playtest by Oz, I was able to see my game from someone elses perspective. 
  
Another lesson learned is to keep the tutorial a completely separate scene than the game/lobby. Right now I have tons of switches getting turned on and off on my scriptable object that are tied to the lobby, which get checked every time a scene change happens. With my next project, this will be a one time check for sure.
  
I just finished a UI element for the tutorial, using Synty Prototype assets, which I will incorporate in the game tonight:
  
![tutorial](https://user-images.githubusercontent.com/3580918/201684486-9104d1b6-252f-426e-94e7-69252b52f333.png)
  
Next, I will finish the remaining bugs related to the newly added Cavern scene and by Wednesday 16th I hope to have a full playthru video on youtube.
  
