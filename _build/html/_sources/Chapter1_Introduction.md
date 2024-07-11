# Chapter 1 Introduction
## 1.1 What is Analysis?

Broadly speaking, *Analysis* is the theory of the *limit*. It serves as a foundation for Calculus, and also enables us to give a mathematically rigorous description of the real number line. Like Algebra, Geometry and Topology, it is one of the central themes of pure mathematics and is still being actively developed by research mathematicians. It is also a vital tool in many applications, for example in  quantum theory, probability theory, finance and economics,...

In this course, we will study *Real Analysis*, so our focus is on real numbers and real-valued functions. In later years, you may choose to study *Complex Analysis* (MAS332), *Functional Analysis* (MAS61018) - where Analysis meets Linear Algebra, or other parts of Analysis that build on the work we'll do here, such as *Metric Spaces* (MAS331), and *Probability with Measure* (MAS31002).

The modern theory of *Calculus*, which is a mathematical theory of change and motion, was to a large extent, discovered independently by two great scientists Isaac Newton (1642-1727) and Gottfried Leibniz (1646--1716), but despite its amazing success in applications, it was not a logically coherent theory at the time that it first burst on the scene, more a collection of useful mathematical methods. You all know the definition of the derivative at a point $x$ of a "sufficiently nice function" $f$:


$$\frac{df}{dx} = \lim_{\Delta x \rightarrow 0}\frac{f(x + \Delta x) - f(x)}{\Delta x};$$ 

but how we know that $df/dx$ exists? What does $\displaystyle{\lim_{\Delta x \rightarrow 0}}$ really mean? What is the "infinitesimal quantity" $\Delta x$, and how can it "tend to zero"? In the eighteenth century, Calculus was fiercely criticised by the British philosopher George Berkeley, who called infinitesimals like $\Delta x$: "the ghost of departed quantities".

Many mathematicians rose to Berkeley's challenge and tried to give a satisfactory foundation to Calculus, but it wasn't until the nineteenth century that modern Analysis was born, and a logically rigorous meaning was given to the concept of the limit. This was mainly the work of three great mathematicians: Augustus Louis Cauchy (1789-1857), Bernhard Bolzano (1781-1848), and Karl Weierstrass (1815-97).

One of the key aims of this course is to understand the definition of the limit, discover its properties, learn how to use these, and also give a more thorough foundation to the real number line, and to Calculus.

In this course, we will study sets of real numbers, sequences and their limits, and the convergence of infinite series. Along the way, we will prove a lot of new theorems, many of which are also very useful in applications.

This will pave the way to studying (in Year 2) limits of functions and what it means for a function to be continuous, differentiation as a limit, Riemann-integration, and you will also learn how one can extend our work on sequences and series of numbers to sequences and series of functions.

## 1.2 The course and what to expect

In order to make sense of an Analysis course, you need to first understand how this theory fits with earlier mathematics. You already know a lot of Calculus from high school and you have "levelled-up" from your exposure to MAS106. In particular you know about functions and about how to differentiate and integrate them, and you also know some things about sequences and series. You may anticipate that Analysis will start from what you know and go upwards; that you will learn fancier and more complicated techniques for integration and differentiation and for working with sequences and series. In fact, that is not what happens at all! 

As already mentioned in the introductory section, Analysis doesn’t build upwards from Calculus - it sits underneath it.\ Other courses do build upwards: you will soon learn (MAS106, this term) about integration and differentiation for functions of more than one variable, and you will eventually learn about solving differential equations, and about how to work with functions of complex variables. But Analysis, on the whole, builds down from Calculus, not up. Instead, in Analysis, we explore the theory that underlies Calculus, and understanding why it all works. Analysis might -at first, at least- seem a long way from what you’ve just been studying so far, and some of the early work will seem insultingly basic. But that’s the point: a theory in advanced mathematics should start from basic things and build up a coherent theory!

Analysis is hard. It’s elegant, clever, and rewarding to learn, but it’s hard. Ask your lecturers (including myself!) and you will find that a good proportion of them think that Analysis is great now but struggled with it at first. 

This course will not make it easy, sorry! **BUT** not for the lack of willingness to do so! That would be impossible because the logical complexity of the fundamental definitions exceeds that encountered in everyday life and in earlier mathematics, so you should expect to face an upswing in the demands on your logical reasoning. I will however try to provide an extended, in-depth explanation of these definitions and of related theorems and proofs. I will aim to give substantial attention to the basics, explaining not only the mathematical concepts but also psychological issues associated with learning to think about them.

