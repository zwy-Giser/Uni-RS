# Uni-RS: A Spatially Faithful Unified Understanding and Generation Model for Remote Sensing

>Weiyu Zhang†, Yuan Hu†, Yong Li, and Yu Liu∗
>  
>**Abstract:** Unified remote sensing multimodal models exhibit a pronounced spatial reversal curse: although they can accurately recognize and describe object locations in images, they often fail to faithfully execute the same spatial relations during text-to-image generation, where such relations constitute core semantic information in remote sensing. Motivated by this observation, we propose Uni-RS, the first unified multimodal model tailored for remote sensing, to explicitly address the spatial asymmetry between understanding and generation. Specifically, we first introduce explicit Spatial-Layout Planning to transform textual instructions into spatial layout plans, decoupling geometric planning from visual synthesis. We then impose Spatial-Aware Query Supervision to explicitly bias learnable queries toward spatial relations specified in the instruction. Finally, we develop Image–Caption Spatial Layout Variation to expose the model to systematic geometry-consistent spatial transformations. Extensive experiments across multiple benchmarks show that our approach substantially improves spatial faithfulness in text-to-image generation, while maintaining strong performance on multimodal understanding tasks like image captioning, visual grounding, and VQA tasks.


The code, data and models are in preparation. 
