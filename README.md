# WhatAreTheOdds7
Fork!
override func viewDidAppear(animated: Bool) {
    super.viewDidAppear(animated)


    UIView.animateWithDuration(1.5, animations: {
        self.myFirstLabel.alpha = 1.0
        self.myFirstButton.alpha = 1.0
        self.mySecondButton.alpha = 1.0
    })
}
