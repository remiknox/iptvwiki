Posted by u/Educational-Ring1091 in r/IPTVGroupBuy on Mon Feb 24 2025 04:36:02 GMT+0

This guide simplifies IPTVEditor’s key features and processes, so you can efficiently create and customize playlists for your IPTV setup. Follow these steps to make the most of IPTVEditor:

- Hot Keys:
    - Shift Click (Selects all items in the list between the two clicks)
    - Ctrl Click (Selects only items that were individually clicked)

———

# 1. Setting Up Your Playlist

1. Create an account on IPTVEditor and navigate to the **Playlist Manager** screen.
2. Click **Add a New Playlist** and give it a name of your choice.
3. Enter the credentials provided by your IPTV provider. Ignore any optional questions unless you’re sure about their impact.
4. When prompted to select streams to import:
    - Select all except for “channel number” (this prevents conflicts if you rearrange channels).
    - If you choose not to import EPG, you’ll need to manually add EPG sources later.

———

# 2. Importing Channel Categories

1. Select channel categories when prompted. If your playlist loads slowly, retry until it works.
2. Load all categories initially; you can eliminate unwanted ones later.
3. Do the same for **Movies** and **TV Series** categories.

———

# 3. Editing Your Playlist

1. In the Playlist Manager, click **Load Channels** next to your playlist to access the editing screen.
2. **EPG Editor**:
    - Click **Add External EPG Source** in the top right.
    - Use the credentials from your IPTV provider in this format: [`http://yourserver.com/xmltv.php?username=test&password=123`](http://yourserver.com/xmltv.php?username=test&password=123)
    - Once successful, use the globe icon to add EPGs provided by IPTVEditor.
3. **Category Editor**:
    - Remove unwanted categories by selecting them and clicking **Remove Category**.
    - You can merge categories by selecting it and and the selecting the category under "Merge Selected Category In". This will merge the category you selected first into the one selected in the list.
4. **Channel Editor**:
    - Delete unwanted channels by selecting them in the **Basic Editor** and clicking **Delete**.
    - If your provider uses the channel name as the event status. Select the channel and check the "Sync Name" option. When you setup auto updater make sure to check the "Sync Streams Name".

**Advanced Channel Editor (Top Right)**:

- "Automatic Name Optimizer": This gives you the ability to easy remove aesthetically unpleasing things from you channels either single or by category. (I tend to use the remove country prefix, symbols and multiple empty space.) This will vary by provider and how they name things.
- "Search & Replace/Remove": This gives you the ability to delete, remove and replace a specific word or characters from your channels easily.
- "Remove Duplicates": This allows you to remove duplicate channels based on url or name.
- "Add/Remove A Prefix or A Suffix": This allows you to easily add or remove a prefix or suffix. (The provider I use put "US:" in front of every channel. So I chose prefix, checked the remove prefix box and put "US:" into the text field.)

———

# 4. Pairing EPGs

1. In the **EPG Editor**, select the channels you want to pair with an EPG source.
2. Choose the EPG source:
    - Use the external source you added or IPTVEditor’s provided EPGs.
3. Use the automatic pairing tool or manually search for channel names to match them.

For sports or other channels without an available EPG:

- Use the **Sync Name** feature in the **Basic Editor**.
- Save, then go to the EPG Editor and select **Use Channel’s Name as EPG Event** to generate a dummy EPG.

———

# 5. Adding Logos

1. Open the **Logo Editor** and select streams to add logos.
2. Options for logos:
    - Auto-add logos for a category.
    - Manually add logos using URLs (e.g., copy image URLs from Google or Wikipedia).
3. Test your playlist in your app (like TiviMate) before adding missing logos.

———

# 6. Customizing Categories

1. Use the **Category Editor** to:
    - Rename categories.
    - Merge or sort categories.
    - Create new categories and move or duplicate channels into them.

For **Movies** and **TV Series**:

- Remove unwanted categories but avoid renaming or making custom categories, as provider updates may disrupt your changes.

———

# 7. Auto-Updater Setup

1. Go to **Auto Updater** in the bottom left and select **Manage Sources**.
2. Choose **Xtream** and proceed past the credentials screen.
3. When selecting sources to auto-update:
    - Check Channels, Movies, and TV Series.
    - Do not check “Disable Domain Security” unless necessary.
4. Map categories:
    - On the right, select your custom category names.
    - On the left, select the original category names from the provider.
    - Click **Add** to map each custom category to its source category.

———

# 8. Finalizing and Testing Your Playlist

1. Replace your old credentials in TiviMate with the new credentials from IPTVEditor:
    - In the Playlist Manager, click the “i” (information icon) next to your playlist.
    - Select **Xtream API** to get the server name, username, and password.
2. Set TiviMate to update the playlist and EPG frequently to reflect your changes.
3. Always duplicate your playlist in IPTVEditor before making significant changes to avoid losing your setup.

———

# 9. Applying Settings for Other Users to Use

There are two ways to apply your settings for others or manage multiple playlists while keeping adjustments centralized:

1. **Duplicate the Playlist**
    - In the **Playlist Manager**, duplicate your existing playlist.
    - Update the provider details (e.g., new credentials) on the duplicate playlist.
    - This creates a standalone version of your playlist with the same structure but linked to different provider details.
2. **Create a Customer from the Playlist**
    - If you want to maintain a single, central playlist for adjustments while linking it to multiple users:
        - Create a customer from your first playlist.
        - During the setup for the customer, change the credentials (e.g., username and password) to match the new user.
    - This method ensures that future adjustments to the main playlist will automatically reflect for all linked customers. It’s ideal for managing multiple users while avoiding repetitive work.

———

I have done some overall minor edits to this post. I want to use this as a starting ground to get into the more advanced side of iptveditor with things that took me some time to figure out. Please feel free to comment with suggestions of things to add/edit. I will do my best to check the comments and add/edit things as necessary.

Credits: u/mrrobvs and u/Capital2