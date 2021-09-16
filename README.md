# WorkhuBE

Workhub Browser Extension

* Use Bookmarks as only data
* Une first degree folders within the %ROOT_WBE_BOOKMARKS_FOLDER% as the Workspaces
* The Workhub Browser Extension is injected within all URLs, so:
  * Permission to scan all URLs is mandatory
  * It adds a HTML panel as the first element in the document
    * The Workspace Ribbon panel is fixable (lock) or hidable (unlock)

UI/UX

* a small handle is always visible at the top (or a certain side of the screen?)
* The first component to appear when we click on the handle is the Workspaces Central Panel, with the following:
  1. Here we add the Workspaces (Bookmarks first degree folders)
  2. We can also go to the Settings in this initial panel
* Once a Workspace created, a click on the handle drops down the WorkhuBE Workspace Ribbon
* the Workspace Ribbon contains the following:
  1. the Workhub Center (space where all the workspaces (first degree bookmark folders) lives) button
  2. a set of Workspace Web Apps (simply Bookmarks (within a Workspace folder) with their downloaded data (social image, favicon, icons))
  3. a Settings button
  4. a Lock Ribbon (to pin the ribbon for it to be always visible)

## Conventions

1. Colors
   1. #707070 (balanced grey)
   2. #000000 (dark color)
   3. #FFFFFF (light color)
2. The WorkhuBE main font family is Verdana
3. Icons used are from the Material UI Resources
4. The extension is themeable (light & dark)
5. The Workspaces Central is 75px of height (including handle)
6. The Workspace Ribbon is 125px of height (including handle)
   1.  The web apps visual resources (favicons, social banner) are 64px square

# Visual Examples

## WorkhuBE black Workspace Central Panel
![WorkhuBE Workspace Central - Black](assets/WorkhuBE%20Workspaces%20Central%20-%20Black.png "WorkhuBE Workspace Central - Black")

## WorkhuBE black Workspace Ribbon 
![WorkhuBE Workspace Ribbon - Black](assets/WorkhuBE%20Ribbon%20-%20Black.png "WorkhuBE Workspace Ribbon - Black")


## WorkhuBE Example with Black Workspace Ribbon
![WorkhuBE Workspace Ribbon - Black](assets/WokhuBE%20Example%20-%20Black.png "WorkhuBE Workspace Ribbon - Black")


## WorkhuBE white Workspace Central 
![WorkhuBE Workspace Central - White](assets/WorkhuBE%20Workspaces%20Central%20-%20White.png "WorkhuBE Workspace Central - White")

## WorkhuBE white Workspace Ribbon 
![WorkhuBE Workspace Ribbon - White](assets/WorkhuBE%20Ribbon-%20White.png "WorkhuBE Workspace Ribbon - White")

## WorkhuBE Example with White Workspace Ribbon
![WorkhuBE Workspace Ribbon - White](assets/WokhuBE%20Example%20-%20White.png "WorkhuBE Workspace Ribbon - White")

