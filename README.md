# GASP

GASP is python script which is intended to be run with Redmine data. It outputs a synthesis written in Redmine wiki format that contains the amount of time spent per user on Redmine tasks.

## Installation

To install, place the scipt in the project's git repository, install the dependancies with

`pip install -r requirements.txt`

Then just run the script with pyhon 3.

## Input

The scipt needs the issues list and the timelogs that can be exported from Redmine as CSVs.

## Output

The outputs are a synthesis per Redmine user, containing the time spent per task, with the commits associated with each task.
