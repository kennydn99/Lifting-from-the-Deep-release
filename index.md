# Abstract

We propose a unified formulation for the problem of 3D human pose estimation from a single raw RGB image that reasons jointly about 2D joint estimation and 3D pose reconstruction to improve both tasks. We take an integrated approach that fuses probabilistic knowledge of 3D human pose with a multi-stage CNN architecture and uses the knowledge of plausible 3D landmark locations to refine the search for better 2D locations. The entire process is trained end-to-end, is extremely efficient and obtains state-of-the-art results on Human3.6M outperforming previous approaches both on 2D and 3D errors.

## Material
<div class="material_cell"> <a href="http://openaccess.thecvf.com/content_cvpr_2017/papers/Tome_Lifting_From_the_CVPR_2017_paper.pdf"> <img src="{{"/assets/pdf_thumbnail.png" | prepend: site.baseurl }}" style="width: 150px" alt="pdf thumbnail"/>
<div>PDF</div> </a> </div>

<div class="material_cell"> <a href="http://visual.cs.ucl.ac.uk/pubs/liftingFromTheDeep/res/supp_material.pdf"> <img src="{{"/assets/pdf_thumbnail.png" | prepend: site.baseurl }}" style="width: 150px" alt="pdf thumbnail"/>
<div>Supplementary material</div> </a> </div>

<div class="material_cell"> <a href="http://visual.cs.ucl.ac.uk/pubs/liftingFromTheDeep/res/slides.pdf"> <img src="{{"/assets/slides_thumbnail.png" | prepend: site.baseurl }}" style="width: 150px" alt="slides thumbnail"/>
<div>Slides - PDF</div> </a> </div>

<div class="material_cell"> <a href="http://visual.cs.ucl.ac.uk/pubs/liftingFromTheDeep/res/poster.pdf"> <img src="{{"/assets/poster_thumbnail.jpg" | prepend: site.baseurl }}" style="width: 150px" alt="poster thumbnail"/>
<div>Poster</div> </a> </div>

<div class="material_cell"> <a href="https://github.com/DenisTome/Lifting-from-the-Deep-release"> <img src="{{"/assets/code_thumbnail.png" | prepend: site.baseurl }}" style="width: 150px" alt="code thumbnail"/>
<div>Code</div> </a> </div>

