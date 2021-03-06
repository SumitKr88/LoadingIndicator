# LoadingIndicator
A lightweight simple reusable loading indicator view 

# LoadingIndicator.swift
Helps in presenting loading indicator across the application in a easy way. 

# Methods:

    - func showOnWindow(loadingIndicatorText: String? = nil)
      Usage : LoadingIndicator.sharedInstance.showOnWindow(loadingIndicatorText: "Please wait...")
        
    - func showOnController(presenter: UIViewController, loadingIndicatorText: String? = nil)
      Usage : LoadingIndicator.sharedInstance.showOnController(presenter: self, loadingIndicatorText: "Loading")
    
    - func showOnView(presenter: UIView, loadingIndicatorText: String? = nil)
      Usage : LoadingIndicator.sharedInstance.showOnView(presenter: self.customView)
    
    - func hide()
      Usage : LoadingIndicator.sharedInstance.hide()

# Installation - Manually

    - Download the repo
    - Copy the LoadingIndicator.swift into your workspace directory.
    
# Example project to demonstrate the use of loading Indicator on

    - Window(Full Screen)
    - View Controller
    - Inside any Custom View

# Having trouble ?
If you are having trouble with this project or if you find any bugs, do open a new issue and describe the problem.

# Spread the word!
Liked the project? Just give it a star ⭐️ and spread the word!

# Author/ Credits
© Sumit Kumar | @SumitKr88

# License
MIT License
