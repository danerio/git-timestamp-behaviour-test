# git-timestamp-behaviour-test
## About
A space for exploring the nuances of playing with git commit timestamps. 

## Interesting Observations
### Present, Past, Present

In my repository I made four commits:
1. My first commit (adding `example.txt`) to the repo in current time
2.  A change to the example file, still in curernt time
3. A change to the test file one day in the past (I moved my clock back one day)
4. A change again in the present (I moved my clock back to today)

<img width="406" alt="image" src="https://user-images.githubusercontent.com/15006755/204103561-1dffd00c-a149-4326-98f1-bf909a9a827a.png">

I then proceeded to push this four commits to my repository:

<img width="1283" alt="image" src="https://user-images.githubusercontent.com/15006755/204103517-ccfba25b-266a-4f6b-b1fb-c49a6d6e35d9.png">

All my timestamps on `github` look like they were reset to the current time...? (I'm assuming this is because github wasn't sure how to display the sequential commits with non-sequential time stamps.

Attempting a pull (suspecting something magical has happend)...

<img width="134" alt="image" src="https://user-images.githubusercontent.com/15006755/204104118-fc7cbffc-1d5f-49c9-ae0d-95af1441ebec.png">



### A week ago and back again...

<img width="572" alt="image" src="https://user-images.githubusercontent.com/15006755/204103918-3e00fd0f-1e14-4841-a995-3bf5f6c23199.png">

<img width="400" alt="image" src="https://user-images.githubusercontent.com/15006755/204103874-a69f825e-a204-4e91-93ba-d53086659fca.png">
