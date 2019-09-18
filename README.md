# Chucky-Chuck's Depressing Day---CSCI 3725 Mission 2: A Markov Distribution
# Kevin Li
Have you seen the "Sit Down Drank Stand Up Drank" meme? Well, if you haven't, here is a link: https://www.youtube.com/watch?v=mUB7t2Vat7c.

Whoooooaaa, imagine if you could use a Markov Chain to simulate a sequence like this---FOREVER. This is precisely what I did in Mission 2. I used the Unity Engine to create a lovely and handsome blue figure named Chucky-Chuck that happens to have a drinking problem. All he can do is: sleep, wake up, stand up, and drink! To make Chucky-Chuck do these "excruciating" tasks, I used Unity's animation and animator to simulate his 4 states and the transitions between them. I used Markov Chains by creating a matrix in Chucky-Chuck's component "Markov", which is connected to my code Markov.cs. The matrix has a size of 4x4, with the format of the conditional probability as "row given column". Attached is a photo of an example of the matrix. I used this matrix to determine the transitions between the states. As you can see, Chucky-Chuck is really depressed! Maybe we can lighten his mood next time......

# How to Run:
1) If you do not have the Unity Engine downloaded, please do so before running this program. (Unity 2019.2.4f1 used)
2) Download and save Markov_Chain_Kevin Li in a NON-read only part of your computer.
3) Open Unity, and open the program
4) Press "Play" to start the program
5) Notice: Comments were written in the console to display the current state. You are able to access and look at the transition between states and parameters via the Animator. If the Animator is not open, you can open it via "Window" --> "Animation" --> "Animator". To access my script "Markov.cs", go to the project folder, find "Assets", click on "Scripts", and finally, click on "Markov". "Markov.cs" was written in C# language, done entirely on Microsoft Visual Studio.



		I love playing games. I love building games. I love memes. Chucky-Chuck's Depressing Day is the best of all these worlds! I've always aspired to be a software engineer or a data scientist, but deep down, I've always had a love for expressing my creativity and thoughts through my own digital creations. This mission gave me the opportunity to not only learn how to create a Markov Chain system, but also learn how to have fun while doing it. In the two years that I've taken computer science courses, I've learned so much through rigorous practicing and learning. I've put lots of effort into becoming a better CS student, and in that process, I feel like I lost a lot of passion in CS, almost as if it was a duty. This Chucky-Chuck's Depressing Day helped me find what made me fall in love with Computer Science in the first place: The limitless possibilities computers can bring to society.
	
		Though I've had prior experience with Unity, this is my first time interacting with animations and the animation controller. I had to completely learn from scratch how the animator worked so that I could build the Markov Chain inside my Unity program. I had trouble making my "Markov.cs" script, which is used by my player Chucky-Chuck to perform actions based on the Markov Chain, but I challenged myself to understand how to express animations and transitions in  forms of the C# coding language. I challenged myself to decrease the amount of time I spend on StackOverflow looking for potential solutions, and invest more time in understanding the fundamentals of how Unity and C# work hand in hand. C# was never a language I thought I would use frequently, and it has forced me to learn my way through it. This is crucial to experience because I will also be learning a lot of new knowledge after I graduate from college, and I should learn to be capable of learning and adapting to new things.
		
		I believe Chucky-Chuck's Depressing Day is creative because it satisfies all three(or two) characteristics of computational creativity. First, it has novelty. Have you ever seen a Markov Chain system made in the Unity Engine? Have you ever seen a Markov Chain system portraying a sad, blue man? I think not. Second, it has value. Did you laugh when you saw this? Most likely. If you didn't, your face deserves to be put on Chucky-Chuck instead. Chucky-Chuck's Depressing Day makes people LAUGH. It's crucial to be able to have fun sometimes, even if you're very busy over a project. Last, it has intentionality. I created Chucky-Chuck to get some laughs. My friends and family loved him. I consider that my intentions of creating a fun figure everyone can laugh about have been satisfied.
		
		I hope you can enjoy Chucky-Chuck's Depressing Day as much as I did! Thanks for your time!

# External Sources:
https://stackoverflow.com/

https://www.youtube.com/watch?v=mUB7t2Vat7c
