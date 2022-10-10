# Session 02 - New Robot Projects

Whenever you want to try something new with robot programming, a new project is a good idea.

## Creating a Project

To create a robot project, you need to open the version of Visual Studio Code installed with WPILib. You then have two options. Either:
1. Click on the WPILib icon to open the WPILib Command Palette or
2. Use Ctrl+Shift+P (Cmd+Shift+P macOS) to open the Command Palette

You must then click on the option for `WPILib: Create a new project`.

You will then select these options:
- `Select a project type (Example or Template)`: `Template`
- `Select a language`: `java`
- `Select a project base`: `Timed Robot`

There are many other options besides these, but for most of our use cases, these are the options you will need, at least when getting started.

For the `Base Folder` option, this is the folder on the computer where your projects will reside. It does not contain just one project, so you can choose the same option every time you make a new project. On Windows, this will usually be the `C:\Users\username\source` directory, where `username` is your Windows account name.

For the `Project Name` option, you will provide the name of the project you are creating. You usually want to be descriptive for what your project accomplishes, but you should also avoid capital letters and spaces; spaces should be avoided because they can be difficult to work with and capital letters should be avoided because some systems (like Windows) are case-insensitive while others (like macOS and Linux) are case-sensitive. Instead of spaces, we prefer to use hyphens. For example, a project where you are testing joystick operations could be named `joystick-test`.

You should always check the `Create a new folder` option, so that your project is contained within one folder within your folder containing your other projects.

The `Team Number` field is critical to make sure your robot code works on your robot. The team number must match across:
- The robot program
- The roboRIO Image
- The Driver Station

For this field, you should set `538`.

Finally, the `Enable Desktop Support` option should be checked. By default, the application leaves it unchecked, so you'll always have to check this one. This allows for simulation of robot programs on a computer, so that you don't need robot hardware to try new things. Keep in mind that not all configurations run in the simulation tool, but many do.

When you have all of the options set, click on `Generate Project`.


## Opening a Project

When you generate a new project, you will see a pop-up to open the new project. In most cases, you will want to select the `Yes (Current Window)` option, which is the default.

The first time the project opens, you will have to wait for a build to complete. This ensures that everything is setup properly based on your selections. You will know it is complete by the `BUILD SUCCESSFUL` text in the terminal at the bottom of the window. This initial build may take some time, but it will generally be faster in the future.

When you open a project in Visual Studio Code, make sure to do it from the project's top-level directory. This will be the directory that contains the `WPILib-License.md` file, among other things. If you open a higher or lower level directory instead, the built-in tools may not work as expected.

