# SODLargerWorlds

Just a simple Repo to hold generated world files for Shadows of Doubt. This is to make it easier for people to share and find.

### **PLEASE NOTE WHEN USING THESE FILES, THEY CAN TAKE UP TO 5 MINUTES TO INITALIZE AFTER LOADING**


- 9 x 9   City requires roughly 11GB of RAM
- 10 x 10 City requires roughly 13GB of RAM
- 10 x 16 City requires roughly 18GB of RAM

*Slightly over estimated, due to the nature of the game these can be lower or higher



### Installation:
- Download the pre-generated city you'd like to use
- Extract the files using 7ZIP into %localappdata%low\ColePowered Games\Shadows of Doubt\Cities\
- Open the game, and click New Game
- Select Sandbox
- Select "Select City"
- Then search for the city installed (The name of the city, will be dependent on the file installed)

### Creating your own city:
***\*Please note we are looking into a more sophisticated solution, to make the process easier***
- Download and install Cheat Engine
- Start the game, and add the process to Cheat Engine
- Click New Game
- Click Sandbox
- Click Generate City
- Set the Size to Small
- Now set Cheat Engine to scan "exact value" with data type as "4 bytes"
- Do First Scan for 5
- Set the Size to Very Large
- Change the scan value to 7, then scan next
- Repeat this flipping between 5 and small, 7 and Very Large till you have only one address (sometimes two will appear you can tell the correct one as one address will change value with no user input)
- The address found will be the X coordinate size
- For the Y size, repeat the process but this time using 5 for Small and 6 for Very Large
- Once both addresses are found, you can then set the values to whatever you wish, then generate

*Thank you to Cooperg2001 for helping with the explanation

**Notes:**
- The coastline of the city *DOES* count as a tile. So when creating a new one you'll need a minimum of 3. that would be a single block of the actual city. We've found 3 x 6 seems to be the smallest possible, generating a 1 x 4 line of blocks.
- Once a new city is generated, it is reccommended to restart the game. This is because there seems to be data that isn't removed when generating, causing the game to eat more RAM than needed. Example is the 10 x 10 city needs about 9GB - 12GB, but when first generated, needed 18GB. 
