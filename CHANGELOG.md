# Mackup Changelog

## WIP

## Mackup 0.7

- Added support for Google Drive to store your files
- Added support for any directory to store your files
- Ability to customize the Mackup directory name
- Improved the test coverage

## Mackup 0.6.1

- Added support for Livestreamer (thx @vitorgalvao)
- Added support for Brackets (thx @vitorgalvao)
- Added a list mode to list supported apps
- Improved the help message
- Prevent Mackup to be run as a superuser
- Code cleanup

## Mackup 0.6

- Added support for custom applications
- Fixed pip support (thx @lachlancooper)
- Added XChat support (thx @scottydelta)
- Removing Ember support, it does not like file links
- Homebrew fixes
- Doc updates

## Mackup 0.5.9

- Added support for rTorrent (thx @mgalkiewicz)
- Added support for Dolphin (thx @lachlancooper)
- Improved Janus support for Vim
- Do not sync Dash Docsets anymore
- Added support for Lightroom 5 (thx @Darep)
- Added support for Adobe Camera Raw (thx @Darep)
- Refactored the code to prepare future modularization

## Mackup 0.5.8

- Extend Little Snitch with latest user config file (thx @stechico)
- Added support to Hands Off! (thx @stechico)
- Fixed GnuPG support

## Mackup 0.5.7

- Only sync the config for Bundler
- Don't sync Apple Messages attachments
- Added support for Default Folder X (thx @Cottser)
- Added support for Path Finder (thx @Cottser)

## Mackup 0.5.6

- Added support for LittleSnitch (thx @stechio)
- Added support for OmniGraffle (thx @stecico)
- Added support for SABnzbd (thx @stechico)
- Added support for Skitch (thx @stechico)
- Added support for FontExplorer X (thx @stechico)
- Improved Transmission support (thx @stechico)
- Added support for Lightroom 2, 3 and 4 (thx @stechico)
- Fix Bundler’s synced dir (thx @atipugin)

## Mackup 0.5.5

- Added support for Enjoyable (thx @vitorgalvao)
- Added support for Deal Alert (thx @vitorgalvao)
- Added support for MagicPrefs (thx @vitorgalvao)
- Added support for LaunchBar (thx @Cottser)
- Added support for XLD (thx @vitorgalvao)
- Added support for Gmail Notifr (thx @lachlancooper)
- Added support for Awareness (thx @lachlancooper)
- Added support for Chicken (thx @lachlancooper)
- Added support for Hexels (thx @lachlancooper)
- Added support for Clementine (thx @lachlancooper)
- Add support for mpd and ncmpcpp (thx @zmrow)
- Improved Sublime 3 support (thx @laupiFrpar)
- Added FileZilla support (thx @kidh0)
- Added support for Light Table (thx @vitorgalvao)

## Mackup 0.5.4

- Added support for Arara and Aspell (thx @twsh)
- Removed support of OS X Services, as it does not support links
- Added support for i2cssh and iTunes Applescripts (thx @jannae)
- Make slogan consistent throughout (thx @Cottser)
- Added tests to cover file copying and linking (thx @Cottser)
- Better Apple Messages support (thx @vitorgalvao)
- Added support for Keka (thx @vitorgalvao)
- Added support for Feeds (thx @vitorgalvao)
- Added support for Textual (thx @vitorgalvao)

## Mackup 0.5.3

- Added support for Divvy (thx @saulshanabrook)
- Added support for Apple Messages (thx @pzbyszynski)
- Added support for Skype (thx @pzbyszynski)
- Added support for SuperDuper! (thx @pzbyszynski)
- Added support for ForkLift 2 (thx @pzbyszynski)
- Added support for Ember (thx @pzbyszynski)
- Added support for Dash and Cyberduck (thx @suprememoocow)
- Added support for Mou (thx @jannae)
- Added support for PokerStars (thx @vitorgalvao)

## Mackup 0.5.2

- Added support for Tower (thx @MichaelRBond)
- Added support for Colloquy (thx @MichaelRBond)
- Added support for Twitterrific (thx @MichaelRBond)
- Mackup path in dropbox is now configurable via constant (thx @MichaelRBond)
- Added support for Spectacle (thx @vincecima)

## Mackup 0.5.1

