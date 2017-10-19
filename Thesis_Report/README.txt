These files are for preparing a doctoral thesis at the University of Melbourne.

The file thesis-master.tex assembles the complete dissertation; this is the file
you should compile.

Each chapter should be written in a new file (e.g., chapter-x.tex), and if you
would like to organise the thesis into 'parts', you should create a new file
for each part (copy from the example: part-1.tex) and add it to thesis-master.tex.

A convenience master (chapter-master.tex) is also available for easily compiling
a single chapter. Modify this to include the chapter(s) you wish to compile.

A script is also included for counting the number of words that count 
towards the total. It requires perl.
>./wordcount

To exclude parts of the main text which should not be counted (e.g., tables) use
%TC:ignore and %TC:endignore.

Good luck!
