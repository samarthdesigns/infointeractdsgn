---
title: Info & Interaction Design, Intro
author: Mick McQuaid
date: 2022-08-26
bibliography: master.bib
format:
  revealjs:
    theme: moon
    css: style.css
    transition: slide
    background-transition: fade
    preview-links: auto
    controls: true
    controls-layout: bottom-right
    center: true
---

::: {.r-fit-text}
Day TWO
:::

## Materials You Need

(A) sketchbook

(B) pencil (preferably soft!)

(C) phone or device with camera

(D) prototyping tools

## (A) Sketchbook

- make it 5 x 8 or thereabouts
- document good design in it!

::: {.notes}
The sketchbook should be similar in size and shape to the Moleskine Cahier Journal, which is approximately 5 x 8 inches and 80 pages and sells for about 5USD. The brand is not important and there are many competitors to Moleskine offering similar journals. The reason for my request for uniformity is so that I can more easily manage collecting them and returning them to you. I have had students insist that they need larger or smaller or spiral bound notebooks or artist sketchpads and it has been problematic. Please restrict yourself to this approximate dimension. If you run out of pages, you can start a new notebook. Most brands offer these unlined, lined, or graph. Since my request for uniformity is related to size and shape to make them easier for me to carry around, I have no requirement for which page style you choose. I recommend unlined but many HCI people recommend graph paper or dotted paper.

Document examples of good design as you encounter them.  You can't get a perfect score on the design sketchbook without adding some good design examples each week.  You should plan to sketch for half an hour per day, three days per week to make a difference in your drawing skill and to receive full credit for the sketchbook.  There should be a noticeable progression in the quality of your results as the semester progresses, so there's no need to start as a perfectionist. This work is to help you express your design ideas, not to identify the most talented artist. Plan to turn in the notebook twice during the semester and expect examples from it to be used for this class and future classes, so don't include anything in it you'd prefer to not share with the class. 

Please use pencil for the notebook. The characteristics of a pencil figure prominently in a few exercises.  Many exercises could be done in pen and some can benefit from color but, for the most part, departure from pencil will be a distraction and a waste of your time and will lead to a lower grade. You can prevent your drawings from smudging by applying spray fixative to them.  Many artists use Krylon Workable Fixative, for about 7USD per can.  The word *workable* in the name signifies that you can apply a layer after your first layer of pencil, then begin drawing over it again.  You can do this repeatedly to prevent smudging drawings in progress.  Googling the term fixative just now led me to a lot of warnings about using it outdoors to avoid the toxic effects.  As with any other chemical, you must exercise appropriate caution and use sensible practices.
:::

---

![](fiJagerWangSketch.png){fig-alt="annotated pencil sketch of a tabletop tripod"}

## (B) pencil

![](fiWSDmechanicalPencil.png){fig-alt="fat mechnical pencil held in someone's hand"}

::: {.notes}
I found this image when I googled soft pencil for drawing. It exemplifies attention to the task!
:::

## (C) Camera

- phone
- tablet
- other camera
- be able to upload images to Canvas in a timely manner

::: {.notes}
Be sure to use Apple Notes > Scan Documents if on iOS, or CamScanner or similar if on Android.
:::

## (D) Prototyping Tools

- Framer will be demonstrated
- Figma
- Sketch
- XD
- Flavor of the month

# Definitions

We need working definitions of the words in the course title and description, even though these words are notoriously resistant to definition.

## (A) Information

```bash
From The Collaborative International Dictionary
of English v.0.48 [gcide]:

  Information \In`for*ma"tion\, n. [F., fr. L.
     information representation, conception.
     See {Inform}, v. t.]
     1. The act of informing, or communicating knowledge
        or intelligence.
        [1913 Webster]
              The active informations of the intellect.
                --South.
        [1913 Webster]

     2. Any fact or set of facts, knowledge, news, or
        advice, whether communicated by others or
        obtained by personal study and investigation;
        any datum that reduces uncertainty about the
        state of any part of the world;
        intelligence; knowledge derived from reading,
        observation, or instruction.
        [1913 Webster +PJC]
              Larger opportunities of information.
                --Rogers.
        [1913 Webster]
              He should get some information in the
              subject he intends to handle.
                --Swift.
        [1913 Webster]

     3. (Law) A proceeding in the nature of a prosecution
        for some offense against the government,
        instituted and prosecuted, really or nominally,
        by some authorized public officer on behalf of
        the government. It differs from an indictment in
        criminal cases chiefly in not being based on the
        finding of a grand jury. See {Indictment}.
        [1913 Webster]

     4. (Information Theory) A measure of the number of
        possible choices of messages contained in a
        symbol, signal, transmitted message, or other
        information-bearing object; it is usually
        quantified as the negative logarithm of the
        number of allowed symbols that could be
        contained in the message; for logarithms to the
        base 2, the measure corresponds to the unit of
        information, the hartley, which is log210, or
        3.323 bits; called also {information content}.
        The smallest unit of information that can be
        contained or transmitted is the bit,
        corresponding to a yes-or-no decision.

     5. (Computers) Useful facts, as contrasted with
        raw data; as, among all this data, there must
        be some interesting information.
        [PJC]

From WordNet (r) 3.0 (2006) [wn]:

  information
      n 1: a message received and understood
           [syn: {information}, {info}]
        2: knowledge acquired through study or
           experience or instruction
        3: formal accusation of a crime
        4: a collection of facts from which
           conclusions may be drawn;
           "statistical data"
           [syn: {data}, {information}]
        5: (communication theory) a numerical measure
           of the uncertainty of an outcome; "the signal
           contained thousands of bits of information"
           [syn: {information}, {selective information},
            {entropy}]

From The Free On-line Dictionary of Computing
     (20 July 2014) [foldoc]:

  information

     <data> The result of applying {data processing} to
     {data}, giving it context and meaning.  Information
     can then be further processed to yield {knowledge}.

     People or computers can find patterns in data to
     perceive information, and information can be used
     to enhance {knowledge}.  Since knowledge is
     prerequisite to wisdom, we always want more data
     and information.  But, as modern societies verge
     on {information overload}, we especially need
     better ways to find patterns.

     1234567.89 is data.

     "Your bank balance has jumped 8087% to $1234567.89"
     is information.

     "Nobody owes me that much money" is knowledge.

     "I'd better talk to the bank before I spend it,
     because of what has happened to other people"
     is wisdom.

     (2007-09-10)
```

::: {.notes}
So, I went online for definitions and here is what I found.
This is a pretty boring definition actually. It uses the term
knowledge, so I looked up knowledge. That definition refers to
knowing, and when I looked *that* up, it refers to information. So
we’ve come full circle and found that these definitions aren’t too helpful.

But there are a few interesting things to notice.

Of particular note in these definitions is that people define
information according to their work. So it’s a highly contextualized term.

One item that I like here is in definition number two with the
reduction of uncertainty about the state of the world. That at least
tells us what information does and it prefigures another definition of
information we’ll see on the next slide.
:::

---

::: {.r-fit-text}
*a message received and understood*
:::

::: {style="text-align: right;"}
&mdash; Claude Shannon
:::

::: {.notes}
Claude Shannon popularized the notion of information as a message received and understood because that notion served his development of information theory, which underlies the field of network communication.
:::

---

*1234567.89 is data.*

*"Your bank balance has jumped 8087% to 1234567.89USD" is information.*

*"Nobody owes me that much money" is knowledge.*

*"I’d better talk to the bank before I spend it, because of what has happened to other people" is wisdom.*

::: {.notes}
This definition comes from the *Free Online Dictionary of Computing* in a 2014 edition.

Some pundits like to posit a hierarchy of data, information, knowledge, and wisdom to support their work in a field called knowledge management. This field was popular about a dozen years ago and its influence had waned by the time this definition had been added to the Free Dictionary of Computing.
:::

---

*A man’s life in these parts often depends on a mere scrap of information.*

::: {style="text-align: right"}
&mdash; line spoken by<br>Clint Eastwood in<br> *A Fistful of Dollars* (1964)
:::

::: {.notes}
So, we know that information is a thing with some value, and that value may vary greatly, as we see in this quote from one of my favorite Spaghetti Western films.
:::

---

## (B) Interaction

If we do the same dictionary exercise with the word Interaction,
we'll find that it has a little more
substance.  It means reciprocal action or influence and
that is something we can work with---how the computer and the human influence each other. Reciprocity is a key to understanding and influencing interaction.

## (C) Design

*a plan or drawing produced to show the
look and function or workings of a building, garment, or
other object before it is built or made*

::: {.notes}
Design
is one of the best of all possible words.  I
always like to look up words in the dictionary, but not
many have the power of the word design.  It's no
accident that it is chosen by propagandists in the
Intelligent Design wars.  It's a very powerful word.
It's all about making conscious choices.
One definition you will find in in a dictionary is the preceding.
:::

---

::: {.r-fit-text}
*Design is all about constraints.*
:::

::: {style="text-align: right"}
&mdash; Charles Eames,<br>in an interview
:::

::: {.notes}
Notice that Eames doesn’t say *compromises* due to constraints. Somehow, a great designer works through constraints or with constraints.

By the way, Eames, along with his wife Ray Eames, was a major 20th century designer, working in various areas of industrial design and filmmaking.
:::

## Groups
Expect to form a semester-long project group and also to work in ad hoc groups on exercises.
Peer evaluations will count! Your semester-long projects will be graded as groups but you will submit anonymous peer evaluations that may affect individual grades.
I suggest that you form your semester-long project group by first forming a duo with someone like you, then putting together two dissimilar duos.

The ad hoc group work will also be evaluated, in part, on what you put into your notebook. Thus, two people in the same group could receive different grades for the differing quality of their notebooks.

## Grading

- The least favorite activity of teachers
- What does the grade mean, if anything?
- Let's discuss grading

::: {.notes}
Students often come to me after receiving a grade of less than a hundred percent and ask what they did wrong. Even after I have provided critiques of the class work in general and have raised the issues I have seen in the questioning student's work about some other work. Still they walk up to me after class and say, what did I do wrong?

It's a tough question to answer. There are several things to say about it. 
I'd like to devote a few words to each aspect of it.

First, there is the notion that it should be easy to obtain a perfect score if you simply learn the eccentricities of the teacher and cater to them. Do you see perfection in the world? Are hundreds of companies succeeding at making smartphones? Cars? Anything? Ask yourself whether you have ever given a negative review on a website. Judging by the number of negative reviews I have seen, not only has everyone on the planet given one but some have given more than their share! If you submit your work to the public, will the public give you a perfect score? And yet, in graduate school, teachers are encouraged to grade A as acceptable, B as bad, and C as catastrophic. It seems almost as if students feel entitled to a good grade by virtue of doing something.

Second, there is the question of the difference between your work and perfection. When you ask me this question, I feel as if you have not listened to the critiques given or you have dismissed them as not applicable to your work. Can I tell you some step you could complete to make your work perfect? Can I provide a box to check that will improve your work? What will happen to your work if I make it more to my taste? Teams at the CHI Student Design Competition under my coaching have competed very successfully against teams following checklists from other coaches. Let me provide you with the benefit of my experience.

The preceding point should suggest that you need to gain insight, not instructions. The only instructions most of you need right now are very very simple. I find myself constantly asking some students the same question: Can you please apply more ink / lead to the page? Until they do that, there is not much more to say. It is no accident that the most famous sports stars do goofy exercises like pushups even after they attain fame. There is very little for a teacher to say to most students. It is much more useful for me to listen to you than to speak to you, especially so early in the semester. The most important thing that anyone said to me on last Thursday was *My hand hurts*. That made me believe that the student (actually three different students said it) had finally put enough lead on the page, for then. Now my task is to exhort you to keep that up, a very simple task, simpler than continuing to listen to you, which remains my main task.

Next, there is the question of what *the other teachers do*. I really do appreciate it when students tell me what other teachers do. I also hope you appreciate that you should get a different perspective from each teacher. Your education should bring you into contact with methods you may not yet understand, methods you may find disagreeable. Yet the role of the student is to *suspend disbelief* and try something new, even if uncomfortable. Unfortunately, the tyranny of student evaluations prevents teachers from being too daring. I would prefer to have student evaluations conducted two to five years after the course is taken because I believe many students evaluate their comfort level right after they take a class. They evaluate their certainty about what they have learned. A contrasting view would be that, if you are so certain about it, you have not changed much, you have not learned much. You have simply filled in some cracks in the structure you already created. In fourteen weeks you can't do a complete renovation of your way of thinking and doing.


One of my own mentors said you can't effectively judge your own past for seven years (plus or minus). He wrote autobiographical books and plays and he claimed that, after more than seven years (plus or minus), memories get rusty and before seven years (plus or minus) you are too close to events to see how you have changed. So I ask you to suspend disbelief for a while and try something new and later see if you agree that you have changed for the better.
:::

## Whether perfect should be average

- Do you like rubrics?
- What is the problem with rubrics?
- Can you succeed at any profession by following clear, specific instructions?

::: {.notes}
One approach to education is to provide students with a clear, simple list of instructions to follow. This is usually called a rubric. Those students who follow the instructions receive a perfect score and the others have only themselves to blame. They had the opportunity to achieve a perfect score because there were clear instructions. Only their own laziness or obstinacy is to blame for ratings below excellent.

The above approach leads to high satisfaction among current students. Students often feel as if they are in control of their education with this approach. They may say that it empowers them. Because young people often have little control over many aspects of their lives, the sense of control can feel like an education. Students often feel that, by taking responsibility for following clear instructions, they are learning a lot. They report favorable learning outcomes after taking courses that follow this approach and, increasingly, they are perceived as customers whose satisfaction is essential to the operation of colleges facing spiraling costs due to mushrooming administration.

As a result, this approach is spreading like a disease across all universities. Once a student has experienced this sense of power, they never want to return to the sense of uncertainty they may have experienced as an alternative. Once this approach is the norm in any department or college, it becomes irresistible for outliers.  Individual teachers may claim that you should use college as a place to experiment with new approaches and maintain an open mind to trying different things, but that argument is ignored if GPA is the only criteria for scholarship, internship, or employment selection. The very same sponsors and employers who bemoan the lack of imagination and inventiveness of recruits encourage this lack by using crude numbers for selection.

I (Mick) strongly believe in quantitative information. When people say that something is not quantifiable, I often find myself disagreeing. The problem is that quantification often requires more time, money, space, or other resources than are practically available. Grading is an example of poor quantification practices tyrannizing thoughtful people.

I need to balance several things in order to provide adequate grades. I need to compromise with the "perfect is average" environment but I also need to find a useful way to score that I can believe improves education rather than simply robbing me of my value as an educator. I need to reevaluate educational goals and techniques because the rest of the world has moved into a new era and the education establishment does not seem to be catching up.

Incredibly, students often complain that I change things and insist that my courses should be cut and dried without deviation from the beginning of one semester to the end. Then, if I want to try things differently, I should begin the next semester differently and remain consistent with the new thing throughout that semester. These same students often complain that education is stuck in the past, yet they contribute to that problem by their very insistence on a glacial pace of change.
:::

## Powerlesspoint

- Guess how much I like it
- Check out `Tufte2003.pdf` if you have time

::: {.notes}
A student once wrote to me expressing that she had a hard time "wading through the lecture notes." In the same message, she suggested that I use Powerpoint, assuring me that it can work well for certain purposes.

I want to help you. I want you to extend yourself. Being a student means exposing yourself to new and different ways of doing things. I want you to abandon your reliance on Powerpoint this semester and try to use different ways to understand and present material.
To support you, there are a few readings that may help.

First, there's a file called `Tufte2003.pdf` under Files > misc on Canvas. This chapter presents a repudiation of Powerpoint based on its information content and suitability to intended purpose.
Tufte invokes Feynman as someone who was appalled by bullet points. Feynman's Lectures on Physics are perhaps the most important vehicle for college students learning physics and they may present an alternative to which educators can aspire.

The second is actually a video. Visit Youtube and search for pixar storyboarding. There are many videos about the storyboarding process at Pixar. I have a DVD (remember those) of Pixar Shorts that includes such a video. I have since discovered that there are so many on Youtube that it is pointless to put something on Canvas. Any of these videos show the appropriate use of storyboarding and should make it clear that slide show software is inadequate to the task. The individual "slides" are attached to walls of conference rooms at Pixar and someone talks through the story while pointing at the relevant pictures on the wall. Participants are free to run around and examine each frame, engage in sidebars, sketch their own alternatives on paper and put them up on the wall, and otherwise engage in a collaborative process.

Third is a profile of a team of high-school students who won a robotics competition in 2005. During the question and answer round of the competition, they raised the judge's eyebrows because they did not provide a Powerpoint. When asked why, they answered that Powerpoint was for people who did not know what to say. The judge was impressed by their responses to questions. They won. They defeated a team from MIT, among other teams, all of whom had slick PP shows.

Please bear in mind that no important works in history have been accomplished in Powerpoint format. The only valuable Powerpoint of which I have ever heard was an experiment by David Byrne and Brian Eno to create art out of Powerpoint.

H.R. McMaster hates Powerpoint. Like Lou Gerstner at IBM, McMaster banned Powerpoint among his staff. Googling these names will lead to more interesting articles decrying PP.

Beware of "good" Powerpoint. Students sometimes tell me that the problem with PP is that it is not well done. I have one student whose father built a lucrative second career out of preparing slick PP for others. He had been a photo slide show specialist in the days when Kodak was big and had simply learned its replacement. I have no doubt that he does "good" PP. He makes a very good living at it. That does not excuse the people who pay him for it and the audiences who evaluate it (the PP) rather than whatever the subject of the PP is. There is, of course, an industry of PP consultants to tell you what colors and words and transitions and fonts and punctuation to use. Do not waste your time, at least this semester, listening to them. Everything that they say is either wrong or is a diluted version of information you can obtain straight from @Arnheim1974 or @Bertin2011 among other sources. Go to the source to learn about design. Avoid mixing your design education with a PP education.
:::

# References

::: {#refs}
:::

---

::: {.r-fit-text}
END
:::

# Colophon

This slideshow was produced using `quarto`

Fonts are *League Gothic* and *Lato*

