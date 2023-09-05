## Prerequisites
1. QMK (https://docs.qmk.fm/#/newbs_getting_started)

## Install
> mkdir -p keyboards/splitkb/aurora/sofle_v2/keymaps/personal
cp splitkb_aurora_sofle_v2_rev1_layout_mine.json <qmk_firware_dir>/keyboards/splitkb/aurora/sofle_v2/keymaps/personal/keymap.json
qmk compile -kb splitkb/aurora/sofle_v2/rev1 -km personal -e CONVERT_TO=rp2040_ce