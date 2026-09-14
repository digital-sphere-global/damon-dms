# damon-dms

Off-premises half of DAMON's dead-man's-switch. The fleet pings outbound; this
repo's scheduled workflow watches for SILENCE and raises the alarm.

Contains no secrets. Heartbeat topic names live only in 0600 files on-fleet.
