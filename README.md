MODEL ARCHITECTURE

![image](https://github.com/user-attachments/assets/59d1e110-5c9f-4a4f-88a4-84a303ace9ef)


TRAINING
•	Loss function used is Structural similarity Index for images with local window to ensure photo realism of the generated images. Therefore, if we train with sufficient training data photo realism can be achieved.
•	To ensure steerability, the diffusion model is conditioned with text embedding along with increasing the dimensions of latent space.
•	All the parameters of UNet model and decoder are trained whereas the CLIP (text to image) model is updated using Low Rank Adaptations (LoRA).


