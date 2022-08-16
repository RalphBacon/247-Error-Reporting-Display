# #245 Error Reporting & Display
### How do we know what's gone wrong with a project?

![Thumbnail Small](https://user-images.githubusercontent.com/20911308/184887223-8c8795c6-dbdf-415c-bd95-bd3dbe4c331b.png)  

![PCBWayLogo](https://user-images.githubusercontent.com/20911308/184890742-6d550514-33f2-442d-b13e-7705d7256abe.png)  

### You've built a project. It's working. Hurrah. Now it's suddenly stopped working. What has gone wrong?  

It's the perennial problem of being able to log an error, in Real Time, so that we can accurately determine where the problem lies with a project that suddenly stops working.

Is it the Wi-Fi? Out of memory? Can't read the SPIFFs partition? Or something else.

I'm designing a very small, dual 7-segment display, just like you find on certain motherboards, to indicate where the problem might be.

Using one industry-standard, 8-bit Shift Register per 7-segment display, we can easily pass a value to a common function to display an error code. I might even have to write a simple library! 😁

► The circuit is based on this Texas Instruments' suggested circuit:
![image](https://user-images.githubusercontent.com/20911308/184888743-4a3339f9-0aff-4c34-9da0-13933e73b3cc.png)  

We can use SMD versions of the 74XX595 and place them on the opposite side of the PCB of the 7-segment LED. If we use a very small (0.3" or smaller) I reckon we can design something that could be easily used in any project at minimal cost.

► List of all my videos  
(Special thanks to Michael Kurt Vogel for compiling this)  
http://bit.ly/YouTubeVideoList-RalphBacon  

► If you like this video please give it a thumbs up, share it and if you're not already subscribed please consider doing so and joining me on my Arduinite (and other μControllers) journey  

My channel, GitHub and blog are here:    
\------------------------------------------------------------------  
• https://www.youtube.com/RalphBacon  
• https://ralphbacon.blog  
• https://github.com/RalphBacon  
• https://buymeacoffee.com/ralphbacon  
\------------------------------------------------------------------  

My ABOUT page with email address: https://www.youtube.com/c/RalphBacon/about  
