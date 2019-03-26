# CommuniTii
###### Winner of the 2018 CUNY Hackathon! 🏆
[Presentation](https://docs.google.com/presentation/d/16eJTBsVmZdMHJJguk9gx2YX0HiETtyadsiMUyb7c2ik/edit?usp=sharing)

### What is CommuniTii?
#### The Problem

In today's society, we find ourselves increasingly isolated by the use of conventional social media platforms. Social media has taken the "social" aspect out of the equation. Not to mention, our privacy is constantly being put at risk.

#### The Solution

CommuniTii is an open platform that encourages people to socialize in-person through the use of gamification. The platform  pairs people with similar interests through the use of AI, Artificial Intelligence. It uses existing infrastructure to leverage social engagement. 

As of right now, our targeted partner market includes both non-profits and programs like SYEP (Summer Youth Employment Program). This is since there are an abundance of volunteering opportunities for non-profits and thousands of students that weren't accepted into the program. Our platform matches these students with positions that are closely related to their interests. Not only does this help non-profits, but it also helps students for it gives them valuable experience which they can cash in when career hunting. 

All of this while keeping your data secure through implementing new and improved privacy safeguards. One safeguard in particular is the ability to add friends solely through the use of QR codes. Users scan each other's QR code to add each other on the network. Not only does this help preserve their anonymity, but it also encourages actual attendance and active participation in any given event.

### Key Components
#### Quest
The user is greeted with this screen that's populated with recommended activities they might be interested in.

![Quest Page Screen](https://i.imgur.com/Rp315js.png)

#### Chat
A list of open chats with other users.

![Chat Page Screen](https://i.imgur.com/Fq3FnVJ.png)
#### Profile
Information regarding the current user. Includes badges earned and a history of previous activities, also known as quests.

![Profile Page Screen](https://i.imgur.com/OMnMf6z.png)


## Development

### Install Instruction
Make sure to install `yarn`, `lerna` and `exp` globally

```
npm i -g exp yarn lerna
```

Clone the repository and then go into the project root and change nvm version using `nvm use`. Then run `yarn i`. It will install all the dependencies.

To run the mobile app, `cd` into `apps/mobile` and run
```
yarn start
```
### Vscode Extensions
* Eslint
* Prettier Code Formatter
* Editorconfig for Vscode
