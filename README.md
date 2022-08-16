# #245 Error Reporting & Display
How do we know what's gone wrong with a project?

![Thumbnail Small](https://user-images.githubusercontent.com/20911308/184887223-8c8795c6-dbdf-415c-bd95-bd3dbe4c331b.png)

You've built a project. It's working. Hurrah. Now it's suddenly stopped working. What has gone wrong?

It's the perennial problem of being able to log an error, in Real Time, so that we can accurately determine where the problem lies with a project that suddenly stops working.

Is it the Wi-Fi? Out of memory? Can't read the SPIFFs partition? Or something else.

I'm designing a very small, dual 7-segment display, just like you find on certain motherboards, to indicate where the problem might be.

Using one industry-standard, 8-bit Shift Register per 7-segment display, we can easily pass a value to a common function to display an error code. I might even have to write a simple library! 😁

The circuit is based on Texas Instruments' suggested circuit (https://www.ti.com/document-viewer/SN74HCT595/datasheet/GUID-0EC2F5AE-5906-45C5-AC67-D86D0FCA8C96#GUID-CCCD2933-BF9E-4525-A4DC-F02E47379022)

![image](https://user-images.githubusercontent.com/20911308/184888743-4a3339f9-0aff-4c34-9da0-13933e73b3cc.png)
We can use SMD versions of the 74XX595 and place them on the opposite side of the PCB of the 7-segment LED. If we use a very small (0.3" or smaller) I reckon we can design something that could be easily used in any project at minimal cost.

