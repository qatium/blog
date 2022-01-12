

If you only want the highlights here they are:

* It's about to develop incrementally
* The challenge is to find the right increments
* Separate problems from solution
* Value is what we want
* There is always more than one way to get there
* Use it to guide the implementation
* Reduce the scope doing engineering
* An increment implementation without quality is a spike
* Don't release each slice

if you want to know a bit more, continue reading.


# Why?

Develop is a researching process and vertical slicing provides us with a mechanic to apply the scientific model to this process. We make hypothesis and get fast feedback to validate or reject them. Additionally, through the development of narrow slices we can provide value sooner and react to changes or error faster. 

We start digging onto this topic because we think we can improve our delivery rate narrowing the scope of our user stories.

# How?

To start learning about this topic we followed the guide wrote by Abraham Vallez [1](https://abrahamvallez.medium.com/vertical-slicing-i-desaprende-lo-que-sabes-sobre-user-stories-y-pon-el-foco-en-desarrollo-b859c5827326). It's very recommendable and not only because it is easy to read and to understand, but as well because it's full of references where you can learn much more. Before starting, you should try to forget anything you know about other techniques and focus on what Abraham tells. There will be time to look for similitude and contradictions, but if you don't want to spend the reading fighting with you preconceived ideas I totally recommend you start with a fresh mindset.

I think I am not spoiling the party if I advance you some of the main ideas I have gotten from these readings:

**An increment provides value if it gives us feedback to reach our final goals**
As Ron Jeffriess explain in "The Nature of Software Development" [2](https://pragprog.com/titles/rjnsd/the-nature-of-software-development/) value is what we want, what matters to us, and it isn't only one thing. Usually there are a bunch of things that are important for the team and feedback is one of them. If the output of the slice is real software working whose outcome is any kind of information we can consider that the increment is good enough.

**Separate the problem space from the solution space**
When it comes to decompose a problem into activities, complexities, and variations it's essential to keep separated the problem from the solution. We developers accustomed to run towards the solution mixing everything and narrowing the spectrum of results that we can offer. In that process the simplest solutions used to vanish.

**Apply different levels of abstraction to different areas**
Vertical slicing is an iterative process. We start with a slice of the problem, and then we start developing a solution using vertical slicing. As we mentioned before these are two different arenas, and we need different mindsets to work in each of them. 

**The right size for a slice is that that provides feedback**
No more, no less. Usually the difficulty isn't to find something extra to add, we are very good on that, but we need to remove the irrelevant keeping the essential to get the feedback we require.

# Lessons learned

## There is always more than one way to get there
We repeated the exercise different days with different people. The slices were always different. To slice a problem is a kind of art. It takes time and practice to develop some skills to master this technique. The good thing was that none of the results was wrong. Furthermore, they were different in shape, but with a very similar intention and therefore a very similar result. 

Fortunately, there are some strategies to help us with it, for example SPIDR[3](https://www.autentia.com/en/2018/07/23/spidr-una-tecnica-para-dividir-tus-historias-de-usuario/) offer us a framework to get some ideas about how to slice our problem.


## Use it to guide the implementation
Vertical slicing is not only about dividing the problem's space. It is about to guide the solution. We should implement small slices that give us quick feedback and allow us to move faster. It is tempting to split the user story once we have worked it out after a vertical slicing session. Front-end and back-end or React components and domain or Database model and whatever else you have. Although this approach works, it is easy to lose the big picture and get lost on technical details spoiling our initial intention of getting fast feedback through the simpler solution. 

I remember a road that will communicate Portada Alta with Malaga's University, they started building the road by both ends hoping to meet in the middle. However, when they reach the planned point both roads didn't match they had to create an impossible curve to communicate both roads. If that happens in an industry with years of experience, procedures, techniques and backed by physic and math it isn't difficult to see why it isn't  the best approach for us.

## Reduce the scope doing engineering
We can't reduce the value. We have chosen an increment that produces the value we are looking for, but we can reduce the technical scope. Applying engineering, thinking more and coding less, producing the same outcome with less output. This doesn't mean reduce the quality as we will see below. 

"Build what you must, buy what you can, and write it all down" ([4](https://increment.com/teams/code-less-engineer-more/?utm_medium=earned-email&utm_source=de19&utm_campaign=GLOBAL_4df5&utm_content=89c8&utm_term=da67f7d830ef&mkt_tok=MDcyLU1ESy0yODMAAAGBY3xK51VQT3urZs9rScedbX7GsjQ0lJOG6bCq6CxfZln2_jTwHpM5dYMuL-0wwZjVRjrf273PcYC2SPvRSfgaaZ40qN0agU6NaXvX0FaNrvbTca8))

## An increment implementation without quality is a spike
To make vertical slicing works we must keep our code in good shape. If we are only concerned about fast delivery, sooner than later we will start running into our own code. The only way we can achieve its promise is finding a balance among technical excellence, simplicity and feasible solutions. How to get that balance is a topic for other post, but meanwhile, if you need help, take a look to XP.

## Don't release each slice
Not every increment has to be releasable. Independently if you are doing CD or not, or what is your branching strategy you have mechanism to hide these increments at the same time you still can get feedback. Feature flags are a good tool on this regard, but you have others. The most important thing is to understand that every increment should not constitute a release, keep it in mind when you start practicing this.


# Conclusion
As a product team our duty is to deliver value as soon as possible through a simple and high quality solution. Vertical slicing help us on getting the former, but is impossible without having the latter. 
