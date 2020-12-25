## Content
The repository contains folder `images` with car logos images.
These data are described in JSON file `car-logos.json` 

### Data example 
```
{  
  "name": "Volkswagen",  
  "url": "https://www.carlogos.org/logo/Volkswagen-logo-2015-1920x1080.png",  
  "fileName": "Volkswagen.png"  
}
```
*url property is original address from where was image downloaded*

## Embedding
If you wish to embed image you can do it with URL from this repository.

### Usage
```
const fileName = 'Volkswagen.png'

const logoUrl = `https://raw.githubusercontent.com/fadbad/car-logos/master/images/${fileName}` 
```

