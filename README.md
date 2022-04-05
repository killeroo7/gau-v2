# gf-007
## [GF](https://github.com/tomnomnom/gf) By [![Twitter](https://img.shields.io/badge/twitter-@TomNomNom-blue.svg)](https://twitter.com/TomNomNom) 
Automates the process of gf tool written by [tomnomnom](https://github.com/tomnomnom)

## Prerequsites
* [Gf Tool](https://github.com/tomnomnom/gf) by [Tomnomnom](https://github.com/tomnomnom/)
* [Gf-Patterns](https://github.com/1ndianl33t/Gf-Patterns/) by [1ndianl33t](https://github.com/1ndianl33t/) [Optional]

## Installation
```
▶ pip3 install termcolor
▶ git clone https://github.com/killeroo7/gf-007.git
▶ cd gf-007 && chmod +x gf-007.py
▶ ln -s $PWD/urls-007.py /usr/local/bin/gf-007 [Add the file to the path environment]
```

## Description
* The tool runs gf on each file in the directory recursively for each pattern.
* It creates a separate text file for each pattern found.
* Summary.txt --> Patterns pointing to file where the pattern was found. 
* Log.txt     --> Has the count on the number of patterns found.

## Usage
```
▶ gf-007 --> Runs gf in the current directory and stores the output in gf-results folder
```

## FLAGS [YET TO BE ADDED]
```
-a --all-files --> Run Gf on js,html,etc files
-u --url-files --> Run Gf on Files having URLs [Ex: -u gau.txt,file2]")
-s --silent    --> Does not print the output on the terminal [YetToAdd]
-w --whitelist --> Run Gf only on these extensions(Ex: js,html,txt) [YetToAdd]
-b --blacklist --> Exclude gf on these file extensions(php,html) [YetToAdd]

```

## CREDITS

* GF by [Tomnomnom](https://github.com/tomnomnom)

* Gf-Patterns by [1ndianl33t](https://github.com/1ndianl33t)

## Follow
**Twitter** --> [Killer007](https://twitter.com/killer007p)

## Support

[![Donate](https://img.shields.io/badge/Donate-PayPal-green.svg)](https://paypal.me/pkiller007)

<a href="https://www.buymeacoffee.com/killer007" target="_blank"><img src="https://cdn.buymeacoffee.com/buttons/v2/default-yellow.png" alt="Buy Me A Coffee" style="height: 10px !important;width: 20px !important;" ></a>
