# Maths_Behind_DS_Duke_University

## Numbers- The Real Number Line
Okay, so first let's meet the real number line. What we do is we draw a line.<br><br>

And I refuse to ever draw it straight. Suppose this is the real number line. It goes all the way on the extreme right to positive infinity, and the extreme left to negative infinity.<br>

And you want to think of this as representing an infinite set. That infinite set is going to be called R, which we usually write this sort of blackboard R symbol. This is equal to the real numbers.<br>

So, now the idea is that every single dot along this line represents a real number. There's a ridiculously large, infinite number of them. And we're going to think about what some of those are. First, let's mark some we know. So usually, somewhere in the middle we put 0, and then we sort of make tick marks for whole numbers. So here's 1, here's 2, here's 3, here's 4, here's 5, on forever. Here's -1, here's -2. Here's -3 on forever. If we're being careful, we try to make the length of each of these little sticks the same.<br>

Okay. So what I just wrote down are whole numbers, who are often called integers. So a subset, if you called z consists of just the integers. This is dot, dot, dot, -3, -2, -1, 0, 1, on forever.<br>

Okay, not every single number on the real number line is an integer. In fact, most of them aren't. Suppose we blew up this little stick between one and two. Let's just take it out here and blow it up, just so we can see it better. Here's one at one end, here's two at the other end. Let's just draw that.<br>

The only thing you really need to know here, without getting into any details Is that every single thing between one and two is also a real number. Same between two and three, same between three and four, and that there's a ridiculously large infinite numbers between one and two, how do you make them all? So here's a recipe, take one put a dot, put any string of whole numbers you want afterwards So, for example, 1.1 is in there. There it is, about there. 1.1, about a tenth of the way. So is 1.4, there it is. So is 1.1538, which might be about there. And in fact, anything that you do whether you continue on finally or really infinitely is a real number. That's the case for any subinterval in here. So if I take this subinterval and I'd blow it up out here, here's -3, here's -2 right about there, might be minus 2.5. So really, a real number is any integer dot any string of integers you might possibly want.<br>

It's a little bit of a nicety, which we won't get into, which is that some of these strings of integers terminate, some of them don't. You've probably heard of real numbers like pi.<br>

Pi, somehow you've probably seen is approximately 3.14128, so on so forth, one of the things that goes bump in the night. There are real numbers which are represented as streams of decimals which continue on forever, don't repeat don't have any pattern. Those are called irrational numbers. We’re not going to think about those here. Really here the take home message is just a real number is a number along this line and there are a whole bunch of them. Okay, one of the things we often do as mathematicians is we compartmentalize big sets into smaller and smaller sets and give different categories for what things are. So the first very big division of the real numbers is into positives and negatives. So here's our friend, the real number line again. Here's zero. Anything to this side of zero will be called positive reals. Positive real numbers.<br>

Anything to this side, if we have a negative real numbers.<br>

So an example of a positive real number might be 5.3 might be 0.001. For example the negative real number right here might be negative 11.7 if we include zero, So the positive reals but including zero we often write the non negative reals- and if we include 0 on the other side we go from right, non positive reals.
<br>
Okay, fine, let's draw that real number line again. Let's try to get straighter each time. An important thing to realize so that in some sense numbers come in pairs, positive and negative versions of the same number. So here's 0. Suppose I take the number over here 7.1. It has a friend on the other side called negative 7.1. Just like here you have 10, here you have negative 10.<br>

Now notice 7.1 is not equal to -7.1. 10 is not equal to -10. However, 7.1 and -7.1 have one important thing in common, which that they have the same distance to zero. The distance from here to here is about 7.1, is exactly 7.1. And the distance from here to here is 7.1. There's a concept called absolute value. Let's define that.<br>

The absolute value- Of a real number and let's say the real number is X for the definition, which we denote like this, X with a little symbol around it. Notice that it looks exactly like the definition of cardinality of a set, which is unfortunate.<br>

