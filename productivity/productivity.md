#  Engineering Productivity
<!-- .slide: data-background="images/light-bulb-1246043_1920.jpg" -->


![WeWork](images/WeWork_logo_transparent-white.png)<!-- .element style="background: transparent;" -->


## First a Little Context
<!-- .slide: data-background="images/self.png" -->

Note: I have been programming for quite a while. Now I really didn't start this early, but it was
pretty close. I actually started learning BASIC on an Apple IIe when I was 12 and I pretty much kept
going since then. So programming really has become my lifelong passion.


## An Agile Introduction
![Menlo Innovations](images/menlo_logo.png)

& <!-- .element style="font-size: 60px" -->

![Compendia Bioscience](images/compendia_logo.jpeg) <!-- .element style="width: 28%" -->

Note: I've been in the industry for over ten years but I started at a little company called Menlo
Innovations followed by Compendia Bioscience. Both of these companies use Agile and extreme
programming, with pair programming, weekly sprints, demos to a realistic customer and, literal TDD.
I had an enormous amount of fun at these two companies and the it was formative for a few reasons
but critically as a contrast to my next company.


## A~~n SDET~~ Productivity Engineer is Born
![Microsoft](images/microsoft_PNG4.png) <!-- .element style="background: none" -->

Note: From these two companies I moved to Microsoft where I was initially hired as an SDET or
Software Developer Engineer in Test. A job I did not understand. This is a job that Microsoft has
mostly done away with but one of my responsibilities was to figure out which bugs to fix and which
bug we were not going to fix. It was a concept I was wholly unfamiliar with and it seemed pretty 
ridiculous to me.


## The Long-Term Cost of Short-Termism
<!-- .slide: class="contrast-bg" data-background="images/hard_for_devs.png" -->
* Every change gets more complicated
* Hard to onboard new developers
* Changes require intense manual work
* Increased time in unplanned work
Note: This transition was basically the radioactive spider bite or (radioactive bug bite) that got
me interested in developer productivity. This process externalized quality from the developer and
lead to a lot of time spent parsing logs, talking to customers, and reading through untested,
undocumented code that they either never touched or have not touched in months. These are a bunch
things that, for the most part, we are not really very good at. Maybe nobody is good at them. Seeing
the start contrast between these two different processes is what got me interested in engineering
productivity in the first place. 


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


# Questions?
<!-- .slide: data-background="images/sunset-1373171_1920.jpg" -->
Note: Image by <a href="https://pixabay.com/users/Cleverpix-2508959/?utm_source=link-attribution&amp;utm_medium=referral&amp;utm_campaign=image&amp;utm_content=1373171">Cindy Lever</a> from <a href="https://pixabay.com/?utm_source=link-attribution&amp;utm_medium=referral&amp;utm_campaign=image&amp;utm_content=1373171">Pixabay</a>
