# Announcement:
- This language is in its testing period, we will probably change some keywords.
- We don't usually update [The Chinese Documentation / 中文文档](https://github.com/Rick-Lang/rickroll-lang/blob/main/doc-Ch.md)
- Also, I am a little bit buzy these days, so I am not going to update rickroll-lang recently

<img src="img/ico1.jpg" align="right" width="160" height="160"/>

# Rick Roll Programming Language

![Build](https://img.shields.io/badge/Build-passing-orange?style=for-the-badge&logo=appveyor)
![Python](https://img.shields.io/badge/Python-3.6%2B-brightgreen?style=for-the-badge&logo=appveyor)
![License](https://img.shields.io/badge/License-MIT-red?style=for-the-badge&logo=appveyor)
<br>
Rick Roll Programming Language, a language for rickrolling!
<br>

![](https://repository-images.githubusercontent.com/367934588/4a27ae00-b73b-11eb-801b-36dd1756dc93)

## Hello World
**The syntax of RickRoll-Lang is not completely similar to Python**
1. It doesn't need indentation
2. The code must be written inside the main method, otherwise the interpreter will not execute

Rick Roll-Lang:
```
take_me_to_ur_heart                                                        # This is the MAIN METHOD
    give_u_up msg = "Never gonna give you up, never gonna let you down~\n" # Define a variable
    i_just_wanna_tell_u_how_im_feeling msg                                 # print the "msg" variable
say_good_bye                                                               # End the main method
```
Equivalent to Python
```python
if __name__ == '__main__':
  msg = "Never gonna give you up, never gonna let you down~\n"
  print(msg, end='')

```

Equivalent to C++
```c++
#include<iostream>
using namespace std;
int main(int argc, char* argv[]){
    string msg = "Never gonna give you up, never gonna let you down~\n";
    cout<<msg;
}
```

**And you can get the output on your terminal:**
![](https://preview.redd.it/w2n81iqx37p51.gif?format=png8&s=a5619fa00938c2aa817496ddd9eceda8a727324c)
<br>
**Sorry, it's this:**
```
Never gonna give you up, never gonna let you down~
```

## Features
- *[Turing-complete](https://en.wikipedia.org/wiki/Turing_completeness)*
- *Support [python 3.6+](https://www.python.org/downloads/release/python-3610/)*
- *Keywords/statements are all comming from [Rick Astley's](https://en.wikipedia.org/wiki/Rick_Astley) lyrics*
- *[Examples](https://github.com/Rick-Lang/rickroll-lang/tree/main/examples) to get started*
- *Translate .rickroll source code to Python3 and C++*
- *[Generate and play audios from .rickroll source code](https://github.com/Rick-Lang/rickroll-lang#Generate-Audio)*


## Generate Audio
How to use this generator:
```
python3 RickRoll.py -r [Source Code File Name] --audio
```
This thing generates an audio from the .rickroll program and plays it in your terminal

![](https://github.com/Rick-Lang/rickroll-lang/blob/main/img/au_generator.PNG)

## Requirements

## Documentation
**[English](https://github.com/Rick-Lang/rickroll-lang/blob/main/doc.md)**
<br>
**[简体中文](https://github.com/Rick-Lang/rickroll-lang/blob/main/doc-Ch.md)**


# Todo!
In order to make RICK ROll becoming a world heritage, YOU and I still have a bunch of things to do!
1. Add more keywords and built-in functions!
2. Write algorithms in RickRoll-Lang and upload them to [examples folder](examples).
3. Make syntax highlights for [VS Code](https://code.visualstudio.com/api/language-extensions/syntax-highlight-guide) and [Sublime](https://www.sublimetext.com/docs/syntax.html)!
4. Improve the current audio generator!
5. Support "writing code by singing"!
6. Design a better icon!
7. Build a virtual machine or interpreter for RickRoll-Lang
8. [**SPREAD RICK ROLL EVERYWHERE!!!**](https://www.youtube.com/watch?v=dQw4w9WgXcQ)

# Rick Roll Language Website
**Address:**
<br>
**[https://rickroll-lang.tech/introduction/](https://www.youtube.com/watch?v=dQw4w9WgXcQ)**

**Here are Rick Astley's songs in my website, you can download them from my website**
<br>
**[https://rickroll-lang.tech/songs/](https://www.youtube.com/watch?v=yPYZpwSpKmA)**

# Contributors
- _**[Sherlockcxk](https://github.com/Sherlockcxk)**_   (Writing code)
- _**[StepfenShawn](https://github.com/StepfenShawn)**_  (Revised typos in source code && fixed bugs)
- _**[Lemonix-xxx](https://github.com/Lemonix-xxx)**_   (Making suggestions/advice)
- _**[henriqueritter](https://github.com/henriqueritter)**_   (Contributed to RickRoll example)