Is the distance- From X to 0, so you want to start at x, you want to walk to 0 and let's figure out how many units you've walked.
Play video starting at :7:6 and follow transcript7:06<br>
We'll notice over here that the absolute value of 7.1 is 7.1 and the absolute value of minus 7.1 Is 7.1, which by the way is the same thing has negative, -7.1. That's not just a huge little formula. We all know that negative times negative equals positive. But it allows us to make a general definition. So let's write that down in here, through the general rule For any real number, for any x in R, the following is true. The absolute value of an x can be one of two things. What I'm going to do here is give you what's called a definition by cases. Part of the point of teaching this is not just to give you the formula for the absolute value. But also you're going to see this definition by cases throughout data science. Death of value of x is equal to plain old x if x is non negative.
<br>
But it's equal to negative x if x is negative.<br>

Let's check if that's true, and while we check this, this'll sort of show us how to parse the definition by cases.<br>

So let's compute the absolute value of 8.7. So according to this definition, 8.7 is our It's either going to be 8.7 or negative 8.7. But which case happens? 8.7 is non-negative so i'm in this case up here. So this is just equal to 8.7. And that's true. Right, I draw my real number line. Here's zero. Here's 8.7.
<br>
That distance is 8.7. Let's check a different one.
<br>
This shouldn't surprise you, let's check a -1. So let's say let's check -10, the absolute value of -10. What should this be by the way? If here is -10, it should be this distance.<br>

Which is 10. So I go through my definition. -10, okay, 10 is negative. Therefore, this formula tells me to take the negative of -10. Is equal to negative -10, <br>
Okay, that concludes this video where we've learned what the real number line looks like, what it means to be positive, negative, non-negative and non-positive, and also about absolute values.
<br>
In the next video, we're going to jump into the idea of inequalities. What it means for one number to be less than another number, less than or equal to another number, and so on. And we'll connect that back to absolute value.


## Numbers - Interval and Interval Notations<br>
So here's the real number line. We've talked before about finite sets, but in fact the real number line is an infinite set.<br> Think of the large infinite number of things on this. <br>
Now there's a lot of subsets of this which are also ridiculously large and infinite. So let's just jump right in, this symbol, [2, 3.1]. <br>
This is an infinite set, but if an infinite set has got a finite bound -- we'll talk about how to describe what this is -- this is equal to the set of all numbers X in R, which satisfy two conditions. <br>
First, X has to be greater than or equal to two, and X has to be less than or equal to 3.1. <br>

In other words, to draw this on the real number line, here's two, here's 3.1, and X is trapped in between these two boundaries but it can hit up to both.<br>
So X is any number in the world as long as X is greater than or equal to two, less or equal to 3.1. So let's name some things in here. For example, 2.3 is in [2, 3.1] because two is less or equal to 2.3, and 2.3 is less or equal to 3.1. Three is in there, also 3.1 is in there, but one is not in the closed interval from two to 3.1, because one is not in fact less or equal to two even though it is actually less or equal to 3.1, well it's not greater or equal to two. OK, so that's a closed interval. Let's introduce the next idea. <br>

Suppose I give you (5,8) and here I use parentheses instead of those bracket symbols. This stands for an infinite set, the set of X in R, such that X is strictly greater than 5 and just strictly less than 8. So, the way we note this is, here is zero. We make a little open symbol for 5, little open symbol for 8, then we just take all the things in between. So the idea is you have to be between 5 and 8 but you can't hit up against those end points. So for example, 5.5 is in the open interval from 5-8, so is 5.0001 is in the open interval from 5-8 but sadly five is not in the open interval from 5-8, because five is not less than five even though it is less than eight. So you might want to think, by the way, what's the difference between the closed interval from 5-8 and the open interval from 5-8?<br>

