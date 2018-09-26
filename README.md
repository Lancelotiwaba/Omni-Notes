 ![icon](assets/icon.png)

Notes Pro From Omni-Notes

Note taking <b>open-source</b> application aimed to have both a <b>simple interface</b> but keeping <b>smart</b> behavior.

The project was inspired by the absence of such applications compatible with old phones and old versions of Android. It aims to provide an attractive look and follow the most recent design guidelines of the Google operating system.

**Follow the developments and post your comments and advice on Google+ Beta Community at http://goo.gl/eF6qqF**

*Help to keep translations updated is always welcome, if you want give a hand checkout the translation project at [Crowdin][2].*

<a href="https://https://play.google.com/store/apps/details?id=com.lancenotes.app" target="_blank">
<img src="https://play.google.com/intl/en_us/badges/images/generic/en-play-badge.png" alt="Get it on Google Play" height="90"/></a>

## Features

Currently the following functions are implemented:

1. Create Notes in text, pictures and checklist 
2. Add reminders on notes
3. Create Notes Categories 
4. Has a trash bin in case of accidental deletion 
5. Back Up and Restore Notes 
6. Multiple languages support
7. Set up your own preferred interface and navigation 
8. Add Map Location to notes
9. Add Automatic Map Location to notes
10. Sort Notes By Title, Creation Date, Last Modified Date and Reminder Date
11. Add Videos to Notes 
12. Supports swipe action (swipe through notes and swipe to trash) 
13. Set your preferred notification tones for reminders
14. Supports Vibration Notification
15. Set reminder intervals for notifications
16. Notes Privacy Through Password Protection
17. Create unlimited notes on a reduced view
18. Custom password recovery questions for instant password recovery 
19. Share notes
20. Sketch notes with your thumb
21. Record audio notes
22. Merge Notes
23. Change common notes to checklists and back
24. Create notes shortcuts

*Has No Ads*/

![](https://raw.githubusercontent.com/federicoiosue/Omni-Notes/fastlane/metadata/android/en-US/images/phoneScreenshots/02.png)
![](https://raw.githubusercontent.com/federicoiosue/Omni-Notes/fastlane/metadata/android/en-US/images/phoneScreenshots/03.png)
![](https://raw.githubusercontent.com/federicoiosue/Omni-Notes/fastlane/metadata/android/en-US/images/phoneScreenshots/04.png)
![](https://raw.githubusercontent.com/federicoiosue/Omni-Notes/fastlane/metadata/android/en-US/images/phoneScreenshots/05.png)

## Contributing

Due to the fact that I'm using [gitflow](https://github.com/nvie/gitflow) as code versioning methodology, you as developer should **always** start working on [develop branch](https://github.com/federicoiosue/Omni-Notes/tree/develop) that contains the most recent changes.

There are many features/improvements that are not on **my** roadmap but someone else could decide to work on them anyway: hunt for issues tagged as [Help Wanted](https://github.com/federicoiosue/Omni-Notes/issues?utf8=✓&q=label%3A"Help+wanted") to find them!

Feel free to add yourself to [contributors.md](https://github.com/federicoiosue/Omni-Notes/blob/develop/contributors.md) file.

**Don't forget to contribute to original code! Don't be selfish or lazy!**

### Test code contributions

All code changes and additions **must** be tested.
See the [related section](#test) about this.

### Fork project

When forking the project you'll have to modify some files that are strictly dependent from my own development / build / third-party-services environment. Files that need some attention are the following:

- *gradle.properties*: this is overridden by another file with the same name inside the *omniNotes* module. You can do the same or leave as it is, any missing property will let the app gracefully fallback on a default behavior.
- *.travis.yml*: if you use [TravisCI](https://travis-ci.org/) as continuous integration platform and a SonarQUBE instance for code quality analysis you'll have to modify this file according to your needs.

## Developed with love and passion by and Recompiled by Lance Apps


* Federico Iosue - [Website](https://federico.iosue.it)
* [Other contributors](https://github.com/federicoiosue/Omni-Notes/blob/master/https://github.com/federicoiosue/Omni-Notes/blob/master/CONTRIBUTORS.md)



## License


    Copyright 2013-2018 Federico Iosue
    
    This program is free software: you can redistribute it and/or modify
    it under the terms of the GNU General Public License as published by
    the Free Software Foundation, either version 3 of the License, or
    (at your option) any later version.
    
    This program is distributed in the hope that it will be useful,
    but WITHOUT ANY WARRANTY; without even the implied warranty of
    MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
    GNU General Public License for more details.
    
    You should have received a copy of the GNU General Public License
    along with this program.  If not, see <http://www.gnu.org/licenses/>.


[2]: https://crowdin.net/project/omni-notes/
[2]: https://crowdin.net/project/omni-notes/
