The following tool creates a C# shellcode runner that attempts basic heuristic avoidance and is caesar ciphered. 

## Installation:

For the added functionality of compiling the payload, you will need to install mono

`sudo pacman -S mono`

note: if you don't want to install mono, simply comment out the last line of csrunner.sh

## Usage

simply give it a port, or it will default to 443

./csrunner.sh \<port\>



TODO:

- Support other payloads.
- Combine with other similar tools.
