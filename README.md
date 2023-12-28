# My-project
project for VTU
git init
git add .
git commit -m "Първоначален комит с моя Python код"
```python
import ast

class Game:
    def __init__(self, scene, wolf_expression, shepherd_expressions):
        self.scene = scene
        self.wolf_expression = wolf_expression
        self.shepherd_expressions = shepherd_expressions
        self.wolf_result = None

    def validate_scene(self):
        # Проверка за валидност на сцената
        
        # Валидиране на размерите на сцената
        if len(self.scene) > 10 or any(len(row) > 10 for row in self.scene):
            return False
        
        # Проверка дали са зададени всички герои на сцената
        # и дали има само един вълк и едно куче
        sheep_count = 0
        shepherd_count = 0
        wolf_count = 0
        dog_count = 0
        for row in self.scene:
            for cell in row:
                if cell == 'S':
                   

git remote add origin 
git push -u origin master
