# MysteryFlight
Beer education gamified, guess what hops, yeast or malt are in an unknown beer.  Project from the [Avery IPAs and APIs Hackathon](https://www.averybrewing.com/events/ipas-and-apis-hackathon) held in Boulder, CO June 10-12, 2016.  Our team [U+1F37A](https://docs.google.com/presentation/d/1jr8Z1cBc9G7TnuylHbfCEbJzHBW64ZlOe44RApn06RE/edit?pref=2&pli=1#slide=id.g14e40deaa6_0_66) (Josh, Emily, Liam and Mark) won first place and each of us were awarded a free year of awesome Avery beer.

##Instructions
1. Download APK to android device and install
2. Launch app
3. Tell "Bartender" which flight theme you want and give them phone
4. Bartender privately selects flight theme and writes down (quickly!) the 3 beers in order.  They will display near bottom of screen for 3.5 seconds
5. Hand phone back to "Taster"
6. Taster plays game, selects a numbered beer, uses sensory skills to guess hops, yeast and malt
7. Taster can tweet when each beer is revealed and at end when the entire flight is revealed
8. Repeat, enjoy tasty Avery beer and enjoy!

##Long Description

Mystery Flight allows a user to choose a theme for a mystery flight, that is three beers that only the bartender and the app knows about.  In the hackathon the bartender knew which beers to pour and how to order them through a back end "point of sale" website, but in the app available here in "demo mode" the beers also display in a toast in the app (so hand the phone to a bartender when picking the theme).  Once the beers are poured you are presented with three frosty beer mugs representing each taster.  Pick one (it will be grayed out on subsequent visits to this screen) and then choose your challenge, which are ranked by difficulty and points you can earn.  After smelling, tasting, and using your senses on your delicious taster of beer, choose to identify a hop, malt or yeast in your beer.  Whether you choose correctly or incorrectly review curated educational content about the correct selection on the answer screen.  Next you are brought to the beer detail screen which reveals the beer.  This includes a picture of the beer in bottle or can and many facts about the beer.  You repeat this process until all three beers are completed at which point you are brought to the final screen.  It reveals all three beers.  It also has an option to play again, which brings you back to the theme selection screen.

##Walk through

This is the app that was demo'd on June 11, except the backend it is pointed to has one extra theme: "expert", you can only see this difference on the first screen.

![Walk through](https://github.com/mscheel/MysteryFlight/raw/master/images/walkthroughgif.gif "Walk through")

##Screenshots

These screenshots are from the original app, they do not include updates since June 11, 2016.

![Flight theme selection](https://github.com/mscheel/MysteryFlight/raw/master/images/screen_1_theme_picker.png "Flight theme selection")
![Point of sale back end web page](https://github.com/mscheel/MysteryFlight/raw/master/images/pos-backend.png "Point of sale back end web page")
![Beer Picker](https://github.com/mscheel/MysteryFlight/raw/master/images/screen_2_beer_picker.png "Beer Picker")
![Challenge Picker](https://github.com/mscheel/MysteryFlight/raw/master/images/screen_3_challenge_picker.png "Challenge Picker")
![Answer a question](https://github.com/mscheel/MysteryFlight/raw/master/images/screen_4_answer_question.png "Answer a question")
![Answer revealed](https://github.com/mscheel/MysteryFlight/raw/master/images/screen_5_answer_reveal.png "Answer revealed")
![Beer reveal 1](https://github.com/mscheel/MysteryFlight/raw/master/images/screen_6_beer_reveal_a.png "Beer reveal 1")
![Beer reveal 2](https://github.com/mscheel/MysteryFlight/raw/master/images/screen_6_beer_reveal_b.png "Beer reveal 2")
![Beer reveal 3](https://github.com/mscheel/MysteryFlight/raw/master/images/screen_6_beer_reveal_c.png "Beer reveal 3")
![Congrats](https://github.com/mscheel/MysteryFlight/raw/master/images/screen_7_congrats.png "Congrats")

##Updates

After the hackathon completed we have made some improvements.

* Added ability to tweet from beer reveal and congrats screens.
* Beers are revealed in app now to make it easier to play on phone, hand phone to bartender, tell them your theme, have them select and note the beers (they display for 3.5 seconds) and then give the phone back to you
