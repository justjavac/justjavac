# justjavac's Deno Modules

[![tag](https://img.shields.io/github/release/justjavac/justjavac)](https://github.com/justjavac/justjavac/releases)
[![Build Status](https://github.com/justjavac/justjavac/workflows/ci/badge.svg?branch=master)](https://github.com/justjavac/justjavac/actions)
[![license](https://img.shields.io/github/license/justjavac/justjavac)](https://github.com/justjavac/justjavac/blob/master/LICENSE)

| Module                           | Description                                                                                                      |
| -------------------------------- | ---------------------------------------------------------------------------------------------------------------- |
| [dvm][dvm]                       | Deno Version Manager - Easy way to manage multiple active deno versions.                                         |
| [ffmpeg][ffmpeg]                 | ffmpeg module for Deno [WASM]                                                                                    |
| [string][string]                 | Deno string utils.                                                                                               |
| [unicode][unicode]               | Unicode lookup table for Deno                                                                                    |
| [starter][starter]               | Deno starter for creating a module                                                                               |
| [semver][semver]                 | The semver parser for Deno (a fork of node-semver using TypeScript)                                              |
| [vendors][vendors]               | List of vendor prefixes known to the web platform                                                                |
| [thanos][thanos]                 | This command could delete a half of your files randomly.                                                         |
| [murmurhash][murmurhash]         | An incremental implementation of MurmurHash3 for JavaScript                                                      |
| [username][username]             | Get the username of the current user                                                                             |
| [slash][slash]                   | Convert Windows backslash paths to slash paths                                                                   |
| [ci][ci]                         | Get environment variables exposed by CI services                                                                 |
| [color_name][color_name]         | A list of color names and its values                                                                             |
| [ieee754][ieee754]               | Parse IEEE754 floating point numbers for Deno                                                                    |
| [build][build]                   | _WIP_                                                                                                            |
| [language][language]             | ISO 639-1 language                                                                                               |
| [cli][cli]                       | _WIP_                                                                                                            |
| [x256][x256]                     | Find the nearest xterm 256 color index for an rgb                                                                |
| [case][case]                     | Convert strings between camelCase, PascalCase, Title Case, snake_case and more                                   |
| [longest][longest]               | Get the length of the longest item in an array.                                                                  |
| [text_indent][text_indent]       | Sets the length of empty space (indentation) that is put before lines of text in a block.                        |
| [word_wrap][word_wrap]           | Wrap words to a specified length.                                                                                |
| [letter_spacing][letter_spacing] | Set the horizontal spacing behavior between text characters.                                                     |
| [is_running][is_running]         | Return true if the given PID is running.                                                                         |
| [num_cpus][num_cpus]             | Get the number of CPUs available on the current system.                                                          |
| [dijkstra][dijkstra]             | A simple JavaScript implementation of Dijkstra's single-source shortest-paths algorithm.                         |
| [module_info][module_info]       | Get module info                                                                                                  |
| [shuffle][shuffle]               | The Fisher-Yates (aka Knuth) shuffle for Deno.                                                                   |
| [tauri][tauri]                   | tauri binding for Deno.                                                                                          |
| [is_git][is_git]                 | Whether the filepath is a git repository.                                                                        |
| [is][is]                         | Detect the running environment and context of the current script                                                 |
| [is_free_port][is_free_port]     | Return true if a port is free.                                                                                   |
| [is_absolute][is_absolute]       | [deprecated] Whether the filepath is a absolute file path.                                                       |
| [is_relative][is_relative]       | Whether the filepath is a relative file path.                                                                    |
| [is_ssh][is_ssh]                 | Whether the process is running inside SSH.                                                                       |
| [is_unc_path][is_unc_path]       | Whether the filepath is a windows UNC file path.                                                                 |
| [hyper][hyper]                   | Fast and safe HTTP for Deno                                                                                      |
| [actix][actix]                   | Actix binding for Deno                                                                                           |
| [latest_version][latest_version] | Get the latest version of Deno module                                                                            |
| [version_info][version_info]     | Get version info of Deno module                                                                                  |
| [ftp][ftp]                       | FTP client for Deno.                                                                                             |
| [wechat][wechat]                 | WeChat API for Deno.                                                                                             |
| [ansi][ansi]                     | ANSI escape codes for manipulating the terminal                                                                  |
| [ctrlc][ctrlc]                   | Cross platform handling of Ctrl-C signals.                                                                       |
| [curl][curl]                     | curl for Deno                                                                                                    |
| [ssh][ssh]                       | Bindings to libssh2 for interacting with SSH servers and executing remote commands, forwarding local ports, etc. |
| [pkg][pkg]                       | _WIP_                                                                                                            |
| [runtime][runtime]               | _WIP_                                                                                                            |
| [getpass][getpass]               | Safely read passwords in a console application on Linux, OSX and Windows                                         |
| [video_dir][video_dir]           | Returns the path to the user's video directory.                                                                  |
| [tmp_dir][tmp_dir]               | Returns the path to the user's tmp directory.                                                                    |
| [template_dir][template_dir]     | Returns the path to the user's template directory.                                                               |
| [public_dir][public_dir]         | Returns the path to the user's public directory.                                                                 |
| [picture_dir][picture_dir]       | Returns the path to the user's picture directory.                                                                |
| [font_dir][font_dir]             | Returns the path to the user's font directory.                                                                   |
| [download_dir][download_dir]     | Returns the path to the user's download directory.                                                               |
| [document_dir][document_dir]     | Returns the path to the user's document directory.                                                               |
| [desktop_dir][desktop_dir]       | Returns the path to the user's desktop directory.                                                                |
| [audio_dir][audio_dir]           | Returns the path to the user's audio directory.                                                                  |
| [executable_dir][executable_dir] | Returns the path to the user's executable directory.                                                             |
| [config_dir][config_dir]         | Returns the path to the user's config directory.                                                                 |
| [cache_dir][cache_dir]           | Returns the path to the user's cache directory.                                                                  |
| [data_local_dir][data_local_dir] | Returns the path to the user's local data directory.                                                             |
| [data_dir][data_dir]             | Returns the path to the user's data directory.                                                                   |
| [password][password]             | _WIP_                                                                                                            |
| [serverless][serverless]         | _WIP_                                                                                                            |
| [machine_id][machine_id]         | Unique machine (desktop) id (no admin privileges required)                                                       |
| [dirs][dirs]                     | Returns the user and platform specific directories                                                               |
| [domain][domain]                 | Get all the top-level domains, including gTLDs such as `.com`, and country-code TLDs such as `.uk`.              |
| [dui][dui]                       | _WIP_                                                                                                            |
| [justjavac][justjavac]           | justjavac's modules                                                                                              |
| [jjc][jjc]                       | justjavac's modules                                                                                              |
| [git][git]                       | libgit2 bindings for Deno                                                                                        |
| [github][github]                 | The GitHub API for Deno                                                                                          |

[dvm]: https://deno.land/x/dvm
[ffmpeg]: https://deno.land/x/ffmpeg
[string]: https://deno.land/x/string
[unicode]: https://deno.land/x/unicode
[starter]: https://deno.land/x/starter
[semver]: https://deno.land/x/semver
[vendors]: https://deno.land/x/vendors
[thanos]: https://deno.land/x/thanos
[murmurhash]: https://deno.land/x/murmurhash
[username]: https://deno.land/x/username
[slash]: https://deno.land/x/slash
[ci]: https://deno.land/x/ci
[color_name]: https://deno.land/x/color_name
[ieee754]: https://deno.land/x/ieee754
[build]: https://deno.land/x/build
[language]: https://deno.land/x/language
[cli]: https://deno.land/x/cli
[x256]: https://deno.land/x/x256
[case]: https://deno.land/x/case
[longest]: https://deno.land/x/longest
[text_indent]: https://deno.land/x/text_indent
[word_wrap]: https://deno.land/x/word_wrap
[letter_spacing]: https://deno.land/x/letter_spacing
[is_running]: https://deno.land/x/is_running
[num_cpus]: https://deno.land/x/num_cpus
[dijkstra]: https://deno.land/x/dijkstra
[module_info]: https://deno.land/x/module_info
[shuffle]: https://deno.land/x/shuffle
[tauri]: https://deno.land/x/tauri
[is_git]: https://deno.land/x/is_git
[is]: https://deno.land/x/is
[is_free_port]: https://deno.land/x/is_free_port
[is_absolute]: https://deno.land/x/is_absolute
[is_relative]: https://deno.land/x/is_relative
[is_ssh]: https://deno.land/x/is_ssh
[is_unc_path]: https://deno.land/x/is_unc_path
[hyper]: https://deno.land/x/hyper
[actix]: https://deno.land/x/actix
[latest_version]: https://deno.land/x/latest_version
[version_info]: https://deno.land/x/version_info
[ftp]: https://deno.land/x/ftp
[wechat]: https://deno.land/x/wechat
[ansi]: https://deno.land/x/ansi
[ctrlc]: https://deno.land/x/ctrlc
[curl]: https://deno.land/x/curl
[ssh]: https://deno.land/x/ssh
[pkg]: https://deno.land/x/pkg
[runtime]: https://deno.land/x/runtime
[getpass]: https://deno.land/x/getpass
[video_dir]: https://deno.land/x/video_dir
[tmp_dir]: https://deno.land/x/tmp_dir
[template_dir]: https://deno.land/x/template_dir
[public_dir]: https://deno.land/x/public_dir
[picture_dir]: https://deno.land/x/picture_dir
[font_dir]: https://deno.land/x/font_dir
[download_dir]: https://deno.land/x/download_dir
[document_dir]: https://deno.land/x/document_dir
[desktop_dir]: https://deno.land/x/desktop_dir
[audio_dir]: https://deno.land/x/audio_dir
[executable_dir]: https://deno.land/x/executable_dir
[config_dir]: https://deno.land/x/config_dir
[cache_dir]: https://deno.land/x/cache_dir
[data_local_dir]: https://deno.land/x/data_local_dir
[data_dir]: https://deno.land/x/data_dir
[password]: https://deno.land/x/password
[serverless]: https://deno.land/x/serverless
[machine_id]: https://deno.land/x/machine_id
[dirs]: https://deno.land/x/dirs
[domain]: https://deno.land/x/domain
[dui]: https://deno.land/x/dui
[justjavac]: https://deno.land/x/justjavac
[jjc]: https://deno.land/x/jjc
[git]: https://deno.land/x/git
[github]: https://deno.land/x/github

### License

[justjavac](https://github.com/justjavac/justjavac) is released under the MIT
License. See the bundled [LICENSE](../LICENSE) file for details.
