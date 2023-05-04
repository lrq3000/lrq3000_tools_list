# lrq3000_tools_list
A non-exhaustive list of open-source tools I use very frequently:

## Note taking
* Zim Desktop Wiki, alternative to Evernote for note taking with hybrid WYSIWYG interface and live zim markup support (but lacks proper support for citations). Can copy/export to Markdown, HTML, etc.
* SyncThing, to synchronize notes and backups with E2EE encryption. Works particularly well with a plaintext markup note taking workflow (eg, synchronize zim/markdown notes between Zim Desktop Wiki and MarkText and Markor). Use SyncTrayzor on Windows and Syncthing-fork on Android.
* Markor, mobile Markdown/Zim/AsciiDoc editor and reader, on Android, with syntax highlighting and separated view mode to render the document. Very ergonomic, very well designed. Hopefully future support for MyST.
* MarkText, a WYSIWYG desktop Markdown editor.

## Productivity
* Element and Jitsi Meet for work chats and video meetings.
* OnionShare or Magic Wormhole (use [RymdPort](https://github.com/Jacalz/rymdport) for a GUI) or Lufi for decentralized, P2P E2EE file sharing of files of arbitrary size, with firewall traversal (ie, works both through internal networks and via internet). Sharedrop.io can be used for smaller files.
* [1List](https://github.com/lolo-io/OneList) for stash/everyday ToDo lists management on Android.
* Super Productivity and SuperProductivityAndroid for advanced ToDo lists managements with project management and timeboxing, which works on both desktop, web and mobile (Android, iOS). Can be synchronized via SyncThing.

## Backup
* SyncThing, alternative to cloud services such as DropBox and Google Photos, can synchronize files of arbitrary size between devices, and auto-backup photos from phone to computers. The server does not even need to be on all the time, it can just be switched on from time to time and SyncThing will synchronize when both devices are online. A little known fact is that SyncThing implements a LOT of [transfer optimizations](https://data.syncthing.net/) so that it is very sparse and uses as little connection as possible to synchronize files!
* FreeFileSync

## Chrome extensions
* [MarkDownload](https://github.com/deathau/markdownload), to save webpages content as markdown files - can be used as a Web Clipper for MarkText/Zim Desktop Wiki.
* [Copy-As-Markdown](https://github.com/yorkxin/copy-as-markdown/), to save list of tabs as a list of markdown links.
* [Automa](https://github.com/AutomaApp/automa), automated scaper using visual block programming.
* [Tabli](https://github.com/antonycourtney/tabli) to quickly sift through tabs.
* The Great Suspender to save memory and still have lots of tabs opened. The original was overtaken by a malicious actor, hence community forks are advised instead, such as [The Marvellous Suspender](https://github.com/gioxx/MarvellousSuspender) or [The Great Suspender notrack](https://github.com/aciidic/thegreatsuspender-notrack).
* Session Buddy to backup tabs or stash them away for later.

