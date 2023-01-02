```
 ___ __ __   ________   ______    _______    ______
/__//_//_/\ /_______/\ /_____/\  /______/\  /_____/\
\::\| \| \ \\::: _  \ \\:::_ \ \ \::::__\/__\::::_\/_
 \:.      \ \\::(_)  \ \\:(_) ) )_\:\ /____/\\:\/___/\
  \:.\-/\  \ \\:: __  \ \\: __ `\ \\:\\_  _\/ \_::._\:\
   \. \  \  \ \\:.\ \  \ \\ \ `\ \ \\:\_\ \ \   /____\:\
    \__\/ \__\/ \__\/\__\/ \_\/ \_\/ \_____\/   \_____\/
```

# margs

Madlib Argument Parser

## Running Locally

### Running Locally with Node

For node:
```shell
madlib compile -i src/Main.mad
```
Then, you can run it like this:
```shell
node build/Main.mjs
```

Or as a single step you can:
```shell
madlib run src/Main.mad
```

### Running Locally as a native binary

As a native binary:
```shell
madlib compile --target llvm -i src/Main.mad -o ./build/marge
```
Then, you can run it like this:
```shell
./build/marge
```
