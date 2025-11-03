
# AI Image Caption Recommendation System

An intelligent image-caption recommendation system powered by **CLIP (Contrastive Language–Image Pretraining)** by OpenAI.  
This project retrieves and recommends the most relevant captions for an image from a predefined caption list using deep learning embeddings.

---

##  Overview

The **AI Image Caption Recommendation System** leverages **CLIP**, a powerful model that understands both images and text in a shared embedding space.  

Given an image and a set of candidate captions, the system:
1. Generates embeddings for both the image and text captions using CLIP.
2. Calculates **cosine similarity** between image and caption embeddings.
3. Ranks and recommends the **top-matching captions** based on similarity.

This makes it ideal for:
- Social media caption generation
- Marketing automation
- Content curation platforms

---

## How It Works

1. **Input Image** → Preprocessed and converted into CLIP embeddings  
2. **Candidate Captions** → Encoded into text embeddings using CLIP  
3. **Cosine Similarity** → Measures alignment between image and captions  
4. **Top Matches** → System outputs most relevant captions ranked by similarity  

---

##  Architecture

