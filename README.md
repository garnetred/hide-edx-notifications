# Hide edX Notifications

## Abstract
This Chrome browser extension hides the open-by-default notifications pane that appears when going through a course on edX. 

## Tech Stack
This project uses vanilla JS, CSS, and HTML.

## Setup/Installation
You can clone the repo locally using `git clone`.

[This article](https://developer.chrome.com/docs/extensions/mv3/getstarted/development-basics/#load-unpacked) offers detailed instructions on loading an unpacked chrome extension. You can navigate to the chrome extensions page via the puzzle piece icon in the toolbar. Enable "developer mode" on the top-right. From there, you can click "load unpacked extension" and choose the folder via the popup. You should then see the notification bell icon appear in the toolbar. When you click on it, you can see "Hide edX Notifications."

On any url that includes `learning.edx.org/course` you should no longer see the notification pane to the right. In order to see it you'll first need to disable the extension. 

## Screenshots
Before:

<img width="669" alt="Screen Shot 2023-11-27 at 11 44 37 PM" src="https://github.com/garnetred/hide-edx-notifications/assets/59572865/11e13c78-9aa2-4f8a-a4a6-6ec087142c93">

After: 

<img width="263" alt="Screen Shot 2023-11-27 at 11 46 13 PM" src="https://github.com/garnetred/hide-edx-notifications/assets/59572865/b84b8978-ad0e-4180-a109-0276521a4a24">

Extension Icon:

<img width="31" alt="Screen Shot 2023-11-27 at 11 44 01 PM" src="https://github.com/garnetred/hide-edx-notifications/assets/59572865/ba19521f-0cc9-44e1-8e9b-42858c5b9566">

Extension Popup Window: 

<img width="203" alt="Screen Shot 2023-11-27 at 11 43 54 PM" src="https://github.com/garnetred/hide-edx-notifications/assets/59572865/28e772b7-3bb0-4202-b9a2-91986c7e8ed9">

## Future Changes
Eventually I hope to port all of my Chrome extensions to Firefox. 


