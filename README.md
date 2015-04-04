# colorcor
Create colored correlation matrices in Stata

The goal is to create a simple and fast program that produces colored correlation matrices.
The syntax is

colorcor var1 var2 var3....varN,nonsig(gray)

It produces a correlation matrix where red indicates negative correlations and green indicates positive correaltions. The stronger the correlation the darker the color. The option nonsig allows for marking non-significant correlations. 

To do:
- Clean file
- Remove dependency from reg command (add manual calc. of correlation coefficient).
- Create option for significance levels
- show correlation coefficients


![alt tag](https://github.com/hhsievertsen/colorcor/blob/master/example.png)
