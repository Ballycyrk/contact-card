Assignment:
"You are going to design a contact card page. The user should be able to input contacts to the page. Using the techniques demonstrated in the videos, you must use jQuery to append new data to the page and make the content interactive. Remember, the content you are making is dynamic, so be sure to attach your handlers appropriately. NOTE: we recommend using $(document).on()for this assignment as opposed to callbacks"

Discoveries:

If you use something like this:

var coding = $(this).children('h3').attr('class');

and there are multiple 'h3' children with different classes, this code will pull the class from the first 'h3' child.  I'm not sure if/how to get a 'younger' sibling if needed.

I'm still not convinced that I'm using the .append in the most efficient way but for now this is working.
