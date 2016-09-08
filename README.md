# algebraicFunctions
I am starting this project to present a method for computing and web-based displaying of algebraic functions using a combination of Mathematica, WebGL and Javascript. 
A description of the work I am doing can be found at my blog:  jujusdiaries.com where I have an embedded real-time 3D viewer of the function described in Section 1.
The file branch1BarycentricData.js contains the vertices, normals, indexes, and barycentric points for the three branches of the function.  This data is in java format such as "var branchOneVertexes=[v1,v2,...,vn]; var branchOneNormals=[n1,n2,...,nn]" and so forth. This data is computed using the method described in my blog and then formatted in Mathematica as a java file that is read by the script.
