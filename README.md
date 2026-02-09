# Day-04-Linux-Processes-and-Services

**Check running processes**
Use `ps aux` or `top` to see all running processes, CPU and memory usage.
You can find a specific process using `ps aux | grep process_name`.

**Inspect one systemd service**
Use `systemctl status sshd` (or any service) to check if it’s active or failed.
It shows service state, logs, and start time.

**Small troubleshooting flow**
If something is not working → check process → check service status → check logs.
Commands: `ps`, `systemctl status service`, `journalctl -xe`.


