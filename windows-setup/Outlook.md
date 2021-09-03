# Outlook

## Place OST files (storeage) on another drive

Set the registry key `ForcePSTPath` to your desired location.

There is also a `ForceOSTPath` key (so maybe set both), but the *PST* key is the one that effects IMAP mail accounts.

Also, this needs to be set before the Outlook profile is created.

[Source](https://www.slipstick.com/outlook/config/how-to-move-the-imap-personal-folder-pst/)

## (Existing) HTML Signatures

1. Create the signuature in Outlook that you want to use.
2. Replace the existing pre-generated HTML file. These are located at `%USERDIR%\AppData\Roaming\Microsoft\Signatures`.

I couldn't get it to link to an on-disk image.

Also, Outlook allows you to set different signatures for "new" emails and forwards/replies.

[Hints](https://www.timeatlas.com/add-outlook-html-signature/)
