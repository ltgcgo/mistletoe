# Winter Mistletoe
🔗 Dialer toolchain in Bash for POSIX. Supports Linux and Android (Termux).

## Usage
- `./update`: Updates all configurations from the pointer.
- `./load`: The loader of the actual dialer.

## Configuration
- `pointer.txt`: Stores the URL for the full list of files with file names to download. URLs can contain an `${auth}` variable to bring in the authentication string.
- `auth.txt`: Stores the authentication string supplied to `pointer.txt`.
- `list.tsv`: Downloaded from `pointer.txt`. Where to fetch the actual configuration templates and dynamic params.