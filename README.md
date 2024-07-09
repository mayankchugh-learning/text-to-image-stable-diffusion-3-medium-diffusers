# text-to-image-stable-diffusion-3-medium-diffusers

### STEPS:
## How to run? 
### STEP 01- Create a conda environment after opening the repository
```bash
conda create -p ttivenv python -y
```

```bash
source activate ./ttivenv
```

### STEP 02- install the requirements
```bash
pip install -r requirements.txt
```

```bash
pip install -U "huggingface_hub[cli]"
huggingface-cli login
```

### STEP 03- run application
```bash
python app.py
```

[Models -> Task -> text-toimage -> stabilityai/stable-diffusion-3-medium ](https://huggingface.co/stabilityai/stable-diffusion-3-medium)

[Step by Step Guide] (https://medium.com/@mayankchugh.jobathk/text-to-image-using-stable-diffusion-3-medium-step-by-step-guide-0f9459d9d012)

[Gradio documentation link](https://www.gradio.app/docs/gradio/file)
[Huggingface CLI] (https://huggingface.co/docs/huggingface_hub/main/en/guides/cli)