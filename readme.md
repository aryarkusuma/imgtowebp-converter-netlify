# Webp Converter API
##### Converting image to webp format, inspired by statically.io image api by Frans Allen

- Build on the top of [Sharp(js)](https://github.com/lovell/sharp) for the image proccessing
- *this codebase is intended to be hosted on netlify*

#### *Endpoint*
> yourdomain.com/api/imageconv/:outputname?width=:width&heigth=:height&url=:url

#### *Only Converting Image*
> yourdomain.com/api/imageconv/:outputname?url=:url

#### *Resizing and Converting Image*
> yourdomain.com/api/imageconv/:outputname?width=:width&heigth=:height&url=:url
#### Only The Height
> yourdomain.com/api/imageconv/:outputname?heigth=:height&url=:url
#### Only The Width
> yourdomain.com/api/imageconv/:outputname?width=:width&url=:url

#### *Example* : [Click this](http://webp.projectxi.my.id/api/imageconv/pepe?url=https://pbs.twimg.com/media/ExwlywDXMAAYI_H.jpg "Click this")

### Future milestones
- Adding input image metadata API

***soon gonna push the code***
