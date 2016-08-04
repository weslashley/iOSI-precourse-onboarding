---
title: Swift Programming for Non-Programmers Guide
creator:
    name: Julie Arditti, Jeff Boykin
    city: NYC
---

# ![](https://ga-dash.s3.amazonaws.com/production/assets/logo-9f88ae6c9c3871690e33280fcf557f33.png) Swift for Non-Programmers Reading Guide

This reading guide provides guiding questions and resources for the first 3 weeks of material.  If you are new to programming or need some extra help with iOS course topics, then this is the guide for you! 

We recommended using this guide as a supplement to course activities. If a topic is unclear, find it in this guide and read up on it using some of the resources recommended here. You'll also see we've provided some guiding questions. As you read through these sources, keep the guiding questions in mind, then check if you can find the answers!

> Instructors: This supplemental guide is inteneded to support new programmers through the first 3 weeks of course materials. Feel free to add to this guide with additional suggestions!

## What's Included In This Guide?
| WEEK   | TOPICS  |
| :---: | --- |
| [Week 1](#week1) | Views, View Controllers, Command Line, Git/Github, Data Types + Values, Variables + Constants, & Control Flow |
| [Week 2](#week2)  | Functions, Data Structure: Arrays + Dictionaries, Optionals, Classes + Objects, Object-Oriented Programming, & IBOutlets/IBActions |
| [Week 3](#week3)  | Table Views, Passing Data, & Debugging Fundamentals in Xcode |

---

<a name="week1"></a>
## Week 1

### Views

Here is an introduction to building code-less UI in Xcode's Interface Builder.

1. [Check Apple's reference docs for the `UIView` Class](https://developer.apple.com/library/ios/documentation/UIKit/Reference/UIView_Class/index.html). This resource gives an overview of the `UIView` class, including how to create a view, the view drawing cycle, and animations. After this reading, you should be able to answer the following question:
 - *What is a view in the context of an iOS app?*

1. [Discover Spring+Struts and Auto Layout with theswiftdev.com](https://theswiftdev.com/2016/05/17/from-springs-and-struts-to-autolayout-and-anchors/). This resource describes Spring+Struts and Auto Layout. After this, you'll be able to answer the following questions:
 - *What's the difference between Springs+Struts layout method and Auto Layout?*
 - *How do you set the proper springs and struts for the desired layouts?*

1. [Learn how to add Image Assets with codepath.com](http://guides.codepath.com/ios/Adding-Image-Assets). This resource walks you through how to add an asset to a project, step by step. After this, you'll be able to answer the following questions:
 - *How do you add images to the media library?*
 - *How do you use those images in UIImagesViews?*


### View Controllers

This is the default, built-in navigation paradigm for iOS apps.

1. [Segue between Swift View Controllers with codingexplorer.com](http://www.codingexplorer.com/segue-swift-view-controllers/). This resource explains how to set up storyboards, wire the segues, and write the view controllers. After this reading you should be able to answer the following questions:
 - *How is Scene/View Controller used in an iOS app?*
 - *How do you add View Controllers of the same or different types to a Storyboard?*
 - *How to embed a View Controller in a UINavigationController?*


### Command Line

The command line gives you access to a multitude of developer tools and serves as the primary interface for quickly navigating files and operating source control systems like Git.

1. [Try "Learn the Command Line the Hard Way"!](http://cli.learncodethehardway.org/book/). This series of exercises will familiarize and get you comfortable with intermediate command line skills. After reading this, you should be able to answer the following question:
 - *How can we use the command line to quickly navigate, create, and edit files on our computer?*

### Git/Github

Source control is a fundamental skill for **all** professional developers.

1. [Learn the basics of Github with rogerdudler](http://rogerdudler.github.io/git-guide/). This is a humorous and simple guide that describes the basics of git and how it controls workflow. After this reading, you should be able to answer the following questions:
 - *How do you make a clone an existing repository?*
 - *How do you pull updates from a repository?*
 - *How do you push a repository and a commit to github?*

**Bonus Resource!**: [Git & Github Video Tutorial Series on Youtube](https://www.youtube.com/playlist?list=PLg7s6cbtAD15G8lNyoaYDuKZSKyJrgwB-).

### Data Types and Values

Data types and values are the foundations for understanding and storing data.

1. [Discovr Swift Data Types with tutorialspoint.com](http://www.tutorialspoint.com/swift/swift_data_types.htm). This resource gives an overview of Swift's basic data types. After reading this guide, you should be able to answer the following question:
 - *What are swifts basic data types and their properties?*

### Variables and Constants

Understanding how to use variables and constants allows you to create safer and more elegant code.

1. [Learn Swift Variables from tutorialspoint.com](http://www.tutorialspoint.com/swift/swift_variables.htm) and [check out Swift Constants also from tutorialspoint.com](http://www.tutorialspoint.com/swift/swift_constants.htm). These resources give you an overview of what variables and constants are, while describing how to declare and name them. After these resources, you should be able to answer the following questions:
 - *When should you use a variable and when should you use a constant?*
 - *How do you assign new values to variables already declared and initialized?*
 - *How does using type annotation allow you to declare variables and constants with explicit typing as opposed to implicit?*

### Control Flow

The term "control flow" describes all of the logical decision-making (e.g. *conditionals*) and automation (i.e. types of *loops*) in one's code. Control flow patterns are used no matter what language you are programming in!

1. [Read up on Swift Loops, Switch Statements, and Ranges in codingexplorer.com](http://www.codingexplorer.com/loops-switch-statements-ranges-swift/). This resource describes some different methods of control flow, including `while` loops, `for-in` loops, `if` statements and `switch` statements. After reading this, you should be able to answer the following questions:
 - *How do if/else statements and switch/case conditionals control the flow of our program?*
 - *How can we use for/while loops to repeat a segment of code?*
 
1. Focus on the ["Logical Operators" and "Comparison Operators" sections](http://www.codingexplorer.com/loops-switch-statements-ranges-swift/) and try answering this question: 
 - *How can we use comparison operators (+, -, =) and boolean operators (!, &&, ||) to create comparison expressions?*

**Bonus Resource!**: [Read up on Control Flow in Apple's developer docs](https://developer.apple.com/library/ios/documentation/Swift/Conceptual/Swift_Programming_Language/ControlFlow.html).


<a name="week2"></a>
## Week 2

### Functions

The `function` is a foundational component of modern programming. Functions allow us to reuse code and break our program into discrete, sequential steps.

1. [Review functions on weheartswift.com](https://www.weheartswift.com/functions/). Read through the intro for this resource to learn about defining and calling the various types of functions. After reading this, you should be able to answer the following questions:
 - *How are parameters used in functions?*
 - *How do you write a function that returns values?*

1. Skip to the ["Nested Functions" section](https://www.weheartswift.com/functions/) and try to answer this question: 
 - *What is function scope?*
 - *How can functions call and return other functions?*

1. [Review Recursion from weheartwift.com](https://www.weheartswift.com/recursion/). Focus on the intro section of this resource, which explains the idea of "recursion" through various examples. After reading, you should be able to answer the following question:
 - *What is recursion?*
 - *Why is this a practical concept in programming?*

**Bonus resource!**: [Look through Apple's Developer docs on Functions](https://developer.apple.com/library/ios/documentation/Swift/Conceptual/Swift_Programming_Language/Functions.html).

### Data Structures

#### Arrays

Arrays are a type of data structure that store an ordered series of values.

1. [Read this Array Reference Guide for Swift from learnswiftonline.com](http://www.learnswiftonline.com/reference-guides/array-reference-guide-for-swift/). This resource gives an overview of arrays and how values can be removed, changed, added, and retrieved from them. After this reading you should be able to answer the following questions:
 - *What are basic operations you can perform on an array?*
 - *How do you build an array?*

#### Dictionaries

Dictionaries store and organize data based on keys, as opposed to indexes.

1. [Review Dictionaries from weheartswift.com](https://www.weheartswift.com/dictionaries/). This resource defines dictionaries and explains some methods of manipulating them. After reading this, you should be able to answer the following questions:
 - *What are dictionaries?*
 - *How do you add and read values from dictionaries?*
 - *When would we use dictionaries over arrays?*

#### Optionals

Optionals are a Swift-specific way to include some limited ambiguity by letting variables have a value of `nil`. Normally, Swift doesn't allow `nil` in order to avoid ambiguity and promote safe code, but optionals can be useful! 

1. [Read up on Swift Optionals from Touch Code Magazine](http://www.touch-code-magazine.com/swift-optionals-use-let/). This resource explains what Optional types are and how to use them. After reading this, you should be able to answer the following questions:
 - *Why are optionals needed?*
 - *How do you declare variables and constants that contain Optional types?*
 - *What's the difference between `?` and `!?`*

### Classes and Objects

Classes and objects are the foundation of object-oriented programming, while "subclassing" is fundamental to data model design and using iOS frameworks.

1. [Read about Swift Property Observers from codingexplorer.com](http://www.codingexplorer.com/swift-property-observers/). This explains property observers and how to implement them. After this resource, you'll be able to answer the following question:
 - How are `get`, `set`, `willSet`, and `didSet` used?

1. [Review Inheritance from tutorialspoint.com](http://www.tutorialspoint.com/swift/swift_inheritance.htm). This gives an overview of inheritence including sub-class, super-class and overriding. After reading this, you should be able to answer the following questions:
 - *How do classes and instances of classes relate?*
 - *How do the keywords `super` and `self` contrast?*

1. [Check out "Swift Programming 101: Inheritance & Polymorphism" from iphonelife.com](http://www.iphonelife.com/blog/31369/swift-programming-101-inheritance-polymorphism). Skip to the section titled "Polymorphism," which explains what polymorphism is and how to convert types with type casting. After reading this, you should be able to answer the following question:
 - *What is polymorphism?*

### Object-Oriented Programming

Knowing the best practices and patterns around objects is a necessary skill for professional developers.

1. [Watch this Model View Controller Video from youtube](https://www.youtube.com/watch?v=Y09RvzZ1mY8). This video is a 9 minute introduction to MVC. After watching this, you should be able to answer the following question:
 - *What is MVC and how are iOS applications based on this design pattern?*

1. [Review this guide to Swift Delegates from useyourloaf.com](http://useyourloaf.com/blog/quick-guide-to-swift-delegates/). This explains how to create, add, and implement a `delegate` property. After reading this, you should be able to answer the following question:
 - *What are delegates?*
 - *How should they be used?*

**Bonus Resource**: [Read up on Model-View-Controllers from Apple's Developer Docs](https://developer.apple.com/library/mac/documentation/General/Conceptual/DevPedia-CocoaCore/MVC.html). Skip to the "Model Objects" section for this question:
 - *How do you create relationships between models?*

### IBOutlets/IBActions

These connect the raw Swift we've been learning to the UI we created at the beginning of the course.

1. [`IBAction` and `IBOutlet` from "thatthinginswift.com"](https://thatthinginswift.com/ibaction-and-iboutlet/). This resource gives you a brief overview of `IBAction` and `IBOutlet`. After reading this, you should be able to answer the following question:
 - *How can you you create IBOutlets and IBActions?*

1. [Learn about `awakeFromNIB` from Apple's Dev Docs](https://developer.apple.com/reference/objectivec/nsobject/1402907-awakefromnib). Apple explains how to declare `awakeFromNib` and what it does. After reading this, you should be able to answer the following question:
 - *What are default methods in the `UIViewController` class?*

---

<a name="week3"></a>
## Week 3

### Table Views

Table views are one of the most common views deployed in iOS apps. It also demonstrates a necessary "design pattern" used in iOS implementation.

1. [Creating a Delegate in Swift from stephenradford.com](http://stephenradford.me/creating-a-delegate-in-swift/). This resource explains what a delegate pattern is, how it's used, and how it's called. After reading this, you should be able to answer the following question:
 - *What is a "Delegate Pattern" and how is it deployed for table views?*

1. [Learn how to create a Table View from Apple's Dev Docs](https://developer.apple.com/library/ios/referencelibrary/GettingStarted/DevelopiOSAppsSwift/Lesson7.html). Apple walks you through the process of creating a table view. After reading this, you should be able to answer the following questions:
 - *How do you create table cells with the dynamic prototype technique?*
 - *How to create `UITableViewCells` using "Reuse identifiers"?*
 - *How to create a standard `UITableViewCell` to show data?*

### Passing Data

The ability to pass data is necessary for the master/detail UI pattern. *

1. [Read about passing data between ViewControllers from jameslist.com](http://jamesleist.com/ios-swift-passing-data-between-viewcontrollers/). This resource goes through the steps of passing data between `ViewControllers`. After reading this, you should be able to answer the following questions:
 - *What is `prepareForSegue` used for?*
 - *How can you create objects from user inputs?*
 - *How do you add multiple segues to the same target view controller and populate it depending on the segue identifier?*

### Debugging fundamentals in Xcode

Finally, you should have some familiarity with tools that enable a developer to inspect running code in order to find and solve problems!

1. [Check out this "Beginning iOS Development: Debugging Fundamentals" resource from tutsplus](http://code.tutsplus.com/tutorials/beginning-ios-development-debugging-fundamentals--mobile-4463). This resource explains some of the different types of errors and debugging methods. After reading this, you should be able to answer the following questions:
 - *What kinds of errors will stop app execution?*
 - *What is a breakpoint and why is it useful?*

1. [Check out "Tracking Tasks With Stack Traces" from cocoawithlove.com](http://www.cocoawithlove.com/blog/2016/02/28/stack-traces-in-swift.html). This resource explains what "stack traces" do and why we use them. After reading this, you should be able to answer the following question:
 - *What is a stack trace?*
 - *How should they be used?*

