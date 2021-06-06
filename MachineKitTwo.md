summary: How to Make MachineKit Work for the BBB/BBBW and LCD Cape...
id: MachineKitTwo
categories: Making Things Work
tags: medium
status: Published 
authors: Seth

## Making MachineKit Work for the BBB/BBBW with LCD Cape...
Duration: 1

- Find the repos. here: https://cloudsmith.io/~mahinekit/repos/

## First, we install the repos...
Duration: 2

1. curl -1sLf \
  'https://dl.cloudsmith.io/public/machinekit/machinekit/setup.deb.sh' \
  | sudo -E bash

2. curl -1sLf \
  'https://dl.cloudsmith.io/public/machinekit/machinekit-hal/setup.deb.sh' \
  | sudo -E bash

3. curl -1sLf \
  'https://dl.cloudsmith.io/public/machinekit/emcapplication/setup.deb.sh' \
  | sudo -E bash

## Then, update the BBB!
Duration: 3

- Firstly... `sudo apt update`
- Then... `sudo apt install machinekit-hal=0.4.20868-1.gitc2e248500~buster`
- Next... `sudo apt install emcapplication=0.4.20868-1.gitc2e248500~buster`

## If you are having issues, please see:
Duration: 4

- http://www.machinekit.io/docs/
