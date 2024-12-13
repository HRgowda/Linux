1. Opening and Closing Files
vim <filename>: Open a file in Vim (creates a new file if it doesn't exist).
:w: Save the file.
:q: Quit Vim.
:wq: Save and quit.
:q!: Quit without saving.

2. Modes in Vim
Normal Mode: Default mode for navigation and commands (press Esc to enter).
Insert Mode: Edit text (press i to enter).
Visual Mode: Select text (press v to enter).
Command-Line Mode: Execute commands (press : to enter).

3. Navigation
h: Move left.
l: Move right.
j: Move down.
k: Move up.
w: Jump to the next word.
b: Jump to the previous word.
0: Move to the start of the current line.
^: Move to the first non-blank character in the line.
$: Move to the end of the current line.
gg: Go to the beginning of the file.
G: Go to the end of the file.
:n: Go to line n.

4. Editing
i: Insert text before the cursor.
I: Insert at the beginning of the line.
a: Append text after the cursor.
A: Append at the end of the line.
o: Open a new line below the current line.
O: Open a new line above the current line.
x: Delete the character under the cursor.
dd: Delete the current line.
dw: Delete the current word.
u: Undo the last change.
Ctrl-r: Redo the last undone change.

5. Copy, Cut, and Paste
yy: Copy the current line.
y: Copy selected text (use with Visual Mode).
dd: Cut the current line.
d: Cut selected text (use with Visual Mode).
p: Paste after the cursor.
P: Paste before the cursor.

6. Search
/text: Search for text forward in the file.
?text: Search for text backward in the file.
n: Repeat the last search forward.
N: Repeat the last search backward.

7. Replace
:s/old/new/: Replace the first occurrence of old with new in the current line.
:s/old/new/g: Replace all occurrences of old with new in the current line.

8. Indentation
>>: Indent the current line to the right.
<<: Indent the current line to the left.
=: Auto-indent the current line.

9. Visual Mode
v: Enter Visual Mode (character selection).
V: Enter Visual Line Mode.
Ctrl-v: Enter Visual Block Mode.

10. Exiting Visual Mode
Press Esc: Return to Normal Mode.