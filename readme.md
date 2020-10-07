### Installing Anaconda:

- Anaconda Navigator is a QT-based GUI. If you are installing Anaconda on a desktop machine and you want to use the GUI application, install the following packages. Otherwise, skip this step.

`sudo apt install libgl1-mesa-glx libegl1-mesa libxrandr2 libxrandr2 libxss1 libxcursor1 libxcomposite1 libasound2 libxi6 libxtst6`

- Download

`wget -P /tmp https://repo.anaconda.com/archive/Anaconda3-2020.02-Linux-x86_64.sh`

- Run the script

`bash /tmp/Anaconda3-2020.02-Linux-x86_64.sh `

- To activate the Anaconda installation, you can either close and re-open your shell or load the new PATH environment variable into the current shell session by typing:

`source ~/.bashrc`

- open the Navigator GUI

`anaconda-navigator`

### Virtual Enviroments:

- Create an enviroment

`conda create --name [env-name] python=3.5 biopython`

- List enviroments info

`conda info --envs`

- Activate envorment

`activate [env-name]`

- Deactivate enviroment:

`deactivate`

## Tips:

- Editor: jupyter nootebook
- quit python: `quit()`
