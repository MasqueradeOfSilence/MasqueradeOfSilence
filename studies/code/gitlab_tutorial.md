[<< Back to STUDIES.md](../../STUDIES.md)
# Gitlab Tutorial: Write-Up

As part of a ticket at work, I needed to learn more about CI/CD. Since we use Gitlab, I thought I would go through a quick tutorial that reviewed the basics of Gitlab and then talked about CI/CD in that context. 

I found [this tutorial](https://www.tutorialspoint.com/gitlab/index.htm) on Tutorialspoint and decided to do it. At first, the tutorial went well. However, it gradually got more obfuscated. I found sections that expected you to have set up your own GitLab server, despite the tutorial only showing you how to use the default Gitlab SaaS server (which, as I found out after quite a few hours of searching, does not allow you to SSH into the server). And it didn't specify that you needed to set up your own local server to get SSH working; it had no steps on how to do that -- it simply jumped into "let's SSH into the server!" with no additional details as to how. It seems like it's missing an entire section. Furthermore, partway through the tutorial, I found that some pages stopped redirecting you to the correct place, and instead redirected to plain HTML pages of the tutorial that didn't have any of the CSS rendered for some reason. By this point, if I hadn't gotten so far along, I would've switched tutorials. 

In short, I was not particularly impressed, and I probably won't be using Tutorialspoint in the future. This tutorial was not well-written. It was good enough to remind myself of the basics, though. It's titled as though it's perfectly suited for absolute beginners, and it simply isn't. 

I just ended up reading anything that involved setting up my own server or using a public repository instead of actually going through it (I made mine private at the beginning because the tutorial did not specify what to do, and then later found out that it would be working with public features). With everything else, though, I followed along. 

# Links
- [Repository (private repo, on Gitlab itself)](https://gitlab.com/alexcn711/testproject)
