===============================================================================
=   W e l c o m e   t o   t h e   V S C o d e   T u t o r   -   Version 0.1   =
===============================================================================

     VSCode is a very powerful IDE that has many commands, too many to
     explain in a tutor such as this.  This tutor is designed to describe
     enough of the commands that you will be able to easily use VSCode as
     an all-purpose editor.

     The approximate time required to complete the tutor is 5-10 minutes,
     depending upon how much time is spent with experimentation.

     ATTENTION:
     Clone this repository to start the tutorial. You can do this manually 
     using   git clone https://github.com/vscodetutor/vscodetutor.git
     
     Or you can open a new VSCode window, click on the three circles 
     "Source control" icon on the left and click "Clone Repository"

     The commands in the lessons will modify the text.  If you cloned the
     repository, VSCode can easily show you the edits you made, so no need
     to make another copy of this file

     It is important to remember that this tutor is set up to teach by
     use.  That means that you need to execute the commands to learn them
     properly.  If you only read the text, you will forget the commands!

     Now, scroll the editor so that Lesson 1.1 is at a comfortable position
     in your screen
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
         Lesson 1.1:  MOVING THE CURSOR


   ** To move the cursor, move the pointer and right click. **
       
  1. Move the cursor around the screen until you are comfortable.

  2. Scroll down.
     Now you know how to move to the next lesson. 

  3. Using the method you prefer, move to Lesson 1.2.

NOTE: If you are ever unsure about something you typed, press CTRL-Z to undo 
      the last action. The editor will focus on the last edited location, 
      You can use CTRL-SHIFT-Z to redo

NOTE: The arrow keys should also work.  But using using the mouse you will be
      able to move around much faster, for large distances.  Really!
      Arrow keys are good for smaller movements

~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
             Lesson 1.2: EXITING VSCODE


  !! NOTE: Before executing any of the steps below, read this entire lesson!!

  1. Press the <X> button at the top of the window
     This exits asks you for confirmation if you have any unsaved changes and 
     allows you to save or discard them.

  2. When VSCode has closed, relaunch it and you should see this workspace
     in your "Recent" section

  3. If you have these steps memorized and are confident, execute steps
     1 through 2 to exit and re-enter the editor.

  4. Move down to Lesson 1.3.


~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
           Lesson 1.3: TEXT EDITING - DELETION


   ** Press  <Backspace>  to delete the character in front of the cursor. **

  1. Move the cursor to the line below marked --->.

  2. To fix the errors, move the cursor until it is on top of the
     character to be deleted.

  3. Press the   <Backspace>  key to delete the unwanted character.

  4. Repeat steps 2 through 4 until the sentence is correct.

---> The ccow jumpedd ovverr thhe mooon.

  5. Now that the line is correct, go on to Lesson 1.4.

NOTE: As you go through this tutor, do not try to memorize, learn by usage.



~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
            Lesson 1.4: TEXT EDITING - INSERTION


         ** Press any character key to insert it **

  1. Move the cursor to the first line below marked --->.

  2. To make the first line the same as the second, move the cursor on top
     of the first character BEFORE where the text is to be inserted.

  3. Type in the necessary additions.

---> There is text misng this .
---> There is some text missing from this line.

  4. When you are comfortable inserting text move to lesson 1.5.



~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
           Lesson 1.5: TEXT EDITING - APPENDING


  1. Move the cursor to the first line below marked --->.
     It does not matter on what character the cursor is in that line.

  2. Press  <End>  and type in the necessary additions.

  3. Move the cursor to the second line marked ---> and repeat 
     step 2 to correct this sentence.

---> There is some text missing from th
     There is some text missing from this line.
---> There is also some text miss
     There is also some text missing here.

  4. When you are comfortable appending text move to lesson 1.6.

