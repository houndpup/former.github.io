# Are You Testing Your Detections?


If you answered yes, fantastic! You can go elsewhere. But, if you answered no, you're in trouble. I encourage you to read on.

All jokes aside, this is a topic that can set apart good security teams from great. 

### Building Detections

Before I get into why this can make a good team great, I want to briefly talk about a specialty called Detection Engineering. You've probably heard the term Detection Engineering thrown around or mentioned over the past couple of years and for good reason. As security teams mature, it is important to have dedicated personnel who build and test detections. When I say detections I mean correlation searches, alerts, or even just scheduled queries on a SIEM platform. Really anything that is expected to "detect" the bad guy who is compromising your company.

Detection engineers are generally responsible for staying up to date with the latest TTP's and trends,  incorporating this into detections that are suited for their companies. Detection Engineers are usually found in larger companies that are more mature in their security journey. For companies that do not have dedicated detection engineers, you may see the SOC analysts or the Security Engineering team build detections.

### Good News
The good news is, at the end of the day it does not matter the structure of the security team or even if the role of detection engineering exists at your company. What really matters is that the folks that are building these detections are taking the next step: testing them.


### Why aren't people testing detections?
Resource shortage
Stubbornness
Relatively new topic that isn't talked about as much as other security topics

These are just generalized reasons that companies aren't testing detections. For starters, it takes time and resources. You likely can't implement a formalized testing process within a couple of hours. This is likely a big enough effort to deem a project. Some folks may think that their detections are perfect and don't need testing. The simple fact that TTP's change as well as most IOCs so it is important to ensure you're testing your work. And lastly, this is not a widely talked about topic. This is one of the reasons I'm writing this article, with the hopes of spreading the word.


So, with all of this being said, it is important to test your detections.

I'm sure you're thinking, well, thanks for telling me this. What do you expect me to do now?

Fear not... I come with recommendations on how to get started!

###Implementing a Testing Process
