Matthew Stein, Steiner Student 2014, matthew@mstein.org
In Der Heym:
An interactive object search game with randomized question order and optimized game flow for multiple pictures (distinct object sets)

Contents:
        README.txt (this)
        inDerHeym.html
        ./images/
        jquery.imagemapster.js

To add new objects:
   * In the "house" object, find the appropriate room in the array and insert the new object as such: ["name", ["yiddish", "translit"]]
   * The "name" should be the English name of the object corresponding to the data-title given in the image maps.
   * New objects also must be clickable, so make sure each item has a corresponding area tag in an image map down at the bottom of the code. Multiple areas in a room may have the same name - the click event just looks to see if the name of the object clicked is equal to the name of the object currently being sought out (and thus whose question is being displayed.)
   * When adding new area maps, there should not be a title - this will prevent displaying the object name on hover. Instead, use the "data-title" attribute.

To change pictures:
   * Change the image source of the appropriate image in the "images" div.
   * Make sure that the usemap attribute equals "#roomName" and the corresponding image map has name="roomName". This is what links image maps to their images.


Potential future improvements:
   * On hover animations to make clickable objects more obvious
   * "Learning Mode" where each object displays its name on hover or on click
   * "Strict Test Mode" where an object gets asked later if not found on the first attempt
   * End results page to show which object took the most attempts to be found


A sheynem dank,
Meyshke / Matthew Stein
