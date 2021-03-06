# Torrent Media

Cliente de bitorrent utilizando WebTorrent de backend y AdminLTE como frontend. Actualmente se encuentra en estado Alpha, por lo que muchas funcionalidades todavia no estan terminadas.

![TorrentMedia Preview](https://raw.githubusercontent.com/FaCuZ/torrentmedia/master/preview.png)

### Compilar

```
	$ git clone https://github.com/FaCuZ/torrentmedia.git
	$ cd torrentmedia
	$ sudo npm install
	$ npm run-script adminlte
```

El comando `npm run-script adminlte` sirve para evitar que el template carge fonts desde la web. 

### Componentes de terceros
* [WebTorrent](https://github.com/feross/webtorrent)
* [AdminLTE](https://github.com/almasaeed2010/AdminLTE)
* [Humanizer-plus](https://github.com/HubSpot/humanize)

### Licencia
```
The MIT License (MIT)

Copyright (c) 2015 Alexandru Rosianu

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
```