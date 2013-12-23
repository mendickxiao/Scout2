AWS Scout2
==========

## Description

Scout2 is a security tool that lets AWS administrators asses their environment's
security posture. Using the AWS API, Scout2 gathers configuration data for manual
inspection and highlights high-risk areas automatically. Rather than pouring
through dozens of pages on the web, Scout2 supplies a clear view of the attack
surface automatically.

## Installation

To install Scout2, simply clone this repository. You may want to put it somewhere
in your `$PATH` to make it easier to run.

In order to run Scout2, you will need to install Boto, Amazon's AWS SDK for
Python (https://aws.amazon.com/sdkforpython).

## Usage

To run Scout2, run the following command:

    $ python Scout2.py

This will generate a number of .json files that contain AWS configuration data.
To review the configuration, open the report.html file your browser.

The following command will provide the list of available command line options:

    $ python Scout2.py -h

## License

GPLv2: See LICENSE.txt.