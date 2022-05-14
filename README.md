# Candy-Crush-In-Assembly
Candy Crush is a classic hit game where your goal is to match candies of same colour to score points.

For my Assembly language course, I decided, alongside my fellow programming [Fahad Waseem](https://github.com/Fahadw9), to recreate this game in assembly language so that we can have a better understanding of graphics processing and register handling in assembly language.

# Setting-up-an-emulator
This game was developed in DOSBox, an x86 emulator with DOS so head on over to https://www.dosbox.com/download.php?main=1 to download the emulator or run any other x86 dos emulator.

# Compiling-and-executing
Firsty download the .asm file provided and open up the dosbox terminal.
Then copy the commands and replace the paranthesis {} with your file path

```bash
mount c: {path to your file}
```

```bash
nasm main.asm -o main.com
```

```bash
main.com
```

Congratulations now you are (hopefully) on the intro screen of the game.