They differ in exactly two numbers. They differ in five and eight. Five and eight are in the top one and not on the bottom. Okay so those are two extremes, here's two things in the middle, which we call "half-open intervals". Let's take for example, (-7.1,15]. You might already be able to guess this. On the open side, that means we use a strict inequality, and on the other one we use less than or equal to. This is an infinite set. Set of all X in R such that -7.1 is strictly less than X is less than or equal to 15. So how am I be drawing that, here is an open -7.1. There is zero, just so we know where we are, and there the closed 15 off the scale and all that stuff in there. Okay, we'll take the other extreme. So let's say for example, [20,20.3).<br>

This will be the set of all X in R plus the 20 is less three or equal to X and less than 20.3. Draw again the real number line. Here's my zero, let's see here's the 20 and here is an open 20.3. There's the stuff in here. But a little point to make, in some sense this seems really small, 20 to 20.3 is really tiny on the real number line compared to -7.1 to 15. It's got infinitely large number of numbers in there. That's the hilarious thing about the real number line. There's a lot of fancy math which you will get into behind it.<br>
<b>We've seen closed intervals, like [2, 3.1] </b>.<br> <b> We've seen open intervals, like (5,8) </b> <br>. <b> And within two species of half open intervals, like (2,3] and like [20,20.3) </b> <br>. <b>Sometimes if we want fancy vocabulary, the first of these half open interval is called left open, this is called right open, that doesn't really matter. OK, let's show you one more slightly more exotic form. Suppose we write, close_two_comma_infinity. This just stands for the set of all X in R, such that X is the greater than or equal to 2, full stop. You don't have to be less than infinity because every number is less than infinity. We often draw that on the real number line, here is zero, there's a two and we just take all the stuff here, kind of going on forever </b>. This is often what we call a "ray". You could also have for example, a minus_infinity_ to_7.1_open. This is the set of all X in R, that should be X is less than 7.1, and you get the idea. Okay, let's close by tying in to the algebra we recalled in this video. We're already comfortable with the idea that if someone asked you to solve for X, and X+5=10, you do some algebra and you solve that X equals five. So X=5 is the answer, a number is an answer. Suppose on the other hand, someone gives you the following problem: Tell me everything you know about X if the following is true; 1_is_less_or_equal_to_X_plus_five_is_less_than_ten. So notice here, a single number is not the answer. For example, if X=4, then 4+5=9, nine is less than 10, nine is greater than or equal to one, but 3.9 would also work. In fact, it turns out that the answer is an interval. If we do a little bit of algebra, let's subtract five from all sides of this. Let's subtract five from the left side, I get -4 is less than or equal to, subtract five from the middle I just get plain old X that's why I subtracted five, that wasn't random. Subtract five from the right, I get 10 minus fSo here's the real number line. We've talked before about finite sets, but in fact the real number line is an infinite set. Think of the large infinite number of things on this. Now there's a lot of subsets of this which are also ridiculously large and infinite. So let's just jump right in, this symbol, [2, 3.1]. This is an infinite set, but if an infinite set has got a finite bound -- we'll talk about how to describe what this is -- this is equal to the set of all numbers X in R, which satisfy two conditions. First, X has to be greater than or equal to two, and X has to be less than or equal to 3.1. In other words, to draw this on the real number line, here's two, here's 3.1, and X is trapped in between these two boundaries but it can hit up to both. So X is any number in the world as long as X is greater than or equal to two, less or equal to 3.1. So let's name some things in here. For example, 2.3 is in [2, 3.1] because two is less or equal to 2.3, and 2.3 is less or equal to 3.1. Three is in there, also 3.1 is in there, but one is not in the closed interval from two to 3.1, because one is not in fact less or equal to two even though it is actually less or equal to 3.1, well it's not greater or equal to two. OK, so that's a closed interval. Let's introduce the next idea. Suppose I give you (5,8) and here I use parentheses instead of those bracket symbols. This stands for an infinite set, the set of X in R, such that X is strictly greater than five and just strictly less than eight. So, the way we note this is, here is zero. We make a little open symbol for five, little open symbol for eight, then we just take all the things in between. So the idea is you have to be between five and eight but you can't hit up against those end points. So for example, 5.5 is in the open interval from 5-8, so is 5.0001 is in the open interval from 5-8 but sadly five is not in the open interval from 5-8, because five is not less than five even though it is less than eight. So you might want to think, by the way, what's the difference between the closed interval from 5-8 and the open interval from 5-8? They differ in exactly two numbers. They differ in five and eight. Five and eight are in the top one and not on the bottom. Okay so those are two extremes, here's two things in the middle, which we call "half-open intervals". Let's take for example, (-7.1,15]. You might already be able to guess this. On the open side, that means we use a strict inequality, and on the other one we use less than or equal to. This is an infinite set. Set of all X in R such that -7.1 is strictly less than X is less than or equal to 15. So how am I be drawing that, here is an open -7.1. There is zero, just so we know where we are, and there the closed 15 off the scale and all that stuff in there. Okay, we'll take the other extreme. So let's say for example, [20,20.3). This will be the set of all X in R plus the 20 is less three or equal to X and less than 20.3. Draw again the real number line. Here's my zero, let's see here's the 20 and here is an open 20.3. There's the stuff in here. But a little point to make, in some sense this seems really small, 20 to 20.3 is really tiny on the real number line compared to -7.1 to 15. It's got infinitely large number of numbers in there. That's the hilarious thing about the real number line. There's a lot of fancy math which you will get into behind it. We've seen closed intervals, like [2, 3.1]. We've seen open intervals, like (5,8). And within two species of half open intervals, like (2,3] and like [20,20.3). Sometimes if we want fancy vocabulary, the first of these half open interval is called left open, this is called right open, that doesn't really matter. OK, let's show you one more slightly more exotic form. Suppose we write, close_two_comma_infinity. This just stands for the set of all X in R, such that X is the greater than or equal to 2, full stop. You don't have to be less than infinity because every number is less than infinity. We often draw that on the real number line, here is zero, there's a two and we just take all the stuff here, kind of going on forever. This is often what we call a "ray". You could also have for example, a minus_infinity_ to_7.1_open. This is the set of all X in R, that should be X is less than 7.1, and you get the idea. Okay, let's close by tying in to the algebra we recalled in this video. We're already comfortable with the idea that if someone asked you to solve for X, and X+5=10, you do some algebra and you solve that X equals five. So X=5 is the answer, a number is an answer. Suppose on the other hand, someone gives you the following problem: Tell me everything you know about X if the following is true; 1_is_less_or_equal_to_X_plus_five_is_less_than_ten. So notice here, a single number is not the answer. For example, if X=4, then 4+5=9, nine is less than 10, nine is greater than or equal to one, but 3.9 would also work. In fact, it turns out that the answer is an interval. If we do a little bit of algebra, let's subtract five from all sides of this. Let's subtract five from the left side, I get -4 is less than or equal to, subtract five from the middle I just get plain old X that's why I subtracted five, that wasn't random. Subtract five from the right, I get 10 minus five or just five. In other words, the first puzzle tells me that the answer is any X in this range. So in other words, as long as X is in the half open interval from [-4,5), that's the answer. That tells me, any X in here tells me, that this up here is true. OK, that concludes everything.ive or just five. In other words, the first puzzle tells me that the answer is any X in this range. So in other words, as long as X is in the half open interval from [-4,5), that's the answer. That tells me, any X in here tells me, that this up here is true. OK, that concludes everything.<br>

