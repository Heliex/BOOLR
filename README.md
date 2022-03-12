# BOOLR - UPDATED - 1.0.6
A digital logic simulator - [UPDATED] - 1.0.6

#### How to develop on BOOLR

The most useful tools to dev is yarn, install yarn with npm 

```bash
# Install Yarn on your machine
npm install -g yarn

# Get BOOLR from this repo (or fork it)
git clone https://github.com/Heliex/BOOLR.git && cd BOOLR

## Fetch dependencies
yarn

## Run BOOLR
yarn start
```

### How to build

Before building BOOLR, you'll have to make some changes so that your application will work with saves function :

- In index.html change line 94 : /../saves to /../../saves
- In saves.js change line 2 : /../saves to /../../saves
- In savedCustomComponents.js line 13 : /../data/customcomponents.json to /../../data/customcomponents.json
- In savedCustomComponents.js line 21 : /../data/customcomponents.json to /../../data/customcomponents.json

```bash

# Build BOOLR
yarn dist 
```

After building : 

- In index.html change line 94 : /../../saves to /../saves
- In saves.js change line 2 : /../../saves to /../saves to
- In savedCustomComponents.js line 13 : /../data/customcomponents.json to /../data/customcomponents.json
- In savedCustomComponents.js line 21 : /../data/customcomponents.json to /../data/customcomponents.json

## What's new SINCE V1.0.4

- LED Array component.
- D Latch component.
- SR Latch Component.
- Flip Flop Component.
- NAND, NOT AND XNOR gates.
- Fix wire bugs.
- Retrieve Saving board working on multi-OS.
- Updated electron version from 1.0.0 to 17.1.0.
- Fixed some UI issues.
