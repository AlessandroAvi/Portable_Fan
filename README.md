# PORTABLE FAN

This repo contains the schematics and the components that I used to build this little portable fan. Additional future work could be the addition of some sort of PWM controller, which should allow to control the fan speed.

Here is the [link](https://www.youtube.com/watch?v=qo8P7rzDw8k) of the original video from which I took the idea and STL file. 

<img src="https://github.com/AlessandroAvi/Portable_Fan/blob/main/Img/void.png" width=50% height=50%>

## BOM

- 1 x 12 V 120 mm fan: stolen from an old computer (model AFC1212DE)
- 1 x Voltage booster: [Aliexpress link](https://it.aliexpress.com/item/4001162729879.html?spm=a2g0s.9042311.0.0.17ac4c4dMwSY0U)
- 1 x Battery charger + protector: [Aliexpress link](https://it.aliexpress.com/item/4000522397541.html?spm=a2g0s.9042311.0.0.17ac4c4dMwSY0U)
- 1 x Battery indicator - 1S: [Aliexpress link](https://it.aliexpress.com/item/32851338868.html?spm=a2g0s.9042311.0.0.17ac4c4dMwSY0U)
- 1 x On/off switch: [Aliexpress link](https://it.aliexpress.com/item/1005002514375645.html?spm=a2g0s.9042311.0.0.17ac4c4dMwSY0U)
- 1 x Battery 18650: [Aliexpress link](https://it.aliexpress.com/item/1005002325103098.html?spm=a2g0s.9042311.0.0.17ac4c4dMwSY0U)
- 1 x Battery 18650 holder: [Aliexpress link](https://it.aliexpress.com/item/1005001660193629.html?spm=a2g0s.9042311.0.0.17ac4c4dMwSY0U)
- 1 x Micro switch push button: [Aliexpress link](https://it.aliexpress.com/item/32850340445.html?spm=a2g0o.productlist.0.0.15551f68HAHMJn&algo_pvid=02955c0b-055e-47af-9147-c170bea6f9e3&algo_exp_id=02955c0b-055e-47af-9147-c170bea6f9e3-18&pdp_ext_f=%7B%22sku_id%22%3A%2265305852762%22%7D)
- 1 x Case print

Total cost is around 10€ for the components (without the fan) + other 7€ for the print.

 ![name-of-you-image](https://github.com/AlessandroAvi/Portable_Fan/blob/main/Img/Material.jpg) 

## CIRCUIT SCHEMATIC

 ![name-of-you-image](https://github.com/AlessandroAvi/Portable_Fan/blob/main/Img/Schematic.jpg)

## PROBLEMS AND MODIFICATION

With respect to the original STL file a hole has been added in the top part for allowing the mounting of a mini rocker ON-OFF switch. Also the slot for the battery LED has been moved 15 mm down. 

One other big problem that I encountered was the deformation of the print. Due to the heat and the printing plane not being glass the final print had a warped shape. I was able to resolve this by heating up again the print with a hairdryer and deform the plastic in order to assume the correct shape.

<img src="https://github.com/AlessandroAvi/Portable_Fan/blob/main/Img/print_warped.jpg" width=70% height=70%>

Another problem encountered was the dimension of the fan. With respect to the original STL file, the fan that I used is 120x120x40 mm. This means that just the fan, without the small traingles will fill up the entire space. To overcome this problem the small triangles are mounted later with some hot glue as shown in the photo.

<img src="https://github.com/AlessandroAvi/Portable_Fan/blob/main/Img/void.png" width=50% height=50%>

## OTHER IMAGES

<img src="https://github.com/AlessandroAvi/Portable_Fan/blob/main/Img/print_3.jpg" width=% height=%>
