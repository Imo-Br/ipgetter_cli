## IPGetter CLI

This is just a cli (command line interface) version of the [IPGetter](https://github.com/Imo-Br/ipgetter) project I made

To build it make sure you have [rust](https://www.rust-lang.org/tools/install) installed

### Manually build and run with cargo

To build it all you need to is run

```sh
$ cargo build --release
```

You should find the binary executable, in your target/release\
To use it first navigate to the same directory as the executable\
For linux and macos run the following command

```sh
$ ./ipgetter_cli <ip>
```

For windows run

```
> ipgetter_cli.exe <ip>
```

You can also optionally add it to your path, to do so  
First of all navigate to the directory containing to the directory containing the repo

#### For linux

Add the following line to your ~/.bashrc file, to include the binary in your PATH:

```sh
export PATH="$PATH:./target/release/ipgetter_cli"
```

#### For macos

Add the same line to your ~/.zshrc

#### For windows

Run the following command

```
setx PATH "%PATH%;./target/release/ipgetter_cli.exe"
```
