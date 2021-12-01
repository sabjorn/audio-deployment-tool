# Audio Deployment Tool (ADT)
## About
A tool for automating metadata for audio specifically to reduce the complexity and error prone nature of preparing audio files for release.

## Installation
### venv (optional)
#### MacOS/Linux
```
python3 -m venv .venv
source .venv/bin/activate
```

### Requirements
```
pip3 install -r requirements.txt
```

### Usage
#### Config file
Tags can be added automatically with a config file by running:

```
./adt -c <config file>.yml
```

see example config: `example_config.yaml`