~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
           Lesson 1.6: EDITING A FILE

          ** Use  CTRL-S  to save a file **

  !! NOTE: Before executing any of the steps below, read this entire lesson!!

  1. Exit this tutor as you did in lesson 1.2

  2. CTRL+N to open a new empty file

  3. Insert and delete text as you learned in the previous lessons.

  4. Save the file with changes with CTRL-S and close the tab with CTRL-W
     (if you didn't save the changes CTRL-W will ask you if you want to save)

  5. After reading the above steps and understanding them: do it.
  
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
                Lesson 1 SUMMARY


  1. The cursor is moved using either the arrow keys or the pointer

  2. To start VSCode from the shell prompt type:  
      code FILENAME/DIRECTORY <ENTER>

  3. To exit VSCode close the window

  4. To delete the character at the cursor type:  <BACKSPACE>

  5. To insert or append text type:
    type the text                          insert before the cursor
    <END>   type appended text             append after the line

Now continue with Lesson 2.

~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
         Lesson 2.1: DELETION COMMANDS


             ** Type  CTRL-D <Backspace> to delete a word **

  1. Move the cursor to the line below marked --->.

  2. Move the cursor to the beginning of a word that needs to be deleted.

  3. Type   CTRL-D <Backspace>    to make the word disappear.

  NOTE: The word will be highlighted when you press CTRL-D VCode selected the
   word for you, if you selected the wrong thing, move the cursor or press
   <ESC>, it will clear the selection

---> There are a some words fun that don't belong paper in this sentence.

  4. Repeat steps 2 and 3 until the sentence is correct and go to Lesson 2.2.


~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
            Lesson 2.2: MORE DELETION COMMANDS


      ** Type  SHIFT-END <Backspace>   to delete to the end of the line. **

  1. Move the cursor to the line below marked --->.

  2. Move the cursor to the end of the correct line (AFTER the first . ).

  3. Type    SHIFT-END <Backspace>    to delete to the end of the line.

---> Somebody typed the end of this line twice. end of this line twice.


  4. Move on to Lesson 2.3 to understand what is happening.





~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
           Lesson 2.3: ON <SHIFT> AND MOTIONS


  You can select text by holding <SHIFT> and moving the cursor.
  
  A short list of motions:
    CTRL-LeftArrow - before the start of the word
    CTRL-RightArrow - after the end of the word
    <END> - to the end of the line
    <HOME> - to the beginning of the line

~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
           Lesson 2.4: REPEATING A MOTION


   ** Repeating a motion will try to repeat a motion **

  1. Move the cursor to the start of the line marked ---> below.

  2. Type  CTRL-RightArrow twice  to move the cursor two words forward.

  3. Type  CTRL-RightArrow three times  to move the cursor to the end of 
     the third word forward.

  4. Type  <HOME> to move to the start of the line.

  5. Repeat steps 2 and 3 with different number of repetitions.

---> This is just a line with words you can move around in.

  6. Move on to Lesson 2.5.




~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
           Lesson 2.5: SELECT MORE TEXT TO DELETE MORE


   ** Repeating a motion repeats it that many times. **

  1. Move the cursor to the first UPPER CASE word in the line marked --->.

  2. Type  CTRL-RightArrow twice and then <Backspace> to delete the two
     UPPER CASE words

  3. Repeat steps 1 and 2 with a different selection to delete the consecutive
     UPPER CASE words with one selection

--->  this ABC DE line FGHI JK LMN OP of words is Q RS TUV cleaned up.





~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
          Lesson 2.6: OPERATING ON LINES


         ** Type  CTRL+X   to delete a whole line. **

  Due to the frequency of whole line deletion, the designers of VSCode decided
  it would be easier to simply type CTRL+X when no text is selected to delete 
  a line.

  1. Move the cursor to the second line in the phrase below.
  2. Type  CTRL+X  to delete the line.
  3. Now move to the fourth line.
  4. Type   CTRL+X twice   to delete two lines.

--->  1)  Roses are red,
--->  2)  Mud is fun,
--->  3)  Violets are blue,
--->  4)  I have a car,
--->  5)  Clocks tell time,
--->  6)  Sugar is sweet
--->  7)  And so are you.


