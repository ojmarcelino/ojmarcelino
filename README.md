```python
class ojmarcelino:
    def __init__(self):
        self.data = {
            "name": "Juliano Marcelino",
            "location": "SC, Brazil",
            "linkedin": "linkedin.com/in/ojmarcelino/",
            "web": "jmarcelino.com.br",
            "telegram": "t.me/ojmarcelino",
            "mail": "juliano at jmarcelino dot com dot br"
        }

    def bio(self):
        bio_text = f"""
          Greetings, I'm {self.data['name']}, and enjoy to solve problems using 
          technology that improves knowledge on a major scale.
          Please, feel free to keep in touch to extrapolate and concatenate ideas.
        """
        return bio_text

print(ojmarcelino().bio())
```
