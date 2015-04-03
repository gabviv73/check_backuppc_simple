# check_backuppc_simple
Nagios plugin to check BAckupPc

This plugins check backup jobs on a local BackupPc server

It checks for errors on hosts and for backup jobs age.

At present, theresolds are not configurable.

The plugins returns

    WARNING of a backup Job is older than 25 hours
    CRITICAL of a backup Job is older than 49 hours
  
    WARNING if 1 host has failed backup
    CRITICAL if more than 1 host has failed backup
