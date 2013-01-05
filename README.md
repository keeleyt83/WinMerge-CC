### WinMerge CC

Starts WinMerge with a set of options suited for ClearCase integration.

http://manual.winmerge.org/CommandLine.html

/e: enables you to close WinMerge with a single Esc key press. This is useful when you use
WinMerge as an external compare application: you can close WinMerge quickly, like a dialog.
Without this parameter, you might have to press Esc multiple times to close all its windows.

/x: closes WinMerge (after displaying an information dialog) when you start a comparison of
identical files. The parameter has no effect after the comparison, for example if the files
become identical as a result of merging or editing. This parameter is useful when you use
WinMerge as an external compare application, or when you want to eliminate unnecessary steps by
ignoring files that don't have any differences.

/s: limits WinMerge windows to a single instance. For example, if WinMerge is already running, a
new compare opens in the same instance. Without this parameter, multiple windows are allowed:
depending on other settings, a new compare might open in the existing window or in a new window.

/wl: opens the left side as read-only. Use this when you don't want to change left side items in
the compare.

/u: prevents WinMerge from adding either path (left or right) to the Most Recently Used (MRU)
list. External applications should not add paths to the MRU list in the Select Files or Folders
dialog.

