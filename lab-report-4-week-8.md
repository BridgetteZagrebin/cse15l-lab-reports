[<--Go Back](https://bridgettezagrebin.github.io/cse15l-lab-reports/)

* [Link to my own markdown-parse repository](https://github.com/BridgetteZagrebin/markdown-parser)
* [Link to the repository reviewed in week 7](https://github.com/21KennethTran/markdown-parser)

## Snippet 1
* It should produce: 

``` 
[`google.com]
```
* Code in MarkdownParseTest.java for it's test:
<img width="447" alt="Screen Shot 2022-05-22 at 12 07 49 PM" src="https://user-images.githubusercontent.com/103292060/169711934-ec2df63f-fdc5-45c2-9acf-54757c6de3e7.png">

* The output based on my implementation:
<img width="587" alt="Screen Shot 2022-05-22 at 12 38 10 PM" src="https://user-images.githubusercontent.com/103292060/169712937-1a3fe482-840c-4cfd-a49c-99b016255915.png">

* The output based on the implementation from week 7:
<img width="505" alt="Screen Shot 2022-05-22 at 12 34 24 PM" src="https://user-images.githubusercontent.com/103292060/169712934-9639a15a-5952-4dc3-8d4f-4d76db11ede5.png">

## Snippet 2
* It should produce: 

``` 
[a.com, a.com(()), example.com] 
```
* Code in MarkdownParseTest.java for it's test:
<img width="624" alt="Screen Shot 2022-05-22 at 12 08 20 PM" src="https://user-images.githubusercontent.com/103292060/169711942-149caf22-ffd0-4a6e-9e17-7aa11d4a48ae.png">

* The output based on my implementation:
<img width="587" alt="Screen Shot 2022-05-22 at 12 38 21 PM" src="https://user-images.githubusercontent.com/103292060/169712949-fad64112-a404-4de2-9804-bc001bcca213.png">

* The output based on the implementation from week 7:
<img width="582" alt="Screen Shot 2022-05-22 at 12 34 58 PM" src="https://user-images.githubusercontent.com/103292060/169712948-c0700226-49f4-4067-858b-4a20f75bed0c.png">

## Snippet 3
* It should produce: 

``` 
[https://sites.google.com/eng.ucsd.edu/cse-15l-spring-2022/schedule] 
```
* Code in MarkdownParseTest.java for it's test:
<img width="807" alt="Screen Shot 2022-05-22 at 12 08 59 PM" src="https://user-images.githubusercontent.com/103292060/169711947-2e026b0e-42f4-4a0e-9b1f-e07db2c3ceb9.png">

* The output based on my implementation:
<img width="587" alt="Screen Shot 2022-05-22 at 12 38 33 PM" src="https://user-images.githubusercontent.com/103292060/169712957-04c7d82d-bdfc-4ad5-bb85-71f7fa80eb5c.png">

* The output based on the implementation from week 7:
<img width="612" alt="Screen Shot 2022-05-22 at 12 35 33 PM" src="https://user-images.githubusercontent.com/103292060/169712955-07208864-d455-43df-8103-d7154bab9455.png">


## Potential Solutions
* I do think there is a small (<10 lines) code change that will make my program work for snippet 1 and all related cases that use inline code with backticks. This code change would require 
* I do think there is a small (<10 lines) code change that will make my program work for snippet 2 and all related cases that nest parentheses, brackets, and escaped brackets. This code change would require
* I do think there is a small (<10 lines) code change that will make my program work for snippet 3 and all related cases that have newlines in brackets and parentheses. This code change would require
