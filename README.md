# Favorite poems
This repo holds some of our favorite poems.  
The structure of the repo is a work in progress.

Here's a style guide for poems:  
- Poems are generally stored in .txt files. (If the layout of the poem on the page is important and not easily representable in a basic text file, it can be stored as a pdf. Looking at e e cummings. The next style guide rules won't apply in that case.)
- The title of the file should be the last name of the author followed by the name of the poem in snake_case.
- The first line of the file should be a list of tags. This will take the form `TAGS: tag1 tag2 tag3`, space separated. Each tag is a single identifier with no spaces. Use snake_case.
- The second line should be the title of the poem. Titles should stay on a single line (no newline characters).
- The third line should be the name of the author, in Title Case or usual styling (Looking at e e cummings again.) If anonymous, this line should contain `Anonymous`.
- The fourth line should be the the birth and death years of the author. This should take the form `YYYY - YYYY` or `b. YYYY` if the author is living. If the author's birth or death year is only approximate, write e.g. `c. YYYY - YYYY` or `c. YYYY - c. YYYY`.
- Follow this with two blank lines and then the text of the poem.
- Do not end files with a newline.