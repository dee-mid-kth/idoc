Run this in terminal on the macs to update the startpage.



defaults write com.apple.Safari HomePage "https://dee-mid-kth.github.io/idoc/"
defaults write com.apple.Safari HomePageURL "https://dee-mid-kth.github.io/idoc/"
defaults write com.apple.Safari NSQuitAlwaysKeepsWindows -bool false
defaults write com.apple.Safari AlwaysRestoreSessionAtLaunch -bool false
defaults write com.apple.Safari OpenPrivateWindowWhenNotRestoringSession -bool false
killall Safari
