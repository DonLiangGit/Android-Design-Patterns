Android-Design-Patterns
=======================

Welcome to `Commit` changes directly, or just tell me [Here](https://github.com/DonLiangGit/Android-Design-Patterns/issues/1).
Hope you guys could bring or get something related to Android Design Pattern when developing Android Application.

### MV* for more complete Android Apps.
MVP Architecture Introduction [Link1](http://www.360doc.com/content/10/0225/18/867320_16805936.shtml)
[Link2](http://www.360doc.com/content/12/0405/13/8101845_201083284.shtml)
- View <-> Presenter: using [MEDIATOR](http://www.tutorialspoint.com/design_pattern/mediator_pattern.htm) pattern to loose the coupling between classes.
- Presenter -> Model: using [COMMAND](http://www.tutorialspoint.com/design_pattern/command_pattern.htm) pattern to decide the data manipulation on objects.

### Gang of Four Patterns in Android:
| Name                  | Example                 | Link  | Details |
| -------------         |:-------------:          | -----:| -----:
| Composite Pattern     | View/ViewGroup          | [Basic](http://javapapers.com/design-patterns/composite-design-pattern/)|
| Adapter Pattern       | Adapter in ListView     | [Basic](http://javapapers.com/design-patterns/adapter-pattern/)|
| Observer Pattern      | Listener in Button      | [Basic](http://shmilyaw-hotmail-com.iteye.com/blog/1557835)|
| MVC Pattern           | ListActivity            | |
| MVVM Pattern          |                         |
| Facade Pattern        | Android Media Framework |
| Bridge Pattern        | AdapterView/Adapter     |
| Factory Method        |                  | [Basic](http://javapapers.com/design-patterns/factory-method-pattern/)
| Template Pattern      |                         |
| Decorator Pattern     |                         |
| Singleton Pattern     | InputMethodManager      |


### Unique Patterns in Android:
| Name                    | Type              | Use                   | Link  | Advanced Link   |
| ----                    | ----              | :----:                | -----:|:------:         |
| ViewHolder Pattern      | Layout Performance| ListView Optimization |[Basic] (http://developer.android.com/training/improving-layouts/smooth-scrolling.html)
| Multithreading Pattern  | Layout Performance| UI thread Performance |[Basic] (http://developer.android.com/training/improving-layouts/smooth-scrolling.html)|[.1](http://www.androiddesignpatterns.com/2014/01/thread-scheduling-in-android.html) [.2](http://www.androiddesignpatterns.com/2012/07/loaders-and-loadermanager-background.html)
| Layout-Hierachy Pattern | Layout Performance| XML Layout            |[Basic] (http://developer.android.com/training/improving-layouts/optimizing-layout.html)
| Viewstub Pattern        | Layout Performance| XML Layout/Reduce Mem |[Basic] (http://developer.android.com/training/improving-layouts/loading-ondemand.html)
| Tag Pattern             | Layout Performance| Re-usable components  |[Basic] (http://developer.android.com/training/improving-layouts/reusing-layouts.html)


