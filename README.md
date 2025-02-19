# BrightML

Low Light Image Enhancement Techniques

Research in low-light image enhancement has gained significant momentum in recent years due to the challenges posed by images with poor illumination, such as those affected by intense shadows, uneven lighting, backlighting, or
taken at night. These images often suffer from issues like underexposure, noisy artifacts, low contrast and color distortion. Initially, traditional methods, including histogram
equalization and gamma correction, were commonly used to address a few of these challenges. However, recent advancements have shifted towards deep learning techniques, that utilize Convolutional Neural Networks (CNNs)
or Transformers to mitigate these drawbacks. In this paper, we first explore several state-of-the-art low-light image enhancement techniques, implementing and comparing them using Peak Signal-to-Noise Ratio (PSNR) as the 
evaluation metric. This analysis leads us to identify Retinexformer as the best-performing model. Next, we thoroughly examine the output of Retinexformer and uncover the presence of halo artifacts, particularly around sharp edges. The focus of this work then shifts towards investigating and implementing strategies to mitigate these halo effects, aiming to improve the overall quality of enhanced images.
