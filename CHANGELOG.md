# Threema Web Changelog

This changelog lists the most important changes for each released version. For
the full log, please refer to the git commit history.

### [v1.4.0][v1.4.0] (2017-07-20)

Changes:

* [feature] Show battery status indicator ([#265][i265])
* [change] Reduce browser CPU usage in conversation ([#264][i264])
* [bug] Add high DPI versions of emoji spritemaps ([#261][i261])

### [v1.3.1][v1.3.1] (2017-06-22)

Changes:

* [bug] Fix bug when inserting emoji in Chrome ([#256][i256])

### [v1.3.0][v1.3.0] (2017-06-22)

Changes:

* [feature] Upgrade to Emojione 3 ([#54][i54] / [#201][i201])
* [feature] Support emoji in conversation and contact names ([#44][i44])
* [feature] Fallback text in user profile if first/last name are not provided ([#238][i238])
* [bug] Make it impossible to open own contact ([#231][i231] / [#235][i235])
* [bug] When pasting text, only trim newline characters ([#237][i237])
* [bug] Fix right-to-left support ([#239][i239])

### [v1.2.1][v1.2.1] (2017-05-17)

Changes:

* [feature] Check for a new version, notify user if version changed ([#183][i183])
* [bug] Fix line breaks when pasting on Windows ([#134][i134])
* [bug] Fix path to sound notification file

### [v1.2.0][v1.2.0] (2017-05-17)

Changes:

* [feature] Support markup and emoji in media box caption ([#177][i177])
* [feature] Optional notification sound for incoming messages ([#178][i178])
* [feature] Consider page visibility when marking messages as read ([#17][i17] / [#108][i108] / [#211][i211])
* [feature] Support all threema url actions ([#190][i190] / [#215][i215])
* [change] Location message redesign ([#185][i185])
* [change] Enhanced desktop notification preview ([#193][i193])
* [bug] Enforce text cursor on compose box ([#204][i204])
* [bug] Fix resizing behavior of back arrow button ([#205][i205])
* [bug] Fix displaying of drafts in active conversation ([#189][i189])
* [bug] Fix MIME type handling ([#90][i90] / [#59][i59] / [#202][i202])

Contributors:

- [@IndianaDschones][@IndianaDschones]
- [@Pythonix][@Pythonix]
- [@econic][@econic]

### [v1.1.0][v1.1.0] (2017-03-16)

Changes:

* [feature] Make notification settings configurable ([#8][i8])
* [feature] Image preview ([#11][i11])
* [feature] Show group members in header ([#6][i6])
* [feature] Check for desktop notifications in troubleshooting tool ([#150][i150])
* [change] Immediately hide desktop notifications for read conversations ([#131][i131])
* [change] Make scrollbars in Chrome a bit wider ([#144][i144])
* [change] Increment minimal required FF version to 50 ([#161][i161])
* [bug] Fix / improve soft reconnect behavior ([#167][i167])
* [bug] Fix flickering of avatars on refresh ([#143][i143])
* [bug] Fix submitting of files with enter key ([#122][i122])
* [bug] Reset unread count after logout ([#148][i148])
* [bug] Fix TypeError when closing a dialog ([#153][i153])
* [bug] Stop supporting multi-line markup ([#156][i156])

Contributors:

- [@IndianaDschones][@IndianaDschones]
- [@FloThinksPi][@FloThinksPi]

### [v1.0.5][v1.0.5] (2017-03-03)

Changes:

* [feature] Add diagnostics/troubleshooting page ([#126][i126] / [#127][i127])
* [bug] Fix bug resulting in slow initial load ([#120][i120])
* [bug] Add meta description to index.html ([#124][i124])

### [v1.0.4][v1.0.4] (2017-03-01)

Changes:

* [feature] Enable support for TURN via TLS (except for FF <53) ([#43][i43] / [#109][i109])
* [feature] Add noscript warning ([#119][i119])
* [bug] Fix compatibility bug for older browsers ([#64][i64])
* [bug] Escape all pasted text in compose area ([#86][i86])
* [bug] Update unread count in title on initial loading ([#93][i93])
* [bug] Fix state transitions when restoring a session ([#102][i102])
* [bug] Improve performance / reduce CPU load ([#117][i117] / [#20][i20] / [#39][i39])

Contributors:

- [@N3dal][@N3dal]
- [@ovalseven8][@ovalseven8]
- [@rugk][@rugk]

### [v1.0.3][v1.0.3] (2017-02-23)

Changes:

* [feature] Autofocus on compose area when opening a conversation ([#41][i41])
* [feature] Create unique file names for downloaded files / images ([#61][i61])
* [feature] Add support for pasting data into compose area ([#82][i82])
* [feature] Split up messages that are too long into multiple messages ([#48][i48] / [#79][i79])
* [bug] Fix for some "stuck at 60%" problems (add support for TURN via TCP) ([#43][i43] / [#83][i83])
* [bug] Fix for some "stuck at 99%" problems ([#38][i38])
* [bug] Fix display of untranslated strings in dialogs ([#57][i57])
* [bug] Fix display of very long file names ([#69][i69])

Contributors:

- [@thommy101][@thommy101]
- [@lgrahl][@lgrahl]


### [v1.0.2][v1.0.2] (2017-02-21)

Changes:

* [feature] Add loading indicator when sending files ([#29][i29])
* [feature] Add warning about browser plugins if PeerConnection setup fails ([#46][i46])
* [feature] Add referrer policy tag to HTML ([#49][i49])
* [feature] Add reload button to error page ([#66][i66])
* [feature] Add warning message if browser blocks local storage ([#67][i67])
* [bug] Fix pasting of HTML code that could lead to a potential XSS
  vulnerability (thanks [Frederik Braun](https://github.com/freddyb) for reporting)
* [bug] Fix some translations

Contributors:

- [@rugk][@rugk]
- [@Mic92][@Mic92]
- [@freddyb][@freddyb]


### v1.0.1 (2017-02-15)

First public release.

[i6]: https://github.com/threema-ch/threema-web/issues/6
[i8]: https://github.com/threema-ch/threema-web/issues/8
[i11]: https://github.com/threema-ch/threema-web/issues/11
[i17]: https://github.com/threema-ch/threema-web/issues/17
[i20]: https://github.com/threema-ch/threema-web/issues/20
[i29]: https://github.com/threema-ch/threema-web/issues/29
[i38]: https://github.com/threema-ch/threema-web/issues/38
[i39]: https://github.com/threema-ch/threema-web/issues/39
[i41]: https://github.com/threema-ch/threema-web/issues/41
[i43]: https://github.com/threema-ch/threema-web/issues/43
[i44]: https://github.com/threema-ch/threema-web/issues/44
[i46]: https://github.com/threema-ch/threema-web/issues/46
[i48]: https://github.com/threema-ch/threema-web/issues/48
[i49]: https://github.com/threema-ch/threema-web/issues/49
[i54]: https://github.com/threema-ch/threema-web/issues/54
[i57]: https://github.com/threema-ch/threema-web/issues/57
[i59]: https://github.com/threema-ch/threema-web/issues/59
[i61]: https://github.com/threema-ch/threema-web/issues/61
[i64]: https://github.com/threema-ch/threema-web/issues/64
[i66]: https://github.com/threema-ch/threema-web/issues/66
[i67]: https://github.com/threema-ch/threema-web/issues/67
[i69]: https://github.com/threema-ch/threema-web/issues/69
[i79]: https://github.com/threema-ch/threema-web/issues/79
[i82]: https://github.com/threema-ch/threema-web/issues/82
[i83]: https://github.com/threema-ch/threema-web/issues/83
[i86]: https://github.com/threema-ch/threema-web/issues/86
[i90]: https://github.com/threema-ch/threema-web/issues/90
[i93]: https://github.com/threema-ch/threema-web/issues/93
[i102]: https://github.com/threema-ch/threema-web/issues/102
[i108]: https://github.com/threema-ch/threema-web/issues/108
[i109]: https://github.com/threema-ch/threema-web/issues/109
[i117]: https://github.com/threema-ch/threema-web/issues/117
[i119]: https://github.com/threema-ch/threema-web/issues/119
[i120]: https://github.com/threema-ch/threema-web/issues/120
[i122]: https://github.com/threema-ch/threema-web/issues/122
[i124]: https://github.com/threema-ch/threema-web/issues/124
[i126]: https://github.com/threema-ch/threema-web/issues/126
[i127]: https://github.com/threema-ch/threema-web/issues/127
[i131]: https://github.com/threema-ch/threema-web/issues/131
[i134]: https://github.com/threema-ch/threema-web/issues/134
[i143]: https://github.com/threema-ch/threema-web/issues/143
[i144]: https://github.com/threema-ch/threema-web/issues/144
[i148]: https://github.com/threema-ch/threema-web/issues/148
[i150]: https://github.com/threema-ch/threema-web/issues/150
[i153]: https://github.com/threema-ch/threema-web/issues/153
[i156]: https://github.com/threema-ch/threema-web/issues/156
[i161]: https://github.com/threema-ch/threema-web/issues/161
[i167]: https://github.com/threema-ch/threema-web/issues/167
[i177]: https://github.com/threema-ch/threema-web/issues/177
[i178]: https://github.com/threema-ch/threema-web/issues/178
[i183]: https://github.com/threema-ch/threema-web/issues/183
[i185]: https://github.com/threema-ch/threema-web/issues/185
[i189]: https://github.com/threema-ch/threema-web/issues/189
[i190]: https://github.com/threema-ch/threema-web/issues/190
[i193]: https://github.com/threema-ch/threema-web/issues/193
[i201]: https://github.com/threema-ch/threema-web/issues/201
[i202]: https://github.com/threema-ch/threema-web/issues/202
[i204]: https://github.com/threema-ch/threema-web/issues/204
[i205]: https://github.com/threema-ch/threema-web/issues/205
[i211]: https://github.com/threema-ch/threema-web/issues/211
[i215]: https://github.com/threema-ch/threema-web/issues/215
[i231]: https://github.com/threema-ch/threema-web/issues/231
[i235]: https://github.com/threema-ch/threema-web/issues/235
[i237]: https://github.com/threema-ch/threema-web/issues/237
[i238]: https://github.com/threema-ch/threema-web/issues/238
[i239]: https://github.com/threema-ch/threema-web/issues/239
[i256]: https://github.com/threema-ch/threema-web/issues/256
[i261]: https://github.com/threema-ch/threema-web/issues/261
[i264]: https://github.com/threema-ch/threema-web/issues/264
[i265]: https://github.com/threema-ch/threema-web/issues/265

[v1.4.0]: https://github.com/threema-ch/threema-web/compare/v1.3.1...v1.4.0
[v1.3.1]: https://github.com/threema-ch/threema-web/compare/v1.3.0...v1.3.1
[v1.3.0]: https://github.com/threema-ch/threema-web/compare/v1.2.1...v1.3.0
[v1.2.1]: https://github.com/threema-ch/threema-web/compare/v1.2.0...v1.2.1
[v1.2.0]: https://github.com/threema-ch/threema-web/compare/v1.1.0...v1.2.0
[v1.1.0]: https://github.com/threema-ch/threema-web/compare/v1.0.5...v1.1.0
[v1.0.5]: https://github.com/threema-ch/threema-web/compare/v1.0.4...v1.0.5
[v1.0.4]: https://github.com/threema-ch/threema-web/compare/v1.0.3...v1.0.4
[v1.0.3]: https://github.com/threema-ch/threema-web/compare/v1.0.2...v1.0.3
[v1.0.2]: https://github.com/threema-ch/threema-web/compare/v1.0.1...v1.0.2

[@rugk]: https://github.com/rugk/
[@Mic92]: https://github.com/Mic92/
[@freddyb]: https://github.com/freddyb/
[@thommy101]: https://github.com/thommy101/
[@lgrahl]: https://github.com/lgrahl/
[@N3dal]: https://github.com/N3dal/
[@ovalseven8]: https://github.com/ovalseven8/
[@IndianaDschones]: https://github.com/IndianaDschones/
[@FloThinksPi]: https://github.com/FloThinksPi/
[@Pythonix]: https://github.com/Pythonix/
[@econic]: https://github.com/econic/
