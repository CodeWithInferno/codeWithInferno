```js
from typing import Tuple, List, Dict

class CodeWithInferno:
    pass

class Attributes(CodeWithInferno):
    @property
    def contact(self) -> Tuple[str, str, str]:
        telegram = "t.me/CodeWithInferno"
        channel  = "t.me/CodeWithInferno"
        email    = "infernotech2618@gmail.com"
	    
        return telegram, channel, email

    @property
    def life(self) -> Tuple[List[str], int]:
        langs = ['English', 'Gujarati', 'Hindi']
        age   = 17
		
        return langs, age
	
    @property
    def coding(self) -> Tuple[Dict[str, List[str]], List[str], List[str], Dict[str]]:
        langs = {
            'expert'      : ['python'],
            'intermediate': ['Next.Js', 'js'],
            'learning'    : ['c', 'c++', 'c#', 'asm', 'java']
        }
        specialities  = ['web/app reverse engineering', 'fullstack', 'ai']
        ide           = ['vscode']
        pc            = {
            'MacOS': {
                'macbook air m3': {
                    'processor': 'm3 | 8 cores',
                    'ram'      : '8gb',
                    'gpu'      : 'm3 | 8 cores'
                }
            },
            'Windows': {
                'custom': {
                    'processor': 'Intel i5 6300U | 2 cores',
                    'ram'      : '8gb',
                    'gpu'      : 'Intel Iris Xe | Cores No Longer Matters'
                }
            }
        }

	return langs, specialities, ide, pc
```
## 🐍 Contribution Snake

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/CodeWithInferno/CodeWithInferno/output/github-snake-dark.svg" />
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/CodeWithInferno/CodeWithInferno/output/github-snake.svg" />
  <img alt="GitHub Contribution Snake" src="https://raw.githubusercontent.com/CodeWithInferno/CodeWithInferno/output/github-snake.svg" />
</picture>
