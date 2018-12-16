# Oscar Guillen. December 2018.

# Digital Reading and Digital Writing: A Final Reflection

Digital Reading and Digital Writing. Honestly, I enrolled in this course because I was late to selecting classes, and there were no other first-year writing classes that interested me whatsoever. I am currently on track to be a computer science major, and the word “digital” in the name was enough to get me to sign up. Throughout the duration of the course, I acquired knowledge in the benefits of using a text editor as opposed to a word processor, utilizing a free online software tool called GitHub, and the practicality of using the Scala programming language to further analyze a piece of text in ways I was previously unaware of.

I was tasked with reading the opinionated article entitled *Word Processors: Stupid and Inefficient* by Allin Cottrell. I never thought about alternatives to Microsoft Word, nor questioned its limitations. Cottrell initiates his claim by stating that word processors are typically promoted by major vendors at a significant asking price, while better, lesser-known alternative methods are available to use for free. Moreover, Cottrell claims that WYSIWYG (“What You See Is What You Get”) word processors, in which text is “continually typeset as you key it in,” is actually a curse rather than a convenience because the author is both “distracted from the proper business of composing text… when [they] should be concentrating on content” and the word processor “sacrifices quality to the speed required for the setting and resetting of the user’s input in real time.” Furthermore, word processors “do not have the right to be a standard for document preparation” since they are far less efficient than other readily-available alternatives, and Microsoft is merely trying to create a quasi-monopoly which “piggybacks off the Microsoft Windows quasi-monopoly,” and this does not include the fact that Microsoft consistently urges its Word users to “upgrade” to newer versions, as potentially important Word documents written on newer software may not be compatible with older versions of Microsoft Word.[^Cottrell]

[^Cottrell]: Cottrell, Allin. “Word Processors: Stupid and Inefficient.” Towards a New Socialism, 29 June 1999, ricardo.ecn.wfu.edu/~cottrell/wp.html.

From my experience, Atom and GitHub were far better options when it came to highly organized file sharing when compared to Word. I will admit: it does take much longer to set up than Word, and it might not be as user-friendly at times, but I am willing to overlook those shortcomings when it comes to the numerous tools available in Atom, from customizability to organization to the low, low price of free.

Another piece of software I was previously unaware of prior to taking this course was the world of GitHub. I never knew about how useful it was until Mrs. Blackwell visited us one class period and told us about file sharing without the organizational headache of sending hundreds of emails resulting in thousands of file versions floating around hundreds of people. Granted, she did not display GitHub, but our professor made the connection between the software her company uses and GitHub. Both had the capacity to be used by hundreds, if not thousands, of people at once while keeping everything in an organized fashion. Where GitHub really shines is its ability to keep file histories with comments in a well-designed manner. Whereas I would previously have stacks of emails worth of files I would send to professors every time a version was due, I would now be able to save myself the inbox clutter and replace it with a clean user interface on GitHub.

Nearing the end of my time in the course, we finally had the chance to create and test a phrase and word compiler of our own creation using the Scala programming language. As with text editors and GitHub, I also learned about the intricacies and usefulness of making a digital edition. I learned about taking basic steps in a virtual machine using Git Bash to load my text by Nepos into a string and splitting the text into individual sentences. From my understanding, we meticulously followed numerous steps to create a corpus of text in Atom and address it the value sentenceCorpus. From within the shell, we booted up SBT Console and used the command sentenceCorpus.ngramHisto(X,Y), wherein X would be the input for number of words you want displayed for each result at a time and Y would be the minimum frequency with which the word must appear within the text to appear in the list. Experimenting on my own, I typed sentenceCorpus.ngramHisto(1,5) into the shell, and a list showing single words that appeared more than five times displayed. From this list, I can glean information about the text I would not be able to get by reading it alone. For instance, in searching for uncommon words, the word “Phocion” appears nine times, “people” appears eight times, and “Athens” appears six times. From this, I can derive that the text is primarily about Phocion, a once-great leader revered and praised by the people of Athens. Continuing, I typed sentenceCorpus.ngramHisto(2,2) into the shell, and the most popular uncommon word combinations from that list were “the people” showing up seven times, “the Piraeeus” showing up four times, “his life” showing up three times, and “the city” showing up three times. From these results, I can deduce that the text speaks of his life, the life of Phocion, within the city of Athens, and his relationship with the people of Athens and Piraeus, the selected port city of classical Athens whose history dates to ancient Greece.[^Greece]

[^Greece]: At. “Piraeus Greece, Piraeus Port of Athens.” Piraeus Greece, Piraeus Port of Athens, piraeus-greece.org/.

Digital Reading and Digital Writing is one of the most interesting and unique classes I have ever taken. I came into the course not knowing about the vast amounts of free and readily-accessible tools designed to enhance the experience of writing on a computer. After years of using Microsoft Word, Atom is now my go-to text editor to complete written assignments. The GitHub community has helped me immeasurably in both my first-year writing and computer science courses. I now have experience in the Scala programming language. Having taken the course, I am a smarter, more skilled student now than I was when I first started.

# Bibliography

1. Cottrell, Allin. “Word Processors: Stupid and Inefficient.” Towards a New Socialism, 29 June 1999, ricardo.ecn.wfu.edu/~cottrell/wp.html.
1. At. “Piraeus Greece, Piraeus Port of Athens.” Piraeus Greece, Piraeus Port of Athens, piraeus-greece.org/.