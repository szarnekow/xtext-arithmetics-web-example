# xtext-arithmetics-web-example
Web integration for the Xtext arithmetics example

Clone and use Gradle tasks to

  - jettyRun - run the web server locally on port 8080
  - eclipse - setup Eclipse project data

Example file content:

```
module test
def fun(a,b) : a * b;
fun(2, fun(3,4)) / (1-2+3);
```
