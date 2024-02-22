# Corne ZMK setup
This is suitable for Corne with the following features:
- 42 keys
- 36 keys (change to `&five_column_transform` in `corne.keymap`, delete outer columns in keymap)
- with or without niceview support
- with mousekey enabled

## First time bluetooth connection
Please test before flashing to avoid complicating troubleshoot procedure.
![ble keyboard corne](https://user-images.githubusercontent.com/79617315/230918198-c6b5562f-e7e5-463d-b915-6c299875f332.jpg)

## Key remap
After you make sure that the board can be connected and every key is registering, you can proceed to remap the keys according to your needs.

## New user 
|![1fork](https://github.com/superxc3/zmk-config-crkbd/assets/79617315/c1d1d583-d07d-4178-bc88-3ae4230202e6)|
|:--:|
|1. Please fork this github repo. Applicable for 5column, board with/without niceview.|

|![2 githubsignin](https://github.com/superxc3/zmk-config-crkbd/assets/79617315/53f00200-1405-48dd-85db-231bd4cf28db)|
|:--:|
|2. Go to [keymap editor](https://nickcoutsos.github.io/keymap-editor/) to edit keymap.	Choose Github from the list. 3. Sign in your github account.|

|![3](https://github.com/superxc3/zmk-config-crkbd/assets/79617315/69422119-67fd-4c99-99bf-5a27e0ba2fab)|
|:-|
| 4. Choose github repo you just forked in 1. Make sure you select the correct Branch `main-with-native-mouse` for mouse repo. |
| 5. Start edit your keymap, after finish click SAVE. |
| 6. For mouse keys, please refer to [Keycode](https://github.com/superxc3/corne-wireless-view-zmk-config/blob/main-with-native-mouse/README.md#keycode). Head to `corne.keymap` and key in mouse keycode |
| 7. Click save or commit changes. If it does not auto run, Go to `Actions`, click `Build`, `Run workflow`|

|![4](https://github.com/superxc3/zmk-config-crkbd/assets/79617315/e56acc85-680d-41fc-a6ad-b10fc1767a37)|
|:--:|
|8. Click firmware and extract the two uf2 out. Drop to left and right respectively.|

## Keycode
Kindly note that some keycodes are different from zmk mouse repo, please refer to [native-keycode](https://github.com/urob/zmk-config/blob/upstream-mouse/config/mouse.dtsi) for full list. Use these keycodes in `corne.keymap`, some codes are not available and synced with Keymap Editor, you are not encouraged to remap mouse key in Keymap Editor.





