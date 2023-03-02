# Implemented basic asic Neural Network from scratch using NumPy and PyTorch and tensorflow and JAX


* Implemented a 3 layer Neural Network using a 3 variable linear equation(plot reperesenting the equation)

**y = 6x^3 + x^2 + x + 1**

`Back Propagation without using relu layer:`


![image](https://user-images.githubusercontent.com/111466561/222329717-d50006a0-4d4e-4f19-8c8b-b65a840aad6f.png)


`Our function against the linear model:`


![image](https://user-images.githubusercontent.com/111466561/222330656-a5bfbb55-7194-43d3-95e7-667d8a516b34.png)



* To avoid this underfitting, we use activation function(relu) to introduce non linearity, where it clips all values less than 0 to 0 and leave other values as is.




`After adding relu layer:`

![image](https://user-images.githubusercontent.com/111466561/222329884-07db27d1-79d9-43a8-a73d-f4874546262a.png)




`After updating weights with lr = 0.01, non-linear function fit the model:`

![image](https://user-images.githubusercontent.com/111466561/222329993-cbbd0da7-af96-4865-8c98-76f2ad109f07.png)


* Using pytorch and tensorflow framewroks, implemented the above neural network functionality.



`References:`

https://colab.research.google.com/drive/1HS3qbHArkqFlImT2KnF5pcMCz7ueHNvY?usp=sharing&authuser=1#scrollTo=EGkS6nN6dQazLinks to an external site.


https://docs.google.com/presentation/d/13Oo5gXwcsoq9oMC4XriAyxkvgicatBxfI4cZzDhRyiE/edit#slide=id.g826a355833_0_525


https://colab.research.google.com/drive/1HS3qbHArkqFlImT2KnF5pcMCz7ueHNvY?usp=sharing&authuser=1#scrollTo=EGkS6nN6dQazLinks to an external site.


https://colab.research.google.com/drive/1UCJt8EYjlzCs1H1d1X0iDGYJsHKwu-NO?authuser=1#scrollTo=KC5RgwGeBP-9


https://colab.research.google.com/drive/1UCJt8EYjlzCs1H1d1X0iDGYJsHKwu-NO?authuser=1#scrollTo=KC5RgwGeBP-9Links to an external site.


https://colab.research.google.com/drive/1UCJt8EYjlzCs1H1d1X0iDGYJsHKwu-NO?authuser=1#scrollTo=WavMVtXGQk-z


https://colab.research.google.com/drive/1UCJt8EYjlzCs1H1d1X0iDGYJsHKwu-NO?authuser=1#scrollTo=SyC7KfV-YcYS


https://colab.research.google.com/drive/169PfzM0kvtA5UP4k6Sl1yCG9tsE2MLia?authuser=1#scrollTo=C_2FyZeXjHd1
