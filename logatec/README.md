Simple cognitive radio example
==============================


LOG-a-TEC
---------

The `logatec.py` script uses one node the Industrial Zone cluster of the
LOG-a-TEC testbed to simulate a cognitive terminal. Another node is used to
simulate a legacy terminal, while three other nodes are setup as spectrum
sensors and observe the transmission.

Since the LOG-a-TEC testbed does not currently support packet based
transmissions and low-latency control of the sensor nodes, the behavior and
transmission frequencies of nodes are programmed in advance. As such this is
not a true demonstration of a cognitive radio, but rather a simulation of how
to simulate a presence of one in the testbed.

![](node_17.png)

Experiments running on LOG-a-TEC testbed are controlled over the Internet from
a Python script running on the user's computer. To run an experiment, you need
the following installed on your system:

 * Python 2.x. (usually already installed on Linux systems),
 * [numpy](http://www.numpy.org/) (usually can be installed through the package manager on Linux systems),
 * [vesna-alh-tools](https://github.com/sensorlab/vesna-alh-tools) and
 * a valid username and password for the LOG-a-TEC testbed (see vesna-alh-tools
   README on how to set it up).

To run the experiment, use:

    $ python logatec.py

See comments in the script for more details.
