# scrviz-profile
Bruce Mcpherson's profile for scrviz - https://scrviz.web.app

This is my profile for https://scrviz.web.app

If you want to enrich your profile from the standard data from github - which looks like this
![image](https://user-images.githubusercontent.com/1894020/110619521-d5ab1e80-818f-11eb-82a7-3e1f2c178c30.png)

You can create a scrviz-profile.json in any of your repositories (or even better make a dedicated repository for it). See my file in this repo for an example, and you can add anything you like (but please respect the other scrviz users and make it relevant and appropriate)

My scrviz profile renders like this
https://scrviz.web.app?owner=brucemcpherson

For more info on scrviz see https://ramblings.mcpher.com/vizzy-scrviz/

## properties

| name | purpose |
| --- | --- |
|scrviz.owner.login | this should match your github login name. It's used to verify that the profile matches the owner who is hosting it and is mandatory |
|scrviz.owner.rows | an array of rows - each one will render a row in the scrviz profile |

#### each row can have these properties

all are optional (except visibile) and will be replaced by some approriate default value if not supplied. 

| name | purpose |
| --- | --- |
| description | the description. If there is a link present, this will be used as the text for the link |
| link | an external link to some more info |
| tip | a tooltip to display when hovering over the description |
| icon | a material design icon to use to decorate this row. It take the format of, for example, mdi-linkedin. The full directory of icons is here https://materialdesignicons.com/ |
| visible | true/false - whether to show it in scrviz - this is mandatory. If not present the row won't be shown. Think of it as agreeing to scrviz conditions |

#### Copying links

For convenience, each row is wired up to be able to be copied to the clipboard if you click on the icon. If there is a link present it'll copy that, otherwise it'll copy the text





