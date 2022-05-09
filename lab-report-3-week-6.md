[Go Back](https://bridgettezagrebin.github.io/cse15l-lab-reports/)

## Streamlining ssh Configuration
> <img width="616" alt="Screen Shot 2022-05-06 at 11 25 43 PM" src="https://user-images.githubusercontent.com/103292060/167245994-ea992f11-cdf3-45dd-9f46-056dc6601a7a.png">
* My `.ssh/config` file is shown above
* I edited it with VScode


> <img width="616" alt="Screen Shot 2022-05-06 at 11 27 07 PM" src="https://user-images.githubusercontent.com/103292060/167246013-e729e469-cba9-48a5-8d7f-bf8ebc44d9ff.png">
* The `ssh` command logging me into my account using just the alias I chose is shown above.


> <img width="810" alt="Screen Shot 2022-05-06 at 11 48 14 PM" src="https://user-images.githubusercontent.com/103292060/167246017-eaf9f65d-abd9-448c-af18-c7f14a2aa5d4.png">
* A `scp` command copying a file to my account using just the alias I chose is shown above.


---
## Setup Github Access from ieng6
> <img width="822" alt="Screen Shot 2022-05-07 at 2 29 04 PM" src="https://user-images.githubusercontent.com/103292060/167318421-f4be6136-d964-49c2-ab2f-540786c7b0c3.png">
* Above is the public key stored on Gitgub.


> <img width="569" alt="Screen Shot 2022-05-07 at 5 30 14 PM" src="https://user-images.githubusercontent.com/103292060/167318436-12bbbfcf-1ed8-4308-a771-21d22795d4b9.png">
* Above shows where the public key(named id_rsa.pub) and private key(named id_rsa) are stored in the .ssh folder.


* Show running git commands to commit and push a change to Github while logged into your ieng6 account.

* [Link to the resulting commit]()


---
## Copy whole directories with `scp -r`
> <img width="673" alt="Screen Shot 2022-05-08 at 1 38 55 PM" src="https://user-images.githubusercontent.com/103292060/167318451-1b9077ce-ffc8-4997-b63e-ff1ef5a0ae97.png">
> <img width="673" alt="Screen Shot 2022-05-08 at 1 39 36 PM" src="https://user-images.githubusercontent.com/103292060/167318458-02f853bb-82d7-4605-bc72-5a910283bfdf.png">
> <img width="673" alt="Screen Shot 2022-05-08 at 1 39 47 PM" src="https://user-images.githubusercontent.com/103292060/167318465-266be694-beab-4184-8931-1c114cd8a1fb.png">
* Above shows the whole markdown-parse direcotry being coppied into my ieng6 account.


> <img width="800" alt="Screen Shot 2022-05-08 at 8 26 26 PM" src="https://user-images.githubusercontent.com/103292060/167335690-e4622ac5-0493-4ab0-b4f4-592b82351c0d.png">
* Above is me logging into my ieng6 account and compiling and running the tests for my repository.


> <img width="1024" alt="Screen Shot 2022-05-08 at 8 54 02 PM" src="https://user-images.githubusercontent.com/103292060/167337990-88f44c45-e215-4b77-8672-28aa0c821b4d.png">
> <img width="1024" alt="Screen Shot 2022-05-08 at 8 54 13 PM" src="https://user-images.githubusercontent.com/103292060/167337997-078f5bfb-7564-4257-b426-8c39de023f73.png">
> <img width="1024" alt="Screen Shot 2022-05-08 at 8 54 22 PM" src="https://user-images.githubusercontent.com/103292060/167338006-677584cb-da26-48c0-8168-ac344eca1130.png">
> <img width="1024" alt="Screen Shot 2022-05-08 at 8 54 41 PM" src="https://user-images.githubusercontent.com/103292060/167338020-5cada383-a415-4864-be23-32ea184b9ec9.png">
* combining `scp`, `;`, and `ssh` to copy the whole directory and run the tests in one line.

