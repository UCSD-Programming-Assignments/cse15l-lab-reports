# Skill Demonstration #1

## Task
For the second skill demonstration, you will create a video screencast of yourself doing some tasks related to editing and debugging entirely in a remote terminal.

You should complete the following tasks, all recorded as part of your screencast:

* Show your face on a webcam and your picture ID (ideally your student ID).
* Log into your course-specific account on ieng6.
* Clone this repository: skill-demo-2-starter
* In that repository, run make test, which causes an infinite loop.
* Open the makefile using vim. Add a new rule debug-test that will run the tests using jdb instead of java. (Use the material/videos from Week 8 if you’re not sure how.)
* Use make debug-test to determine which test is causing the infinite loop. Demonstrate this by suspending the program in jdb and showing the stack trace. Say out loud in the video which test is triggering the infinite loop, and which methods in LinkedList are on the stack.
* Use jdb to show the local variables in the method/loop that was running at the time the program was suspended. Use step to move forward in the program until it reaches the same line again.
* Say out loud in the video what you think the problem is that’s causing the infinite loop.
* Exit the debugger, then open the code file LinkedList.java with vim and edit it to fix the infinite loop while still passing all the other tests.
* Re-run make test and show all the tests passing successfully.

Your video should be no longer than 10 minutes. You may need to practice it a few times to get it right and get it to under 10 minutes. It’s impossible for us to enforce that you don’t discuss the bug that causes the infinite loop, but you’ll learn more if you try to figure it out on your own.

You’re free to use any and all course notes/code/videos/labs/etc. for help, along with your prior work. Your video must be entirely your own work.

<p align = "center">
<iframe width="560" height="315" src="https://www.youtube.com/embed/kZ_LR4ihkJg" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
</p>