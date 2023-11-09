### Hi there! 👋
```python
class Self_intro:     
    def __init__(self, name, age, work):         
        self.name = name         
        self.age = age         
        self.work = work
    
    def __repr__(self):         
        return f'Self-introduction: {self.name}, {self.age} years, {self.work}'

fhelipe = Self_intro('Fhelipe Ribeiro', 22, 'Software Developer')
print(fhelipe)
