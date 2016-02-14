# FLAC to iTunes 

Automatic encoding and covers embedding script.

## Installation 

```
brew install ffmpeg atomicparsley python3    
brew install gnu-sed --with-default-names  
pip3 install sacad
```  

### Workflow

Unzip and put "FLAC to iTunes importer.workflow" into ```~/Library/Workflows/Applications/Folder Actions/```

## Usage

1) Folder action setup.

![Folder action setup (service)](https://raw.githubusercontent.com/glushchenko/flac-to-itunes/master/how-to/workflow-folder-actions-services.png)

2) Attach.

![Folder action setup (attach)](https://raw.githubusercontent.com/glushchenko/flac-to-itunes/master/how-to/workflow-folder-actions-attach.png)

3) Copy album into workflow folder and tracks will be automatic imported in iTunes.

