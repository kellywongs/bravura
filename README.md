# bravura
*a sheet music transcribing app that doesn't suck*

## concept
+ **One-handed controls**: One thumb should be able to write a whole line of music without leaving the screen. 
+ **Note Values**: The y (up/down) axis is the note value.
  + The staff is sized appropriately to be within range of the thumb. It has to be large enough for clarity, yet small enough for control.
  + Notes can be written by tapping on a line or space, or dragging a note up and down to be able to access chromatics. 
  + *3D Touch integration:* Weird exotic sharps and flats can be accessed by going to the single sharp/flat and then pressing it hard to toggle on the double. Haptics!
  + If you're approaching a note from the top, it will suggest sharps; if you're approaching it from the bottom you'll get flats. Depending on the key signature, you'll also find naturals. 
    + TODO: List of behaviors of sharps/flats/naturals for different key signatures
  + Instant auditory feedback a la Noteflight. (See Noises.)
  + *3D Touch integration:* Hard-pressing (or long-pressing, depending on device) a note will bring up a control panel of articulation markings that can be further customized in Settings. These don't count crescendos/decrescendos, dynamic markings, slurs, etc; rather, they're focused on the individual note.
    + examples: tenuto, stacatto, accents, up/down bows, harmonics if you're into that kinda thing, tremelo.
    + organized by type of instrument (bowed, strummed, blown, tapped)? bowed -> up/down 
    + TODO: Look up articulations specifically for 
+ **Note Length**: The x (left/right) axis is note length.
  + A little bar follows your thumb and shows a grayed-out version of your note at the length you've arrived at
  + haptic feedback when note length changes
  + Left for shorter notes, right for longer notes
    + order: 256th, 64th, 32nd, sixteenth, eighth, dotted eighth?, quarter, dotted quarter, half, dotted half, whole, drag far right to grab more? 
+ **Noises**: To keep it simple, the app is built with a little piano. 
  + Getting MuseScore's level of complexity with different noises and articulations (pizzicato, difference between violins and violas) is difficult and quite possibly on a scope way too large for an iPhone.
  
  
