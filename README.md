# SLCB Channel Points Random Gif

This script allows the user to add up to 5 Twitch channel point rewards to display random gifs/images via an obs browser source.

## Installing

This script was built for use with Streamlabs Chatbot.
Follow instructions on how to install custom script packs at:
https://github.com/StreamlabsSupport/Streamlabs-Chatbot/wiki/Prepare-&-Import-Scripts

Click [Here](https://github.com/Encrypted-Thoughts/SLCB-ChannelPointsRandomGif/blob/master/ChannelPointsRandomGif.zip?raw=true) to download the script pack.

Once installed you will need to provide an oAuth token. You can get one by clicking the Get Token button in script settings.

![token](https://user-images.githubusercontent.com/50642352/82402817-f8165480-9a22-11ea-8810-fc93899d785a.png)

You will also need to give the script access to broadcast streamlabs events. This can be achieved by right clicking on the script in Streamlabs Chatbot and selecting "Insert API Key".

![api key](https://user-images.githubusercontent.com/50642352/83985340-7701fd00-a8fe-11ea-9aca-393d6dc7d4b4.png)

After that you should be able to add a new Browser source in OBS and point it to "index.html" located in the "overlay" folder in the script folder. If you're unsure how to locate the streamlabs custom scripts folder you can select "Open Script Folder" shown in the above step.

![index](https://user-images.githubusercontent.com/50642352/83985548-48d0ed00-a8ff-11ea-94f8-0e56c4f42d64.png)

## Use

Once installed you just need to add custom channel point rewards to your twitch channel and then match the names of the reward to a Twitch Reward event in the script settings.

![image](https://user-images.githubusercontent.com/50642352/83985380-a6b10500-a8fe-11ea-96f0-c3edbd58e2d1.png)

![image2](https://user-images.githubusercontent.com/50642352/83985417-d102c280-a8fe-11ea-9449-ce6042eb2ecb.png)

## Author

EncryptedThoughts - [Twitch](https://www.twitch.tv/encryptedthoughts)

## References

This script makes use of TwitchLib's pubsub listener to detect the channel point redemptions. Go check out their repo at https://github.com/TwitchLib/TwitchLib for more info.

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details

