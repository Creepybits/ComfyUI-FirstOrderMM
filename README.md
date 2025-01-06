# ComfyUI-FirstOrderMM

Note: This repository is copied from: https://github.com/FuouM/ComfyUI-FirstOrderMM

The reson I didn't just fork it is because I found a lot of information needed to install this in various places, and it was both confusing and hard to find all bits and pieces. I figure I'll make it easier by keeping everything at one place.

Below is the workflow with the settings that worked the best for me.

## Workflow:
![DF Video Maker working WF](https://github.com/user-attachments/assets/0860801c-c614-4b48-8121-1f3c349848c3)


## Where to put everything?
I've made it really easy to download all checkpoints and models that are needed. All modules/models/checkpoints that belong together are put together in a zip file.

### CHECKPOINTS:


![image](https://github.com/user-attachments/assets/8d6bfaae-a1af-4ae6-8cca-37e534d1b931)

The checkpoints can be downloaded here, and all go according to the image above. [CHECKPOINTS](https://drive.google.com/file/d/1dIVHqkJXvScW9NQWi2L1y9uGkmI7aS5M/view?usp=sharing) 


### Face Parsers


![image](https://github.com/user-attachments/assets/a23aa4c1-4def-4ef5-a1a8-652d33c6d45f) 

Download them here, and put them in the folder as shown above: [FACE PARSERS](https://drive.google.com/drive/folders/1WPmCJ_35B2RVgKkRhu29yfde6zuPnaPo?usp=sharing) 


### module_articulate: vox256.pth

![image](https://github.com/user-attachments/assets/2eb63cd6-f7b6-40f3-beee-8d480b5c1d08)

Download it here: [MODULE ARTICULATE](https://drive.google.com/drive/folders/1f5KotRDdb5Vs2KB5zVmQ4Y6N5Y9J8f-e?usp=sharing)


### module_fsrt: kp_detector, vox256, vox256_2Source

![image](https://github.com/user-attachments/assets/e3f80f66-6523-48d3-9ba0-2177f4bb29ce)

Download them here: [MODULE_FSRT](https://drive.google.com/drive/folders/1kNH931Yf9f5tNOm7BtwGSHjqNpisa-Zk?usp=sharing) 



### module_mrfa: VOX.PTH, celebvhq.PTH

![image](https://github.com/user-attachments/assets/ea5d988e-04a7-4e8c-b64c-3ad67203ca2a) 

Download them here: [MODULE_MRFA](https://drive.google.com/drive/folders/1yWkkvrVguJeSN0bEpXtkZrQzZV2NMUvi?usp=sharing) 


### module_spline: vox.pth.tar 

![image](https://github.com/user-attachments/assets/f68b1aaf-645c-43f3-87ad-5afd69f27a76) 

Download it here: [MODULE_SPLINE](https://drive.google.com/drive/folders/189zwBWvZ-2hTfNclBBXx2hcR6p89RCqM?usp=sharing) 


## Installation

1. Clone the repo to `ComfyUI/custom_nodes/`
```
git clone https://github.com/Creepybits/ComfyUI-FirstOrderMM.git 
```

2. Install required dependencies
```
pip install -r requirements.txt
```

**Optional**: Install [face-alignment](https://github.com/1adrianb/face-alignment) to use the `find_best_frame` feature:

```
pip install face-alignment
```




