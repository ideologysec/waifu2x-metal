# waifu2x-metal

## How to Compile and Run

```
git clone https://github.com/safx/waifu2x-metal.git
cd waifu2x-metal
xcodebuild -project waifu2x-metal.xcodeproj
cd build/Release
cp ../../model/scale2.0x_model.json .
./waifu2x-metal Sample.jpg
```

This repo forked from the original in an attempt to bring it up to date with Swift 4 and Metal 2 (probably won't be accomplished, but still worth a shot)