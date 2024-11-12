# Typst Notes For Patrick


## Wishes Granted!

1. Skip the title page(s) but still start the page numbers from 1:
   
   ```typst
   #pagebreak() // creates a division between your title pages and the content - you may have already done this in another way
   
   #counter(page).update(1) // sets the counter to 1 instead of 1 + quantity of title pages
   
   #set page(numbering: "1") // adds the page number - and for the record, it's weird as hell that the "numbering" parameter is a string, but it automatically does all kinds of crap to it
   ```

   I think that this is appropriately clean for your use case. We can get onto variables later, and then you'll probably realise that they're something you've learned before! :D

## Miscellaneous Useful Things!

1. The shortcut for commenting something out (so you can do things like \"disable\" sections of formatting, to see what's causing what):
   
    * ___Mac:___\
     select text; <kbd>cmd</kbd> + <kbd>/</kbd>
   
    * ___Windows/Linux:___\
     select text; <kbd>ctrl</kbd> + <kbd>/</kbd> (I think - let me know if it doesn't work!)
   
1. You. (I didn't have a second list item at the time of writing.)

1. Autocomplete:
   
   <kbd>ctrl</kbd> + <kbd>/</kbd>

   You have your options conveniently laid out for you, so you don't have to guess which arguments a function takes, or which functions can come next!

1. [The documentation spells it out nice and clearly, too.](https://typst.app/docs/reference) Obviously you're already using this, but it's always worth remembering that these things don't have to feel vague or fuzzy.
  
