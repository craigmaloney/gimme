# gimme

Written by Craig Maloney`

Plugin for [todo.sh](http://todotxt.org/) for picking a random item from either the default file or a separate file having the specified criteria.

## Usage

`todo.sh gimme @computer`

Selects an item from your default todo.txt file having `@computer`.

`todo.sh gimmef someday.txt`

Selects an item from your someday.txt file.

`todo.sh gimmef someday.txt pepper`

Selects an item from your someday.txt file having `pepper`.

## Installation

Copy `gimme` and `gimmef` into your `.todo.actions.d` folder. Refer to [Creating and Installing Add-ons](https://github.com/todotxt/todo.txt-cli/wiki/Creating-and-Installing-Add-ons) for more details.

## Additional things

You may wish to add `gimmef` to your todo.sh tab completion. To do this under `bash` you'll need to add the following to your `.bashrc` file:

`_todo_file1_actions="gimmef"`

(Note that in order to add additional commands you'll need to separate them with the `|` character. On the author's machine this variable looks like the following, which adds the `rmf`, `edit`, `e`, and `gimmef` commands)

`_todo_file1_actions="rmf|gimmef|edit|e"`

## License

This code is licensed under the GPL v3.0 license. See LICENSE for further details.
