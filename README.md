# philo - stack-test.rb
#
# Implemented using node.js
#
# Installation Instructions
#   1. Install following dependencies:
#      - npm install winston
#      - npm install uuid
#      - npm install commander
#   2. Customize your config.json
#   3. Make sure directory for logDirctory exists, e.g. prompt> mkdir logs/
#
# Execution Instructions
#   1. Configure your NODE_ENV for the right logging level: 
#      - e.g. prompt> export NODE_ENV=debugging
#      - default is development, see below for options
#   2. Execute the code, e.g. prompt> node server.js
#   3. Kill gracefully w/ CTRL+c or kill (or murder it, that's fine too)
# 
# Environment configuration (see winston documentation for description of log levels)
#  o production  - Only log errors, no console
#  o testing     - Log up to info, no console
#  o development - Log up to verbose, with console
#  o debugging   - Log silly, with console
#
# Diagnostic instructions
#   1. The diagnostic port is configured in config.json
#   2. I like running it with >telnet <ipAddr> <port>
#
# Tested on macOS with the following:
# - node v10.13.0
# - prompt> sw_vers
#  ProductName:	        Mac OS X
#  ProductVersion:      10.14
#  BuildVersion:        18A391
# - ruby ruby 2.3.7p456 (2018-03-28 revision 63024) [universal.x86_64-darwin18]
#
