# Mathematical-modelling
# Rational Fractal Spline

## 📌 Introduction  
Rational Fractal Spline is an advanced interpolation technique in approximation theory, leveraging **fractal interpolation functions (FIFs)**. It is useful for modeling complex natural structures such as **mountain ranges, cloud tops, and forest horizons**.

This approach extends **rational cubic interpolation** by introducing **shape parameters** and **scaling factors**, providing greater flexibility in data approximation.

## 🚀 Features  
✅ **Shape Preservation** – Ensures monotonicity, positivity, and convexity.  
✅ **Adaptive Rational Cubic IFS** – More flexible than classical cubic splines.  
✅ **Efficient Computation** – Automated shape parameter selection.  

## 🔍 Problem & Solution  
### ⚠️ Problem:  
- Traditional fractal interpolation may distort monotonicity, positivity, or convexity.  
- Manual tuning of parameters is inefficient.

### ✅ Solution:  
- **Trial-and-error tuning** (less precise).  
- **Automated selection of scaling factors and shape parameters** for improved shape preservation.

## 📁 Implementation  
- Define **Iterated Function System (IFS)** for given dataset **\((x_i, f_i)\)**.  
- Compute scaling factors **\(\alpha_i\)** and shape parameters **\(v_i, w_i\)**.  
- Apply **rational cubic FIF** for smooth interpolation.  

## 🛠 Installation  
```bash
git clone https://github.com/yourusername/Rational-Fractal-Spline.git
cd Rational-Fractal-Spline

