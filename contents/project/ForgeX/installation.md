---
hide:
  - toc
---
Go-ForgeX provides a convenient CLI tool to effortlessly set up your Go projects. Follow the steps below to install the tool on your system.

## Binary Installation

To install the Go-ForgeX CLI tool as a binary, Run the following command:

```sh
go install github.com/melkeydev/forgex@latest
```

This command installs the Go-ForgeX binary, automatically binding it to your `$GOPATH`.


## Building and Installing from Source

If you prefer to build and install Go-ForgeX directly from the source code, you can follow these steps:

Clone the Go-ForgeX repository from GitHub:

```sh
git clone https://github.com/melkeydev/forgex
```
   
Build the Go-ForgeX binary:

```sh
go build
```
Install in your `$PATH` to make it accessible system-wide:

```sh
go install
```

Verify the installation by running:

```sh
go-ForgeX version
```

This should display the version information of the installed Go-ForgeX.

Now you have successfully built and installed Go-ForgeX from the source code.
