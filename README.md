# Freesound API

A set of abstractions for accessing the [Freesound](http://www.freesound.org/) API from within Pure Data.

Revised 2019 so that only dependencies are `purest_json` and `ggee/getdir` (for `ggee/getdir`) both available via `deken`, Pure Data's package manager.

## Abstractions

[fs_download](fs_download.pd)	Download sound from [Freesound](http://www.freesound.org/)
[fs_query](fs_query.pd)	Query sound from [Freesound](http://www.freesound.org/)
[fs_display](fs_display.pd)	Display data from a sound entry
[fs_tokens](fs_tokens.pd)	Load json files with client and access tokens.


## Script

[auth](auth)	Script to get access code, tokens and to refresh token from [Freesound](http://www.freesound.org/)
