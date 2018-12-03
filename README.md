# Slack Mutli-Teams Overview.

This [Bitbar Plugin](https://getbitbar.com)
provides an overview of unread channels, unread messages and channel histories
using [Slack Legacy Token](https://api.slack.com/custom-integrations/legacy-tokens) (from now).

## Features:
* **multiple teams** (workspaces)
* **mark as read** and **open in slack** buttons
* display **all channels** or only unread ones

![preview](https://drive.google.com/uc?export=download&id=1vxQ5qr8opWaHhiqFlJZmi0oCOG3ik0uJ)

More screenshots:
* [How data is organized](https://drive.google.com/file/d/14qLm4YIySg-zPPHFtJcC9o-IuCMCoNnc/view?usp=sharing)
* [Invalid token behaviour](https://drive.google.com/file/d/1klZVGoDb-g9Bzw3cd884uf6A4xM01Fqe/view?usp=sharing)

## How to:
1. Move this file (`slack-multi-teams.1m.rb`) into your BitBar plugins directory.
[more information](https://github.com/matryer/bitbar#get-started)

2. Insert your Slack Legacy Token.
[how to get the token](https://api.slack.com/custom-integrations/legacy-tokens)

3. Enjoy a handy overview!

## Requirements:

* ruby 2.4

if not already preinstalled:
* net/http
* open-uri
* json

## Note:

Refresh rate is set to every minute, because 180+ lines of code and 4 requests are running per team (one channel, one user).

For a simple unread indicator check out [slack-unread by @mgjo5899](https://github.com/matryer/bitbar-plugins/blob/master/Messenger/slack-unread.1s.py)

Feel free to use, customize and contribute! :v:
