# Claude 3.5 Sonnet for agentic coding

URL: https://www.youtube.com/watch?v=A598ESCoC70
数値: 21
時間: 2m

- As a software engineer, I find that writing tests and fixing code usually takes much longer than writing the code itself. Our new model, Claude 3.5 Sonnet, can help write tests and fix code autonomously. We'll show you how Claude takes us from an incomplete implementation to a fully functioning one, including unit tests with minimal input from me.
- I've written a function that resizes and crops images into circles. This could be used to make sure that users on a website have profile photos that are all the same dimensions. But, there's a bug in this function. When I run it, the cropped images are still square and they've got a white background. So let's see if Claude can write tests for the expected behavior, find the error and fix it.
- For this demo, I've given Claude tools to edit files and run commands and code in a secure sandbox environment with no internet access. I tell Claude about the bug I'm seeing the path to the file where the function lives, and some instructions for what I want it to do. First, Claude chooses to open the file with the function I've written to understand the current implementation and identify some potential problems.
- Then Claude writes a test suite for us and puts it into the file I asked it to. Now, Claude's going to run those tests. Let's give it a second. And just as expected, the tests are failing due to that bug. So now Claude's going to go ahead and fix that bug for us. Here you're going to see Claude edit the function file to fix the bug.
- And now Claude's going to rerun those tests. And the tests are passing. So now if we rerun the function... look, our image no longer has that white background. Thanks, Claude.