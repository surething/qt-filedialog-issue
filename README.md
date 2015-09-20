A small example project that demonstrates an issue with file dialogs in Qt.

Experienced with Qt `5.3` and `5.5`.

Built with Xcode `5.1.1`

Xcode project generated with e.g.:

    /usr/local/Cellar/qt5/5.5.0/bin/qmake -spec macx-xcode

Run the application, and the file dialog opens fine. Dismiss it using `Cancel`. Tab away, and tab back to the application, and the orphaned window is presented:

![](https://github.com/surething/filedialog/blob/master/window.png)
