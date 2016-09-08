# algebraicFunctions
I am starting this project to present a method for computing and web-based displaying of algebraic functions w(z) using a combination of Mathematica, WebGL and Javascript. 
The functions are of the form:
f(z,w)=a_0(z)+a_1(z)w+a_2(z)w^2+...+a_n(z)w^n=0  where z and w are complex numbers and a_i(z) is a polynomial function of z.
A description of the functions can be found at jujusdiaries.com which includes index.html embedded  in Section 1 of that blog.
The file branch1BarycentricData.js contains the vertices, normals, indexes, and barycentric points for the three branches of the function.  This data is in java format such as "var branchOneVertexes=[v1,v2,...,vn]; var branchOneNormals=[n1,n2,...,nn]" and so forth. This data is computed using the method described in the blog and then formatted in Mathematica as a java file that is then read by the script.
I am new to WebGL, HTML, and Javascript so appreciate any suggestions for improvements.
