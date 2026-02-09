
# ChartingSoftware

![alt text](https://www.longrichk.com/static/media/stockSoftWare.ccfd5bda.png)

Attempting to make a fully open source stock trading software. Most code is pulled and edited from a 3 year old project called "JavaStockProject" located on my git.

What happened was back in 2017 Yahoo discontinued their API causing a basic data array needing to be updated. The entire platform still worked 100% fine with a normalize static data feed.

Another issue is that with Java since I'm doing the front-end from scratch without charting libs I have to make different configurations for each OS. Windows, Mac, and Linux all run it a little differently.

I also had poor documentation on my last project. When I say poor I mean literally none. I will be slowly documenting each part of the software as I now realize it's importance. 

# File Structure

<h5> 1.) Chart</h5> Holds all code for producing the front end from scratch. Using Min - Max conversion and ICON images to produce the image. Ran into flicking problems with the purple crosshairs before implementing imaging .  

<h5> 2.) Data </h5>  Started with the Yahoo finance API which was closed in 2017 out of nowhere. Now use alpha advantage. Uses a JSON response which I just parse myself. There are several JSON parsing libs in Java but imo they all suck so I just built a very static / custom one for the time being

<h5> 3.) Driver </h5> Used for benchmarks / testing. Will expand on this once I refactor and the code becomes more robust.

<h5> 4.) Indicators </h5> Each indicator is programmed from scratch within an array. Custom parameters are available on each one. Currently support around a decent amount of the most used / popular ones. Basic math.
