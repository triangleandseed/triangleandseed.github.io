# samrao.github.io

----Website Updating Guidelines----

Whenever a new video is added, an image square and text needs to be added to the grid (under the "squares" class), to the html file:"index.html". Furthermore, all related pages should be updated. This means that if there are 7 different video pages that load up different vimeo embeds on the click of the corresponding link on the grid, each of these pages needs have the image square and text added. Finally, a new page needs to be created with the embed for the video being added.

In the case that I implement javascript so that I don't need to load a different page every time I click a link on the grid (using display properties), the process is simplified. I update the "index.html" to add another square to the grid, and I add a few lines to the javascript that tells the new video to display (also hiding whatever was there before).

Not sure SSI is a great option here.

Edit: I implimented the javascript to simplify things, but I don't have time to update the guidelines. As a self-reminder, the functions in the javascript file need to be changed when updating the site:
1. another function needs to be added to allow the embed to appear and disappear on click of the corresponding link.
2. each of the previous functions need to have a "hideimage('new video id')" line added to make sure that the new video disappears when another link is clicked.
