TexMod

TexMod was originally created by RS as a modding utility for “Tomb Raider 7: Legend” 
back in 2006. It allows to extract textures from DirectX 9 applications, and 
to pack eventually changed textures into TPF files (TexMod Package File) to 
load those back to the application replacing the original textures. 
This allowed players to change the appearance of Lara Croft and other 
characters of the game. TexMod and a lot customizations are still available 
at Tomb Raider HUB.

Years later, players of Guild Wars discovered TexMod and its great functionality, 
and so they started to make their own customizations for Guild Wars. Being to only 
real way to change a player's interface, plus the fact that it was being allowed by 
the developer ArenaNet, it got very popular. Now when searching for TexMod on google, 
the first result is linking to an article about it on the official Guild Wars Wiki.

However as great as the original TexMod is, its development stopped with the actual 
release of it, so this project is an approach to create an open source port of TexMod 
while integrating new features and hopefully a great future compilance 
(regarding DirectX 10 and 11).
Universal Modding Engine (uMod)

Wiki in Englisch ; Wiki in Deutsch

We decided to rename the project (earlier OpenTexMod).

Features:

    modify the game while it is running (activating and deactivating a mod)
    support the original TexMod (*.tpf) Mods
    save textures from the game
    create templates for a easy game start (no need to select all the mods again and again) 

Features of uMod 2:

    mod creator: arrange your texture into groups to extend the usability of your mods
    mod user: activate or deactivate single textures inside a mod and if present also 
    groups and subgroups
    size and format filters if you let uMod save all texture 

You can download uMod V1.0 and uMod V2.0 Alpha. I decided to redesign uMod instead of 
coding the DirectX 10 support, because uMod already works with GW2 ;)

There is also a list of known bugs. If you find a new bug or have more information about
a known bug, please submit or extend an Issue.
Become a member of this project

I need co-workers. Do YOU want to join this project?

requirements:

    English or German
    some basic experience in C++
    skype or TeamSpeak 

what know-how is useful, but definitely not required!

    DirectX 8-11
    dll-injection
    GUI programming 

what can be done or add in future:

    improvement of the code ;)
    support of DirectX 8, 10, and 11
    OnScreenDisplay (configure uMod without minimizing the game)
    modding of meshes
    managing templates without a running game in the background
    starting the game through uMod with a certain template -> shortcuts
    a MapEditor for generating Mods for a game map automatically 
    (e.g. quest/mission marks in a RPG, or tactical points for PVP teams), 
    but this should be outsourced to a new project 
