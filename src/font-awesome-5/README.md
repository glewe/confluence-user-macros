# Font Awesome 5 #
This Confluence user displays a Font Awesome 5 icon with many options for customization.

# Confluence User Macros #
Confluence is Atlassian's Enterprise Wiki.

Check it out here: https://www.atlassian.com/software/confluence

When running Confluence on your own server, it allows you to create so-called "User Macros" that you can insert into your pages to add great features and visuals.

Read more about Confluence User Macros here:
https://confluence.atlassian.com/doc/writing-user-macros-4485.html

## Installation in Confluence Server or Data Center
## Include Font Awesome 5 style shhet ##

1. Login as administrator
1. Go to "General Configuration", then select "Custom HTML" from the menu on the left
1. Click the "Edit" button
1. Select text box "At end of the HEAD"
1. Add the line: `<link rel="stylesheet" href="https://use.fontawesome.com/releases/v5.3.1/css/all.css" integrity="sha384-mzrmE5qonljUremFsqc01SB46JvROS7bZs3IO2EmfFsd15uHvIt+Y8vEf7N7fWAU" crossorigin="anonymous">`
1. Click Save

## Install the User Macro ##
_Note: User Macros are not available in Confluence Cloud!_

1. Login as administrator
1. Go to "General Configuration", then select "User Macros" from the menu on the left
1. Scroll down to the bottom and click on "Create a User Macro"
1. Enter the appropriate Macro Browser Information
1. Select "No macro body"
1. Paste the template code from the *.vtl file into the Template field
1. Click Save

# License #
This Confluence User Macro is distributed under the GNU LGPLv3 license.

## Credits
Icon font and macro icon from [Font Awesome](https://fontawesome.com/)
