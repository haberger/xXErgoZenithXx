
1. load .json to configurator  https://config.qmk.fm/#/crkbd/rev1/LAYOUT_split_3x6_3
2. configure 
3. download json
4. move to qmk user folder qmk_firmware\keyboards\crkbd\rev1\keymaps\USER
5. convert .json to .c
    ```qmk json2c -o keymap.c filename.json```
6. compile hex
    ```qmk compile -kb crkbd -km USER```
7. flash via qmk toolbox
8. set handedness

