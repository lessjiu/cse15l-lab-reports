## Lab Report 4- Week 8
### More Tests

**Links to Repositories:** <br>
[MyMarkdownParseRepo](https://github.com/lessjiu/markdown-parse) <br>
[ReviewedMarkdownParseRepo](https://github.com/JessalynWang/markdown-parse)

**Previews**
- Snippet 1 should produce: ``[`google.com, google.com, ucsd.edu]``
![](prev1.png)

- Snippet 2 should produce: `[a.com, a.com(()), example.com]`
![](prev2.png)

- Snippet 3 should produce: `[https://www.twitter.com, https://ucsd-cse15l-w22.github.io/, https://cse.ucsd.edu/]`
![](prev3.png)

**Tests**
![](mdt.png)

**Outputs**
- My output: All 3 tests failed
![](myOutput.png)

- Review output: All 3 tests failed
![](reviewOutput.png)

**Questions**
1. Do you think there is a small (<10 lines) code change that will make your program work for snippet 1 and all related cases that use inline code with backticks? If yes, describe the code change. If not, describe why it would be a more involved change.

2. Do you think there is a small (<10 lines) code change that will make your program work for snippet 2 and all related cases that nest parentheses, brackets, and escaped brackets? If yes, describe the code change. If not, describe why it would be a more involved change.

3. Do you think there is a small (<10 lines) code change that will make your program work for snippet 3 and all related cases that have newlines in brackets and parentheses? If yes, describe the code change. If not, describe why it would be a more involved change.