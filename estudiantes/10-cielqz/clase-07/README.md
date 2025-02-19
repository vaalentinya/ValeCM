# Clase 07

- [Mitchel Resnick](https://www.media.mit.edu/people/mres/overview/), Media Lab
- [Tuan Huang](https://tuan-h.com/)
- [Limzy Kenneth](https://github.com/limzykenneth/quantize.limzykenneth.com)
- [noc-book-2](www.github.com/nature-of-code/noc-book-2)
- [Q](https://qianqian-ye.com/) :-)
- [Apuntes](https://github.com/disenoUDP/dis9034-2024-1/tree/main/clases/clase-07#bibliograf%C3%ADa)

# [Processing](https://processing.org/)
#### · Sonido: [Bibliotecas](https://github.com/disenoUDP/dis9034-2024-1/tree/main/clases/clase-07#bibliotecas-y-lenguajes-de-sonido-digital)
- [strudel](https://strudel.cc/)
- (cmnd + space = buscador)
> processing.app > gestionar modos > contribution manager > libraries > [sound](https://processing.org/reference/libraries/sound/index.html) > instalar
>
> archivo > ejemplos > sonido.
>
> sketch > añadir archivo >

- .aif: audio interchange file format de archivo de audio de alta calidad desarrollado por apple
- .wav: waveform audio format desarrollado por microsoft
- .mp3: nada :p

Se determinan 12 notas en occidente pipipipi

#### · [Referencias Processing](https://processing.org/reference/)
- pan() = sonido stereo
- play() = soundfile.play(rate) - reate = velecidad (1, 1.5, 2, etc)
---------
- [Análisis de Fourier](https://github.com/disenoUDP/dis9034-2024-1/tree/main/clases/clase-07#an%C3%A1lisis-de-fourier): Estudio de ondas graficables x(t) y descomponerla como suma de [ondas sinuosidales](https://github.com/disenoUDP/dis9034-2024-1/tree/main/clases/clase-07#ondas-sinusoidales) (frecuencia de amplitud constante). Teniendo control de estas, se puede construir cualquier sonido. :-)
- [Ruido Blanco](https://github.com/disenoUDP/dis9034-2024-1/tree/main/clases/clase-07#ruido-blanco) y [oscilación](https://github.com/disenoUDP/dis9034-2024-1/tree/main/clases/clase-07#osciladores): disrupción de la presión atmosférica. Oscilador no estra nada pero sí sale sonido.
- [Filtros](https://github.com/disenoUDP/dis9034-2024-1/tree/main/clases/clase-07#definici%C3%B3n-de-filtro-y-sabores-de-filtros): Efecto que modifica el audio original, creando uno nuevo dependiendo de la frecuencia. Filtro pasa bajo: lo que tenga frecuencia baja lo multiplica en uno y lo que sea más agudo le baja el volumen (no lo deja pasar) y sirve para simular que algo está lejos. ARP2600 fue un equipo capaz de manipular sonido con osciladores y filtros. :-)
- Musique Concrete, Stockhausen, Pierre Schaeffer - Étudies de Bruits (1948): cortes de cintas de audio. The Beatles - Tomorrow Never Knows: cortes de cintas y grabaciones unidas, se le sube y baja el volumen aleatoriamente.
- ADSR: Attack - Decay - Sustain - Release

![adsr](https://github.com/cielqz/dis9034-2024-1/assets/163901464/06c864b3-7853-4460-be01-23e7a609aa36)


#### Samples y buffers: 
- [Roger Linn] En colaboración con la marca japonesa AKAI, crea una MPC, una especie de disco duro con 16 botones distribuidos en 4x4 para ser manipulada con una mano. Se considera la base del hip-hop, al mismo tiempo, varios instrumentos provienen de esta herramienta. No existe el concepto de notan o escala musical.
- [Critter and Guitari](www.critterandguitari.com)
- [Oficina de sonido](www.instagram.com/oficina_de_sonido/) utiliza el código de [Bleep Labs](bleeplabs.com/devices/) para hacer su maquinita de cumbia :o

### Explorarión
- Examples > sound > soundfile > keyboard = This example shows how to make a simple keyboard-triggered sampler with the Sound library. In this sketch 5 different short samples are loaded and played back at different speeds, which also changes their perceived pitch by one or two octaves.
- Examples > sound > soundfile > simpleplayback = This is a simple sound file player. Use the mouse position to control playback speed, amplitude and stereo panning.
