# OtherBrowser
[Download](https://github.com/grgggy/OtherBrowser/releases/latest) | [Source Download](https://sites.google.com/site/xtrathreads/OtherBrowser.zip?attredirects=0)

## Getting Started
### Setup
- Drag OtherBrowser.app to the ~/Applications folder.
- Right-click on OtherBrowser and select “Open” to launch it once.

_All this does is get you past macOS’s gatekeeper. The app will launch and immediately quit._

### Bookmarklets
- Copy the browser appropriate bookmarklet.
- Go to the browser you want to install the bookmarklet it in, create a new bookmark and paste the bookmarklet in as its address.

#### Bookmarklet to send current page to Chrome
`javascript:var%20y=document.location.href;y=y.substring(y.indexOf(%27://%27));y=%27otherbrowser-chrome%27+y;window.location=y;`

#### Bookmarklet to send current page to Safari
`javascript:var%20y=document.location.href;y=y.substring(y.indexOf(%27://%27));y=%27otherbrowser-safari%27+y;window.location=y;`

## Credits
AppleScript by [David Halter](http://davidhalter.tumblr.com/post/30466837244/otherbrowser)
