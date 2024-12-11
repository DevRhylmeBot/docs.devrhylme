---
hide:
  - toc
---
ForgeX provides a convenient CLI tool to effortlessly set up your  projects. Follow the steps below to install the tool on your system.

## Binary Installation

To install the ForgeX CLI tool as a binary, Run the following command:

```sh
 install github.com/melkeydev/forgex@latest
```

This command installs the ForgeX binary, automatically binding it to your `$PATH`.


## Building and Installing from Source

If you prefer to build and install ForgeX directly from the source code, you can follow these steps:

Clone the ForgeX repository from GitHub:

```sh
git clone https://github.com/melkeydev/forgex
```
   
Build the ForgeX binary:

```sh
 build
```
Install in your `$PATH` to make it accessible system-wide:

```sh
 install
```

Verify the installation by running:

```sh
ForgeX version
```

This should display the version information of the installed ForgeX.

Now you have successfully built and installed ForgeX from the source code.