## Sigma Notation - Introduction to Summation
we often use for sigma this big Greek letter, sigma, which kind of looks like a big pointy S. And as always in these lectures, the point is not necessarily to bombard you with computations or to judge you on right or wrong answers. But simply to demystify and explain notation, which would otherwise be mystifying. So what we're going to do in this lecture is work through three examples. Each one of them an example of sigma notation, each one of these things here. The sum from i = 1 to 4 of i squared, the sum from i = 1 to 5 of 2i + 3 and the sum from j = 3 to 7 of j over 2. These are all just fancy ways of writing numbers. In fact, tell you the answers in advance, this first number equals 30, the second number equals 45 and this last number equals 25 halves. How on Earth did I know that? Point of this lecture is to learn why that's true. Let's dive in to do the first one. We're going to compute the sum from i = 1 to 4 of i squared. What I'm going to do is just do this myself first, and then walk you through and unpack, how I did that. Okay, so the sum from i = 1 to 4 of i squared is equal to 1 squared + 2 squared + 3 squared + 4 squared. Okay, so suppose someone paid me to do this problem, I'd consider myself done. I've worked it out, I've translated it from sigma notation to something someone who knows arithmetic could do. A person that is really a stickler for details, they're going to say well keep going, but I'm going to say, maybe you need to pay me more money. After we're done with that negotiation, we'll say, okay, from here, it's arithmetic, that's just equal to dot dot dot. The dots covering up the fact that I've done this in advance. This is equal to 30, the answer we saw before. But the real point of today's lecture is to understand this first equals sign. How on Earth did I know that this funny symbol, the sum from i = 1 to 4 of i squared is equal to 1 squared + 2 squared + 3 squared + 4 squared? Okay, so let's walk through that. The first thing to realize looking at this symbol is there's a bunch of things. First, there's a counter in here, there's a symbol in here i squared. That same person walking out to me on the street is pretty annoying by now says, I'll give you ten bucks if you tell me what i squared is. No deal, it's not really a fair question. I know what i is, but actually I had some hints. Down here at the bottom, I know how to start my range of i. I know that I should start from i = 1, and at the top, I know that I should finish when i is 4. Okay, so let's do some scratch work and work that out on the side. Here I have i = 1, here I have i = 2, here I have i = 3 and here I have i = 4. So you'll notice that starting range, starting from 1, that finishing range ending at 4. And actually there's something here that's a little unfair, nothing in the symbol tells me that I count by one, going from the bottom of my range to the top of my range. That's okay, that's sort of a cultural agreement. You start from the low i, you end at the top i, and you count by one. Okay, fine, so what do we do? To each one of these i's we do what this thing in the middle tells us to do. In this case, this thing in the middle, very bossy, tells us to square i. So if i = 1 then i squared = 1 squared. If i = 2, then i squared = 2 squared. If i = 3, then i squared = 3 squared. I think you get the hang of it. i = 4, and i squared = 4 squared. Okay, we've done the scratch work on the side. What do we do next? Well sigma, What you ought to think about this is equal to sum. Meaning, we take all of these answers here and we add them up. And that's how we get what we get up here. We've computed on the side that 1i = 1i squared = 1 squared and so on, and then we add them all up and get our answer. For those of you who are sort of business minded you can think of this as a process. Which can be broken up into parallel processes undertaken by different workers. So one worker can compute what 1i = 1. One worker can do 1i = 2. One might i = 3. One might i = 4, doesn't really matter when they do them. They do them at the same time in parallel. The end of the day, they compare their answers. The last worker adds them all up, and we get the answer we get over here, or over here<br>

