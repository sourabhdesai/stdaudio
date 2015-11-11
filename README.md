# stdaudio
Takes PCM data from stdin, plays it on your speaker

## Usage
    Usage: stdaudio [options]

    Options:

    -h, --help            output usage information
    -V, --version         output the version number
    -c, --channels <n>    number of channels in audio data
    -b, --bitdepth <n>    bit depth of audio data
    -s, --samplerate <n>  samplerate of audio data

## Example
`cat test/NXCAM_Guitar_audio_demo_v2.wav | node bin/stdaudio`

The above will start playing the wav file on the local device's speakers.