# Why I wish I knew Bayes Theorem before my surgery

> And how you may benefit from knowing it**

**Bayes theorem** — The confusing relation you may vaguely remember from high school probability class that made you think, *“When am I going to use any of this in real life?”*

This blog post is my about my painful and confusing medical journey to fix my breathing difficulties, and finally finding answers to bothering questions, thanks to a simple but powerful math equation.

To tell you that, I must tell you how I developed a breathing problem at the first place, what I did to try and fix it, and finally how that simple math equation *could have* helped me decide better.

So let’s begin with a quick rewind to the year 2017, a year when I was rocking in my first job after college as a project manager at Cisco Systems, having learned business-level french in 6 months and achieved a promotion after my very first year.

Despite my professional successes, my health was declining, as the city I was living in, Bangalore, usually known as the **city of rivers**, saw a record increase in pollution, warming and water contamination. Such a worsening state of the city had a negative effect on me, as simple jogs around my neighbourhood left me with a perpetually stuffed nose and frequent breathing difficulties leading to headaches and sleepless nights.

All this took a turn for the worse at the end of the year, as I woke up one Sunday morning, not being able to breathe at all\! But the worst was yet to come, as a routine visit to the emergency room at a nearby hospital, became the start of a nightmare when instead of my regular nasal spray prescriptions, the emergency physician suggested that I should consider a nasal correction surgery to aide my breathing.

At the time, this seemed like the **holy grail** solution, and as a bachelor of engineering, it made complete sense to me\! 

*If the nasal canal is choked, why not just steam roll through it and make space for air?*

So with that idea, as my company prepared for an end of year shutdown in December, I met the first Otolaryngologist I could find and described to him my troubles. We quickly agreed upon the said surgical intervention (called Septoplasty)

As a part of my *research, a* quick search on realself.com suggested that **91%** of those operated upon, approved the surgery, which was quite impressive.  
So within two days, I was in a hospital gown, ready for surgery\! 

At that time, it fit perfectly. A surgery with a recovery time for 5 days, and I’d be all set to go back to Bangalore and rock 2018\!

20/20 hindsight, has me wondering how the hell did a take it so lightly?

**Post Surgery**

The surgery, apparently, was a success (in the words of the doctor, obviously), but I had a huge stuffing in my nose, which made it difficult for me to make any judgement.   
I spent the next two days breathing from my mouth, and finally after painfully waiting for what seemed like a decade, my nose was cleared and ready to pump air\!

But, like the returns promised on the next *hotshot stock* I didn’t feel like I gained anything at all. My questions and concerns were politely ignored, and the doctor said it usually takes about 4 weeks for full breathing function to resume.   
Okay No Problem\!   
And just like that, four weeks of the new year passed away, but with my optimism waning with each passing day.   
The response by my surgeon remained the same. “It takes time”, and after some time, I stopped getting any responses from him.

So I waited, but my symptoms exacerbated. I can’t explain what happened, but I felt unusually fatigued, more breathless and with a general sense of malaise.

The trouble turned on its head in late February, as I just couldn’t sleep anymore. Google searches ended up being a rabbit hole, as I found **a good number** of people expressing similar issues, with no respite. The subjective responses ranged from hopelessness to anger, but with no directive to improve the situation.

Frankly speaking, one night, I broke down, but when I *tried* to cry, the tears made my breathless, and I couldn’t even cry anymore, and that’s when I lost it\!  
Something was wrong, and with not much changed in my life recently, it had to be the medical intervention, and I had to figure out how I could fix it.

So, I spent the next three months, meeting all sorts of doctors, with an honest attempt to find answers, but the trend appeared as though a doctor with a particular speciality, somehow diagnosed me with something he was specialised in\! (Kind of like the doctor’s edition of *if you have a hammer, everything seems like a nail.)*

I felt I was walking on the edge of ambiguity among medics, and I didn’t want to be the *life is so cruel* guy. I just wanted to breathe well and be happy, and not stress about the newly welcomed misery of my life (which was reminded to me with every breath)

So after months of medical consults, self study and pure frustration, I put aside my *search for answers* and spent the remaining part of the year, and the years ahead, in doing whatever I could, to take my mind off this issue.

