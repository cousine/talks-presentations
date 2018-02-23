This repository contains slides for any talks and/or presentations by Omar Mekky
([cousine](https://github.com/cousine)).

# License

This work is licensed under the Creative Commons Attribution 4.0 International 
License. To view a copy of this license, visit 
[Creative Commons Attribution 4.0 International License](http://creativecommons.org/licenses/by/4.0/)
or send a letter to Creative Commons, PO Box 1866, Mountain View, CA 94042, USA.

[![Creative Commons License](https://i.creativecommons.org/l/by/4.0/88x31.png)](http://creativecommons.org/licenses/by/4.0/)

# Installation

Unless stated otherwise, all slides use the [Go Present](https://godoc.org/golang.org/x/tools/present) 
tool, to install you first need to have a properly configured [Go](https://golang.org/)
installation on your machine.

Once you have [Go](https://golang.org/) installed, install [Present](https://godoc.org/golang.org/x/tools/present)
using the following command:

```
$ go get -u golang.org/x/tools/present
```

This will clone the present tool source code to `$GOPATH/src/` and build the
`present` executable and place it in `$GOPATH/bin/`.

# Usage

To view any presentation, just navigate to the topic folder and run:

```
$ present
```

This should start an http server where you can navigate the available slides in
the topic folder.

# Talks and Presentations

## Rails

* [Refactoring Fat Models With Service Layers](rails/refactoring_fat_models_with_service_layers)