~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
          Lesson 2.7: THE UNDO COMMAND


   ** Press  CTRL+Z   to undo the last commands **

  1. Move the cursor to the line below marked ---> and place it on the
     first error.
  2. Type  <Backspace>  to delete the first unwanted character.
  3. Now type  CTRL+Z  to undo the last command executed.
  4. This time fix all the errors on the line using <Backspace>.
  5. Now type a capital  CTRL+Z until the line returns to its original state.
  6. Now type  CTRL+SHIFT+Z or CTRL-Y  a few times to redo the commands 
     (undo the undo's).

---> Fiix the errors oon thhis line and reeplace them witth undo.

  8. These are very useful commands.  Now move on to the Lesson 2 Summary.




~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
                Lesson 2 SUMMARY


  1. To delete from the cursor up to the next word type:    
     CTRL-SHIFT-RightArrow <Backspace>
  2. To delete from the cursor to the end of a line type:    SHIFT-END <Backspace>
  3. To delete a whole line type:    CTRL-X

  4. To repeat a motion just repeat the motion
  5. To select text, hold shift and move the cursor
  6. To move to the start of the line use a zero:  <HOME>

  7. To undo previous actions, type:           CTRL-Z
     To undo all the changes on a line, type:  CTRL-Z until necessary
     To undo the undo's, type:             CTRL-SHIFT-Z / CTRL-Y

~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
          Lesson 3.1: THE PASTE COMMAND


       ** Type   CTRL-V  to paste previously copied text after the cursor. **

  1. Move the cursor to the first ---> line below.

  2. Type  CTRL-X  to cut the line and store it in the clipboard.

  3. Move the cursor to the c) line, ABOVE where the deleted line should go.

  4. Type   CTRL-V   to put the line below the cursor.

  5. Repeat steps 2 through 4 to put all the lines in correct order.

---> d) Can you learn too?
---> b) Violets are blue,
---> c) Intelligence is learned,
---> a) Roses are red,



~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
             Lesson 3.2: REPLACING CHARACTERS


       ** Type  <Backspace> x  to replace the character at the cursor with  x . **

  1. Move the cursor to the first line below marked --->.

  2. Move the cursor so that it is in front of the first error.

  3. Type   <Backspace>   and then the character which should be there.

  4. Repeat steps 2 and 3 until the first line is equal to the second one.

--->  Whan this lime was tuoed in, someone presswd some wrojg keys!
--->  When this line was typed in, someone pressed some wrong keys!

  5. Now move on to Lesson 3.3.

NOTE: Remember that you should be learning by doing, not memorization.



~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
         Lesson 3.3: REPLACING TEXT


      ** To change until the end of a word, type  CTRL-SHIFT-RightArrow . **

  1. Move the cursor to the first line below marked --->.

  2. Place the cursor before the  u  in  lubw.

  3. Type  CTRL-SHIFT-RightArrow  and the correct word (in this case, type  ine ).

  4. Move to the next character that needs to be changed.

  5. Repeat steps 3 and 4 until the first sentence is the same as the second.

---> This lubw has a few wptfd that mrrf changing usf the change operator.
---> This line has a few words that need changing using the change operator.


~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
             Lesson 3.4: REPLACING MORE TEXT


     ** You can select text and then replace it with anything you want. **

  1. Lesson 2 covered how to select text 

  2. Move to the first line below marked --->.

  3. Move the cursor to the first error.

  4. Type  SHIFT-END  and type the rest of the line like the second

---> The end of this line needs some help to make it like the second.
---> The end of this line needs to be corrected using the  c$  command.

NOTE:  You can use the Backspace key to correct mistakes while typing.

