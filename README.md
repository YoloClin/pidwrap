# PidLockWrap 

A dirty pid-locking wrapper for shell scripts

## Usage

```
pidlockwrap -n sleeper sleep 5 &
pidlockwrap -n sleeper sleep 5 &
pidlockwrap -n sleeper sleep 5 &
sleep 5;
pidlockwrap -n sleeper sleep 5 &
pidlockwrap -n sleeper sleep 5 &
```
