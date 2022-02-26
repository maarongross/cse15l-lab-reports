# Lab 4 Report
- Here is a [link](https://github.com/ezhou413/markdown-parse) to my group's markdown-parse repo.
- Here is a [link](https://github.com/sm52/markdown-parse) to the group's markdown-parse repo whom we reviewed.
## Snippet 1 Test File Preview
![Image](snippet1 preview.png)
## Snippet 2 Test File Preview
![Image](snippet2 preview.png)
## Snippet 3 Test File Preview
![Image](snippet3 preview.png)
## MarkdownParseTest.java
![Image](markdownparsetest.png)
## Testing Our Implementation
- Our code failed all three tests.
![Image](testing our implementation.png)
## Testing Their Implementation
- The code that my lab group reviewed also failed all three tests.
![Image](testing their implementation.png)
## How We Should Fix our Code
- For the first snippet, our code needs to have a way to check for inline backticks. This could be done quite easily by just checking for the back ticks before or after the link, since back ticks that are in the link do not seem to work according to the preview for snippet 1.