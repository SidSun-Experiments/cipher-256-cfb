## cipher-256-cfb

### cipher-256-cfb is a CLI program which implements the AES & finalists: Serpent, TwoFish along with SeaLion, Seaturtle Block Ciphers in CFB (cipher feedback) mode with 256-Bit key length, using SHA3-256 with files.

## Usage:

```
To encrypt: cipher-256-cfb (--aes/ --twofish / --serpent / --sealion / --seaturtle) (--encrypt / -e) <input file> <passphrase file> <output file (optional)>

To decrypt: cipher-256-cfb (--aes/ --twofish / --serpent / --sealion / --seaturtle) (--decrypt / -d) <encrypted input> <passphrase file> <output file (optional)>

To get version number: cipher-256-cfb (--version / -v)

To get help: cipher-256-cfb(--help / -h)
```

## Installation:

### Build:

```
go mod download
go build .
```
