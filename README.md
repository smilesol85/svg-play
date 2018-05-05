# svg-play

## Compare png and svg
> test image width:416px, height:480  
> png compressions : https://tinypng.com/  
> svg compressions : http://www.svgminify.com/  
> Sources : https://www.flaticon.com/packs/business-194  
- png size : 12KB(original) / 5.9KB(compressions)  
- png size : 9KB(original) / 5.9KB(compressions)  
- svg size : 5KB(original) / 2KB(compressions)  

## svg(Scalable Vector Graphics) advantage  
- XML format
- Don't loose any quality if they are zoomed or resized
- Every element and every attribute in SVG files can be animated
- W3C recommendation

## Browser compatibility  
https://caniuse.com/#search=svg  
`Need to image tag with svg tag for browser compatibility`  
```html
<svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 68 65">
  <path fill="#1A374D" d="..."/>
  <path d="..."/>
</svg>
<img src="filename.png" alt="icon" style="display:none">
```

## svg compressor
- https://jakearchibald.github.io/svgomg/
- https://github.com/RazrFalcon/svgcleaner-gui
- http://www.svgminify.com/

## TODO
- svg path generator ([issue](https://github.com/smilesol85/svg-play/issues/3))