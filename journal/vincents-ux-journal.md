<div align="center">
    <h1>Checking Out YouTube’s Video Playing UX</h1>
    <p>Vincent Roberson</p>
    <p>2025-11-10</p>
</div>

<hr>

So I went ahead and opened up a YouTube video, like I usually do when I’m bored. This time, for some reason, I was feeling like checking out a little Ted Talk. The one I picked happened to be “How to learn any language in six months,” by Chris Lonsdale. Though, instead of going ahead and watching the video, after I clicked on the video, I decided to pause it and appreciate YouTube’s UX.

<div align="center">
    <img src="/portfolio-bincent0929/assets/first-journal-images/initial-video-page.png" style="max-width: 500px; width: 100%;">
    <p>This is what I was greeted with when I clicked on the video.</p>
</div>

As you can see in the image below the header, the video is featured on the left-hand side of the screen; with recommended videos on the right hand side of the screen, and more information about the video just below the video. In terms of the **visual hierarchy** of the page –––which elements are highlighted vs. less highlighted––– the video player seems to be most prominent, yet takes up less area of the page than the other elements combined.

After giving the UI a little look over, I decided to unpause the video, and shortly after, I was thinking that there has to be a way to get the video to be more prominent on my screen. To make it the primary visual element on the page. Maybe I could get it into fullscreen or maybe another choice that allows me to still interact with other elements on the page if I move away from the video.

So I went ahead and hovered over the video, and was greeted with the updated page below.

<div align="center">
    <img src="/portfolio-bincent0929/assets/first-journal-images/on-hover-and-theater.png" style="max-width: 500px; width: 100%;">
    <p>When you hover over the image, you are greeted with a multitude of options to change the behavior of the video.</p>
</div>

Ok, I actually did a little more than hover over the video— I actually also pressed the theater mode button (or pressed “t,” for theater) to enlarge the video, in addition to hovering over the video. Which is actually what I was alluding to before I hovered over the video.

In this hovered and enlarged state, the watcher is presented with a multitude of choices to change their video viewing experience. The obvious possible choices, including, play/pause, volume adjustment, seeking through the video, a fullscreen toggle, and a captions toggle were all present. All stuff a user would conventionally find on basically any video player on their computer. Thanks to this, YouTube's video player perfectly fits the **mental model** (what a user expects based on their previous experiences) of anyone that has watched a video using a computer before. Additionally, YouTube has a few extras that would be outside of the mental mode of the typical user. Which includes things like theater mode ---which I mentioned before--- with its very unique icon, the autoplay button ---which plays a video right after the current one finishes--- and then the gear icon that allows you to change various other aspects about how the video is played, like video quality. I will talk about the latter more later in this journal.

In my opinion, I think that the theater icon is a little ambiguous for new users, it doesn't have a strong **affordance** for the user. By "affordance" I mean the implicit usefulness of the, in this case, icon on the screen. You could assume that maybe the icon stretches the video player in some way with the arrows pointing two directions, but I would still say it's not very obvious. With the autoplay button, it's easy to learn what it does as a user because YouTube forces it on for you when you start to use the site. Making you as the user try to scramble to figure out why YouTube keeps playing stuff after you've finished watching your video, and eventually leads you to find the button for it.

In a more natural way, like with the standard icons on the player, the gear icon is something that a user may assume allows you to change the “settings” of the video, thanks to their mental model of what gear icons allow you to do in software programs. And, as you might've assumed, when you click on it, you’re presented with the options in the image below.

<div align="center">
    <img src="/portfolio-bincent0929/assets/first-journal-images/video-settings.png" style="max-width: 500px; width: 100%;">
    <p>With the changes to the video including, subtitles, playback speed, quality, and more, as the image shows.</p>
</div>

The playback quality is pretty standard for internet video players. I would say the same for changing the playback speed and subtitles, but relative to software video players more broadly rather than just purely internet players.

It does look like YouTube has a few extra things that most other internet and/or software video players don’t have. For example, I am honestly not really familiar with what ambient mode does. That’s new to me. And I can't really tell what it does from looking at the icon. Which makes me comfortably say that it has a low affordance for the user. 

Whereas, I can guess that “Stable Volume” may reduce peaking in the video and make the audio nicer if it was mixed poorly by the videographer. Similarly with the “Sleep timer,” it's pretty straight forward what the button does. It makes the video stop, or "sleep," after a certain amount of time.

For annotations, I’m only familiar with it because I have used YouTube a lot— it’s used for allowing or disallowing info elements being written over the video player. Though, I feel like as a new user, it’d be kind of hard to understand what this does unless you went ahead and turned it off and then appreciated what was missing when it was off vs. when you had it on. Leading me to say it has a pretty low affordance.

After getting the video all tuned up and playing like I like, I wanted to get a better idea of some background of the video while I listened. So I decided to scroll down to engage a little bit with the video, and I was presented with the below portion of the page.

<div align="center">
    <img src="/portfolio-bincent0929/assets/first-journal-images/video-description.png" style="max-width: 500px; width: 100%;">
    <p>Here’s most of the description of the video (below is just socials for the channel and a YouTube-generated transcript from the captions)</p>
</div>

Just below the video gives you some date and viewing information about the video, and then expands into a full description of the video, as posted by the channel that uploaded it.

This is relatively new, but just below the description, it’s apparent that YouTube pulls “Key moments” from the video. Which was kind of funny, because, in the hovered state of the video, in the first picture of my journal, there were no timestamps placed by the makers of the video. So, it seems that these are auto-generated by YouTube— at least as a user, myself, I’m assuming that. But, overall, the “Key moments” section is very clear and easy to follow as a user in terms of its usefulness in helping me parse the video **efficiently**. By "efficiently", in terms of UX terminology, I mean that it helps me, as a user, accomplish my goal quickly.

Finally, I scrolled just pasted the description box of the video, and was greeted with a comment section. The top of which can be seen in the image below.

<div align="center">
    <img src="/portfolio-bincent0929/assets/first-journal-images/video-comments.png" style="max-width: 500px; width: 100%;">
    <p>I didn’t want to show any actual comments, just in case they were crazy.</p>
</div>

Clearly, it has a super simple layout. It tells you how many comments there are, you can sort through and see what people have said, and it has an indicator of where you can add a comment with “Add a comment…” and an underline below it standing as a **call-to-action** for the user to comment on the page. "Call-to-action" may be pretty, but I'll go ahead and define it for UX more specifically. Basically, a "call-to-action" in software is a call for the user to act in a certain way to produce an outcome that the creator of the application may desire.

Now that I have looked through a little bit about the video, I decided to go back and really watch the video, and, after a while, I finished watching it. I now know how I can learn Russian quickly to say hello to someone in St. Petersburg!

After the video was over, I was still bored, and took myself out of theater mode and looked back at what I could tell were more videos on the right hand side of the page. The thumbnails **effectively** (enabled me as a user of the site to accomplish my goal) helped me to get an idea of what the video looked like, and the titles in combination with them, helped me to get an idea of what they were about.

<div align="center">
    <img src="/portfolio-bincent0929/assets/first-journal-images/video-suggestions.png" style="max-width: 500px; width: 100%;">
    <p>The recommended videos from the first image in my journal.</p>
</div>

I decided to pick the video with the most views. If everyone else wants to hear about what the guy is saying, why shouldn’t I?

And then the **user flow** (how the user iteratively interacts with the program) of YouTube continues for its users until the user decides to close the site...