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
