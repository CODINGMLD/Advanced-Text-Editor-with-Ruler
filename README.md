## Advanced Text Editor with Ruler

![1](https://user-images.githubusercontent.com/65526236/224259184-af1372c1-85cc-4ffa-b78d-1861470775d9.PNG)

<h2>Introduction</h2>

> About two years ago I was creating a project for university. It was a complex of five programs that were related to testing (checking knowledge I mean). One of them contained a text editor. But unfortunately, I didn't know how to do that, that's why it was very simple. So, after these two years, I decided to rewrite my program in C# .NET (initially, it was written in VB.NET) and create a new powerful text editor. You can see part of it here.

<h2>Background</h2>

> I spent a lot of time(!) searching the Internet for controls like this, but the best ones are shareware and others did not fit my needs. So, what does this control have? I tried to make it look like Microsoft Word and I think that there are some similarities. The ruler lets you change the following: left and right margins, left indent, hanging indent and right indent. You also can disable margins (their values are set to 1). You can see how it looks in the picture above.

> Also, you can add tabs by clicking on the control with the left mouse button. But it is allowed only inside the area bounded by margins. If you want to remove a tab, just drag it off from the control.

> The editor lets you use lists, underline styles, advanced char styles (you can create your own links, that are not words starting with "http://" or even "www"), OLE functionality is also available. I want to thank Oscar Londoño for his article Inserting Images into a RichTextBox Control (The OLE Way). It helped me a lot to deal with OLE. This project contains his code.

<h2>Using the Code</h2>

> You can use the code according to the CPOL.

> Projects are created as Windows Applications, but you can easily convert them into *.dll or just embed code into your project.

> Unfortunately, I removed Visual Studio 2005, so, sorry but I can't create and upload a Visual Studio 2005 project. But you can import all required files into a Visual Studio 2005 project without any problems. However, note that Visual Studio 2008 added some new namespaces (like LINQ) that Visual Studio 2005 does not "understand". Just remove them. That's all. You are ready.

<h2>Points of Interest</h2>>

> One thing that shocked me is that Microsoft has released RichTextBox 6.0! (It is distributed with Microsoft Office 2007) but... with one exception. There is no documentation about its features. All that I've found is a list of added functions. You can find it here. There are also descriptions for all released versions of RichTextBox.
