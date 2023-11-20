# OpenGL-3D-Rendering-Engine
An OpenGL rendering engine written in C++. The engine is small and light. It implements things like shadow mapping, ambient occlusion, and shader application. This engine is made open source through the MPL 2.0 license.

* This is a software rasterizer for OpenGL
* This does not use any existing graphics libraries

I wanted to try and understand the fundamentals of graphics rendering after getting a good GPU for my computer. I initiated a graphics rendering project to understand fundamental concepts, starting with basic 2D shapes and index buffers. This then evolved into a robust 3D rendering engine, featuring shaders, meshes, textures, and advanced lighting techniques (specular, diffuse, Blinn-Phong). Implemented dynamic camera motion, spotlight, point light, and directional lighting.
I further enriched the engine with advanced graphics techniques, including Geometry Shaders, Multi-Object Instancing, Anti-Aliasing, Bloom, High Dynamic Range, Gamma Correction, Shadow Maps, Parallax Occlusion Mapping, and Face-Culling. The result is a visually captivating rendering engine, showcasing the journey from basics to sophisticated graphics programming.

This multifaceted rendering engine encompasses a spectrum of elements, starting with the implementation of shaders, meshes, objects, and textures. Noteworthy features include dynamic camera motion, specular and diffuse lighting, as well as the incorporation of spotlight, point light, directional lighting, and Blinn-Phong Lighting techniques for achieving nuanced and realistic visuals.

The project's evolution didn't stop there; additional graphics techniques were seamlessly integrated to enhance the rendering capabilities. This expansion included the implementation of Geometry Shaders for more complex geometries, Multi-Object Instancing for efficient rendering of numerous objects, and Anti-Aliasing to ensure smooth and artifact-free visuals. Bloom effects were introduced to add a layer of vibrancy, while High Dynamic Range (HDR) and Gamma Correction techniques were applied to achieve a more lifelike representation of light and color.

Delving deeper into the intricacies of rendering, the project also embraced Shadow Maps to cast realistic shadows, Parallax Occlusion Mapping for detailed surface rendering, and Face-Culling to optimize performance by excluding unseen geometry.

As the project unfolded, it evolved into a sophisticated custom 3D rendering engine, showcasing a progression from foundational concepts to advanced visual effects, evident in the captivating screenshots below.

## Compiling
### Ubuntu (and similar)

```sh
bash install-deps-ubuntu.sh
make
cd build/
./ThomasOpenGL.vcxproj
```

## DEVELOPMENT PROCESS

