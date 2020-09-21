## Good code saves people's time, bad code drains people's time, Majorana code does both.

# Repos for work :wrench:

**instrDAQ**: A LabVIEW program for transport measurements. Support 1D scans and a sequence of 1D scans. A 1D scan has the form `scan(channel, stop_value, minimum_time_interval=0, step=0)`. The parameter `step` is ignored if ramping a continuous channel, i.e. the magnetic field or the time.

**repository/qt/qtlab scan scripts/**: A python script for measurements with [qtlab](http://qtlab.sourceforge.net/). Supprot 3D scans, `scan(D1,D2,D3)`, where `Di (i=1,2,3)` has the form `([channel_i1, channel_i2, channel_i3, ...], [start_i1, start_i2, start_i3, ...], [stop_i1, stop_i2, stop_i3, ...], num_of_points_i, stabilization_time_after_set_i)`. Note that 1D and 2D are special cases of 3D.

**qtplot**: Forked from [Rubenknex/qtplot](https://github.com/Rubenknex/qtplot). Plot data generated by qtlab 1-3D scans. Add features such as visualizing scans in realtime and improving human efficiency of massive replotting and noting.

**qtplotter**: Try to fit [Rubenknex/qtplot](https://github.com/Rubenknex/qtplot) into Jupyter Notebook and Python 3 by creating a new repo. It gets rid of features such as realtime visualization/fast data navigation and focuses on publication quality, production efficiency and the ability to share visualized, maybe interactive data. I guess I need to study the license of [Rubenknex/qtplot](https://github.com/Rubenknex/qtplot) before pushing this project too far away.

**FP-monitor**: Monitor readings on Leiden fridge's LabVIEW executable. Send notifications through either email or Slack. Controls for reading, events, email list/Slack channels can be modified in .ini files.

**repository/OI/dr200 alarmer.bat**: Work together with dr200 alarmer.py. Similar to FP-monitor, the script monitors the status of an Oxford fridge by reading the log file periodically and send notifications to Slack channels.

**tcp-visa-server**: A virtual instrument server receiving messages from VISA Write and responses to VISA Read. It is used as a wrapper to integrate things without VISA support, i.e. instruments with DLL drivers or readings from a program, to measurement programs such as InstrDAQ or even qtlab. Check **Leiden/1.0_190721_LV17** for reading Leiden fridge's temperatures. There is also a version for the PPMS field and temperature, but I don't have time to find and upload it yet.

**repository/klayout/** Useful scripts for Klayout and EBL pattern design.

# Repos for fun :beer:

**2DEG**: A webpage calculator for some physics.

**cover-me.github.io**: Create a website for fun and then post something for more fun. Hmmm... :confused: 

**matplotlib**: The vector image formats are no good enough for science! PDF is not treated as figures on a webpage while SVG may look different in different programs (PDF is better but still suffers from the same problem, see my post [here](https://cover-me.github.io/2019/02/17/Save-2d-data-as-a-figure.html)). There come problems when one uses Jupyter Notebook, Inkscape, and matplotlib. [Here](https://github.com/matplotlib/matplotlib/pull/17062) is my PR regarding one of the problems. Other problems are doing Gouraud shading in SVG files and more (another [post](https://cover-me.github.io/2020/04/18/Save-2D-data-as-a-figure-III.html)).  Those would require an update from big vendors such as Firefox and may take years.

**KindleEar**: Forked from [cdhigh/KindleEar](https://github.com/cdhigh/KindleEar). I use KindleEar to grab news from RSS sources and the latest manga/novel chapters. Automatically pushing is an awesome idea for Kindle as I am not a greedy book reader recently due to the heavy life. Without the push service, I would simply search and read everything without a kindle. I did some customization to KindleEar for better reading experience in my Kindle 4. Later I traded in the old Kindle 4 and purchased a Kindle paperwhite, which has LED background lights and a higher resolution (for mangas), making life a lot easier. 

**sms-backup-plus**: Forked from [jberkel/sms-backup-plus](https://github.com/jberkel/sms-backup-plus). The main goal of the original program was to _backup_ while what I wanted at that time was to _sync_ incoming calls and texts as emails so that I can leave one of my cellphones at home but still get instant notifications...



# More :moyai:

There are always more!

