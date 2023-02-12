# Arizona State University CSE 205 - Visual Studio Code JavaFX template

This is github template mean’t to help students in CSE205 at Arizona State University setup a non-modular JavaFX development environment in Visual Studio Code. 

## **Requirements**

- ### [JavaFX SDK](https://gluonhq.com/products/javafx/)

    - MacOS for *Apple Silicon(x64) and Intel(aarch64)*

    - Windows for *x64 and x84*

    - Linux for *aarch64, arm32, and x64*

- ### [Java Profile](https://vscode.dev/profile/github/e744b3bf06217f783adcd7fafdd9c3eb)(optional)

    - An optional download, but will have necessary extensions for JavaFX projects, along with some other helpful extensions I use. If you decide you don’t want to download it. You’ll need to download the following extensions:

        ### ****[Extension Pack for Java](https://marketplace.visualstudio.com/items?itemName=vscjava.vscode-java-pack)****

## Setup

### 1.) **Create the Java project**

- open the command palette and enter `Java: Create Java project...`, then select it.

- ![Screenshot 2023-02-12 at 12.05.42 AM.png](JavaFX%20in%20Visual%20Studio%20Code%20d1c52977e74b41da94056a8a0b698593/Screenshot_2023-02-12_at_12.05.42_AM.png)

- select `No build tools` in the list as the project type.

- ![Screenshot 2023-02-12 at 12.06.34 AM.png](JavaFX%20in%20Visual%20Studio%20Code%20d1c52977e74b41da94056a8a0b698593/Screenshot_2023-02-12_at_12.06.34_AM.png)

- Then name the project of the file(i.e `assignment_06`) and then select a target location where you want to store the new project.

- ![Screenshot 2023-02-12 at 12.10.13 AM.png](JavaFX%20in%20Visual%20Studio%20Code%20d1c52977e74b41da94056a8a0b698593/Screenshot_2023-02-12_at_12.10.13_AM.png)

- From here, the newly created project will open in a new Visual Studio Code window.

### 2.) Add Java SDK library dependencies

- To add JavaFX as dependencies to your project, you can simply copy all the jar files from the lib folder of your downloaded JavaFX SDK, for instance `/Users/your-user/Downloads/javafx-sdk-19/lib/` to the lib folder of your project.

- ![Screenshot 2023-02-12 at 1.07.17 AM.png](JavaFX%20in%20Visual%20Studio%20Code%20d1c52977e74b41da94056a8a0b698593/Screenshot_2023-02-12_at_1.07.17_AM.png)

- Or alternatively, under `JAVA PROJECTS`, by the `Reference Libraries` click on the `+` sign and add the reference libraries needed for the project. In the 2 picture below, I’m adding all of the reference libraries in the Java SDK download.

- ![Screenshot 2023-02-12 at 12.35.06 AM.png](JavaFX%20in%20Visual%20Studio%20Code%20d1c52977e74b41da94056a8a0b698593/Screenshot_2023-02-12_at_12.35.06_AM.png)

- ![Screenshot 2023-02-12 at 12.42.08 AM.png](JavaFX%20in%20Visual%20Studio%20Code%20d1c52977e74b41da94056a8a0b698593/Screenshot_2023-02-12_at_12.42.08_AM.png)

- you know if they downloaded correctly if you can see the file in `Reference Libraries` section under `JAVA PROJECTS`.

- ![Screenshot 2023-02-12 at 12.46.17 AM.png](JavaFX%20in%20Visual%20Studio%20Code%20d1c52977e74b41da94056a8a0b698593/Screenshot_2023-02-12_at_12.46.17_AM.png)

### 3.) From here, you have everything you need to make an JavaFX project in Visual Studio Code. Just make sure all you source files aka `.java` files are in `/src`
