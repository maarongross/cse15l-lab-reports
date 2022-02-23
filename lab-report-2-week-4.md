# Lab 2 Report
## First Example
![Image](lab 2 code change 1.png)
- Here is a [link](https://github.com/maarongross/markdown-parse/blob/main/test-file-new.md) to the test file that caused my group to make this change.
- Here is the symptom that was caused by this faulty input.
- ![Image](lab 2 bad output 1.png)
- The output above printed a blank list, which is not what we wanted from our program. This was due to the structure of our test file, which consisted of a link, an image, and then another link, which made our program unable to read the entire file. With the change that we made, we are now able to print the desired output, which consists of two links instead of the bad output shown in the image.
## Second Example
![Image](lab 2 code change 2.png)
- Here is a [link](https://github.com/ezhou413/markdown-parse/blob/main/broken-test-file.md) to the test file that caused my group to make this change.
- Here is the symptom that was caused by this faulty input.
- ![Image](lab 2 bad output 2.png)
- The test file that we used caused an infinite loop in the MarkdownParse.java file. Our updated MarkdownParse.java file now is able to stop this from happening since the variable currentIndex is always incremented for every loop iteration, so the program now cannot loop infinitely.
## Third Example
![Image](lab 2 code change 3.png)
- Here is a [link](https://github.com/wross3150/markdown-parse/blob/main/test-file2.md) to the test file that caused my group to make this change.
- Here is the symptom that was caused by this faulty input.
- ![Image](lab 2 bad output 3.png)
- The output here fails the test that we provided in our MarkdownParseTest.java file, so we made a new test that is made to specifically test that type of file's contents. The file then passed our new test since we could now accommodate for said type of file.