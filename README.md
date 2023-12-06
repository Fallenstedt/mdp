# Markdown Preview

Converts markdown to HTML, and then opens it in a browser. 

## Running locally

1. Cone repo
2. `go build`
3. `mdp -file README.md`

A browser will open with the generated HTML. The temporary file is removed too.

## Installing

After building the project

1. Copy the binary file to `/usr/local/bin`. `cp ./mdp /usr/local/bin/mdp`
2. Execute the application from anywhere `mdp`
