# Bash Morse Code Translator

This script translates the Morse Code file to a text file and conversely. It allows translating in both directions. The script also has a few other options, like displaying an audio version of the given code or saving the Morse Alphabet to a specific file.


## Available flags:

- **-h** -> help

- **-s FILE** -> emits an audio version of the Morse Code given in the FILE

- **--alph FILE** -> saves the Morse Alphabet to the given FILE

- **--totext FILE1 FILE2** -> reads the Morse Code from FILE1 and saves its translated version to FILE2

- **--tomorse FILE1 FILE2** -> the reverse of --totext flag, translates text file FILE1 to the Morse Code and saves the result to FILE2


## Requirements

To use the -s flag, you need to install morse using following command:
```
sudo apt-get install -y morse
```

## Run script

Examples:
```
./morse -h
```

```
./morse --alph file
```

```
echo "sos help" > text_file
./morse --tomorse text_file file
```

```
./morse -s file
```

```
echo "... --- ..." > morse-file
./morse --totext morse-file file
```

## Examples:

- using -h
![Help](/readme_images/help.jpg =100x20)

- using -s
![Sound](/readme_images/sound.jpg =100x20)

- using --alph
![Alphabet](/readme_images/alphabet.jpg =100x20)

- using --tomorse
![Morse](/readme_images/tomorse.jpg =100x20)

- using --totext
![Text](/readme_images/totext.jpg =100x20)

## Built With

-   Bash

## Authors

**Karina Szubert** (https://github.com/Karina-00)

## License

[Mozilla Public License 2.0](https://choosealicense.com/licenses/mpl-2.0/)
