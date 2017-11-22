# Free AIML Files
Free AIML Files from Mitsuku Creator Square Bear a.k.a. Steve Worswick

### 20q.aiml
This AIML allows your bot to play 20 questions with your users. The bot thinks of an object, and the user asks 20 yes or no questions to try and determine what it is. However, it's a trick because the bot randomly says yes or no until the user gives up! It's just a bit of fun, some of the user's responses are pretty funny once they realise what's happening.

### Battledome.aiml
A (very) basic battle type game similar to those you see in Dungeons and Dragon type games. Say "BATTLEDOME" to get it going then just keep saying "FIGHT" to fight the various monsters. Someone may be able to incorporate it into an adventure game.

### Binary.aiml
Allows your bot to convert any number from 0 to 255 into binary. A bit geeky perhaps but you will be surprised at what a chatbot gets asked.


### Blackjack.aiml
A casino style blackjack game. You can't split or take insurance like a casino but everything else is there. Say BLACKJACK to start the game.

### Bornin.aiml
Last update: 25th January 2012

The bot can work out your age if you tell it what year you were born.
It covers 1800-2012 and will stop awkward replies like:

Human: I was born in 1970.
Bot: Do you still live there?

Now the bot replies like this:

Human: I was born in 1970.
Bot: So that makes you about 42 years old?
Human: If a man was born in 1934, how old would he be?
Bot: It is now 2012, so I would say 78 years old.
Human: If I was born on February 23, 1980 how old am I?
Bot: Your birthday is February 23 1980. So that makes you about 32 years old? Hmm. You are 32. Yes?

This file will need amending each year.

### Botcompare.aiml
A function that allows a Pandorabot to compare two values to see if they are the same. Say BOTCOMPARE X XSPLIT Y to compare X and Y and it will set a variable called "match" to equal YES if they are the same and NO if they are different.

### Calendar.aiml
Say "CALENDAR" to your bot and it will display the current month's calendar for you. Thanks to Ciprian Murariu for including the formatting. This may display incorrectly for flash enabled bots.

### Chatbots32.aiml
This contains the categories I used in my presentation at the Chatbots 3.2 conference in Philadelphia on how to use databases in AIML. If you want to try and set something similar up yourself and need assistance, please mail me using the contact page.

### Copyme.aiml
If the user asks your bot to repeat what they say (which happens for some strange reason), your bot can now do exactly that. It will carry on repeating them until they say "Stop copying me" twice, much to the annoyance of the users!

### Currency.aiml
The bot knows what currency is used in what country.

### Daystoxmas.aiml
How many days to Christmas. (I created this for my Santa bot).

### Drphil.aiml
A personality test that I got through email and converted to AIML. 
Say PERSONALITY TEST to start the test.

### Gender.aiml
Last update: 3rd May 2010

The bot now knows the gender of a first name. This stops people from saying things like, "My name is Eric. I am a girl". It can also answer what sex the user is from their first name.
This file is updated regularly as I find new names.

### Hangman.aiml
This is the start of a hangman game I created in AIML. I was going to finish it and include it in my Loebner Prize entry but decided against it. If anyone wants to finish it, it is nearly complete and just needs a game over when the lives hit zero, as well as many more puzzles. If you do finish it, please let me know. Say TEXTHANGMAN to start the game.

