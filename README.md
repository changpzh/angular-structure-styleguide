# Angular Structure Guide
A style guide for structuring modular angular applications

## Quick intro
In most angular applications the complexity of the code grows fairly rapidely. Having no strategy leads to bulky controllers and fragmented components. One way to battle this is by splitting up code over multiple files, but it shouldn't end there. This paper answers the question '**where to put your code**' and introduces an architectual schema that is designed to eliminate code complexity.

*The below image is a quick look at how the code will be structured using this schema.*
![Overview](https://raw.githubusercontent.com/kevinvanhove/angular-structure-styleguide/master/documentation/overview.png)

## applicationPath

Combining the modulePath, pagePath and scopePath gives you the applicationPath. This allows you to document certain areas or locations in your app. It makes it also easier to send other developer to a certain location in your app... work in progress...

![Overview](https://raw.githubusercontent.com/kevinvanhove/angular-structure-styleguide/master/documentation/overview2.png)
