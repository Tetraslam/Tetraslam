```python
    import random
    class Tetraslam:
        def __init__(self, name, username, location, bio, languages):
            self.name = 'Shresht'
            self.username = 'Tetraslam'
            self.location = 'Bangalore'
            self.bio = '17 year old wannabe startup founder'
            self.languages = ['python', 'htmx', 'c', 'rust']

        def generate_intro(self):
            intro = f"Hello there! \n\nI'm {self.name}, a {self.bio} based in {self.location}.\n\n"
            intro += f"- 🌱 I'm currently learning {', '.join(self.languages)}\n"
            intro += f"- 📫 How to reach me:
```
[![Medium](https://img.shields.io/badge/Medium&nbsp;Blog-12100E?style=for-the-badge&logo=medium&logoColor=white)](https://medium.com/@Tetraslam) [![Spotify](https://img.shields.io/badge/My&nbsp;Playlist-Spotify-1ED760?style=for-the-badge&logo=spotify&logoColor=white)](https://open.spotify.com/playlist/63yXZkbWd3SydPVQcaECZN?si=42105eaec8eb4639) [![Gmail](https://img.shields.io/badge/Write&nbsp;To&nbsp;Me&nbsp;On&nbsp;Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:bhowmickshresht@gmail.com) [![Instagram](https://img.shields.io/badge/Instagram-%23E4405F.svg?style=for-the-badge&logo=Instagram&logoColor=white)](https://instagram.com/skynovurm) [![LinkedIn](https://img.shields.io/badge/linkedin-%230077B5.svg?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/shreshtbhowmick) [![Twitter](https://img.shields.io/badge/Twitter-%231DA1F2.svg?style=for-the-badge&logo=Twitter&logoColor=white)](https://twitter.com/@Tetraslam) [![Reddit](https://img.shields.io/badge/Reddit-%23FF4500.svg?style=for-the-badge&logo=Reddit&logoColor=white)](https://reddit.com/u/TheWhiteRyder)
```python          
            \n"
            intro += f"- ⚡ Fun fact: {self.get_fun_fact()}\n"
            return intro
    
        def get_fun_fact(self):
            fun_facts = [
            "I've traveled to over 30 countries!"
            "I'm a fan of roguelike and roguelite videogames, especially Dead Cells and Hades."
            "My favorite author is Brandon Sanderson!"
            "I mostly listen to K-pop, J-rock, and shoegaze rock."
            ]
            return random.choice(fun_facts)

```
