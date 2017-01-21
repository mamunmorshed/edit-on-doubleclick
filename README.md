# edit-on-doubleclick
A simple script to edit any text on double click. <https://mamunmorshed.github.io/edit-on-doubleclick/>

Link the script file to the project & call the function `doubleClickEdit`. Function accepts three parameter.

**Parameters**

  *First Parameter:* Selector of the elements you wish to be editable.
  
  *Second Parameter:* Pass the class you wish to assign on the element while it is editable
  
  *Third Parameter:* Pass the callback which will be feeded with the updated value on the element.
   

**Note:** Currently an error is logged into the console while you press enter after editing an item. Becasue in the form elements submit event, call back is called & the form element destroyed. For that input elements blur eventlistener fail to set. Work in progress to fix that.