# [Virtual Art Gallery](https://clementcariou.github.io/virtual-art-gallery/build) [![Build Status](https://travis-ci.com/ClementCariou/virtual-art-gallery.svg?branch=master)](https://travis-ci.com/github/ClementCariou/virtual-art-gallery)

[![screenshot](ArtGallery.png "App screenshot")](https://clementcariou.github.io/virtual-art-gallery/build)

## Description

This project simulates an art gallery in your browser using [REGL](https://github.com/regl-project/regl).
It aims at reproducing the experience of a real art gallery.
The architecture is generated using a 10km long 6th order [Hilbert Curve](https://en.wikipedia.org/wiki/Hilbert_curve).
The paintings are asynchronously loaded from the [ARTIC](https://api.artic.edu) and placed on the walls.
You can use this project to display your own artworks.

## Setup

Installation :
```shell
https://github.com/leeseomin/virtual-art-gallery 
cd virtual-art-gallery
npm install
```
Start the budo dev server : 
```shell
npm start
```
Build : 
```shell
npm build
```

## Using it with [local images](https://clementcariou.github.io/virtual-art-gallery/build?api=local)

The local api is accessible using this URI params in the address bar: ```?api=local``` (it's possible to load automatically this API by changing the default API in the [api.js](api/api.js) file). You can change the displayed images in the folder [images](images), you will need to rebuild the project (or relauch the dev server) to apply the modifications.