## Sigma Notation : Simplification Rule:

Okay, welcome back everyone. Last video we did some elementary examples of sigma notation. Today we're going to make it a little bit more complicated, and we're going to go over some rules, For manipulating,
<br>
Slash simplifying, Or making for complicated, if you like, sigma notation.
<br>
I'm going to start with our first rule, it’s just an example. Last time, remember, that we worked through that the sum from i=1 to 4 of i squared was 30. But now we're going to give you a different problem, which when you think about it is not going to be too different. The new problem is going to ask you the sum from i=1 to 4 of 3i squared. Now in fact, we could work this out directly, just as we did before. Make our little scratch work with our i and add it up. But let's work through this just enough so that we can see the pattern, see the point of this example. So if we work this out, this is equal to 3 times (1) squared + 3 times (2) squared + 3 times (3) squared + 3 times (4) squared.
<br>
Now again, to the guy who's paying us to do this, we're done, you can make that into a number. Let's do that a little bit further, just for our own purposes. If we use some stuff from elementary mathematics, namely something you may remember as the distributive property, multiplication over addition, let's pull out the 3. This Is equal to 3 times [1 squared + 2 squared + 3 squared + 4 squared].
<br>
That's equal to 3 times our old friend, which we're now getting pretty bored of, as we do with old friends, the sum from i=1 to 4 of i squared.
<br>
So
I started off with an expression, the sum from i=1 to something. And internal here to the thing inside the sigma notation was an expression 3i squared that had a constant in it, namely 3. I can pull that constant outside and get that the sum from i=1 to 4 of 3i squared is the same thing as 3 times the same exact expression, but without the 3 sitting there.
<br>
Turns out this is a general rule.

