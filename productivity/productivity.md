#  Engineering Productivity
<!-- .slide: data-background="images/light-bulb-1246043_1920.jpg" -->
Note: Good Evening. I am incredibly excited to be here. This is my first time in Mountain View, my
first time at Atlassian, and my very first public presentation!


![WeWork](images/WeWork_logo_transparent-white.png)<!-- .element style="background: transparent;" -->
Note: This presentation is proudly sponsored by WeWork. Which is to say they payed for my flight and
food and hotel or at least they will as soon as I submit my expense report. I am the Engineering
Manager for the Test Infrastructure team and I have been there for a little over are year and I am
having a lot of fun.


## First a Little Context
<!-- .slide: data-background="images/self.png" -->
Note: Today I am going to talking about the cultural aspects of Engineering productivity. I think
this problem is incredibly interesting because it is as much about culture as it is about tooling.
There is no silver bullet that will maximize the productivity of every engineer, but, there are an
awful lot of lead ones. Let me start with a little context so you understand where I am coming from.


## An Agile Introduction
![Menlo Innovations](images/menlo_logo.png)

& <!-- .element style="font-size: 60px" -->

![Compendia Bioscience](images/compendia_logo.jpeg) <!-- .element style="width: 28%" -->

Note:  The first two companies I worked at placed a high value of the long term productivity of
their Engineers, and long term productivity means a lot of things. There are the obvious things like
good tooling and good CI, but there are some less obvious and more pervasive things like good code.
Both of these companies used SCRUM and XP. They did pair programming, weekly demos to the customer,
literal TDD, and a lot of other good practices, and the outcome of this, was that in my two years
working at these companies I never saw a bug. We would just spend six hours a day hands on keyboard
cranking out new features, then we would go home, rest easy, and come in and do it again.


## A~~n SDET~~ Productivity Engineer is Born

Note: From these two companies I moved on to my next company where I was initially hired as an SDET
or Software Developer Engineer in Test, and I did not know what that meant, so I asked, "What is my
job?", and they said, "Your job is to triage the bugs and pick which bugs we are not going to fix.",
and this idea sounded absolutely ludicrous to me. They were paying the engineer to make the bugs,
they were paying me to sort the bugs, and they they mostly done away with but one of my
responsibilities was to figure out which bugs to fix and which bug we were not going to fix. It was
a concept I was wholly unfamiliar with and it seemed pretty ridiculous to me.


## The Long-Term Cost of Short-Termism
<!-- .slide: class="contrast-bg" data-background="images/hard_for_devs.png" -->
* Every change gets more complicated
* Hard to onboard new developers
* Changes require intense manual work
* Increased time in unplanned work
Note: This transition was basically the radioactive spider bite or that got me interested in
developer productivity. This process externalized quality from the developer and lead to a lot of
time spent parsing logs, talking to customers, and reading through untested, undocumented code that
they either never touched or have not touched in months. These are a bunch things that, for the most
part, we are not really very good at. Maybe nobody is good at them. Seeing the start contrast
between these two different processes is what got me interested in engineering productivity in the
first place. 


## A Focus on Engineering Productivity
<!-- .slide: class="contrast-bg" data-background="images/Bloombergadvanced8.gif" data-state="blur"-->
* Arcane code base
* Diverse set of customer requirements
* Constantly changing requirements (with real world deadlines)
Note: From there I transition to Bloomberg where I get to focus on the productivity problem full
time and here is where I got to  try a series of experiments. Bloomberg is an interesting company
and they deal with some really interesting problems. They have a pretty arcane codebase going back
to the early 80s. On top of that they need to meet a pretty diverse set of customer requirements and
they regularly need to update their software in response to changing financial regulation. So they
are some really hard problems and I enjoyed working there. When I joined they were working to
introduce some modern best practices into the system like modern version control, CI/CD, and unit
testing. These problems all have a technical component of course but there is also an important
cultural component as well.


## How Do You Change the Culture of a Company
<!-- .slide: data-background="images/dandelion-2817950_1920.jpg" -->

Note: This is really the central question. How do you introduce new processes and best practices
into a business that has been successful for so many years? Do you even need to change anything?


## Education
<!-- .slide: data-background="images/board-1848724_1920.jpg" -->
* Introduction to Automated Testing
* Introduction to GoogleTest/GoogleMock
* Dependency Breaking Techniques in C++

