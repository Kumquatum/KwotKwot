# KwotKwot

IRC bot for the [bioinfo-fr.net](bioinfo-fr.net "bioinfo-fr.net") chan (#bioinfo-fr on freenode)

Functionality to implement :
- quoting : (that's where this bot idea came from) select last X sentences or more accurately select block of sentences by giving start and end (ex : "a funny ponny" + "after he met the horse" even if it's note in the message from the same personne)
- ping me when ... : ask KwotKwot to ping you when someone comes back, for a date
- left message : (could use some code from 'ping me when...') pass message by mp or in chan for someone as soon as it connects (and maybe add a confirmation of lecture to manage those who connect/disconnect often and lose their logs)
- propaganda : welcome any new head on the irc chan (with some ip checking in order to avoid spam), often remember we need mor blog articles (could be funny to trigger when there is too many people speaking in a short time)
- whistleblower : built upon 'ping me when...' to notify admins there were probably some forbidden subjects spoken (note : remember to include the forbidden dictionnary into .gitignore in order to avoid those filthy trolls on #bioinfo-fr)
- quizz : use some already coded irc quizz bot and full it with bioinformatics specific questions

