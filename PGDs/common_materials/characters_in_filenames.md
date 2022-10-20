# Characters to Avoid in Directories and Filenames

- see also [this post](https://unix.stackexchange.com/questions/269093/characters-best-avoided-in-filenames-when-used-in-bash-e-g)

Your web files will be viewed by numerous users who use a wide variety of operating systems
(Mac, PC, and Linux for instance) and devices (desktops, tablets, and smartphones are some examples).
Therefore, it is essential to play it safe and avoid common illegal directory and filename characters.


Naming conventions are important in web folders as well as for downloadable files such as PDFS, Word documents, and Excel spreadsheets.


Do not use any of these common illegal characters/symbols:


- `#` pound	< left angle bracket
- `$` dollar sign
- `+` plus sign
- `%` percent
- `>` right angle bracket
- `!` exclamation point
- `` ` `` backtick 
- `&` ampersand
- `*` asterisk
- `'` single quotes
- `|` pipe
- `{` left bracket
- `?` question mark	
- `"` double quotes
- `=` equal sign
- `}` right bracket
- `/` forward slash
- `:` colon	 
- `\` back slash
- ` ` blank spaces
- `@` at sign	 

Also, keep these rules in mind.

- Don’t start or end your filename with a space, period, hyphen, or underline.
- Keep your filenames to a reasonable length and be sure they are under 31 characters.
- Most operating systems are case sensitive; always use lowercase.
- Avoid using spaces and underscores; use a hyphen instead.

**Bad filenames:     -->     Web Browsers see:**
```
F&A Costs.html   -->   F&amp;A%20Costs.html

my PDF file#name.pdf  -->  my%20PDF%20file%23name.pdf
```
**Good filenames:**

fa-costs/index.html

my-pdf-file-name.pdf

Note: This list is not exhaustive. It is meant to help you avoid common errors in filenames.
