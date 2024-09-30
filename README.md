# DressRecon: Freeform 4D Human Reconstruction from Monocular Video

### [Website](https://jefftan969.github.io/dressrecon) | [Paper](https://jefftan969.github.io/dressrecon/paper.pdf)

[Jeff Tan](https://jefftan969.github.io/), 
[Donglai Xiang](https://xiangdonglai.github.io/), 
[Shubham Tulsiani](https://shubhtuls.github.io/),
[Deva Ramanan](https://www.cs.cmu.edu/~deva/),
[Gengshan Yang](https://gengshan-y.github.io/)<br>

Abstract: Given a single input video of a human, DressRecon reconstructs a time-consistent 4D body model, including shape, appearance, time-varying body articulations, as well as extremely loose clothing deformation or accessory objects. We propose a hierarchical bag-of-bones deformation model that allows body and clothing motion to be separated. We leverage image-based priors such as human body pose, surface normals, and optical flow to make optimization more tractable. The resulting neural fields can be extracted into time-consistent meshes, or further optimized as explicit 3D Gaussians for high-fidelity interactive rendering.
