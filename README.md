# SH Overlay

WARNING: The packages in this overlay are considered to be extremely experimental considering the current state of SuperH.
Use this overlay with extreme caution and hopefully with the intention of contributing to it.

This is the overlay used for staging packages to test on SuperH before submitting them to the main repository

## Adding the overlay

1. Using `eselect repository`, run `eselect repository add sh-overlay git https://github.com/GentooSH/sh-overlay.git`
2. Run `emaint sync -r` to update it
