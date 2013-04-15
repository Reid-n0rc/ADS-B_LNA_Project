The filter/LNA project is designed to improve the ADS-B Reception of a RTL-SDR USB Dongle.  More on operation of the dongle and reception of ADS-B can be found at <http://www.reddit.com/r/rtlsdr>.

There are three elements extrenal to the software/sdr that this project emcompasses: the antenna, frontend filter, and LNA.  Any antenna that covers 1090MHz can be used for this purpose.  I am using a design found here: <http://www.sprut.de/electronic/pic/projekte/adsb/adsb_en.html#antenne>.

Files for the filter design are contained the in the Filter directory.  There are two versions of the filter layout.  The "standard" filter, and filter_slant.  Filter_slant is the same as filter, just adjusted so the connectors are in a line in the X/Y Plane.  This will allows for a narrower PCB, and keeps any forces in the same direction, ie. doesn't try to pull the connector off to the side.  This is good for an antenna mounted design.

The LNA design is still in the works, but is based on the design shown here: <http://www.lll.lu/~edward/edward/adsb/preamp/ADSBpremap.html> and modified as per the instructions of Dr. Ken Filardo, KA0THK

CC-BY-SA N0RC, 2013.
