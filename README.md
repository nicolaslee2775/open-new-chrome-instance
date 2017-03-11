# Open New Chrome Instance (for Mac)

Open a new Google Chrome instance with `disable-web-security` flag. So that no cross-domain problem would occur.

#### Usage

Run the following command in Terminal (for MacOS only), where `/Volumes/Temp/ChromeDir` is the user data directory (choose a empty folder for first time).

```sh
open -na /Applications/Google\ Chrome.app/ --args --user-data-dir=/Volumes/Temp/ChromeDir --disable-web-security
```

#### References

- https://productforums.google.com/forum/#!topic/chrome/9nHBcjNW384
- http://askubuntu.com/questions/35392/how-to-launch-a-new-instance-of-google-chrome-from-the-command-line
- http://stackoverflow.com/questions/27708660/remove-parallels-binding-to-a-command-line-open-app-command