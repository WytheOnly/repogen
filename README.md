repogen
===============

_Version 0.1_

__repogen__ is a toy to generate a Markdown index document of GitHub user's starred repositories. 

# Install

Go 1.1+ is required. [Golang Getting Started](http://golang.org/doc/install)

```
$ go get -u github.com/skyjia/repogen

```

Exuecte it:

```
$ repogen -u USERNAME
```

Which takes the following flags:

- __-u:__ This the GitHub username of which starred repositories you want to generate. (Required)

Output to a Markdown document:
```
$ repogen -u USERNAME > /path/to/your/document.md
```

[Example](example/skyjia_index.md)
