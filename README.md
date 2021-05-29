# simpeg: SIMple jPEG Decoder-Encoder

This repo does nothing expect for a decode-encode process of reading RGB data from a `jpg` image, and output as another `jpg` file.

## Dependency

- `libjpeg` or `libjpeg-turbo` to load and convert JPEG information into color space

## Build & Run

C++ 11 is used.
```bash
$ make
$ ./simpeg input.jpg output.jpg 90
```

## Demo

<center class="half">
    <a href="https://sm.ms/image/YfAZOFrgic4KGsN" target="_blank"><img src="https://i.loli.net/2021/05/29/YfAZOFrgic4KGsN.jpg" 
        alt="lena-color.jpg" width="200"></a>
    <a href="https://sm.ms/image/zatQOAi1ocYh5ZL" target="_blank"><img src="https://i.loli.net/2021/05/29/zatQOAi1ocYh5ZL.jpg"
        alt="lena-color-30.jpg" width="200"></a>
</center>

The left one is the origin while the right is JPEG compressed image with quality equals to 30.

## References

- [read jpeg image with libjpeg](https://gist.github.com/kentakuramochi/f64e7646f1db8335c80f131be8359044)
- [jpeg compress algorithm](https://create.stephan-brumme.com/toojpeg/)
