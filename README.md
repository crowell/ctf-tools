# ctf-tools

This is a collection of setup scripts to create an install of various security research tools.
Of course, this isn't a hard problem, but it's really nice to have them in one place that's easily deployable to new machines and so forth.

Installers for the following tools are included:

| Category | Tool | Description |
|----------|------|-------------|
| binary | [afl](http://lcamtuf.coredump.cx/afl/) | State-of-the-art fuzzer. | <!--tool-->
| binary | [barf](https://github.com/programa-stic/barf-project) | Binary Analysis and Reverse-engineering Framework. | <!--tool-->
| binary | [bindead](https://bitbucket.org/mihaila/bindead/wiki/Home) | A static analysis tool for binaries. | <!--tool-->
| binary | [checksec](https://github.com/slimm609/checksec.sh) | Check binary hardening settings. | <!--tool-->
| binary | [codereason](https://github.com/trailofbits/codereason) | Semantic Binary Code Analysis Framework. | <!--tool-->
| binary | [crosstool-ng](http://crosstool-ng.org/) | Cross-compilers and cross-architecture tools. | <!--tool-->
| binary | [evilize](http://www.mathstat.dal.ca/~selinger/md5collision/) | Tool to create MD5 colliding binaries | <!--tool-->
| binary | [gdb](http://www.gnu.org/software/gdb/) | Up-to-date gdb with python2 bindings. | <!--tool-->
| binary | [peda](https://github.com/longld/peda) | Enhanced environment for gdb. | <!--tool-->
| binary | [preeny](https://github.com/zardus/preeny) | A collection of helpful preloads (compiled for many architectures!). | <!--tool-->
| binary | [villoc](https://github.com/wapiflapi/villoc) | Visualization of heap operations. | <!--tool-->
| binary | [qemu](http://qemu.org) | Latest version of qemu! | <!--tool-->
| binary | [pathgrind](https://github.com/codelion/pathgrind) | Path-based, symbolically-assisted fuzzer. | <!--tool-->
| binary | [virtualsocket](https://github.com/antoniobianchi333/virtualsocket) | A nice library to interact with binaries. | <!--tool-->
| binary | [pwntools](https://github.com/Gallopsled/pwntools) | Useful CTF utilities. | <!--tool-->
| binary | [python-pin](https://github.com/blankwall/Python_Pin) | Python bindings for pin. | <!--tool-->
| binary | [radare2](http://www.radare.org/) | Some crazy thing crowell likes. | <!--tool-->
| binary | [shellnoob](https://github.com/reyammer/shellnoob) | Shellcode writing helper. | <!--tool-->
| binary | [taintgrind](https://github.com/wmkhoo/taintgrind) | A valgrind taint analysis tool. | <!--tool-->
| binary | [qira](http://qira.me) | Parallel, timeless debugger. | <!--tool-->
| binary | [xrop](https://github.com/acama/xrop) | Gadget finder. | <!--tool-->
| binary | [rp++](https://github.com/0vercl0k/rp) | Another gadget finder. | <!--tool-->
| forensics | [binwalk](https://github.com/devttys0/binwalk.git) | Firmware (and arbitrary file) analysis tool. | <!--tool-->
| forensics | [dislocker](http://www.hsc.fr/ressources/outils/dislocker/) | Tool for reading Bitlocker encrypted partitions. | <!--tool-->
| forensics | [exetractor](https://github.com/kholia/exetractor-clone) | Unpacker for packed Python executables. Supports PyInstaller and py2exe. | <!--tool-->
| forensics | [firmware-mod-kit](https://code.google.com/p/firmware-mod-kit/) | Tools for firmware packing/unpacking. | <!--tool-->
| forensics | [testdisk](http://www.cgsecurity.org/wiki/TestDisk) | Testdisk and photorec for file recovery. | <!--tool-->
| forensics | [pdf-parser](http://blog.didierstevens.com/programs/pdf-tools/) | Tool for digging in PDF files | <!--tool-->
| forensics | [scrdec](https://gist.github.com/bcse/1834878) | A decoder for encoded Windows Scripts. | <!--tool-->
| crypto | [cribdrag](https://github.com/SpiderLabs/cribdrag) | Interactive crib dragging tool (for crypto). | <!--tool-->
| crypto | [foresight](https://github.com/ALSchwalm/foresight) | A tool for predicting the output of random number generators. To run, launch "foresee". | <!--tool-->
| crypto | [hashpump](https://github.com/bwall/HashPump) | A tool for performing hash length extension attaacks. | <!--tool-->
| crypto | [hashpump-partialhash](https://github.com/mheistermann/HashPump-partialhash) | Hashpump, supporting partially-unknown hashes. | <!--tool-->
| crypto | [hash-identifier](https://code.google.com/p/hash-identifier/source/checkout) | Simple hash algorithm identifier. | <!--tool-->
| crypto | [littleblackbox](https://github.com/devttys0/littleblackbox) | Database of private SSL/SSH keys for embedded devices. | <!--tool-->
| crypto | [pemcrack](https://github.com/robertdavidgraham/pemcrack) | SSL PEM file cracker. | <!--tool-->
| crypto | [reveng](http://reveng.sourceforge.net/) | CRC finder. | <!--tool-->
| crypto | [ssh_decoder](https://github.com/jjyg/ssh_decoder) | A tool for decoding ssh traffic. You will need `ruby1.8` from `https://launchpad.net/~brightbox/+archive/ubuntu/ruby-ng` to run this. Run with `ssh_decoder --help` for help, as running it with no arguments causes it to crash. | <!--tool-->
| crypto | [sslsplit](https://github.com/droe/sslsplit) | SSL/TLS MITM. | <!--tool-->
| crypto | [python-paddingoracle](https://github.com/mwielgoszewski/python-paddingoracle) | Padding oracle attack automation. | <!--tool-->
| crypto | [xortool](https://github.com/hellman/xortool) | XOR analysis tool. | <!--tool-->
| crypto | [yafu](http://sourceforge.net/projects/yafu/) | Automated integer factorization. | <!--tool-->
| web | [burpsuite](http://portswigger.net/burp) | Web proxy to do naughty web stuff. | <!--tool-->
| web | [commix](https://github.com/stasinopoulos/commix) | Command injection and exploitation tool. | <!--tool-->
| web | [dirs3arch](https://github.com/maurosoria/dirs3arch) | Web path scanner. | <!--tool-->
| web | [sqlmap](http://sqlmap.org/) | SQL injection automation engine. | <!--tool-->
| web | [subbrute](https://github.com/TheRook/subbrute) | A DNS meta-query spider that enumerates DNS records, and subdomains. | <!--tool-->
| stego | [sound-visualizer](http://www.sonicvisualiser.org/) | Audio file visualization. | <!--tool-->
| stego | [stegdetect](http://www.outguess.org/) | Steganography detection/breaking tool. | <!--tool-->
| stego | [steganabara](http://www.caesum.com/handbook/stego.htm) | Antoher image steganography solver. | <!--tool-->
| stego | [stegsolve](http://www.caesum.com/handbook/stego.htm) | Image steganography solver. | <!--tool-->
| android | [APKTool](https://ibotpeaches.github.io/Apktool/) | Dissect, dis-assemble, and re-pack Android APKs | <!--tool-->

There are also some installers for non-CTF stuff to break the monotony!

| Category | Tool | Description |
|----------|------|-------------|
| game | [Dwarf Fortress](http://www.bay12games.com/dwarves/) | Something to help you relax after a CTF! | <!--tool-->

## Usage

To use, do:

```bash
# set up the path
/path/to/ctf-tools/bin/manage-tools setup
source ~/.bashrc

# list the available tools
manage-tools list

# install gdb, allowing it to try to sudo install dependencies
manage-tools -s install gdb

# install pwntools, but don't let it sudo install dependencies
manage-tools install pwntools

# uninstall gdb
manage-tools uninstall gdb

# uninstall all tools
manage-tools uninstall all

# search for a tool
manage-tools search preload
```

Where possible, the tools keep the installs very self-contained (i.e., in to tool/ directory), and most uninstalls are just calls to `git clean` (**NOTE**, this is **NOT** careful; everything under the tool directory, including whatever you were working on, is blown away during an uninstall).
To support python dependencies, however, make sure to create a virtualenv before installing and using tools (i.e., `mkvirtualenv ctf`).

## Adding Tools

To add a tool (say, named *toolname*), do the following:

1. Create a `toolname` directory.
2. Create an `install` script.
3. (optional) if special uninstall steps are reuired, create an `uninstall` script.

### Install Scripts

The install script will be run with `$PWD` being `toolname`. It should install the tool into this directory, in as contained a manner as possible.
Ideally, full uninstallation should be possible with a `git clean`.

The install script should create a `bin` directory and put its executables there.
These executables will be automatically linked into the main `bin` directory for the repo.
They could be launched from any directory, so don't make assumptions about the location of `$0`!

## License

The individual tools are all licensed under their own licenses.
As for ctf-tools itself, it is "starware".
If you find it useful, star it on github (https://github.com/zardus/ctf-tools).

Good luck!

# See Also

There's a curated list of CTF tools, but without installers, here: https://github.com/apsdehal/awesome-ctf.
