# VSCode Python

This extension contains code snippets for Python for Visual Studio Code.

**Note**: This snippets.json was generated automaticaly base on https://github.com/honza/vim-snippets

## Installation

To install this extension type _Extensions_ in Command Pallete, then find a `vscode-python-snippets` extension.

## Suported file types

- Python (.py)

## Snippets (WIP)

| Abbreviation | Description                                    |
| ------------ | ---------------------------------------------- |
| env, #!      | #!/usr/bin/env python                          |
| env2, #!2    | #!/usr/bin/env python2                         |
| env3, #!3    | #!/usr/bin/env python3                         |
| enc          | # -_- coding=utf-8 -_-                         |
| enco         | # coding=utf-8                                 |
| im, imp      | import                                         |
| fim, from    | from ... import ...                            |
| fdt          | from dataclasses import dataclass              |
| cl, cls      | New class                                      |
| cla          | New class with description                     |
| clai         | New class with description and init            |
| claip        | New class with description, init and post_init |
| dtcl, dtcls  | New dataclass                                  |
| dtcla        | New dataclass with description                 |
| dtclap       | New dataclass with description and post_init   |
| df, def      | New function                                   |
| dff, deff    | New method                                     |
| sdf, sdef    | New static method                              |

## Todo

Extend a functionality base on other popular sets of snsippets

1. https://github.com/cstrap/python-snippets

### Base

| Abbreviation | Description               |
| ------------ | ------------------------- |
| property     | New property              |
| if           | if                        |
| for          | for                       |
| while        | while                     |
| try          | try:except:               |
| tryef        | try:except:else:finally:  |
| trye         | try:except:else:          |
| tryf         | try:except:finally:       |
| .            | self                      |
| \_\_         | **magic**                 |
| ifmain       | if **name** == "**main**" |

### Comprehensions

| Abbreviation | Description                        |
| ------------ | ---------------------------------- |
| lc           | List comprehension                 |
| lcie         | List comprehension if else         |
| lci          | List comprehension if filter       |
| dc           | Dictionary comprehension           |
| dci          | Dictionary comprehension if filter |
| sc           | Set comprehension                  |
| sci          | Set Comprehension if filter        |
| gc           | Generator comprehension            |
| gci          | Generator comprehension if filter  |

### Unittest

| Abbreviation | Description        |
| ------------ | ------------------ |
| ase          | Assert equal       |
| asne         | Assert not equal   |
| asr          | Assert raises      |
| ast          | Assert True        |
| asf          | Assert False       |
| asi          | Assert is          |
| asint        | Assert is not      |
| asino        | Assert is None     |
| asinno       | Assert is not None |
| asin         | Assert in          |
| asni         | Assert not in      |
| as           | Assert             |
| fail         | Fail (a test)      |

### Debugging

| Abbreviation | Description    |
| ------------ | -------------- |
| pdb          | PDB set trace  |
| ipdb         | iPDB set trace |
| rpdb         | rPDB set trace |
| pudb         | PuDB set trace |

### Tkinter

| Abbreviation | Description        |
| ------------ | ------------------ |
| imtk         | Import Tkinter py2 |
| imtk3        | Import tkinter py3 |
| config       | Root configuration |
| button       | Button             |
| label        | Label              |
| frame        | Frame              |
| entry        | Entry              |
| grid         | Grid               |
| sticky       | Sticky             |
| checkbutton  | Check button       |
| mainloop     | Main loop          |
| pack         | Pack               |
| side         | Side               |
| bind         | Bind               |
| menu         | Menu               |
| addcascade   | Add cascade        |
| addcommand   | Add command        |
| addseperator | Add seperator      |
