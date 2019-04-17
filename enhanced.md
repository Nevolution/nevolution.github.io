What is Enhanced Mode?
-----------------------
Enhanced mode is a special mode Nevolution can be working in on Android 8+.

Compared to normal working mode, enhanced mode provides the following benefits:

* Avoid the "double-alert" issue on some devices.
* Add "Until next boot" to the snooze duration options for sticky notifications.
* Add "Unsnooze all" to the shortcuts of Nevolution.

How to activate?
-----------------
Enhanced mode needs to be activated via the following ADB shell until Android Q:

For Android **8.0**:

`settings put secure enabled_notification_assistant com.oasisfeng.nevo/.Assistant`

For Android **8.1 & 9**:

`cmd notification allow_assistant com.oasisfeng.nevo/.Assistant`

There's no command output for successful activation.

You can verify the working mode by launching Nevolution, to see if it shows "Nevolution is ready (Enhanced mode)".
