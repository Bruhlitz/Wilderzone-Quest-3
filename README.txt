WILDERZONE - META QUEST 3
==========================

Put the headset in developer mode (the Meta Horizon phone app > the headset > Headset settings > Developer mode),
plug it in, allow USB debugging in the headset, then:
    adb install -r SkiForeverVR.apk
In the headset it is under Library > Unknown Sources. The Quest's own app or SideQuest can install it too.

In the headset you are your pilot: first person, always, with your own suit, arms and legs below you; your arms follow
your controllers, and other pilots see them move. The menus are a big screen in front of you; the HUD is on your visor.
QUALITY has two levels here, LOW (the default: the smoothest frame) and HIGH.
Point the right controller at a menu and pull the RIGHT TRIGGER (or press A) to choose; the left stick
and A work too. The left stick steers, the right stick left and right turns you, and turning your head turns you too.
LEFT TRIGGER skis. RIGHT GRIP jets. RIGHT TRIGGER fires the weapon in your right hand, wherever you point it.
RIGHT STICK UP and DOWN change weapon. A uses your core (the pack). B uses your utility (turret, mine, grenade).
LEFT GRIP uses your health kit. X respawns. Y holds the scoreboard up. MENU pauses.
Press the RIGHT STICK to throw the flag, the LEFT STICK to open the map. LOADOUT is in the pause menu.
Every button can be changed in OPTIONS, CONTROLS: point at the right-hand column and press the button you want.

If the picture is stuck to your head with no menu, a yellow line in front of you says what the headset rig is waiting
for or where it stopped; the whole story is in a file on the headset:
    adb pull /sdcard/Android/data/com.playspace.skiforever.vr/files/vr-log.txt
Online play works in the headset the same way as on a PC: HOST A MATCH and send the code, or type a friend's code and JOIN.
