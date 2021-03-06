# Code Snippet Studio

Code Snippet Studio is an application that makes it easy to create, edit, package, and share IntelliSense code snippets for **Visual Studio 2015** and **Visual Studio Code**. For C# and Visual Basic snippets, it also provides live [Roslyn](https://github.com/dotnet/roslyn) code analysis as you type to immediately detect code issues.

![Code Snippet Studio](http://www.visual-basic.it/Portals/0/Contents/thumb/CodeSnippetStudio.jpg)

[Getting Started Guide](https://github.com/AlessandroDelSole/CodeSnippetStudio/blob/master/CodeSnippetStudio_StandAlone/Assets/Code_Snippet_Studio_User_Guide.pdf)

With Code Snippet Studio, you have a fully-functional code editor with syntax highlighting, basic IntelliSense, and live code issue detection as you type, where you can write or paste your snippets and supply the information that is required by the respective schema references. Studio will generate the proper .snippet or .json files for you, depending on the target IDE (Visual Studio or Code). You will then be able to package a number of code snippets into a Visual Studio extension by building .vsix packages that you can share with other developers and that you can even publish to the Visual Studio Gallery! Additional tools are available to work with both .vsix and .vsi installers.

Code Snippet Studio is available both as a [stand-alone WPF application](https://codesnippetstudio.codeplex.com/downloads/get/clickOnce/CodeSnippetStudio.application) and as an [integrated tool window for Visual Studio 2015](https://visualstudiogallery.msdn.microsoft.com/803e021c-fce2-4637-a05d-bb078cffc492).

Code Snippet Studio has been built using controls from [Syncfusion's Essential Studio for WPF (Community license)](https://www.syncfusion.com/products/communitylicense) and is built upon the [DelSole.VSIX library](https://github.com/AlessandroDelSole/delsolevsix).
