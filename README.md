# scobc-a1-sample-blinky
Unofficial SC-boards sample repository. This repository is for test only.

## Clone the repository
```
git clone https://github.com/moonlight83340/scobc-a1-sample-blinky.git
```

## Init the repository
```
west init -l .
west update
```
# Currently not working, some modification are neeed to make the led work.

## Build the sample
```
west build -p always -b scsat1_main . -DBOARD_ROOT=../sc-boards
```

## Flash the sample
```
west flash
```

