Project "figures"

2. If you call moveDown, the object will move down by 20 units (or pixels), as is indicated in the Java code of the objects (for both Circle & Square)
No matter how many times you call it, it will always move down my 20 pixels each time it's called (20 => 40 => 60)
Calling makeInvisible simply doesn't do anything if the object was already invisible to begin with. If you have previously called makeVisible, then it will become invisible. 
However, if makeVisible hasn't been called beforehand, then no changes will occur no matter the amount of times that makeInvisible is called. 

3. In order to use moveHorizontal to move an object 70 pixels to the left, all we have to do it moveHorizontal(-70);

4. If you specify a color that isn't known, it simply cannot change it to said color. However, it should be possible to add any color from the RGB wheel by implementing a few new lines of code.

5. For the image, I decided to merge both refrences and drew a house on top of a hill with two stick figures (person) standing in fornt of it.
