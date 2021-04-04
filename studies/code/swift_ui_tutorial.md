# Swift UI Tutorial: Write-Up

On April 3rd, 2021, I finished [Apple's official Swift UI tutorial series](https://developer.apple.com/tutorials/swiftui), thus fulfilling my goal of obtaining a fundamental overview of mobile app development for Apple before beginning to code my own apps with the intent of eventually launching them. 

This was an interesting project, building a Landmarks app for iOS, MacOS, and watchOS. I did this tutorial in order to get a basic overview of Swift and Swift UI programming, as I have wanted to learn iPhone app development (and Apple Watch development) for a very long time. 

I tend to be very obsessive about tutorials. There is something about my brain that is insistent on covering everything in a tutorial first, before starting my own projects. I would rather plan something out in advance, and execute it step-by-step in code, than haphazardly vomit stuff onto the page and beat it into submission — though, realistically, a combination of both is what’s going to happen. I think I’m just wired for sequential learning in that regard. 

While I really enjoyed the tutorial, I must admit that I started to lose focus towards the end. It is a very detailed tutorial, and demands 100% of your attention, so trying to binge-code it on a Saturday did not have the best results. The instructions say it will only take 4 to 5 hours to complete, but in my experience, it took me upwards of 15. Towards the end, I became very copy-pastey in order to finish it on time, and move on to other assignments for my classes. While I learned a ton, there were admittedly some concepts that I unintentionally ended up glazing over, simply due to fatigue with finals approaching. 

Regardless, I would still recommend this tutorial for anyone who wants to learn Swift and Swift UI. It is very thorough, and I am sure I will reference it as I begin to develop apps. Here are some tips:

- Take the quizzes at the end of each section. If you get a question wrong, it doesn't matter much, because Apple will happily explain to you the correct solution. A fair warning, it is very easy to get mobile stuff working while glazing over the programmatic concepts that underlie mobile architecture, even when taking these quizzes. I know I struggled with that. Regardless, often the best understanding comes with time. 
- Sometimes your previews will stop working. First, restart Xcode. If that doesn't work, check your build targets, they may be wrong. 
- If you have two classes with the same name, that are both selecting for the same build target, there will be blood. You can change the name of one of the classes, but this may lead to further build issues. It is better to ascertain that if two classes have the exact same name, they should be aimed at different build targets. I ended up doing both -- changing targets and names -- just to be on the safe side. 
- Xcode is a powerful piece of software, but it will suck your battery life until it is an empty husk. 
- Set deadlines. It is easy to get distracted when following a tutorial. 
- This tutorial series is *strongly* focused on the UX side of things. For example, you learn how to display an alert when a user is approaching a destination, but not the actual algorithm that computes physical distance (all the data loading is done virtually, via an APNS file). 
- If you're confused about modality, as I was, check out [this](https://uxplanet.org/modality-the-one-ux-concept-you-need-to-understand-when-designing-intuitive-user-interfaces-e5e941c7acb1). 
- Everything will take you 2-3x as long as the tutorial says it will. The Apple developers are brilliant, but not very good with time estimation. 
- Finally, don't be too concerned about trying to understand every single piece. I've struggled a lot with that in the past. However, some things simply aren't going to be understood the first time around, and if you don't realize that, you will never finish the tutorial. And do not give up. At the end, you will have a really cool cross-platform (well, cross-Apple platform) application built. 

I will probably reference this tutorial in the future. The Mac OS application module may especially be worth a revisit, as it is quite heavy-hitting at the end of a long tutorial series. 

Most importantly, don't give up! 

# Links
- [Repository](https://github.com/MasqueradeOfSilence/swiftui_tutorial)
