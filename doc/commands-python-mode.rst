Python-mode commands

====================

py-smart-operator-check
-----------------------
Check, if smart-operator-mode is loaded resp. available.

Give some hints, if not.

py-autopair-check
-----------------
Check, if autopair-mode is available.

Give some hints, if not.

toggle-py-nil-docstring-style
-----------------------------
If nil docstring-style should be on or off.

  Returns value of `py-docstring-style' switched to. 
To set permanently,  customize this variable 

py-nil-docstring-style-on
-------------------------
Make sure, nil docstring-style' is on.

  Returns value of `py-docstring-style'. 
To set permanently,  customize this variable 

py-nil-docstring-style-off
--------------------------
Make sure, nil docstring-style is off.

  Returns value of `py-docstring-style'. 
To set permanently,  customize this variable 

toggle-py-onetwo-docstring-style
--------------------------------
If onetwo docstring-style should be on or off.

  Returns value of `py-docstring-style' switched to. 
To set permanently,  customize this variable 

py-onetwo-docstring-style-on
----------------------------
Make sure, onetwo docstring-style' is on.

  Returns value of `py-docstring-style'. 
To set permanently,  customize this variable 

py-onetwo-docstring-style-off
-----------------------------
Make sure, onetwo docstring-style is off.

  Returns value of `py-docstring-style'. 
To set permanently,  customize this variable 

toggle-py-pep-257-docstring-style
---------------------------------
If pep-257 docstring-style should be on or off.

  Returns value of `py-pep-257-docstring-style' switched to. 

py-pep-257-docstring-style-on
-----------------------------
Make sure, pep-257 docstring-style' is on.

Returns value of `py-pep-257-docstring-style'. 

py-pep-257-docstring-style-off
------------------------------
Make sure, pep-257 docstring-style is off.

Returns value of `py-pep-257-docstring-style'. 

toggle-py-pep-257-nn-docstring-style
------------------------------------
If pep-257-nn docstring-style should be on or off.

  Returns value of `py-pep-257-nn-docstring-style' switched to. 

py-pep-257-nn-docstring-style-on
--------------------------------
Make sure, pep-257-nn docstring-style' is on.

  Returns value of `py-docstring-style'. 
To set permanently,  customize this variable 

py-pep-257-nn-docstring-style-off
---------------------------------
Make sure, pep-257-nn docstring-style is off.

  Returns value of `py-docstring-style'. 
To set permanently,  customize this variable 

toggle-py-symmetric-docstring-style
-----------------------------------
If symmetric docstring-style should be on or off.

  Returns value of `py-docstring-style' switched to. 
To set permanently,  customize this variable 

py-symmetric-docstring-style-on
-------------------------------
Make sure, symmetric docstring-style' is on.

  Returns value of `py-docstring-style'. 
To set permanently,  customize this variable 

py-symmetric-docstring-style-off
--------------------------------
Make sure, symmetric docstring-style is off.

  Returns value of `py-docstring-style'. 
To set permanently,  customize this variable 

toggle-py-django-docstring-style
--------------------------------
If django docstring-style should be on or off.

  Returns value of `py-docstring-style' switched to. 
To set permanently,  customize this variable 

py-django-docstring-style-on
----------------------------
Make sure, django docstring-style' is on.

  Returns value of `py-docstring-style'. 
To set permanently,  customize this variable 

py-django-docstring-style-off
-----------------------------
Make sure, django docstring-style is off.

  Returns value of `py-docstring-style'. 
To set permanently,  customize this variable 

toggle-py-underscore-word-syntax-p
----------------------------------
If `py-underscore-word-syntax-p' should be on or off.

  Returns value of `py-underscore-word-syntax-p' switched to. 

py-underscore-word-syntax-p-on
------------------------------
Make sure, py-underscore-word-syntax-p' is on.

Returns value of `py-underscore-word-syntax-p'. 

py-underscore-word-syntax-p-off
-------------------------------
Make sure, `py-underscore-word-syntax-p' is off.

Returns value of `py-underscore-word-syntax-p'. 

toggle-py-electric-comment-p
----------------------------
If `py-electric-comment-p' should be on or off.

  Returns value of `py-electric-comment-p' switched to. 

py-electric-comment-p-on
------------------------
Make sure, py-electric-comment-p' is on.

Returns value of `py-electric-comment-p'. 

py-electric-comment-p-off
-------------------------
Make sure, `py-electric-comment-p' is off.

Returns value of `py-electric-comment-p'. 

toggle-force-local-shell
------------------------
If locally indicated Python shell should be taken and
enforced upon sessions execute commands.

Toggles boolean `py-force-local-shell-p' along with `py-force-py-shell-name-p'
Returns value of `toggle-force-local-shell' switched to.

When on, kind of an option 'follow', local shell sets `py-shell-name', enforces its use afterwards.

See also commands
`py-force-local-shell-on'
`py-force-local-shell-off'
 

py-force-local-shell-on
-----------------------
Make sure, `py-py-force-local-shell-p' is on.

Returns value of `py-force-local-shell-p'.

Kind of an option 'follow', local shell sets `py-shell-name', enforces its use afterwards 

py-force-local-shell-off
------------------------
Restore `py-shell-name' default value and `behaviour'. 

toggle-force-py-shell-name-p
----------------------------
If customized default `py-shell-name' should be enforced upon execution.

If `py-force-py-shell-name-p' should be on or off.
Returns value of `py-force-py-shell-name-p' switched to.

See also commands
force-py-shell-name-p-on
force-py-shell-name-p-off

Caveat: Completion might not work that way.


force-py-shell-name-p-on
------------------------
Switches `py-force-py-shell-name-p' on.

Customized default `py-shell-name' will be enforced upon execution.
Returns value of `py-force-py-shell-name-p'.

Caveat: Completion might not work that way.


force-py-shell-name-p-off
-------------------------
Make sure, `py-force-py-shell-name-p' is off.

Function to use by executes will be guessed from environment.
Returns value of `py-force-py-shell-name-p'. 

py-toggle-indent-tabs-mode
--------------------------
Toggle `indent-tabs-mode'.

Returns value of `indent-tabs-mode' switched to. 

py-indent-tabs-mode-on
----------------------
Switch `indent-tabs-mode' on. 

py-indent-tabs-mode-off
-----------------------
Switch `indent-tabs-mode' off. 

toggle-py-jump-on-exception
---------------------------
If `py-jump-on-exception' should be on or off.

  Returns value of `py-jump-on-exception' switched to. 

py-jump-on-exception-on
-----------------------
Make sure, py-jump-on-exception' is on.

Returns value of `py-jump-on-exception'. 

py-jump-on-exception-off
------------------------
Make sure, `py-jump-on-exception' is off.

Returns value of `py-jump-on-exception'. 

toggle-python-mode-v5-behavior-p
--------------------------------
If `python-mode-v5-behavior-p' should be on or off.

  Returns value of `python-mode-v5-behavior-p' switched to. 

python-mode-v5-behavior-p-on
----------------------------
Make sure, `python-mode-v5-behavior-p' is on.

Returns value of `python-mode-v5-behavior-p'. 

python-mode-v5-behavior-p-off
-----------------------------
Make sure, `python-mode-v5-behavior-p' is off.

Returns value of `python-mode-v5-behavior-p'. 

py-toggle-shell-switch-buffers-on-execute
-----------------------------------------
If `py-switch-buffers-on-execute-p' should be on or off.

  Returns value of `py-switch-buffers-on-execute-p' switched to. 

py-shell-switch-buffers-on-execute-on
-------------------------------------
Make sure, `py-switch-buffers-on-execute-p' is on.

Returns value of `py-switch-buffers-on-execute-p'. 

py-shell-switch-buffers-on-execute-off
--------------------------------------
Make sure, `py-switch-buffers-on-execute-p' is off.

Returns value of `py-switch-buffers-on-execute-p'. 

py-toggle-split-windows-on-execute
----------------------------------
If `py-split-windows-on-execute-p' should be on or off.

  Returns value of `py-split-windows-on-execute-p' switched to. 

py-split-windows-on-execute-on
------------------------------
Make sure, `py-split-windows-on-execute-p' is on.

Returns value of `py-split-windows-on-execute-p'. 

py-split-windows-on-execute-off
-------------------------------
Make sure, `py-split-windows-on-execute-p' is off.

Returns value of `py-split-windows-on-execute-p'. 

py-toggle-highlight-indentation
-------------------------------
If `highlight-indentation-p' should be on or off. 

py-highlight-indentation-off
----------------------------
If `highlight-indentation-p' should be on or off. 

py-highlight-indentation-on
---------------------------
If `highlight-indentation-p' should be on or off. 

py-toggle-smart-indentation
---------------------------
If `py-smart-indentation' should be on or off.

Returns value of `py-smart-indentation' switched to. 

py-smart-indentation-on
-----------------------
Make sure, `py-smart-indentation' is on.

Returns value of `py-smart-indentation'. 

py-smart-indentation-off
------------------------
Make sure, `py-smart-indentation' is off.

Returns value of `py-smart-indentation'. 

toggle-py-smart-operator-mode-p
-------------------------------
If `py-smart-operator-mode-p' should be on or off.

  Returns value of `py-smart-operator-mode-p' switched to. 

py-smart-operator-mode-p-on
---------------------------
Make sure, py-smart-operator-mode-p' is on.

Returns value of `py-smart-operator-mode-p'. 

py-smart-operator-mode-p-off
----------------------------
Make sure, py-smart-operator-mode-p' is off.

Returns value of `py-smart-operator-mode-p'. 

toggle-py-use-current-dir-when-execute-p
----------------------------------------
If `py-use-current-dir-when-execute-p' should be on or off.

  Returns value of `py-use-current-dir-when-execute-p' switched to. 

py-use-current-dir-when-execute-p-on
------------------------------------
Make sure, py-use-current-dir-when-execute-p' is on.

Returns value of `py-use-current-dir-when-execute-p'. 

py-use-current-dir-when-execute-p-off
-------------------------------------
Make sure, `py-use-current-dir-when-execute-p' is off.

Returns value of `py-use-current-dir-when-execute-p'. 

py-toggle-autopair-mode
-----------------------
If `py-autopair-mode' should be on or off.

  Returns value of `py-autopair-mode' switched to. 

py-autopair-mode-on
-------------------
Make sure, py-autopair-mode' is on.

Returns value of `py-autopair-mode'. 

py-autopair-mode-off
--------------------
Make sure, py-autopair-mode' is off.

Returns value of `py-autopair-mode'. 

toggle-py-switch-buffers-on-execute-p
-------------------------------------
If `py-switch-buffers-on-execute-p' should be on or off.

  Returns value of `py-switch-buffers-on-execute-p' switched to. 

py-switch-buffers-on-execute-p-on
---------------------------------
Make sure, `py-py-switch-buffers-on-execute-p' is on.

Returns value of `py-switch-buffers-on-execute-p'. 

py-switch-buffers-on-execute-p-off
----------------------------------
Make sure, `py-switch-buffers-on-execute-p' is off.

Returns value of `py-switch-buffers-on-execute-p'. 

toggle-py-split-windows-on-execute-p
------------------------------------
If `py-split-windows-on-execute-p' should be on or off.

  Returns value of `py-split-windows-on-execute-p' switched to. 

py-split-windows-on-execute-p-on
--------------------------------
Make sure, `py-py-split-windows-on-execute-p' is on.

Returns value of `py-split-windows-on-execute-p'. 

py-split-windows-on-execute-p-off
---------------------------------
Make sure, `py-split-windows-on-execute-p' is off.

Returns value of `py-split-windows-on-execute-p'. 

py-toggle-sexp-function
-----------------------
Opens customization 

py-shell-get-process
--------------------
Get appropriate Python process for current buffer and return it.

py-shell-send-string
--------------------
Send STRING to inferior Python PROCESS.
When `py-verbose-p' and MSG is non-nil messages the first line of STRING.

py-switch-to-shell
------------------
Switch to inferior Python process buffer.

py-guess-pdb-path
-----------------
If py-pdb-path isn't set, find location of pdb.py. 

py-forward-line
---------------
Goes to end of line after forward move.

Travels right-margin comments. 

py-go-to-beginning-of-comment
-----------------------------
Go to the beginning of current line's comment, if any.

From a programm use macro `py-beginning-of-comment' instead 

py-leave-comment-or-string-backward
-----------------------------------
If inside a comment or string, leave it backward. 

py-beginning-of-list-pps
------------------------
Go to the beginning of a list.
Optional ARG indicates a start-position for `parse-partial-sexp'.
Return beginning position, nil if not inside.

empty-line-p
------------
Returns t if cursor is at an line with nothing but whitespace-characters, nil otherwise.

py-count-lines
--------------
Count lines in accessible part until current line.

See http://debbugs.gnu.org/cgi/bugreport.cgi?bug=7115

py-switch-to-python
-------------------
Switch to inferior Python process buffer.

py-proc
-------
Return the current Python process.

Start a new process if necessary. 

py-insert-default-shebang
-------------------------
Insert in buffer shebang of installed default Python. 

py-electric-comment
-------------------
Insert a comment. If starting a comment, indent accordingly.

If a numeric argument ARG is provided, that many "#" are inserted
non-electrically.
With C-u "#" electric behavior is inhibited inside a string or comment.

py-electric-colon
-----------------
Insert a colon and indent accordingly.

If a numeric argument ARG is provided, that many colons are inserted
non-electrically.

Electric behavior is inhibited inside a string or
comment or by universal prefix C-u.

Switched by `py-electric-colon-active-p', default is nil
See also `py-electric-colon-greedy-p' 

py-empty-out-list-backward
--------------------------
Deletes all elements from list before point. 

py-electric-backspace
---------------------
Delete preceding character or level of indentation.

With ARG do that ARG times.
Returns column reached. 

py-electric-delete
------------------
Delete following character or levels of whitespace.

With ARG do that ARG times. 

py-indent-line-outmost
----------------------
Indent the current line to the outmost reasonable indent.

With optional C-u an indent with length `py-indent-offset' is inserted unconditionally 

py-indent-line
--------------
Indent the current line according to Python rules.

When called interactivly with C-u, ignore dedenting rules for block closing statements
(e.g. return, raise, break, continue, pass)

An optional C-u followed by a numeric argument neither 1 nor 4 will switch off `py-smart-indentation' for this execution. This permits to correct allowed but unwanted indents.
Similar to `toggle-py-smart-indentation' resp. `py-smart-indentation-off' followed by TAB.

This function is normally used by `indent-line-function' resp.
TAB.
Returns current indentation

When bound to TAB, C-q TAB inserts a TAB.

When `py-tab-shifts-region-p' is `t', not just the current line,
but the region is shiftet that way.

If `py-tab-indents-region-p' is `t' and first TAB doesn't shift
--as indent is at outmost reasonable--, indent-region is called.

C-q TAB inserts a literal TAB-character.

py-newline-and-indent
---------------------
Add a newline and indent to outmost reasonable indent.
When indent is set back manually, this is honoured in following lines. 

py-newline-and-dedent
---------------------
Add a newline and indent to one level below current.
Returns column. 

py-indent-tabs-mode
-------------------
With positive ARG switch `indent-tabs-mode' on.

With negative ARG switch `indent-tabs-mode' off.
Returns value of `indent-tabs-mode' switched to. 

py-guess-indent-forward
-----------------------
Called when moving to end of a form and `py-smart-indentation' is on. 

py-guess-indent-offset
----------------------
Guess `py-indent-offset'.

Set local value of `py-indent-offset', return it

Might change local value of `py-indent-offset' only when called
downwards from beginning of block followed by a statement. Otherwise default-value is returned.

py-narrow-to-defun
------------------
Make text outside current def or class invisible.

The defun visible is the one that contains point or follows point. 

py-shift-left
-------------
Dedent region according to `py-indent-offset' by COUNT times.

If no region is active, current line is dedented.
Returns indentation reached. 

py-shift-right
--------------
Indent region according to `py-indent-offset' by COUNT times.

If no region is active, current line is indented.
Returns indentation reached. 

py-shift-paragraph-right
------------------------
Indent paragraph by COUNT spaces.

COUNT defaults to `py-indent-offset',
use [universal-argument] to specify a different value.

Returns outmost indentation reached. 

py-shift-paragraph-left
-----------------------
Dedent paragraph by COUNT spaces.

COUNT defaults to `py-indent-offset',
use [universal-argument] to specify a different value.

Returns outmost indentation reached. 

py-shift-block-right
--------------------
Indent block by COUNT spaces.

COUNT defaults to `py-indent-offset',
use [universal-argument] to specify a different value.

Returns outmost indentation reached. 

py-shift-block-left
-------------------
Dedent block by COUNT spaces.

COUNT defaults to `py-indent-offset',
use [universal-argument] to specify a different value.

Returns outmost indentation reached. 

py-shift-minor-block-left
-------------------------
Dedent minor-block by COUNT spaces.

COUNT defaults to `py-indent-offset',
use [universal-argument] to specify a different value.

Returns outmost indentation reached.
A minor block is started by a `for', `if', `try' or `with'. 

py-shift-minor-block-right
--------------------------
Indent minor-block by COUNT spaces.

COUNT defaults to `py-indent-offset',
use [universal-argument] to specify a different value.

Returns outmost indentation reached.
A minor block is started by a `for', `if', `try' or `with'. 

py-shift-clause-right
---------------------
Indent clause by COUNT spaces.

COUNT defaults to `py-indent-offset',
use [universal-argument] to specify a different value.

Returns outmost indentation reached. 

py-shift-clause-left
--------------------
Dedent clause by COUNT spaces.

COUNT defaults to `py-indent-offset',
use [universal-argument] to specify a different value.

Returns outmost indentation reached. 

py-shift-block-or-clause-right
------------------------------
Indent block-or-clause by COUNT spaces.

COUNT defaults to `py-indent-offset',
use [universal-argument] to specify a different value.

Returns outmost indentation reached. 

py-shift-block-or-clause-left
-----------------------------
Dedent block-or-clause by COUNT spaces.

COUNT defaults to `py-indent-offset',
use [universal-argument] to specify a different value.

Returns outmost indentation reached. 

py-shift-def-right
------------------
Indent def by COUNT spaces.

COUNT defaults to `py-indent-offset',
use [universal-argument] to specify a different value.

Returns outmost indentation reached. 

py-shift-def-left
-----------------
Dedent def by COUNT spaces.

COUNT defaults to `py-indent-offset',
use [universal-argument] to specify a different value.

Returns outmost indentation reached. 

py-shift-class-right
--------------------
Indent class by COUNT spaces.

COUNT defaults to `py-indent-offset',
use [universal-argument] to specify a different value.

Returns outmost indentation reached. 

py-shift-class-left
-------------------
Dedent class by COUNT spaces.

COUNT defaults to `py-indent-offset',
use [universal-argument] to specify a different value.

Returns outmost indentation reached. 

py-shift-def-or-class-right
---------------------------
Indent def-or-class by COUNT spaces.

COUNT defaults to `py-indent-offset',
use [universal-argument] to specify a different value.

Returns outmost indentation reached. 

py-shift-def-or-class-left
--------------------------
Dedent def-or-class by COUNT spaces.

COUNT defaults to `py-indent-offset',
use [universal-argument] to specify a different value.

Returns outmost indentation reached. 

py-shift-line-right
-------------------
Indent line by COUNT spaces.

COUNT defaults to `py-indent-offset',
use [universal-argument] to specify a different value.

Returns outmost indentation reached. 

py-shift-line-left
------------------
Dedent line by COUNT spaces.

COUNT defaults to `py-indent-offset',
use [universal-argument] to specify a different value.

Returns outmost indentation reached. 

py-shift-statement-right
------------------------
Indent statement by COUNT spaces.

COUNT defaults to `py-indent-offset',
use [universal-argument] to specify a different value.

Returns outmost indentation reached. 

py-shift-statement-left
-----------------------
Dedent statement by COUNT spaces.

