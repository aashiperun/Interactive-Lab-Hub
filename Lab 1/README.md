

# Staging Interaction

In the original stage production of Peter Pan, Tinker Bell was represented by a darting light created by a small handheld mirror off-stage, reflecting a little circle of light from a powerful lamp. Tinkerbell communicates her presence through this light to the other characters. See more info [here](https://en.wikipedia.org/wiki/Tinker_Bell). 

There is no actor that plays Tinkerbell--her existence in the play comes from the interactions that the other characters have with her.

For lab this week, we draw on this and other inspirations from theatre to stage interactions with a device where the main mode of display/output for the interactive device you are designing is lighting. You will plot the interaction with a storyboard, and use your computer and a smartphone to experiment with what the interactions will look and feel like. 

_Make sure you read all the instructions and understand the whole of the laboratory activity before starting!_



## Prep

### To start the semester, you will need:
1. Set up your own Github "Lab Hub" repository to keep all you work in record by [following these instructions](https://github.com/FAR-Lab/Developing-and-Designing-Interactive-Devices/blob/2021Fall/readings/Submitting%20Labs.md).
2. Set up the README.md for your Hub repository (for instance, so that it has your name and points to your own Lab 1) and [learn how to](https://guides.github.com/features/mastering-markdown/) organize and post links to your submissions on your README.md so we can find them easily.
3. (extra: Learn about what exactly Git is from [here](https://git-scm.com/book/en/v2/Getting-Started-What-is-Git%3F).)

### For this lab, you will need:
1. Paper
2. Markers/ Pens
3. Scissors
4. Smart Phone -- The main required feature is that the phone needs to have a browser and display a webpage.
5. Computer -- We will use your computer to host a webpage which also features controls.
6. Found objects and materials -- You will have to costume your phone so that it looks like some other devices. These materials can include doll clothes, a paper lantern, a bottle, human clothes, a pillow case, etc. Be creative!

### Deliverables for this lab are: 
1. Storyboard
1. Sketches/photos of costumed device
1. Any reflections you have on the process
1. Video sketch of the prototyped interaction
1. Submit the items above in the lab1 folder of your class [Github page], either as links or uploaded files. Each group member should post their own copy of the work to their own Lab Hub, even if some of the work is the same from each person in the group.

### The Report
This README.md page in your own repository should be edited to include the work you have done (the deliverables mentioned above). Following the format below, you can delete everything but the headers and the sections between the **stars**. Write the answers to the questions under the starred sentences. Include any material that explains what you did in this lab hub folder, and link it in your README.md for the lab.

## Lab Overview
For this assignment, you are going to:

A) [Plan](#part-a-plan) 

B) [Act out the interaction](#part-b-act-out-the-interaction) 

C) [Prototype the device](#part-c-prototype-the-device)

D) [Wizard the device](#part-d-wizard-the-device) 

E) [Costume the device](#part-e-costume-the-device)

F) [Record the interaction](#part-f-record)

Labs are due on Mondays. Make sure this page is linked to on your main class hub page.

## Part A. Plan 

To stage the interaction with your interactive device, think about:

_Setting:_ Where is this interaction happening? (e.g., a jungle, the kitchen) When is it happening?

_Players:_ Who is involved in the interaction? Who else is there? If you reflect on the design of current day interactive devices like the Amazon Alexa, it’s clear they didn’t take into account people who had roommates, or the presence of children. Think through all the people who are in the setting.

_Activity:_ What is happening between the actors?

_Goals:_ What are the goals of each player? (e.g., jumping to a tree, opening the fridge). 

The interactive device can be anything *except* a computer, a tablet computer or a smart phone, but the main way it interacts needs to be using light.

\*\***Describe your setting, players, activity and goals here.**\*\*

The Interactive Device I am building is a Smart Toothbrush.

<img width="614" alt="image" src="https://user-images.githubusercontent.com/66789469/187313719-806dd0e2-6997-4658-bb7e-613fe86dd6f8.png">

Sketch a storyboard of the interactions you are planning. It does not need to be perfect, but must get across the behavior of the interactive device and the other characters in the scene. 

\*\***Include a picture of your storyboard here**\*\*

![Untitled (3)](https://user-images.githubusercontent.com/66789469/187329394-eb5cf28b-f71e-4a68-93ea-68f77732358b.jpg)

Present your idea to the other people in your breakout room. You can just get feedback from one another or you can work together on the other parts of the lab.

\*\***Summarize feedback you got here.**\*\*

1) The user might find it frustrating while waiting for the light color to change. 
2) Can the light provide any other information other than just acting as a timer?

## Part B. Act out the Interaction

Try physically acting out the interaction you planned. For now, you can just pretend the device is doing the things you’ve scripted for it. 

\*\***Are there things that seemed better on paper than acted out?**\*\*

* Looking at the same color for one minute felt like a dull process, since the light was telling me nothing other than the time duration I was brushing for.
* The anticipation of the light changing made me feel like it was longer than a minute.
* I would like to convey more information to the user through the light to keep the user engaged.

\*\***Are there new ideas that occur to you or your collaborators that come up from the acting?**\*\*

New Idea : 
* Breakdown the steps of Brushing into the following steps:

   * Step 1: Brush the Outer Surface of the Upper Teeth.
   * Step 2: Brush the Outer Surface of the Lower Teeth.
   * Step 3: Brush the Biting Surface of the Upper Teeth.
   * Step 4: Brush the Biting Surface of the Lower Teeth.
   * Step 5: Brush the Inner Surface of the Upper Teeth.
   * Step 6: Brush the Inner Surface of the Lower Teeth.

* Since there are six steps and the recommended duration for brushing your teeth is 2 minutes. I am diving all the steps into equal durations of time.
Each Step will be done for 20 seconds.

* I am going to allocate colors for each step. Everytime the toothbrush changes its color, the user will perform the step associated with it.

    <img width="257" alt="image" src="https://user-images.githubusercontent.com/66789469/187323964-ffdbfa2c-6fe7-4666-946f-b2eaaf2c6d30.png">

* Storyboard for New Idea:

    ![Untitled (4)](https://user-images.githubusercontent.com/66789469/187329303-52d8a817-432d-44bf-a6ab-f242253f4703.jpg)

## Part C. Prototype the device

You will be using your smartphone as a stand-in for the device you are prototyping. You will use the browser of your smart phone to act as a “light” and use a remote control interface to remotely change the light on that device. 

Code for the "Tinkerbelle" tool, and instructions for setting up the server and your phone are [here](https://github.com/FAR-Lab/tinkerbelle).

We invented this tool for this lab! 

If you run into technical issues with this tool, you can also use a light switch, dimmer, etc. that you can can manually or remotely control.

\*\***Give us feedback on Tinkerbelle.**\*\*
I did face an issue while trying to install the requirements.txt

Fix: Changed Gevent version to v21.12.0 and greenlet to >= 1.1.0 in the requirements.txt file.

## Part D. Wizard the device
Take a little time to set up the wizarding set-up that allows for someone to remotely control the device while someone acts with it. Hint: You can use Zoom to record videos, and you can pin someone’s video feed if that is the scene which you want to record. 

\*\***Include your first attempts at recording the set-up video here.**\*\*

https://drive.google.com/file/d/1nMv6Hhr5GmIExjmIS7vnezWTVvrR-sSS/view?usp=sharing

Now, hange the goal within the same setting, and update the interaction with the paper prototype. 

\*\***Show the follow-up work here.**\*\*

* While trying the set-up for the first time, I had to constantly look down at the phone screen to see the color, which was inconvinient. 
* To make the device more user-friendly, I am adding the color indicating light on the toothbrush as shown below.
    * <img width="217" alt="Screen Shot 2022-08-30 at 12 56 56 AM" src="https://user-images.githubusercontent.com/66789469/187352643-b957e54b-0bcc-4e32-a6fb-67a31bbbc7c4.png">

## Part E. Costume the device

Only now should you start worrying about what the device should look like. Develop a costume so that you can use your phone as this device.

Think about the setting of the device: is the environment a place where the device could overheat? Is water a danger? Does it need to have bright colors in an emergency setting?

\*\***Include sketches of what your device might look like here.**\*\*

\*\***What concerns or opportunitities are influencing the way you've designed the device to look?**\*\*


## Part F. Record

\*\***Take a video of your prototyped interaction.**\*\*

https://drive.google.com/file/d/1nUVVzPG4UXP5E_6qMvV0WUXcOatT7RGS/view?usp=sharing

\*\***Please indicate anyone you collaborated with on this Lab.**\*\*
Be generous in acknowledging their contributions! And also recognizing any other influences (e.g. from YouTube, Github, Twitter) that informed your design. 



# Staging Interaction, Part 2 

This describes the second week's work for this lab activity.


## Prep (to be done before Lab on Wednesday)

You will be assigned three partners from another group. Go to their github pages, view their videos, and provide them with reactions, suggestions & feedback: explain to them what you saw happening in their video. Guess the scene and the goals of the character. Ask them about anything that wasn’t clear. 

\*\***Summarize feedback from your partners here.**\*\*

## Make it your own

Do last week’s assignment again, but this time: 
1) It doesn’t have to (just) use light, 
2) You can use any modality (e.g., vibration, sound) to prototype the behaviors! Again, be creative!
3) We will be grading with an emphasis on creativity. 

\*\***Document everything here. (Particularly, we would like to see the storyboard and video, although photos of the prototype are also great.)**\*\*
