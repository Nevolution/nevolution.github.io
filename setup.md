How to activate Synchronous Removal
-------------------------------------

Execute the following commands in ADB shell: (Some ROMs may require enabling extra option like "ADB Security")

1. `setprop persist.log.tag.NotificationService DEBUG`
2. `pm grant com.oasisfeng.nevo android.permission.READ_LOGS`

**REBOOT** your device and enjoy!
