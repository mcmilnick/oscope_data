# oscope_analysis
Apply settings and pull data from your oscope to your computer.
This can allow you to pull and analyze data faster. No more slow tools,
usb sticks, etc. In addition, you can do processing on your computer, thus
freeing up the oscope and helping to automate your analysis.

I have made this accessible in python, matlab, and C#
They all act a little differently. In python, there is a base loop looking for
an interrupt to grab data. In Matlab it acts as a control interface for
controlling an Arduino while collecting data. In C# we have a much more polished
and thread safe app.
It uses a tektronix oscope, but the principles are the same for all oscopes.

I am documenting all work on my blog site. https://techtures.wordpress.com/about/