# Think, write
My website: https://cover-me.github.io/

# Code

## Repos for work :wrench: 

**[instrDAQ](https://github.com/cover-me/instrDAQ)**: A LabVIEW program for transport measurements. Support 1D scans and a sequence of 1D scans. A 1D scan has the form `scan(channel, stop_value, minimum_time_interval=0, step=0)`. The parameter `step` is ignored if ramping a continuous channel, i.e. the magnetic field or the time. Mostly used for 1D scans.

**[repository/qt/qtlab scan scripts/](https://github.com/cover-me/repository/tree/master/qt/qtlab%20scan%20scripts)**: A python scan script for transport measurements. It makes use of the [qtlab](http://qtlab.sourceforge.net/) for instrument communication and my forked version of [qtplot](https://github.com/cover-me/qtplot) for real-time visualization. It's a script for any 3D linear scans `scan(D1,D2,D3)`, where `Di (i=1,2,3)` is like `([channel_i1, channel_i2, channel_i3, ...], [start_i1, start_i2, start_i3, ...], [stop_i1, stop_i2, stop_i3, ...], num_of_points_i, stabilization_time_after_setting_i1_to_in)`. Note that 1D and 2D scans are just special cases of 3D scans.

**[qtplot](https://github.com/cover-me/qtplot)**: Forked from [Rubenknex/qtplot](https://github.com/Rubenknex/qtplot). Plot data generated by qtlab 1D, 2D, or 3D scans. Add features such as realtime measurement visualization, easier reproducing (save status to INI files, drag and drop INI files to reproduce figures), easier noting (strings like "\<instrument:channel\>" will be replaced with the value in data files).

**[qtplotter](https://github.com/cover-me/qtplotter)**: Try to fit [Rubenknex/qtplot](https://github.com/Rubenknex/qtplot) into Jupyter Notebook and Python 3 by creating a new repo. It gets rid of features such as realtime visualization/fast data navigation and focuses on publication quality, production efficiency and the ability to share visualized, maybe interactive data. It appears that the python library holoviews would be the future though I am quite satisfied with the matplotlib now.

**[FP-monitor](https://github.com/cover-me/FP-monitor)**: Monitor readings on Leiden fridge's LabVIEW programs. Send notifications through email or Slack. "Paths" to front panel controls, thresholds, email list/Slack channels can be modified in INI files.

**[repository/OI/dr200 alarmer.bat](https://github.com/cover-me/repository/tree/master/OI)**: Work together with dr200 alarmer.py. Similar to FP-monitor, the script monitors the status of an Oxford fridge by reading the log file periodically and send notifications to Slack channels.

**[repository/Leiden/fridge data plotter/L plotter.ipynb](https://github.com/cover-me/repository/tree/master/Leiden/fridge%20data%20plotter)**: You need a program to visualize Leiden fridge sensor data for troubleshooting! Edit the start time, the end time, names of values to plot, and there you go. 

**[tcp-visa-server](https://github.com/cover-me/tcp-visa-server)**: A virtual instrument server receiving messages from VISA Write and responses to VISA Read. It is used as a wrapper to integrate things without VISA support, i.e. instruments with DLL drivers or readings from a program, to measurement programs such as InstrDAQ or even qtlab. Check **[TC_messenger](https://github.com/cover-me/repository/tree/master/Leiden)** for reading Leiden fridge's temperatures. There is also a version for the PPMS field and temperature, but I don't have time to find and upload it yet.

**[repository/klayout/](https://github.com/cover-me/repository/tree/master/klayout)**: Useful scripts for Klayout and EBL pattern design. Designing layouts for quantum devices is time-consuming, isn't it? There are techniques such as auto-routing but I am too busy to learn anything about it... Luckily, big companies are in the game and (or will) bring us tools such as [Qcodes](https://github.com/QCoDeS/Qcodes) or [Qiskit Metal](https://qiskit.org/metal/).

## Repos beyond work :beer:

**2DEG**: A webpage calculator for some physics. https://cover-me.github.io/2DEG/

**[cover-me.github.io](https://github.com/cover-me/cover-me.github.io)**: My website hosted on GitHub.

**matplotlib**: The vector image formats are no good enough for science! PDF is not treated as figures on a webpage while SVG may look different in different programs (PDF is better but still suffers from the same problem, see my post [here](https://cover-me.github.io/2019/02/17/Save-2d-data-as-a-figure.html)). There come problems when one uses Jupyter Notebook, Inkscape, and matplotlib. [Here](https://github.com/matplotlib/matplotlib/pull/17062) is my PR regarding one of the problems. Other problems are doing Gouraud shading in SVG files and more (another [post](https://cover-me.github.io/2020/04/18/Save-2D-data-as-a-figure-III.html)).  Those would require an update from big vendors such as Firefox and may take years.

**KindleEar**: Forked from [cdhigh/KindleEar](https://github.com/cdhigh/KindleEar). I use KindleEar to grab news from RSS sources and the latest manga/novel chapters. Automatically pushing is an awesome idea for Kindle as I am not a greedy book reader recently due to the heavy life. Without the push service, I would simply search and read everything without a kindle. I did some customization to KindleEar for better reading experience in my Kindle 4. Later I traded in the old Kindle 4 and purchased a Kindle paperwhite, which has LED background lights and a higher resolution (for mangas), making life a lot easier. 

**sms-backup-plus**: Forked from [jberkel/sms-backup-plus](https://github.com/jberkel/sms-backup-plus). The main goal of the original program was to _backup_ while what I wanted at that time was to _sync_ incoming calls and texts as emails so that I can leave one of my cellphones at home but still get instant notifications...


## More repos :moyai:

There are always more! The author are too busy to list them here... :flushed:

