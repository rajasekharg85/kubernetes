##### ENTRYPOINT

ENTRYPOINT is also used to run container just like CMD, but there are few differences.
1. We can't override ENTRYPOINT, but we can override CMD.
2. We can't override ENTRYPOINT, if you try to do so it will go and append to the ENTRYPOINT command.
3. If you use CMD and ENTRYPOINT and dont give any command from terminal, CMD acts as orgument provider to ENTRYPOINT