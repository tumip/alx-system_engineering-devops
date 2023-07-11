Hello World _ A script that prints Hello, World, followed by a new line to the standard output.
Confused smiley _ A script that displays a confused smiley_ "(Ôo)'.
Let's display a file _ A script that displays the content of the /etc/passwd file.
What about 2? _ A scipt that displays content of /etc/passwd and /etc/hosts.
Last lines of a file _ A script that displays the last 10 lines of /etc/passwd.
I'd prefer the first ones actually _ A scipt that displays the first 10 lines of etc/passwd.
Line #2 _ A script that displays the third line of the file iacta.
The file iacta will be in the working directory and you are not allowed to use sed.
It is a good file that cuts iron without making a noise _ A script that creates a file named exactly \*\\'"Best School"\'\\*$\?\*\*\*\*\*_) containing the text Best School ending by a new line.
For this challenge, remember to use a single backslash \ to escape special characters and double backslash \\ to escape the backslash itself.
Save current state of directory _ A script that writes into the file ls_cwd_content the result of the command ls -la. If the file ls_cwd_content already exists, it should be overwritten. If the file ls_cwd_contentdoes not exist, create it.
Duplicate last line _ A script that duplicates the last line of the file iacta.
No more javascript _ A script that deletes all the regular files (not the directories) with a .js extension that are present in the current directory and all its subfolders.
Don't just count your directories, make your directories count _ A script that counts the number of directories and sub-directories in the current directory.
The current and present directories should not be taken into account.
Hidden directories should be counted.
Solution_ mindepth 1 ; To exclude root directory
Others_ maxdepth 1 ; To avoid parsing sub directories. (you may need this in future.)
Whats12's new _ A script that prints the 10 newest files in the current directory.
The output should be; one file per line and sorted from the newest to the oldest.
Being unique is better than being perfect _ A script that takes a list of words as input and prints only words that appear exactly once.
Input and Output format is; One word per line.
Words should be sorted. (use this list as your input to see if the challenge will work. 😊) cat list | ./13-unique
It must be in that file _ A script that prints lines containing the pattern "root" from the file /etc/passwd.
Count that word _ A script that displays the number of lines that contain the pattern "bin" in the file /etc/passwd.
What's next? _ A script that containing the pattern "root" and 3 lines after them in the file /etc/passwd.
B _ This shows the lines before your pattern match.
A _ This shows the lines after your pattern match.
I hate bins _ A script that displays all the lines in the file /etc/passwd that do not contain the pattern "bin".
Letters only please _ A script that displays all lines of the file /ect/ssh/sshd_config starting with a letter, including capital letters as well.
This also works _ grep ^[[_alpha_]] /etc/ssh/sshd_config
A to Z _ A script that replaces all characters A and C from input to Z and E respectively.
Without C, you would live in hiago _ A script that removes all letters c and C from input.
esreveR _ A script that reverse its input.
DJ Cut Killer _ A scipt that displays all users and their home directories, sorted by users, based on the /etc/passwd file.
Empty casks make the most noise _ A script that finds all empty files and directories in the current directory and all sub-directories.
Only names of the files and directories should be displayed (not the entire path.)
Hidden files should be listed also, one file name per line and the listing should end with a new line.
You are not allowed to use basename, grep, egrep, fgrep or rgrep.
A gif is worth ten thousand words _ A script that lists all the files with a .gif extension in the current directory and all its sub-directories.
Hidden files should be listed.
Only regular files (not directories) should be listed.
The names of the files should be displayed without their extensions.
The files should be sorted by byte values, but case-insensitive (file aaa should be listed before file bbb, file .b should be listed before file a, and file Rona should be listed after file jay)
One file name per line.
The listing should end with a new line.
You are not allowed to use basename, grep, egrep, fgrep or rgrep.
Acrostic _ A script that decodes acrostics that use the first letter of each line.
What to decode_ An acrostic is a poem (or other form of writing) in which the first letter (or syllable, or word) of each line (or paragraph, or other recurring feature in the text) spells out a word, message or the alphabet. The word comes from the French acrostiche from post-classical Latin acrostichis). As a form of constrained writing, an acrostic can be used as a mnemonic device to aid memory retrieval. Read more here
The ‘decoded’ message has to end with a new line.
You are not allowed to use grep, egrep, fgrep or rgrep.
The biggest fan _ A script that parses web servers logs in TSV format as input and displays the 11 hosts or IP addresses which did the most requests.
Download this file_ wget http_//indeedeng.github.io/imhotep/files/nasa_19950801.tsv
Run command this way_ ./103-the_biggest_fan < nasa_19950801.tsv.
Order by number of requests, most active host or IP at the top.
You are not allowed to use grep, egrep, fgrep or rgrep.