## Examples on MPII dataset
<table> <tr> <td style="width:16.67%;" align="center"><img src="{{"/assets/LiftingFromTheDeep/MPII/1_042500241.jpg" | prepend: site.baseurl }}" class="img_table" /></td> <td style="width:16.67%;" align="center"><img src="{{"/assets/LiftingFromTheDeep/MPII/0001.jpg" | prepend: site.baseurl }}" class="img_table"/></td> <td style="width:16.67%;" align="center"><img src="{{"/assets/LiftingFromTheDeep/MPII/3_003836155.jpg" | prepend: site.baseurl }}" class="img_table" /></td> <td style="width:16.67%;" align="center"><img src="{{"/assets/LiftingFromTheDeep/MPII/0003.jpg" | prepend: site.baseurl }}" class="img_table"/></td> <td style="width:16.67%;" align="center"><img src="{{"/assets/LiftingFromTheDeep/MPII/16_013562662.jpg" | prepend: site.baseurl }}" class="img_table" /></td> <td style="width:16.67%;" align="center"><img src="{{"/assets/LiftingFromTheDeep/MPII/img0016.jpg" | prepend: site.baseurl }}" class="img_table"/></td> </tr> <tr> <td style="width:16.67%;" align="center"><img src="{{"/assets/LiftingFromTheDeep/MPII/28_027792201.jpg" | prepend: site.baseurl }}" class="img_table" /></td> <td style="width:16.67%;" align="center"><img src="{{"/assets/LiftingFromTheDeep/MPII/img0028.jpg" | prepend: site.baseurl }}" class="img_table"/></td> <td style="width:16.67%;" align="center"><img src="{{"/assets/LiftingFromTheDeep/MPII/32_056733993.jpg" | prepend: site.baseurl }}" class="img_table" /></td> <td style="width:16.67%;" align="center"><img src="{{"/assets/LiftingFromTheDeep/MPII/img0032.jpg" | prepend: site.baseurl }}" class="img_table"/></td> <td style="width:16.67%;" align="center"><img src="{{"/assets/LiftingFromTheDeep/MPII/34_076858133.jpg" | prepend: site.baseurl }}" class="img_table" /></td> <td style="width:16.67%;" align="center"><img src="{{"/assets/LiftingFromTheDeep/MPII/0034.jpg" | prepend: site.baseurl }}" class="img_table"/></td> </tr> <tr> <td style="width:16.67%;" align="center"><img src="{{"/assets/LiftingFromTheDeep/MPII/38_023374079.jpg" | prepend: site.baseurl }}" class="img_table" /></td> <td style="width:16.67%;" align="center"><img src="{{"/assets/LiftingFromTheDeep/MPII/0038.jpg" | prepend: site.baseurl }}" class="img_table"/></td> <td style="width:16.67%;" align="center"><img src="{{"/assets/LiftingFromTheDeep/MPII/42_071336755.jpg" | prepend: site.baseurl }}" class="img_table" /></td> <td style="width:16.67%;" align="center"><img src="{{"/assets/LiftingFromTheDeep/MPII/img0042.jpg" | prepend: site.baseurl }}" class="img_table"/></td> <td style="width:16.67%;" align="center"><img src="{{"/assets/LiftingFromTheDeep/MPII/45_044908796.jpg" | prepend: site.baseurl }}" class="img_table" /></td> <td style="width:16.67%;" align="center"><img src="{{"/assets/LiftingFromTheDeep/MPII/img0045.jpg" | prepend: site.baseurl }}" class="img_table"/></td> </tr> <tr> <td style="width:16.67%;" align="center"><img src="{{"/assets/LiftingFromTheDeep/MPII/50_083578744.jpg" | prepend: site.baseurl }}" class="img_table" /></td> <td style="width:16.67%;" align="center"><img src="{{"/assets/LiftingFromTheDeep/MPII/0050.jpg" | prepend: site.baseurl }}" class="img_table"/></td> <td style="width:16.67%;" align="center"><img src="{{"/assets/LiftingFromTheDeep/MPII/84_086634144.jpg" | prepend: site.baseurl }}" class="img_table" /></td> <td style="width:16.67%;" align="center"><img src="{{"/assets/LiftingFromTheDeep/MPII/0084.jpg" | prepend: site.baseurl }}" class="img_table"/></td> <td style="width:16.67%;" align="center"><img src="{{"/assets/LiftingFromTheDeep/MPII/92_093682246.jpg" | prepend: site.baseurl }}" class="img_table" /></td> <td style="width:16.67%;" align="center"><img src="{{"/assets/LiftingFromTheDeep/MPII/0092.jpg" | prepend: site.baseurl }}" class="img_table"/></td> </tr> </table>

## Videos
<div class="paper_videos"> <iframe class="video" src="https://www.youtube.com/embed/ljWHGVgKKsc?ecver=1" frameborder="0" allowfullscreen></iframe>

<iframe class="video" src="https://www.youtube.com/embed/tKfkGttx0qs?ecver=1" frameborder="0" allowfullscreen></iframe>
</div>

## BibTeX
{% highlight bibtex %} @InProceedings{Tome_2017_CVPR, author = {Tome, Denis and Russell, Chris and Agapito, Lourdes}, title = {Lifting From the Deep: Convolutional 3D Pose Estimation From a Single Image}, booktitle = {The IEEE Conference on Computer Vision and Pattern Recognition (CVPR)}, month = {July}, year = {2017} }

## Acknowledgements
This work has been supported by the SecondHands project, funded from the EU Horizon 2020 Research and Innovation programme under grant agreement No 643950.

<img src="{{"/assets/Second-hands-logo_final_sml.jpg" | prepend: site.baseurl }}" class="aknowledgments_img" /> <img src="{{"/assets/eu-flag.gif" | prepend: site.baseurl }}" class="aknowledgments_img" />