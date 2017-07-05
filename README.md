# Shrinkpack TAR Proof of Concept

This repo is intended to display the use case for offline module caching in the uncompressed tar format as opposed to tgz. Specifically, using tar allows git to detect renames for simple changes, as well as perform far superior delta compression, which reduces repo size and bandwidth considerably.

## Usage

- Fork the repo
- Clone it
- `npm install`
- `npm t`

This will give the diff when upgrading from `react-native` 0.45.0 to 0.46.0. To display delta compression, commit and push.
