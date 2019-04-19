# boe

boe stands for **B**atch **O**pus **E**ncoder

# Use case

Encoding your entire (lossless) music collection into something a little more mobile friendly (space-wise)

# Dependencies

opusenc (to encode to opus)

# Usage

## Clone repository
```
git clone https://cryptid.cc/lost/boe.git
cd boe
```

## Encoding a single album with no subdirectories

To encode an album with no subdirectories you need to specify the "-o" and "-i" arguments with the output directory and input directory respectively.
```
./boe -i /path/to/albumdirectory -o /path/to/outputdirectory
```

## Encoding a single album with a different bitrate 

For this you would use the "-b" argument
```
./boe -i /path/to/albumdirectory -o /path/to/outputdirectory -b YOURBITRATE (example: -b 128)
```

## Encoding multiple albums and multiple subdirectories in the album

Using the "-r" or recursive option allows you to recursively encode all subdirectories in the directory you specify
```
./boe -i /path/to/albumdirectory -o /path/to/outputdirectory -r
```
