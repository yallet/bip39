# BIP39 Tool - iOS Yallet edition

A tool for converting BIP39 mnemonic phrases to addresses and private keys.   

**⚠️ ⚠ ️⚠️ WARNING: this tool will only work for wallets created with Yallet on iOS. ⚠️ ⚠️ ⚠️**

## Standalone offline version

Download `bip39-standalone.html`

Open the file in a browser by double clicking it.

This can be compiled from source using the command `python compile.py`

## Usage

Enter your BIP39 phrase into the 'BIP39 Phrase' field

## Donations

Since this project is the efforts of many people, most of which don't appear in
the obvious places like code or issues, donating to the project itself causes
significant operational difficulties.

As a result, if you would like to support this project financially you are
encouraged to donate to one of the many groups that makes the internet a place
amenable to projects such as this one.

[Donation-accepting organizations and projects](https://en.bitcoin.it/wiki/Donation-accepting_organizations_and_projects)

If the list is too difficult to choose from, the EFF is a good choice.

[Electronic Frontier Foundation](https://supporters.eff.org/donate)

or for a direct bitcoin address, consider donating to the
[Free Software Foundation](https://www.fsf.org/about/ways-to-donate/)
at 1PC9aZC4hNX2rmmrt7uHTfYAS3hRbph4UN

![alt text](https://static.fsf.org/nosvn/images/bitcoin_qrcodes/fsf.png "FSF Bitcoin Address")

## Making changes

Please do not make modifications to `bip39-standalone.html`, since they will
be overwritten by `compile.py`.

Make changes in `src/*`.

Changes are applied during release using the command `python compile.py`, so
please do not commit changes to `bip39-standalone.html`

# Tests

Tests depend on [phantomjs](http://phantomjs.org/).

Run tests from the command-line

```
$ phantomjs tests.js
```

# License

This BIP39 tool is released under the terms of the MIT license. See LICENSE for
more information or see https://opensource.org/licenses/MIT.
