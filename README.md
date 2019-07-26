# dconf-terminal-profiles

**To backup:**

From a terminal, run:
`dconf dump /org/mate/terminal/profiles/ > backup_mate-terminal_profiles`

save the backup_mate-terminal_profiles file somewhere for later

To reset to defaults:
`dconf reset -f /org/mate/terminal/profiles/`

To restore all your settings:
`dconf load /org/mate/terminal/profiles/ < backup_mate-terminal_profiles`

Modify profile list
`dconf write /org/mate/terminal/global/profile-list "['default', 'dracula', 'solarized-dark', 'solarized-light']"`
