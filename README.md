shiny-thing
===========

shiny-thing is just me playing with Go packages in a repo.

TODO: Show how to put a program (with main) in this repo


Assumming we have src, pkg and bin directories under our GOPATH

How to fetch packages from a git hub repo

    $ go get github.com/ZiCog/shiny-thing/foo
    $ go get github.com/ZiCog/shiny-thing/bar

Note: the above will pcome the package names
Note: if get fails then "rm -rf mygo/src/github.com/ZiCog/shiny-thing"
and try again.


How to build Go packages

    $ go build github.com/ZiCog/shiny-thing/foo
    $ go build github.com/ZiCog/shiny-thing/bar

How to install Go packages (under pkg)

   $ go install  github.com/ZiCog/shiny-thing/bar 
   $ go install  github.com/ZiCog/shiny-thing/foo

How to build a Go program (Something with main in it)

    $ go build myprog

How to install the program (under src)

    $ go install myprog

Or you can just run it

    $ go run myprog
