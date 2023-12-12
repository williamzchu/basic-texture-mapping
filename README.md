# basic-texture-mapping
 
Basic mapping of texture on a teapot, and a cubemap with images with GLSL, webGL.

![image](https://github.com/williamzchu/basic-texture-mapping/assets/59345558/a3791775-4132-41da-a1a8-1c5e592c306a)

![image](https://github.com/williamzchu/basic-texture-mapping/assets/59345558/c91aa388-0757-40ab-abca-2e0fea07e527)

Can be accessed by starting an http server (ex: python -m http.server), as webGL requires images to be loaded from secure contexts, and navigating to "texturemap.html"

As its a basic shader, disregards many aliasing artifacts (choppy pixels) without mipmapping techniques.

![image](https://github.com/williamzchu/basic-texture-mapping/assets/59345558/647e1f00-43a1-4bc1-a46b-b4c2700b4b98)