### Happy.aiml
The bot can correct the user if they get dates such as Valentines Day, Christmas or the bot's birthday wrong. You will need to amend the first few categories to get it to work with your bot's birthday. It defaults to January 2nd (Mitsuku's birthday).

### Highroller.aiml
A version of the dice game Yahtzee by Milton Bradley games. Say "High Roller" to start the game..

### Horoscope.aiml
Turn your bot into Mystic Meg. Say HOROSCOPE to reveal your future!

### Howmany.aiml
Many visitors will try and trip your bot up by asking questions like "how many legs do 3 ducks have". This AIML file will help your bot to answer these questions.

### Jokes.aiml
A few jokes for your bot to tell. They are all clean.
Say TELL ME A JOKE to display a random joke.

### Knockknock.aiml
Some knock knock jokes. Some are better than others but they are all clean. You will need to put the words "KNOCK KNOCK" into your pickup lines for the bot to say a random knock knock joke.

### learn.aiml
Last update: 28th April 2011

This allows users to teach your bot new facts rather than just correcting its replies using badanswer.aiml. The user should say LEARN then the fact. For example:

Human: Learn the sun is hot
Bot: Ok I will learn that the sun is hot.
Human: Learn London is in England
Bot: Ok I will learn that London is in England.
Human: Learn a cat has four legs.
Bot: Ok I will learn that a cat has 4 legs.
Human: What has 4 legs?
Bot: a cat.
Human: What is the sun?
Bot: hot.
Human: Learn the sun is hot and yellow
Bot: Ok I will learn that the sun is hot and yellow.
Human: What is hot and yellow?
Bot: the sun.
Human: What is the sun?
Bot: hot and yellow.
Human: Where is London?
Bot: in England.
Human: What is in England?
Bot: London.
Human: Learn Dr Wallace is an AI expert
Bot: Ok I will learn that Dr Wallace is an AI expert.
Human: What is an AI expert?
Bot: Dr Wallace.
Human: Who is an AI expert?
Bot: Dr Wallace.
Human: Who is Dr Wallace?
Bot: an AI expert.
Human: What is hot?
Bot: the sun.
Human: What does a cat have?
Bot: 4 legs.

Update: I have amended this file so it can learn languages like this:

Human: Do you speak Polish?
Bot: No. Can you teach me a few phrases in Polish.
Human: czesc means how are you in Polish.
Bot: Ok I will add that fact about czesc to my database.
Human: what is czesc?
Bot: how are you in Polish.
Human: what is how are you in Polish?
Bot: czesc.
Human: Do you speak Polish?
Bot: I was taught that czesc means how are you in Polish.
Human: czesc
Bot: I am fine, thank you. Yourself?

### Luckyslots.aiml
A fruit machine game with hold feature. Say LUCKYSLOTS to start the game.

### Maths.aiml
Some maths trivia. Suitable for when someone queries your bot about maths.
Say MATHS FACT to display random maths trivia.

### Numberdrop.aiml
An addition game where you have to make a row of numbers add up to the total.
Say NUMBERDROP to start the game.

### Numberones.aiml
Last update: 25th January 2012

This file will allow your bot to display the UK number one hit single for any date from the 14th November 1952 (when the charts began) to the current day. This is popular for chatters who wish to know what the nuber one was on their birthday.

If anyone wishes to convert it for the US Billboard charts (or any other country), please feel free but I would like a copy if you do so.

It can handle the date input in most formats. Here is an example:

Human: What was number one on 16th September 2003?
Bot: According to my records, the UK number one hit single on 16th / September / 2003 was Black Eyed Peas - "Where Is The Love?".

This file will need amending each time there is a new number one, so keep checking back for updates.

### Onthisday.aiml
What happened on this day in history. It's mostly English facts but feel free to amend them for whatever happened in your country. Say "ON THIS DAY" to show the history of the current day or enter a date in the format "month day" eg "JANUARY 23", "MARCH 07" to display the history of a specific date. Note the zero at the beginning of dates with a single digit.


### Poker.aiml
This file enables your bot to play a game of "Jacks or Better" video poker.
Say 5CARDPOKER to start the game.

### Quizfacts.aiml
Pub quiz style trivia. "When was the battle of...", Birthstones and things like that.
It still needs completing but there's plenty of trivia in there.


### Seasons.aiml
Your bot can tell which season it is both north and south of the equator.

### Shutup.aiml
Fed up of users telling your bot to shut up?
Now the bot refuses to talk to them unless they say sorry.

### Tictactoe.aiml
Tic-tac-toe (or noughts and crosses as we Brits call it). Say TICTACTOE to your bot to start the game. I've coded it so it plays perfect strategy. This means you will either lose or draw to it. However, if anyone does manage to win it, please let me know how you did it!

This may display incorrectly for flash enabled bots due to the HTML code in the table formatting. If it does, just amend the DRAWGRID category to something simpler.

### Warnings.aiml
This file will give your users 5 warnings before temporarily banning them from talking to your bot. Just add <srai>addinsult</srai> to the start of any categories such as "f*** off", "will you have sex with me" or any other categories you don't want your users saying.

The users can also ask "how many warnings do I have" to check on their status.

### Whatday_eng.aiml

Works out the day of the week from any date between 1753 and 2299. It will also give the chatter some facts about what happened on that day in history too if you upload my onthisday.aiml file to your bot. Say WHATDAY to begin the script.

### Whatday_usa.aiml
Same as whatday_eng but more suitable for the US bots who format the date as mm/dd/yyyy.

### Wordplay.aiml
An anagram game. Guess the jumbled words. Say WORDPLAY to start the game.


### Yomama.aiml
A load of "yo mamma" type jokes for when the user starts insulting the bot's mother.

### Zbert.aiml
A fake admin menu. It's surprising how many people try to "reformat" the bot. If you get your bot to drop a few hints every now and then that the password is "zbert", people will soon pick up on it.
