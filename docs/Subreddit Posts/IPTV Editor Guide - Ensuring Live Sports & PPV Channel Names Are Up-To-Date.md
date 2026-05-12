Posted by u/jcumb3r in r/IPTVGroupBuy Tue Dec 31 2024 14:15:55 GMT+0000
	
These are all things I learned through trial & error with IPTV Editor, hopefully these tips will save someone else a bit of time.

**It does not update the playlist from your provider automatically**

This is most important for live sports or PPV events.  This means that when your provider updates the channels for sports/PPV, you won’t see the updated names in the guide on your player.

US NFL example: if the Broncos play the Chargers this week, the channel name from your provider is something like:

_Denver Broncos vs Los Angeles Chargers - 1600 ET_

Next week, when you go to view the NFL schedule, you’ll still see the Broncos/Chargers channel name, even though this week the Broncos play someone else.

**How to fix this:** In IPTV Editor, you must set up ‘auto updater’ for each playlist you are managing.  You need to tick the option for ‘sync streams name’ for the names of channels like this to be updated.

**If you change category names, it breaks auto-channel updates**

Now let’s say you have the great idea to change all your channel names like 'UK| CATEGORY NAME' to remove the “UK|”.  This works great until you want to sync things automatically because now the category from your provider doesn’t match the category name in your list.

**How to fix this:** In the configuration for auto-updater, you have to enable ‘custom categories auto sync’ and you have to map the provider name of the channel (UK| CATEGORY NAME) to the name you are now using (CATEGORY NAME).

**Even if you do both of the above, channel names still won’t auto-update**

**How to fix this:** To enable channel name updates, you must do two more things…

One: In the category editor, choose all of the categories where you need to sync channel names and tick the option for ‘sync channels name.’

Two: (this seems like it should be unnecessary, but until I did this as well, I didn’t always get the channel names to sync).  Go into the ‘basic editor’, and then open each of the categories you selected above and select all channels in the group.  Then tick the option here for ‘sync name.’

**Bonus tip:** to make the event information easier to see in your guide, in the EPG Editor, for all of these sports/PPV channels, choose the option for “Use channel’s name as EPG event.’.  This will copy the name of the channel into the EPG for every time slot in the day.  You still will have to read the name of the event to see when it is actually airing, but having this option makes it much easier to see the date/time of the event because it’s displayed across the time slot in the EPG vs in the very small area typically reserved for the channel name in the guide.

If anyone has other tips I missed... drop them in the comments below!