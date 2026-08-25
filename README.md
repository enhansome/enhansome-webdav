# Awesome WebDAV with stars

A curated list of awesome apps that support the WebDAV protocol ([RFC 4918](https://tools.ietf.org/html/rfc4918)) and tools related to it.

## Contents

* [Resources](#resources)
  * [General](#general)
  * [Client guides](#client-guides)
  * [Server guides](#server-guides)
* [Servers](#servers)
  * [Standalone](#standalone)
  * [Web servers](#web-servers)
  * [Docker images](#docker-images)
* [PWA and online apps](#pwa)
* [Command line tools](#cli)
* [Desktop apps](#desktop-apps)
  * [File managers and tools](#file-managers-and-tools)
  * [Backup and sync](#backup-and-sync)
  * [Other apps](#other-apps)
* [Mobile apps](#mobile-apps)
  * [Android](#android)
  * [iOS](#ios)
* [Libraries](#libraries)
  * [C](#c)
  * [C++](#c-1)
  * [Go](#go)
  * [Java](#java)
  * [JavaScript](#javascript)
  * [Python](#python)
* [Cloud providers](#cloud-providers)
* [Extensions](#extensions)

## Resources

### General

*General information about WebDAV*

* [Wikipedia article](https://en.wikipedia.org/wiki/WebDAV)
* [DAV Frequently Asked Questions](http://www.webdav.org/other/faq.html)
* Book [WebDAV: Next-Generation Collaborative Web Authoring: Next-Generation Collaborative Web Authoring](https://www.amazon.com/WebDAV-Next-Generation-Collaborative-Web-Authoring/dp/0130652083) - the author, goes into not only the details, but explains the problems with some of the specs (especially DeltaV).
* [Exploiting WebDAV](https://vk9-sec.com/exploiting-webdav/)
* [WebDavServer.com](https://webdavserver.com/) an online demo to test

### Client guides

*Mounting a WebDAV volume if you have an existing server*

* [Connect to or disconnect from a WebDAV server on Mac](https://support.apple.com/en-au/guide/mac-help/mchlp1546/mac)
* [Accessing WebDAV with Windows](https://help.dreamhost.com/hc/en-us/articles/216473357-Accessing-WebDAV-with-Windows)
* [How do I establish a WebDAV connection in Gnome 3?](https://askubuntu.com/questions/233242/how-do-i-establish-a-webdav-connection-in-gnome-3)

### Server guides

*Setting up a WebDAV server*

* [How To Configure WebDAV Access with Apache on Ubuntu 14.04](https://www.digitalocean.com/community/tutorials/how-to-configure-webdav-access-with-apache-on-ubuntu-14-04)
* [Run your own WebDAV server with Docker](https://docs.bytemark.co.uk/article/run-your-own-webdav-server-with-docker/)
* [WebDAV Share with Lighttpd](https://openwrt.org/docs/guide-user/services/nas/webdav) - instruction for OpenWrt WiFi routers firmware.

## Servers

### Standalone

*Standalone servers and personal cloud solutions specifically built for WebDAV and its extensions*

* [copyparty](https://github.com/9001/copyparty) ⭐ 46,361 | 🐛 254 | 🌐 Python | 📅 2026-08-23 - a portable file server with resumable uploads, dedup, WebDAV, SFTP, FTP, TFTP, zeroconf, media indexer, thumbnails. It has an [Android app](https://f-droid.org/packages/me.ocv.partyup/).  `MIT` `Python`
* [Stalwart](https://github.com/stalwartlabs/stalwart) ⭐ 14,328 | 🐛 73 | 🌐 Rust | 📅 2026-08-24 - Open-source Mailserver and WebDAV, CalDAV and CardDAV server written in Rust.
* [SFTPGo](https://github.com/drakkan/sftpgo) ⭐ 12,444 | 🐛 173 | 🌐 Go | 📅 2026-08-24 - SFTP server with optional FTP/S and WebDAV support.
* [miniserve](https://github.com/svenstaro/miniserve) ⭐ 7,814 | 🐛 91 | 🌐 Rust | 📅 2026-08-01 - A file sharing server, supports read-only WebDAV
* [hacdias-webdav](https://github.com/hacdias/webdav) ⭐ 5,797 | 🐛 20 | 🌐 Go | 📅 2026-08-23 - A simple yet configurable WebDAV server written in Go.
* [Davis](https://github.com/tchapi/davis) ⭐ 741 | 🐛 22 | 🌐 PHP | 📅 2026-07-30 - a simple interfacefor `sabre/dav` based on `Symfony` and `Bootstrap`, largely inspired by `Baïkal`.
* [dave](https://github.com/micromata/dave/) ⚠️ Archived - a simple WebDAV server written in Go. `Apache-2.0` `Golang`
* [Seafile](https://github.com/haiwen/seafdav) ⭐ 92 | 🐛 0 | 🌐 Python | 📅 2026-08-19 - A webdav server written in Python
* [asgi-webdav](https://github.com/rexzhang/asgi-webdav) ⭐ 89 | 🐛 9 | 🌐 Python | 📅 2026-08-24 - an asynchronous WebDAV server, Support multi-provider, multi-account and permission control. `MIT` `Python`
* [QuickDAV](https://sciactive.com/quickdav/) - Network file transfer app. [Sources](https://github.com/sciactive/quickdav) ⭐ 59 | 🐛 0 | 🌐 Svelte | 📅 2026-03-15. `Apache-2.0`
* [tolsen/limestone](https://github.com/tolsen/limestone) ⭐ 9 | 🐛 0 | 🌐 C | 📅 2011-03-14 - Advanced WebDAV server backed by a Postgres database. Supports ACL, Search, BIND, Redirect, and partial DeltaV.
* [tolsen/limeberry](https://github.com/tolsen/limeberry) ⭐ 4 | 🐛 0 | 🌐 C | 📅 2011-01-28 - WebDAV server (Rails 1.2)
* [WebDAV VFS gate](https://github.com/a-langer/webdav-vfs-gate) ⭐ 3 | 🐛 1 | 🌐 Java | 📅 2024-09-24 - Open source JEE application for web containers, such as Tomcat, Jetty, JBoss and similar.
* [FuguHub](https://fuguhub.com/) - a personal cloud server with a web UI.
* [Group-Office](https://www.group-office.com/) - Open Source CRM and Groupware with CalDAV, CardDAV and WebDAV.
* [Nextcloud](https://nextcloud.com/) - Collaboration and communication platform: includes files, calendar, contacts, mailclient, chat, videoconferencing and much more. [Try it](https://try.nextcloud.com), [Docs WebDAV](https://docs.nextcloud.com/server/latest/user_manual/en/files/access_webdav.html), [Docs calDAV](https://docs.nextcloud.com/server/latest/admin_manual/groupware/calendar.html), [Docs CardDAV](https://docs.nextcloud.com/server/latest/admin_manual/groupware/contacts.html). `AGPL-3.0` `PHP`
* [Nephele Serve](https://www.npmjs.com/package/nephele-serve) - File System or S3 Backed WebDAV Server. `Apache-2.0`
* [ownCloud](https://doc.owncloud.org/server/latest/user_manual/files/access_webdav.html) - Personal cloud solution, brother project to the `NextCloud`.  `AGPL-3.0` `PHP`
* [phởdav (a.k.a. chezdav)](https://wiki.gnome.org/phodav) - A minimal open source WebDAV server, ideal for sharing one folder (for FreeBSD, Linux, and Windows).
* [sabre/dav](https://sabre.io/) - Open source CardDAV, CalDAV and WebDAV server.
* [weborf](https://ltworf.github.io/weborf/) - a minimal HTTP server to share your files. Has a GUI [qweborf](https://ltworf.github.io/weborf/qweborf.html).
* "Written in Rust". They all are similar to weborf by functionality but more advanced and fancy
  * [sigoden/dufs](https://github.com/sigoden/dufs) ⭐ 10,657 | 🐛 12 | 🌐 Rust | 📅 2026-06-29
  * [thecoshman/http](https://github.com/thecoshman/http) ⭐ 493 | 🐛 6 | 🌐 Rust | 📅 2026-08-07
  * [messense/dav-server-rs](https://github.com/messense/dav-server-rs) ⭐ 241 | 🐛 2 | 🌐 Rust | 📅 2026-05-04 library for WebDAV and there are a lot of [small webservers based on it](https://github.com/messense/dav-server-rs/network/dependents) ⭐ 241 | 🐛 2 | 🌐 Rust | 📅 2026-05-04.

### Web servers

*Web servers that support WebDAV or have modules to enable WebDAV support*

* [Apache HTTP Server](https://httpd.apache.org/docs/2.4/mod/mod_dav.html) - Supports WebDAV via the `mod_dav` module.
* [Caddy](https://caddyserver.com/docs/modules/http.handlers.webdav) - Supports WebDAV via the `http.handlers.webdav` module.
* [lighttpd](https://redmine.lighttpd.net/projects/1/wiki/Docs_ModWebDAV) - Supports WebDAV via the `mod_webdav` module.
* [Microsoft Internet Information Services (IIS)](https://docs.microsoft.com/en-us/iis/configuration/system.webServer/webdav/) - Supports WebDAV starting with version 7.0 when *WebDAV Publishing* is enabled.
* [nginx](https://nginx.org/en/docs/http/ngx_http_dav_module.html) - Supports a subset of WebDAV methods via the `ngx_http_dav_module` module.
  * [`nginx-dav-ext-module`](https://github.com/arut/nginx-dav-ext-module) ⭐ 511 | 🐛 32 | 🌐 C | 📅 2024-05-18 - Unofficial module that adds full WebDAV support.

### Docker images

*Docker images for easily deploying a WebDAV server*

* [bytemark/webdav](https://hub.docker.com/r/bytemark/webdav) - Based on Apache HTTP Server.
* [ugeek/webdav](https://hub.docker.com/r/ugeek/webdav) - Based on nginx.
* [stalwartlabs/stalwart](https://hub.docker.com/r/stalwartlabs/stalwart) - Open-source WebDAV, CalDAV and CardDAV server written in Rust.

<a name="pwa" />

## PWA and online apps

Online apps that can connect directly to your WebDAV share. You'll need a CORS enabled.
See an example [WebDAV with CORS using Lighttpd](https://gist.github.com/stokito/0a6274106d407ba6d9fb776e7773445d)

* [Supper Productivity](https://app.super-productivity.com/) - A powerful TODO App. [Source code](https://github.com/johannesjo/super-productivity) ⭐ 21,573 | 🐛 1,476 | 🌐 TypeScript | 📅 2026-08-24.
* [KeeWeb](https://app.keeweb.info/) - A password manager [Source code](https://github.com/keeweb/keeweb) ⭐ 12,988 | 🐛 440 | 🌐 HTML | 📅 2026-05-08
* [Diffuse](https://diffuse.sh/) - an onine music player [Source code](https://github.com/icidasset/diffuse) ⭐ 874 | 🐛 11 | 🌐 JavaScript | 📅 2026-08-24.
* [Davros](https://github.com/mnutt/davros) ⭐ 301 | 🐛 56 | 🌐 JavaScript | 📅 2026-08-13 - a web file manager in NodeJS that uses WebDAV as a protocol. Used by [Sandstorm.io](https://sandtorm.io)
* [OxIDE](https://github.com/bootrino/reactoxide) ⚠️ Archived - a simple code editor that you can add to your ReactJS projects. `MIT` `TypeScript`
* [webdav-js](https://github.com/dom111/webdav-js) ⭐ 111 | 🐛 33 | 🌐 TypeScript | 📅 2024-02-26 - A simple WebDAV file manager for use as a bookmarklet, or integration into a web server. May be used as a simplest in-browser UI
* [webdav-browser](https://github.com/WebDAVDevs/webdav-browser-extension) ⭐ 35 | 🐛 6 | 🌐 JavaScript | 📅 2024-11-09 - a browser extension to browse a URL as a WebDAV share directly. `0BSD`, `JavaScript`
* [DevNotes](https://rainu.github.io/dev-notes/) - A notes app. [Source code](https://github.com/rainu/dev-notes) ⭐ 11 | 🐛 22 | 🌐 Vue | 📅 2023-01-07
* [webdave](https://katomaso.github.io/webdave/) - A file manager. [Source code](https://github.com/katomaso/webdave) ⭐ 6 | 🐛 2 | 🌐 JavaScript | 📅 2022-06-29
* [Astiga](https://asti.ga/) - an onine music player. `Proprieatary`
* [Filerun](https://filerun.com/) - a paid self hosted cloud. `Proprieatary`
* [TiddlyWiki](https://tiddlywiki.com/) - A non-linear notebook for capturing, organising and sharing complex information

## Command line tools

<a name="cli" />

* [WebDAV-AudioPlayer](https://github.com/StefH/WebDAV-AudioPlayer) ⭐ 26 | 🐛 2 | 🌐 C# | 📅 2026-07-25 - a simple AudioPlayer (web-based Blazor & Windows WinForms).
* [tolsen/Prestan](https://github.com/tolsen/Prestan) ⭐ 4 | 🐛 0 | 🌐 C | 📅 2013-06-05 - a WebDAV performance benchmark
* [tolsen/rubydav](https://github.com/tolsen/rubydav/tree/master/test) ⭐ 3 | 🐛 0 | 🌐 Ruby | 📅 2010-12-17 - a test suite for WebDAV server
* [cadaver](https://notroj.github.io/cadaver/) - A command-line interactive FTP-like WebDAV client.
* [curl](https://gist.github.com/stokito/cf82ce965718ce87f36b78f7501d7940) - a low level command line http client that allows to query WebDAV methods.
* [davfs2](https://savannah.nongnu.org/projects/davfs2) - Allows mounting a WebDAV server as a local filesystem (for Linux).
* [DaviX](https://davix.web.cern.ch/davix/docs/devel/) - A client for WebDAV and Amazon S3 for Windows, macOS and Linux. `LGPL` `C++`
* [GNOME gvfs-mount](https://jeromebelleman.gitlab.io/posts/filesystems/gvfs/#from-a-webdav-server) - Mounting a WebDAV with GNOME Virtual Filesystem in user space. Linux.
* [KDE kioclient](https://manpages.ubuntu.com/manpages/bionic/en/man1/kioclient.1.html) - supports basic operations e.g. `kioclient cp file.txt 'webdavs://user@example.com/dav/`
* [rclone](https://rclone.org/) - Supports WebDAV as a backup target and [can itself act as a WebDAV server](https://rclone.org/commands/rclone_serve_webdav/) (for Windows, Mac and Linux).
* [litmus](https://notroj.github.io/litmus/) - a test suite from author of neon, which aims to test whether a server is compliant with the WebDAV protocol. `GPL-2.0` `C`

## Desktop apps

<a name="desktop-file-managers" />

### File managers and tools

*General purpose apps to browse and manage files on a WebDAV server*

* [far2l](https://github.com/elfmz/far2l) ⭐ 2,210 | 🐛 477 | 🌐 C++ | 📅 2026-08-24 - A heavily rewritten Linux and MacOS port of FAR Manager. Has a NetRocks plugin with WebDAV support.
* [CrossFTP](https://www.crossftp.com/) - Free client software that supports many protocols, including WebDAV (for Windows, Mac and Linux).
* [Far Manager](https://www.farmanager.com/) - A Norton Comander like file manager for Windows. Has a NetBox plugin with WebDAV support.
* [FileZilla Pro](https://filezillapro.com/how-to-connect-to-webdav/) - File transfer tool that supports many protocols, including WebDAV (for Windows, Mac and Linux).
* [PotPlayer](https://potplayer.tv) - Windows only. `Proprietary`
* [SmartFTP](https://www.smartftp.com/) - A file transfer program. `Proprietary`
* [UIVI](https://sourceforge.net/projects/uivi/) - a Java GUI client. Can be runned as JNLP applet. `Public Domain` `Java`
* [WinSCP](https://winscp.net/) - A popular SFTP client that also supports WebDAV (for Windows). `Proprietary`
* [WebDrive](https://webdrive.com/) - A drive mapping utility. Windows, OS X, Android and iOS. `Proprietary`

#### macOS only

* [Commander One](https://mac.eltima.com/file-manager.html) - A file manager for macOS
* [CloudMounter](https://mac.eltima.com/mount-cloud-drive.html) - mounting cloud storages for macOS
* [Cyberduck](https://cyberduck.io/) - Libre server and cloud storage browser with WebDAV support (for Windows and Mac).
* [ForkLift](https://binarynights.com/) - A dual pane file manager and file transfer client for macOS.
* [Mountain Duck](https://mountainduck.io/) - Lets you mount server and cloud storage including WebDAV as a disk (for Windows and Mac).
* [Transmit](https://panic.com/transmit/) - A file transfer apps for macOS

<a name="desktop-other-apps" />

### Backup and sync

*Apps used for backup and/or synchronizing data between multiple destinations*

* [Duplicati](https://github.com/duplicati/duplicati) ⭐ 14,930 | 🐛 633 | 🌐 C# | 📅 2026-08-24 - Supports WebDAV as a backup target (for Windows, Mac and Linux).
* [ioBroker.backitup](https://github.com/simatec/ioBroker.backitup) ⭐ 72 | 🐛 6 | 🌐 TypeScript | 📅 2026-08-22 - a module for ioBroker home automation.
* [rclone](https://rclone.org/) - Supports WebDAV as a backup target and [can itself act as a WebDAV server](https://rclone.org/commands/rclone_serve_webdav/) (for Windows, Mac and Linux).
* [Duplicacy](https://duplicacy.com/) - Beta support for WebDAV as a backup target (for Windows, Mac and Linux).
* [GNOME Déjà Dup](https://wiki.gnome.org/Apps/DejaDup) - Supports WebDAV as a backup target.

### Other apps

*Apps and browser extensions that support WebDAV in some form, e.g. for backup and sync*

* [Table Habit](https://github.com/FriesI23/mhabit) ⭐ 1,458 | 🐛 78 | 🌐 Dart | 📅 2026-08-24 – Micro habits tracking app with [sync via WebDAV](https://github.com/FriesI23/mhabit/wiki/Feature%EA%9E%89-WebDAV-Sync) ⭐ 1,458 | 🐛 78 | 🌐 Dart | 📅 2026-08-24. `AL2` `Dart`  `Apache-2.0`
* [Buttercup](https://buttercup.pw/) - A password manager. [Source code](https://github.com/buttercup)
* [Cryptomator](https://cryptomator.org/) - a tool to encrypt files and backup.
* [KODI](https://kodi.tv/) - An advanced media player for smart TV: Raspberry Pi, Android, tvOS.
* [gnome-user-share](https://gitlab.gnome.org/GNOME/gnome-user-share) - configure an Apache WebDAV directly from Nautilus
* [Gnome Gnote](https://wiki.gnome.org/Apps/Gnote) - app for taking notes with WebDAV sync.
* [KeePass Password Safe](https://keepass.info/) - Password manager that supports WebDAV sync (for Windows).
* [PhotoPrism](https://photoprism.app/) AI-Powered Photos App. Supports [sync by WebDAV](https://docs.photoprism.app/user-guide/sync/webdav/)
* [Floccus](https://floccus.org/) - Browser extension for bookmark sync that supports WebDAV (for Chrome, Firefox and Edge).
* [RetroArch](https://retroarch.com) - A frontend for emulators and game engines that can use WebDAV for backing up game saves.
* [Stylus](https://add0n.com/stylus.html) - Browser extension for custom CSS that can sync with WebDAV.
* [Violentmonkey](https://violentmonkey.github.io/) - A web browser extension for UserJS management that can sync with WebDAV.
* [Zotero](https://www.zotero.org/) - an easy-to-use desktop app to collect, organize, annotate, cite, and share research. `AGPLv3` `JavaScript`

## Mobile apps

### Android

<a name="android-file-managers" />

#### File managers and backup

*General purpose apps to browse and manage files on a WebDAV server*

* [Android DataBackup](https://github.com/XayahSuSuSu/Android-DataBackup) ⭐ 7,265 | 🐛 187 | 🌐 Kotlin | 📅 2026-08-21
* [NextCloud Android App](https://github.com/nextcloud/android) ⭐ 5,526 | 🐛 1,555 | 🌐 Kotlin | 📅 2026-08-25 `GPL-2.0`
* [Round Sync](https://github.com/newhinton/Round-Sync) ⭐ 2,324 | 🐛 193 | 🌐 Java | 📅 2025-11-16 Rclone sync for Android (fork of RCX). `GPL-3.0`
* [RCX](https://github.com/x0b/rcx) ⭐ 2,032 | 🐛 145 | 🌐 Java | 📅 2023-11-26 Rclone sync for Android (unmaintained, use Round Sync). `GPL-3.0`
* [alexbakker/webdav-provider](https://github.com/alexbakker/webdav-provider) ⭐ 261 | 🐛 3 | 🌐 Kotlin | 📅 2026-07-25 - WebDAV storage to other apps through Android's Storage Access Framework (SAF). `GPL-3.0`
* [EasySync](https://github.com/phpbg/easysync) ⭐ 232 | 🐛 26 | 🌐 Kotlin | 📅 2026-08-15 - backup and sync files with WebDAV share. `MIT`
* [ndl/wedaban](https://github.com/ndl/wedaban) ⭐ 2 | 🐛 0 | 🌐 Kotlin | 📅 2020-09-28 - an implementation of Android Backup API for backups to WebDAV servers. `WIP`
* [Cx File Explorer](https://play.google.com/store/apps/details?id=com.cxinventor.file.explorer) - File manager that has a WebDAV support built in. `Proprietary`
* [DAVx5](https://www.davx5.com/) - WebDAV, CalDAV and CardDAV client for Android.
* [Total Commander](https://play.google.com/store/apps/details?id=com.ghisler.android.TotalCommander) - File manager that has a WebDAV plugin. `Proprietary`
* [X-plore File Manager](https://play.google.com/store/apps/details?id=com.lonelycatgames.Xplore) - File manager supporting WebDAV mounts. `Proprietary`
* [MiXplorer](https://forum.xda-developers.com/showpost.php?p=23109280\&postcount=2) - File manager that supports WebDAV. `Proprietary`
* [FolderSync](https://play.google.com/store/apps/details?id=dk.tacit.android.foldersync.lite) - backup. `Proprietary`
* [Owlfiles](https://play.google.com/store/apps/details?id=com.skyjos.apps.fileexplorerfree) - File Manager. `Proprietary`
* [RS File Explorer](https://play.google.com/store/apps/details?id=com.rs.explorer.filemanager) - a file manager supporting WebDAV. `Proprietary`
* [WebDAV Navigator](https://play.google.com/store/apps/details?id=com.schimera.webdavnav) - WebDAV client for Android devices. `Proprietary`

<a name="android-players" />

#### Players

* [NOVA](https://github.com/nova-video-player/aos-AVP) ⭐ 4,633 | 🐛 937 | 🌐 HTML | 📅 2026-08-21 - an open source video player with AndroidTV support. `Apache-2.0`
* [danfr/webdav-player](https://github.com/danfr/webdav-player) ⚠️ Archived - access to remote WebDAV repository and play media files using VLC. `WIP`
* [CloudBeats](https://www.cloudbeatsapp.com/) - A music player. `Proprietary`
* [Capriccio ](https://play.google.com/store/apps/details?id=me.ideariboso.capriccio) - a music player. `Proprietary`
* [FX Player](https://play.google.com/store/apps/details?id=tv.fipe.fplayer) - music/video player. `Proprietary`
* [GOM Player](https://play.google.com/store/apps/details?id=com.gretech.gomplayerko) - music/video player. `Proprietary`
* VLC: [is planed](https://wiki.videolan.org/Bounties/#Webdav_support)
* [Neutron](https://play.google.com/store/apps/details?id=com.neutroncode.mpeval) - a music player. `Proprietary`

<a name="android-other-apps" />

#### Other apps

*Apps that support WebDAV in some form, e.g. for backup and sync*

* [Keepass2Android](https://play.google.com/store/apps/details?id=keepass2android.keepass2android) - KeePass-based password manager that supports WebDAV sync. [Sources](https://github.com/PhilippC/keepass2android) ⭐ 6,200 | 🐛 1,163 | 🌐 C# | 📅 2026-08-20. `GPL3`
* [BeeCount](https://github.com/TNT-Likely/BeeCount) ⭐ 2,174 | 🐛 111 | 🌐 Dart | 📅 2026-08-23 – Privacy-first expense tracker with multi-backend cloud sync including WebDAV. `Source-Available` `Dart`
* [Table Habit](https://github.com/FriesI23/mhabit) ⭐ 1,458 | 🐛 78 | 🌐 Dart | 📅 2026-08-24 – Micro habits tracking app with [sync via WebDAV](https://github.com/FriesI23/mhabit/wiki/Feature%EA%9E%89-WebDAV-Sync) ⭐ 1,458 | 🐛 78 | 🌐 Dart | 📅 2026-08-24. `AL2` `Dart`  `Apache-2.0`
* [SimpleTask](https://github.com/mpcjanssen/simpletask-android) ⚠️ Archived - a simple task manager. `GPL3` `Kotlin`
* [ntodotxt](https://github.com/tmaegel/ntodotxt) ⭐ 220 | 🐛 41 | 🌐 Dart | 📅 2026-08-14 - TODO App with sync via WebDAV. `MIT`
* [pokatomnik/Davno](https://github.com/pokatomnik/Davno) ⭐ 1 | 🐛 1 | 🌐 Kotlin | 📅 2023-03-30 - Web**DAV NO**tes, Android app, unfinished. `WIP`, `Kotlin`
* [Joplin](https://play.google.com/store/apps/details?id=net.cozic.joplin) - Note taking and to-do application that supports WebDAV sync.
* [Moon+ Reader](https://www.moondownload.com) - Reading app that supports syncing books, reading position, notes, & highlights via WebDAV. `Proprietary`
* [Orgzly](https://www.orgzly.com/) - Outliner for notes and to-do lists. [Source code](https://github.com/orgzly).

### iOS

<a name="ios-file-managers" />

#### File managers

*General purpose apps to browse and manage files on a WebDAV server*

* Apple Files app – Can connect to WebDAV servers. `Proprietary`
* [Documents: File Manager & Docs](https://apps.apple.com/app/documents-file-manager-docs/id364901807) - PDF Converter & Reader, ZIP/RAR, suppoers WebDAV.
* [WebDAV Nav+](https://apps.apple.com/app/webdav-nav/id412341302) - Download, share, store and edit files on a WebDAV server.
* [WebDAV Navigator](https://apps.apple.com/app/webdav-navigator/id382551345) - Download, share, store and edit files on a WebDAV server.
* [Owlfiles](https://apps.apple.com/app/owlfiles-file-manager/id510282524) - File Manager. `Proprietary`
* [FE File Explorer](https://apps.apple.com/app/id499470113) - a file manager from OwlFiles developers.  Supports music and video playback, text editing, local folder sync.  `Proprietary`

<a name="ios-other-apps" />

#### Other apps

*Apps that support WebDAV in some form, e.g. for backup and sync*

* [BeeCount](https://apps.apple.com/app/id6754611670) – Privacy-first expense tracker with multi-backend cloud sync including WebDAV. [Source](https://github.com/TNT-Likely/BeeCount) ⭐ 2,174 | 🐛 111 | 🌐 Dart | 📅 2026-08-23. `Source-Available` `Dart`
* [Table Habit](https://github.com/FriesI23/mhabit) ⭐ 1,458 | 🐛 78 | 🌐 Dart | 📅 2026-08-24 – Micro habits tracking app with [sync via WebDAV](https://github.com/FriesI23/mhabit/wiki/Feature%EA%9E%89-WebDAV-Sync) ⭐ 1,458 | 🐛 78 | 🌐 Dart | 📅 2026-08-24. `AL2` `Dart`  `Apache-2.0`
* [1Writer](https://apps.apple.com/app/1writer-markdown-text-editor/id680469088) - Markdown text editor that supports importing from WebDAV.
* [beorg](https://apps.apple.com/app/beorg-to-do-list-agenda/id1238649962) - TO-DO list and agenda app with WebDAV sync support.
* [GoodReader](https://apps.apple.com/app/goodreader-pdf-editor-viewer/id777310222) - PDF viewer and editor that supports WebDAV sync.
* [Joplin](https://apps.apple.com/app/joplin/id1315599797) - Note taking and to-do application that supports WebDAV sync.
* [Notability](https://apps.apple.com/app/notability/id360593530) - Note-taking app that supports WebDAV for backups.
* [Notebooks 10](https://apps.apple.com/app/notebooks-write-and-organize/id1490084838) - Writing app, a text and markdown editor with WebDAV support.
* [Strongbox](https://apps.apple.com/app/strongbox-password-safe/id897283731) - KeePass-based password manager that supports WebDAV sync.

## Libraries

*Libraries for accessing a WebDAV storage and/or building a WebDAV server*

### C

* [neon](https://github.com/notroj/neon) ⭐ 165 | 🐛 5 | 🌐 C | 📅 2026-08-09 - An HTTP/1.1 and WebDAV client library with a C API.

### C++

* [webdav-client-cpp](https://github.com/CloudPolis/webdav-client-cpp) ⭐ 132 | 🐛 5 | 🌐 CMake | 📅 2024-05-01 - C++ WebDAV Client.

### Objective-C / iOS

* <https://github.com/mattrajca/DAVKit> ⭐ 116 | 🐛 10 | 🌐 Objective-C | 📅 2012-05-20
* <https://github.com/zwaldowski/DZWebDAVClient> ⚠️ Archived

### .Net

* <https://github.com/saguiitay/WebDAVClient> ⭐ 133 | 🐛 11 | 🌐 C# | 📅 2026-08-24

### Go

* [go-webdav](https://github.com/emersion/go-webdav) ⭐ 495 | 🐛 54 | 🌐 Go | 📅 2026-06-28 - Client library for WebDAV, CalDAV and CardDAV.
* [gowebdav](https://github.com/studio-b12/gowebdav) ⭐ 370 | 🐛 9 | 🌐 Go | 📅 2026-07-09 - WebDAV client library and command line tool.
* [golang.org/x/net/webdav](https://godoc.org/golang.org/x/net/webdav) - WebDAV server implementation as part of the standard library.

### Java

* [sardine](https://github.com/lookfirst/sardine) ⭐ 623 | 🐛 23 | 🌐 Java | 📅 2026-03-09 - Java client based on Apache HTTP Client. `Apache-2.0`
* [sardine-android](https://github.com/thegrizzlylabs/sardine-android) ⭐ 395 | 🐛 19 | 🌐 Java | 📅 2024-02-14 - a WebDAV client for Android based on OkHttp. `Apache-2.0`
* [milton2](https://github.com/miltonio/milton2) ⭐ 211 | 🐛 15 | 🌐 Java | 📅 2026-08-12 - Milton Java WebDAV / CalDAV / CardDAV Server Library. `Apache-2.0`
* [owncloud/android-library](https://github.com/owncloud/android-library) ⚠️ Archived - an ownCloud library that internally use WebDAV over OkHttp. `MIT`
* [dav4jvm](https://github.com/bitfireAT/dav4jvm) ⭐ 103 | 🐛 3 | 🌐 Kotlin | 📅 2026-08-24 - dav4jvm is a WebDAV/CalDAV/CardDAV library for JVM (Java/Kotlin) developed for DAVx⁵. `MPL-2.0`
* [Jackrabbit WebDAV Library](https://jackrabbit.apache.org/jcr/components/jackrabbit-webdav-library.html) - WebDAV Library component of the Apache Jackrabbit project. `Apache-2.0`

### JavaScript and Dart

* [perry-mitchell/webdav-client](https://github.com/perry-mitchell/webdav-client) ⭐ 814 | 🐛 27 | 🌐 TypeScript | 📅 2026-05-03 - WebDAV client written in JavaScript for Node.js and the browser.
* [mikedeboer/jsDAV](https://github.com/mikedeboer/jsDAV) ⭐ 679 | 🐛 50 | 🌐 JavaScript | 📅 2017-07-24 - a Node.js port of SabreDAV with support of many features.
* [unifile](https://github.com/silexlabs/unifile) ⭐ 152 | 🐛 21 | 🌐 JavaScript | 📅 2022-03-17 - Node.js library to access cloud storage which supports WebDAV.
* [FriesI23/simple\_webdav\_client](https://github.com/FriesI23/simple_webdav_client) ⭐ 12 | 🐛 1 | 🌐 Dart | 📅 2025-03-05 - Dart library `Dart` `MIT`
* [nephele](https://www.npmjs.com/package/nephele) - WebDAV, CardDAV, and CalDAV server for Node.js and Express. `Apache-2.0`

### Python

* [YaDiskClient](https://github.com/TyVik/YaDiskClient) ⭐ 61 | 🐛 4 | 🌐 Python | 📅 2022-10-19 - a simple to use client for Yandex Disk. `MIT`
* [webdavclient3](https://pypi.org/project/webdavclient3/) - WebDAV client for Python 3.x.

## Cloud providers

*Cloud services that offer a WebDAV server or otherwise allow access via WebDAV*

* [1und1.de](https://www.1und1.de/) - a hosting and cloud (HiDrive). Based in Germany.
* [4shared](https://www.4shared.com/web/helpCenter/fGeDNHCrXce#par_eight) - Fully supports WebDAV and allows synchronization over it. Based in Ukraine.
* [~~Box~~](https://support.box.com/hc/en-us/articles/360043696414-WebDAV-with-Box) - Has a WebDAV URL that allows access via WebDAV (no longer supported).
* [CloudMe](https://www.cloudme.com/en/webdav) - cloud solution.  Based in Sweden.
* [EDIS](https://www.edis.at/) - a (web) server and infrastructure hoster. Based in Austria.
* [FastMail](https://www.fastmail.help/hc/en-us/articles/1500000277882-Remote-file-access) - an Email service with WebDAV access to files. Based in Australia.
* [GM Cloud](https://www.gmx.com/cloud/) -  a Web portal with cloud feature. Based in Germany.
* [IceDrive](https://icedrive.net/) - a cloud solution. Based in UK.
* [infomaniak](https://www.infomaniak.com/) - The Ethical Cloud and colaboration service. Based in Switzerland.
* [IONOS](https://www.ionos.com/) - a hosting and cloud (HiDrive). Based in US.
* [Jianguoyun / Nutstore](https://www.jianguoyun.com/) - a cloud and workspace. Based in China.
* [Kolab Now](https://kb.kolabnow.com/faq/can-i-access-my-files-via-webdav) - a collaboration service. Based in Switzerland.
* [Koofr](https://koofr.eu/) - a personal cloud services. Based in Slovenia.
* [luckycloud](https://docs.luckycloud.de/en/cloud-storage/webdav) - an advanced cloud. Based in Germany.
* [mail.com](https://www.mail.com/) - an Email service but also provides WebDAV access to stored files.
* [MyDrive](https://www.mydrive.ch/) - s cloud solution. Based in Switzerland.
* [OpenDrive](https://www.opendrive.com/) - a cloud and office suite. Based in US.
* [pCloud](https://www.pcloud.com/) - business level accounts can use WebDAV.
* [STRATO](https://www.strato.com/) - a hosting and cloud (HiDrive). Based in Germany, Netherlands, Spain, France, UK, Sweden.
* [T-Online.de / Magenta](https://cloud.telekom-dienste.de/) - a ISP and cloud. Based in Germany.
* [transip.nl](https://www.transip.nl/) - an ISP that offers cloud. Based in the Netherlands.
* [web.de](https://hilfe.web.de/cloud/netzlaufwerk/windows-10.html) - a Web portal with cloud feature. Based in Germany.
* [Woelkli](https://woelkli.com/) - a NextCloud-based service. Based in Switzerland.
* [Yandex.Disk](https://yandex.com/dev/disk/webdav/) - Has a WebDAV API that treats its storage like a file system. Based in Russia.
* [Zaclys](https://www.zaclys.com/) - a NextCloud-based service. Based in France.

Comparision of the providers:

* [Linux и бесплатные облачные хранилища, семь лет спустя](https://habr.com/ru/articles/651609/)

## Extensions

*Protocol extensions and related protocols*

* [CalDAV](https://en.wikipedia.org/wiki/CalDAV)
* [CardDAV](https://en.wikipedia.org/wiki/CardDAV)
* [Microsoft Extensions](https://docs.microsoft.com/en-us/openspecs/sharepoint_protocols/ms-wdvme/8cafdf55-ee5c-443e-bdb7-2cb2ab1fb2c3)

## Contributing

Contributions welcome! Read the [contribution guidelines](contributing.md) first.

***

> _Enhansomed by [enhansome](https://github.com/enhansome) on 2026-08-25._
