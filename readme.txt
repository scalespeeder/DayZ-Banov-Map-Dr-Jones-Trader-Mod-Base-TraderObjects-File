DayZ Dr Jones Trader Mod Custom TraderObjects File To Spawn Trader Base At Alica Airfield On Banov For PC Servers Instructions & Terms Of Use

This traderobjects file will place a trader base at the Alica airfield on Banov, 4875.00 / 4769.82

Must be used with correctly istalled Dr Jones Trader Mod, replacing the vanilla traderobjects file.

https://steamcommunity.com/sharedfiles/filedetails/?id=1590841260

Limited Testing on PC Banov Local Server DAYZ Version 1.20 May 2023.

Trader & .dze Files Created by @scalespeeder . Please report bugs & errors to scalespeeder@gmail.com with screenshots.

Included in the repository is my DayZ Editor Mod .dze file, which you could use to customise the trader - you would
need to re-export as json and then convert to Dr Jones Trader mod format.

TERMS OF USE
THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND,
EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS
OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN
AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH
THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.

Using these modded files and instructions could break the functioning of your DAYZ server, requiring a reinstall that would wipe
all player progress.

Using these modded files neccessitates increased regular restarts to prevent server crashing.

It is suggested you thoroughly test your server after applying these files to ensure proper
functioning of your server.

I always recomend you validate your files at: https://www.xmlvalidation.com/ and https://jsonformatter.curiousconcept.com/

To download all of the files from the Github, click on the green "Code" button then "download zip" and extract / unzip that file onto your local PC hard-drive.

Instructions:

Install Dr Jones Trader on your server.

Inside your servers config / profiles / settings folder (can have different names) find the Trader folder, and inside that replace the existing TraderObjects
file with the one included in this depository.

Open up your servers cfgeventspawns.xml, scroll down to <event name="StaticContaminatedArea"> and replace the following line:

<pos x="4921.78" y="202.332" z="4817.25" a="0"/>

with

<!-- <pos x="4921.78" y="202.332" z="4817.25" a="0"/> Alica Airport Trader Area -->

This will stop gas artillery strikes on your trader.

Save & re-start your server for the changes to take effect.

Thanks, Rob.