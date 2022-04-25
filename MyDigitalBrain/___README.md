# Setup:
1. . Get your *Calendar* to render in the right sidebar, if it's not visible. To do this, use the *Command Palette* (`CMD+P`), enter 'Calendar', type and select 'Open View.'  You may then need to select it (see image) ![[Pasted image 20220422132543.png]]
	1. *note*: if you don't see that option, you'll first have to close out the plugin windows on the right: ![[Pasted image 20220425081003.png]]
2. Get the **Daily Planner** to render in your right sidebar as well.  Use the *Command Palette* for that as well.
	-  Type and select 'Show the Day Planner Timeline'
	- You can view an example planner in [[Day Planner-EXAMPLE]]
3. Review hotkeys (mac) but the four I use all the time are:
	- *Command Palette*: `CMD+P`  
	- *Insert from template*: `CMD+T`
	- *Insert from **Templater** template*: `CMD+SHFT+T`
		- This is the one you want, as the `_Auto Template`  requires **Templater**.  More on this later
	- *Add/Edit Task*: `CTRL+T`
	- *Toggle View/Edit mode*: `CMD+E`
		- I generally use 'Live View Preview' mode, but sometimes it gets annoying, and I'll need to toggle between Edit and View modes
	- *Settings*: `CMD+,`
		- Listing this just in case it blows someone's mind ;) 
	- *Forward/Back*: `CMD+[`, `CMD+]`, respectively

---

# Current Implementation:
(All of this should be setup because you're using this vault as a template, but this is how it's wired up)
##### For any additional information about these plugins, in Settings, you can access each of their GitHub pages and additional documentation.
- **Calendar** is on
- **Daily Notes** use the `Templates/Daily Template`
- **Daily Planner** is linked to from each daily note.
	- *note:* The Daily Planner does not use templates, but there is a template available in `Templates/Daily Planner`
- **Data View** is being used by **Daily Notes** (in the `Daily Template` under [[Daily Template#Habit Tracker]])
- **Tasks** is used *all* over the place, like almost everywhere.
- **Advanced Tables** for a better Markdown table experience
- **Templater** allows some of the dynamic dates in `Daily Template` to render properly

---

# My Current Daily [*Life + Work Note*] Workflow:
As mentioned above, I use **Tasks** as my bread and butter for my **Daily Notes**.  All *Objectives*, *Followups*, and *Task* lists leverage **Tasks** querying language.
### AM
1. Create a new daily template (by clicking on the day in the calendar sidebar)
2. Create my [[Daily Template#Schedule]] for the day
3. Review [[Daily Template#Deadlines]] and [[Daily Template#Tasks]] 
	1. *note:*  [[Daily Template#Deadlines]] require a *due date*, so until you have a task with a *due date* (`CTRL+T`) you're not going to see anything rendered here.
4. Choose my [[Daily Template#Daily Focus]] items
5. Create my Habits file for the day [[Daily Template#Habit Tracker]] by clicking the generated link.
	1. Once in the file, simply use the **Templater** hotkey (`CMD+SHFT+T`) to insert the `_Auto Template` which will insert the [[Daily Habits]] Template and move it into the `Daily Habits` folder (which is required for the **DataView** query to pick it up).
6. During the day, fill out both *work* and *personal* tasks, utilize meeting notes, closeout tasks, etc.
	- I will forward-date things in [[2022 Work Meeting Notes]] under a heading (## YYYY MM DD) for upcoming meetings so I can have talking points ready
### PM
1. If I didn't do #5 from above, do that first.
2. Review [[Daily Template#Deadlines]] and [[Daily Template#Tasks]]  and make sure everything I accomplished got crossed out.
3. Fill out my daily [[Daily Template#Reflection]]
4. If necessary or inspired, create tomorrow's daily note (by clicking on the day in the calendar sidebar) to make sure I don't miss something that's currently on my mind
	1. *note:* This can be done at **any time** for *any* day, so if you need to create a reminder for a particular future day, you can create a note for that day and fill out whatever is top of mind.  However, double-check the dates, they may need some help depending on how it renders.

--- 

# My Current Note-Taking Workflow:
This is *very* much a WIP (outside of the Meeting Notes mentioned Above [[___README#AM]] #6), so read the following as my *intentions*/the beginnings of my system.  If you have a better system, please share!
1. I use `__Inbox` for new note fragments and incoming ideas that need to be worked on (or are *being* worked on). 
2. There's a bit of **Templater** madness that I've orchestrated to make this a bit easier. But the TL;DR here is that if you follow this naming key: [[Templater Automation Key]] and then use the **Templater** hotkey mentioned above to apply the `_Auto Template` the note will get moved to the `__Inbox` and get the correct template applied to it.
	1. To read a little more about my *Tags* and *Status'* go here: [[Inbox Note Tag Taxonomy]]
---

# Inspiration/resources:
1. [How it started](https://www.reddit.com/r/ObsidianMD/comments/sfq78s/unpopular_opinion_obsidian_is_an_excellent_task/)
2. [What blew my brain and convinced me to *USE* Obsidian](https://www.youtube.com/watch?v=zIh1S7ra3aI)
3. [Kinda covers Daily Notes & Daily Planner](https://www.youtube.com/watch?v=hxf3_dXIcqc)
4.  [Some Daily Planner Info](https://www.youtube.com/watch?v=4j4hG_0AoWs)
7. [Data View](https://www.youtube.com/watch?v=7kFEl7Ovsr8)
8. [*DEEP* Dive on Zettlekasten workflow & Obsidian](https://www.youtube.com/watch?v=wB89lJs5A3s)
9. [Zettlekasten is wat?](https://www.youtube.com/watch?v=rOSZOCoqOo80)
10. [Evergreen Notes?](https://notes.andymatuschak.org/Evergreen_notes)
11. [Evergreen Notes (via Roam)](https://maggieappleton.com/roam-garden)
12. [More Evergreen shit, because I'm still trying to figure it out entirely](https://www.youtube.com/watch?v=9_F5MC2pthk)
13. [On building habits](https://hubermanlab.com/the-science-of-making-and-breaking-habits/)