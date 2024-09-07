# Tags

Character cards and groups can be assigned zero or more tags. They are useful to organize quickly growing collections by themes, quality, provenance or whatever you like.

## Tagging

There are several ways to add or remove tags to a character card:

- Import embedded tags during the import.
- Open a card from the Character Management panel. From there you will be able to assign tags to a character card.
- Mass tagging.

To do mass tagging, click the "Bulk edit characters" button (pencil icon), select the cards you want to tag, right click on any of them, then click "Tag" in the contextual menu.

!!! info Note
Please note that groups cannot be tagged like this.
!!!

From this screen you will be able to:
- add or remove tags using the combo box
- remove all tags from the selected cards ("All")
- remove the intersection of tags among all selected cards from those cards ("Mutual")
- import (create locally) all tags stored in the character card, in case you imported it ("Import All")
- import (create locally) tags stored in the character card which also exist locally with matching names ("Import Existing")

## Managing

To view and manage all existing tags, open the Character Management panel then click on the "Manage tags" button (gear icon).

You can backup and restore all the information here (tag list, tag assignments to cards, colors, folder settings, etc) using the buttons on the top right.

You can use grip buttons on the left to reorder tags as they will appear in the tag filter in Character Management.

!!! warning Warning
The tags backup JSON file is not intented for sharing with others as it contains information specific to your instance only, such as internal entity names!
!!!

## Importing tags when importing character cards

When importing external character cards from downloaded images (or from the "Import content from external URL" button), you'll be prompted to optionally import the tags that it contains. They are not required for the card to function; tags are simply organizational.

!!! info Note
This popup will appear only if a User Settings option "Import Card Tags" is set to "Ask". 
!!!

In the "Import tags for CHARACTER NAME" popup that opens, you'll see a list of Existing tags (which you already had locally with a matching name), and New tags (which you did not have locally).

You can either:

- trim the lists as needed and then hit "Import" -- remaining Existing tags will be added to the imported character card, and remaining New tags will be created locally and then added to the card.
- or simply hit "Import none" to ignore tags contained in the character card and import ONLY the card
- or "Import All" as a shortcut to import all tags found in the character card (NOTE: including any that you trimmed from the lists above; use the "Import" button if you did)
- or "Import Existing" as a shortcut to only import tags that existed locally with a matching name.

## Filtering character cards

After you create tags, you will see them on a row in the Character Management panel. You can click these to switch tag filtering state; in order:

- one click will show cards tagged with this tag
- another click to only show cards NOT tagged with this tag
- another click to reset filtering by this tag

You can filter by any number of tags at the same time.

## Tags as Folders

!!! info Note
To use this functionality, it has to be enabled first in the User Settings, under the UI Theme column. The state of this toggle also saves with the UI theme.
!!!

From the "Manage tags" button (gear icon), each tag entry has a multi-state toggle button to cycle between these tags-as-folder modes (called "bogus folder" in the code):

- one click to turn this tag into an "open folder". It will appear as a virtual entry in the card list; clicking into it will only show cards with that tag
- another click to turn this tag into a "closed folder". As above, but cards tagged with this tag will not appear by default - you'll need to click into the folder to see them.
- another click to reset tag-as-folder state for this tag.