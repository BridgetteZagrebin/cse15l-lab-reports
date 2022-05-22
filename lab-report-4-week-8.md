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
<img width="686" alt="Screen Shot 2022-05-22 at 12 23 14 PM" src="https://user-images.githubusercontent.com/103292060/169712457-b7ade6f8-44dd-4b71-996d-e58a168d0eba.png">

* The output based on the implementation from week 7:
<img width="686" alt="Screen Shot 2022-05-22 at 12 23 39 PM" src="https://user-images.githubusercontent.com/103292060/169712604-c96471ba-6960-4690-b604-1082e377067d.png">

## Snippet 2
* It should produce: 

``` 
[a.com, a.com(()), example.com] 
```
* Code in MarkdownParseTest.java for it's test:
<img width="624" alt="Screen Shot 2022-05-22 at 12 08 20 PM" src="https://user-images.githubusercontent.com/103292060/169711942-149caf22-ffd0-4a6e-9e17-7aa11d4a48ae.png">

* The output based on my implementation:
<img width="686" alt="Screen Shot 2022-05-22 at 12 23 14 PM" src="https://user-images.githubusercontent.com/103292060/169712614-6dd7c191-3867-40ab-8437-a34b6986a2c7.png">

* The output based on the implementation from week 7:
<img width="686" alt="Screen Shot 2022-05-22 at 12 23 39 PM" src="https://user-images.githubusercontent.com/103292060/169712622-635d9bca-cd8b-4ca2-937e-e879765911d0.png">

## Snippet 3
* It should produce: 

``` 
[https://sites.google.com/eng.ucsd.edu/cse-15l-spring-2022/schedule] 
```
* Code in MarkdownParseTest.java for it's test:
<img width="807" alt="Screen Shot 2022-05-22 at 12 08 59 PM" src="https://user-images.githubusercontent.com/103292060/169711947-2e026b0e-42f4-4a0e-9b1f-e07db2c3ceb9.png">

* The output based on my implementation:
<img width="686" alt="Screen Shot 2022-05-22 at 12 23 14 PM" src="https://user-images.githubusercontent.com/103292060/169712628-d454ebcb-8355-4dc4-9f03-0bf7e5a97959.png">

* The output based on the implementation from week 7:
<img width="686" alt="Screen Shot 2022-05-22 at 12 23 39 PM" src="https://user-images.githubusercontent.com/103292060/169712631-8f6d62c2-7271-40a1-a4ab-97b972273581.png">


## Potential Solutions
* Do you think there is a small (<10 lines) code change that will make your program work for snippet 1 and all related cases that use inline code with backticks? If yes, describe the code change. If not, describe why it would be a more involved change.
* Do you think there is a small (<10 lines) code change that will make your program work for snippet 2 and all related cases that nest parentheses, brackets, and escaped brackets? If yes, describe the code change. If not, describe why it would be a more involved change.
* Do you think there is a small (<10 lines) code change that will make your program work for snippet 3 and all related cases that have newlines in brackets and parentheses? If yes, describe the code change. If not, describe why it would be a more involved change.

