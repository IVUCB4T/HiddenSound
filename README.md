# HiddenSound
Embedding secret messages in wave audio file

# What is HiddenSound
HiddenSound is a python based program for simple audio steganography. You can hide your secret text messages in wave audio file. You can play this audio in any media player and secretly share your private message with any one.

# Requirements
<p>This tool require python3</p>

## Installation

```
git clone https://github.com/IVUCB4T/HiddenSound.git
cd HiddenSound
```
## Usage
<p>HiddenSound have two python scripts. </p>
<ul>
<li><b>HiddenSound.py :</b> for hide secret information.</li>
<li><b>ExHiddenSound.py :</b> for extract secret information for wave audio file.</li>
</ul>

### Hide Secret Information in Audio file

```
python3 HiddenSound.py -f Demo.wav -m "Secret Msg" -o output.wav
```
### Extract Secret Information from Audio file

```
python3 ExHiddenSound.py -f output.wav
```

### Video Demo

#### For More Video subcribe <a href="http://youtube.com/@IVUCB4T">IVUCB4T YouTube Channel</a>
