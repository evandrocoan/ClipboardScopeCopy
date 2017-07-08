# Sublime Text Shell Script

Copy the current Sublime Text scope under the mouse cursor to the clipboard.

1. It has the default keybinding to the keystroke `F6`.
1. Creates the command `Clipboard Scope Copy: Get Current Scope` on the command palette.

You can use `view.window().run_command( "get_scope_always_text" )` on the Sublime Text Console, to
get the current scope name. But the package `ScopeAlways` and its command should be activated by
`Toggle ScopeAlways` in order to this to work. For this, it also:

1. Creates the command `Clipboard Scope Copy: Get Scope Always Text` on the command palette.



___
## License

All files in this repository are released under GNU General Public License v3.0
or the latest version available on http://www.gnu.org/licenses/gpl.html

1. The [LICENSE](LICENSE) file for the GPL v3.0 license
1. The website https://www.gnu.org/licenses/gpl-3.0.en.html

For more information.


