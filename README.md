I have started using this Sensilabs AR Sandbox software in my Sandbox builds as well and its very cool! Inspired by the Sandbox developed my Dr. Kreylos but rebuilt 
from scratch in Unity. 

So I forked it to see if I could add a fractal simulation to it, again using Claude and VS Code extension Cline to do the coding. 
It's been very interesting learning about Unity and C# in the process. I keep hitting limits of the tokens I am able to use and also as the complexity of the task increases Claude starts going
into loops where it starts forgetting the context of work its already completed. 

I've gotten quite close to getting it to work after many attempts. Hopefully with the latest updates I can return to this project and get it to work better. 
Right now this is not a working version. 

You can find the original source here: https://github.com/SensiLab/sensilab-ar-sandbox

I've included Sensilabs original Readme below if you want to know more about this very cool program. 





# SensiLab AR Sandbox
![SensiLab AR Sandbox](https://sensilab.monash.edu/new-sensilab/wp-content/uploads/2018/06/43I5615.jpg)
This project is a from-scratch Unity rebuild and extension of the AR Sandbox project developed by the [KeckCAVES group at UC Davis](https://web.cs.ucdavis.edu/~okreylos/ResDev/SARndbox/)

The new version was developed in [SensiLab](https://sensilab.monash.edu) at Monash University, Melbourne, Australia

Updates include:
* Rebuilt in Unity for faster iteration of new features
* Use of the Windows Kinect SDK for support of newer Kinect hardware (Kinect 2)
* Updated Water simulations
* Fire simulations
* Wind simulations
* Complex Geology simulations
* Ability to save, recall and export topologies
* Various configuration options
* Support for a secondary touch screen

 ## Requirements
 * Windows 7 or newer
 * Unity 2017.4.X (last developed version, project can be updated)
 * Kinect 2
 * Kinect for Windows SDK (available [here](https://www.microsoft.com/en-au/download/details.aspx?id=44561))

## License
GNU General Public License v3.0 or later

See [COPYING](COPYING) to see the full text
