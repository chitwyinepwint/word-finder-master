##Word Finder

I took every english word (over 200k words) and built a little NodeJS
app that will help you find words that contain specific characters.

Additionally, here are instructions to deploy this app to Heroku.

##How to Use

###The underscore

Type a word into the text box with the following pattern:

    he__o

And you'll get words such as:

    hello
    helio

###The question mark

This character is great for games like What's the Phrase (a knock off
of Wheel of Fortune)

Type a word into the text box with the following pattern:

    st???

and you'll get words such as:

    stack
    stade
    staff
    stage
    stagy

but you wont get words like

    start

because the `t` would already be visible (in What's the Phrase), and
you would have typed:

    st??t

