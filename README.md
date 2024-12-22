# Gen-AI

What is Generative AI?

Generative AI refers to algorithms that can generate new content, such as text, images, videos, or audio, by learning patterns and structures from existing data.

What are the common techniques used in Generative AI?

Generative Adversarial Networks (GANs): Two neural networks (Generator and Discriminator) compete to produce realistic data.

Variational Autoencoders (VAEs): Encodes data into a latent space and reconstructs it, generating similar data.

Transformers (e.g., GPT): Uses self-attention mechanisms for generating text or sequences.

Diffusion Models: Generate data by iteratively denoising a random Gaussian sample (e.g., DALL-E).

Flow-based Models: Model the probability distribution of data directly (e.g., RealNVP).

What differentiates discriminative models from generative models?

Discriminative Models: Learn the decision boundary between classes (e.g., logistic regression, SVMs).

Generative Models: Learn the joint probability distribution of features and classes to generate new data samples.

What is the role of latent space in Generative AI?

Latent space is a lower-dimensional representation of data where features are encoded. Generative models use latent space to sample and reconstruct data.

How do GANs work?

A Generator creates fake data.  

A Discriminator distinguishes between real and fake data.

Both networks train adversarially, improving the Generator's ability to create realistic data over time.

What are the challenges in training GANs?

Mode Collapse: The Generator produces limited types of outputs.

Vanishing Gradients: The Discriminator becomes too confident, providing little feedback.

Training Instability: Adversarial nature makes convergence difficult.

What are Diffusion Models, and how do they generate images?

Diffusion models work by adding noise to training data and learning to reverse this process (denoising) to generate new samples. Examples: Stable Diffusion and DALL-E.

What is Few-shot or Zero-shot Learning in Generative AI?

Few-shot Learning: The model performs well with minimal labeled examples.

Zero-shot Learning: The model generalizes to new tasks without specific training (e.g., GPT models using prompt engineering).

What is the Transformer architecture, and why is it important in Generative AI?

Transformers are foundational for models like GPT and BERT, using self-attention mechanisms to model relationships between all tokens in a sequence. They are pivotal for large-scale sequence generation tasks in text, images, and audio.


![image](https://github.com/user-attachments/assets/5c9a44ba-dae4-4155-a194-37ab1d6a15f9)

How does GPT generate text?

GPT uses a causal language model, predicting the next word in a sequence by considering all previous tokens. Each generated token is appended to the input for the next prediction.

What are the differences between GPT-3, GPT-4, and GPT-5?

GPT-3: Focuses on text generation and understanding with 175 billion parameters.

GPT-4: Multimodal capabilities (text and images) with enhanced reasoning.

GPT-5 (expected): Likely to have even better multimodal understanding, fine-tuned reasoning, and efficiency.

What is prompt engineering?

Crafting specific input queries (prompts) to guide Generative AI models like GPT toward desired outputs without fine-tuning the model.

Advanced Topics


![image](https://github.com/user-attachments/assets/3ed64ac1-0b82-4c68-bc86-f60ce2b0a7ef)


![image](https://github.com/user-attachments/assets/e0bd96e2-43ef-44ce-a55b-e420f8463319)


![image](https://github.com/user-attachments/assets/91d091fd-0cb7-40f0-9df7-3f6a83b9b97c)


![image](https://github.com/user-attachments/assets/7da57ac7-9e34-4a88-a244-851ea0361b69)


![image](https://github.com/user-attachments/assets/827be2e8-16f5-414c-870a-07b752d837cc)


![image](https://github.com/user-attachments/assets/18aa615f-a696-4f09-aee0-efa2820e041c)










