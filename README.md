# Android Skeleton

This is a simple Android app skeleton using a kind of MVVM architecture.

```
project
│   README.md
│
└───src.main.java.com.kth
│   └───ui
│       │   Activities(.kt)
│       └───[home] <--- depend on user story 
│           │   ViewModels(.kt)
│           │   Fragments(.kt)
│   └───data
│       │   Repositories(.kt)
│   └───model
│       │   Objects(.kt)
```

###Libraries

- _Timber_

### Clone it - Use it

Use some google research or anything if you clone it in order to rename it as u want. 

For me a simple way to do this (and which did the trick) was to : 

1. Close AS/IntelliJ & rename the project folder
2. Delete **.idea** folder & **.iml** file (**WARNING :** Those can be hidden)
3. Open **settings.gradle** and change _rootProject.name_ property to your new project name.
4. Open AS/IntelliJ, Gradle sync and Enjoy ! :-)

