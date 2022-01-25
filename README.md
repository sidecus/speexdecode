# speexdecode
Wechat speex decoder 

# Build docker image
```
docker build -t speexdecode ./ 
```

# Run docker image - mounting data folder
```
docker run -it -v $HOME/repos/audiodata:/audiodata speexdecode
```

# decode
```
speex_decode /audiodata/input.speex /audiodata/output.wav
```
