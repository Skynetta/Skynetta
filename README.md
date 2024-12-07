# Declare characters used by this game.
define s = Character(_("Sylvie"), color="#c8ffc8")
define m = Character(_("Me"), color="#c8c8ff")

# This is a variable that is True if you've compared a VN to a book, and False
# otherwise.
default book = False

# The game starts here.
label start:

    # Start by playing some music.
    play music "sometimes.mp3"

    scene bg lecturehall
    with fade

    "It's only when I hear the sounds of shuffling feet and supplies being put away that I realize that the lecture's over."

    "Professor Eileen's lectures are usually interesting, but today I just couldn't concentrate on it."

    "I've had a lot of other thoughts on my mind...thoughts that culminate in a question."

    "It's a question that I've been meaning to ask a certain someone."

    scene bg uni
    with fade

    "When we come out of the university, I spot her right away."

    show sylvie green normal
    with dissolve

    "I've known Sylvie since we were kids. She's got a big heart and she's always been a good friend to me."

    "But recently... I've felt that I want something more."

    "More than just talking, more than just walking home together when our classes end."

return
