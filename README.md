### System Requirements
- Python >=3.7 and <=3.9
- CUDA 11
- Nvidia GPU with 12 GB ram at least
- Open3d >=0.14.1
- the package of clip (https://github.com/openai/CLIP)

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