- Added support for exercism (thx @mwarkentin)
- Added support for Skim
- Added support for Scenario
- Added support for Ack (thx @adamlogic)
- Added support for Stata and SelfControl (thx @kfinlay)
- Added support for LaTeXiT (thx @twsh)
- Do not link ~/Library/* files on GNU/Linux, should fix #104

## Mackup 0.5

- Added GNU/Linux support (thx @flexiondotorg)
- Added the ability to explicitly list the list of applications to sync (thx
  @zuhao)
- Added support for Shuttle, the heroku-accounts plugin for Heroku, bundler, pry
  and awesome-print for Ruby (thx @yabawock)
- Added support for Bash it (thx @Tam-Lin)

## Mackup 0.4.4

- Conflict folder sync fix (thx @ediventurin)
- Added support for PIP (thx @dhellmann)
- Added support for FTP's .netrc, Chef, Pear (thx @yabawock)
- Added support for Irssi (thx @louisrli)
- Added support for Htop and Janus (thx @walkertraylor)
- Added support for Transmit (thx @dustinmm80)
- Improved Vim support (thx @yabawock)

## Mackup 0.4.3

- Added support for nvALT (thx @stenehall)
- Added support for Adobe Lightroom, OS X Scripts Services and Quicklook (thx
  @Tam-Lin)
- Added support for Bartender, Caffeine, CloudApp, Droplr, Fantastical, Moom,
  OmniFocus, Pastebot, PopClip, Slogger (thx @ediventurin)
- Added support for ClipMenu, MenuMeters, PhpStorm 6, RubyMine 5, Spotify
  (thx @hakubo)
- Added support for Concentrate (thx @raylillywhite)
- Added support for BibDesk (thx @twsh)

## Mackup 0.4.2

- Made a method to check if a process is running (not yet)
- Added support for XCode (thx @adeca)
- Added support for CoRD, Spark, f.lux, BetterTouchTool, BetterSnapTool and
  Coda 2 (thx @TimCorcoran)
- Added support for Mailplane and Gitbox (thx @THEY)

## Mackup 0.4.1

- Hotfix: Checking that a process is runnin is not working everywhere

## Mackup 0.4

- Fixed support for locked files e.g. SourceTree (thx @dbingham)
- Added support for Nano (thx @stechico)
- Added support for SHSH Blobs (thx @stechico)
- Added support for Teamocil and Tmuxinator (thx @djquan)
- Added support for Viscosity and Transmission (thx @ovrtn)
- Fixed support for Sublime Text (thx @nZac)
- Added a config file to not sync some user defined applications (thx @nZac)

## Mackup 0.3.2

- Added support for iTerm2 (thx @joshbrown)
- Added support for SourceTree (thx @stechico)
- Added support for OS X's ColorSync profiles (thx @stechico)
- Added support of AppCode 2 (thx @MarcoSero)
- Added support of IntelliJIdea 12 (thx @MarcoSero)
- Added support of RubyMine 4 (thx @MarcoSero)
- Fixed a typo (thx @dhellmann)
- Added support for Screen (thx @dhellmann)
- Added support for PyPI (thx @dhellmann)
- Added support for ExpanDrive (thx @dhellmann)
- Added support for Git Hooks (thx @dhellmann)

## Mackup 0.3.1

- Added support for Slate (thx @stechico)
- Added support for Adium (thx @stechico)
- Improved support for Mercurial (thx @stechico)
- Added support for Sublime Text 3 (thx @laupiFrpar)
- Added support for MPV (thx @Nyx0uf)
- Added support for Ventrilo (thx @stechico)
- Added support for TextMate (thx @hkaju)
- Added support for Tmux, SizeUp, Quicksilver, Witch, ControlPlane, GeekTool,
  Keymo, KeyRemap4MacBook, MercuryMover, PCKeyboardHack (thx @orenshk)
- Made the help screen more readable (too many supported apps)

## Mackup 0.3

- Added an uninstall mode to revert a system to its pre-Mackup state
- Added support for Byobu (thx @drye)
- Added support for Fish (thx @saulshanabrook)
- Improved the Vim support

## Mackup 0.2

- Added support for Emacs and XEmacs
- Added support for Zsh
- Added support for LimeChat
- Added support for Subversion (thx @adamme)
- Added support for Oh My Zsh (thx @adamme)
- Added support for Ruby and Rails (thx @atipugin)
- Added support for Pow (thx @atipugin)
- Added support for Ruby Version (thx @adamstac)
- Added support for Pentadactyl (thx @alanning)
- Added support for Vimperator (thx @alanning)
- Improved Git support (thx @atipugin)
- Improved Bash support (thx @adamme)
- Doc updates

## Mackup 0.1

- Initial release