What you **should not** expect from this course is a list of procedures to follow. It is extremely important to recognize this. Analysis, like much undergraduate pure mathematics, can be understood as a theory: a network of general results linked together by valid logical arguments known as proofs. The fact that a proof is valid for all objects that satisfy the premises of the associated theorem means that it could be applied repeatedly to particular objects. However, Analysis does not focus on algorithmic processes and calculations. Rather, its focus is the theory: it is the theorems, proofs and ways of thinking about them that you are supposed to understand. Having said that, there are patterns that appear again and again, and I will be trying to offer you certain templates to guide your thinking. In the many years that I have been thinking about Analysis (which, by the way, is my main area of expertise and has my vote for the most interesting area of Mathematics!), I have discovered several rules of thumb (heuristics) that help me understand various results (visually too), and even better, guide my thinking when I construct new proofs. I have every intention (if "desire" sounds too cheesy) to pass these on to you.

However, while I will be helping you along the way, developing this understanding is ultimately your responsibility. Myself (and the tutors in your weekly tutorials, as well as the markers of your homeworks) will do our best to support your learning. But most of the time you will be part of a large class where opportunities for individual attention are limited, and you will leave numerous lectures with only a partial understanding of the new material. You therefore need to get good at working out for yourself what it all means. What **will help**:

* **Come to class!**
* **Go to the tutorials!**
* **Ask questions in class/office hours/tutorials!**

and more importantly 

**Work on problems! Don't just read maths, write/fight/play with it!**

*If you attempt to go through this course without working on a significant number of exercises, I will come to your house and annoy you until you beg for mercy. It is important to not just have a vague sense of what is true, but to be able to actually get your hands dirty. As Prof. Mark Kisin (Harvard University) has said,* **You can wave your hands all you want, but it still won’t make you fly."**



### 1.2.1 Some vague cheerleading and some generally helpful advice

With that in mind, I’ll leave you with a quick review of some important things to remember. [^Alcock1]

Every student of Analysis should pay attention to the definitions.

