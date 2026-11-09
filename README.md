# morphicgames-maps

Content repository for the **Morphic Games** Paper plugin.

The plugin downloads this repository's files when it loads on a server: only new or changed files are fetched,
each one is checked against its hash, and the cached copy is used when the server is offline.

All content is encrypted:
- `manifest.json` names the current index.
- `index.mgx` is the encrypted file index.
- `blobs/` holds the encrypted content, one file per hash.

The files are not meant to be read or edited by hand.
