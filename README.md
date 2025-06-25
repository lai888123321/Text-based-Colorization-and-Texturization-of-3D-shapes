### Create Environment
```bash
# conda create -n texture python=3.8
# conda install pytorch==2.1.2 torchvision==0.16.2 torchaudio==2.1.2 pytorch-cuda=11.8 -c pytorch -c nvidia
# pip install open3d
# pip install git+https://github.com/openai/CLIP.git
# ...
```
### Train
Call the below shell scripts to generate example styles. 
```bash
# sofa made of a chesterfield
./demo/run_sofa_chesterfield.sh
# sofa made of a leather
./demo/run_sofa_leather.sh
# ...
```
The outputs will be saved to `results/demo`

### Validate
Generate gif. 
```bash
# sofa made of a chesterfield
./demo/run_sofa_chesterfield.sh
# sofa made of a leather
./demo/run_sofa_leather.sh
# ...
```
