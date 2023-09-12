# Introduction to Markdown

Markdown is a language used to create formatted text typically used for creating documentation.

## Basic commands and syntax

### Headings
Headings are created by adding a # symbol to the beginning of the line containing the heading. The number of #'s that are used determines the size of the heading. One to six # can be used.

!!! tip "Format"
	 # The largest heading <br />
	 ## The second largest <br />
	 ###### The smallest <br />

!!! success "Result"
	# The largest heading
	## The second largest
	###### The smallest

### Styling text
A variety of different styles can be used to place emphasis: bold, italic, or strikethrough.

| Style | Syntax | Example | Output |
| ----- | ------ | ------- | ------ |
| Italic | ` * * ` or `_ _`| `_Italicised text_` | _Italicised text_ |
| Bold | ` ** **` or `__ __ `| `**Bold text**` | **Bold text**|
| Bold and italic | ` *** ***` or `___ ___ `| `***Bold and italic text***` | ***Bold and italic text***|
| Strikethrough | ` ~~ ~~` | `~~Scratch this~~` | ~~Scratch this~~ |

### Quoting
#### Code quoting
Code can be quoted within a sentence using a single backtick `.

!!! tip "Format"
	Use \`git status\` to list all new or modified files that haven't been committed yet.

!!! success "Result"
	Use `git status` to list all new or modified files that haven't been committed yet.

Or to format code into its own distinct block, use triple backtick `.

!!! tip "Format"
	Basic Git commands are: <br />
	\`\`\` <br />
	git status <br />
	git add <br />
	git commit <br />
	\`\`\`

!!! success "Result"
	Basic Git commands are:
	```
	git status
	git add
	git commit
	```

#### Text quoting
Text can be quoted with a `>`.
!!! tip "Format"
	This is NOT a quote.
	
	\> This IS a quote.
!!! success "Result"
	This is NOT a quote.
	
	> This IS a quote.

### Links
#### URL links
An inline link can be created by wrapping the link text in `[ ]`, and then wrapping the URL in `( )`.

!!! tip "Format"
	You can find the CHIME/FRB GitHub page \[here]\(https://github.com/CHIMEFRB)

!!! success "Result"
	You can find the CHIME/FRB GitHub page [here](https://github.com/CHIMEFRB)

#### Section links
You can also link to a section within your `.md` file by preceding the section title in lower case with a hash `#`.

!!! tip "Format"
	Here is the section on \[Quoting]\(#quoting).

!!! success "Result"
	Here is the section on [Quoting](#quoting).

#### Relative links
You can define relative links and image paths to other files in your repository. Relative links are easier for users who clone your repository - relative links are recommended for referring to other files in your repository as absolute links may be broken in clones of the repository.


#### Image links
To include an image in your `.md` file the same syntax as a URL link is used, however the brackets are proceded by an exclamation mark `!`.

!!! tip "Format"
	!\[Photo of the main CHIME telescope]\(https://chime-experiment.ca/images/gallery/Full-chime-2_nearlycomplete.jpg)

!!! success "Result"

	![Photo of the main CHIME telescope](https://chime-experiment.ca/images/gallery/Full-chime-2_nearlycomplete.jpg){ loading=lazy }

### Lists
You can create an unordered list by preceding one or more lines of text with `-` or `*`.

!!! tip "Format"
	\- Ice cream <br/>
	\- Doughnuts <br/>
	\- Gateau <br/>

!!! success "Result"
	- Ice cream
	- Doughnuts
	- Gateau

Or to order the list, precede each line with a number.

!!! tip "Format"
	1. Ice cream <br/>
	2. Doughnuts <br/>
	3. Gateau <br/>

!!! success "Result"
	1. Ice cream
	2. Doughnuts
	3. Gateau

## Further reading
After reading this `.md` you should have enough basic commands under your belt to start writing documentation with Markdown. However, there is more to Markdown that you can learn, a good starting point is [GitHub - Get started / Basic formatting syntax](https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax).
