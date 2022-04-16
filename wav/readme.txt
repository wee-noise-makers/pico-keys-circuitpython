Samples from http://machines.hyperreal.org/manufacturers/Roland/TR-909/samples/TR909all.zip

```console
$ wget http://machines.hyperreal.org/manufacturers/Roland/TR-909/samples/TR909all.zip
$ unzip TR909all.zip
$ for file in *.WAV; do; sox --show-progress  "${file}" -t wav --endian little -c 1 -r 22050 "${file}_22k.wav"; done
$ mkdir wav
$ cp BT3A0D7.WAV_22k.wav BT3A0DA.WAV_22k.wav BT7A0D0.WAV_22k.wav \
     BTAAAD0.WAV_22k.wav CSHD4.WAV_22k.wav  HANDCLP2.WAV_22k.wav \
     HHCD0.WAV_22k.wav HHCD8.WAV_22k.wav HHOD0.WAV_22k.wav \
     HHOD8.WAV_22k.wav HT0D0.WAV_22k.wav HT7D0.WAV_22k.wav \
     LT0D0.WAV_22k.wav LT3D3.WAV_22k.wav MT0D0.WAV_22k.wav \
     MT3DA.WAV_22k.wav RIDED0.WAV_22k.wav RIM127.WAV_22k.wav \
     ST0T3SA.WAV_22k.wav ST0TAS3.WAV_22k.wav ST3T0S3.WAV_22k.wav \
     wav
```
