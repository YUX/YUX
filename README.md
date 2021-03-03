<h3 align="center">👋 Hello! I'm YUX.</h3>

<p align="center">
  <a href="https://yux.io">Blog</a> •
  <a href="https://twitter.com/realYUX">Twitter</a> •
  <a href="https://github.com/YUX">GitHub</a> •
  <a href="https://instagram.com/realyuxiao">instagram</a> •
  <a href="https://t.me/realYUX">Telegram</a>
</p>

<div align="center">
  <a href="https://github.com/ryo-ma/github-profile-trophy"><img src="https://github-profile-trophy.vercel.app/?username=YUX"></a>
</div>

<!-- Zero width character is used to put extra blank lines before and after code -->

<h3>
    
```python
​
import json
from dataclasses import asdict, dataclass


@dataclass
class Stack:
    languages   : tuple = ("Golang", "Mandarin", "Python", "C++", "français", "English")
    ongoing     : tuple = ("CSAPP")
    todos       : tuple = ("JuliaLang", "PyTorch")
    gears       : tuple = ("Maths", "m1 mba", "vscode", "vim", "Debian", "raspi 4")
    misc        : tuple = ("TensorFlow", "Docker", "Mathematica")
    edu         : tuple = ("Sorbonne Université Campus Pierre et Marie Curie", "Beijing University of Technology")
    
    def serialize(self):
        return json.dumps(asdict(self), indent=4)


stack = Stack()
print(stack.serialize())
​
```
</h3>
