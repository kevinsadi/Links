# Links
A list of papers / resources online that have helped me. Mostly about AI / Graphics / Math / Audio.

Learning Resources 
- [LearnCpp](https://www.learncpp.com/) - Amazing resource to learn c++ from scratch. Great for the experienced programmer or new programmer.
- [LearnOpenGL](https://learnopengl.com/) - Describes how to build basic rendering engine from scratch with theory. 
- [The Book of Shaders](https://thebookofshaders.com/) - Resource on slowly learning more and more complicated fragment shaders.
- [Tu Wain Rendering / RayTracing Course](https://www.youtube.com/playlist?list=PLujxSBD-JXgnGmsn7gEyN28P1DnRZG7qi) - Entire course from Tu Wain on RayTracing in cpp
- [Scratchapixel](https://scratchapixel.com/) - Education site that progressively introduces you to the world of computer graphics

Learning Blogs
- [Technical Writing](https://css-tricks.com/technical-writing-for-developers/) - Quick blogpost on technical writing 
- [3D rotations blog](https://thenumb.at/Exponential-Rotations/) - Blog post describing different methods of rotation

Practice Resources
- [godbolt](https://godbolt.org/) - online C/C++/etc. compiler. 
- [Shadertoy](https://www.shadertoy.com/) - Great site to practice with fragment shaders (if I didn't want to use my own engine).
- [RGB -> HSV demo](https://math.hws.edu/graphicsbook/demos/c2/rgb-hsv.html) - Tool to build intuition behind HSV colorspace

Cpp Resources
- [Blog on Build Systems](https://julienjorge.medium.com/an-overview-of-build-systems-mostly-for-c-projects-ac9931494444) - good overview on build systems to compile code to vs2022, xcode, gnu make (premake vs cmake vs ninja vs meson)
- [Unreal Engine 5 Docs](https://docs.unrealengine.com/5.0/en-US/API/Runtime/Engine/Camera/UCameraComponent/) - The documentation for unreal engine 5.

Good Generative Model Papers (as of 2023)
- [Paper Collection](https://kesen.realtimerendering.com/) - List of papers submitted at SIGGRAPH, but very easily accessible]
- [Variable Bitrate Neural Fields](https://nv-tlabs.github.io/vqad/) - use neural fields to compress geometry
- [Terrain Synthesis from DEGs](https://faculty.cc.gatech.edu/~turk/my_papers/terrain_synth_tvcg.pdf) - Use Elevation Models to create terrain that follows a user's sketch
- [StyleGAN](https://github.com/NVlabs/stylegan) - Change traditional GAN architecture to include intermediate latent space. Also style mixing. Best paper to get started with the StyleGAN series. 
- [Prompt-to-Prompt Image Editing with Cross Attention Control](https://arxiv.org/abs/2208.01626) - Change weights of words / add words / replace words in a prompt to edit generative images
- [Neural Codec Language Models are Zero-Shot Text to Speech Synthesizers (VALL-E)](https://valle-demo.github.io/) - Leverage Codec Intermediate space and lots of data to create very good TTS. Can replicate someone's voice or emotion with 3 seconds of input.
- [NeRF-VAE: A Geometry Aware 3D Scene Generative Model](https://arxiv.org/abs/2104.00587) - Use NeRFs to generate novel 3D scenes. Similar idea to autoencoders in general. 
- [Neural Discrete Representation Learning (VQ-VAE)](https://arxiv.org/abs/1711.00937) - Vector quantized Auto Encoders. The same idea as other continuous autoencoders, but the bottle neck is a quantized quassian distribution. Has solid results, and is used in DALL-E 1 and Muse. 
- [eDiff-I: Text-to-Image Diffusion Models with an Ensemble of Expect Denoisers](https://arxiv.org/abs/2211.01324) - Generative Diffusion Models perform better when you have different denoisers for different sections of the denoising process temporally.
- [Get3D: A Generative Model of High Quality 3D Textured Shapes Learned from Images](https://nv-tlabs.github.io/GET3D/) - Use SDFs, differentiable surface modeling, and differentiable rendering to make high-quality 3D textured meshes
- [Text2Tex: Text-driven Texture Synthesis via Diffusion Models](https://arxiv.org/pdf/2303.11396.pdf) - Given a depth -> image diffusion model, generate textures from many different angles. Result in a fully textured mesh. 
- [Discovering Interpretable Directions in the Semantic Latent Space of Diffusion Models](https://arxiv.org/abs/2303.11073) - Find parallels between GAN latent vectors and the latent vectors in diffusion models. 
- [Guided Conditional Diffusion for Controllable Traffic Simulation](https://aiasd.github.io/ctg.github.io/) - Use diffusion to generate controlled and realistic trajectories for traffic between many vehicles. Could be extended to general group behaviors. 


Transformers / Self Attention Based Methods
- [Blog on transformers](https://peterbloem.nl/blog/transformers) - very good blog with code on transformers.
- [Transformer Neural Networks Explained](https://www.youtube.com/watch?v=TQQlZhbC5ps) - Great teaching style and short form video on transformers

Textbooks
- [Physically Based Rendering: From Theory to Implementation](https://www.pbr-book.org/) - Book on Physically Based Rendering, simply meaning the rendering is based on how light behaves in the real world. This book describes how you can use pbr concepts when implementing a ray tracer.
- [Game Engine Architecture (3rd edition)](https://www.gameenginebook.com/) - Fundamental book in game engine architecture
- [Ray Tracing in a weekend](https://raytracing.github.io/books/RayTracingInOneWeekend.html) - Great concise resource that builds a simple ray tracer without an API
- [Real-Time Rendering](https://www.realtimerendering.com/) - Book on real-time rendering techniques 
- [Fundamentals of Computer Graphics](https://learning.oreilly.com/library/view/fundamentals-of-computer/9781482229417/) - This textbook is a good resource for the fundamentals of computer graphics. More helpful if one has not had an introductory class on Computer Graphics.

Videos
- [Stable Diffusion by Computerphile](https://www.youtube.com/watch?v=1CIpzeNxIhU) - Simple but in depth explanation of stable diffusion
- [Stable Diffusion coding by Computerphile](https://www.youtube.com/watch?v=-lz30by8-sU) - More in depth look of the code of stable diffusion
- [Multiplayer in Minecraft Clone](https://www.youtube.com/watch?v=UAUdIQZKV88) - First look at programming multiplayer in cpp
- [The Continuity of Splines](https://www.youtube.com/watch?v=jvPPXbo87ds&t=3975s) - Video essay looking at Splines. Very in depth and informative.
- [The Art of Code](https://www.youtube.com/watch?v=pmS-F6RJhAk) - Youtube channel for fragment shading. 

Math
- [Matrix Decomposition & Algorithms](https://medium.com/mlearning-ai/matrix-decomposition-and-algorithms-675339d8f48a) - Blog post on the overview of matrix decompositons
- [Linear Algebra Notes Annotated](Resources/Linear%20Algebra%20Notes%20Annotated.pdf) - All of my notes from when I took Linear Algebra at Georgia Tech

Git 
- [Forks and Setting Upstreams](https://docs.github.com/en/get-started/quickstart/fork-a-repo)