~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
                Lesson 3 SUMMARY


  1. To put back text that has just been copied, type   CTRL-V .  This puts the
     deleted text AFTER the cursor (if a line was cut it will go on the
     line above the cursor if the line the cursor is on is not empty).

  2. To replace the character under the cursor, type   <Backspace>   and then the
     character you want to have there.

  3. Select text using SHIFT, type to replace the selection

Now go on to the next lesson.



~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
        Lesson 4.1: CURSOR LOCATION AND FILE STATUS

  ** You can see the cursor position in the status bar at the bottom of the window
     Look for "Ln <Number>, Col <Number>"
     Type  CTRL-G  to move to a line in the file. **

  NOTE: Read this entire lesson before executing any of the steps!!

  1. Hold down the Ctrl key and press  g .  We call this CTRL-G.
     A message will appear at the top of the page with the position in the file.
     Remember the line number for Step 3.

NOTE:  You may see the cursor position in the lower right corner of the screen

  2. Press  CTRL-G  to move you to the bottom of the file.
     Hold <PageUp> to move you to the start of the file. (or scroll)

  3. CTRL-G, type the number of the line you were on and then  <ENTER> .  This will
     return you to the line you were on when you first pressed CTRL-G.

  4. If you feel confident to do this, execute steps 1 through 3.

NOTE: If you moved the view by scrolling, it doesn't move the cursor, you can 
   press any arrow key and VSCode will focus the editor where the cursor is if
   the cursor was not in view

~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
         Lesson 4.2: THE SEARCH COMMAND


     ** Type  CTRL-F  followed by a phrase to search for the phrase. **

  1. Press CTRL-F.  Notice that the cursor moved to an input bar at the 
     top right corner of the editor

  2. Now type 'errroor' <ENTER>.  This is the word you want to search for.

  3. To search for the same phrase again, simply type  <ENTER> .
     To search for the same phrase in the opposite direction, 
     type  SHIFT-ENTER . (or use the buttons)

  4. To go back to where you came from press  CTRL-U  (Keep Ctrl down while
     pressing the letter u).  Repeat to go back further.  By default going 
     forward does not have a keybinding.

--->  "errroor" is not the way to spell error;  errroor is an error.
NOTE: When the search reaches the end of the file it will continue at the
      start

