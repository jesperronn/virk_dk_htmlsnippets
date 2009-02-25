Virk.dk HTML snippets
============

HTML snippets for building HTML to Virk.dk website (works in textmate, e-texteditor, gedit, etc)

This snippet library will reflect content in the Virk HTMLguide, currently 
at http://xmltools2.oio.dk/virk/htmlguide/

In general we found that developers are more productive with a HTML Guide than just the design specification. See my article [Design Guide or HTML Markup Guide](http://justaddwater.dk/2008/02/08/design-guide-or-html-markup-guide/). Using HTML snippets makes development even faster.

Snippets available
------------------

`skel`(tab) -- creates HTML skeleton in blank file. Adds correct doctype, head, body and container divs required for the virk.dk html to show correctly.

`fieldset`(tab)   Groups of form elements. Use where you would have used ordinary fieldsets. 
See HTML guide &raquo; [Form grupper (fieldsets)]
(http://xmltools2.oio.dk/virk/htmlguide/form-fieldset.html)  
`float`(tab) -- ??

`button`(tab) -- submit button and other buttons. See HTML guide &raquo;
 [Knapper](http://xmltools2.oio.dk/virk/htmlguide/buttons.html) 
`inputcheck`(tab) -- checkbox. See HTML guide &raquo; [Simple form elementer](http://xmltools2.oio.dk/virk/htmlguide/form-simple.html)  
`inputradio`(tab) -- checkbox. See HTML guide &raquo; [Simple form elementer](http://xmltools2.oio.dk/virk/htmlguide/form-simple.html)  
`inputtext`(tab) -- checkbox. See HTML guide &raquo; [Simple form elementer](http://xmltools2.oio.dk/virk/htmlguide/form-simple.html)  
`select`(tab) -- checkbox. See HTML guide &raquo; [Simple form elementer](http://xmltools2.oio.dk/virk/htmlguide/form-simple.html)  
`option`(tab) -- options inside a select element. See HTML guide 
&raquo; [Simple form elementer](http://xmltools2.oio.dk/virk/htmlguide/form-simple.html)  
`readonly`(tab) -- readonly element. See HTML guide 
&raquo; [Særlige form elementer](http://xmltools2.oio.dk/virk/htmlguide/form-special.html)  
`textarea`(tab) -- textarea element. See HTML guide &raquo; [Simple form elementer](http://xmltools2.oio.dk/virk/htmlguide/form-simple.html)


`table`(tab) -- table element. See HTML guide &raquo; [Tabeller](http://xmltools2.oio.dk/virk/htmlguide/tables.html)  
`td`(tab) -- table cell inside table row.  
`th`(tab) -- table header cell inside table row.


Installing the snippets
-----------------------

Download from the  [virk\_dk\_htmlsnippets project page on GitHub](http://github.com/jesperronn/virk_dk_htmlsnippets/tree/master) 

Unzip the file and do the following:

 * Mac/Textmate: Just double-click the .tmbundle folder will install the bundle in textmate
 * Windows/E-texteditor: Just copy the .tmbundle folder to the "Bundles" folder in the user 
   settings application directory, usually something like 
   "C:\Documents and Settings\[username]\Application Data\e" 

Contributors can read more in the following section (TODO list)

Work in progress -- TODO list
-----------------------------

NOTE that the current state of these snippets is quite uncomplete.
Feel free to fill in the gaps and send me your change suggestions.

I left the actual code here all of a sudden half a year ago. So chances are you will find gaps and holes. Here are some of the obvious I saw.

* There are references to 'BRS brugerrettigheds administration' -- should be changed to virk
* There are at least one 'To be done' reference in a snippet
* Creating other sets of snippets for supporting this HTML markup. For instance, I'd like to create a Rails form builder called something like VirkFormBuilder that could create the relevant HTML code.

Developers and contributors would have to create a fork of this project (and send me pull requests). You could also ask me for commit rights directly on this project. Send me your first patch and GitHub user ID.

Snippets created by Jesper Rønn-Jensen, jesperrr@gmail.com, Capgemini 2008