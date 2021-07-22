# ToxicFilter
[![Scrutinizer Code Quality](https://scrutinizer-ci.com/g/swbreuer/ToxicFilter/badges/quality-score.png?b=main)](https://scrutinizer-ci.com/g/swbreuer/ToxicFilter/?branch=main)
[![Build Status](https://scrutinizer-ci.com/g/swbreuer/ToxicFilter/badges/build.png?b=main)](https://scrutinizer-ci.com/g/swbreuer/ToxicFilter/build-status/main)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

[![MOST logo](https://www.appropedia.org/w/images/thumb/c/c2/Sunhusky.png/240px-Sunhusky.png)](https://www.appropedia.org/Category:MOST)

`ToxicFilter` is designed to take the output of [MFAssignR](https://github.com/skschum/MFAssignR) and process the toxic compounds into an easily readable and understandable format.

Contents
========

 * [Why?](#why)
 * [Installation](#installation)
 * [Usage](#usage)
 
 ### Why?
 
 This project has been designed in tandem with MOST's [BioPROTEIN project](https://www.appropedia.org/BioPROTEIN) to act as a precursor to live animal testing of completely novel food sources. This is intended to decrease the number of live animal tests required as to both decrease cost and increase ethical use of research resources. This project also seeks to serve as a useful tool in researching potential food sources for desperate times such as common agricultural wastes and potential future reprocessing research. To mee this goal this project uses entirely open source and free to use tools in its full workflow, including [MZMine](http://mzmine.github.io) and the previously mentioned [MFAssignR](https://github.com/skschum/MFAssignR).
 
 
 ### Installation
 The installation of this project is very simple. 
 1. Install with [`pip3`](https://pypi.org/project/shallow-backup/)
    + `$ pip3 install shallow-backup`
    + `$ shallow-backup`

### Usage
Proper usage of this project includes using MZMine and MFAssignR, described in the paper to be published soon in MethodsX.