Note: Along with a group of very smart and motivated developers we came up with some training
material. An introduction to automated testing, which targeted product managers as well as
engineers. An introduction to GoogleTest and GoogleMock which were the most popular testing
frameworks at the time in the company, and a class on dependency breaking techniques in C++. The
training involved lectures and labs where the examples were drawn from a code base that the
developers would be familiar with. Education was really successful in changing the conversation,
but, it was almost totally ineffective in changing the culture. I think this happened for a few
reasons but one of the most basic reasons is that it was difficult for Engineers to bridge the gap
between the simplified examples that we used and the complicated code they were working with.


## Champions
<!-- .slide: data-background="images/chess-1483735_1920.jpg" -->
* Identify motivated engineers
* Provide hands on training
* Sync up regularly on problems
Note: So we moved on to our next experiment which was to nominate champions. There were a few
individuals across the department that had the know how and the motivation to apply the training and
get tests into their code. We would meet regularly and talk through problems. However, after a few
months it was apparent that this approach also failed to really move the needle. It seemed like
there was always some bug, or emergency, or fire drill that prevented the teams and the champions
from really committing the time to make the investments into long term productivity. Now when I say
this was a failure I don't mean to say it was a total failure. There were a few instances where we
started to see a change. A few teams had at least one person who was able to commit the time to
making some long term productivity enhancements. Wherever one or two folks in a team could commit
the time we started to see meaningful change take place. 


## Direct Assistance
<!-- .slide: class="contrast-bg" data-background="images/stormtrooper-2296199_1920.jpg" -->
* Temporarily embed into a team
* Make some long term productivity enhancements
* Train the team on the impact and value of each
Note: Learning from our first two failures we moved on to our next experiment which was supplying
direct assistance to the teams. This was basically an attempt to replicate some of the successes we
saw earlier. One of the lessons we learned is that the first step just orders of magnitude more
difficult than the second step. For these teams trying to make a shift to value the long term
productivity the first step involved learning a host of tools like the testing tools, the CI system,
and some pretty advance things about C++. However, once the initial hurdle had bee crossed making
those same investments across the team was about as complex as copy, paste, and edit.
Image by <a href="https://pixabay.com/users/aitoff-388338/?utm_source=link-attribution&amp;utm_medium=referral&amp;utm_campaign=image&amp;utm_content=2296199">Andrew Martin</a> from <a href="https://pixabay.com/?utm_source=link-attribution&amp;utm_medium=referral&amp;utm_campaign=image&amp;utm_content=2296199">Pixabay</a>


## A Recap but not a Capitulation

* Education can change the conversion but not the culture
* Incentives are powerful motivators (or de-motivators)
* The first investment takes more time than the second
* Motivated teams will make some investments


## The Engineering Productivity Team
<!-- .slide: class="contrast-bg" data-background="images/stormtrooper-2899993_1920.jpg" -->
### Embedded Productivity Engineers

## +

### A Brute Squad

## + 

### A Tools Team
Note: Image by <a href="https://pixabay.com/users/aitoff-388338/?utm_source=link-attribution&amp;utm_medium=referral&amp;utm_campaign=image&amp;utm_content=2899993">Andrew Martin</a> from <a href="https://pixabay.com/?utm_source=link-attribution&amp;utm_medium=referral&amp;utm_campaign=image&amp;utm_content=2899993">Pixabay</a>


## Results
* Faster adoption of best practices
* Unblocked from technology upgrades
* Happier developers
* Happier customers


## Looking Forward
<!-- .slide: class="contrast-bg" data-background="images/lemon-3976559_1920.jpg" -->
* Segment the population
* Find motivated partners
* Market your successes
* Gather data


## Recommended Reading (and listening)
<!-- .slide: class="contrast-bg" data-background="images/books-1655783_1280.jpg" -->
* [This American Life #561 - NUMMI 2015](https://www.thisamericanlife.org/561/nummi-2015)
* Clean Code - Robert C. Martin
* Working Effectively With Legacy Code - Michael C. Feathers
* To Sell Is Human - Daniel H. Pink
* How Google Tests Software - James A. Whittaker et al.


# Questions?
<!-- .slide: data-background="images/sunset-1373171_1920.jpg" -->
Note: Image by <a href="https://pixabay.com/users/Cleverpix-2508959/?utm_source=link-attribution&amp;utm_medium=referral&amp;utm_campaign=image&amp;utm_content=1373171">Cindy Lever</a> from <a href="https://pixabay.com/?utm_source=link-attribution&amp;utm_medium=referral&amp;utm_campaign=image&amp;utm_content=1373171">Pixabay</a>
