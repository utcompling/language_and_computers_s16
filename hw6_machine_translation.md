---
layout: homework
title:  "HW6"
excerpt: "Homework 6: Machine Translation"
date:   2016-04-07 0:0:00
---

# Homework 6: Machine Translation

**Due**: April 19, 2016

  
### Problem 1 (20 points)

Go to [Google Translate](http://translate.google.com), a site which allows you to type in text and translate it into another language. By copying and pasting you can also backtranslate, i.e., translate back into the original language. 

For this problem, you must translate the following passage (from the book [Arrowsmith](https://en.wikipedia.org/wiki/Arrowsmith_(novel)) by Sinclair Lewis) into three different languages and then translate back into English.

> Watters's house was new, and furnished in a highly built-in and
> leaded-glass manner. He had in three years of practice already
> become didactic and incredibly married; he had put on weight and
> infallibility; and he had learned many new things about which to be
> dull. Having been graduated a year earlier than Martin and having
> married an almost rich wife, he was kind and hospitable with an
> emphasis which aroused a desire to do homicide.
   
For example, this translates into Hindi as:

> wattairs ke ghar naya tha, aur ek atyant nirmit aur laiadaid gilaas
> dhang se prastut kee. unhonne kaha ki pahale se hee abhyaas
> upadeshaatmak aur avishvasaneey roop se shaadee banane ke teen saal
> mein tha; vah vajan aur achookata par rakha tha; aur vah kaee naee
> cheejon ke baare mein jo sust hona seekh liya tha. karane ke baad ek
> saal pahale kee tulana mein maartin snaatak kee upaadhi praapt kee
> gaee aur lagabhag ek ameer patnee se shaadee kar lee hai, vah dayaalu
> aur ek jor jo hatya karane kee ichchha jagaaya saath mehamaananavaaj
> tha.
  
And then this translates back into English as:

> Watters was new to the house, and with the manner of a highly built
> and leaded glass. He already didactic practice and in three years had
> become incredibly marriage; He had put on weight and infallibility;
> And many new things he had learned about the slowdown. After more than
> a year ago Martin has graduated and is almost married a rich wife,
> he's kind and hospitable, with an emphasis which had aroused a desire
> to kill.

So, some things have obviously gone quite wrong.

(a) (5 points) Choose one European language, one African language (not Afrikaans), and one Asian language (not Hindi). Write down the languages, and the English backtranslations associated with each one. Based on the backtranslations, do you think that some languages are better matched with English than others with respect to ease of translation? Give evidence for your answer using the backtranslations as examples. 

(b) (15 points)

Find three lexical or syntactic errors that are apparent from the backtranslations, such as "dull" becoming "slowdown" (lexical), or "light ants on fire" becoming "Watters was new to the house" (syntactic). Discuss why you think they may have come about. Focus especially on words that receive different translations in different languages, or syntactic constructions that seem especially hard.  How "fatal" are these errors for being able to understand the backtranslation (and thus possibly also the translation into another language)?

Feel free to use any knowledge you have of the others languages in answering this (though knowledge of other languages is not required to answer this).  Also, feel free to construct or use other examples of English sentences that you backtranslate in answering this question.

### Problem 2 (40 points)

This exercise deals with word translation probabilities from Tagalog to English.

(a) (10 points)

Consider the examples below:

	1a. the teacher bought a book .
	1b. bumili ng libro ang titser .

	2a. the thing a teacher bought is a book .
	2b. libro ang binili ng titser .

	3a. the teacher said that Linda bought the car .
	3b. nagsabi ang titser na binili ni Linda ang kotse .

Using the bag of words alignment model, provide the probabilities for translating:

 1. *bumili*, *binili*, *libro*, and *titser* given *teacher*.
 1. *bumili*, *binili*, *libro*, and *titser* given *book*.
 1. *bumili*, *binili*, *libro*, and *titser* given *bought*.
 1. *ng*, *ang*, *na*, and *titser* given *a*
 1. *ng*, *ang*, *na and *titser* given *the*


(b) (15 points)

The bag of words model, of course, gets better with more aligned sentences. Here are two more:

	4a. who bought a book ?
	4b. sino ang bumili ng libro ? 
	
	5a. who said that Linda bought the dress ?
	5b. sino ang nagsabi na binili ni Linda ang damit ?

Recompute the probabilities you did for Part A using sentences 4 and 5 in addition to 1-3.

(c) (5 points)

Describe how these extra sentences in (4) and (5) help you translate certain words. (i.e., Which words get easier to translate and why?)

(d) (10 points)

Here are the actual translations (actually, *ng* and *ang* are more complicated than these simple translations indicate, but you don't need to worry about that here):

 * bumili = bought (active voice)
 * binili = bought (passive voice)
 * libro = book
 * titser = teacher
 * ng = a
 * ang = the
  
Which words were translated well using the bags-of-words method? Discuss any problems you see with the translation probabilities you calculated. Can you think of any ways to change the method so that it would create more accurate translation probabilities? (You don't have to actually do it, just suggest possibilities.)

### Problem 3 (15 points)

The English verb "to know" translates into Portuguese as *conhecer* "to be familiar with (a person)" and *saber* "to know (a thing)". For example, *Maria conhece Bill* means "Mary knows Bill," and *Maria sabe a resposta* means "Mary knows the answer."

(a) (5 points) In terms of hyponymy/hypernymy, describe the relationship between the English verb to know and the Portuguese verbs conhecer and saber.

(b) (10 points) *Conhecer* also means "to meet." For example, *ela conheceu ele* can mean "she met him." Draw a Venn diagram showing how the English verbs to know and to meet overlap with the Portuguese verbs conhecer and saber.

### Problem 4 (25 points)

How much do you think language influences thought? Does it determine it, influence it to some degree, or not influence it at all? Give argumentation and evidence for your position. You can use outside sources for answering this question, as well as the course slides. For example, you might look at these:

  
 * Wikipedia's [Sapir-Whorf Hypothesis page](http://en.wikipedia.org/wiki/Sapir%E2%80%93Whorf_hypothesis)
 * Wikipedia's [Framing page](http://en.wikipedia.org/wiki/Framing_%28social_sciences%29)
 * Geoffrey Pullum's [The Great Eskimo Vocabulary Hoax](http://users.utu.fi/freder/Pullum-Eskimo-VocabHoax.pdf)
 * The debate in The Economist about [Language and Thought](http://jhpr.webs.uvigo.es/teoria/Economist2.pdf)
 
You can also consider words in other languages that form lexical gaps in others, and how much work can go into explaining them; for example:

 * Portuguese: [saudade](http://en.wikipedia.org/wiki/Saudade)
 * German: [schadenfreude](http://en.wikipedia.org/wiki/Schadenfreude)