## Loading Verticies
![image](https://github.com/ThomasOli/OpenGL-3D-Rendering-/assets/51518411/02b8ea63-7a48-4bdf-9a18-0d06ba6b9c88)

## Texture Loading
![image](https://github.com/ThomasOli/OpenGL-3D-Rendering-/assets/51518411/788b8765-4116-4332-babd-b587d3265a01)

## Loading 3-D Objects
![image](https://github.com/ThomasOli/OpenGL-3D-Rendering-/assets/51518411/c5fa3f60-68c7-4105-9d0a-0d63eab72481)
![image](https://github.com/ThomasOli/OpenGL-3D-Rendering-/assets/51518411/6fbe571b-1ac2-4ad3-bf37-d7bb3de83074)
![image](https://github.com/ThomasOli/OpenGL-3D-Rendering-/assets/51518411/8293cce4-becb-4104-b77d-e867c2166dbb)

## Camera 
![image](https://github.com/ThomasOli/OpenGL-3D-Rendering-/assets/51518411/2346bb7a-635c-4767-b663-6074c1cd088e)
![image](https://github.com/ThomasOli/OpenGL-3D-Rendering-/assets/51518411/83bcb3b5-f10f-4659-aa31-8228cc1e9c05)

## Lighting
![image](https://github.com/ThomasOli/OpenGL-3D-Rendering-/assets/51518411/53e093c8-86fb-4d1f-932a-07c607b6bac9)

![image](https://github.com/ThomasOli/OpenGL-3D-Rendering-/assets/51518411/ad4418ce-3c7f-4832-b10a-b8fc31db758a)

![image](https://github.com/ThomasOli/OpenGL-3D-Rendering-/assets/51518411/b45b0b95-0dc1-43f2-957d-96535f7704bd)
![image](https://github.com/ThomasOli/OpenGL-3D-Rendering-/assets/51518411/37c34bf4-3c75-4647-9d5d-242dd8d3c6f7) ![image](https://github.com/ThomasOli/OpenGL-3D-Rendering-/assets/51518411/e1969fe3-56f7-4799-a96c-18d2aeef6a0f) ![image](https://github.com/ThomasOli/OpenGL-3D-Rendering-/assets/51518411/fd322e9a-0fb4-4d26-99a0-fecafb0cea41)

## Point Lighting 
![image](https://github.com/ThomasOli/OpenGL-3D-Rendering-/assets/51518411/95ddd32b-1da7-4766-bd70-05dcd9c18717)

![image](https://github.com/ThomasOli/OpenGL-3D-Rendering-/assets/51518411/97b88389-a751-4b41-91c6-6226e7da7bed)
![image](https://github.com/ThomasOli/OpenGL-3D-Rendering-/assets/51518411/579b8192-a0da-4c6b-914e-5cb7f6633e44) ![image](https://github.com/ThomasOli/OpenGL-3D-Rendering-/assets/51518411/313ff162-6267-485c-b5fc-7c7f48f558ff)![image](https://github.com/ThomasOli/OpenGL-3D-Rendering-/assets/51518411/01358389-8bae-48e4-a7a1-69508a0b6c52)


## Directional Lighting

![image](https://github.com/ThomasOli/OpenGL-3D-Rendering-/assets/51518411/f961f48d-748d-4d9b-a873-b5fe093e6ea0)
![image](https://github.com/ThomasOli/OpenGL-3D-Rendering-/assets/51518411/3b056daf-63f7-4e80-909d-091d774f23d4)![image](https://github.com/ThomasOli/OpenGL-3D-Rendering-/assets/51518411/bfdbf8a5-f934-4070-896a-64166e4e9321)

## Spot Light 
![image](https://github.com/ThomasOli/OpenGL-3D-Rendering-/assets/51518411/cff37218-5ca5-4a5a-89e4-ea91d0801f65)
![image](https://github.com/ThomasOli/OpenGL-3D-Rendering-/assets/51518411/4d173057-cfa7-4069-ba94-03e5467655e9)
![image](https://github.com/ThomasOli/OpenGL-3D-Rendering-/assets/51518411/750a04ab-61fc-44aa-adac-1aabc2cfed43)


## Third Party Code
* OpenGL
* GLSL
* GLM.
* GLAD.
* GLFW.
* stb_image.
* pugixml.
* GLM AABB wrapper: ([https://github.com/iauns/cpm-glm-aabb](https://github.com/iauns/cpm-glm-aabb)).

## Resources Used
*  Learn OpenGL.com provides good and clear modern 3.3+ OpenGL tutorials with clear examples. A great resource to learn modern OpenGL aimed at beginners. ([Learn OpenGL - online print edition - Free PDF](https://learnopengl.com/book/book_pdf.pdf))
*  _Fast Extraction of Viewing Frustum Planes from the World-View-Projection Matrix_ ([http://www.cs.otago.ac.nz/postgrads/alexis/planeExtraction.pdf](http://www.cs.otago.ac.nz/postgrads/alexis/planeExtraction.pdf)). Gribb, Hartman (2001).
* _Forward+: Bringing Deferred Lighting to the Next Level_ ([https://takahiroharada.files.wordpress.com/2015/04/forward_plus.pdf](https://takahiroharada.files.wordpress.com/2015/04/forward_plus.pdf)). Harada, McKee, Yang (2012).
* _Solid Wireframe_ ([http://developer.download.nvidia.com/SDK/10/direct3d/Source/SolidWireframe/Doc/SolidWireframe.pdf](http://developer.download.nvidia.com/SDK/10/direct3d/Source/SolidWireframe/Doc/SolidWireframe.pdf)). Nvidia (2007).
* _Physically Based Rendering_ ([https://learnopengl.com/#!PBR/IBL/Specular-IBL](https://learnopengl.com/#!PBR/IBL/Specular-IBL))
* _Variance Shadow Mapping_ ([http://developer.download.nvidia.com/SDK/10.5/direct3d/Source/VarianceShadowMapping/Doc/VarianceShadowMapping.pdf](http://developer.download.nvidia.com/SDK/10.5/direct3d/Source/VarianceShadowMapping/Doc/VarianceShadowMapping.pdf))
* _Tessellated Terrain Rendering with Dynamic LOD_ ([http://victorbush.com/2015/01/tessellated-terrain/](http://victorbush.com/2015/01/tessellated-terrain/))
