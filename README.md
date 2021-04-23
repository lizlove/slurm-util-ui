# slurm-util-ui
UI Mock for Slurm Utility Data Analysis Site


## Todo
- Add tooltips for all
- Add estimated usage / average line chart with threshold dotted line
    - Y axis: Efficiency, X axis: time. Dropdown with time frames: 3 days, 7, 30, 90 days.
- Add Fido link to user pgae on header
- Change tables to a tab view with All/Running/Pending/Completed
- Link to general docs
- Partition link to wiki on queue in tooltip


## Done
- Remove ceph as a bar - has no limit. Change to color coded usage < 1TB green, > 100TB very red
- Split home usage into 2 bars 1 bytes, 1 files (1M cap) [see elovero df -H or df -Hi for my file info]
- YTD Time - add 'in hours' change hour units to sci notation and make a table

## Questions
- What is the byte limit?
- sci notation to what decimal? swap at what point?
- What is the range for ceph values - help me set the gradient!