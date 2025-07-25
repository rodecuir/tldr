# nano

> Command-line text editor. An enhanced `Pico` clone.
> See also: `pico`, `rnano`.
> More information: <https://nano-editor.org>.

- Start the editor:

`nano`

- Start the editor without using configuration files:

`nano {{[-I|--ignorercfiles]}}`

- Open specific files, moving to the next file when closing the previous one:

`nano {{path/to/file1 path/to/file2 ...}}`

- Open a file and position the cursor at a specific line and column:

`nano +{{line}},{{column}} {{path/to/file}}`

- Open a file and enable soft wrapping:

`nano {{[-S|--softwrap]}} {{path/to/file}}`

- Open a file and indent new lines to the previous line's indentation:

`nano {{[-i|--autoindent]}} {{path/to/file}}`

- Open a file and create a backup file (`path/to/file~`) on save:

`nano {{[-B|--backup]}} {{path/to/file}}`

- Exit nano:

`<Ctrl x>`
