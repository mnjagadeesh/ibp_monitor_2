# Beacon Monitor-2 Project

Thank you for your attention and patience to the Beacon Monitor-2 Project.

**New**: Facebook Page is also available.  https://www.facebook.com/beaconmonitor2/

After the statement on the web site (http://ayoko.net/beacon/) on
March, 2017, the progress was quite slow until this October.

However, due to getting more spare time :) , the progress is pretty
accelerating at the moment.

I had decided to postpone rewriting the current "Signal Recorder",
which was written by
C language, and started rewriting other (or succeeding) signal
processing parts by Python language so that the project software
becomes more portable (or be able to run on many PC or Raspberry Pi).

However, as of Nov. 18, the parts have been mostly completed, so I'm
now rewriting the Signal Recorder code by Python and ALSA library.

My main receiver for Beacon Monitor is SoftRock and PCM2902 USB CODEC
adapter, so I'm focusing on it.

The current code can be found in the branch ```dev_start_20171016```
(https://github.com/yokoyama-flogics/ibp_monitor_2/tree/dev_start_20171016).

# Current Status

The following shows the current progress.  (As of Nov. 18, 2017)

![Current Progress Diagram](./doc/diagram.png)

- Migration software, which converts the output of Signal Recorder,
  was written by Nov. 3.

- Database engine (using SQLite3) was done as of Nov. 10.

- Signal Characteristics Extractor was written by Nov. 6.

- Station Frequency Deviation Tracker was written by Nov. 10.

- Bayesian Inference Program was completed by Nov. 13.

- Bar Graph Visualizer was written by Nov. 15.

- Signal Cleaner was done by Nov. 17.

- Task Keeper to run the above parts continuously, by Nov. 17.

- Now coding Signal Recorder for SoftRock + PCM2902 USB CODEC adapter,
  by ALSA library.

- Remaining code which I need to complete are,

	- Map Visualizer (may be postponed?)
	- Twitter bot (may be postponed?)

I guess, if I won't face any business problems, the above code will be
completed by end of this November or December.

Thank you for your additional patience...

Regards,

Atsushi Yokoyama (JN1SDD)
