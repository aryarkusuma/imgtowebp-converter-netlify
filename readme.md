# Image (Resizer-Converter) to Webp format ( restful api )
##### Resizing-Converting image to webp format, inspired by statically.io image api by Frans Allen

notes: 
- Build on the top of [Sharp(js)](https://github.com/lovell/sharp) for the image proccessing ( pls read the diffrent machine arch installation of Sharp(js) )
- (*this codebase is intended to be hosted on netlify*)


### ***Click this to redirect you to the website***
[![Website](https://img.shields.io/website?style=for-the-badge&url=https%3A%2F%2Fiwebp.projectxi.my.id%2F)](https://iwebp.projectxi.my.id/)

### 
### Endpoint
#### *Only Converting Image*
> yourdomain.com/api/imageconv/:outputname?url=:url

#### *Resizing and Converting Image*
> yourdomain.com/api/imageconv/:outputname?width=:width&heigth=:height&url=:url
#### Resizing and Converting Image (by Height)
> yourdomain.com/api/imageconv/:outputname?height=:height&url=:url
#### Resizing and Converting Image (by Width)
> yourdomain.com/api/imageconv/:outputname?width=:width&url=:url

#### *Example* : [Click this](https://iwebp.projectxi.my.id/api/imageconv/pepe?width=123&height=123&url=https://raw.githubusercontent.com/aryarkusuma/aryarkusuma/main/png-clipart-pepe-the-frog-smiling-illustration-pepe-the-frog-video-game-warframe-meme-pepe-the-frog-sticker-game-food-thumbnail-removebg-preview%20(1).png)

