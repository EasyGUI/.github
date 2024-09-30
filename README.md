# Current station
Currently, we have a lot of GUI development framework, but most of them are too heavy, and the simple ones are too simple to build a beatufaul application.  

At now (2024.9.30), only few framework can meet most needs of people:
- QT: Good enough, but it's heavy and not free.
- GTK: Only good in linux, and not easy to use in other platform.
- Sciter: Support js mostly. Good, but not open source and not free.
- FLTK,TK: Simple enough, but too old, too ugly to use in products.
- AWTK/LCUI: Simple and good, but not easy to use it with other language.
- Duilib, WPF, WinForm ... : most of them can't be used in linux or heavy or only binding one language.

# What i want
- Can support from MCU to PC.
- Can build using xml/json description file and CSS style. (Design Tools)
- Can binding easily(python, go, rust, js, C#, c/c++).
- Can support i18n.
- Can support system tray/menu/window style.
- Easy to custom UI theme or widget skin.
- API Thread safe.
- Document and demo.
- Depends little, package size small. Better to support one file.
