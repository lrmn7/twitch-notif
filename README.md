## 🔧 Configuration:
```json
{
    token: '',
    CLIENT_ID: '',
    twitch_id: '',
    twitch_token: '',
    twitch_secret: '',
    activities: [
        `Love has a cost, and both of us lost`,
        `Mostly sleepless🌛`,
        `Mewwme's Everywhere`,
    ],
    defaultStatusType: 1, // 1: Playing, 2: Streaming, 3: Listening, 4: Watching
    defaultStatus: "dnd", // idle, dnd, online
}
```

1. The "token" is the token of your discord bot. (If you haven't one, you can create one here: https://discord.com/developers/applications)

2. You can blank the "twitch_token" part for the moment.

3. In the twitch_id value, you will need to put the id of your twitch application here. (If you haven't one, you can create one here: https://dev.twitch.tv/console/apps)

4. In the twitch_secret value, you will need to put the secret of your twitch application. (If you haven't one, you can create one here: https://dev.twitch.tv/console/apps)

5. Finally you will need to put the id of your discord bot in the CLIENT_ID value (If you don't know how to get it, simply go on the page of your discord bot and on the "General informations" page, you will find a section "Application id" and then copy it)

When everything is ready, open a terminal in the folder and write: ```node index.js or node .```

📝 Very important note:

Don't forget to add the ```mewwme.database.json``` file if it is not done yet and see if there's ```{}``` in the file.

## Members

- Add your twitch username

/add_your_twitch [your_username]

- Edit the twitch username that you added

/change_your_twitch [your_new_username]

- Display your current twitch

/your_twitch

- Delete my twitch from the bot for a certain server

/delete_your_twitch

## Admins

- Set the channel to send notifications

/set_notification_channel [channel_notification]

- Change the twitch of a member

/change_the_twitch_of_a_member [user]  [new_twitch]

- Delete the twitch of a member

/delete_the_twitch_of_a_member [user]