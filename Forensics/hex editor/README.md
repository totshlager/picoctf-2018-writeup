# hex editor
Points: 150

## Category
Forensics

## Question
>This [cat](files/hex_editor.jpg) has a secret to teach you. You can also find the file in /problems/hex-editor_2_c1a99aee8d919f6e42697662d798f0ff on the shell server. 

### Hint
>What is a hex editor?
>
>Maybe google knows.
>
>[xxd](http://linuxcommand.org/man_pages/xxd1.html)
>
>[hexedit](http://linuxcommand.org/man_pages/hexedit1.html)
>
>[bvi](http://manpages.ubuntu.com/manpages/natty/man1/bvi.1.html)

## Solution
strings hex_editor.jpg shows the flag at the bottom.
xxd hex_editor.jpg also shows the same in ASCII but also a hex dump.
Need to include the quotes with this flag for some reason.

### Flag
"picoCTF{and_thats_how_u_edit_hex_kittos_dF817ec5}"

