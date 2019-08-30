# boe

boe stands for **B**atch **O**pus **E**ncoder

# Use case

Encoding your entire (lossless) music collection into something a little more mobile friendly (space-wise)

# Dependencies

- modern version of bash (bash >= 4)
- opusenc (to encode to opus)

# Usage

## Clone repository
```
git clone https://cryptid.cc/lost/boe.git
cd boe
```

## Encoding albums

To encode albums you need to specify the "-o" and "-i" arguments with the output directory and input directory respectively.
```
./boe -i /path/to/inputdirectory -o /path/to/outputdirectory
```

## Encoding albums with a different bitrate 

For this you would use the "-b" argument to specify a bitrate (in kbps)
```
./boe -i /path/to/inputdirectory -o /path/to/outputdirectory -b bitrate
```
