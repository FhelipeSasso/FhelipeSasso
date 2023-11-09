### Hi there! 👋
```python
class SelfIntro:     
    def __init__(self, name, age, work):         
        self.name = name         
        self.age = age         
        self.work = work
    
    def __repr__(self):         
        return f'Self-introduction: {self.name}, {self.age} years, {self.work}'

fhelipe = SelfIntro('Fhelipe Ribeiro', 22, 'Software Developer')
print(fhelipe)
