# Go Lang Slides Examples

This repo has a few examples for using [go lang's](https://go.dev/) tool [present](https://pkg.go.dev/golang.org/x/tools/present)

A few things to note about this directory:
- golangbasics.slide is from [Drashti Ved](https://github.com/drashtived03/goslides) repo, along with the assets directory and Golang-Logo.jpg
- the present.slide and legacy.slide is taken from go lang's present tool website and slightly modified
- hello directory has a simple hello world script written in go and this is used in a few of the slide presentations
- slide directory has one more example to show how to override the default stylesheet to modify pagenumber order & colour
  - presenting this directory requires Option 1, see below under **Override Style**

## Installation

To use go lang's present tool you can use either option 1 or 2:
1. install go lang and the necessary tools 
2. use [go-talks.appspot.com](https://go-talks.appspot.com/)

### Option 1

Install a stable version of [go](https://go.dev/dl/) for your operating system.

And follow the [offical installation instructions](https://go.dev/doc/install)

Now you can download and install the present tool in one step

    go install golang.org/x/tools/cmd/present@latest

You can go to your directory with .slide file written in markdown to create a slide deck to showcase go lang

### Option 2

[go-talks.appspot.com](https://go-talks.appspot.com/) site plays slide presentations and articles stored on GitHub in the present format

The syntax for URLs is:

   https://go-talks.appspot.com/github.com/owner/project/file.slide
   https://go-talks.appspot.com/github.com/owner/project/sub/directory/file.slide

The supported file extensions (.ext) are .slide and .article but the .html command is not supported

#### Example

You can present the `present.slide`, from this repo, by pasting the link below into your browser

  https://go-talks.appspot.com/github.com/davidhintelmann/slides/present.slide

or the `golangbasics.slide`

  https://go-talks.appspot.com/github.com/davidhintelmann/slides/golangbasics.slide

## Override Style

Since [go-talks.appspot.com](https://go-talks.appspot.com) can not use .html present command invocations you will have to present the slide directory from a local environment i.e. Option 1 above.