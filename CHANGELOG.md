# Change Log
All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## Unreleased
...

## 5.0.1 - 
### Fixed
- Get access token (spam likes and top interaction is not working)

## 5.0.0 - 2021-12-09
### Fixed
- Get access token, fb dtsg

## 4.4.4 - 2021-09-22
### Fixed
- Download facebook video (some urls cannot be received)

## 4.4.3 - 2021-04-22
### Fixed
- Group management
- Top interaction
- Spam like (fix logic code when user enter username url)

### Removed
- Scan group other joined

## 4.4.2 - 2021-03-26
### Fixed
- Group management
- Scan group of friend (fix logic code when user enter username url)
- Find the first message (fix logic code when user enter username url), fix bug: If your friend deletes the chat, that tool does not count

### Removed
- Unseen message

## 4.4.1 - 2021-02-27
### Fixed
- Count time spend on facebook
- Find the first message (api get avatar doesn't work)
- Unseen (old api doesn't work)
- Download video facebook
- Stop load more newsfeed
- Custom theme (Facebook)

### Removed
- Return old facebook layout
- Who is online
- Donation js
- Dark/custom theme for Google, Youtube red, Website blocker (Policy violation: https://developer.chrome.com/docs/extensions/mv2/single_purpose/)
- Change the message alert tone with google speech
- Emoji

## 4.4.0 - 2021-02-10
### Fixed
- Fix avatar
- Disable scan friend online
- Return to the old facebook layout

## 4.3.2 - 2020-10-09
### Fixed
- Scan group
- Scan group other joined
- Remove tabs permission

## 4.3.1 - 2020-06-22
### Fixed
- Get dtsg

## 4.3.0 - 2020-04-28
### Fixed
- Load menu and report dialog in a common way
- Get the page your friend liked
- Get the group your friend joined

## 4.2.2 - 2020-04-16
### Added
- Facebook Kount: add column Stranger; add multi language for table
- Top interaction: add multi language for table
- Who is online: add multi language for table
- Group and page management: add multi language for table

### Fixed
- Top interaction: after get data => order by comment; remove search by reaction
- Facebook Kount: fix error not working

## 4.2.1 - 2020-03-04
### Fixed
- Fix bug UI: missing menu Top interaction
- Fix bug UI: change column ID -> Multi select in table Top interaction

### Added
- Add user id when user report or feedback

## 4.2.0 - 2020-02-29
### Added
- Top interaction
- Add donation to dashboard
- Add version to dashboard

### Changed
- Title Facebook Kount
- Group and page management (choose all: only select all item on current page)
- Mutli language for donation

### Removed
- Paypal donation

## 4.1.5 - 
### Added
- Momo donation
- Bank number

### Fixed
- Fb Kount
- Group and page management
- See the first message
- Profile guard/protect avatar
- Spam like

### Changed
- Use js, css from extension (don't use from server)

### Removed
- Unghotoi donation

## 4.1.4 - 2019-09-30
### Fixed
- Facebook dark theme

## 4.1.3 - 2019-09-27
### Changed
- Compile js code by Closure Compiler

## 4.1.2 - 2019-09-25
### Changed
- Unminify js code

## 4.1.1 - 2019-09-24
### Changed
- Deobfucate js code
- Minify js code

## 4.1.0 - 
### Added
- Vrdonate donation

### Changed
- Enable Group and page management
- Enable See the first message
- Enable Storm(spam) likes your friend

### Removed
- Bao Kim donation

## 4.0.0 - 2019-08-27
### Fixed
- Get token

### Changed
- Disable Group and page management
- Disable See the first message
- Disable Storm(spam) likes your friend

## 3.0.0 - 2019-05-30
### Added
- Profile Picture Guard.
- Who is online.
- See the first message
- Storm(spam) likes your friend.

## 2.0.0 - 2019-03-08
### Fixed
- Facebook Kount.
- Group and page management.
- Download video from facebook.

### Changed
- Name (change to user id).

### Removed
- Profile Picture Guard.
- Who is online.
- See the first message
- Storm(spam) likes your friend.

## 1.0.1 - 2019-01-01
### Added
- Enter event (Message alert tone with google speech).

### Fixed
- Facebook Kount (Missing avatar group, group name is null).

## 1.0.0 - 2018-12-23
### Added
- Support Vietnamese.
- Add website blocking to the right click menu.
- Download video from Facebook.
- Count the time you spend on facebook.
- Storm(spam) like.
- Enter event (protect avatar, find the first message).
- Clear button (protect avatar, find the first message).

### Changed
- Report bug/Feedback: Simple, easier to send messages.
- Datetime format.
- User interface and content notifications for users.
- Facebook Kount (group)

### Fixed
- User enter invalid url (protect avatar, find the first message).
- Website blocker (website url is empty).
- Message alert tone with google speech.
- Get token.

## 0.0.2 - 2018-11-29
### Added
- Website blocker.
- Change the message alert tone with google speech.
- Tips.

### Changed
- Font weight.
