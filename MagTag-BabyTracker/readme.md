# MagTag Baby Tracker

https://learn.adafruit.com/magtag-cat-feeder-clock/code-the-magtag-cat-fed-clock

LEDs could blink and a sound could play if it has been over X hours since the last feeding/changing time

Use light or heavy sleep mode when the light sensor detects low levels of light, but wake for a minute if a button or two are pressed to get ready for new inputs

Log out activities to a file or files with the timestamp and activity type, could eventually log up to Adafruit I/O for more analysis

Main screen is "activities"

Button 1 - Diaper changes
   Triggers sub menu where there are options for:
       Wet
       BM
       Dry
       Other?
Button 2 - Feedings
    Triggers sub menu with options:
        Start, then prompts for method (breast/bottle/baby food), amount (for bottle/baby food), with "Back", +/- and Log feeding keys
        Prompts whether vitamin D was added for breastfeeding babies
Button 3 - Naps
    Triggers sub menu with options:
          Start, then whether planned/unplanned, and keeps timer on screen with a Neopixel flashing periodically to remind that the timer is running
          Stop/Wakeup, and then "reason" like "feeding required" or "diaper change required"
Button 4 - Bath time or view charts?
     Log a bath, but since they only need to happen every 2-3 days, it might be easier to track those on a calendar
