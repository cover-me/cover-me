### Hi there 👋

### For work :wrench:

**instrDAQ**: A LabVIEW program for transport measurements. Support 1D sacns and a sequence of 1D scans. A 1D scan has the form `scan(channel, stop_value, minimum_time_interval, step)`. The parameter `step` is ignored if ramping a continuous channel, i.e. the magnetic field or the time.

**repository/qt/qtlab scan scripts/**: A python script for measurements with [qtlab](http://qtlab.sourceforge.net/). Supprot 3D scan, `scan(D1,D2,D3)`, where `Di (i=1,2,3)` has the form `([channeli1, channeli2, channeli3, ...], [starti1, starti2, starti3, ...], [stopi1, stopi2, stopi3, ...], num_of_points_i, stabilization_time_after_set_i)`. Note that 1D and 2D are special cases of 3D.

**qtplot**: Forked from [Rubenknex/qtplot](https://github.com/Rubenknex/qtplot). Plot data from qtlab 1-3D scans. Add features to visulaize scans in realtime and improve efficiency for replotting and noting.



### For fun :beer:

### Misc. :moyai:

