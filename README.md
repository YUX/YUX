<h3 align="center">👋 Hello! I'm YUX.</h3>

<p align="center">
  <a href="https://realyux.com"><img src="https://shields.io/badge/ipns-realyux.eth-green?logo=Ethereum&style=for-the-badge&logoColor=blue"></a>
</p>

<p align="center">
  <a href="https://twitter.com/realYUX">Twitter</a> •
  <a href="https://github.com/YUX">GitHub</a> •
  <a href="https://instagram.com/realyuxiao">instagram</a> •
  <a href="https://t.me/realYUX">Telegram</a>
</p>

<div align="center">
  <a href="https://github.com/ryo-ma/github-profile-trophy"><img src="https://github-profile-trophy.vercel.app/?username=YUX&row=1&column=7&no-bg=true&theme=dark_lover&no-frame=true"></a>
  
  
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
    todos       : tuple = ("JuliaLang", "Rust⚙️")
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
