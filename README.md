# CurvedTextMeshPro
A simple plugin to make curved TextMeshPro texts that follow a mathematical function specified by code.

![](https://thumbs.gfycat.com/AggravatingNarrowAbalone-size_restricted.gif)

## Getting Started
To see what the CurvedTextMeshPro plugin is able to do, start by giving it a try. Open the Unity project and then head to the Assets\CurvedTextMeshPro\Scenes folder and open the DemoScene scene. You will find three texts that have been curved to follow a circle arc, a full circle and an exponential function. You can start by investigating the scripts attached to them and playing with their parameters.

## Using it in other projects
After you have tested the sample, you would like for sure to use this plugin in a project of yours. To do this, you have just to:
* Copy the Assets\CurvedTextMeshPro folder inside the Assets folder of your Unity project;
* If you just need to write a text on a circle arc, attach the TextProOnACircle script to your TextMeshPro object and play with its parameters until you obtain the results that you need
* If you just need to write a text on a exponential function, attach the TextProOnAExp script to your TextMeshPro object and play with its parameters until you obtain the results that you need
* If you need to write a text on a custom function of yours, you have to create a script that extends the TextProOnACurve class and attach it to your TextMeshPro object

### Custom curves
As I've said, I have included in the repo already a script that follows a circle arc and an exponential function. You may have a look of the code of the classes TextProOnACircle and TextProOnAExp to see how you can create your custom classes by subclassing the main TextProOnACurve class. 

I have written lots of comments in the code to explain to you what you have to do... the only thing you need is some math expertise and some coding skills :)

## Prerequisites
If you want to use the project, you must have Unity editor installed. It has been developed and tested with Unity 2018.3.6f1.
  
## Known issues
This is an experimental project in its first version and so it is not optimized and may have some bugs.
Furthermore, in the circle text example, since I consider the characters from their central point, you may need to specify an angle a bit bigger than the one you have in mind to compensate for the external margins of the font (e.g. to have a text that makes a perfect half-circle, you have to input an angle greater than 180)

People more skilled than me are welcome to contribute to this project... to improve and expand it.

## Authors

* **Antony Vitillo (Skarredghost)** - [Blog](http://skarredghost.com) - [Company](https://ntwalkers.it) - [Patreon](https://www.patreon.com/skarredghost)

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details.

## Acknowledgments

I have developed this plugin while developing the mixed reality fitness game [HitMotion:Reloaded](https://hitmotion.games/) at my agency New Technology Walkers.

I'm releasing this for free, to be helpful for the community. I would really appreciate whatever kind of support if you use this plugin in your project: a hug, a thank you, a subscription to the newsletter of [my blog](https://skarredghost.com), a mention in the credits of your project, a collaboration proposal for your XR project, a donation of 1 million Euros on my [Patreon account](https://www.patreon.com/skarredghost), the phone number of Scarlett Johansson, etc... 

You can contact me [here](https://skarredghost.com/contact/) if you wish.

Have fun :)
