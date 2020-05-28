# join
To join multiline `StdIn` to a single Line `StdOut` - optionally divided by a given Separator

Best to be used with [paste](https://github.com/jalbersdorfer/paste.asm) and [Launchy](https://github.com/OpenNingia/Launchy).

## Usage
```bash
$ paste | join <divider>

  <divider> - Optional Separator to be placed between the previous Lines.
```

## Examples

To Convert Clipboard Content

```
Foo\r\n
Bar
```

to

```
Foo, Bar
```

use *(mention the Whitespace behind the comma - you can have a multi character divider)*

```bash
$ paste | join , 
```
