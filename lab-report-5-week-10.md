[Go Back](https://bridgettezagrebin.github.io/cse15l-lab-reports/)

I found the tests with different results by using vimdiff on the results of running a bash for loop.

## First Test - 194.md
* [Link to test-file with different results](https://github.com/nidhidhamnani/markdown-parser/blob/main/test-files/194.md)
* The implementation given from week 9 was correct. It is correct because it produces the correct link formatting.
* My output: []
* Week 9 output: [url]
* Expected links: []
* The output should be: 
<img width="521" alt="Screen Shot 2022-06-05 at 10 12 33 PM" src="https://user-images.githubusercontent.com/103292060/172099670-c803773d-22ec-4f6b-ad7e-1ab2ed3bea9b.png">
* My implementation is wrong because it has a bug where it does not recognize a link when things are in between the closed bracket and the open parenthesis. Along with this, the extra closed parenthesis adds to this bug since it does not recognize the link in this case. 
* Where my implementation could be fixed:
<img width="531" alt="Screen Shot 2022-06-05 at 10 53 19 PM" src="https://user-images.githubusercontent.com/103292060/172103181-11ce290d-b5ec-446c-b4dd-550768794369.png">


## Second Test - 201.md
* [Link to test-file with different results](https://github.com/nidhidhamnani/markdown-parser/blob/main/test-files/201.md?plain=1)
* My implementation was correct. It is correct because it produces the correct link formatting.
* My output: []
* Week 9 output: [baz]
* Expected links: [baz]
* The output should be:
 <img width="539" alt="Screen Shot 2022-06-05 at 10 12 48 PM" src="https://user-images.githubusercontent.com/103292060/172099677-6f9e9bfd-084c-4fd2-a917-4952d5b03b10.png">
 * Week 9's implementation is wrong because it has a bug where it recognizes a link when things are in between the closed bracket and the open parenthesis. Along with this, the false link with "<>" adds to this bug since it does not recognize that this false link should throw off the case of it being a link.
 * Where week 9's implementation could be fixed:
 <img width="683" alt="Screen Shot 2022-06-05 at 11 01 51 PM" src="https://user-images.githubusercontent.com/103292060/172104304-7dd59484-b6fa-4c7a-bae4-7f7d1f209d75.png">
