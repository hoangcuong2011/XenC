XenC
====


Added by me:

How to install it:

1. sudo apt-get install libbz2-dev


2. sudo apt-get install libboost-all-dev


3. cmake . -BOOST_LIBRARYDIR="/usr/lib/x86_64-linux-gnu"

4. ./XenC -s en -t fr --order 3 -i ./French/indomain.en -o ./French/mixdomain.en --in-ttext ./French/indomain.fr --out-ttext ./French/mixdomain.fr -m 3 -b --threads 8
sudo poweroff



XenC: an open-source data selection tool for Natural Language Processing

See INSTALL for build instructions.

These files are part of XenC: an open-source tool for data selection in Natural Language Processing.

Copyright 2016, Anthony Rousseau, LIUM, University of Le Mans, France
Contact: anthony.rousseau@lium.univ-lemans.fr

Development of the XenC tool has been partially funded by the
European Commission under the MateCat project.

To reference XenC in your publications, please cite this article:

@article{Rousseau13,
  title={XenC: An Open-Source Tool for Data Selection in Natural Language Processing},
  author={Rousseau, Anthony},
  journal={The Prague Bulletin of Mathematical Linguistics},
  number={100},
  pages={73--82},
  year={2013}
}
