' ChristmasCTF_2021-22 - Agnes


Format of the repository:

Challenge catagories (ie days) should be the first level directories. Inside each catagory should contain a directiry of each challenge.

The challenge directories should contain:

    1 README.md : Explains the challenge, type of challenge (ie dockerized/distribute files), any dependancies, author, percieved difficulty
    Challenge files : Should contain all required content for the challenge. Dockerfile should be on first level on this subdirectory (if applicable)
        1 solve directory containing : 1 README.md as a walkthrough; solver script (if applicable)

Example

```bash
> tree
.
├── example_challenge
│   ├── challenge_0
│   │   ├── bin
│   │   │   ├── challenge
│   │   │   └── flag
│   │   ├── challenge.c
│   │   ├── ctf.xinetd
│   │   ├── Dockerfile
│   │   ├── README.md
│   │   ├── solve
|   |   |   ├── README.md
│   │   │   └── solve.py
│   │   └── start.sh
│   ├── challenge_1
│   │   ├── bin
│   │   │   ├── challenge
│   │   │   └── flag
│   │   ├── challenge.c
│   │   ├── ctf.xinetd
│   │   ├── Dockerfile
│   │   ├── README.md
│   │   ├── solve
|   |   |   ├── README.md
│   │   │   └── solve.py
│   │   └── start.sh
```
