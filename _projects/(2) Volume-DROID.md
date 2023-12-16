---
name: Volume-DROID - All you need is a camera!
tools: [Robotics, Perception, CV]
image: https://github.com/peterstratton/Volume-DROID/raw/main/figures/output.gif
description: Volumetric semantic mapping using monocular video
---
<div class="center-image">
<img alt="Teaser Figure" src="https://github.com/peterstratton/Volume-DROID/raw/main/figures/output.gif" />
</div>

<div class="project-links" markdown="1" style="display: flex; justify-content: center; align-items: center">
[![](/assets/logos/acrobat.svg){:
    style="height: 1.1em;" 
    class="text-logo"
 } Report](https://arxiv.org/pdf/2306.06850.pdf){:
    style="background-color: #24292F; color: #FFFFFF; width: 80px; text-align: center;" 
    class="btn btn-grey" 
    target="_blank" 
    rel="noopener noreferrer" 
  }
[![](/assets/logos/github-mark.svg){: 
    style="height: 1.1em;" 
    class="text-logo" 
} Code](https://github.com/peterstratton/Volume-DROID){: 
    style="background-color: #24292F; color: #FFFFFF; width: 80px; text-align: center;" 
    class="btn btn-grey" 
    target="_blank" 
    rel="noopener noreferrer" 
}
</div>

Volume-DROID is a novel SLAM architecture created by combining the recent works: DROID-SLAM and NeuralBKI. Volume-DROID takes camera images (monocular or stereo) or frames from video as input and outputs online, 3D semantic mapping of the environment via combination of DROID-SLAM, point cloud registration, off-the-shelf semantic segmentation and ConvBKI. The novelty of our method lies in the fusion of DROID-SLAM and ConvBKI by the introduction of point cloud generation from RGB-Depth frames and optimized camera poses. By having only camera images or a stereo video as input, we achieved functional real-time online 3D semantic mapping.

All of our code is original, adapted from the NeuralBKI codebase, or adapted from the DROID-SLAM codebase.

NeuralBKI code adapted from: https://github.com/UMich-CURLY/NeuralBKI
DROID-SLAM code adapted from: https://github.com/princeton-vl/DROID-SLAM

