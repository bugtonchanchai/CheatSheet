# tmux

## ref
https://linuxize.com/post/getting-started-with-tmux/

## command list

| Command | Description |
| ----------- | ----------- |
| tmux | new session |
| tmux new -s session_name | new session |
| tmux a -t session_name | attach to session session_name |

## short key

| Key | Description |
| ----------- | ----------- |
| Ctrl+b ? | Help |
| Ctrl+b d | Detaching from Tmux Session |
| Ctrl+b c | Create a new window (with shell) |
| Ctrl+b w | Choose window from a list |
| Ctrl+b 0 | Switch to window 0 (by number) |
| Ctrl+b , | Rename the current window |
| Ctrl+b % | Split current pane horizontally into two panes |
| Ctrl+b " | Split current pane vertically into two panes |
| Ctrl+b o | Go to the next pane |
| Ctrl+b ; | Toggle between the current and previous pane |
| Ctrl+b x | Close the current pane |
