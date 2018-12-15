# PokeGan
A Deep Convolutional GAN that is capable of generating new Pokémon!

![](pokegan.gif)

<p align="center">
  <img src="pokegan summ.jpg">
</p>


## Data 

I've written a simple webscraping script that obtains all pokemon images from [here](pokemondb.net)
All images are in **pokemon_imgs** folder.

## Installation and Prerequisites

All you need is Keras.

```
pip install keras
```

## Running the script

```
$ python dcgan.py
```

that's it!

you can edit the **dcgan.py** file and change the epochs/batch size.

## Results

All results -i.e generated pokemon - are stored in the **images** folder.




