# RabbitGame
A simple command line game of rabbit's simple life.

# Story
Help rabbit find his carrot and store it in the rabbit hole.

![RabbitGame](https://user-images.githubusercontent.com/56764399/180026886-4e905322-0fb0-4d50-ae45-292dba11ea60.gif)

## Install
```bash
git clone https://github.com/adhadse/RabbitGame.git
cd RabbitGame
python -m venv ./venv
source ./venv/bin/activate
pip install -r requirements.txt

```
## Gameplay
- use `a` to move left and `d` to move right.
- pick carrot (`c`) using `p` (rabbit changes from `r` to `R`) and drop it in rabbit hole (`O`).
- Jump over rabbit hole using `j`.
- Press `esc` key anytime to escape the game
```bash
py main.py
```

## Testing
Test passes.
```bash
pytest --no-header -v
```
![Screenshot from 2022-07-20 20-49-19](https://user-images.githubusercontent.com/56764399/180022568-0725a9ee-45d7-4f08-8859-391f954800f9.png)
