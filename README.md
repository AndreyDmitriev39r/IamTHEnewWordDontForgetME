# IamTHEnewWordDontForgetME

### Description

Application for non-native English speakers to better memorize new words.

### Concept:

I am not native English speaker, and though my English is somewhat decent, I encounter new words on a regular basis.
Sometimes I memorize and begin to use such words right off the bat, but many words is forgotten because they are used on a rare occasion or for any other reason.

That said, I will build an application that will allow me keep track of my new vocabulary and look up some encountered words when I see fit.
*Note: having such application could have positive emotional side-effect I think: sometimes process of learning new words is associated with fun memories, it’s nice to refresh such memories*

I will start small with just a couple of basic features, and will consider additional features when basic features will be implemented, tested and some feedback will be received.


### Features:

1. User should have an opportunity to input new encountered word and translation for it.
2. List of words should be stored in file/database(need to do more research on this one) in format {word in English : word in native language}.

*Note for future features: consider to store/get from user more data associated with each word: date when word was encountered, maybe context, website where it was encountered etc. Some data can be provided automatically(date/time when user added new word)*
*Consider to find various ways to perform such data to user:*
*for example, with dates we can perform some charts and user will have some stats: yesterday I encountered 12 new words, and in last month 50… something like that*

3. User can request either random English word from application or user can specify which word they want to get from app.Word will be provided without translation first: user should have an opportunity to recall it on their own. However, translation will be provided if user will make additional request.

4. User also can request random/specified word with translation right away.


### Possible future features based on feedback

Make it so the app takes a word, a definition, and an example sentence from the user (or you could use an API to let the app grab the definition and the example from an online dictionary).

The app shows 5 (just an arbitrary number) random words along with their definitions and examples in a single card, sort of like a flash card.

There should be buttons on the card to let the user choose another set of 5 words.

There should be a section to let the user test his/her knowledge.

The test section should display some definifitions. Each definition should have multiple options (e.g., 4).

The test section should store the data about the words the user has correctly identified as well as the ones the user failed to remember.

The words that were not correctly matched to their definitions should have a higher priority and be put in the tests more often.

There should be a chart showing the users the words he/she had the most trouble recognizing.

