Recreation of SwapChain

C:\VulkanSDK\Vulkan\Bin
C:\ARTR\01-Vulkan\01-Windows\03-Triangle\31-Ortho\Shaders

Shader Compliation for vertex
glslangValidator.exe -V -H -o Shader.vert.spv Shader.vert

Shader Compliation for fragment
glslangValidator.exe -V -H -o Shader.frag.spv Shader.frag

GLM is CPP File due to VK.c change to CPP but its whole containt is C base no cpp features inclued

Shader are same as Ortho

Taken base code as:C:\ARTR\artr01_036_rohit-kshirsagar\01-Vulkan\01-Windows\03-Triangle\32-Perspective\02-Corrected-Y\02-PerspectiveMatrix-Way

Triangle Will be not be defaulted means Normal View Triangle and  in Perspective