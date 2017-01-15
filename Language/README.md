# Otter-ish - Language
My own configuration and alterations to Otter Browser

Everything in here is my personal builds and setups to make it easier for me to move between machines.

Feel free to download just about everything (and hopefully merge into main branch)

This is in no way affiliated with anything.

The segments
* Language - .qm and .ts files with additions (hotkeys mainly)

This is only the english (UK/GB) language file with additions for hotkeys.

To use:
1. Download otter-browser_en_GB_accel.qm
2. start otter 
3. click *Help* (top menu)
4. *Switch application language*
5. Select language: *Custom*
6. Browse to the *otter-browser_en_GB_accel.qm* you just downloaded

To convert from a .ts to a .qm use:
lrelease otter-browser_en_GB_accel.ts otter-browser_en_GB_accel.qm
(lrelease is in the package qt4-linguist-tools)

The .ts-file is an xml-file and can be edited with any plaintext-editor.

