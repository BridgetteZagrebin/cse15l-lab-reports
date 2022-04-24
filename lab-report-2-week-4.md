[Go Back](https://bridgettezagrebin.github.io/cse15l-lab-reports/)

## Code Change 1
<img width="848" alt="Screen Shot 2022-04-23 at 4 19 37 PM" src="https://user-images.githubusercontent.com/103292060/164949264-25e22904-f148-419f-8092-5233484ac5e3.png">
* [Link to test file that prompted us to make this change](https://github.com/BridgetteZagrebin/markdown-parser/blob/main/testFile.md?plain=1)
* Symptom: 
 ```
  Exception in thread "main" java.lang.OutOfMemoryError: Java heap space
        at java.base/java.util.Arrays.copyOfRange(Arrays.java:3822)
        at java.base/java.lang.StringLatin1.newString(StringLatin1.java:766)
        at java.base/java.lang.String.substring(String.java:2708)
        at MarkdownParse.getLinks(MarkdownParse.java:19)
        at MarkdownParse.main(MarkdownParse.java:30)
```
<img width="846" alt="Screen Shot 2022-04-23 at 9 40 42 PM" src="https://user-images.githubusercontent.com/103292060/164956975-bb1f41a0-bf16-4c54-9ba5-9cacbc1afa1d.png">
* The relationship between the bug, the symptom, and the faliure-inducing input is.

## Code Change 2
<img width="845" alt="Screen Shot 2022-04-23 at 4 39 28 PM" src="https://user-images.githubusercontent.com/103292060/164949631-967da1a4-e393-4ca5-ab0e-007314814174.png">
* [Link to test file that prompted us to make this change](https://github.com/BridgetteZagrebin/markdown-parser/blob/main/test2-file.md?plain=1)
* Symptom: 
```
Exception in thread "main" java.lang.OutOfMemoryError: Java heap space
```
<img width="846" alt="Screen Shot 2022-04-23 at 9 42 24 PM" src="https://user-images.githubusercontent.com/103292060/164957005-ed4b94f2-f8e8-408b-98df-0cdb302d407e.png">
* The relationship between the bug, the symptom, and the faliure-inducing input is.

## Code Change 3
<img width="845" alt="Screen Shot 2022-04-23 at 4 41 40 PM" src="https://user-images.githubusercontent.com/103292060/164949653-e54e31ba-3ea0-4ed4-a618-87b2c7545d07.png">
* [Link to test file that prompted us to make this change](https://github.com/BridgetteZagrebin/markdown-parser/blob/main/testFile.md?plain=1)
* Symptom: 
```
  Exception in thread "main" java.lang.OutOfMemoryError: Java heap space
        at java.base/java.util.Arrays.copyOfRange(Arrays.java:3822)
        at java.base/java.lang.StringLatin1.newString(StringLatin1.java:766)
        at java.base/java.lang.String.substring(String.java:2708)
        at MarkdownParse.getLinks(MarkdownParse.java:19)
        at MarkdownParse.main(MarkdownParse.java:30)
```
<img width="846" alt="Screen Shot 2022-04-23 at 9 40 42 PM" src="https://user-images.githubusercontent.com/103292060/164956975-bb1f41a0-bf16-4c54-9ba5-9cacbc1afa1d.png">
* The relationship between the bug, the symptom, and the faliure-inducing input is.


