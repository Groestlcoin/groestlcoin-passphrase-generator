# Groestlcoin Random Word Passphrase Generator
This script can be used to generate random passphrase words for groestlcoin wallets.

## Prerequisites
The **Groestlcoin Random Word Passphrase Generator** script requires **/usr/share/dict/words** wordlist file available on your system. Before using this script install wordlist from a standard repository of your Linux distribution.
```
UBUNTU / DEBIAN
# apt install wamerican-small

CENTOS / REDHAT:
# yum install words

FEDORA:
# dnf install words

ARCH LINUX:
# pacman -S words
```

## Usage
**groestlcoin-passphrase-generator.sh** script requires a single argument to determine the number of random words to be generated

### Example
Generate 24 random keywords:
```
$ ./groestlcoin-passphrase-generator.sh 24
Generating a random word list from 62887 words:
departures inebriated pecans riddles totter suspender grannie cures preachier refulgent uselessly crumpet swab plainclothesmen agendas calisthenic smothering enclosure pathetic skylarked whined clacks encores slogan
```
Generate 10 random keyword:
```
$ ./groestlcoin-passphrase-generator.sh 10
Generating a random word list from 62887 words:
exigencies marchers sublet splicers transcends handling uninformative plowmen lumpiness diuretic
```
