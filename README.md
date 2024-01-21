# LAG - The latest multimodal music dataset open for you!
LAG (Lyric-Audio-Genre) - A song feature dataset for metal, rnb, pop and rap genre music.

Our new dataset, LAG, contains 663 samples, packed in a pickle file (.pkl), each containing 5 features as given below:
- `fileName`: name of the audio sample used [string]
- `lyrics`: as present in the respective audio sample, to the nearest word (manually verified) [string]
- `mfcc`: using FFMPEG, mfcc of the actual audio files were extracted to a size of (55168,) [vector of shape (55168,)]
- `genre`: describes the genre of the audio sample, limited to 'metal', 'rnb', 'pop' and 'rap' [string]
- `genreIdx`: label encoded value of the genre, useful for classification purposes. [number - metal ⇒ 0 | pop ⇒ 1 | rnb ⇒ 2 | rap => 3]


![image](https://github.com/blitzfa-india/LAG/assets/43881544/a5107c27-5933-48dd-b35e-3415281a3abc)

To zoom in, one such data point in our dataset would look something like this:

```
[
    "out_Can_you_hear_me_Vanden_Plas_0_2",
    "We had all the gods among us",
    [
      -291.4468078613281,
      -239.32164001464844,
      -228.03614807128906,
      -252.06797790527344,
      -231.99853515625,
      -191.72869873046875,
      -202.8234405517578,
      -231.3618927001953,
      -254.9090576171875,
      -275.6394958496094,
      -228.58197021484375,
      -185.22433471679688,
      -215.76168823242188,
      -286.9477233886719,
      -273.1100769042969,
      -265.9569091796875,
      -272.7559509277344,
      -279.12506103515625,
      -193.7666778564453,
      -120.65702056884766,
      -106.29338073730469,
      -126.46701049804688,
      -147.24468994140625,
      -167.37974548339844,
      -181.86651611328125,
      ...
      -37.49418258666992,
      -33.93297576904297,
      -31.638160705566406,
      -31.275402069091797,
      ...
    ]
    "metal",
    0
]
```


### More details
To know more about our dataset, please read our latest Medium article where we delve into the finest details of the dataset and a possible application for the same.

### Download
To download the dataset, you can refer the Latest Version in this repo or head over to the following link:
 > https://github.com/blitzfa-india/LAG/releases/tag/metal-rnb-pop-rap