That search for a *distraction* somehow resulted in an increased interest in mathematics of data science. In sifting through those concepts, I came across a simple concept all the way from high school, but which underpins major principles in machine learning, **Bayes Theorem.**  
In the most unusual case of “finding your destiny on the path to avoid it”, this little rule ended up giving me some answers to my enduring questions.

## Bayes Theorem

Before I tell you how I got the answers, it warrants to give you a quick recap of what exactly Bayes Theorem talks about.  
But the story of Bayes Theorem pivots on something called **conditional probability**, so here’s a quick definition of conditional probability.

Definition of conditional

Shuffle it up a bit

Time for Mr Bayes

Simple, but effective

If these concepts are unclear, I suggest you read this excellent blog post by Harvard professor Rahul Dave whose passion for Bayesian Statistics rekindle my interest in this was kind enough to drill it in my head through his interesting case studies.

## Hindsight 2020 but foresight blind?

Now, powered with Bayes theorem, let’s fast forward to the night of 10th June 2020, the night I was ready to tackle the question from three years ago. 

*“If 91% of people were happy with the surgery, how come I landed in the wretched 9%? Why me\!”*

Time to employ conditional probability and Bayes theorem.

First, let’s take 100 people, who were operated on.   
We assume that here that the realself website somehow approximates the actual distribution of responses, to make our analysis easy to follow.

91 out of 100 were happy with the outcome of the surgery, 9 were not.

Now, a detail not mentioned before, was that out of the several medics I visited, one was a pulmonologist, who magically concluded I was asthmatic (although I had no discernible history of asthma before the operation, and I was an active sportsperson all my life)

He based his theory on an IgG test, which showed values that were ten times normal. This test is a sign of a heavy allergic reaction in the body, but the test cannot determine what causes the allergy.

The asthma was a stretch, but it was clear that I had significant allergies.  
It became clear that many people with symptoms like my own are regular candidates for Septoplasty, for similar breathing difficulties like my own.

The other common class of people opting for Septoplasty are those with significant nasal deviations, leading to breathe difficulties.  
This is surprisingly not uncommon for people of the Indian subcontinent, with doctors claiming that 90% of the people have some form of deviation. (Check yourself in the mirror, your nose may be crooked too)

So we have an additional category of people not considered earlier, i.e. people with allergies, and people with deviations.

To simplify the argument, let’s term people with deviations as those not having allergies, and so post-surgery, we have four categories, i.e. combinations of Unhappy/Happy, and Allergic/Not Allergic

So the million dollar question now shaped up as, 

*Given that I was allergic, what are my odds of being happy with the operation?*

which is a much more relevant question to me than the general,

*What are my odds of being happy with the operation? *

Some math here

and here

So the odds of a **happy** outcome, given I was allergic was just about **50%** \!\!\!

Now, I underscore that several assumptions were made in the lead up to this figure, which ought to be well researched and studied further.

However, without doubt, the figure reveals how misleading the original conclusion of 91% happiness was.

At **91%** it seems a sure bargain and a no-brainer to undergo surgery. Odds look really good.

But at roughly 50%?

Would I be willing to risk a medical intervention, on a sensory receptor that is responsible for a breath every other second, on just about **50%** chance of satisfaction\!?\! Will I place my odds of medical misery on a flip of a coin? Absolutely not\!

If I had such information, I’d rather be compelled to try every other possible non-invasive remedy, from yoga to a trip to the Himalayas, before taking such a leap of faith, and gamble on life-long repercussions. 

### Parting thoughts

Obviously hindsight is 2020, but Bayes theorem gives solid lessons for the future as well, which is:  
*Unconditional* probability figures and statistics such as surgery success rates, or mortality rates of infections, are all a facade, and mask too much information to be of serious use.   
It’s essential to at least try to make some ***conditional*** estimates, and carefully examine how the odds change for your specific condition **before** you take a decision.

So next time, before you consider a hair transplant, botox or lasik, and feel empowered by the stats on some website like realself.com, think again,   
*“Does it apply to me?”* and if you don’t have the answers, call a friend who scored an A grade in Stats 101 before you make a decision.

For more news and views, stay tuned to GenSecTimes.
