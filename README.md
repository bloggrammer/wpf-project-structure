
# wpf-project-structure
A layout project and folder structure for WPF application using the MVVM design pattern.

#### Is there a right way to structure a WPF solution?
* [ ] Yes, absolutely*.

Building an enterprise application that is easily maintable, extenable and unit testable may often be intimitadint especially if you're new to WPF. 

WPF platform is so big and something as basic as project structure may seem overwhelming.  If you find yourself in this position, you're not alone!  Don’t let project structure prevent you from making immediate progress. 

This repo layout project and folder structure for WPF application using the MVVM design pattern.

Just to be clear, I’m not referring to application architecture in this post. I’m talking only about how you structure and manage your projects, files, resources, etc, within your Visual Studio solution.

This approach makes it fairly simple to build a WPF application that is easy to maintain, extend and unit test.

## A bit about MVVM

Model–view–viewmodel is a software structural design pattern that facilitates the separation of the development of the graphical user interface – be it via a markup language or GUI code – from the development of the business logic or back-end logic so that the view is not dependent on any specific model platform.

This pattern separates objects into three distinct groups:

| Objects        | Descriptions
| ------------- |----------------|
| Models     | **Models** hold application data. They're usually structs or simple classes.|
| ViewModels      | **ViewModels** transform model information into values that can be displayed on a view. They’re usually classes, so they can be passed around as references.      |
| Views| **Views** display visual elements and controls on the screen. They're typically subclasses of `UIView` (`window`)      |

![MVVM Design Pattern](https://community.devexpress.com/blogs/donw/image_5D163328.png)
