
<img src="https://github.com/user-attachments/assets/06d3e172-5c07-4354-bf92-eef50ff10918" alt="Fractal_Logo" height="400"/>

# Fractal
A fractal generator in written in python and C with the Pygame UI library

## 🧱 Builing Fractal generator
You can simply generate fractal with this program by cloning the repo, building the environement and starting the program

> [!NOTE]
> Default value for the julia set generator is defined to 0.39 + 0i, you can change it by 

```bash
git clone https://github.com/technoc-5255/Fractal.git
make build
make run
```

## 💻 Julia set customization

 - `--val VALUE`
 - `--threads VALUE`
 - `--hidden` Hide the HUD when image mode not enabled
 - `--image PATH` Set generator to image mode (no window will be shown) and ouputs the image in the given image path
