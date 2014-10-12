---
title: Incremental Reading 1
author: Christian Broomfield
date: 2014-10-12
template: article.jade
---

An introduction into the wonderful world of spaced repetition and incremental reading.

---

# Incremental Reading

If you've ever experienced or practiced something called *spaced repetition*, then you might have stumbled across the nebulous *incremental reading* before. Spaced repetition is a fancy term for using flashcards to retain pieces of information over long stretches of time, usually measured in years. It does this by *spacing* each flash card out according to how well you remembered it the last time you saw it. Conventional software allows you to rate your answer to a flashcard from *Poor*- repeat within a few hours or days- to *Great*- repeat only within the next weeks or months. 

*Incremental reading* is seen as something of an extension to spaced repetition. You need to create those question/answer flashcards from a source of information, usually articles, books and other forms of media. Instead of perusing a text, writing your little flashcard, and then reviewing *just* the flashcard, incremental reading brings the entire process into one workflow. You import the entire article into your spaced repetition program and read it as if it were a flashcard- it's in what is called the study queue and presented using the same spacing algorithm as the flashcards.

As you read the article within your program, you can highlight text to create questions on the fly. These questions have many benefits, such as being tagged or linked to the source article, or able to appear in context of the article or on its own. Of course, just reading my description of spaced reptition can seem vague and unintuitive, especially if you haven't tried spaced repetition at all! Instead, let's look at some pictures.

Spaced reptition flashcards consist of a question and answer portion:

![A simple flashcard mockup. The top side has a question 'Who was the first president of the United States?' and the bottom side is a button to reveal the answer.](http://i.imgur.com/Et7n2DO.png)

You should honestly attempt to answer the question without looking at the answer. Once you've made your guess, you click on *Show Answer*.

![A flashcard with a revealead answer and four buttons to gauge how easily the answer came to you.](http://i.imgur.com/94QjqqP.png)

As the honest individual I'm sure you are, you now evaluate how quickly you were able to come up with the solution. If it took no effort at all, you click *Immediate*, otherwise *Correct*. If you failed to come up with an answer, but at least made a guess, you press *Incorrect*, otherwise *Total Blank*. These buttons help the spacing algorithm determine when this card should be presented again.

Let's assume I created this question because I [read the Wikipedia entry on George Washington](http://en.wikipedia.org/wiki/George_Washington). Faithful to most current spaced repetition software, I continue reading from the browser directly and inputting any relevant information into my program as necessary. Not only does this create needless software and mental context switching, I often have to type in the information a second time. As with most things that humans do manually, a machine could do it much, much better :) Here's how:

We first import the article into our program.

![Importing the George Washington article into our theoretical incremental reading program.](http://i.imgur.com/aP52IOD.png)

Notice that the layout, and buttons, have changed. We can easily navigate, highlight, and modify the text as we see fit. If, for instance, there is a sentence we find particularly important, then we can click on *remember* to create a *text fragment*.

![We remembered a fragment of George Washington's wiki article and can now format it.](http://i.imgur.com/IJMuohU.png)

If we think the article is too dense, too sparse, or missing any context clues relevant for our understanding of this fragment on its own, then we can edit it until it's just perfect.

![A slightly edited fragment](http://i.imgur.com/c33JD5b.png)

This fragment is now ready to be launched into the study queue and will be brought up alongside the rest of your flashcards. It can be repeated sooner or later depending on how important you rate the fragment, or even forget it if its importance is void.

![The fragment is now part of the study queue and you can choose to see it again sooner, later, or never again.](http://i.imgur.com/wKJPyJW.png)

So much for remembering fragments. What if you want to format a piece of information as a question? Instead of just extracting a text fragment, you'd like to give yourself a flashcard. Great! Let's do just that. We just need one extra button for our *Remember* context.

![We just clicked *Remember* again to extract a text and prepare it for questions.](http://i.imgur.com/LdTeijK.png)

As you can tell, it's almost identical to the previous *Remember* context. All that's changed is that we added an extract button at the bottom. For the sake of simplicity, this button lets us create questions out of our fragment. What happens if we highlight the words "United States Consitution" and then hit *Extract*?

![We just hit extract on the words "United State Consitution" and turned it into a flashcard.](http://i.imgur.com/fcyJ7K6.png)

Not bad, not bad at all! It could use some reformatting and simplifying that we did in the previous *Remember* example, but otherwise it's a perfectly decent flashcard. What's more is that we didn't need to type all that information again (the repetition will hammer that information into our brains whether we'd like it or not) and we have a direct reference to the source article within the flaschard! If we feel that the answer or question could be improved, it's just a hop and skip away from the original article to gather more information or context.

Personally, I find this quite elegant. It lets us remember information in tiny, appreciable chunks that we can blaze through within seconds. The information isn't lost, it's instead repeated again and again until it has been imprinted on our minds. While learning through rote isn't always the best answer, it's still useful for a great many things. Most spaced repetition programs focus on language or dictionaries of words in the medical or law fields. These are natural fits for flashcards, but what if you're a Computer Science student in an Operating Systems class reading through the latest copy of "Operating System Concepts" by Silberschatz et al? The answer, at least in my opinion, is through incremental reading. Effortful, dedicated learning and retention of important concepts as fragments, flash cards, and the articles themselves.

Over the course of the next couple of articles I'll try to detail good spaced repetition practices and give insights on the development of just such a proposed incremental reading program. All source code will eventually be found on my github page, but the project hasn't officially passed the design phase just yet :) I hope you enjoyed the read and feel free to [drop me an email if you have any questions or comments!](mailto:christian.broomfield@posteo.de)