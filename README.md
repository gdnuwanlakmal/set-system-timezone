# set-system-timezone

Configured system timezone by listing available timezones and setting it to Asia/Colombo with timedatectl

### ⏱️ Set System Timezone using timedatectl

This section shows how to manage the system timezone using the timedatectl command on Linux systems (typically systems with systemd).

### View Current Time and Timezone

  ```shell
  timedatectl
```
Displays the current system date, time, timezone, and NTP status.

### List Available Timezones

```shell
timedatectl list-timezones
```
Lists all available timezones. Useful for finding the correct timezone string (e.g., Asia/Colombo).

### Set Timezone

  ```shell
  sudo timedatectl set-timezone Asia/Colombo
```
Sets the system timezone to Asia/Colombo. Requires sudo or root privileges.

### Verify Changes
```shell
timedatectl
```
Run again to confirm the new timezone has been applied.
