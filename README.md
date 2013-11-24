# mixcast

Command line podcast mixing tool

Uses `sox` and `id3v2` to mix, create mp3 and inject data

* Inputs:

- A description file, containing

  - A list of tracks
  - an outro with start-offset

  - mp3 tags

  - title

  - description


* Outputs:

- an .mp3

- uploads the mp3 to libsyn over sftp (use keyring to store login
  info?)

