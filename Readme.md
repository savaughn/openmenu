
# openMenu

This project is a front-end for the Dreamcast, integrating with GDMenuCardManager.

## Build Instructions

### Prerequisites

- Ensure you have the KallistiOS (KOS) development environment set up.
- `$ source /opt/toolchains/dc/kos/environ.sh`

### Steps

1. Clone the repository:
    ```sh
    git clone https://github.com/mrneo240/openmenu.git
    cd openmenu
    ```

2. Build the project:
    ```sh
    make
    ```

### Clean Up

To clean up the build artifacts, run:
```sh
make clean
```

To clean only the ELF file, run:
```sh
make clean-elf
```

## License
This project is licensed under the Modified BSD License. See the LICENSE file for details.


## Credits
[u/westhinksdifferent](https://www.reddit.com/user/westhinksdifferent/) for design mockups