1. When reading lecture notes or a textbook, read properly. Read whole mathematical sentences, not just the algebraic bits. Ideally, read out loud, especially if you’re stuck. 
2. Look for links between diagrams or other informal representations and the formal mathematics. I say this because Analysis students often tell me that they "get the ideas" but don’t understand much of their notes. Usually these students will try to explain their understanding by gesturing or by drawing diagrams, and it’s clear that their thinking is fairly accurate. What they haven’t done is linked that understanding in detail to the expressions that appear in a relevant definition, theorem or proof. In particular you should give the **self-explanation** [^Alcock2] a go [(I am a link in the online version - click me)](https://drive.google.com/file/d/1m7Anp3Qrchh0evW7gYYoWWwEBISvgjwb/view?usp=share_link). 
3. When trying to write mathematics, get something down on the page! Students sometimes seem paralyzed in the face of a blank page - they are unwilling to write anything down because they don’t know how to produce a full and perfect calculation or argument. Iteratively improve your work, but start writing something!
4. In your studies in general, aim for a balance between persevering and taking proper breaks. You’ll never get anywhere if you give up as soon as something gets a bit difficult, but there are no prizes for the student who can sit at a desk the longest. If you keep going when you’re tired you’ll become less and less effective; if you do that repeatedly you’ll burn yourself out. It is an especially bad idea to pull all-nighters during exams.
5. Embrace opportunities to be wrong. For that you will also need to put your ego away: you are guaranteed to feel silly and question your knowledge AND your intelligence (which happens to me 95\% of every day). The "secret" is to keep at it, and also believe that you will get better with practice and reflection. You **do** get better and better. It's like going to the gym: first you can't lift much or run for long, but you keep pushing a bit more every time, you rest wisely and keep going day-after-day, and you will see improvements.*"Practice makes perfect" is a lie*. Practice DOES make better (and better) though!

[^Alcock1]: This is taken, for the most part, from Lara Alcock's book {cite}`Alcock`, Chapter "Conclusion". I strongly encourage you to check this book out, it can be very helpful.

[^Alcock2]: Also taken from Lara Alcock's book {cite}`Alcock`.


## 1.3 About these lecture notes

These notes are not comprehensive, in the sense that you can find more results and ideas in other books and notes. Having said that, they are also *more* comprehensive than more lecture notes you will find. I very much doubt that we will manage to cover everything that's in the notes, but this is not something I am worried about: I will tell you clearly what can be safely ignored, and what will be examinable. We may cover some of the material in a section with an asterisk in the title, but these will definitely not be examinable.

I have tried to maintain a conversational tone, which you should not expect in general from reading mathematical books/lecture notes. The side effect is that in doing so I ended up writing *much more than you should expect to see in mathematical texts in general* (I am managing your expectations here). The reason this happened though, is because I have tried to convey my way of thinking when processing new results and constructing new proofs, but I appreciate that my style won't necessarily resonate with each one of you. In lectures, I make a conscious effort to present the material in different styles (e.g., both "algebraic" and "visual/geometric"). However, you can help me help you by letting me know (the sooner the better!) if something doesn't make sense! I will try to reword it and perhaps manage to present it in a different way that makes more sense to you.

### 1.3.1 How to use these notes and study for the course in general

**First of all**, the lectures will follow the notes, but rather *loosely*. I am not planning to cover all the examples or all the proofs, and in general, I will be trying to use different examples than in the notes for you to have access to a larger library of resources.

**After each lecture**, 

* I will be updating a "course diary" on Blackboard (I usually call it "material covered so far"). Each entry will summarise the highlights of the corresponding lecture, point to the relevant pages in the notes, and also make a guess about what will be covered in the next lecture (and give a guess about the relevant pages in the notes; it will be a guess because I may have to go slower than planned).
	
* Based on your class notes and your reading of these notes, you should make your own notes after every lecture. My advice is to wait for a few hours after the lecture before you do that. You should also actively engage with this process, forcing yourself to constantly question your understanding as you go, don't just copy passively! *Make a list of things you don't understand and ask me!* Ask me sooner than later, don't wait until Easter or until close to the exam period.
	
* After you've done the above, you need to work on some exercises. For this, I will also have a file (again on Blackboard, probably attached to the "course diary") where I will be setting some exercises for practice on the material covered in the lecture. **It is MOST IMPORTANT that you work on those!** I am more than happy to discuss them (email/discussion board/office hours) but please spend time thinking about them on your own first, before you start collaborating with other students or ask me. Solutions to those will be posted before the next lecture.

**Before the new lecture**, check the course diary and have a quick (10 minutes maybe?) look at the material I said I am planning to cover. Don't underestimate the usefulness of this practice. Don't take my word for it, try it a few times and see for yourselves!

**Come to the weekly tutorials**, and apply yourself to seriously working on the problems.

**Do and submit the homeworks** and carefully read the feedback your grader will give. While I am not marking them myself (it's some very competent PhD students who do), I want you to come to me regarding any questions on your work or the feedback given.


### 1.3.2 What if you fall behind?


**Don't panic!** Come and talk to me. While Maths is quite hierarchical (stuff depends on previous stuff), the **biggest mistake** you can make is to think you are too far behind to go to lectures, and promise yourself that you will start going again once you've caught up. Don't do this! Learning rarely happens linearly anyway, learn to accept some concepts as "black boxes", and revisit them later (perhaps again and again). Apply them even if you don't fully understand them. I am dead serious about this. We get used to things, we absorb "vocabulary" and "rules", and if we keep trying to understand what's going on, understanding will come. Understanding comes in waves, don't expect to leave the classroom and have internalized everything. But do come to class because I will try to guide your thinking and help you build from there.

## 1.4 Logic and Proof

Writing rigorous mathematical proofs is a skill best learned by doing, and there is plenty of on-the-job training just ahead. There is an artistic quality to mathematics of this type, which may or may not come easily, and undergraduate students often think that proofs are mysterious. They’re really not. A specific proof might be difficult to understand because of its logical complexity, or because a student doesn’t have a good enough grip on the definitions of the relevant concepts. But the idea is not difficult at all: a proof is just a convincing argument that something is true. A proof is an essay of sorts (the good type of essays, I know most of you hate them, but bear with me here :) It is a set of carefully crafted directions, which, when followed, should leave the reader absolutely convinced of the truth of the proposition in question. To achieve this, the steps in a proof must follow logically from previous steps or be justified by some other agreed-upon set of facts. In addition to being valid, these steps must also fit coherently together to form a cogent argument. Mathematics has a specialised vocabulary, to be sure, but that does not exempt a good proof from being written in grammatically correct English.

The next result illustrates a number of the issues just discussed and introduces a few more.

````{prf:theorem}
:label: firstproof

Two real numbers $a$ and $b$ are equal, if and only if, for every real number $\epsilon > 0$ it follows that $|a-b|<\epsilon.$

````

````{prf:proof}
I want to draw your attention to two important phrases in the above statement. The second one is "for every" which we will discuss in a moment, but I first want to make some comments on "if and only if" (often abbreviated as *"iff"*). This is a very commonly employed way to state, in a single stroke, that the result is true in both the "forward" and the "backward" direction.

To elaborate:
	
In the forward direction, we need to prove the statement: 
	
$(\Rightarrow)$ If $a=b,$ then for every real number $\epsilon > 0,$ it follows that $|a-b| < \epsilon.$

We must also prove the "converse" (backwards) statement:
	
$(\Leftarrow)$ if for every real number $\epsilon > 0$ it follows that $|a-b|<\epsilon,$ then we must have $a=b.$
	
You will surely agree with me that for the forward statement there is hardly anything to say. If $a=b,$ then $|a-b|=0,$ so certainly $|a-b|< \epsilon,$ no matter which  $\epsilon > 0$ is chosen.
	
For the converse, we will give a proof by contradiction. The conclusion of the proposition in the backwards direction states that $ a = b,$ so we assume that $a \neq b.$ We need to produce a chain of logical arguments that will result in something unacceptable, and to do this we start by focusing on the  "for every $\epsilon > 0$" phrase. 
	
**Be warned:** This **literally** means **for all!** It perhaps belabours this point, but let's see some equivalent ways to state the same hypothesis. It would be equivalent to say that "for all possible choices of $\epsilon > 0$ " or "no matter how $\epsilon > 0$  is selected", it will always be the case that $|a-b|< \epsilon.$
	
But as we are assuming (for the sake of contradiction) that $a \neq b,$ already the choice of

```{math}
\epsilon_0 := |a-b| > 0,
```

is a troublemaker.
	
Why? Because, as we are working under the assumption that $|a-b| < \epsilon$ *for every* $\epsilon > 0$, this should definitely include the specific $\epsilon > 0$ we just defined. Obviously, the statements	

```{math}
|a-b| = \epsilon_0 \quad \text{and} \quad |a-b| < \epsilon_0
```


cannot both be true. This contradiction means that our initial assumption that $a \neq b$ is unacceptable.

Therefore $a=b$ and the indirect proof is complete.

````

A few comments are in order:

One of the **most fundamental skills** required for reading and writing Analysis proofs is *the ability to confidently manipulate the quantifying phrases "for all" and "there exists"*. Significantly more attention will be given to this issue in
the rest of these notes and the course.

Notice that part of the above proof used an indirect strategy called proof by contradiction. A direct proof begins from some valid statement, most often taken from the theorem’s hypothesis, and then proceeds through rigorously logical deductions to a demonstration of the theorem’s conclusion. As we saw earlier, an indirect proof always begins by negating what it is we would like to prove. This is not always as easy to do as it may sound. Not to scare you, but negating statements involving "for all" and "there exists" will often be the name of the game [^worrynot] . The argument then proceeds until (hopefully) a logical contradiction with some other accepted fact is uncovered. Many times, this accepted fact is part of the hypotheses of the theorem. When the contradiction is with some of the theorem’s hypotheses, we technically have what is called a contrapositive proof.

[^worrynot]: Worry not, we will get plenty of practice with that, but it will be a good idea to review the relevant parts of your MAS107 notes from Semester 1.


Another very common strategy we will use (especially when we get to the "Sequences" part of the course) will be **induction**. You have already seen this in Semester 1 (in both MAS106 and MAS107), and in a lot of detail, so I won't go beyond a quick reminder. Induction is used in conjunction with the natural numbers, $\mathbb N$ (sometimes we include $0$ and look at the set $\mathbb N \cup \{0\}$ of non-negative integers). The fundamental principle behind induction is that if $A$ is some subset of $\mathbb N$ with the properties that 

1. $A$ contains $1$ and 
2. whenever $A$ contains a natural number $k,$ it also contains $k+1$

then it must be the case that $A= \mathbb N.$

Or, in terms you have encountered (but completely equivalent to the above), if we want to show that some statement, $P(n)$ is true for all $n$ (i.e., that the set $A$ of $n \in \mathbb{N}$ for which $P(n)$ holds is all of $\mathbb N$),  we need to check that $P(1)$ is satisfied (i.e., that $1 \in A$) and that, assuming $P(k)$ is true, we can show that $P(k+1)$ holds.

Any discussion about why induction is a valid argumentative technique immediately opens up a box of questions about how we understand the natural numbers. At this stage I am happy to side with Leopold Kronecker and put forward his famous claim that "The natural numbers are the work of God. All of the rest is the work of mankind." Although we will not improve on this explanation here, it should be pointed out that a more...agnostic, and mathematically satisfying, approach to $\mathbb N$ is possible from the point of view of axiomatic set theory. Pedagogically speaking, the foundations of mathematics are best learned and appreciated in a kind of reverse order. A rigorous study of the natural numbers and the theory of sets is certainly recommended, but only after we have an understanding of the subtleties of the real number system. It is this latter topic that is the business of Real Analysis, which will be our focus for this term!
