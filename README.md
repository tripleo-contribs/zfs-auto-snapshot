zfs-auto-snapshot:

An alternative implementation of the zfs-auto-snapshot service for Linux
that is compatible with zfs-linux and zfs-fuse.

Automatically create, rotate, and destroy periodic ZFS snapshots. This is
the utility that creates the @zfs-auto-snap_frequent, @zfs-auto-snap_hourly,
@zfs-auto-snap_daily, @zfs-auto-snap_weekly, and @zfs-auto-snap_monthly
snapshots if it is installed.

This program is a posixly correct bourne shell script.  It depends only on
the zfs utilities and cron, and can run in the dash shell.


Installation:
-------------

```shell
wget https://github.com/tripleo-contribs/zfs-auto-snapshot/archive/main.tar.gz
tar -xzf master.tar.gz
cd zfs-auto-snapshot
make install
```
