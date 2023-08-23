Sprite extruder is pretty good but the cooling is just not good enough!

So I did some research, got inspired by a couple of models and made my own.

Since I was making my own, I thought I make it a bit extra.

I always wanted to have a nozzle cam so I designed the shroud around it.

I'm using a [OV5640 camera](https://www.aliexpress.us/item/3256804790797706.html?spm=a2g0o.order_list.order_list_main.21.7e001802xt1yaI&gatewayAdapt=glo2usa) with autofocus, since that has a smaller package. The video is stable, I'm not getting any flickering, maybe I just got lucky with it :)

The focal length is more than 20mm with this camera so I used this [macro lens](https://www.amazon.com/gp/product/B08MFSDZB8/ref=ppx_yo_dt_b_search_asin_title?ie=UTF8&psc=1) to achieve the shooting distance required! I cut it down the same size of the camera and just placed it in front of it, it sits just well because left some clearance for it in the model. Shoutout to [chilicoke](https://github.com/chilicoke) for finding that macro lens. He has an awesome [video](https://www.youtube.com/watch?v=GAp23w_dnNc&t=65s) for his own Voron nozzle camera mod.

There's a bracket next to the fan for the camera PCB. I used [M1.6 heatset](https://www.aliexpress.us/item/3256804538587668.html?spm=a2g0o.order_detail.order_detail_item.3.484df19cw1qEP4&gatewayAdapt=glo2usa) insert and screws to mount it.

And obviously I needed light to see what I'm printing so I added two tiny LEDs, I had extra [WS2813 LEDs](https://www.digikey.com/en/products/detail/seeed-technology-co-ltd/601000200/8120706) around so I used them but I think other models may fit also If they have similar size. Please refer to the spec sheet for details on wiring for your choice of LEDs.

Soldering was a pain the back for me! I'm not a pro at it. It took me a while and I think I killed two LEDs in the process but I eventually got it :) I also added some cable management clips on both arms of the shroud. Be gentle with them and they work, otherwise you might break them.

Finally just throw in a good 5015 fan, I got [this one](https://www.filastruder.com/products/delta-bfb0524hh-blower-fan) from Filastruder. I also made some holes that goes to the camera and the LEDs, hoping that it might help with their cooling? :) Not 100% sure how much that affects to be honest because I was lazy to test with and without them but I wanted to be safe and give them some airflow too! :) They also have holes at the bottom and they're for making disassembly easy if ever needed.

I printed with ABS, with 0.2 layer height, with a self made chamber and I used a bit of fan starting from layer 10+, which makes the print have good detail and helps with some the overhangs. I didn't use supports and I think you should be able to print without supports as well. Also I'd suggest considering the thermal shrinkage when printing it, I scaled my model 0.6 % in XY and %0.2 in Z. Obviously don't just copy my numbers, yours will be different depending on material, slicer settings, cooling, printer environment etc.

Anyways, enough talk, I hope some of you find it useful and make your own. It's a very dangerous project though, because once you have it working you get addicted to watching it!! :)
