# Carbon Spice

Carbon spice is an attempt to create a colorscheme that has good contrast and
readability along with meaningful highlights for code editing.

It is based on [IBM's design
language](https://www.ibm.com/design/language/color/) and inspired by
[Oxocarbon](https://github.com/shaunsingh/oxocarbon.nvim).

## Screenshot

![carbon-spice-nvim](https://user-images.githubusercontent.com/15707316/224126011-88172d32-fc99-4d90-8a5e-da262ea58118.png)

## Design

The theme simply uses `vim.api.nvim_set_hl` to set highlight colors and does not aim to provide any customisability as opposed to oxocarbon.

I have previously created some vim/neovim colorschemes but they never stuck
(neither did any other themes). I always found inconsistencies and nitpicks,
usually because too many things were being colored on my screen. The
approach I took this time is create new colors and gradually replace the
originals. For syntactic elements, if I am unsure of what color to assign I
have assigned white and will revisit if it looks odd when editing specific
pieces of code.

This is very much a Work In Progress and there will be many inconsistencies to
start with.
