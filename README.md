# Fungus-QTE-Command
Add an QTE command to fungus games

* [Fungus Game](http://fungusgames.com/) is a Unity3D plugin to make the cut-scenes type developing much more easier.
* QTE(quick time event) is a system that the player needs to press the button within a predefined time in order to trigger certain event.

This is a command plugin which you can use along with fungus to do your own QTE scene.


This command plugin includes the following public variables which you can use to define your own QTE scene:

- Block when failed: When the QTE failed, it will go to this block
- Block when success: When the QTE success, it will go to this block
- QTE Button: You can choose which button should the player press
- Count Timer: How long should the QTE lasts?
- Delay Timer: How long should we wait before the event starts?
- Button Display: A GameObject which will shrink through time when QTE

When the QTE begins, the command will display the GameObject from the **Button Display** on the screen, then the player needs to press the button of the "QTE Button" within the "Count Timer". The size of the button will be decreased over time, in the end it will fully disappear from sight. The player should press the button before it disappears.
