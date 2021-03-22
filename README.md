# storying_combined 

***Storying Extinction: Responding to the Loss of North Idaho’s Mountain Caribou*** is a multidisciplinary digital humanities project aimed at representing community response to the recent extirpation (2019) of mountain caribou from the South Selkirk mountains of North Idaho—the last caribou to inhabit the coterminous United States.

# handy things

`for f in *.avi; do ffmpeg -i "$f" -c:v copy -c:a copy -y "${f%.avi}.mp4"; done`

`for f in *.avi; do ffmpeg -i "$f" -y "${f%.avi}.mp4"; done`

## License

CollectionBuilder documentation and general web content is licensed [Creative Commons Attribution-ShareAlike 4.0 International](http://creativecommons.org/licenses/by-sa/4.0/). 
This license does *NOT* include any objects or images used in digital collections, which may have individually applied licenses described by a "rights" field.
CollectionBuilder code is licensed [MIT](https://github.com/CollectionBuilder/collectionbuilder-sa/blob/master/LICENSE). 
This license does not include external dependencies included in the `assets/lib` directory, which are covered by their individual licenses.
