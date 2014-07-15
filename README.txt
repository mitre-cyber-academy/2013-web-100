Name: Truth in Fandom

Description: One of your friends, a hardcore Star Wars fan, told you to check
out his site <link>. He said he's got the scoop on the new movie. Maybe you can
find some truth in his website after all.

How to Solve: The first thing to note is the modified image at the bottom,
telling the participant to check out the source code. Going to the top, there
are two CSS files imported. One of them (color.css) contains four definitions
of ID elements. Each one has some kind of color information and each one is
labeled with 'M', 'C', 'A', or '-'. By concatenating the color information in
each tag, the flag can be found.

What to distribute: Just the link to the web page should be given out.

What not to distribute: The code for the page and the site in general can be
found in src/. The file src/challenge_server.py should be run. It uses
standalone Bottle to work.  Update the static directory path in
challenge_server.py

Flag: MCA-57412B01
