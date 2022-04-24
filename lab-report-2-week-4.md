[Go Back](https://bridgettezagrebin.github.io/cse15l-lab-reports/)

## Code Change 1
<img width="848" alt="Screen Shot 2022-04-23 at 4 19 37 PM" src="https://user-images.githubusercontent.com/103292060/164949264-25e22904-f148-419f-8092-5233484ac5e3.png">
* [Link to test file that prompted us to make this change](https://github.com/BridgetteZagrebin/markdown-parser/blob/main/testFile.md?plain=1)
* Symptom: 
 ```
  Exception in thread "main" java.lang.OutOfMemoryError: Java heap space
```

* **The relationship between the bug, the symptom, and the faliure-inducing input:**
The symptom of this error was the code crashing. This is visible on the faliure inducing input above. The bug was the the code running into multiple loops when it could not find another open bracket; which made the code crash.

## Code Change 2
<img width="845" alt="Screen Shot 2022-04-23 at 4 39 28 PM" src="https://user-images.githubusercontent.com/103292060/164949631-967da1a4-e393-4ca5-ab0e-007314814174.png">
* [Link to test file that prompted us to make this change](https://github.com/BridgetteZagrebin/markdown-parser/blob/main/test2-file.md?plain=1)
* Symptom: 
```
Exception in thread "main" java.lang.OutOfMemoryError: Java heap space
```

* **The relationship between the bug, the symptom, and the faliure-inducing input:**
The 
  
## Code Change 3
(This was something that we revisited after taking it out earlier)
<img width="845" alt="Screen Shot 2022-04-23 at 4 41 40 PM" src="https://user-images.githubusercontent.com/103292060/164949653-e54e31ba-3ea0-4ed4-a618-87b2c7545d07.png">
* [Link to test file that prompted us to make this change](https://github.com/BridgetteZagrebin/markdown-parser/blob/main/file1.md)
* Symptom: 
```
[]
```

* **The relationship between the bug, the symptom, and the faliure-inducing input:**
The symptom of this error was the code crashing; which is visible on the faliure inducing input above. The bug was the the code running into multiple loops when it could not find another open bracket; which made the code crash.

