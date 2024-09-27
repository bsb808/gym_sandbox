# gym_sandbox
sudo apt install python3-venv

python3 -m venv .venv

source .venv/bin/activate

pip install "gymnasium[atari]"
pip install autorom[accept-rom-license]
AutoROM --accept-license
pip install moviepy

deactivate