# Are You Testing Your Detections?


If you answered yes, fantastic! You can go elsewhere. But, if you answered no, you're in trouble. I encourage you to read on.

All jokes aside, this is a topic that can set apart good security teams from great. 

### Building Detections

Before I get into why this can make a good team great, I want to briefly talk about a specialty called <i> Detection Engineering </i>. You've probably heard the term Detection Engineering thrown around or mentioned over the past couple of years and for good reason. As security teams mature, it is important to have dedicated personnel who build and test detections. When I say detections I mean correlation searches, alerts, or even just scheduled queries on a SIEM platform. Really anything that is expected to "detect" the bad guy who is compromising your company.

Detection engineers are generally responsible for staying up to date with the latest TTP's and trends,  incorporating this into detections that are suited for their companies. Detection Engineers are usually found in larger companies that are more mature in their security journey. For companies that do not have dedicated detection engineers, you may see the SOC analysts or the Security Engineering team build detections.

Ultimately, the structure of the security team at your organization does not matter. What really matters is that the folks that are building these detections are taking the next step: testing them.


### Why aren't people testing detections?
1. Resource shortage
2. Rely solely on red team engagements
3. Stubbornness
4. Relatively new topic that isn't talked about as much as other security topics

These are just a few vague reasons why companies aren't taking the next step and testing detections. For starters, it certainly does take time and resources. You can't expect to implement a formalized testing process within a couple of hours. Some may even say it's a big enough effort to turn into a project. When I say stubbornness, I am referring to the fact that folks may think that their detections are perfect and don't need testing. The simple fact is that TTP's change as well as most IOCs, so it is important to ensure you're testing your work with up to date attack simulations. And lastly, this is not a widely talked about topic. This is one of the reasons I'm writing this article, with the hopes of spreading the word.

So, with all of this being said, it is important to test your detections.

I'm sure you're thinking, well, thanks for telling me all of this. What do you expect me to do now?

Fear not... I come with recommendations on how to get started!

### So How Do I Implement This "Testing Process" You Speak Of?

This is where the fun begins. It is going to feel great when you see those detections that you've spent long hours building trigger and notify your team. The confidence and morale is going to grow with your SOC, and you will be able to spend more time building new detections.

1. Find an attack simulation tool

As you begin looking into what type of simulation tool you need, ask yourself some guiding questions like:

- Do I need a free tool or can I get budget for this?
- What type of attacks will I be performing?
- What kind of infrastructure will I host the attack simulation tool on?

These questions will help you narrow down what is best to use.

I personally recommend Atomic Red Team. This is an open source tool with active contributors and is built extremely well.

2. Schedule and plan when to run your attacks

Once you have selected your attack simulation tool, you'll want to run the attack techniques that are covered by your detections. <b> Make sure that you have notified your security department that this will be occuring on X date </b>. This should be a frequent process to keep your detections up to date and fresh. Once they are complete, check to ensure your detections have triggered.

3. Update logic behind alerts

This step is necessary if you find that your detections are not firing. It is important to make sure that the SIEM is not skipping the searches and that it is not the issue.

4. Build more detections and keep testing!

Now that you've tested your detections, it is time to keep building and staying current with the trends. You have implemented a formalized process and have helped mature your security team, time to celebrate! 

I have some great articles that I recommend reading:
