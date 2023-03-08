Preface
=======

**I find bioimage analysis hard.**

````{margin}
```{image} images/good-bad-analysis.png
:class: dark-light
:width: 90%
````

After working in the field for over 15 years, developing algorithms, software and workshops, I feel like I *should* have amassed some level of expertise -- but I still find pretty much every new project I attempt to be difficult.
It remains common to find me wandering around the house, mumbling and grumbling to myself, while grappling with some tricky analysis problem whose solution eludes me.

If you want to read a book by someone who is pretty confident in their ability to quantitatively analyse whatever images come their way, this isn't the one for you.

I'm self-reflective enough to recognize that I might just not be very good at what I (try to) do.
Perhaps I'm ill-suited to a career that I tumbled into almost entirely by accident.
However, I take some comfort in the fact that, as I get to know more and more image analysts, it seems that most (if not all?) of us find many aspects of our work pretty difficult.

This isn't to say that *no one* finds analysing biological and biomedical images easy.
I've encountered plenty of people who believe it's really quite simple: you can see the stuff in the image, now just detect it and quantify it.
With ImageJ.
Or AI.
Or something.
Set a threshold?
Do whatever they did in that paper.
Just have the summary plots for the group meeting next week, ok?

The trouble is that, in my experience at least, this attitude tends to be found exclusively among people who are either too early or too late in their careers to actually have to sit in front of a computer and wrestle meaningful information from a billion uncooperative pixels.
Those of us who *do* need to sit at the computer know that it's not that straightforward.

But I don't want to get too gloomy.
Image analysis is hard, but there are good reasons not to give up.

I would argue that the problem is *not* that the concepts are difficult.
In fact, the most important ones are remarkably straightforward -- once you know about them.
A lot of the maths is basic arithmetic.

Rather, I'd say that image analysis is hard for two main reasons:

1. **Images in biology are *enormously* varied.**
Almost nothing 'just works'.
I might find a paper describing a marvellous method to detect, classify and track cells -- but there is no guarantee the method will work to detect, classify and track *my* cells.
Maybe I have a different type of cell.
Imaged on a different kind of microscope.
At a different spatial and temporal resolution.
To answer a different question.
In short, I have a very different computational challenge from the one described in the paper -- even if the shared theme of 'tracking cells' initially made it sound similar.

1. **Bioimage analysis involves a lot of disciplines**. Analysing images in a scientifically justifiable way typically requires (at least a bit of) knowledge across a lot of domains.
Of course it's necessary to know about the scientific question, e.g. the biology.
But to really understand the data, you also need to know about the experimental setup, the imaging hardware, fundamental limits like noise and diffraction, and also how digital images are represented, stored and (sometimes) compressed.
Then there are a plethora of image processing techniques that might help answer your scientific questions.
You need to know not only what these are, but also how to assemble them together into a sequence of steps that work reliably and with minimal bias -- either using existing software or by writing new computer code.
And finally statistics to bring it all together.
It's a lot.

But amidst all this variety lurk some of the positive things about image analysis: it's **creative**, it's **challenging** (most of the time in a good way), and -- because it's rare for any individual to be an expert in all the related domains -- it's usually **collaborative** (or at least it should be).

The fact that bioimage analysis is so cross-disciplinary means that pretty much everyone can have valuable insights to contribute.

This underpins my motivation in writing this book: I want to explain the concepts I use every day as an image analyst to people who spend their days differently.
No matter who you are, you know a huge amount of stuff I don't know.
My hope is that if we put the stuff we know together, we'll do better research, faster.

The one instruction is: **be prepared to think hard.**

When I'm confronted by an image analysis problem, my goal is never really to find the *right* way to do the analysis.
That generally doesn't exist.

Instead, my goal is to find the *least wrong* way to do the analysis -- and to be able to understand and explain whatever lingering limitations and biases can't be entirely overcome.
It can be frustrating, I still don't feel terribly good at it, but it is -- in its own strange way -- kind of *enjoyable*.
There's always something new to learn, and some new angle from which to look at the problem.
And each new angle can help us wring more drops of knowledge out of our data.

My hope is that this book will help introduce others find the weird, frustrating pleasure of thinking more deeply about scientific images.
Through this, I hope it might make a small contribution towards helping us do image analysis a bit better.

<div style="text-align: right; font-weight: bold;">Pete Bankhead</div>
<div style="text-align: right; font-style: italic;">April 2022</div>
