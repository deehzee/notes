# Tmux

## Keyboard Shortcuts

* `^b` then `c` to create a new window
* `^b` then `n` to switch to the next window
* `^b` then `,` then [type something] then `⌤` to rename the current window
* `^b` then `%` to split the current window into panes vertically
* `^b` then `"` to split the current window into panes horizontally
* `^b` then `↑` to move to the above pane (works for all four arrows)
* `^b` then `o` to cycle between panes
* `^b` then `q` to show pane numbers, then (optionally) the number to switch to that pane
* `^b` then `⎇↑` to resize the current pane up (works for all four arrows)
* `^b` then `x` to kill the current pane (or window if it only has one pane)
* `^b` then `[` to enter copy mode, then four arrow keys to move, even past the visible point, which is great for scrolling--I don't use it much for copying/pasting.
* `^b` then `L` to switch between sessions
* `^b` then `0`-`9` to switch to the window 0-9
* `^b` then `d` to detach a session
* `^b` then `x` to kill a pane (or a window if it has a single pane)


## Commands

* `tmux new -s <session-name>`: Create a new session (aka `new-session`)
* `tmux switchc -t <session-name>`: Switch to the named session (aka `switch-client`)
* `tmux ls`: List all sessions (aka `list-sessions`)
* `tmux a -t <session_name>`: Attach or switch to a session (aka `attach`)
* `:resizep -U N`: resize pane upward by `N` cells (aka `resize-pane`, possible directions: `U`, `D`, `L`, `R`)


## Credits

__Source:__ https://coderwall.com/p/mxzdrg/keyboard-shortcuts-i-use-every-day-in-tmux
