# NICOLAS GIANNANTONIO
Study of WebGL, WebGPU, and web performance with vanilla JS.

Articles I wish I had earlier:
- [Object fit with webgl](https://medium.com/@nicolasgiannantonio/object-fit-in-webgl-5c50cf6a0c00)
- [Background-cover - ogl](https://medium.com/@nicolasgiannantonio/background-cover-effect-with-webgl-4ea26138c998)
- [Simple post-processing effect - ogl](https://medium.com/@nicolasgiannantonio/post-processing-effect-18b9c3be1c80)
<!--
- "M0,0 C0.208,0.438 0.062,1 1,1 "

- 1.61803398875
- mix(vec3(noise(vec2(uTime + st.x - st.y))), vec3(1.0), wave)

///
PERMET DE FAIRE CHANGER D'IMAGE DE GAUCHE À DROITE
vec2 fractUV = cos(fract(vUv / 10.0) / 100.0);
uv.x += (abs(fractUV.x) * 10.0) * uInt / 10.0;
                    

///

/*------------------------------
Background Cover UV
--------------------------------
u = basic UV
s = plane size
i = image size
------------------------------*/
vec2 CoverUV(vec2 u, vec2 s, vec2 i) {
  float rs = s.x / s.y; // Aspect plane size
  float ri = i.x / i.y; // Aspect image size
  vec2 st = rs < ri ? vec2(i.x * s.y / i.y, s.y) : vec2(s.x, i.y * s.x / i.x); // New st
  vec2 o = (rs < ri ? vec2((st.x - s.x) / 2.0, 0.0) : vec2(0.0, (st.y - s.y) / 2.0)) / st; // Offset
  return u * s / st + o;
}

- ease-in-circ: cubic-bezier(0.6,0.04,0.98,0.335);
- ease-out-circ: cubic-bezier(0.075,0.82,0.165,1);
- ease-in-out-circ: cubic-bezier(0.785,0.135,0.15,0.86);


**nicolas-giannantonio/Nicolas-Giannantonio** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.
- ease-in-cubic: cubic-bezier(0.55,0.055,0.675,0.19);
- ease-in-quart: cubic-bezier(0.895,0.03,0.685,0.22);
- ease-in-quint: cubic-bezier(0.755,0.05,0.855,0.06);
- ease-in-expo: cubic-bezier(0.95,0.05,0.795,0.035);

- ease-in-out-quad: cubic-bezier(0.455,0.03,0.515,0.955);
- ease-in-out-cubic: cubic-bezier(0.645,0.045,0.355,1);
- ease-in-out-quart: cubic-bezier(0.77,0,0.175,1);
- ease-in-out-quint: cubic-bezier(0.86,0,0.07,1);
- ease-in-out-expo: cubic-bezier(1,0,0,1);

- ease-out-quad: cubic-bezier(0.25,0.46,0.45,0.94);
- ease-out-cubic: cubic-bezier(0.215,0.61,0.355,1);
- ease-out-quart: cubic-bezier(0.165,0.84,0.44,1);
- ease-out-quint: cubic-bezier(0.23,1,0.32,1);
- ease-out-expo: cubic-bezier(0.19,1,0.22,1);

- ease-in-quad: cubic-bezier(0.55,0.085,0.68,0.53);
-->
