## wobblewobble

slow oscillators for crow outputs.

![image](https://user-images.githubusercontent.com/6550035/118399616-dee2bc80-b612-11eb-8594-5385cec7ea38.gif)

assign each of the four crow outputs one of many different types of slowly oscillating modulation sources. oscillators are configured in SuperCollider making it easy to configure / design / add new oscillators, including complex ones from the [chaotic UGens](https://doc.sccode.org/Browse.html#UGens%3EGenerators%3EChaotic). current oscillators:

#### constant

![constant](https://user-images.githubusercontent.com/6550035/118861929-eb287d00-b891-11eb-9efd-2a09f0142d5f.PNG)

#### sine

![sine](https://user-images.githubusercontent.com/6550035/118861927-ea8fe680-b891-11eb-9fe1-7ce6c2f93c81.PNG)

#### triangle

![triangle](https://user-images.githubusercontent.com/6550035/118861926-ea8fe680-b891-11eb-85b1-8a9cc5df7c94.PNG)

#### wobbly sine

![wobblysine](https://user-images.githubusercontent.com/6550035/118861924-e9f75000-b891-11eb-9b49-b1df6d0cc18e.PNG)

#### snek

![snek](https://user-images.githubusercontent.com/6550035/118861922-e95eb980-b891-11eb-9d31-bc03bc69210f.PNG)

#### lorenzian

![lorenz](https://user-images.githubusercontent.com/6550035/118861920-e95eb980-b891-11eb-9705-3b80d592c4fe.PNG)

#### henonian

![henon](https://user-images.githubusercontent.com/6550035/118861918-e8c62300-b891-11eb-97ed-3affa265dd18.PNG)

#### random walk

![randomwalk](https://user-images.githubusercontent.com/6550035/118861917-e82d8c80-b891-11eb-940b-4877262f5110.PNG)

#### latoocarfian

![LatoocarfianC](https://user-images.githubusercontent.com/6550035/118861930-eb287d00-b891-11eb-9225-3f78d48dd050.PNG)

#### standard chaotic

![standard](https://user-images.githubusercontent.com/6550035/118861935-ec59aa00-b891-11eb-838e-cbaed31b23e8.PNG)

#### fbsine

![fbsine](https://user-images.githubusercontent.com/6550035/118861938-ecf24080-b891-11eb-9475-281177b24c5d.PNG)


#### quad

![quad](https://user-images.githubusercontent.com/6550035/118861937-ec59aa00-b891-11eb-965f-2856069def06.PNG)

#### gingerbreadman

![gingerbread](https://user-images.githubusercontent.com/6550035/118861933-ebc11380-b891-11eb-96b3-118671315bd9.PNG)


each output can also be configured to respond to midi input, either modulating the voltage level via pitch (any note, or top note), or modulating the voltage level from an envelope.

### Requirements

- norns
- crow

### Documentation

- hold K1 to switch crow
- K2/K3 switch modulator
- E1 changes frequency
- E2 changes lfo min
- E3 changes lfo max

via the parameters menu, "`WOBBLE`", you can also...

- clamp the minimum and maximum values of the lfo
- add midi input to control pitch (top note, any note) or add an envelope
- meta param

## download

```
;install https://github.com/schollz/wobblewobble
```

## license 

mit 



