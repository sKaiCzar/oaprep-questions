# questions
repo of questions of OAPrep
## Format of pr request for questions:
### Filename format rules
filename: (String(MD5 checksum(username of contributor)) + String(question no from their perspective))).json

Example sKaiCzar's first question : 769bad48a0abba78ae3110d6ccf9e7120.json

MD5(sKaiCzar) = 769bad48a0abba78ae3110d6ccf9e712

Question sequence by this user = 0

Use [this link to generate MD5](https://emn178.github.io/online-tools/md5.html)

[Shoutout to emn178](https://github.com/emn178) for making the above static solution for hashing algorithms.
### Format for internal question
```
{
  question : "question",
  questionImageUrl : [],
  options : [],
  optionImageUrl: [],
  answer : [],
  tags : [],
}
```

Please use MD5 for generating answer with hash. 
Please push in respective directory or make new directory.

## Contact Information
For any further question please contact [sKaiCzar on X](twitter.com/sKaiCzar)
or mail at: skaiczar@protonmail.com
