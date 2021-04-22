## Ants Application

This repository contains code for the [Ants Project][ants]
from the UC Berkeley CS61a course.

### What to Do

1. Complete the code for [Ants Vs. SomeBees][ants] as described at the link.

2. [Test your code](#test-your-code) frequently.

3. [Save and submit your work](#save-and-submit-your-work-using-git) regularly using Git -- do this everytime you work on something, not just when you finish the assignment.

### Test Your Code

Use the `ok` program included with the code to test your program, as described in the [Ants assignment][ants].
You should gradually work on this project in phases and use `ok` to check your work.  
You should *not* submit your work to `ok` grader; thus, you should add the `--local` option at each command, e.g.,
for Problem 0, you should call:
    ```
    python3 ok -q 00 -u --local
    ```
and for Problem 1, you should call
    ```
    python3 ok -q 01 -u --local
    ```
to check your understanding and then, after you finish writing code, you should call
    ```
    python3 ok -q 01 --local
    ```

### Save and Submit Your Work Using Git

Use Git to regularly add work to your local repository and then send it to Github.  This is a good software development practice and protects you from losing work.

The commands are:

1. Check what files you have changed:
   ```
   git status

   Modified files:
      ants.py
      .ok_history
   ```
2. Use `git add` to tell git you want to save the modified files or add new files:
   ```
   git add ants.py .ok_history
   ```
3. Commit the files to your local repository:
   ```
   git commit -m "write a message describing what work you did"
   ```
   Or, combine step 2 and step 3 into one command:
   ```
   git commit -am "write a message describing what work you did"
   ```
4. Copy your local repository updates to Github:
   ```
   git push
   ```
5. Visit your repository on Github to verify your new work is there!

### What to Submit

You should "push" (upload) your code to Github.

You can "push" your code many times until the project deadline.

### Git

You need the "git" client program on your computer
and added to your environment's PATH.

Get Git from <https://git-scm.com/downloads>.

[ants]: https://cs61a.org/proj/ants/
