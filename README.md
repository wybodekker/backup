# backup

backup and restore, full or partial

## Properties

|key|value|
|-:|:-|
|  script:|backup|
|   short:|backup and restore, full or partial|
|    type:|bash|
|  author:|Wybo Dekker|
|   email:|[wybodekker@me.com](mailto:wybodekker@me.com)|
| version:|3.23|
| license:|GNU General Public License|
|   intro:|Back up files into zip compressed archives, or restore|
|         |files from those.  Both full and partial backups are|
|         |possible.|

## Options

|option|description|
|:-|:-|
|-h,--help	|print this help and exit|
|-H,--Help	|print full documentation via less and exit|
|-V,--version	|print version and exit|
|-v,--verbose	|print intermediate messages for debugging|
|-d,--dir	|show the backup directory path and exit|
|-c,--conf=X	|use X as configuration file; if X is -, don’t read any|
|		|configuration file and use defaults|
|-f,--full	|make a full backup|
|-s,--show	|Show a listing of the current backups|
|-r,--restore=X	|Restore file X in current directory|
|-n,--named=X	|make partial backup to X.zip|