~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
         Lesson 4.3: MATCHING PARENTHESES SEARCH


         ** Type  CTRL-SHIFT-\  to find a matching ),], or } . **

  1. Place the cursor on any (, [, or { in the line below marked --->.

  2. Now type the  CTRL-SHIFT-\  character.

  3. The cursor will move to the matching parenthesis or bracket.

  4. Type  CTRL-SHIFT-\  to move the cursor to the other matching bracket.

  5. Move the cursor to another (,),[,],{ or } and see what  CTRL-SHIFT-\  does.

---> This ( is a test line with ('s, ['s ] and {'s } in it. ))


NOTE: VSCode will highlight unmatched parenthesis



~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
            Lesson 4.4: THE FIND REPLACE COMMAND


   ** Type  CTRL-H "old" <TAB> "new" to substitute 'new' for 'old'. **

  1. Move the cursor to the line below marked --->.

  2. Type  CTRL-H "thee" <TAB> "the" <ENTER>.  
     Note that this command only changes one occurrence of "thee" each time you
     press enter

  3. Now type  CTRL-ALT-ENTER .  CTRL-ALT-ENTER means to substitute
     globally in the file (you can also use the replace all button)

Note: You usually may want to replace one thing at a time, you may also
   use CTRL-D to repeat a selection e.g. try to move the cursor to the first 
   "thee" after the ---> press CTRL-D three times, you can now edit all three
   "thee" at the same time (also see Lesson 6.3)

---> thee best time to see thee flowers is in thee spring.

  4. To change every occurrence of a character string between two lines,
     Use find until you are focused on the first occurrence of the string
     you want to replace, replace until you are satisfied
     Replace all to change every occurrence in the whole file.
     
  5. You can use CTRL-SHIFT-F to search in the whole workspace, typing something
     in the replace bar will preview the substitution
   
  6. You can find and replace using regex, in the replace field you can use
     $1, $2, $3... to substitute the corresponding capture groups

~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
                Lesson 4 SUMMARY


  1. CTRL-G  displays your location in the file and the file status.
     Scrolling down enough moves to the end of the file.
     CTRL-G number         moves to that line number.
     Scrolling up enough   moves to the first line.

  2. Typing  CTRL-F   followed by a phrase and ENTER searches FORWARD for the 
     phrase.
     Typing  CTRL-F   followed by a phrase and SHIFT-ENTER searches BACKWARD 
     for the phrase.
     After a search type ENTER to find the next occurrence in the same direction
     or  SHIFT-ENTER  to search in the opposite direction.
     CTRL-U takes you back to older positions, CTRL-SHIFT-P "Cursor redo" to 
     newer positions. (for "Cursor redo" click the "cog" button to set a key
     binding)

  3. Typing  CTRL-SHIFT-\   while the cursor is on a (,),[,],{, or } goes to its match.
     VSCode will highlight matching parentheses, so you can scroll to its match

  4. To substitute new for the first old in a line type    CTRL-H
     Or CTRL-F and click on the ">" button on the left

~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
      Lesson 5.1: HOW TO EXECUTE AN EXTERNAL COMMAND


   ** Type  CTRL-`   to open a terminal **


~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
            Lesson 5.2: MORE ON WRITING FILES


     ** To save the changes made to the text, type  CTRL-S **

  1. CTRL-SHIFT-E to focus the "Explorer view" which contains a file tree of
     your workspace

  2. Choose a filename that does not exist yet, such as TEST.

  3. Click of the file tree on a directory, press the "new file" button at the 
     top of the file tree to create a new file, type TEST as file name

  4. This creates an empty file, click the file in the file tree to open it

  5. Now remove the file by clicking on it and pressing <DELETE>


~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
          Lesson 5.3: SELECTING TEXT TO WRITE


   ** To save part of the file, select the part, copy it, create a new file 
      and paste the selection **

  1. Move the cursor to this line.

  2. Press  SHIFT  and move the cursor to the fifth item below.  Notice that the
     text is highlighted.

  3. Press the  CTRL-C  character. 

  4. Type  CTRL-SHIFT-N

  5. CTRL-V to paste

  6. CTRL-S to save, this opens a prompt to ask you where to save the file
     e.g. you can edit the last fragment of the past to choose a name like TEST

~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
         Lesson 5.4: RETRIEVING AND MERGING FILES


       ** To insert the contents of a file, copy it and then paste it  **

  1. Place the cursor just above this line.

NOTE:  After executing Step 2 you will see text from Lesson 5.3.  Then move
       DOWN to see this lesson again.

  2. Now retrieve your TEST file using CTRL-P to fuzzy find a file, type TEST
     <ENTER> to open it
     Copy and paste it's content (CTRL-A to select all text)

NOTE:  You can also read the output of an external command.  For example,
       you can copy paste the output of the command from the terminal


~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
                Lesson 5 SUMMARY


  1.  CTRL-` to open the integrated terminal

  2.  CTRL-S to save files (you can toggle auto saving in the settings)

  3.  Hold SHIFT to select

  4.  You can do a lot just copy pasting

~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
          Lesson 6.1: NOTHING TO ADD

~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
         Lesson 6.2: NOTHING TO ADD

~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
          Lesson 6.3: ANOTHER WAY TO REPLACE


      ** Select a string and press CTRL-D to repeat the selection **

  1. Move the cursor to the first line below marked --->.  Move the cursor to
     the beginning of the first  xxx .

  2. Now press  CTRL-D twice, it should select both xxx

  3. Press the down arrow, you should have two cursors now that move at the same
     time. Hold SHIFT and select both 456 and 579 which are right below the xxx
     CTRL-C to copy both

  4. Select both xxx again, either moving both cursors or exiting multiple cursor
     mode using ESC (or clicking anywhere) and reselect using CTRL-D
  
  5. With both xxx selected press CTRL-V, it will paste and replace 456, 579 for
     the corresponding xxx

---> Adding 123 to xxx gives you xxx.
---> Adding 123 to 456 gives you 579.

NOTE:  After some practice it can become natural to use multiple cursors, you
  will probably use CTRL-D more than find replace, unless you are doing a 
  replace all

~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
         Lesson 6.4: COPY AND PASTE TEXT


     ** Use the  CTRL-C  operator to copy text and  CTRL-V  to paste it **

  1. Go to the line marked with ---> below and place the cursor after "a)".
  
  2. Select "this is the", CTRL-C

  3. Move the cursor to the end of the next line <DownArrow> <END>

  4. Type  CTRL-V  to put (paste) the text.

  6. Copy " item.", paste at the end of the next line

--->  a) this is the first item.
      b)

~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
             Lesson 6.5: SEARCH OPTION


     ** Set an option so a search or substitute ignores case **

  1. Open the finder with CTRL-F

  2. Press the "Aa" button to toggle case sensitive search

  3. Press the "ab" button to toggle whole word match

  4. Press ".*" to toggle regex search

~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
                Lesson 6 SUMMARY

  1. CTRL-RightArrow  command moves to the end of a word.

  2. CTRL-C copies text,  CTRL-V pastes it.

  3. CTRL-R to open the find / replace bar, ESC to close it

  4. Toggle find options using the buttons (or hover the button for the key
     bindings)

~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
             Lesson 7.1: GETTING HELP


            ** Use the on-line help system **

  VSCode has a large userbase, it's probably easy to find help using a search 
  engine
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
            Lesson 7.2: CUSTOMIZE VSCODE

           ** VSCode settings **
  
  CTRL-SHIFT-P "Settings UI" to change any settings
  
  You probably want to check the "Commonly used" settings to suit your workflow

  CTRL-SHIFT-P "Color theme" to change your theme

           ** Extend VSCode features **

  VSCode has an extension marketplace

  You can open the Extensions panel by clicking on the four squares icon on the
  left to search and install extensions

  VSCode will "Reccommend" a few extensions depending on the files in your
  workspace, but do your due diligence!

  The extension publishing process is not super strict and extensions can 
  execute any core on your computers

  

~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
              Lesson 7.3: COMPLETION


         ** Command line completion with <TAB> **

  The integrated terminal uses your system shell (search on the internet
  how to choose a custom shell)

         ** Code completion with CTRL-Space **
   
  Many extensions provide "language services" including code competition
  CTRL-Space shows suggestions, by default typing certain strings will also 
  show suggestions

  1. often typing a '.' will show type based suggestions
  2. you can register keywords for snippets, typing the keyword will suggest
     filling in the snippet
  3. extension that offer AI based language services may show suggestions all 
     the time or on demand with CTRL-Space

~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
                Lesson 7 SUMMARY


  1. Use your favourite search engine (the VSCode documentation is also great)


~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

  This concludes the VSCode Tutor.  It was intended to give a brief overview of
  the VSCode editor, just enough to allow you to use the editor fairly easily.
  It is far from complete as VSCode has many many more features.  Read the VSCode
  documentation next:

  https://code.visualstudio.com/docs

  There are also a lot of resources with tips and tricks for all levels

  Since it's possible to be very productive immediately using VSCode, you can
  probably take it slowly 

  This tutorial is a tribute to the "vimtutor" tutorial that was written 
  by Michael C. Pierce and Robert K. Ware,
  Colorado School of Mines using ideas supplied by Charles Smith,
  Colorado State University.  E-mail: bware@mines.colorado.edu.

  and Modified for Vim by Bram Moolenaar.

~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~