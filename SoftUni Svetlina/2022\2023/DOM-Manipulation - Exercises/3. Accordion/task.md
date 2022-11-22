An html file is given and your task is to show more/show less information by clicking a button (it is not an
actual button, but a span that has an onlick event attached to it). When More link is clicked, it reveals the
contents of a hidden div and change the text of the link to Less. When the same link is clicked again (now
reading Less), hide the div and change the text of the link back. Link action should be toggleable (you
should be able to click the button infinite amount of times).

Hints:
 To change the text content of a button you could use getElementsByClassName. Which, however,
returns a collection and we need only one element from it so the correct way is to use it like this:
getElementsByClassName(‘button’)[0] and it will return the needed span element.
 After that we should change the display style of the div with id “extra”. If the display style is
“none” we should change it to “block” and the opposite.
 Alongside all of this, we should change the text content of the button to Less/More.