Let's try one more example, if I did the sum,

From r=4 to 25 of 18 r cubed, I really don't want to work that out. But I can tell you this is the same thing as 18 times the sum from r=4 to 25 of r cubed, whatever on earth that is.
<br>
And this is always true.

Whenever you have an expression with a constant inside the sigma, you can pull it outside, and just then evaluate it.

Why is this true? There's something from elementary mathematics which you may or may not have heard called the distributive property.

Namely, if you have A times (b + c) that's the same thing Ab + Ac. And all we're doing is we're taking this expression and we're doing it over and over again with the sigma notation.
<br>
Okay, so that's lesson number one, that's one way of simplifying sigma notation expressions.
Play video starting at :3:50 and follow transcript3:50
Let's give you a new problem.

The sum from i=1 to 4, and internal here we're going to have i squared plus 2i.
Play video starting at :4:3 and follow transcript4:03
So let's just work this out directly. So this is equal to 1 squared + 2 times (1) + 2 squared plus 2 times (2) + 3 squared + 2 times (3) + 4 squared + 2 times (4). And again we could say we're done, down tools, that's it. But let's break this up for our own purposes. Notice in this sum we have terms that look like two different things. One looks like things squared, like these ones. And one looks like two times things, like these. Let's break those up and write those separately.
<br>
This is the same thing as being equal to (1 squared + 2 squared + 3 squared + 4 squared) + (2 times (1) + 2 times (2) + 2 times (3) + 2 times (4)). Let's pause for a second and remember why that's so. Basically it's so because I could add numbers in any order I want. Someone told me to add them the way I have up here, but I can add them the way I have down here, I'm just shuffling them around.
<br>
Why did I do that? Well let's recognize, what's this guy here?

That's equal to our old friend, the sum from i=1 to 4 of i squared.

Fine, what's this guy here? That's equal to a new friend, that's equal to the sum from i=1 to 4 of 2 times i.

Notice we have a rule here, I started off with the summation and then there's something inside the summation which was broken up into two different things, i squared + 2i. I can fragment that, break that up into two different summations, should I want to.
<br>
Why is that true? It's true because when you add up things in any order you want.
Play video starting at :6:4 and follow transcript6:04
Okay, let's do our last rule here. This one seems really silly and really simple, but it makes you think about it a little bit. Let me give you the sum from k=1 to 10 of 5. Seems like a trick question. Notice the thing in the middle has no dependence on k. What do we do? This is almost convention, this is equal to, each time I evaluate something I'm going to evaluate it from k=1 to 10. But I don't do anything with k, I just write down what’s in there. This is equal to 5 + 5 + 5 +, plus, plus, dot, dot, dot, dot, + 5. How many of them? 10 of them.
<br>
So this is equal to 10 times 5 = 50.

The general rule here, whenever you’re summing up a constant, in this case it's 5, but it could be anything. You just add up that constant the number of times you're supposed to do. So for example, the sum from r=1 to 7 of 8 would be 8 + 8 + itself 7 times.
Play video starting at :7:17 and follow transcript7:17
This is the same thing as 8 times 7 or 56.























