# DreamBooth Training with Stable Diffusion 1.5

In this project, I've undertaken DreamBooth training in the Stable Diffusion 1.5 version by automatic1111, focusing on generating images of a specific individual. In this case, the model has been trained for the legendary Lionel Messi. The project utilizes safetensors generated during the training as checkpoints, which are then employed in the Stable Diffusion web UI to generate outputs.

## Training Details

### Model Training
- **DreamBooth Training:** Stable Diffusion 1.5 version by automatic1111.
- **Target Individual:** Lionel Messi.

### Checkpoints and Safetensors
- **Checkpoint File:** `messi_3200.safetensors` generated upon completion of training.

### Training Configuration
- **Base Checkpoint:** [civitai.com/models/4384/dreamshaper](https://civitai.com/models/4384/dreamshaper)
- **Instance Prompt:** "photo of nyd messi"
- **Instance Token:** "nyd"
- **Class Token:** "messi"
- **Class Prompt:** "photo of messi"
- **Class Images per Instance Image:** 10
- **Sample Image Prompt:** "photo of nyd messi wearing green shirt"
- **Optimizer:** 8bitAdamW
- **Mixed Precision:** fp16
- **Training Steps per Image:** 100
- **Save Model Frequency:** 250
- **Save Preview Frequency:** 100
- **Learning Rate:** 0.000002
- **Text Encoder Learning Rate:** 0.000001
The training ended after 3200 steps.
These parameter configurations have proven effective in achieving desirable outcomes during the DreamBooth training. Feel free to explore the generated outputs and experiment with the provided safetensors. If you have any questions or suggestions, please don't hesitate to reach out!

Happy DreamBooth generating! 🌌