COUNT defaults to `py-indent-offset',
use [universal-argument] to specify a different value.

Returns outmost indentation reached. 

py-indent-and-forward
---------------------
Indent current line according to mode, move one line forward. 

py-indent-region
----------------
Reindent a region of Python code.

With optional INDENT-OFFSET specify a different value than `py-indent-offset' at place.

Guesses the outmost reasonable indent
Returns and keeps relative position 

py-beginning-of-paragraph-position
----------------------------------
Returns beginning of paragraph position. 

py-end-of-paragraph-position
----------------------------
Returns end of paragraph position. 

py-beginning-of-block-position
------------------------------
Returns beginning of block position. 

py-end-of-block-position
------------------------
Returns end of block position. 

py-beginning-of-minor-block-position
------------------------------------
Returns beginning of minor-block position. 

py-end-of-minor-block-position
------------------------------
Returns end of minor-block position. 

py-beginning-of-clause-position
-------------------------------
Returns beginning of clause position. 

py-end-of-clause-position
-------------------------
Returns end of clause position. 

py-beginning-of-block-or-clause-position
----------------------------------------
Returns beginning of block-or-clause position. 

py-end-of-block-or-clause-position
----------------------------------
Returns end of block-or-clause position. 

py-beginning-of-def-position
----------------------------
Returns beginning of def position. 

py-end-of-def-position
----------------------
Returns end of def position. 

py-beginning-of-class-position
------------------------------
Returns beginning of class position. 

py-end-of-class-position
------------------------
Returns end of class position. 

py-beginning-of-def-or-class-position
-------------------------------------
Returns beginning of def-or-class position. 

py-end-of-def-or-class-position
-------------------------------
Returns end of def-or-class position. 

py-beginning-of-line-position
-----------------------------
Returns beginning of line position. 

py-end-of-line-position
-----------------------
Returns end of line position. 

py-beginning-of-statement-position
----------------------------------
Returns beginning of statement position. 

py-end-of-statement-position
----------------------------
Returns end of statement position. 

py-beginning-of-comment-position
--------------------------------
Returns beginning of comment position. 

py-end-of-comment-position
--------------------------
Returns end of comment position. 

py-beginning-of-top-level-position
----------------------------------
Returns beginning of top-level position. 

py-end-of-top-level-position
----------------------------
Returns end of top-level position. 

py-beginning-of-partial-expression-position
-------------------------------------------
Returns beginning of partial-expression position. 

py-end-of-partial-expression-position
-------------------------------------
Returns end of partial-expression position. 

py-beginning-of-expression-position
-----------------------------------
Returns beginning of expression position. 

py-end-of-expression-position
-----------------------------
Returns end of expression position. 

py-list-beginning-position
--------------------------
Return lists beginning position, nil if not inside.

Optional ARG indicates a start-position for `parse-partial-sexp'.

py-end-of-list-position
-----------------------
Return end position, nil if not inside.

Optional ARG indicates a start-position for `parse-partial-sexp'.

py-in-triplequoted-string-p
---------------------------
Returns character address of start tqs-string, nil if not inside. 

py-in-string-p
--------------
Returns character address of start of string, nil if not inside. 

py-in-statement-p
-----------------
Returns list of beginning and end-position if inside.

Result is useful for booleans too: (when (py-in-statement-p)...)
will work.


py-bounds-of-statement
----------------------
Returns bounds of statement at point.

With optional POSITION, a number, report bounds of statement at POSITION.
Returns a list, whose car is beg, cdr - end.

py-bounds-of-statements
-----------------------
Bounds of consecutive multitude of statements around point.

Indented same level, which don't open blocks. 

py-bounds-of-block
------------------
Returns bounds of block at point.

With optional POSITION, a number, report bounds of block at POSITION.
Returns a list, whose car is beg, cdr - end.

py-bounds-of-clause
-------------------
Returns bounds of clause at point.

With optional POSITION, a number, report bounds of clause at POSITION.
Returns a list, whose car is beg, cdr - end.

py-bounds-of-block-or-clause
----------------------------
Returns bounds of block-or-clause at point.

With optional POSITION, a number, report bounds of block-or-clause at POSITION.
Returns a list, whose car is beg, cdr - end.

py-bounds-of-def
----------------
Returns bounds of def at point.

With optional POSITION, a number, report bounds of def at POSITION.
Returns a list, whose car is beg, cdr - end.

py-bounds-of-class
------------------
Returns bounds of class at point.

With optional POSITION, a number, report bounds of class at POSITION.
Returns a list, whose car is beg, cdr - end.

py-bounds-of-region
-------------------
Returns bounds of region at point.

Returns a list, whose car is beg, cdr - end.

py-bounds-of-buffer
-------------------
Returns bounds of buffer at point.

With optional POSITION, a number, report bounds of buffer at POSITION.
Returns a list, whose car is beg, cdr - end.

py-bounds-of-expression
-----------------------
Returns bounds of expression at point.

With optional POSITION, a number, report bounds of expression at POSITION.
Returns a list, whose car is beg, cdr - end.

py-bounds-of-partial-expression
-------------------------------
Returns bounds of partial-expression at point.

With optional POSITION, a number, report bounds of partial-expression at POSITION.
Returns a list, whose car is beg, cdr - end.

py-bounds-of-declarations
-------------------------
Bounds of consecutive multitude of assigments resp. statements around point.

Indented same level, which don't open blocks.
Typically declarations resp. initialisations of variables following
a class or function definition.
See also py-bounds-of-statements 

py-beginning-of-comment
-----------------------
Go to the beginning of current line's comment, if any.

Returns position if succesful. 

py-end-of-comment
-----------------
Go to the end of comment at point.

Returns position, nil if not in comment.

py-comment-region
-----------------
Like `comment-region' but uses double hash (`#') comment starter.

py-comment-block
----------------
Comments block at point.

