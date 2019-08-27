## Create your own Bot with vTask! 
vTask is a program which allows you to create scripts to automate your work with Windows. The biggest advantage of vTask is how easy it is to use even with zero knowledge about programing. The only thing you need to know is what exactly your script is supposed to do. 

## Patterns
A project related to gaming brings additional fun and thus makes it easier and faster to learn about new technologies, than by doing some typical copy paste project (at least this is the case for me). Having this in mind I have thought about changing typical range of program function and make something that could be used in gaming. The only title in which I could find nice a pattern of redoing one and the same action was a mobile game that I have played some time. To ensure that no one related to this game’s community is going to use this project for cheating in said game, I'm going to call it here "X". 

"X" is a typical example of a Gacha type game. As a player, your job is to make your team stronger by “leveling” your monsters that you acquire from gatcha, as well as put "runes" on them. Runes can be obtain by running instances. With knowledge about pattern that makes up a whole single run you can create a block diagram of every possibility. The possibilities here being winning, losing or obtaining different items. In case of game "X" I wanted to create a script which can automate the process of running one instance up to the moment of running dry on energy. Block Diagram of patterns should look like this:

<img align="center" src="https://github.com/Nersian/Mobile_BOT/blob/master/readme_img/Game_Diagram.png?raw=true" width="800">

## "Coding" 
As I said earlier vTask doesn't required coding skill. By dragging "Action" to your script and adjusting it's parameters, it's easy to build a functional program especially with a hand drawn diagram. Making it beforehand surely will shorten the time of making your code. With a trial and error method, element after an element you can adjust your script in order to correct any newly found problem, such as time delay between the subsequent images, finding golden value of image required match parameters, or changing the search field in order to make your program run more smoothly. Additionally you can add variables to your script in order to increase the data about your Winning/Loses Ratio.
<img src="https://github.com/Nersian/Mobile_BOT/blob/master/readme_img/vTask_Interface.PNG?raw=true">

## Phone mirroring 
Of course using screen mirroring is not necessary, there are plenty of other ways to access games like running Android emulators, such as nox or Bluestack. In this case I have decided to use screen mirroring program called Mobizen. This decision was motivated by its low RAM requirements, which is a good thing on lower spec PC. Connecting your phone with mobizen is quite easy. To do so, you can use your USB cable or connect your phone to the same Wi-Fi as your PC that is running the script. The only thing you need to do, is to launch your app and click one button to automate farming process. 

## Note 
This project was made only for Academic purpose. Private usage of this program can lead to deleting users accounts due to violations of terms of use. Overall it is a fun project to make, one that allows you to find bugs and improve your code through gaming. However once again, usage of bots such as this one is strictly prohibited, for most of the games.
