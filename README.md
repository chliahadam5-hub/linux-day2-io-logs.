# linux-day2-io-logs.
# Lab: Linux Standard Streams & I/O Redirection

### Objective
Simulated application log management to demonstrate mastery of standard streams (stdin, stdout, stderr) in a Linux environment.

### Technical Implementation
* **Filtered Logs:** Used `grep` with `>` redirection to isolate specific error patterns from raw application logs.
* **Error Handling:** Implemented `2>` redirection to capture standard error streams, preventing silent failures in automated environments.
* **Stream Merging:** Utilized `2>&1` to merge stdout and stderr into a single audit trail, a critical requirement for production cron job logging and troubleshooting.
