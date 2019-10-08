# Visual Editor (VI)

The default editor that comes with the UNIX operating system is called vi (visual editor). The alternate editors for UNIX environments include pico and emacs, a product of GNU.

The UNIX vi editor is a full screen editor and has two modes of operation:

-  Command mode commands which cause action to be taken on the file, and

-  Insert mode in which entered text is inserted into the file.

In the command mode, every character typed is a command that does something to the text file being edited; a character typed in the command mode may even cause the vi editor to enter the insert mode. In the insert mode, every character typed is added to the text in the file; pressing the <Esc> (Escape) key turns off the Insert mode.
  
## To Get Into and Out Of vi

##### To Start vi

To use vi on a file, type in vi filename. If the file named filename exists, then the first page (or screen) of the file will be displayed; if the file does not exist, then an empty file and screen are created into which you may enter text.

vi filename	edit filename starting at line 1

vi -r filename	recover filename that was being edited when system crashed
		
##### To Exit vi

Usually the new or modified file is saved when you leave vi. However, it is also possible to quit vi without saving the file.

The cursor moves to bottom of screen whenever a colon (:) is typed. This type of command is completed by hitting the <Return> (or <Enter>) key.
  
	:x<Return>	quit vi, writing out modified file to file named in original invocation
  
 	:wq<Return>	quit vi, writing out modified file to file named in original invocation
  
 	:q<Return>	quit (or exit) vi
  
	:q!<Return>	quit vi even though latest changes have not been saved for this vi call
		

