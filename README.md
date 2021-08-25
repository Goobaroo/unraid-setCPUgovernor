# unraid-setCPUgovernor
Unraid script to set CPU governor if VM is running.

This script can be used with the userScripts plugin in Unraid to check for running VMs (presumably gaming ones) and flip the CPU governor to performance.

I found this helped in gaming peroformance using a Ryzen 5700G processor.

When the VM is shut down, it sets thet governor back to ondemand.  It only changes the value if needed.

I have mine running on a schedule every 5 mintues.

## Setup

1. Have the (CA User Scripts)[https://forums.unraid.net/topic/48286-plugin-ca-user-scripts/] Plugin installed on your Unraid server.

2. Add a new script and copy the contents of the script file.

3. Set a custom scheule, I used every 5 minutes `*/5 * * * *`

4. All set.