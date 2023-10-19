# shortcut-to-run-Python-with-SublimeREPL

{ </br>
  "keys": ["ctrl+alt+b"], "command": "run_existing_window_command", "args": </br>
{ </br>
  "id": "repl_python_run", </br>
  "file": "config/Python/Main.sublime-menu" </br>
}} </br>

_In Sublime, go to: Preferences --> Key Bindings - user. </br>
Copy the shortcut to the sublime-keymap and save it. </br>
Shortcut keys: "ctrl+alt+b" </br>_

# uBlock Origin yt filter rules (effective as of 19.10.23)
youtube.com##+js(set, yt.config_.openPopupConfig.supportedPopups.adBlockMessageViewModel, false) </br>
youtube.com##+js(set, Object.prototype.adBlocksFound, 0) </br>
youtube.com##+js(set, ytplayer.config.args.raw_player_response.adPlacements, []) </br>
youtube.com##+js(set, Object.prototype.hasAllowedInstreamAd, true) </br>

# Clean-up Microsoft Edge
127.0.0.1       localhost </br>
::1             localhost </br>
127.0.0.1  data.microsoft.com </br>
127.0.0.1  msftconnecttest.com </br>
127.0.0.1  azureedge.net </br>
127.0.0.1  activity.windows.com </br>
127.0.0.1  bingapis.com </br>
127.0.0.1  msedge.net </br>
127.0.0.1  assets.msn.com </br>
127.0.0.1  scorecardresearch.com </br>
127.0.0.1  edge.microsoft.com </br>
127.0.0.1  data.msn.com </br>
