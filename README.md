<div align="center"><img src='./image/logo.png' style="height:auto; width: 15%; min-width: 15%; max-width: 200px;"/>
<h1>MSASect2</h1>
<strong>Advanced Cross-section Analysis Software (Available on Windows and MacOS)</strong>  
  <br><br>
</div>

[![Official Website](http://img.shields.io/badge/Website-msasect.com-green?style=flat&logo=world&logoColor=white)](http://www.MSASect.com)
<a href="https://github.com/zsulsw/MSASect2/releases" target="_blank">
<img alt="macOS" src="https://img.shields.io/badge/-macOS-red?style=flat-square&logo=apple&logoColor=white" />
</a>
<a href="https://github.com/zsulsw/MSASect2/releases" target="_blank">
<img alt="Windows" src="https://img.shields.io/badge/-Windows-blue?style=flat-square&logo=windows&logoColor=white" />
</a>
![Status](https://img.shields.io/badge/status-beta-orange)

<!--![Stable Version](https://img.shields.io/badge/version-1.0.6-green)-->
<!--![Platform](https://img.shields.io/badge/platform-windows%20%7C%20macos-red)-->

![Screen Shot Gif](/image/Main-Page.gif)

## 🌟 About the Software
**MSASect2** is a cross-platform software developed for comprehensive analysis of arbitrary cross-sections with nonsymmetric shapes. This includes examining their cross-sectional properties, yield strengths, global and local buckling capacities, etc. The software hosts the advanced numerical algorithms, derived from the research team led by [**Dr. Siwei Liu**](https://www.polyu.edu.hk/cee/people/academic-staff/dr-siwei-liu/) from the Department of Civil and Environmental Engineering at Hong Kong Polytechnic University. **MSASect2** is developed to address design challenges associated with complex and irregular cross-sections, which are increasingly popular in modern structures due to their superior structural efficiency. The software is free for both research and educational use. 

**Please download the latest version:** <td><a href='https://github.com/zsulsw/MSASect2/releases'> <img src='./image/windows.png' style="height:auto; width: 14px" /> <b>Windowes: *.zip </b></a> | </td> <td><a href='https://github.com/zsulsw/MSASect2/releases'> <img src='./image/mac.png' style="height:auto; width: 15px" /> <b>MacOS - Apple Silicon Chips: *.dmg</b></a></td>

If you find the software helpful for your research or have thoughts on collaborative research, we would be delighted to hear from you.

## ⛄ Developers
**Developed by:**

- [**Siwei Liu**](https://www.polyu.edu.hk/cee/people/academic-staff/dr-siwei-liu/) - Assistant Professor, The Hong Kong Polytechnic University, Hong Kong. [**si-wei.liu@polyu.edu.hk**](mailto:si-wei.liu@polyu.edu.hk).
- [**Ronald D. Ziemian**](https://www.bucknell.edu/fac-staff/ronald-ziemian) - Professor, Bucknell University, USA. [**ziemian@bucknell.edu**](mailto:ziemian@bucknell.edu).

**Contributed by (surnames in alphabetical order):**

- Ahmed Hussain Ali Abdelrahman, Liang Chen, Wenlong Gao, Guanhua Li, Weihang Ouyang, and Haoyi Zhang. 

## 💻 Install
<table>
  <tr>
    <td><a href='https://github.com/zsulsw/MSASect2/releases'><img src='./image/windows.png' style="height:auto; width: 14px" /> <b>Windows:</b></a></td>
    <td colspan="2" style="text-align:center"><b>1. Download "Windows-MSASect2-(version number).zip"<br>2. Unzip and Run "MSASect2.exe"</b></td>
  <tr>
    <td><a href='https://github.com/zsulsw/MSASect2/releases'><img src='./image/mac.png' style="height:auto; width: 15px" /> <b>MacOS-ARM:</b></a></td>
    <td><b>1. Download "MacOS-ARM-MSASect2-(version number).dmg"<br>2. Open DMG file and copy "MSASect2" to Application</b></td>
</table>

Visit the **[GitHub Releases](https://github.com/zsulsw/MSASect2/releases)** to download the latest version or any previous release.

## 📕 Functions and Features

### Advanced Analysis Algorithms
+ Cross-section Properties:  
  - **Coordinate Method (CM):** Specifically designed for thin-walled sections modeled via centerlines.
  - **Finite Element Method (FEM):** Suitable for general cross-sections modeled by outlines.
  - Geometric and sectorial properties, elastic and plastic modulus, Wagner coefficients, etc.
+ Section Buckling Analysis:
  - **Finite Strip Method (FSM):** Efficient computational method for thin-walled sections. 
  - **Shell Fintie Element Method (SFEM):** Advanced computational method for the sections modeled via centerlines.
  - Elastic eigen-buckling analysis to evaluate the local, distortional and global buckling behaviors.  
+ Member Buckling Analysis:
  - **Twisting Effects**: As the requirements in American Steel Design Specification (ANSI/AISC 360-22),the buckling behaviors of members with nonsymmetric or monosymmetric sections should be studied for the twisting effects.
  - **Analytical Solutions:** Flexural buckling, lateral torsional buckling, axial-torsional buckling.  
  - **Line Finite Element Method (LFEM)** Buckling analysis using advanced line finite-element, derived based on the nonsymmetric cross-section assumption, for general buckling conditions.
+ Yield-surface Analysis:
  - **Quasi-Newton Divergence-Free Algorithms**:  Robust numerical algorithms for generation of yield surfaces.
  - **Fiber Section Solution:** Stress integration method using fibers is adopted with less computational efficiency but versatile. 
  - **Gaussian Line-Segment Solution** New stress integration method using gaussian line segments for centerline models and very efficient computationally.
  - Initial yield surface, failure surface, strength interaction surfaces at a specific strain status.  
+ Moment Curvature Analysis:
  - **Twisting Effects**: 
  - **Analytical Solution:** Efficient computational method for thin-walled sections. 
  - **Line Finite Element Method (LFEM)** .
  - .  

### User-Friendly UI and Visualization
- Real shapes and details of cross-sections.
- Visualize cross-sections on members and shell element/finite strip models.
- Explore 3D contours of buckling mode shapes.

## 📌 Citation

If you use MSASect2 for academic research, please cite the software using the following:

<details>
<summary><strong>APA Format:</strong> 📋</summary>

Liu, S. W., & Ziemian, R. D. (2023). MSASect2 - Matrix Structural Analysis Software for Arbitrary Cross-sections. Retrieved from http://www.msasect.com

</details>

<details>
<summary><strong>MLA Format:</strong> 📋</summary>

Liu, Si-Wei, and Ziemian, Ronald D. "MSASect2 - Matrix Structural Analysis Software for Arbitrary Cross-sections." 2023. Web. <http://www.msasect.com>
</details>


<!-- If you use MSASect2 for academic research, please cite the software using the following:

**APA:**
```
Liu, S. W., & Ziemian, R. D. (2023). MSASect2 - Matrix Structural Analysis Software for Arbitrary Cross-sections. Retrieved from http://www.msasect.com
```
**MLA:**
```
Liu, Si-Wei, and Ziemian, Ronald D. "MSASect2 - Matrix Structural Analysis Software for Arbitrary Cross-sections." 2023. Web. <http://www.msasect.com>.```
```
-->

## 🎁 Contributing

**Your contributions** are greatly appreciated! If you have any questions or suggestions that could further enhance the software, please don't hesitate to open a [**github issue**](https://github.com/zsulsw/MSASect2/issues). Your input will help make the software even better.

We welcome contributions from the community to help improve and enhance MSASect2. Whether it's code improvements, bug fixes, or new features, your contributions are valuable. If you are interested in research collaborations related to the software's capabilities, please contact Dr. Siwei Liu at Email: [**si-wei.liu@polyu.edu.hk**](mailto:si-wei.liu@polyu.edu.hk).

## ✔️ Disclaimer

**Considerable care** has been taken to ensure the accuracy of this software. However, the user assumes full responsibility for its use, and the developers or distributors will not be liable for any damage caused by the use or misuse of this software. The user should have a thorough understanding of the software's modeling, analysis, and design algorithms, and should compensate for any aspects that are not addressed. 

## 📜 Useful References

- Liu, S.W., Ziemian, R.D., Chen, L., and Chan S.L.:
*"Bifurcation and large-deflection analyses of thin-walled beam-columns with non-symmetric open-sections"*,
Thin-Walled Structures, 2018. 132: p. 287-301,
[DOI](https://doi.org/10.1016/j.tws.2018.07.044)

- Liu, S.W., Gao, W.L., & Ziemian, R.D.:
*"Improved line-element formulations for the stability analysis of arbitrarily- shaped open-section beam-columns"*,
Thin-Walled Structures, 2019. 144, 106290,
[DOI](https://doi.org/10.1016/j.tws.2019.106290)

- Gao, W.L., Abdelrahman, A.H.A., Liu, S.W., & Ziemian, R.D.:
*"Second-order dynamic time-history analysis of beam-columns with nonsymmetrical thin-walled steel sections"*,
Thin-Walled Structures, 2021. 160(3), 107367,
[DOI](https://doi.org/10.1016/j.tws.2020.107367)

- Liu, S.W., Pekoz, T., Gao, W.L., Ziemian, R.D., & Crews, J:
*"Frame analysis and design of industrial rack structures with perforated cold-formed steel columns"*,
Thin-Walled Structures, 2021. 163, 107755,
[DOI](https://doi.org/10.1016/j.tws.2021.107755)

- Chen, L., Gao, W.L., Liu, S.W., Ziemian, R.D., & Chan, S.L.:
*"Geometric and material nonlinear analysis of steel members with nonsymmetric sections"*,
Journal of Constructional Steel Research, 2022. 198, 107537,
[DOI](https://doi.org/10.1016/j.jcsr.2022.107537)

