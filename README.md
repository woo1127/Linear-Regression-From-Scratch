## Multiple Linear Regression From Scratch

### Compute Prediction
### $f_{\vec{w},b}(\vec{x}) = \vec{w} \cdot \vec{x} + b$

<br/>

### Compute Cost Function
### $J(\vec{w},b) = \frac{1}{2m} \sum_{i=0}^{m} (f_{\vec{w},b}(\vec{x}^{(i)}) - y^{(i)})^2 $

<br/>

### Compute Gradient of Cost
### $\frac{\partial J}{\partial \vec{w}} = \frac{1}{m} \vec{x}^T \cdot (f_{\vec{w},b}(\vec{x}) - y)$
### $\frac{\partial J}{\partial b} = \frac{1}{m} (f_{\vec{w},b}(\vec{x}) - y)$

<br/>

### Gradient Descent
### $w_j := w_j - \alpha \frac{\partial J}{\partial \vec{w}}$
### $b := b - \alpha \frac{\partial J}{\partial b}$

