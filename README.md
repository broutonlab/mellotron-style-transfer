# Broutonlab article on Nvidia Mellotron 

![mellotron](https://cdn-images-1.medium.com/max/800/1*DtFu22h85vp7C_mwyyU6nw.png)
Nvidia Mellotron: a multispeaker voice synthesis model based on Tacotron 2 GST that can extract properties such as pitch, rhythm and emphasis, making the generated speech expressive and natural.

## How it works
By picking randomly trained speaker we are able to imitate original speech properties. In order to do that we will pick source mel-spectrogram and predict such spectrogram for our speaker. According described mechanics in the article, Mellotron will extract source pitch contour with its rhythm
![predicted audio properties](https://cdn-images-1.medium.com/max/800/1*YUiS2NYyKaP5AIrOUu07Ig.png)

## Results & Resources
Helpful links with generated samples from different papers:
- Last Google Tacotron [results](https://google.github.io/tacotron/publications/prosody_prior/index.html)
- Nvidia Mellotron [extended results](https://nv-adlr.github.io/Mellotron)
