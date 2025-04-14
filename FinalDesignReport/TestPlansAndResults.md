Testing a Game is difficult. This is why game developers are often spending lots of time fixing bugs and pushing
changes after a game has been released. Therfore, due to the scale of our games, we could afford to do manual testing.

Godot uses GDScript as an scripting language to be able to control objects. That being said, game testing is not
really viable in GDScript and we must use C++ or other langauges. With that being said, it was hard to make tests for
each different features since it required using another language to test.

To solve this issue, we decided to rely on manual testing. This comes from the fact that the game is not too big. It
has GUI Components and Gameplay Component.
    - For the Gameplay component, we decided to Playtest the game and figure out bugs as it goes. For example, we would
    play the game and if sometimes unexpected occurs due to some combinations of buttons, we would go to fix that. Using this techinique, we located and fixed my bugs but many more will remain due to the nature of game fixing being difficult.
    - For the GUI component, we tested combinations of clicking on certain buttons to see what it does, waiting for some time before clicking a button, pressing invalid buttons and so on and fixed many issues that resulted from that.

Using this techniques of manual testing, we isolated and fixed many bugs.