# Typst Notes For Patrick


## Wishes Granted!

1. Skip the title page(s) but still start the page numbers from 1:
   
   ```typst
   #pagebreak() // creates a division between your title pages and the content - you may have already done this in another way
   
   #counter(page).update(1) // sets the counter to 1 instead of 1 + quantity of title pages
   
   #set page(numbering: "1") // adds the page number - and for the record, it's weird as hell that the "numbering" parameter is a string, but it automatically does all kinds of crap to it
   ```

## Miscellaneous Useful Things!

1. The shortcut for commenting something out (so you can do things like \"disable\" sections of formatting, to see what's causing what):\
   
    * ___Mac:___\
     select text; <kbd>cmd</kbd> + <kbd>/</kbd>
   
    * ___Windows/Linux:___\
     select text; <kbd>ctrl</kbd> + <kbd>/</kbd> (I think - let me know if it doesn't work!)
   
1. You. (I didn't have a second list item at the time of writing.)
