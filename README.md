# Mutagen Installer

This script installs the latest [Mutagen](https://mutagen.io/) version on your system. It supports various platforms and architectures.

## Supported Platforms and Architectures

| Platform | Architectures |
| --- | --- |
| Linux | amd64, arm64, arm, 386, mips64le, mips64, mipsle, mips, ppc64le, ppc64, riscv64, s390x |
| FreeBSD | amd64, arm64, 386, arm |
| Darwin | amd64, arm64 |
| DragonFly | amd64 |
| NetBSD | amd64, arm64, arm, 386 |
| AIX PPC | ppc64 |
| OpenBSD | amd64, arm64, arm, 386 |
| Solaris | amd64 |

## Installation

1. Clone this repository or download the `install_mutagen` script.
```bash
# Clone this repository
git clone https://github.com/S0mbr3/install_mutagen 
```
2. Make the script executable by running `chmod +x install_mutagen`.
3. Run the script by executing `./install_mutagen`.
4. Follow the prompts to select your platform and architecture.
5. The script will download and extract the latest version of Mutagen.
6. The script will add Mutagen to your system's PATH.

## Note

This script requires `curl` to be installed on your system.

## License

This script is released under the MIT License.