Uses double hash (`#') comment starter when `py-block-comment-prefix-p' is  `t',
the default

py-comment-minor-block
----------------------
Comments a block started by a `for', `if', `try' or `with'.

Uses double hash (`#') comment starter when `py-block-comment-prefix-p' is  `t',
the default

py-comment-top-level
--------------------
Comments top-level form at point.

Uses double hash (`#') comment starter when `py-block-comment-prefix-p' is  `t',
the default

py-comment-clause
-----------------
Comments clause at point.

Uses double hash (`#') comment starter when `py-block-comment-prefix-p' is  `t',
the default

py-comment-block-or-clause
--------------------------
Comments block-or-clause at point.

Uses double hash (`#') comment starter when `py-block-comment-prefix-p' is  `t',
the default

py-comment-def
--------------
Comments def at point.

Uses double hash (`#') comment starter when `py-block-comment-prefix-p' is  `t',
the default

py-comment-class
----------------
Comments class at point.

Uses double hash (`#') comment starter when `py-block-comment-prefix-p' is  `t',
the default

py-comment-def-or-class
-----------------------
Comments def-or-class at point.

Uses double hash (`#') comment starter when `py-block-comment-prefix-p' is  `t',
the default

py-comment-statement
--------------------
Comments statement at point.

Uses double hash (`#') comment starter when `py-block-comment-prefix-p' is  `t',
the default

py-uncomment
------------
Uncomment commented lines at point.

If region is active, restrict uncommenting at region 

py-delete-comments-in-def-or-class
----------------------------------
Delete all commented lines in def-or-class at point

py-delete-comments-in-class
---------------------------
Delete all commented lines in class at point

py-delete-comments-in-block
---------------------------
Delete all commented lines in block at point

py-delete-comments-in-region
----------------------------
Delete all commented lines in region. 

py-fill-comment
---------------
Fill the comment paragraph at point

py-end-of-string
----------------
Go to end of string at point, return position.

Takes the result of (syntax-ppss)

py-fill-this-paragraph
----------------------
Fill just the paragraph at point. 

py-fill-paragraph
-----------------
`fill-paragraph-function'

If `py-paragraph-fill-docstring-p' and inside a docstring, the whole docstring is formatted.
See also `py-fill-string' 

py-fill-labelled-string
-----------------------
Fill string or paragraph containing lines starting with label

See lp:1066489 

py-fill-string
--------------
String fill function for `py-fill-paragraph'.
JUSTIFY should be used (if applicable) as in `fill-paragraph'.

DOCSTRING is either a boolean or 'no
If `py-paragraph-fill-docstring-p' is `t', `M-q` fills the
complete docstring according to setting of `py-docstring-style' 

py-fill-string-django
---------------------
Fill docstring according to Django's coding standards style.

    """
    Process foo, return bar.
    """

    """
    Process foo, return bar.

    If processing fails throw ProcessingError.
    """

See available styles at `py-fill-paragraph' or var `py-docstring-style'


py-fill-string-onetwo
---------------------
One newline and start and Two at end style.

    """Process foo, return bar."""

    """
    Process foo, return bar.

    If processing fails throw ProcessingError.

    """

See available styles at `py-fill-paragraph' or var `py-docstring-style'


py-fill-string-pep-257
----------------------
PEP-257 with 2 newlines at end of string.

    """Process foo, return bar."""

    """Process foo, return bar.

    If processing fails throw ProcessingError.

    """

See available styles at `py-fill-paragraph' or var `py-docstring-style'


py-fill-string-pep-257-nn
-------------------------
PEP-257 with 1 newline at end of string.

    """Process foo, return bar."""

    """Process foo, return bar.

    If processing fails throw ProcessingError.
    """

See available styles at `py-fill-paragraph' or var `py-docstring-style'


py-fill-string-symmetric
------------------------
Symmetric style.

    """Process foo, return bar."""

    """
    Process foo, return bar.

    If processing fails throw ProcessingError.
    """

See available styles at `py-fill-paragraph' or var `py-docstring-style'


py-beginning-of-top-level-p
---------------------------
Returns position, if cursor is at the beginning of a top-level, nil otherwise. 

py-beginning-of-expression-p
----------------------------
Returns position, if cursor is at the beginning of a expression, nil otherwise. 

py-statement-opens-block-p
--------------------------
Return position if the current statement opens a block
in stricter or wider sense.

For stricter sense specify regexp. 

py-statement-opens-clause-p
---------------------------
Return position if the current statement opens block or clause. 

py-statement-opens-block-or-clause-p
------------------------------------
Return position if the current statement opens block or clause. 

py-statement-opens-class-p
--------------------------
Return `t' if the statement opens a functions or class definition, nil otherwise. 

py-statement-opens-def-p
------------------------
Return `t' if the statement opens a functions or class definition, nil otherwise. 

py-statement-opens-def-or-class-p
---------------------------------
Return `t' if the statement opens a functions or class definition, nil otherwise. 

py-look-downward-for-clause
---------------------------
If beginning of other clause exists downward in current block.

If succesful return position. 

py-current-defun
----------------
Go to the outermost method or class definition in current scope.

Python value for `add-log-current-defun-function'.
This tells add-log.el how to find the current function/method/variable.
Returns name of class or methods definition, if found, nil otherwise.

See customizable variables `py-current-defun-show' and `py-current-defun-delay'.

py-sort-imports
---------------
Sort multiline imports.

Put point inside the parentheses of a multiline import and hit
M-x py-sort-imports to sort the imports lexicographically

py-which-def-or-class
---------------------
Returns concatenated `def' and `class' names in hierarchical order, if cursor is inside.

Returns "???" otherwise
Used by variable `which-func-functions' 

py-which-function
-----------------
Return the name of the function or class, if curser is in, return nil otherwise. 

py-beginning-of-statements
--------------------------
Got to the beginning of statements in current level which don't open blocks. 

py-end-of-statements
--------------------
Got to the end of statements in current level which don't open blocks. 

py-beginning-of-expression
--------------------------
Go to the beginning of a compound python expression.

With numeric ARG do it that many times.

A a compound python expression might be concatenated by "." operator, thus composed by minor python expressions.

If already at the beginning or before a expression, go to next expression in buffer upwards

Expression here is conceived as the syntactical component of a statement in Python. See http://docs.python.org/reference
Operators however are left aside resp. limit py-expression designed for edit-purposes.

py-end-of-expression
--------------------
Go to the end of a compound python expression.

With numeric ARG do it that many times.

A a compound python expression might be concatenated by "." operator, thus composed by minor python expressions.

Expression here is conceived as the syntactical component of a statement in Python. See http://docs.python.org/reference

Operators however are left aside resp. limit py-expression designed for edit-purposes. 

py-beginning-of-line
--------------------
Go to beginning-of-line, return position.

If already at beginning-of-line and not at BOB, go to beginning of previous line. 

py-end-of-line
--------------
Go to end-of-line, return position.

If already at end-of-line and not at EOB, go to end of next line. 

py-beginning-of-statement
-------------------------
Go to the initial line of a simple statement.

For beginning of compound statement use py-beginning-of-block.
For beginning of clause py-beginning-of-clause.

Referring python program structures see for example:
http://docs.python.org/reference/compound_stmts.html

py-beginning-of-declarations
----------------------------
Got to the beginning of assigments resp. statements in current level which don't open blocks.


py-end-of-declarations
----------------------
Got to the end of assigments resp. statements in current level which don't open blocks. 

py-beginning-of-form-intern
---------------------------
Go to beginning of FORM.

With INDENT, go to beginning one level above.
Whit IACT, print result in message buffer.

Returns beginning of FORM if successful, nil otherwise

Referring python program structures see for example:
http://docs.python.org/reference/compound_stmts.html

py-beginning-of-block
---------------------
Go to beginning block, skip whitespace at BOL.

Returns beginning of block if successful, nil otherwise

Referring python program structures see for example:
http://docs.python.org/reference/compound_stmts.html

py-beginning-of-clause
----------------------
Go to beginning clause, skip whitespace at BOL.

Returns beginning of clause if successful, nil otherwise

Referring python program structures see for example:
http://docs.python.org/reference/compound_stmts.html

py-beginning-of-block-or-clause
-------------------------------
Go to beginning block-or-clause, skip whitespace at BOL.

Returns beginning of block-or-clause if successful, nil otherwise

Referring python program structures see for example:
http://docs.python.org/reference/compound_stmts.html

py-beginning-of-def
-------------------
Go to beginning def, skip whitespace at BOL.

Returns beginning of def if successful, nil otherwise

When `py-mark-decorators' is non-nil, decorators are considered too.

Referring python program structures see for example:
http://docs.python.org/reference/compound_stmts.html

py-beginning-of-class
---------------------
Go to beginning class, skip whitespace at BOL.

Returns beginning of class if successful, nil otherwise

When `py-mark-decorators' is non-nil, decorators are considered too.

Referring python program structures see for example:
http://docs.python.org/reference/compound_stmts.html

py-beginning-of-def-or-class
----------------------------
Go to beginning def-or-class, skip whitespace at BOL.

Returns beginning of def-or-class if successful, nil otherwise

When `py-mark-decorators' is non-nil, decorators are considered too. 

py-beginning-of-if-block
------------------------
Go to beginning if-block, skip whitespace at BOL.

Returns beginning of if-block if successful, nil otherwise

Referring python program structures see for example:
http://docs.python.org/reference/compound_stmts.html

py-beginning-of-try-block
-------------------------
Go to beginning try-block, skip whitespace at BOL.

Returns beginning of try-block if successful, nil otherwise

Referring python program structures see for example:
http://docs.python.org/reference/compound_stmts.html

py-beginning-of-minor-block
---------------------------
Go to beginning minor-block, skip whitespace at BOL.

Returns beginning of minor-block if successful, nil otherwise
A minor block is started by a `for', `if', `try' or `with'.


py-beginning-of-block-lc
------------------------
Go to beginning block, go to BOL.

Returns beginning of block if successful, nil otherwise

Referring python program structures see for example:
http://docs.python.org/reference/compound_stmts.html

py-beginning-of-clause-lc
-------------------------
Go to beginning clause, go to BOL.

Returns beginning of clause if successful, nil otherwise

Referring python program structures see for example:
http://docs.python.org/reference/compound_stmts.html

py-beginning-of-block-or-clause-lc
----------------------------------
Go to beginning block-or-clause, go to BOL.

Returns beginning of block-or-clause if successful, nil otherwise

Referring python program structures see for example:
http://docs.python.org/reference/compound_stmts.html

py-beginning-of-def-lc
----------------------
Go to beginning def, go to BOL.

Returns beginning of def if successful, nil otherwise

When `py-mark-decorators' is non-nil, decorators are considered too.

Referring python program structures see for example:
http://docs.python.org/reference/compound_stmts.html

py-beginning-of-class-lc
------------------------
Go to beginning class, go to BOL.

Returns beginning of class if successful, nil otherwise

When `py-mark-decorators' is non-nil, decorators are considered too.

Referring python program structures see for example:
http://docs.python.org/reference/compound_stmts.html

py-beginning-of-def-or-class-lc
-------------------------------
Go to beginning def-or-class, go to BOL.

Returns beginning of def-or-class if successful, nil otherwise

When `py-mark-decorators' is non-nil, decorators are considered too.

Referring python program structures see for example:
http://docs.python.org/reference/compound_stmts.html

py-beginning-of-if-block-lc
---------------------------
Go to beginning if-block, go to BOL.

Returns beginning of if-block if successful, nil otherwise

Referring python program structures see for example:
http://docs.python.org/reference/compound_stmts.html

py-beginning-of-try-block-lc
----------------------------
Go to beginning try-block, go to BOL.

Returns beginning of try-block if successful, nil otherwise

Referring python program structures see for example:
http://docs.python.org/reference/compound_stmts.html

py-beginning-of-minor-block-lc
------------------------------
Go to beginning minor-block, go to BOL.

Returns beginning of minor-block if successful, nil otherwise

Referring python program structures see for example:
http://docs.python.org/reference/compound_stmts.html

py-beginning-of-top-level
-------------------------
Go up to beginning of statments until level of indentation is null.

Returns position if successful, nil otherwise 

py-end-of-top-level
-------------------
Go to end of top-level form at point.

Returns position if successful, nil otherwise

Referring python program structures see for example:
http://docs.python.org/reference/compound_stmts.html

py-beginning
------------
Go to beginning of compound statement or definition at point.

Referring python program structures see for example:
http://docs.python.org/reference/compound_stmts.html

py-end
------
Go to end of of compound statement or definition at point.

Returns position block if successful, nil otherwise

Referring python program structures see for example:
http://docs.python.org/reference/compound_stmts.html

py-up
-----
Go up or to beginning of form if inside.

If inside a delimited form --string or list-- go to it's beginning.
If not at beginning of a statement or block, go to it's beginning.
If at beginning of a statement or block, go to beginning one level above of compound statement or definition at point.

Referring python program structures see for example:
http://docs.python.org/reference/compound_stmts.html

py-down
-------
Go to beginning one level below of compound statement or definition at point.

If no statement or block below, but a delimited form --string or list-- go to it's beginning. Repeated call from there will behave like down-list.

Returns position if successful, nil otherwise

Referring python program structures see for example:
http://docs.python.org/reference/compound_stmts.html

py-end-of-block
---------------
Go to end of block.

Returns end of block if successful, nil otherwise

Referring python program structures see for example:
http://docs.python.org/reference/compound_stmts.html

py-end-of-clause
----------------
Go to end of clause.

Returns end of clause if successful, nil otherwise

Referring python program structures see for example:
http://docs.python.org/reference/compound_stmts.html

py-end-of-block-or-clause
-------------------------
Go to end of block-or-clause.

Returns end of block-or-clause if successful, nil otherwise

Referring python program structures see for example:
http://docs.python.org/reference/compound_stmts.html

py-end-of-def
-------------
Go to end of def.

Returns end of def if successful, nil otherwise

Referring python program structures see for example:
http://docs.python.org/reference/compound_stmts.html

py-end-of-class
---------------
Go to end of class.

Returns end of class if successful, nil otherwise

Referring python program structures see for example:
http://docs.python.org/reference/compound_stmts.html

py-end-of-def-or-class
----------------------
Go to end of def-or-class.

Returns end of def-or-class if successful, nil otherwise

With M-x universal argument or `py-mark-decorators' set to `t', decorators are marked too. 

py-end-of-if-block
------------------
Go to end of if-block.

Returns end of if-block if successful, nil otherwise

Referring python program structures see for example:
http://docs.python.org/reference/compound_stmts.html

py-end-of-try-block
-------------------
Go to end of try-block.

Returns end of try-block if successful, nil otherwise

Referring python program structures see for example:
http://docs.python.org/reference/compound_stmts.html

py-end-of-minor-block
---------------------
Go to end of minor-block.

Returns end of minor-block if successful, nil otherwise

Referring python program structures see for example:
http://docs.python.org/reference/compound_stmts.html

py-declarations
---------------
Copy and mark assigments resp. statements in current level which don't open blocks or start with a keyword.

See also `py-statements', which is more general, taking also simple statements starting with a keyword. 

py-statements
-------------
Copy and mark simple statements in current level which don't open blocks.

More general than py-declarations, which would stop at keywords like a print-statement. 

py-end-of-statement
-------------------
Go to the last char of current statement.

To go just beyond the final line of the current statement, use `py-down-statement-bol'.

Optional argument REPEAT, the number of loops done already, is checked for py-max-specpdl-size error. Avoid eternal loops due to missing string delimters etc. 

py-goto-statement-below
-----------------------
Goto beginning of next statement. 

py-beginning-of-decorator
-------------------------
Go to the beginning of a decorator.

Returns position if succesful 

py-end-of-decorator
-------------------
Go to the end of a decorator.

Returns position if succesful 

py-statement
------------
Statement at point.

Return code of `py-statement' at point, a string. 

py-top-level
------------
Top-Level at point.

Return code of `py-top-level' at point, a string. 

py-block
--------
Block at point.

Return code of `py-block' at point, a string. 

py-clause
---------
Clause at point.

Return code of `py-clause' at point, a string. 

py-block-or-clause
------------------
Block-Or-Clause at point.

Return code of `py-block-or-clause' at point, a string. 

py-def
------
Def at point.

Return code of `py-def' at point, a string. 

py-class
--------
Class at point.

Return code of `py-class' at point, a string. 

py-def-or-class
---------------
Def-Or-Class at point.

Return code of `py-def-or-class' at point, a string. 

py-expression
-------------
Expression at point.

Return code of `py-expression' at point, a string. 

py-partial-expression
---------------------
Partial-Expression at point.

Return code of `py-partial-expression' at point, a string. 

py-minor-block
--------------
Minor-Block at point.

Return code of `py-minor-block' at point, a string. 

py-mark-paragraph
-----------------
Mark paragraph at point.

Returns beginning and end positions of marked area, a cons. 

py-mark-block
-------------
Mark block at point.

Returns beginning and end positions of marked area, a cons. 

py-mark-minor-block
-------------------
Mark minor-block at point.

Returns beginning and end positions of marked area, a cons. 

py-mark-clause
--------------
Mark clause at point.

Returns beginning and end positions of marked area, a cons. 

py-mark-block-or-clause
-----------------------
Mark block-or-clause at point.

Returns beginning and end positions of marked area, a cons. 

py-mark-def
-----------
Mark def at point.

With M-x universal argument or `py-mark-decorators' set to `t', decorators are marked too.
Returns beginning and end positions of marked area, a cons. 

py-mark-class
-------------
Mark class at point.

Returns beginning and end positions of marked area, a cons. 

py-mark-def-or-class
--------------------
Mark def-or-class at point.

Returns beginning and end positions of marked area, a cons. 

py-mark-line
------------
Mark line at point.

Returns beginning and end positions of marked area, a cons. 

py-mark-statement
-----------------
Mark statement at point.

Returns beginning and end positions of marked area, a cons. 

py-mark-top-level
-----------------
Mark top-level form at point.

Returns beginning and end positions of marked area, a cons. 

py-mark-expression
------------------
Mark expression at point.

Returns beginning and end positions of marked area, a cons. 

py-mark-partial-expression
--------------------------
Mark partial-expression at point.

Returns beginning and end positions of marked area, a cons. 

py-copy-statement
-----------------
Copy statement at point.

Store data in kill ring, so it might yanked back. 

py-copy-top-level
-----------------
Copy top-level at point.

Store data in kill ring, so it might yanked back. 

py-copy-block
-------------
Copy block at point.

Store data in kill ring, so it might yanked back. 

py-copy-clause
--------------
Copy clause at point.

Store data in kill ring, so it might yanked back. 

py-copy-block-or-clause
-----------------------
Copy block-or-clause at point.

Store data in kill ring, so it might yanked back. 

py-copy-def
-----------
Copy def at point.

Store data in kill ring, so it might yanked back. 

py-copy-class
-------------
Copy class at point.

Store data in kill ring, so it might yanked back. 

py-copy-def-or-class
--------------------
Copy def-or-class at point.

Store data in kill ring, so it might yanked back. 

py-copy-expression
------------------
Copy expression at point.

Store data in kill ring, so it might yanked back. 

py-copy-partial-expression
--------------------------
Copy partial-expression at point.

Store data in kill ring, so it might yanked back. 

py-copy-minor-block
-------------------
Copy minor-block at point.

Store data in kill ring, so it might yanked back. 

py-delete-statement
-------------------
Delete STATEMENT at point.

Don't store data in kill ring. 

py-delete-top-level
-------------------
Delete TOP-LEVEL at point.

Don't store data in kill ring. 

py-delete-block
---------------
Delete BLOCK at point.

Don't store data in kill ring. 

py-delete-block-or-clause
-------------------------
Delete BLOCK-OR-CLAUSE at point.

Don't store data in kill ring. 

py-delete-def
-------------
Delete DEF at point.

Don't store data in kill ring. 

py-delete-class
---------------
Delete CLASS at point.

Don't store data in kill ring. 

py-delete-def-or-class
----------------------
Delete DEF-OR-CLASS at point.

Don't store data in kill ring. 

py-delete-expression
--------------------
Delete EXPRESSION at point.

Don't store data in kill ring. 

py-delete-partial-expression
----------------------------
Delete PARTIAL-EXPRESSION at point.

Don't store data in kill ring. 

py-delete-minor-block
---------------------
Delete MINOR-BLOCK at point.

Don't store data in kill ring. 
A minor block is started by a `for', `if', `try' or `with'.

py-kill-statements
------------------
Delete statements declared in current level.

Store deleted statements in kill-ring 

py-kill-declarations
--------------------
Delete variables declared in current level.

Store deleted variables in kill-ring 

py-kill-expression
------------------
Delete expression at point.
  Stores data in kill ring. Might be yanked back using `C-y'. 

py-kill-partial-expression
--------------------------
Delete partial-expression at point.
  Stores data in kill ring. Might be yanked back using `C-y'.

"." operators delimit a partial-expression expression on it's level, that's the difference to compound expressions.

py-kill-statement
-----------------
Delete statement at point.

Stores data in kill ring. Might be yanked back using `C-y'. 

py-kill-top-level
-----------------
Delete top-level form at point.

Stores data in kill ring. Might be yanked back using `C-y'. 

py-kill-block
-------------
Delete block at point.

Stores data in kill ring. Might be yanked back using `C-y'. 

py-kill-minor-block
-------------------
Delete minor-block at point.

Stores data in kill ring. Might be yanked back using `C-y'. 

py-kill-block-or-clause
-----------------------
Delete block-or-clause at point.

Stores data in kill ring. Might be yanked back using `C-y'. 

py-kill-def-or-class
--------------------
Delete def-or-class  at point.

Stores data in kill ring. Might be yanked back using `C-y'. 

py-kill-class
-------------
Delete class  at point.

Stores data in kill ring. Might be yanked back using `C-y'. 

py-kill-def
-----------
Delete def  at point.

Stores data in kill ring. Might be yanked back using `C-y'. 

py-kill-clause
--------------
Delete clause at point.

Stores data in kill ring. Might be yanked back using `C-y'. 

py-beginning-of-block-bol-p
---------------------------
Returns position, if cursor is at the beginning of block, at beginning of line, nil otherwise. 

py-end-of-block-bol
-------------------
Goto beginning of line following end of block.
  Returns position reached, if successful, nil otherwise.

See also `py-down-block': down from current definition to next beginning of block below. 

py-mark-block-bol
-----------------
Mark block, take beginning of line positions. 

Returns beginning and end positions of region, a cons. 

py-copy-block-bol
-----------------
Delete block bol at point.

Stores data in kill ring. Might be yanked back using `C-y'. 

py-kill-block-bol
-----------------
Delete block bol at point.

Stores data in kill ring. Might be yanked back using `C-y'. 

py-delete-block-bol
-------------------
Delete block bol at point.

Don't store data in kill ring. 

py-beginning-of-clause-bol-p
----------------------------
Returns position, if cursor is at the beginning of clause, at beginning of line, nil otherwise. 

py-end-of-clause-bol
--------------------
Goto beginning of line following end of clause.
  Returns position reached, if successful, nil otherwise.

See also `py-down-clause': down from current definition to next beginning of clause below. 

py-mark-clause-bol
------------------
Mark clause, take beginning of line positions. 

Returns beginning and end positions of region, a cons. 

py-copy-clause-bol
------------------
Delete clause bol at point.

Stores data in kill ring. Might be yanked back using `C-y'. 

py-kill-clause-bol
------------------
Delete clause bol at point.

Stores data in kill ring. Might be yanked back using `C-y'. 

py-delete-clause-bol
--------------------
Delete clause bol at point.

Don't store data in kill ring. 

py-beginning-of-block-or-clause-bol-p
-------------------------------------
Returns position, if cursor is at the beginning of block-or-clause, at beginning of line, nil otherwise. 

py-end-of-block-or-clause-bol
-----------------------------
Goto beginning of line following end of block-or-clause.
  Returns position reached, if successful, nil otherwise.

See also `py-down-block-or-clause': down from current definition to next beginning of block-or-clause below. 

py-mark-block-or-clause-bol
---------------------------
Mark block-or-clause, take beginning of line positions. 

Returns beginning and end positions of region, a cons. 

py-copy-block-or-clause-bol
---------------------------
Delete block-or-clause bol at point.

Stores data in kill ring. Might be yanked back using `C-y'. 

py-kill-block-or-clause-bol
---------------------------
Delete block-or-clause bol at point.

Stores data in kill ring. Might be yanked back using `C-y'. 

py-delete-block-or-clause-bol
-----------------------------
Delete block-or-clause bol at point.

Don't store data in kill ring. 

py-beginning-of-def-bol-p
-------------------------
Returns position, if cursor is at the beginning of def, at beginning of line, nil otherwise. 

py-end-of-def-bol
-----------------
Goto beginning of line following end of def.
  Returns position reached, if successful, nil otherwise.

See also `py-down-def': down from current definition to next beginning of def below. 

py-mark-def-bol
---------------
Mark def, take beginning of line positions. 

With M-x universal argument or `py-mark-decorators' set to `t', decorators are marked too.
Returns beginning and end positions of region, a cons. 

py-copy-def-bol
---------------
Delete def bol at point.

Stores data in kill ring. Might be yanked back using `C-y'. 

py-kill-def-bol
---------------
Delete def bol at point.

Stores data in kill ring. Might be yanked back using `C-y'. 

py-delete-def-bol
-----------------
Delete def bol at point.

Don't store data in kill ring. 

py-beginning-of-class-bol-p
---------------------------
Returns position, if cursor is at the beginning of class, at beginning of line, nil otherwise. 

py-end-of-class-bol
-------------------
Goto beginning of line following end of class.
  Returns position reached, if successful, nil otherwise.

See also `py-down-class': down from current definition to next beginning of class below. 

py-mark-class-bol
-----------------
Mark class, take beginning of line positions. 

With M-x universal argument or `py-mark-decorators' set to `t', decorators are marked too.
Returns beginning and end positions of region, a cons. 

py-copy-class-bol
-----------------
Delete class bol at point.

Stores data in kill ring. Might be yanked back using `C-y'. 

py-kill-class-bol
-----------------
Delete class bol at point.

Stores data in kill ring. Might be yanked back using `C-y'. 

py-delete-class-bol
-------------------
Delete class bol at point.

Don't store data in kill ring. 

py-beginning-of-def-or-class-bol-p
----------------------------------
Returns position, if cursor is at the beginning of def-or-class, at beginning of line, nil otherwise. 

py-end-of-def-or-class-bol
--------------------------
Goto beginning of line following end of def-or-class.
  Returns position reached, if successful, nil otherwise.

See also `py-down-def-or-class': down from current definition to next beginning of def-or-class below. 

py-mark-def-or-class-bol
------------------------
Mark def-or-class, take beginning of line positions. 

With M-x universal argument or `py-mark-decorators' set to `t', decorators are marked too.
Returns beginning and end positions of region, a cons. 

py-copy-def-or-class-bol
------------------------
Delete def-or-class bol at point.

Stores data in kill ring. Might be yanked back using `C-y'. 

py-kill-def-or-class-bol
------------------------
Delete def-or-class bol at point.

Stores data in kill ring. Might be yanked back using `C-y'. 

py-delete-def-or-class-bol
--------------------------
Delete def-or-class bol at point.

Don't store data in kill ring. 

py-beginning-of-statement-bol-p
-------------------------------
Returns position, if cursor is at the beginning of statement, at beginning of line, nil otherwise. 

py-beginning-of-statement-bol
-----------------------------
Goto beginning of line where statement starts.
  Returns position reached, if successful, nil otherwise.

See also `py-up-statement': up from current definition to next beginning of statement above. 

py-end-of-statement-bol
-----------------------
Goto beginning of line following end of statement.
  Returns position reached, if successful, nil otherwise.

See also `py-down-statement': down from current definition to next beginning of statement below. 

py-mark-statement-bol
---------------------
Mark statement, take beginning of line positions. 

Returns beginning and end positions of region, a cons. 

py-copy-statement-bol
---------------------
Delete statement bol at point.

Stores data in kill ring. Might be yanked back using `C-y'. 

py-kill-statement-bol
---------------------
Delete statement bol at point.

Stores data in kill ring. Might be yanked back using `C-y'. 

py-delete-statement-bol
-----------------------
Delete statement bol at point.

Don't store data in kill ring. 

py-up-statement
---------------
Go to the beginning of next statement upwards in buffer.

Return position if statement found, nil otherwise. 

py-down-statement
-----------------
Go to the beginning of next statement downwards in buffer.

Return position if statement found, nil otherwise. 

py-up-block
-----------
Go to the beginning of next block upwards in buffer.

Return position if block found, nil otherwise. 

py-up-minor-block
-----------------
Go to the beginning of next minor-block upwards in buffer.

Return position if minor-block found, nil otherwise. 

py-up-clause
------------
Go to the beginning of next clause upwards in buffer.

Return position if clause found, nil otherwise. 

py-up-block-or-clause
---------------------
Go to the beginning of next block-or-clause upwards in buffer.

Return position if block-or-clause found, nil otherwise. 

py-up-def
---------
Go to the beginning of next def upwards in buffer.

Return position if def found, nil otherwise. 

py-up-class
-----------
Go to the beginning of next class upwards in buffer.

Return position if class found, nil otherwise. 

py-up-def-or-class
------------------
Go to the beginning of next def-or-class upwards in buffer.

Return position if def-or-class found, nil otherwise. 

py-down-block
-------------
Go to the beginning of next block below in buffer.

Return position if block found, nil otherwise. 

py-down-minor-block
-------------------
Go to the beginning of next minor-block below in buffer.

Return position if minor-block found, nil otherwise. 

py-down-clause
--------------
Go to the beginning of next clause below in buffer.

Return position if clause found, nil otherwise. 

py-down-block-or-clause
-----------------------
Go to the beginning of next block-or-clause below in buffer.

Return position if block-or-clause found, nil otherwise. 

py-down-def
-----------
Go to the beginning of next def below in buffer.

Return position if def found, nil otherwise. 

py-down-class
-------------
Go to the beginning of next class below in buffer.

Return position if class found, nil otherwise. 

py-down-def-or-class
--------------------
Go to the beginning of next def-or-class below in buffer.

Return position if def-or-class found, nil otherwise. 

py-up-block-bol
---------------
Go to the beginning of next block upwards in buffer.

Go to beginning of line.
Return position if block found, nil otherwise. 

py-up-minor-block-bol
---------------------
Go to the beginning of next minor-block upwards in buffer.

Go to beginning of line.
Return position if minor-block found, nil otherwise. 

py-up-clause-bol
----------------
Go to the beginning of next clause upwards in buffer.

Go to beginning of line.
Return position if clause found, nil otherwise. 

py-up-block-or-clause-bol
-------------------------
Go to the beginning of next block-or-clause upwards in buffer.

Go to beginning of line.
Return position if block-or-clause found, nil otherwise. 

py-up-def-bol
-------------
Go to the beginning of next def upwards in buffer.

Go to beginning of line.
Return position if def found, nil otherwise. 

py-up-class-bol
---------------
Go to the beginning of next class upwards in buffer.

Go to beginning of line.
Return position if class found, nil otherwise. 

py-up-def-or-class-bol
----------------------
Go to the beginning of next def-or-class upwards in buffer.

Go to beginning of line.
Return position if def-or-class found, nil otherwise. 

py-down-block-bol
-----------------
Go to the beginning of next block below in buffer.

Go to beginning of line
Return position if block found, nil otherwise 

py-down-minor-block-bol
-----------------------
Go to the beginning of next minor-block below in buffer.

Go to beginning of line
Return position if minor-block found, nil otherwise 

py-down-clause-bol
------------------
Go to the beginning of next clause below in buffer.

Go to beginning of line
Return position if clause found, nil otherwise 

py-down-block-or-clause-bol
---------------------------
Go to the beginning of next block-or-clause below in buffer.

Go to beginning of line
Return position if block-or-clause found, nil otherwise 

py-down-def-bol
---------------
Go to the beginning of next def below in buffer.

Go to beginning of line
Return position if def found, nil otherwise 

py-down-class-bol
-----------------
Go to the beginning of next class below in buffer.

Go to beginning of line
Return position if class found, nil otherwise 

py-down-def-or-class-bol
------------------------
Go to the beginning of next def-or-class below in buffer.

Go to beginning of line
Return position if def-or-class found, nil otherwise 

py-forward-into-nomenclature
----------------------------
Move forward to end of a nomenclature section or word.

With C-u (programmatically, optional argument ARG), do it that many times.

A `nomenclature' is a fancy way of saying AWordWithMixedCaseNotUnderscores.

py-backward-into-nomenclature
-----------------------------
Move backward to beginning of a nomenclature section or word.

With optional ARG, move that many times.  If ARG is negative, move
forward.

A `nomenclature' is a fancy way of saying AWordWithMixedCaseNotUnderscores.

match-paren
-----------
Go to the matching brace, bracket or parenthesis if on its counterpart.

Otherwise insert the character, the key is assigned to, here `%'.
With universal arg  insert a `%'. 

py-beginning-of-block-current-column
------------------------------------
Reach next beginning of block upwards which starts at current column.

Return position

python
------
Start an Python interpreter.

Optional C-u prompts for options to pass to the Python interpreter. See `py-python-command-args'. 

ipython
-------
Start an IPython interpreter.

Optional C-u prompts for options to pass to the IPython interpreter. See `py-python-command-args'. 

python3
-------
Start an Python3 interpreter.

Optional C-u prompts for options to pass to the Python3 interpreter. See `py-python-command-args'. 

python2
-------
Start an Python2 interpreter.

Optional C-u prompts for options to pass to the Python2 interpreter. See `py-python-command-args'. 

python2\.7
----------
Start an Python2.7 interpreter.

Optional C-u prompts for options to pass to the Python2.7 interpreter. See `py-python-command-args'. 

jython
------
Start an Jython interpreter.

Optional C-u prompts for options to pass to the Jython interpreter. See `py-python-command-args'. 

python3\.2
----------
Start an Python3.2 interpreter.

Optional C-u prompts for options to pass to the Python3.2 interpreter. See `py-python-command-args'. 

python3\.3
----------
Start an Python3.3 interpreter.

Optional C-u prompts for options to pass to the Python3.3 interpreter. See `py-python-command-args'. 

python3\.4
----------
Start an Python3.3 interpreter.

Optional C-u prompts for options to pass to the Python3.4 interpreter. See `py-python-command-args'. 

bpython
-------
Start an Bpython interpreter.

Optional C-u prompts for options to pass to the Bpython interpreter. See `py-python-command-args'. 

python-dedicated
----------------
Start an unique Python interpreter in another window.

Optional C-u prompts for options to pass to the Python interpreter. See `py-python-command-args'.

ipython-dedicated
-----------------
Start an unique IPython interpreter in another window.

Optional C-u prompts for options to pass to the IPython interpreter. See `py-python-command-args'.

python3-dedicated
-----------------
Start an unique Python3 interpreter in another window.

Optional C-u prompts for options to pass to the Python3 interpreter. See `py-python-command-args'.

python2-dedicated
-----------------
Start an unique Python2 interpreter in another window.

Optional C-u prompts for options to pass to the Python2 interpreter. See `py-python-command-args'.

python2\.7-dedicated
--------------------
Start an unique Python2.7 interpreter in another window.

Optional C-u prompts for options to pass to the Python2.7 interpreter. See `py-python-command-args'.

jython-dedicated
----------------
Start an unique Jython interpreter in another window.

Optional C-u prompts for options to pass to the Jython interpreter. See `py-python-command-args'.

python3\.2-dedicated
--------------------
Start an unique Python3.2 interpreter in another window.

Optional C-u prompts for options to pass to the Python3.2 interpreter. See `py-python-command-args'.

python3\.3-dedicated
--------------------
Start an unique Python3.3 interpreter in another window.

Optional C-u prompts for options to pass to the Python3.3 interpreter. See `py-python-command-args'.

bpython-dedicated
-----------------
Start an unique Bpython interpreter in another window.

Optional C-u prompts for options to pass to the Bpython interpreter. See `py-python-command-args'.

python-switch
-------------
Switch to Python interpreter in another window.

Optional C-u prompts for options to pass to the Python interpreter. See `py-python-command-args'.

ipython-switch
--------------
Switch to IPython interpreter in another window.

Optional C-u prompts for options to pass to the IPython interpreter. See `py-python-command-args'.

python3-switch
--------------
Switch to Python3 interpreter in another window.

Optional C-u prompts for options to pass to the Python3 interpreter. See `py-python-command-args'.

python2-switch
--------------
Switch to Python2 interpreter in another window.

Optional C-u prompts for options to pass to the Python2 interpreter. See `py-python-command-args'.

python2\.7-switch
-----------------
Switch to Python2.7 interpreter in another window.

Optional C-u prompts for options to pass to the Python2.7 interpreter. See `py-python-command-args'.

jython-switch
-------------
Switch to Jython interpreter in another window.

Optional C-u prompts for options to pass to the Jython interpreter. See `py-python-command-args'.

python3\.2-switch
-----------------
Switch to Python3.2 interpreter in another window.

Optional C-u prompts for options to pass to the Python3.2 interpreter. See `py-python-command-args'.

python3\.3-switch
-----------------
Switch to Python3.3 interpreter in another window.

Optional C-u prompts for options to pass to the Python3.3 interpreter. See `py-python-command-args'.

bpython-switch
--------------
Switch to Bpython interpreter in another window.

Optional C-u prompts for options to pass to the Bpython interpreter. See `py-python-command-args'.

python-no-switch
----------------
Open an Python interpreter in another window, but do not switch to it.

Optional C-u prompts for options to pass to the Python interpreter. See `py-python-command-args'.

ipython-no-switch
-----------------
Open an IPython interpreter in another window, but do not switch to it.

Optional C-u prompts for options to pass to the IPython interpreter. See `py-python-command-args'.

python3-no-switch
-----------------
Open an Python3 interpreter in another window, but do not switch to it.

Optional C-u prompts for options to pass to the Python3 interpreter. See `py-python-command-args'.

python2-no-switch
-----------------
Open an Python2 interpreter in another window, but do not switch to it.

Optional C-u prompts for options to pass to the Python2 interpreter. See `py-python-command-args'.

python2\.7-no-switch
--------------------
Open an Python2.7 interpreter in another window, but do not switch to it.

Optional C-u prompts for options to pass to the Python2.7 interpreter. See `py-python-command-args'.

jython-no-switch
----------------
Open an Jython interpreter in another window, but do not switch to it.

Optional C-u prompts for options to pass to the Jython interpreter. See `py-python-command-args'.

python3\.2-no-switch
--------------------
Open an Python3.2 interpreter in another window, but do not switch to it.

Optional C-u prompts for options to pass to the Python3.2 interpreter. See `py-python-command-args'.

python3\.3-no-switch
--------------------
Open an Python3.3 interpreter in another window, but do not switch to it.

Optional C-u prompts for options to pass to the Python3.3 interpreter. See `py-python-command-args'.

bpython-no-switch
-----------------
Open an Bpython interpreter in another window, but do not switch to it.

Optional C-u prompts for options to pass to the Bpython interpreter. See `py-python-command-args'.

python-switch-dedicated
-----------------------
Switch to an unique Python interpreter in another window.

Optional C-u prompts for options to pass to the Python interpreter. See `py-python-command-args'.

ipython-switch-dedicated
------------------------
Switch to an unique IPython interpreter in another window.

Optional C-u prompts for options to pass to the IPython interpreter. See `py-python-command-args'.

python3-switch-dedicated
------------------------
Switch to an unique Python3 interpreter in another window.

Optional C-u prompts for options to pass to the Python3 interpreter. See `py-python-command-args'.

python2-switch-dedicated
------------------------
Switch to an unique Python2 interpreter in another window.

Optional C-u prompts for options to pass to the Python2 interpreter. See `py-python-command-args'.

python2\.7-switch-dedicated
---------------------------
Switch to an unique Python2.7 interpreter in another window.

Optional C-u prompts for options to pass to the Python2.7 interpreter. See `py-python-command-args'.

jython-switch-dedicated
-----------------------
Switch to an unique Jython interpreter in another window.

Optional C-u prompts for options to pass to the Jython interpreter. See `py-python-command-args'.

python3\.2-switch-dedicated
---------------------------
Switch to an unique Python3.2 interpreter in another window.

Optional C-u prompts for options to pass to the Python3.2 interpreter. See `py-python-command-args'.

python3\.3-switch-dedicated
---------------------------
Switch to an unique Python3.3 interpreter in another window.

Optional C-u prompts for options to pass to the Python3.3 interpreter. See `py-python-command-args'.

bpython-switch-dedicated
------------------------
Switch to an unique Bpython interpreter in another window.

Optional C-u prompts for options to pass to the Bpython interpreter. See `py-python-command-args'.

py-which-execute-file-command
-----------------------------
Return the command appropriate to Python version.

Per default it's "(format "execfile(r'%s') # PYTHON-MODE\n" filename)" for Python 2 series.

py-execute-region-no-switch
---------------------------
Send the region to a Python interpreter.

Ignores setting of `py-switch-buffers-on-execute-p', buffer with region stays current.
 

py-execute-region-switch
------------------------
Send the region to a Python interpreter.

Ignores setting of `py-switch-buffers-on-execute-p', output-buffer will being switched to.


py-execute-region
-----------------
Send the region to a Python interpreter.

When called with C-u, execution through `default-value' of `py-shell-name' is forced.
When called with C-u followed by a number different from 4 and 1, user is prompted to specify a shell. This might be the name of a system-wide shell or include the path to a virtual environment.

When called from a programm, it accepts a string specifying a shell which will be forced upon execute as argument.

Optional DEDICATED 

py-execute-region-default
-------------------------
Send the region to the systems default Python interpreter. 

py-execute-region-dedicated
---------------------------
Get the region processed by an unique Python interpreter.

When called with C-u, execution through `default-value' of `py-shell-name' is forced.
When called with C-u followed by a number different from 4 and 1, user is prompted to specify a shell. This might be the name of a system-wide shell or include the path to a virtual environment.

When called from a programm, it accepts a string specifying a shell which will be forced upon execute as argument. 

py-execute-region-default-dedicated
-----------------------------------
Send the region to an unique shell of systems default Python. 

py-execute-string
-----------------
Send the argument STRING to a Python interpreter.

See also `py-execute-region'. 

py-execute-string-dedicated
---------------------------
Send the argument STRING to an unique Python interpreter.

See also `py-execute-region'. 

py-fetch-py-master-file
-----------------------
Lookup if a `py-master-file' is specified.

See also doku of variable `py-master-file' 

py-execute-import-or-reload
---------------------------
Import the current buffer's file in a Python interpreter.

If the file has already been imported, then do reload instead to get
the latest version.

If the file's name does not end in ".py", then do execfile instead.

If the current buffer is not visiting a file, do `py-execute-buffer'
instead.

If the file local variable `py-master-file' is non-nil, import or
reload the named file instead of the buffer's file.  The file may be
saved based on the value of `py-execute-import-or-reload-save-p'.

See also `M-x py-execute-region'.

This may be preferable to `M-x py-execute-buffer' because:

 - Definitions stay in their module rather than appearing at top
   level, where they would clutter the global namespace and not affect
   uses of qualified names (MODULE.NAME).

 - The Python debugger gets line number information about the functions.

py-execute-buffer-dedicated
---------------------------
Send the contents of the buffer to a unique Python interpreter. 

py-execute-buffer-switch
------------------------
Send the contents of the buffer to a Python interpreter and switches to output. 

py-execute-buffer-dedicated-switch
----------------------------------
Send the contents of the buffer to an unique Python interpreter.

Ignores setting of `py-switch-buffers-on-execute-p'. 

py-execute-buffer
-----------------
Send the contents of the buffer to a Python interpreter. 

py-execute-buffer-no-switch
---------------------------
Send the contents of the buffer to a Python interpreter but don't switch to output. 

py-execute-defun
----------------
Send the current defun (class or method) to the inferior Python process.

py-process-file
---------------
Process "python filename".

Optional OUTPUT-BUFFER and ERROR-BUFFER might be given. 

py-execute-line
---------------
Send current line from beginning of indent to Python interpreter. 

py-output-filter
----------------
Clear output buffer from py-shell-input prompt etc. 

py-execute-file
---------------
When called interactively, user is prompted for filename. 

py-pdbtrack-toggle-stack-tracking
---------------------------------
Set variable `py-pdbtrack-do-tracking-p'. 

py-fetch-docu
-------------
Lookup in current buffer for the doku for the symbol at point.

Useful for newly defined symbol, not known to python yet. 

py-find-imports
---------------
Find top-level imports.

Returns imports 

py-help-at-point
----------------
Print help on symbol at point.

If symbol is defined in current buffer, jump to it's definition
Optional C-u used for debugging, will prevent deletion of temp file. 

py-describe-mode
----------------
Dump long form of `python-mode' docs.

py-load-file
------------
Load a Python file FILE-NAME into the inferior Python process.

If the file has extension `.py' import or reload it as a module.
Treating it as a module keeps the global namespace clean, provides
function location information for debugging, and supports users of
module-qualified names.

py-find-definition
------------------
Find source of definition of SYMBOL.

Interactively, prompt for SYMBOL.

py-insert-super
---------------
Insert a function "super()" from current environment.

As example given in Python v3.1 documentation » The Python Standard Library »

class C(B):
    def method(self, arg):
        super().method(arg) # This does the same thing as:
                               # super(C, self).method(arg)

Returns the string inserted. 

py-nesting-level
----------------
Accepts the output of `parse-partial-sexp'. 

py-beginning-of-commented-section
---------------------------------
Leave upwards comments and/or empty lines. 

py-symbol-at-point
------------------
Return the current Python symbol.

py-continuation-offset
----------------------
With numeric ARG different from 1 py-continuation-offset is set to that value; returns py-continuation-offset. 

py-compute-indentation
----------------------
Compute Python indentation.

When HONOR-BLOCK-CLOSE-P is non-nil, statements such as `return',
`raise', `break', `continue', and `pass' force one level of dedenting.

Optional arguments are flags resp. values set and used by `py-compute-indentation' internally


py-indentation-of-statement
---------------------------
Returns the indenation of the statement at point. 

py-guess-default-python
-----------------------
Defaults to "python", if guessing didn't succeed. 

py-set-ipython-completion-command-string
----------------------------------------
Set and return `ipython-completion-command-string'. 

py-ipython--module-completion-import
------------------------------------
Import module-completion 

py-shell-dedicated
------------------
Start an interactive Python interpreter in another window.

With optional C-u user is prompted by
`py-choose-shell' for command and options to pass to the Python
interpreter.


py-toggle-split-windows-function
--------------------------------
If window is splitted vertically or horizontally.

When code is executed and `py-split-windows-on-execute-p' is `t', the result is displays in an output-buffer, "*Python*" by default.

Customizable variable `py-split-windows-on-execute-function' tells how to split the screen.

py-shell
--------
Start an interactive Python interpreter in another window.
Interactively, C-u 4 prompts for a buffer.
C-u 2 prompts for `py-python-command-args'.
If `default-directory' is a remote file name, it is also prompted
to change if called with a prefix arg.

Returns py-shell's buffer-name.
Optional string PYSHELLNAME overrides default `py-shell-name'.
BUFFER allows specifying a name, the Python process is connected to
When DONE is `t', `py-shell-manage-windows' is omitted


py-indent-forward-line
----------------------
Indent and move one line forward to next indentation.
Returns column of line reached.

If `py-kill-empty-line' is non-nil, delete an empty line.
When closing a form, use py-close-block et al, which will move and indent likewise.
With M-x universal argument just indent.


py-dedent-forward-line
----------------------
Dedent line and move one line forward. 

py-dedent
---------
Dedent line according to `py-indent-offset'.

With arg, do it that many times.
If point is between indent levels, dedent to next level.
Return indentation reached, if dedent done, nil otherwise.

Affected by `py-dedent-keep-relative-column'. 

py-close-def
------------
Set indent level to that of beginning of function definition.

If final line isn't empty and `py-close-block-provides-newline' non-nil, insert a newline. 

py-close-class
--------------
Set indent level to that of beginning of class definition.

If final line isn't empty and `py-close-block-provides-newline' non-nil, insert a newline. 

py-close-clause
---------------
Set indent level to that of beginning of clause definition.

If final line isn't empty and `py-close-block-provides-newline' non-nil, insert a newline. 

py-close-block
--------------
Set indent level to that of beginning of block definition.

If final line isn't empty and `py-close-block-provides-newline' non-nil, insert a newline. 

py-class-at-point
-----------------
Return class definition as string.

With interactive call, send it to the message buffer too. 

py-match-paren
--------------
Go to the matching brace, bracket or parenthesis if on its counterpart.

Otherwise insert the character, the key is assigned to, here `%'.
With universal arg  insert a `%'. 

py-printform-insert
-------------------
Inserts a print statement out of current `(car kill-ring)' by default, inserts STRING if delivered. 

With optional C-u print as string

eva
---
Put "eval(...)" forms around strings at point. 

pst-here
--------
Kill previous "pdb.set_trace()" and insert it at point. 

py-line-to-printform-python2
----------------------------
Transforms the item on current in a print statement. 

py-switch-imenu-index-function
------------------------------
Switch between series 5. index machine `py-imenu-create-index' and `py-imenu-create-index-new', which also lists modules variables 

py-choose-shell-by-path
-----------------------
Select Python executable according to version desplayed in path, current buffer-file is selected from.

Returns versioned string, nil if nothing appropriate found 

py-choose-shell-by-shebang
--------------------------
Choose shell by looking at #! on the first line.

If SHEBANG is non-nil, returns the shebang as string,
otherwise the Python resp. Jython shell command name. 

py-which-python
---------------
Returns version of Python of current environment, a number. 

py-python-current-environment
-----------------------------
Returns path of current Python installation. 

py-switch-shell
---------------
Toggles between the interpreter customized in `py-shell-toggle-1' resp. `py-shell-toggle-2'. Was hard-coded CPython and Jython in earlier versions, now starts with Python2 and Python3 by default.

ARG might be a python-version string to set to.

C-u `py-toggle-shell' prompts to specify a reachable Python command.
C-u followed by numerical arg 2 or 3, `py-toggle-shell' opens a respective Python shell.
C-u followed by numerical arg 5 opens a Jython shell.

Should you need more shells to select, extend this command by adding inside the first cond:

                    ((eq NUMBER (prefix-numeric-value arg))
                     "MY-PATH-TO-SHELL")

py-choose-shell
---------------
Return an appropriate executable as a string.

Returns nil, if no executable found.

This does the following:
 - look for an interpreter with `py-choose-shell-by-shebang'
 - examine imports using `py-choose-shell-by-import'
 - look if Path/To/File indicates a Python version
 - if not successful, return default value of `py-shell-name'

When interactivly called, messages the shell name, Emacs would in the given circtumstances.

With C-u 4 is called `py-switch-shell' see docu there.

py-install-directory-check
--------------------------
Do some sanity check for `py-install-directory'.

Returns `t' if successful. 

py-guess-py-install-directory
-----------------------------
Takes value of user directory aka $HOME
if `(locate-library "python-mode")' is not succesful.

Used only, if `py-install-directory' is empty. 

py-set-load-path
----------------
Include needed subdirs of python-mode directory. 

py-report-comint-variable-setting
---------------------------------
Display some comint-mode variables of interest for debugging.

Some vars like comint-mode maps and tables are not displayed here because of its amount.

Typing `q' will close the buffer displayed

py-edit-abbrevs
---------------
Jumps to `python-mode-abbrev-table' in a buffer containing lists of abbrev definitions.
You can edit them and type C-c C-c to redefine abbrevs
according to your editing.
Buffer contains a header line for each abbrev table,
 which is the abbrev table name in parentheses.
This is followed by one line per abbrev in that table:
NAME   USECOUNT   EXPANSION   HOOK
where NAME and EXPANSION are strings with quotes,
USECOUNT is an integer, and HOOK is any valid function
or may be omitted (it is usually omitted).  

py-add-abbrev
-------------
Defines python-mode specific abbrev for last expressions before point.
Argument is how many `py-partial-expression's form the expansion; or zero means the region is the expansion.

Reads the abbreviation in the minibuffer; with numeric arg it displays a proposal for an abbrev.
Proposal is composed from the initial character(s) of the
expansion.

Don't use this function in a Lisp program; use `define-abbrev' instead.

py-python-version
-----------------
Returns versions number of a Python EXECUTABLE, string.

If no EXECUTABLE given, `py-shell-name' is used.
Interactively output of `--version' is displayed. 

py-version
----------
Echo the current version of `python-mode' in the minibuffer.

py-install-local-shells
-----------------------
Builds Python-shell commands from executable found in LOCAL.

If LOCAL is empty, shell-command `find' searches beneath current directory.
Eval resulting buffer to install it, see customizable `py-extensions'. 

py-python3-shell-complete
-------------------------
Complete word before point, if any. Otherwise insert TAB. 

py-shell-complete
-----------------
Complete word before point, if any. Otherwise insert TAB. 

ipython-complete
----------------
Complete the python symbol before point.

If no completion available, insert a TAB.
Returns the completed symbol, a string, if successful, nil otherwise. 

pylint-flymake-mode
-------------------
Toggle `pylint' `flymake-mode'. 

pyflakes-flymake-mode
---------------------
Toggle `pyflakes' `flymake-mode'. 

pychecker-flymake-mode
----------------------
Toggle `pychecker' `flymake-mode'. 

pep8-flymake-mode
-----------------
Toggle `pep8' `flymake-mode'. 

pyflakespep8-flymake-mode
-------------------------
Toggle `pyflakespep8' `flymake-mode'.

Joint call to pyflakes and pep8 as proposed by
Keegan Carruthers-Smith

py-pep8-run
-----------
*Run pep8, check formatting - default on the file currently visited.

py-pep8-help
------------
Display pep8 command line help messages. 

py-pylint-run
-------------
*Run pylint (default on the file currently visited).

For help see M-x pylint-help resp. M-x pylint-long-help.
Home-page: http://www.logilab.org/project/pylint 

py-pylint-help
--------------
Display Pylint command line help messages.

Let's have this until more Emacs-like help is prepared 

py-pylint-doku
--------------
Display Pylint Documentation.

Calls `pylint --full-documentation'

py-pyflakes-run
---------------
*Run pyflakes (default on the file currently visited).

For help see M-x pyflakes-help resp. M-x pyflakes-long-help.
Home-page: http://www.logilab.org/project/pyflakes 

py-pyflakes-help
----------------
Display Pyflakes command line help messages.

Let's have this until more Emacs-like help is prepared 

py-pyflakespep8-run
-------------------
*Run pyflakespep8, check formatting (default on the file currently visited).


py-pyflakespep8-help
--------------------
Display pyflakespep8 command line help messages. 

py-flake8-run
-------------
Flake8 is a wrapper around these tools:
        - PyFlakes
        - pep8
        - Ned Batchelder's McCabe script

        It also adds features:
        - files that contain this line are skipped::
            # flake8: noqa
        - lines that contain a ``# noqa`` comment at the end will not issue warnings.
        - a Git and a Mercurial hook.
        - a McCabe complexity checker.
        - extendable through ``flake8.extension`` entry points.

py-flake8-help
--------------
Display flake8 command line help messages. 

py-pychecker-run
----------------
*Run pychecker (default on the file currently visited).

virtualenv-current
------------------
Barfs the current activated virtualenv

virtualenv-deactivate
---------------------
Deactivate the current virtual enviroment

virtualenv-workon
-----------------
Issue a virtualenvwrapper-like virtualenv-workon command

py-execute-statement
--------------------
Send statement at point to a Python interpreter. 

py-execute-block
----------------
Send block at point to a Python interpreter. 

py-execute-block-or-clause
--------------------------
Send block-or-clause at point to a Python interpreter. 

py-execute-def
--------------
Send def at point to a Python interpreter. 

py-execute-class
----------------
Send class at point to a Python interpreter. 

py-execute-def-or-class
-----------------------
Send def-or-class at point to a Python interpreter. 

py-execute-expression
---------------------
Send expression at point to a Python interpreter. 

py-execute-partial-expression
-----------------------------
Send partial-expression at point to a Python interpreter. 

py-execute-top-level
--------------------
Send top-level at point to a Python interpreter. 

py-execute-clause
-----------------
Send clause at point to a Python interpreter. 

py-execute-file-python
----------------------
Send file to a Python interpreter.

py-execute-file-python-switch
-----------------------------
Send file to a Python interpreter.
Ignores default of `py-switch-buffers-on-execute-p', uses it with value "non-nil"

py-execute-file-python-no-switch
--------------------------------
Send file to a Python interpreter.
Ignores default of `py-switch-buffers-on-execute-p', uses it with value "nil"

py-execute-file-python-dedicated
--------------------------------
Send file to a Python interpreter.

Uses a dedicated shell.

py-execute-file-python-dedicated-switch
---------------------------------------
Send file to a Python interpreter.

Uses a dedicated shell.
Ignores default of `py-switch-buffers-on-execute-p', uses it with value "non-nil"

py-execute-file-ipython
-----------------------
Send file to a Ipython interpreter.

py-execute-file-ipython-switch
------------------------------
Send file to a Ipython interpreter.
Ignores default of `py-switch-buffers-on-execute-p', uses it with value "non-nil"

py-execute-file-ipython-no-switch
---------------------------------
Send file to a Ipython interpreter.
Ignores default of `py-switch-buffers-on-execute-p', uses it with value "nil"

py-execute-file-ipython-dedicated
---------------------------------
Send file to a Ipython interpreter.

Uses a dedicated shell.

py-execute-file-ipython-dedicated-switch
----------------------------------------
Send file to a Ipython interpreter.

Uses a dedicated shell.
Ignores default of `py-switch-buffers-on-execute-p', uses it with value "non-nil"

py-execute-file-python3
-----------------------
Send file to a Python3 interpreter.

py-execute-file-python3-switch
------------------------------
Send file to a Python3 interpreter.
Ignores default of `py-switch-buffers-on-execute-p', uses it with value "non-nil"

py-execute-file-python3-no-switch
---------------------------------
Send file to a Python3 interpreter.
Ignores default of `py-switch-buffers-on-execute-p', uses it with value "nil"

py-execute-file-python3-dedicated
---------------------------------
Send file to a Python3 interpreter.

Uses a dedicated shell.

py-execute-file-python3-dedicated-switch
----------------------------------------
Send file to a Python3 interpreter.

Uses a dedicated shell.
Ignores default of `py-switch-buffers-on-execute-p', uses it with value "non-nil"

py-execute-file-python2
-----------------------
Send file to a Python2 interpreter.

py-execute-file-python2-switch
------------------------------
Send file to a Python2 interpreter.
Ignores default of `py-switch-buffers-on-execute-p', uses it with value "non-nil"

py-execute-file-python2-no-switch
---------------------------------
Send file to a Python2 interpreter.
Ignores default of `py-switch-buffers-on-execute-p', uses it with value "nil"

py-execute-file-python2-dedicated
---------------------------------
Send file to a Python2 interpreter.

Uses a dedicated shell.

py-execute-file-python2-dedicated-switch
----------------------------------------
Send file to a Python2 interpreter.

Uses a dedicated shell.
Ignores default of `py-switch-buffers-on-execute-p', uses it with value "non-nil"

py-execute-file-python2\.7
--------------------------
Send file to a Python2.7 interpreter.

py-execute-file-python2\.7-switch
---------------------------------
Send file to a Python2.7 interpreter.
Ignores default of `py-switch-buffers-on-execute-p', uses it with value "non-nil"

py-execute-file-python2\.7-no-switch
------------------------------------
Send file to a Python2.7 interpreter.
Ignores default of `py-switch-buffers-on-execute-p', uses it with value "nil"

py-execute-file-python2\.7-dedicated
------------------------------------
Send file to a Python2.7 interpreter.

Uses a dedicated shell.

py-execute-file-python2\.7-dedicated-switch
-------------------------------------------
Send file to a Python2.7 interpreter.

Uses a dedicated shell.
Ignores default of `py-switch-buffers-on-execute-p', uses it with value "non-nil"

py-execute-file-jython
----------------------
Send file to a Jython interpreter.

py-execute-file-jython-switch
-----------------------------
Send file to a Jython interpreter.
Ignores default of `py-switch-buffers-on-execute-p', uses it with value "non-nil"

py-execute-file-jython-no-switch
--------------------------------
Send file to a Jython interpreter.
Ignores default of `py-switch-buffers-on-execute-p', uses it with value "nil"

py-execute-file-jython-dedicated
--------------------------------
Send file to a Jython interpreter.

Uses a dedicated shell.

py-execute-file-jython-dedicated-switch
---------------------------------------
Send file to a Jython interpreter.

Uses a dedicated shell.
Ignores default of `py-switch-buffers-on-execute-p', uses it with value "non-nil"

py-execute-file-python3\.2
--------------------------
Send file to a Python3.2 interpreter.

py-execute-file-python3\.2-switch
---------------------------------
Send file to a Python3.2 interpreter.
Ignores default of `py-switch-buffers-on-execute-p', uses it with value "non-nil"

py-execute-file-python3\.2-no-switch
------------------------------------
Send file to a Python3.2 interpreter.
Ignores default of `py-switch-buffers-on-execute-p', uses it with value "nil"

py-execute-file-python3\.2-dedicated
------------------------------------
Send file to a Python3.2 interpreter.

Uses a dedicated shell.

py-execute-file-python3\.2-dedicated-switch
-------------------------------------------
Send file to a Python3.2 interpreter.

Uses a dedicated shell.
Ignores default of `py-switch-buffers-on-execute-p', uses it with value "non-nil"

py-execute-file-python3\.3
--------------------------
Send file to a Python3.3 interpreter.

py-execute-file-python3\.3-switch
---------------------------------
Send file to a Python3.3 interpreter.
Ignores default of `py-switch-buffers-on-execute-p', uses it with value "non-nil"

py-execute-file-python3\.3-no-switch
------------------------------------
Send file to a Python3.3 interpreter.
Ignores default of `py-switch-buffers-on-execute-p', uses it with value "nil"

py-execute-file-python3\.3-dedicated
------------------------------------
Send file to a Python3.3 interpreter.

Uses a dedicated shell.

py-execute-file-python3\.3-dedicated-switch
-------------------------------------------
Send file to a Python3.3 interpreter.

Uses a dedicated shell.
Ignores default of `py-switch-buffers-on-execute-p', uses it with value "non-nil"

py-execute-file-bpython
-----------------------
Send file to a Bpython interpreter.

py-execute-file-bpython-switch
------------------------------
Send file to a Bpython interpreter.
Ignores default of `py-switch-buffers-on-execute-p', uses it with value "non-nil"

py-execute-file-bpython-no-switch
---------------------------------
Send file to a Bpython interpreter.
Ignores default of `py-switch-buffers-on-execute-p', uses it with value "nil"

py-execute-file-bpython-dedicated
---------------------------------
Send file to a Bpython interpreter.

Uses a dedicated shell.

py-execute-file-bpython-dedicated-switch
----------------------------------------
Send file to a Bpython interpreter.

Uses a dedicated shell.
Ignores default of `py-switch-buffers-on-execute-p', uses it with value "non-nil"

py-execute-statement-python
---------------------------
Send statement at point to Python interpreter. 

py-execute-statement-python-switch
----------------------------------
Send statement at point to Python interpreter.

Switch to output buffer. Ignores `py-switch-buffers-on-execute-p'. 

py-execute-statement-python-no-switch
-------------------------------------
Send statement at point to Python interpreter.

Keep current buffer. Ignores `py-switch-buffers-on-execute-p' 

py-execute-statement-python-dedicated
-------------------------------------
Send statement at point to Python unique interpreter. 

py-execute-statement-python-dedicated-switch
--------------------------------------------
Send statement at point to Python unique interpreter and switch to result. 

py-execute-statement-ipython
----------------------------
Send statement at point to IPython interpreter. 

py-execute-statement-ipython-switch
-----------------------------------
Send statement at point to IPython interpreter.

Switch to output buffer. Ignores `py-switch-buffers-on-execute-p'. 

py-execute-statement-ipython-no-switch
--------------------------------------
Send statement at point to IPython interpreter.

Keep current buffer. Ignores `py-switch-buffers-on-execute-p' 

py-execute-statement-ipython-dedicated
--------------------------------------
Send statement at point to IPython unique interpreter. 

py-execute-statement-ipython-dedicated-switch
---------------------------------------------
Send statement at point to IPython unique interpreter and switch to result. 

py-execute-statement-python3
----------------------------
Send statement at point to Python3 interpreter. 

py-execute-statement-python3-switch
-----------------------------------
Send statement at point to Python3 interpreter.

Switch to output buffer. Ignores `py-switch-buffers-on-execute-p'. 

py-execute-statement-python3-no-switch
--------------------------------------
Send statement at point to Python3 interpreter.

Keep current buffer. Ignores `py-switch-buffers-on-execute-p' 

py-execute-statement-python3-dedicated
--------------------------------------
Send statement at point to Python3 unique interpreter. 

py-execute-statement-python3-dedicated-switch
---------------------------------------------
Send statement at point to Python3 unique interpreter and switch to result. 

py-execute-statement-python2
----------------------------
Send statement at point to Python2 interpreter. 

py-execute-statement-python2-switch
-----------------------------------
Send statement at point to Python2 interpreter.

Switch to output buffer. Ignores `py-switch-buffers-on-execute-p'. 

py-execute-statement-python2-no-switch
--------------------------------------
Send statement at point to Python2 interpreter.

Keep current buffer. Ignores `py-switch-buffers-on-execute-p' 

py-execute-statement-python2-dedicated
--------------------------------------
Send statement at point to Python2 unique interpreter. 

py-execute-statement-python2-dedicated-switch
---------------------------------------------
Send statement at point to Python2 unique interpreter and switch to result. 

py-execute-statement-python2\.7
-------------------------------
Send statement at point to Python2.7 interpreter. 

py-execute-statement-python2\.7-switch
--------------------------------------
Send statement at point to Python2.7 interpreter.

Switch to output buffer. Ignores `py-switch-buffers-on-execute-p'. 

py-execute-statement-python2\.7-no-switch
-----------------------------------------
Send statement at point to Python2.7 interpreter.

Keep current buffer. Ignores `py-switch-buffers-on-execute-p' 

py-execute-statement-python2\.7-dedicated
-----------------------------------------
Send statement at point to Python2.7 unique interpreter. 

py-execute-statement-python2\.7-dedicated-switch
------------------------------------------------
Send statement at point to Python2.7 unique interpreter and switch to result. 

py-execute-statement-jython
---------------------------
Send statement at point to Jython interpreter. 

py-execute-statement-jython-switch
----------------------------------
Send statement at point to Jython interpreter.

Switch to output buffer. Ignores `py-switch-buffers-on-execute-p'. 

py-execute-statement-jython-no-switch
-------------------------------------
Send statement at point to Jython interpreter.

Keep current buffer. Ignores `py-switch-buffers-on-execute-p' 

py-execute-statement-jython-dedicated
-------------------------------------
Send statement at point to Jython unique interpreter. 

py-execute-statement-jython-dedicated-switch
--------------------------------------------
Send statement at point to Jython unique interpreter and switch to result. 

py-execute-statement-python3\.2
-------------------------------
Send statement at point to Python3.2 interpreter. 

py-execute-statement-python3\.2-switch
--------------------------------------
Send statement at point to Python3.2 interpreter.

Switch to output buffer. Ignores `py-switch-buffers-on-execute-p'. 

py-execute-statement-python3\.2-no-switch
-----------------------------------------
Send statement at point to Python3.2 interpreter.

Keep current buffer. Ignores `py-switch-buffers-on-execute-p' 

py-execute-statement-python3\.2-dedicated
-----------------------------------------
Send statement at point to Python3.2 unique interpreter. 

py-execute-statement-python3\.2-dedicated-switch
------------------------------------------------
Send statement at point to Python3.2 unique interpreter and switch to result. 

py-execute-statement-python3\.3
-------------------------------
Send statement at point to Python3.3 interpreter. 

py-execute-statement-python3\.3-switch
--------------------------------------
Send statement at point to Python3.3 interpreter.

Switch to output buffer. Ignores `py-switch-buffers-on-execute-p'. 

py-execute-statement-python3\.3-no-switch
-----------------------------------------
Send statement at point to Python3.3 interpreter.

Keep current buffer. Ignores `py-switch-buffers-on-execute-p' 

py-execute-statement-python3\.3-dedicated
-----------------------------------------
Send statement at point to Python3.3 unique interpreter. 

py-execute-statement-python3\.3-dedicated-switch
------------------------------------------------
Send statement at point to Python3.3 unique interpreter and switch to result. 

py-execute-statement-bpython
----------------------------
Send statement at point to Bpython interpreter. 

py-execute-statement-bpython-switch
-----------------------------------
Send statement at point to Bpython interpreter.

Switch to output buffer. Ignores `py-switch-buffers-on-execute-p'. 

py-execute-statement-bpython-no-switch
--------------------------------------
Send statement at point to Bpython interpreter.

Keep current buffer. Ignores `py-switch-buffers-on-execute-p' 

py-execute-statement-bpython-dedicated
--------------------------------------
Send statement at point to Bpython unique interpreter. 

py-execute-statement-bpython-dedicated-switch
---------------------------------------------
Send statement at point to Bpython unique interpreter and switch to result. 

py-execute-block-python
-----------------------
Send block at point to Python interpreter. 

py-execute-block-python-switch
------------------------------
Send block at point to Python interpreter.

Switch to output buffer. Ignores `py-switch-buffers-on-execute-p'. 

py-execute-block-python-no-switch
---------------------------------
Send block at point to Python interpreter.

Keep current buffer. Ignores `py-switch-buffers-on-execute-p' 

py-execute-block-python-dedicated
---------------------------------
Send block at point to Python unique interpreter. 

py-execute-block-python-dedicated-switch
----------------------------------------
Send block at point to Python unique interpreter and switch to result. 

py-execute-block-ipython
------------------------
Send block at point to IPython interpreter. 

py-execute-block-ipython-switch
-------------------------------
Send block at point to IPython interpreter.

Switch to output buffer. Ignores `py-switch-buffers-on-execute-p'. 

py-execute-block-ipython-no-switch
----------------------------------
Send block at point to IPython interpreter.

Keep current buffer. Ignores `py-switch-buffers-on-execute-p' 

py-execute-block-ipython-dedicated
----------------------------------
Send block at point to IPython unique interpreter. 

py-execute-block-ipython-dedicated-switch
-----------------------------------------
Send block at point to IPython unique interpreter and switch to result. 

py-execute-block-python3
------------------------
Send block at point to Python3 interpreter. 

py-execute-block-python3-switch
-------------------------------
Send block at point to Python3 interpreter.

Switch to output buffer. Ignores `py-switch-buffers-on-execute-p'. 

py-execute-block-python3-no-switch
----------------------------------
Send block at point to Python3 interpreter.

Keep current buffer. Ignores `py-switch-buffers-on-execute-p' 

py-execute-block-python3-dedicated
----------------------------------
Send block at point to Python3 unique interpreter. 

py-execute-block-python3-dedicated-switch
-----------------------------------------
Send block at point to Python3 unique interpreter and switch to result. 

py-execute-block-python2
------------------------
Send block at point to Python2 interpreter. 

py-execute-block-python2-switch
-------------------------------
Send block at point to Python2 interpreter.

Switch to output buffer. Ignores `py-switch-buffers-on-execute-p'. 

py-execute-block-python2-no-switch
----------------------------------
Send block at point to Python2 interpreter.

Keep current buffer. Ignores `py-switch-buffers-on-execute-p' 

py-execute-block-python2-dedicated
----------------------------------
Send block at point to Python2 unique interpreter. 

py-execute-block-python2-dedicated-switch
-----------------------------------------
Send block at point to Python2 unique interpreter and switch to result. 

py-execute-block-python2\.7
---------------------------
Send block at point to Python2.7 interpreter. 

py-execute-block-python2\.7-switch
----------------------------------
Send block at point to Python2.7 interpreter.

Switch to output buffer. Ignores `py-switch-buffers-on-execute-p'. 

py-execute-block-python2\.7-no-switch
-------------------------------------
Send block at point to Python2.7 interpreter.

Keep current buffer. Ignores `py-switch-buffers-on-execute-p' 

py-execute-block-python2\.7-dedicated
-------------------------------------
Send block at point to Python2.7 unique interpreter. 

py-execute-block-python2\.7-dedicated-switch
--------------------------------------------
Send block at point to Python2.7 unique interpreter and switch to result. 

py-execute-block-jython
-----------------------
Send block at point to Jython interpreter. 

py-execute-block-jython-switch
------------------------------
Send block at point to Jython interpreter.

Switch to output buffer. Ignores `py-switch-buffers-on-execute-p'. 

py-execute-block-jython-no-switch
---------------------------------
Send block at point to Jython interpreter.

Keep current buffer. Ignores `py-switch-buffers-on-execute-p' 

py-execute-block-jython-dedicated
---------------------------------
Send block at point to Jython unique interpreter. 

py-execute-block-jython-dedicated-switch
----------------------------------------
Send block at point to Jython unique interpreter and switch to result. 

py-execute-block-python3\.2
---------------------------
Send block at point to Python3.2 interpreter. 

py-execute-block-python3\.2-switch
----------------------------------
Send block at point to Python3.2 interpreter.

Switch to output buffer. Ignores `py-switch-buffers-on-execute-p'. 

py-execute-block-python3\.2-no-switch
-------------------------------------
Send block at point to Python3.2 interpreter.

Keep current buffer. Ignores `py-switch-buffers-on-execute-p' 

py-execute-block-python3\.2-dedicated
-------------------------------------
Send block at point to Python3.2 unique interpreter. 

py-execute-block-python3\.2-dedicated-switch
--------------------------------------------
Send block at point to Python3.2 unique interpreter and switch to result. 

py-execute-block-python3\.3
---------------------------
Send block at point to Python3.3 interpreter. 

py-execute-block-python3\.3-switch
----------------------------------
Send block at point to Python3.3 interpreter.

Switch to output buffer. Ignores `py-switch-buffers-on-execute-p'. 

py-execute-block-python3\.3-no-switch
-------------------------------------
Send block at point to Python3.3 interpreter.

Keep current buffer. Ignores `py-switch-buffers-on-execute-p' 

py-execute-block-python3\.3-dedicated
-------------------------------------
Send block at point to Python3.3 unique interpreter. 

py-execute-block-python3\.3-dedicated-switch
--------------------------------------------
Send block at point to Python3.3 unique interpreter and switch to result. 

py-execute-block-bpython
------------------------
Send block at point to Bpython interpreter. 

py-execute-block-bpython-switch
-------------------------------
Send block at point to Bpython interpreter.

Switch to output buffer. Ignores `py-switch-buffers-on-execute-p'. 

py-execute-block-bpython-no-switch
----------------------------------
Send block at point to Bpython interpreter.

Keep current buffer. Ignores `py-switch-buffers-on-execute-p' 

py-execute-block-bpython-dedicated
----------------------------------
Send block at point to Bpython unique interpreter. 

py-execute-block-bpython-dedicated-switch
-----------------------------------------
Send block at point to Bpython unique interpreter and switch to result. 

py-execute-clause-python
------------------------
Send clause at point to Python interpreter. 

py-execute-clause-python-switch
-------------------------------
Send clause at point to Python interpreter.

Switch to output buffer. Ignores `py-switch-buffers-on-execute-p'. 

py-execute-clause-python-no-switch
----------------------------------
Send clause at point to Python interpreter.

Keep current buffer. Ignores `py-switch-buffers-on-execute-p' 

py-execute-clause-python-dedicated
----------------------------------
Send clause at point to Python unique interpreter. 

py-execute-clause-python-dedicated-switch
-----------------------------------------
Send clause at point to Python unique interpreter and switch to result. 

py-execute-clause-ipython
-------------------------
Send clause at point to IPython interpreter. 

py-execute-clause-ipython-switch
--------------------------------
Send clause at point to IPython interpreter.

Switch to output buffer. Ignores `py-switch-buffers-on-execute-p'. 

py-execute-clause-ipython-no-switch
-----------------------------------
Send clause at point to IPython interpreter.

Keep current buffer. Ignores `py-switch-buffers-on-execute-p' 

py-execute-clause-ipython-dedicated
-----------------------------------
Send clause at point to IPython unique interpreter. 

py-execute-clause-ipython-dedicated-switch
------------------------------------------
Send clause at point to IPython unique interpreter and switch to result. 

py-execute-clause-python3
-------------------------
Send clause at point to Python3 interpreter. 

py-execute-clause-python3-switch
--------------------------------
Send clause at point to Python3 interpreter.

Switch to output buffer. Ignores `py-switch-buffers-on-execute-p'. 

py-execute-clause-python3-no-switch
-----------------------------------
Send clause at point to Python3 interpreter.

Keep current buffer. Ignores `py-switch-buffers-on-execute-p' 

py-execute-clause-python3-dedicated
-----------------------------------
Send clause at point to Python3 unique interpreter. 

py-execute-clause-python3-dedicated-switch
------------------------------------------
Send clause at point to Python3 unique interpreter and switch to result. 

py-execute-clause-python2
-------------------------
Send clause at point to Python2 interpreter. 

py-execute-clause-python2-switch
--------------------------------
Send clause at point to Python2 interpreter.

Switch to output buffer. Ignores `py-switch-buffers-on-execute-p'. 

py-execute-clause-python2-no-switch
-----------------------------------
Send clause at point to Python2 interpreter.

Keep current buffer. Ignores `py-switch-buffers-on-execute-p' 

py-execute-clause-python2-dedicated
-----------------------------------
Send clause at point to Python2 unique interpreter. 

py-execute-clause-python2-dedicated-switch
------------------------------------------
Send clause at point to Python2 unique interpreter and switch to result. 

py-execute-clause-python2\.7
----------------------------
Send clause at point to Python2.7 interpreter. 

py-execute-clause-python2\.7-switch
-----------------------------------
Send clause at point to Python2.7 interpreter.

Switch to output buffer. Ignores `py-switch-buffers-on-execute-p'. 

py-execute-clause-python2\.7-no-switch
--------------------------------------
Send clause at point to Python2.7 interpreter.

Keep current buffer. Ignores `py-switch-buffers-on-execute-p' 

py-execute-clause-python2\.7-dedicated
--------------------------------------
Send clause at point to Python2.7 unique interpreter. 

py-execute-clause-python2\.7-dedicated-switch
---------------------------------------------
Send clause at point to Python2.7 unique interpreter and switch to result. 

py-execute-clause-jython
------------------------
Send clause at point to Jython interpreter. 

py-execute-clause-jython-switch
-------------------------------
Send clause at point to Jython interpreter.

Switch to output buffer. Ignores `py-switch-buffers-on-execute-p'. 

py-execute-clause-jython-no-switch
----------------------------------
Send clause at point to Jython interpreter.

Keep current buffer. Ignores `py-switch-buffers-on-execute-p' 

py-execute-clause-jython-dedicated
----------------------------------
Send clause at point to Jython unique interpreter. 

py-execute-clause-jython-dedicated-switch
-----------------------------------------
Send clause at point to Jython unique interpreter and switch to result. 

py-execute-clause-python3\.2
----------------------------
Send clause at point to Python3.2 interpreter. 

py-execute-clause-python3\.2-switch
-----------------------------------
Send clause at point to Python3.2 interpreter.

Switch to output buffer. Ignores `py-switch-buffers-on-execute-p'. 

py-execute-clause-python3\.2-no-switch
--------------------------------------
Send clause at point to Python3.2 interpreter.

Keep current buffer. Ignores `py-switch-buffers-on-execute-p' 

py-execute-clause-python3\.2-dedicated
--------------------------------------
Send clause at point to Python3.2 unique interpreter. 

py-execute-clause-python3\.2-dedicated-switch
---------------------------------------------
Send clause at point to Python3.2 unique interpreter and switch to result. 

py-execute-clause-python3\.3
----------------------------
Send clause at point to Python3.3 interpreter. 

py-execute-clause-python3\.3-switch
-----------------------------------
Send clause at point to Python3.3 interpreter.

Switch to output buffer. Ignores `py-switch-buffers-on-execute-p'. 

py-execute-clause-python3\.3-no-switch
--------------------------------------
Send clause at point to Python3.3 interpreter.

Keep current buffer. Ignores `py-switch-buffers-on-execute-p' 

py-execute-clause-python3\.3-dedicated
--------------------------------------
Send clause at point to Python3.3 unique interpreter. 

py-execute-clause-python3\.3-dedicated-switch
---------------------------------------------
Send clause at point to Python3.3 unique interpreter and switch to result. 

py-execute-clause-bpython
-------------------------
Send clause at point to Bpython interpreter. 

py-execute-clause-bpython-switch
--------------------------------
Send clause at point to Bpython interpreter.

Switch to output buffer. Ignores `py-switch-buffers-on-execute-p'. 

py-execute-clause-bpython-no-switch
-----------------------------------
Send clause at point to Bpython interpreter.

Keep current buffer. Ignores `py-switch-buffers-on-execute-p' 

py-execute-clause-bpython-dedicated
-----------------------------------
Send clause at point to Bpython unique interpreter. 

py-execute-clause-bpython-dedicated-switch
------------------------------------------
Send clause at point to Bpython unique interpreter and switch to result. 

py-execute-block-or-clause-python
---------------------------------
Send block-or-clause at point to Python interpreter. 

py-execute-block-or-clause-python-switch
----------------------------------------
Send block-or-clause at point to Python interpreter.

Switch to output buffer. Ignores `py-switch-buffers-on-execute-p'. 

py-execute-block-or-clause-python-no-switch
-------------------------------------------
Send block-or-clause at point to Python interpreter.

Keep current buffer. Ignores `py-switch-buffers-on-execute-p' 

py-execute-block-or-clause-python-dedicated
-------------------------------------------
Send block-or-clause at point to Python unique interpreter. 

py-execute-block-or-clause-python-dedicated-switch
--------------------------------------------------
Send block-or-clause at point to Python unique interpreter and switch to result. 

py-execute-block-or-clause-ipython
----------------------------------
Send block-or-clause at point to IPython interpreter. 

py-execute-block-or-clause-ipython-switch
-----------------------------------------
Send block-or-clause at point to IPython interpreter.

Switch to output buffer. Ignores `py-switch-buffers-on-execute-p'. 

py-execute-block-or-clause-ipython-no-switch
--------------------------------------------
Send block-or-clause at point to IPython interpreter.

Keep current buffer. Ignores `py-switch-buffers-on-execute-p' 

py-execute-block-or-clause-ipython-dedicated
--------------------------------------------
Send block-or-clause at point to IPython unique interpreter. 

py-execute-block-or-clause-ipython-dedicated-switch
---------------------------------------------------
Send block-or-clause at point to IPython unique interpreter and switch to result. 

py-execute-block-or-clause-python3
----------------------------------
Send block-or-clause at point to Python3 interpreter. 

py-execute-block-or-clause-python3-switch
-----------------------------------------
Send block-or-clause at point to Python3 interpreter.

Switch to output buffer. Ignores `py-switch-buffers-on-execute-p'. 

py-execute-block-or-clause-python3-no-switch
--------------------------------------------
Send block-or-clause at point to Python3 interpreter.

Keep current buffer. Ignores `py-switch-buffers-on-execute-p' 

py-execute-block-or-clause-python3-dedicated
--------------------------------------------
Send block-or-clause at point to Python3 unique interpreter. 

py-execute-block-or-clause-python3-dedicated-switch
---------------------------------------------------
Send block-or-clause at point to Python3 unique interpreter and switch to result. 

py-execute-block-or-clause-python2
----------------------------------
Send block-or-clause at point to Python2 interpreter. 

py-execute-block-or-clause-python2-switch
-----------------------------------------
Send block-or-clause at point to Python2 interpreter.

Switch to output buffer. Ignores `py-switch-buffers-on-execute-p'. 

py-execute-block-or-clause-python2-no-switch
--------------------------------------------
Send block-or-clause at point to Python2 interpreter.

Keep current buffer. Ignores `py-switch-buffers-on-execute-p' 

py-execute-block-or-clause-python2-dedicated
--------------------------------------------
Send block-or-clause at point to Python2 unique interpreter. 

py-execute-block-or-clause-python2-dedicated-switch
---------------------------------------------------
Send block-or-clause at point to Python2 unique interpreter and switch to result. 

py-execute-block-or-clause-python2\.7
-------------------------------------
Send block-or-clause at point to Python2.7 interpreter. 

py-execute-block-or-clause-python2\.7-switch
--------------------------------------------
Send block-or-clause at point to Python2.7 interpreter.

Switch to output buffer. Ignores `py-switch-buffers-on-execute-p'. 

py-execute-block-or-clause-python2\.7-no-switch
-----------------------------------------------
Send block-or-clause at point to Python2.7 interpreter.

Keep current buffer. Ignores `py-switch-buffers-on-execute-p' 

py-execute-block-or-clause-python2\.7-dedicated
-----------------------------------------------
Send block-or-clause at point to Python2.7 unique interpreter. 

py-execute-block-or-clause-python2\.7-dedicated-switch
------------------------------------------------------
Send block-or-clause at point to Python2.7 unique interpreter and switch to result. 

py-execute-block-or-clause-jython
---------------------------------
Send block-or-clause at point to Jython interpreter. 

py-execute-block-or-clause-jython-switch
----------------------------------------
Send block-or-clause at point to Jython interpreter.

Switch to output buffer. Ignores `py-switch-buffers-on-execute-p'. 

py-execute-block-or-clause-jython-no-switch
-------------------------------------------
Send block-or-clause at point to Jython interpreter.

Keep current buffer. Ignores `py-switch-buffers-on-execute-p' 

py-execute-block-or-clause-jython-dedicated
-------------------------------------------
Send block-or-clause at point to Jython unique interpreter. 

py-execute-block-or-clause-jython-dedicated-switch
--------------------------------------------------
Send block-or-clause at point to Jython unique interpreter and switch to result. 

py-execute-block-or-clause-python3\.2
-------------------------------------
Send block-or-clause at point to Python3.2 interpreter. 

py-execute-block-or-clause-python3\.2-switch
--------------------------------------------
Send block-or-clause at point to Python3.2 interpreter.

Switch to output buffer. Ignores `py-switch-buffers-on-execute-p'. 

py-execute-block-or-clause-python3\.2-no-switch
-----------------------------------------------
Send block-or-clause at point to Python3.2 interpreter.

Keep current buffer. Ignores `py-switch-buffers-on-execute-p' 

py-execute-block-or-clause-python3\.2-dedicated
-----------------------------------------------
Send block-or-clause at point to Python3.2 unique interpreter. 

py-execute-block-or-clause-python3\.2-dedicated-switch
------------------------------------------------------
Send block-or-clause at point to Python3.2 unique interpreter and switch to result. 

py-execute-block-or-clause-python3\.3
-------------------------------------
Send block-or-clause at point to Python3.3 interpreter. 

py-execute-block-or-clause-python3\.3-switch
--------------------------------------------
Send block-or-clause at point to Python3.3 interpreter.

Switch to output buffer. Ignores `py-switch-buffers-on-execute-p'. 

py-execute-block-or-clause-python3\.3-no-switch
-----------------------------------------------
Send block-or-clause at point to Python3.3 interpreter.

Keep current buffer. Ignores `py-switch-buffers-on-execute-p' 

py-execute-block-or-clause-python3\.3-dedicated
-----------------------------------------------
Send block-or-clause at point to Python3.3 unique interpreter. 

py-execute-block-or-clause-python3\.3-dedicated-switch
------------------------------------------------------
Send block-or-clause at point to Python3.3 unique interpreter and switch to result. 

py-execute-block-or-clause-bpython
----------------------------------
Send block-or-clause at point to Bpython interpreter. 

py-execute-block-or-clause-bpython-switch
-----------------------------------------
Send block-or-clause at point to Bpython interpreter.

Switch to output buffer. Ignores `py-switch-buffers-on-execute-p'. 

py-execute-block-or-clause-bpython-no-switch
--------------------------------------------
Send block-or-clause at point to Bpython interpreter.

Keep current buffer. Ignores `py-switch-buffers-on-execute-p' 

py-execute-block-or-clause-bpython-dedicated
--------------------------------------------
Send block-or-clause at point to Bpython unique interpreter. 

py-execute-block-or-clause-bpython-dedicated-switch
---------------------------------------------------
Send block-or-clause at point to Bpython unique interpreter and switch to result. 

py-execute-def-python
---------------------
Send def at point to Python interpreter. 

py-execute-def-python-switch
----------------------------
Send def at point to Python interpreter.

Switch to output buffer. Ignores `py-switch-buffers-on-execute-p'. 

py-execute-def-python-no-switch
-------------------------------
Send def at point to Python interpreter.

Keep current buffer. Ignores `py-switch-buffers-on-execute-p' 

py-execute-def-python-dedicated
-------------------------------
Send def at point to Python unique interpreter. 

py-execute-def-python-dedicated-switch
--------------------------------------
Send def at point to Python unique interpreter and switch to result. 

py-execute-def-ipython
----------------------
Send def at point to IPython interpreter. 

py-execute-def-ipython-switch
-----------------------------
Send def at point to IPython interpreter.

Switch to output buffer. Ignores `py-switch-buffers-on-execute-p'. 

py-execute-def-ipython-no-switch
--------------------------------
Send def at point to IPython interpreter.

Keep current buffer. Ignores `py-switch-buffers-on-execute-p' 

py-execute-def-ipython-dedicated
--------------------------------
Send def at point to IPython unique interpreter. 

py-execute-def-ipython-dedicated-switch
---------------------------------------
Send def at point to IPython unique interpreter and switch to result. 

py-execute-def-python3
----------------------
Send def at point to Python3 interpreter. 

py-execute-def-python3-switch
-----------------------------
Send def at point to Python3 interpreter.

Switch to output buffer. Ignores `py-switch-buffers-on-execute-p'. 

py-execute-def-python3-no-switch
--------------------------------
Send def at point to Python3 interpreter.

Keep current buffer. Ignores `py-switch-buffers-on-execute-p' 

py-execute-def-python3-dedicated
--------------------------------
Send def at point to Python3 unique interpreter. 

py-execute-def-python3-dedicated-switch
---------------------------------------
Send def at point to Python3 unique interpreter and switch to result. 

py-execute-def-python2
----------------------
Send def at point to Python2 interpreter. 

py-execute-def-python2-switch
-----------------------------
Send def at point to Python2 interpreter.

Switch to output buffer. Ignores `py-switch-buffers-on-execute-p'. 

py-execute-def-python2-no-switch
--------------------------------
Send def at point to Python2 interpreter.

Keep current buffer. Ignores `py-switch-buffers-on-execute-p' 

py-execute-def-python2-dedicated
--------------------------------
Send def at point to Python2 unique interpreter. 

py-execute-def-python2-dedicated-switch
---------------------------------------
Send def at point to Python2 unique interpreter and switch to result. 

py-execute-def-python2\.7
-------------------------
Send def at point to Python2.7 interpreter. 

py-execute-def-python2\.7-switch
--------------------------------
Send def at point to Python2.7 interpreter.

Switch to output buffer. Ignores `py-switch-buffers-on-execute-p'. 

py-execute-def-python2\.7-no-switch
-----------------------------------
Send def at point to Python2.7 interpreter.

Keep current buffer. Ignores `py-switch-buffers-on-execute-p' 

py-execute-def-python2\.7-dedicated
-----------------------------------
Send def at point to Python2.7 unique interpreter. 

py-execute-def-python2\.7-dedicated-switch
------------------------------------------
Send def at point to Python2.7 unique interpreter and switch to result. 

py-execute-def-jython
---------------------
Send def at point to Jython interpreter. 

py-execute-def-jython-switch
----------------------------
Send def at point to Jython interpreter.

Switch to output buffer. Ignores `py-switch-buffers-on-execute-p'. 

py-execute-def-jython-no-switch
-------------------------------
Send def at point to Jython interpreter.

Keep current buffer. Ignores `py-switch-buffers-on-execute-p' 

py-execute-def-jython-dedicated
-------------------------------
Send def at point to Jython unique interpreter. 

py-execute-def-jython-dedicated-switch
--------------------------------------
Send def at point to Jython unique interpreter and switch to result. 

py-execute-def-python3\.2
-------------------------
Send def at point to Python3.2 interpreter. 

py-execute-def-python3\.2-switch
--------------------------------
Send def at point to Python3.2 interpreter.

Switch to output buffer. Ignores `py-switch-buffers-on-execute-p'. 

py-execute-def-python3\.2-no-switch
-----------------------------------
Send def at point to Python3.2 interpreter.

Keep current buffer. Ignores `py-switch-buffers-on-execute-p' 

py-execute-def-python3\.2-dedicated
-----------------------------------
Send def at point to Python3.2 unique interpreter. 

py-execute-def-python3\.2-dedicated-switch
------------------------------------------
Send def at point to Python3.2 unique interpreter and switch to result. 

py-execute-def-python3\.3
-------------------------
Send def at point to Python3.3 interpreter. 

py-execute-def-python3\.3-switch
--------------------------------
Send def at point to Python3.3 interpreter.

Switch to output buffer. Ignores `py-switch-buffers-on-execute-p'. 

py-execute-def-python3\.3-no-switch
-----------------------------------
Send def at point to Python3.3 interpreter.

Keep current buffer. Ignores `py-switch-buffers-on-execute-p' 

py-execute-def-python3\.3-dedicated
-----------------------------------
Send def at point to Python3.3 unique interpreter. 

py-execute-def-python3\.3-dedicated-switch
------------------------------------------
Send def at point to Python3.3 unique interpreter and switch to result. 

py-execute-def-bpython
----------------------
Send def at point to Bpython interpreter. 

py-execute-def-bpython-switch
-----------------------------
Send def at point to Bpython interpreter.

Switch to output buffer. Ignores `py-switch-buffers-on-execute-p'. 

py-execute-def-bpython-no-switch
--------------------------------
Send def at point to Bpython interpreter.

Keep current buffer. Ignores `py-switch-buffers-on-execute-p' 

py-execute-def-bpython-dedicated
--------------------------------
Send def at point to Bpython unique interpreter. 

py-execute-def-bpython-dedicated-switch
---------------------------------------
Send def at point to Bpython unique interpreter and switch to result. 

py-execute-class-python
-----------------------
Send class at point to Python interpreter. 

py-execute-class-python-switch
------------------------------
Send class at point to Python interpreter.

Switch to output buffer. Ignores `py-switch-buffers-on-execute-p'. 

py-execute-class-python-no-switch
---------------------------------
Send class at point to Python interpreter.

Keep current buffer. Ignores `py-switch-buffers-on-execute-p' 

py-execute-class-python-dedicated
---------------------------------
Send class at point to Python unique interpreter. 

py-execute-class-python-dedicated-switch
----------------------------------------
Send class at point to Python unique interpreter and switch to result. 

py-execute-class-ipython
------------------------
Send class at point to IPython interpreter. 

py-execute-class-ipython-switch
-------------------------------
Send class at point to IPython interpreter.

Switch to output buffer. Ignores `py-switch-buffers-on-execute-p'. 

py-execute-class-ipython-no-switch
----------------------------------
Send class at point to IPython interpreter.

Keep current buffer. Ignores `py-switch-buffers-on-execute-p' 

py-execute-class-ipython-dedicated
----------------------------------
Send class at point to IPython unique interpreter. 

py-execute-class-ipython-dedicated-switch
-----------------------------------------
Send class at point to IPython unique interpreter and switch to result. 

py-execute-class-python3
------------------------
Send class at point to Python3 interpreter. 

py-execute-class-python3-switch
-------------------------------
Send class at point to Python3 interpreter.

Switch to output buffer. Ignores `py-switch-buffers-on-execute-p'. 

py-execute-class-python3-no-switch
----------------------------------
Send class at point to Python3 interpreter.

Keep current buffer. Ignores `py-switch-buffers-on-execute-p' 

py-execute-class-python3-dedicated
----------------------------------
Send class at point to Python3 unique interpreter. 

py-execute-class-python3-dedicated-switch
-----------------------------------------
Send class at point to Python3 unique interpreter and switch to result. 

py-execute-class-python2
------------------------
Send class at point to Python2 interpreter. 

py-execute-class-python2-switch
-------------------------------
Send class at point to Python2 interpreter.

Switch to output buffer. Ignores `py-switch-buffers-on-execute-p'. 

py-execute-class-python2-no-switch
----------------------------------
Send class at point to Python2 interpreter.

Keep current buffer. Ignores `py-switch-buffers-on-execute-p' 

py-execute-class-python2-dedicated
----------------------------------
Send class at point to Python2 unique interpreter. 

py-execute-class-python2-dedicated-switch
-----------------------------------------
Send class at point to Python2 unique interpreter and switch to result. 

py-execute-class-python2\.7
---------------------------
Send class at point to Python2.7 interpreter. 

py-execute-class-python2\.7-switch
----------------------------------
Send class at point to Python2.7 interpreter.

Switch to output buffer. Ignores `py-switch-buffers-on-execute-p'. 

py-execute-class-python2\.7-no-switch
-------------------------------------
Send class at point to Python2.7 interpreter.

Keep current buffer. Ignores `py-switch-buffers-on-execute-p' 

py-execute-class-python2\.7-dedicated
-------------------------------------
Send class at point to Python2.7 unique interpreter. 

py-execute-class-python2\.7-dedicated-switch
--------------------------------------------
Send class at point to Python2.7 unique interpreter and switch to result. 

py-execute-class-jython
-----------------------
Send class at point to Jython interpreter. 

py-execute-class-jython-switch
------------------------------
Send class at point to Jython interpreter.

Switch to output buffer. Ignores `py-switch-buffers-on-execute-p'. 

py-execute-class-jython-no-switch
---------------------------------
Send class at point to Jython interpreter.

Keep current buffer. Ignores `py-switch-buffers-on-execute-p' 

py-execute-class-jython-dedicated
---------------------------------
Send class at point to Jython unique interpreter. 

py-execute-class-jython-dedicated-switch
----------------------------------------
Send class at point to Jython unique interpreter and switch to result. 

py-execute-class-python3\.2
---------------------------
Send class at point to Python3.2 interpreter. 

py-execute-class-python3\.2-switch
----------------------------------
Send class at point to Python3.2 interpreter.

Switch to output buffer. Ignores `py-switch-buffers-on-execute-p'. 

py-execute-class-python3\.2-no-switch
-------------------------------------
Send class at point to Python3.2 interpreter.

Keep current buffer. Ignores `py-switch-buffers-on-execute-p' 

py-execute-class-python3\.2-dedicated
-------------------------------------
Send class at point to Python3.2 unique interpreter. 

py-execute-class-python3\.2-dedicated-switch
--------------------------------------------
Send class at point to Python3.2 unique interpreter and switch to result. 

py-execute-class-python3\.3
---------------------------
Send class at point to Python3.3 interpreter. 

py-execute-class-python3\.3-switch
----------------------------------
Send class at point to Python3.3 interpreter.

Switch to output buffer. Ignores `py-switch-buffers-on-execute-p'. 

py-execute-class-python3\.3-no-switch
-------------------------------------
Send class at point to Python3.3 interpreter.

Keep current buffer. Ignores `py-switch-buffers-on-execute-p' 

py-execute-class-python3\.3-dedicated
-------------------------------------
Send class at point to Python3.3 unique interpreter. 

py-execute-class-python3\.3-dedicated-switch
--------------------------------------------
Send class at point to Python3.3 unique interpreter and switch to result. 

py-execute-class-bpython
------------------------
Send class at point to Bpython interpreter. 

py-execute-class-bpython-switch
-------------------------------
Send class at point to Bpython interpreter.

Switch to output buffer. Ignores `py-switch-buffers-on-execute-p'. 

py-execute-class-bpython-no-switch
----------------------------------
Send class at point to Bpython interpreter.

Keep current buffer. Ignores `py-switch-buffers-on-execute-p' 

py-execute-class-bpython-dedicated
----------------------------------
Send class at point to Bpython unique interpreter. 

py-execute-class-bpython-dedicated-switch
-----------------------------------------
Send class at point to Bpython unique interpreter and switch to result. 

py-execute-region-python
------------------------
Send region at point to Python interpreter. 

py-execute-region-python-switch
-------------------------------
Send region at point to Python interpreter.

Switch to output buffer. Ignores `py-switch-buffers-on-execute-p'. 

py-execute-region-python-no-switch
----------------------------------
Send region at point to Python interpreter.

Keep current buffer. Ignores `py-switch-buffers-on-execute-p' 

py-execute-region-python-dedicated
----------------------------------
Send region at point to Python unique interpreter. 

py-execute-region-python-dedicated-switch
-----------------------------------------
Send region at point to Python unique interpreter and switch to result. 

py-execute-region-ipython
-------------------------
Send region at point to IPython interpreter. 

py-execute-region-ipython-switch
--------------------------------
Send region at point to IPython interpreter.

Switch to output buffer. Ignores `py-switch-buffers-on-execute-p'. 

py-execute-region-ipython-no-switch
-----------------------------------
Send region at point to IPython interpreter.

Keep current buffer. Ignores `py-switch-buffers-on-execute-p' 

py-execute-region-ipython-dedicated
-----------------------------------
Send region at point to IPython unique interpreter. 

py-execute-region-ipython-dedicated-switch
------------------------------------------
Send region at point to IPython unique interpreter and switch to result. 

py-execute-region-python3
-------------------------
Send region at point to Python3 interpreter. 

py-execute-region-python3-switch
--------------------------------
Send region at point to Python3 interpreter.

Switch to output buffer. Ignores `py-switch-buffers-on-execute-p'. 

py-execute-region-python3-no-switch
-----------------------------------
Send region at point to Python3 interpreter.

Keep current buffer. Ignores `py-switch-buffers-on-execute-p' 

py-execute-region-python3-dedicated
-----------------------------------
Send region at point to Python3 unique interpreter. 

py-execute-region-python3-dedicated-switch
------------------------------------------
Send region at point to Python3 unique interpreter and switch to result. 

py-execute-region-python2
-------------------------
Send region at point to Python2 interpreter. 

py-execute-region-python2-switch
--------------------------------
Send region at point to Python2 interpreter.

Switch to output buffer. Ignores `py-switch-buffers-on-execute-p'. 

py-execute-region-python2-no-switch
-----------------------------------
Send region at point to Python2 interpreter.

Keep current buffer. Ignores `py-switch-buffers-on-execute-p' 

py-execute-region-python2-dedicated
-----------------------------------
Send region at point to Python2 unique interpreter. 

py-execute-region-python2-dedicated-switch
------------------------------------------
Send region at point to Python2 unique interpreter and switch to result. 

py-execute-region-python2\.7
----------------------------
Send region at point to Python2.7 interpreter. 

py-execute-region-python2\.7-switch
-----------------------------------
Send region at point to Python2.7 interpreter.

Switch to output buffer. Ignores `py-switch-buffers-on-execute-p'. 

py-execute-region-python2\.7-no-switch
--------------------------------------
Send region at point to Python2.7 interpreter.

Keep current buffer. Ignores `py-switch-buffers-on-execute-p' 

py-execute-region-python2\.7-dedicated
--------------------------------------
Send region at point to Python2.7 unique interpreter. 

py-execute-region-python2\.7-dedicated-switch
---------------------------------------------
Send region at point to Python2.7 unique interpreter and switch to result. 

py-execute-region-jython
------------------------
Send region at point to Jython interpreter. 

py-execute-region-jython-switch
-------------------------------
Send region at point to Jython interpreter.

Switch to output buffer. Ignores `py-switch-buffers-on-execute-p'. 

py-execute-region-jython-no-switch
----------------------------------
Send region at point to Jython interpreter.

Keep current buffer. Ignores `py-switch-buffers-on-execute-p' 

py-execute-region-jython-dedicated
----------------------------------
Send region at point to Jython unique interpreter. 

py-execute-region-jython-dedicated-switch
-----------------------------------------
Send region at point to Jython unique interpreter and switch to result. 

py-execute-region-python3\.2
----------------------------
Send region at point to Python3.2 interpreter. 

py-execute-region-python3\.2-switch
-----------------------------------
Send region at point to Python3.2 interpreter.

Switch to output buffer. Ignores `py-switch-buffers-on-execute-p'. 

py-execute-region-python3\.2-no-switch
--------------------------------------
Send region at point to Python3.2 interpreter.

Keep current buffer. Ignores `py-switch-buffers-on-execute-p' 

py-execute-region-python3\.2-dedicated
--------------------------------------
Send region at point to Python3.2 unique interpreter. 

py-execute-region-python3\.2-dedicated-switch
---------------------------------------------
Send region at point to Python3.2 unique interpreter and switch to result. 

py-execute-region-python3\.3
----------------------------
Send region at point to Python3.3 interpreter. 

py-execute-region-python3\.3-switch
-----------------------------------
Send region at point to Python3.3 interpreter.

Switch to output buffer. Ignores `py-switch-buffers-on-execute-p'. 

py-execute-region-python3\.3-no-switch
--------------------------------------
Send region at point to Python3.3 interpreter.

Keep current buffer. Ignores `py-switch-buffers-on-execute-p' 

py-execute-region-python3\.3-dedicated
--------------------------------------
Send region at point to Python3.3 unique interpreter. 

py-execute-region-python3\.3-dedicated-switch
---------------------------------------------
Send region at point to Python3.3 unique interpreter and switch to result. 

py-execute-region-bpython
-------------------------
Send region at point to Bpython interpreter. 

py-execute-region-bpython-switch
--------------------------------
Send region at point to Bpython interpreter.

Switch to output buffer. Ignores `py-switch-buffers-on-execute-p'. 

py-execute-region-bpython-no-switch
-----------------------------------
Send region at point to Bpython interpreter.

Keep current buffer. Ignores `py-switch-buffers-on-execute-p' 

py-execute-region-bpython-dedicated
-----------------------------------
Send region at point to Bpython unique interpreter. 

py-execute-region-bpython-dedicated-switch
------------------------------------------
Send region at point to Bpython unique interpreter and switch to result. 

py-execute-buffer-python
------------------------
Send buffer at point to Python interpreter. 

py-execute-buffer-python-switch
-------------------------------
Send buffer at point to Python interpreter.

Switch to output buffer. Ignores `py-switch-buffers-on-execute-p'. 

py-execute-buffer-python-no-switch
----------------------------------
Send buffer at point to Python interpreter.

Keep current buffer. Ignores `py-switch-buffers-on-execute-p' 

py-execute-buffer-python-dedicated
----------------------------------
Send buffer at point to Python unique interpreter. 

py-execute-buffer-python-dedicated-switch
-----------------------------------------
Send buffer at point to Python unique interpreter and switch to result. 

py-execute-buffer-ipython
-------------------------
Send buffer at point to IPython interpreter. 

py-execute-buffer-ipython-switch
--------------------------------
Send buffer at point to IPython interpreter.

Switch to output buffer. Ignores `py-switch-buffers-on-execute-p'. 

py-execute-buffer-ipython-no-switch
-----------------------------------
Send buffer at point to IPython interpreter.

Keep current buffer. Ignores `py-switch-buffers-on-execute-p' 

py-execute-buffer-ipython-dedicated
-----------------------------------
Send buffer at point to IPython unique interpreter. 

py-execute-buffer-ipython-dedicated-switch
------------------------------------------
Send buffer at point to IPython unique interpreter and switch to result. 

py-execute-buffer-python3
-------------------------
Send buffer at point to Python3 interpreter. 

py-execute-buffer-python3-switch
--------------------------------
Send buffer at point to Python3 interpreter.

Switch to output buffer. Ignores `py-switch-buffers-on-execute-p'. 

py-execute-buffer-python3-no-switch
-----------------------------------
Send buffer at point to Python3 interpreter.

Keep current buffer. Ignores `py-switch-buffers-on-execute-p' 

py-execute-buffer-python3-dedicated
-----------------------------------
Send buffer at point to Python3 unique interpreter. 

py-execute-buffer-python3-dedicated-switch
------------------------------------------
Send buffer at point to Python3 unique interpreter and switch to result. 

py-execute-buffer-python2
-------------------------
Send buffer at point to Python2 interpreter. 

py-execute-buffer-python2-switch
--------------------------------
Send buffer at point to Python2 interpreter.

Switch to output buffer. Ignores `py-switch-buffers-on-execute-p'. 

py-execute-buffer-python2-no-switch
-----------------------------------
Send buffer at point to Python2 interpreter.

Keep current buffer. Ignores `py-switch-buffers-on-execute-p' 

py-execute-buffer-python2-dedicated
-----------------------------------
Send buffer at point to Python2 unique interpreter. 

py-execute-buffer-python2-dedicated-switch
------------------------------------------
Send buffer at point to Python2 unique interpreter and switch to result. 

py-execute-buffer-python2\.7
----------------------------
Send buffer at point to Python2.7 interpreter. 

py-execute-buffer-python2\.7-switch
-----------------------------------
Send buffer at point to Python2.7 interpreter.

Switch to output buffer. Ignores `py-switch-buffers-on-execute-p'. 

py-execute-buffer-python2\.7-no-switch
--------------------------------------
Send buffer at point to Python2.7 interpreter.

Keep current buffer. Ignores `py-switch-buffers-on-execute-p' 

py-execute-buffer-python2\.7-dedicated
--------------------------------------
Send buffer at point to Python2.7 unique interpreter. 

py-execute-buffer-python2\.7-dedicated-switch
---------------------------------------------
Send buffer at point to Python2.7 unique interpreter and switch to result. 

py-execute-buffer-jython
------------------------
Send buffer at point to Jython interpreter. 

py-execute-buffer-jython-switch
-------------------------------
Send buffer at point to Jython interpreter.

Switch to output buffer. Ignores `py-switch-buffers-on-execute-p'. 

py-execute-buffer-jython-no-switch
----------------------------------
Send buffer at point to Jython interpreter.

Keep current buffer. Ignores `py-switch-buffers-on-execute-p' 

py-execute-buffer-jython-dedicated
----------------------------------
Send buffer at point to Jython unique interpreter. 

py-execute-buffer-jython-dedicated-switch
-----------------------------------------
Send buffer at point to Jython unique interpreter and switch to result. 

py-execute-buffer-python3\.2
----------------------------
Send buffer at point to Python3.2 interpreter. 

py-execute-buffer-python3\.2-switch
-----------------------------------
Send buffer at point to Python3.2 interpreter.

Switch to output buffer. Ignores `py-switch-buffers-on-execute-p'. 

py-execute-buffer-python3\.2-no-switch
--------------------------------------
Send buffer at point to Python3.2 interpreter.

Keep current buffer. Ignores `py-switch-buffers-on-execute-p' 

py-execute-buffer-python3\.2-dedicated
--------------------------------------
Send buffer at point to Python3.2 unique interpreter. 

py-execute-buffer-python3\.2-dedicated-switch
---------------------------------------------
Send buffer at point to Python3.2 unique interpreter and switch to result. 

py-execute-buffer-python3\.3
----------------------------
Send buffer at point to Python3.3 interpreter. 

py-execute-buffer-python3\.3-switch
-----------------------------------
Send buffer at point to Python3.3 interpreter.

Switch to output buffer. Ignores `py-switch-buffers-on-execute-p'. 

py-execute-buffer-python3\.3-no-switch
--------------------------------------
Send buffer at point to Python3.3 interpreter.

Keep current buffer. Ignores `py-switch-buffers-on-execute-p' 

py-execute-buffer-python3\.3-dedicated
--------------------------------------
Send buffer at point to Python3.3 unique interpreter. 

py-execute-buffer-python3\.3-dedicated-switch
---------------------------------------------
Send buffer at point to Python3.3 unique interpreter and switch to result. 

py-execute-buffer-bpython
-------------------------
Send buffer at point to Bpython interpreter. 

py-execute-buffer-bpython-switch
--------------------------------
Send buffer at point to Bpython interpreter.

Switch to output buffer. Ignores `py-switch-buffers-on-execute-p'. 

py-execute-buffer-bpython-no-switch
-----------------------------------
Send buffer at point to Bpython interpreter.

Keep current buffer. Ignores `py-switch-buffers-on-execute-p' 

py-execute-buffer-bpython-dedicated
-----------------------------------
Send buffer at point to Bpython unique interpreter. 

py-execute-buffer-bpython-dedicated-switch
------------------------------------------
Send buffer at point to Bpython unique interpreter and switch to result. 

py-execute-expression-python
----------------------------
Send expression at point to Python interpreter. 

py-execute-expression-python-switch
-----------------------------------
Send expression at point to Python interpreter.

Switch to output buffer. Ignores `py-switch-buffers-on-execute-p'. 

py-execute-expression-python-no-switch
--------------------------------------
Send expression at point to Python interpreter.

Keep current buffer. Ignores `py-switch-buffers-on-execute-p' 

py-execute-expression-python-dedicated
--------------------------------------
Send expression at point to Python unique interpreter. 

py-execute-expression-python-dedicated-switch
---------------------------------------------
Send expression at point to Python unique interpreter and switch to result. 

py-execute-expression-ipython
-----------------------------
Send expression at point to IPython interpreter. 

py-execute-expression-ipython-switch
------------------------------------
Send expression at point to IPython interpreter.

Switch to output buffer. Ignores `py-switch-buffers-on-execute-p'. 

py-execute-expression-ipython-no-switch
---------------------------------------
Send expression at point to IPython interpreter.

Keep current buffer. Ignores `py-switch-buffers-on-execute-p' 

py-execute-expression-ipython-dedicated
---------------------------------------
Send expression at point to IPython unique interpreter. 

py-execute-expression-ipython-dedicated-switch
----------------------------------------------
Send expression at point to IPython unique interpreter and switch to result. 

py-execute-expression-python3
-----------------------------
Send expression at point to Python3 interpreter. 

py-execute-expression-python3-switch
------------------------------------
Send expression at point to Python3 interpreter.

Switch to output buffer. Ignores `py-switch-buffers-on-execute-p'. 

py-execute-expression-python3-no-switch
---------------------------------------
Send expression at point to Python3 interpreter.

Keep current buffer. Ignores `py-switch-buffers-on-execute-p' 

py-execute-expression-python3-dedicated
---------------------------------------
Send expression at point to Python3 unique interpreter. 

py-execute-expression-python3-dedicated-switch
----------------------------------------------
Send expression at point to Python3 unique interpreter and switch to result. 

py-execute-expression-python2
-----------------------------
Send expression at point to Python2 interpreter. 

py-execute-expression-python2-switch
------------------------------------
Send expression at point to Python2 interpreter.

Switch to output buffer. Ignores `py-switch-buffers-on-execute-p'. 

py-execute-expression-python2-no-switch
---------------------------------------
Send expression at point to Python2 interpreter.

Keep current buffer. Ignores `py-switch-buffers-on-execute-p' 

py-execute-expression-python2-dedicated
---------------------------------------
Send expression at point to Python2 unique interpreter. 

py-execute-expression-python2-dedicated-switch
----------------------------------------------
Send expression at point to Python2 unique interpreter and switch to result. 

py-execute-expression-python2\.7
--------------------------------
Send expression at point to Python2.7 interpreter. 

py-execute-expression-python2\.7-switch
---------------------------------------
Send expression at point to Python2.7 interpreter.

Switch to output buffer. Ignores `py-switch-buffers-on-execute-p'. 

py-execute-expression-python2\.7-no-switch
------------------------------------------
Send expression at point to Python2.7 interpreter.

Keep current buffer. Ignores `py-switch-buffers-on-execute-p' 

py-execute-expression-python2\.7-dedicated
------------------------------------------
Send expression at point to Python2.7 unique interpreter. 

py-execute-expression-python2\.7-dedicated-switch
-------------------------------------------------
Send expression at point to Python2.7 unique interpreter and switch to result. 

py-execute-expression-jython
----------------------------
Send expression at point to Jython interpreter. 

py-execute-expression-jython-switch
-----------------------------------
Send expression at point to Jython interpreter.

Switch to output buffer. Ignores `py-switch-buffers-on-execute-p'. 

py-execute-expression-jython-no-switch
--------------------------------------
Send expression at point to Jython interpreter.

Keep current buffer. Ignores `py-switch-buffers-on-execute-p' 

py-execute-expression-jython-dedicated
--------------------------------------
Send expression at point to Jython unique interpreter. 

py-execute-expression-jython-dedicated-switch
---------------------------------------------
Send expression at point to Jython unique interpreter and switch to result. 

py-execute-expression-python3\.2
--------------------------------
Send expression at point to Python3.2 interpreter. 

py-execute-expression-python3\.2-switch
---------------------------------------
Send expression at point to Python3.2 interpreter.

Switch to output buffer. Ignores `py-switch-buffers-on-execute-p'. 

py-execute-expression-python3\.2-no-switch
------------------------------------------
Send expression at point to Python3.2 interpreter.

Keep current buffer. Ignores `py-switch-buffers-on-execute-p' 

py-execute-expression-python3\.2-dedicated
------------------------------------------
Send expression at point to Python3.2 unique interpreter. 

py-execute-expression-python3\.2-dedicated-switch
-------------------------------------------------
Send expression at point to Python3.2 unique interpreter and switch to result. 

py-execute-expression-python3\.3
--------------------------------
Send expression at point to Python3.3 interpreter. 

py-execute-expression-python3\.3-switch
---------------------------------------
Send expression at point to Python3.3 interpreter.

Switch to output buffer. Ignores `py-switch-buffers-on-execute-p'. 

py-execute-expression-python3\.3-no-switch
------------------------------------------
Send expression at point to Python3.3 interpreter.

Keep current buffer. Ignores `py-switch-buffers-on-execute-p' 

py-execute-expression-python3\.3-dedicated
------------------------------------------
Send expression at point to Python3.3 unique interpreter. 

py-execute-expression-python3\.3-dedicated-switch
-------------------------------------------------
Send expression at point to Python3.3 unique interpreter and switch to result. 

py-execute-expression-bpython
-----------------------------
Send expression at point to Bpython interpreter. 

py-execute-expression-bpython-switch
------------------------------------
Send expression at point to Bpython interpreter.

Switch to output buffer. Ignores `py-switch-buffers-on-execute-p'. 

py-execute-expression-bpython-no-switch
---------------------------------------
Send expression at point to Bpython interpreter.

Keep current buffer. Ignores `py-switch-buffers-on-execute-p' 

py-execute-expression-bpython-dedicated
---------------------------------------
Send expression at point to Bpython unique interpreter. 

py-execute-expression-bpython-dedicated-switch
----------------------------------------------
Send expression at point to Bpython unique interpreter and switch to result. 

py-execute-partial-expression-python
------------------------------------
Send partial-expression at point to Python interpreter. 

py-execute-partial-expression-python-switch
-------------------------------------------
Send partial-expression at point to Python interpreter.

Switch to output buffer. Ignores `py-switch-buffers-on-execute-p'. 

py-execute-partial-expression-python-no-switch
----------------------------------------------
Send partial-expression at point to Python interpreter.

Keep current buffer. Ignores `py-switch-buffers-on-execute-p' 

py-execute-partial-expression-python-dedicated
----------------------------------------------
Send partial-expression at point to Python unique interpreter. 

py-execute-partial-expression-python-dedicated-switch
-----------------------------------------------------
Send partial-expression at point to Python unique interpreter and switch to result. 

py-execute-partial-expression-ipython
-------------------------------------
Send partial-expression at point to IPython interpreter. 

py-execute-partial-expression-ipython-switch
--------------------------------------------
Send partial-expression at point to IPython interpreter.

Switch to output buffer. Ignores `py-switch-buffers-on-execute-p'. 

py-execute-partial-expression-ipython-no-switch
-----------------------------------------------
Send partial-expression at point to IPython interpreter.

Keep current buffer. Ignores `py-switch-buffers-on-execute-p' 

py-execute-partial-expression-ipython-dedicated
-----------------------------------------------
Send partial-expression at point to IPython unique interpreter. 

py-execute-partial-expression-ipython-dedicated-switch
------------------------------------------------------
Send partial-expression at point to IPython unique interpreter and switch to result. 

py-execute-partial-expression-python3
-------------------------------------
Send partial-expression at point to Python3 interpreter. 

py-execute-partial-expression-python3-switch
--------------------------------------------
Send partial-expression at point to Python3 interpreter.

Switch to output buffer. Ignores `py-switch-buffers-on-execute-p'. 

py-execute-partial-expression-python3-no-switch
-----------------------------------------------
Send partial-expression at point to Python3 interpreter.

Keep current buffer. Ignores `py-switch-buffers-on-execute-p' 

py-execute-partial-expression-python3-dedicated
-----------------------------------------------
Send partial-expression at point to Python3 unique interpreter. 

py-execute-partial-expression-python3-dedicated-switch
------------------------------------------------------
Send partial-expression at point to Python3 unique interpreter and switch to result. 

py-execute-partial-expression-python2
-------------------------------------
Send partial-expression at point to Python2 interpreter. 

py-execute-partial-expression-python2-switch
--------------------------------------------
Send partial-expression at point to Python2 interpreter.

Switch to output buffer. Ignores `py-switch-buffers-on-execute-p'. 

py-execute-partial-expression-python2-no-switch
-----------------------------------------------
Send partial-expression at point to Python2 interpreter.

Keep current buffer. Ignores `py-switch-buffers-on-execute-p' 

py-execute-partial-expression-python2-dedicated
-----------------------------------------------
Send partial-expression at point to Python2 unique interpreter. 

py-execute-partial-expression-python2-dedicated-switch
------------------------------------------------------
Send partial-expression at point to Python2 unique interpreter and switch to result. 

py-execute-partial-expression-python2\.7
----------------------------------------
Send partial-expression at point to Python2.7 interpreter. 

py-execute-partial-expression-python2\.7-switch
-----------------------------------------------
Send partial-expression at point to Python2.7 interpreter.

Switch to output buffer. Ignores `py-switch-buffers-on-execute-p'. 

py-execute-partial-expression-python2\.7-no-switch
--------------------------------------------------
Send partial-expression at point to Python2.7 interpreter.

Keep current buffer. Ignores `py-switch-buffers-on-execute-p' 

py-execute-partial-expression-python2\.7-dedicated
--------------------------------------------------
Send partial-expression at point to Python2.7 unique interpreter. 

py-execute-partial-expression-python2\.7-dedicated-switch
---------------------------------------------------------
Send partial-expression at point to Python2.7 unique interpreter and switch to result. 

py-execute-partial-expression-jython
------------------------------------
Send partial-expression at point to Jython interpreter. 

py-execute-partial-expression-jython-switch
-------------------------------------------
Send partial-expression at point to Jython interpreter.

Switch to output buffer. Ignores `py-switch-buffers-on-execute-p'. 

py-execute-partial-expression-jython-no-switch
----------------------------------------------
Send partial-expression at point to Jython interpreter.

Keep current buffer. Ignores `py-switch-buffers-on-execute-p' 

py-execute-partial-expression-jython-dedicated
----------------------------------------------
Send partial-expression at point to Jython unique interpreter. 

py-execute-partial-expression-jython-dedicated-switch
-----------------------------------------------------
Send partial-expression at point to Jython unique interpreter and switch to result. 

py-execute-partial-expression-python3\.2
----------------------------------------
Send partial-expression at point to Python3.2 interpreter. 

py-execute-partial-expression-python3\.2-switch
-----------------------------------------------
Send partial-expression at point to Python3.2 interpreter.

Switch to output buffer. Ignores `py-switch-buffers-on-execute-p'. 

py-execute-partial-expression-python3\.2-no-switch
--------------------------------------------------
Send partial-expression at point to Python3.2 interpreter.

Keep current buffer. Ignores `py-switch-buffers-on-execute-p' 

py-execute-partial-expression-python3\.2-dedicated
--------------------------------------------------
Send partial-expression at point to Python3.2 unique interpreter. 

py-execute-partial-expression-python3\.2-dedicated-switch
---------------------------------------------------------
Send partial-expression at point to Python3.2 unique interpreter and switch to result. 

py-execute-partial-expression-python3\.3
----------------------------------------
Send partial-expression at point to Python3.3 interpreter. 

py-execute-partial-expression-python3\.3-switch
-----------------------------------------------
Send partial-expression at point to Python3.3 interpreter.

Switch to output buffer. Ignores `py-switch-buffers-on-execute-p'. 

py-execute-partial-expression-python3\.3-no-switch
--------------------------------------------------
Send partial-expression at point to Python3.3 interpreter.

Keep current buffer. Ignores `py-switch-buffers-on-execute-p' 

py-execute-partial-expression-python3\.3-dedicated
--------------------------------------------------
Send partial-expression at point to Python3.3 unique interpreter. 

py-execute-partial-expression-python3\.3-dedicated-switch
---------------------------------------------------------
Send partial-expression at point to Python3.3 unique interpreter and switch to result. 

py-execute-partial-expression-bpython
-------------------------------------
Send partial-expression at point to Bpython interpreter. 

py-execute-partial-expression-bpython-switch
--------------------------------------------
Send partial-expression at point to Bpython interpreter.

Switch to output buffer. Ignores `py-switch-buffers-on-execute-p'. 

py-execute-partial-expression-bpython-no-switch
-----------------------------------------------
Send partial-expression at point to Bpython interpreter.

Keep current buffer. Ignores `py-switch-buffers-on-execute-p' 

py-execute-partial-expression-bpython-dedicated
-----------------------------------------------
Send partial-expression at point to Bpython unique interpreter. 

py-execute-partial-expression-bpython-dedicated-switch
------------------------------------------------------
Send partial-expression at point to Bpython unique interpreter and switch to result. 

py-execute-line-python
----------------------
Send line at point to Python interpreter. 

py-execute-line-python-switch
-----------------------------
Send line at point to Python interpreter.

Switch to output buffer. Ignores `py-switch-buffers-on-execute-p'. 

py-execute-line-python-no-switch
--------------------------------
Send line at point to Python interpreter.

Keep current buffer. Ignores `py-switch-buffers-on-execute-p' 

py-execute-line-python-dedicated
--------------------------------
Send line at point to Python unique interpreter. 

py-execute-line-python-dedicated-switch
---------------------------------------
Send line at point to Python unique interpreter and switch to result. 

py-execute-line-ipython
-----------------------
Send line at point to IPython interpreter. 

py-execute-line-ipython-switch
------------------------------
Send line at point to IPython interpreter.

Switch to output buffer. Ignores `py-switch-buffers-on-execute-p'. 

py-execute-line-ipython-no-switch
---------------------------------
Send line at point to IPython interpreter.

Keep current buffer. Ignores `py-switch-buffers-on-execute-p' 

py-execute-line-ipython-dedicated
---------------------------------
Send line at point to IPython unique interpreter. 

py-execute-line-ipython-dedicated-switch
----------------------------------------
Send line at point to IPython unique interpreter and switch to result. 

py-execute-line-python3
-----------------------
Send line at point to Python3 interpreter. 

py-execute-line-python3-switch
------------------------------
Send line at point to Python3 interpreter.

Switch to output buffer. Ignores `py-switch-buffers-on-execute-p'. 

py-execute-line-python3-no-switch
---------------------------------
Send line at point to Python3 interpreter.

Keep current buffer. Ignores `py-switch-buffers-on-execute-p' 

py-execute-line-python3-dedicated
---------------------------------
Send line at point to Python3 unique interpreter. 

py-execute-line-python3-dedicated-switch
----------------------------------------
Send line at point to Python3 unique interpreter and switch to result. 

py-execute-line-python2
-----------------------
Send line at point to Python2 interpreter. 

py-execute-line-python2-switch
------------------------------
Send line at point to Python2 interpreter.

Switch to output buffer. Ignores `py-switch-buffers-on-execute-p'. 

py-execute-line-python2-no-switch
---------------------------------
Send line at point to Python2 interpreter.

Keep current buffer. Ignores `py-switch-buffers-on-execute-p' 

py-execute-line-python2-dedicated
---------------------------------
Send line at point to Python2 unique interpreter. 

py-execute-line-python2-dedicated-switch
----------------------------------------
Send line at point to Python2 unique interpreter and switch to result. 

py-execute-line-python2\.7
--------------------------
Send line at point to Python2.7 interpreter. 

py-execute-line-python2\.7-switch
---------------------------------
Send line at point to Python2.7 interpreter.

Switch to output buffer. Ignores `py-switch-buffers-on-execute-p'. 

py-execute-line-python2\.7-no-switch
------------------------------------
Send line at point to Python2.7 interpreter.

Keep current buffer. Ignores `py-switch-buffers-on-execute-p' 

py-execute-line-python2\.7-dedicated
------------------------------------
Send line at point to Python2.7 unique interpreter. 

py-execute-line-python2\.7-dedicated-switch
-------------------------------------------
Send line at point to Python2.7 unique interpreter and switch to result. 

py-execute-line-jython
----------------------
Send line at point to Jython interpreter. 

py-execute-line-jython-switch
-----------------------------
Send line at point to Jython interpreter.

Switch to output buffer. Ignores `py-switch-buffers-on-execute-p'. 

py-execute-line-jython-no-switch
--------------------------------
Send line at point to Jython interpreter.

Keep current buffer. Ignores `py-switch-buffers-on-execute-p' 

py-execute-line-jython-dedicated
--------------------------------
Send line at point to Jython unique interpreter. 

py-execute-line-jython-dedicated-switch
---------------------------------------
Send line at point to Jython unique interpreter and switch to result. 

py-execute-line-python3\.2
--------------------------
Send line at point to Python3.2 interpreter. 

py-execute-line-python3\.2-switch
---------------------------------
Send line at point to Python3.2 interpreter.

Switch to output buffer. Ignores `py-switch-buffers-on-execute-p'. 

py-execute-line-python3\.2-no-switch
------------------------------------
Send line at point to Python3.2 interpreter.

Keep current buffer. Ignores `py-switch-buffers-on-execute-p' 

py-execute-line-python3\.2-dedicated
------------------------------------
Send line at point to Python3.2 unique interpreter. 

py-execute-line-python3\.2-dedicated-switch
-------------------------------------------
Send line at point to Python3.2 unique interpreter and switch to result. 

py-execute-line-python3\.3
--------------------------
Send line at point to Python3.3 interpreter. 

py-execute-line-python3\.3-switch
---------------------------------
Send line at point to Python3.3 interpreter.

Switch to output buffer. Ignores `py-switch-buffers-on-execute-p'. 

py-execute-line-python3\.3-no-switch
------------------------------------
Send line at point to Python3.3 interpreter.

Keep current buffer. Ignores `py-switch-buffers-on-execute-p' 

py-execute-line-python3\.3-dedicated
------------------------------------
Send line at point to Python3.3 unique interpreter. 

py-execute-line-python3\.3-dedicated-switch
-------------------------------------------
Send line at point to Python3.3 unique interpreter and switch to result. 

py-execute-line-bpython
-----------------------
Send line at point to Bpython interpreter. 

py-execute-line-bpython-switch
------------------------------
Send line at point to Bpython interpreter.

Switch to output buffer. Ignores `py-switch-buffers-on-execute-p'. 

py-execute-line-bpython-no-switch
---------------------------------
Send line at point to Bpython interpreter.

Keep current buffer. Ignores `py-switch-buffers-on-execute-p' 

py-execute-line-bpython-dedicated
---------------------------------
Send line at point to Bpython unique interpreter. 

py-execute-line-bpython-dedicated-switch
----------------------------------------
Send line at point to Bpython unique interpreter and switch to result. 

py-remove-overlays-at-point
---------------------------
Remove overlays as set when `py-highlight-error-source-p' is non-nil. 

py-down-exception
-----------------
Go to the next line down in the traceback.
With M-x univeral-argument (programmatically, optional argument
BOTTOM), jump to the bottom (innermost) exception in the exception
stack.

py-up-exception
---------------
Go to the previous line up in the traceback.
With C-u (programmatically, optional argument TOP)
jump to the top (outermost) exception in the exception stack.

py-mouseto-exception
--------------------
Jump to the code which caused the Python exception at EVENT.
EVENT is usually a mouse click.

py-goto-exception
-----------------
Go to the line indicated by the traceback.

py-output-buffer-filter
-----------------------
Clear output buffer from py-shell-input prompt etc. 

py-send-string
--------------
Evaluate STRING in inferior Python process.

py-send-file
------------
Send FILE-NAME to inferior Python PROCESS.
If TEMP-FILE-NAME is passed then that file is used for processing
instead, while internally the shell will continue to use
FILE-NAME.

