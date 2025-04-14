# Temporally Consistent Amodal Completion in Human-Object Interaction

Understanding Human-Object Interaction (HOI) in dynamic scenes is critical for applications such as Virtual Reality (VR), Augmented Reality (AR), and autonomous systems. A major challenge in HOI analysis lies in handling severe occlusions that obscure parts of the human body or objects during interaction. While existing amodal completion methods can infer occluded regions, most focus on single-frame inputs and fail to ensure temporal consistency across videos. In this paper, we propose a novel pipeline for temporally consistent amodal completion in HOI videos. Our method leverages latent image features and optical flow to warp features across frames and employs a deterministic cross-attention mechanism to integrate contextual information from temporally adjacent frames. This approach ensures coherent completion of occluded regions throughout the video sequence. By combining recent advances in generative modeling and flow-based feature warping, our pipeline achieves high-quality, temporally stable reconstructions, enabling more realistic and reliable HOI representations suitable for downstream applications.


- To run the code, download "ece570_hoi.ipynb" and open it with Google Colab.
  
- To use the dataset, download "dataset.zip" from the link. (https://drive.google.com/file/d/1PdSlx4_Tn684JWnjGeCNkVJIG3ZbcdD5/view?usp=drive_link)

- To access the demo video, use the link below. (https://drive.google.com/file/d/1qkfWCfm0YCpzv0aK9fA0hdlNuRi8Kvag/view?usp=sharing)
