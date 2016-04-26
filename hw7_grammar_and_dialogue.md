---
layout: homework
title:  "HW7"
excerpt: "Homework 7: Grammar and Dialogue"
date:   2016-04-20 0:0:00
---

# Homework 7: Grammar and Dialogue

**Due**: April 28, 2016

### Problem 1 (10 points)

(a) [5 pts] Define what open class words and closed class words are.

(b) [5 pts]] For the parts-of-speech *noun*, *verb*, *determiner*, *adjective*, *preposition*, and *adverb*, say whether they are open or closed class, and construct an example sentence that contains at least one word for each part-of-speech. Label the parts of speech below the sentence, for example:

	Clowns smile
	Noun   Verb

(For your sentence, you'll need at least six words to cover all the above parts of speech.)

### Problem 2 (20 points)

The sentence "I saw the man with a telescope" is ambiguous. Given the lexicon below, draw the two derivations for the sentence "I saw the man with a telescope". 

	I := s/(s\np)
	I := np
	man := n 
	saw := s\np
	saw := (s\np)/np 
	a := np/n
	the := np/n
	with := (n\n)/np
	with := ((s\np)\(s\np))/np
	telescope := n

Indicate which derivation corresponds to the man having the telescope and which one corresponds to the speaker using the telescope to see.

a) Provide the derivation that corresponds to the man having the telescope.

b) Provide the derivation that corresponds to the speaker using the telescope to see.

Note: you only need the rules of function application to do this problem:

	Forward application:   X/Y   Y => X (>)
	Backward application:  Y   X\Y => X (<)

Also note that you need to select the appropriate categories from the above lexicon -- you don't need all of them.

### Problem 3 (20 points)

The sentence "the man that I think that Mary saw walks" has a relative clause with a long distance dependency (in which "man" is the thing that Mary sees).

(a) [12 pts] Provide a derivation for the sentence (which must result in "s"). In addition to the lexicon from problem 2, you'll need to use *some* of the following lexical entries:

    Mary := np
    Mary := s/(s\np)
    that := s/s
    that := (n\n)/(s\np)
    that := (n\n)/(s/np)
    walks := s\np
    walks := (s\np)/np
    think := s\np
    think := (s\np)/np
    think := (s\np)/s
  
You will need the composition rules (in addition to the application rules of the previous problem) for this derivation:

	Forward composition:   X/Y  Y/Z  =>  X/Z  (>B)
	Backward composition:  Y\Z  X\Y  =>  X\Z  (<B)

**NOTE**: Give yourself plenty of space on the paper when doing your derivation. Students sometimes try to fudge on problems like this by writing messily and hoping the charitable interpretation is taken -- if we can't read it, you won't get the points. The best thing will be to do the derivation on scratch paper and then copy over the final answer.

(b) [1 pts] Name a derived category from your derivation above that is not also a lexical category.

(c) [3 pts] Name two categories from the lexicons in problem 2 and problem 3a that create direct recursion? 

(d) [4 pts] Why is recursion necessary for analyzing the syntax of human languages?

#### Problem 4 (30 points)

Go to one of the following online chatbots:

- [Eliza](http://www-ai.ijs.si/eliza/eliza.html): an implementation of the classic [ELIZA](https://en.wikipedia.org/wiki/ELIZA) program.
- [Elbot](http://www.elbot.com/): winner of the Loebner Prize in 2008
- [A.L.I.C.E.](http://alice.pandorabots.com/): winner of the Loebner Prize in 2000, 2001, and 2004
- [Jabberwacky](http://www.jabberwacky.com/): winner of the Loebner Prize in 2005 and 2006
- [Rose](http://brilligunderstanding.com/rosedemo.html): winner of the Loebner Prize in 2014 and 2015

Have a conversation with at least 5 turns with at least two of the chatbots. For two chatbots, write down the conversation (include them in your homework submission). Identify instances where each of the four Gricean maxims (Quantity, Quality, Relevance, Manner) were violated by the chatbot during the conversation, saying what the maxim is and how it was violated. Which of the chatbots do you think best obeyed the Gricean maxims?

### Problem 5 (20 points)

Pick one of the following statements and write one to two paragraphs that argues for or against it:

- It would be a great idea to have a voice-activated TV.
- One does not need to understand what is being said in order to carry on a conversation.
- A dialogue system must be embodied to achieve true conversational capabilities.
- The Chinese room argument is right: machines will never actually be able to think because they are just manipulating symbols.

You should use concepts from the dialogue system component, such as (but not necessarily limited to) closed/open domains, depth of analysis, the uncanny valley, turn taking, and emergence.