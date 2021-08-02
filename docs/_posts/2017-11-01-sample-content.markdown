---
layout: default
title:  "Paper"
date:   2017-09-01 17:50:00
categories: main
---

<img src="{{"/assets/architecture.jpg" | prepend: site.baseurl }}" />

## Abstract

We propose a unified formulation for the problem of 3D human pose estimation from a single raw RGB
image that reasons jointly about 2D joint estimation and 3D pose reconstruction to improve both
tasks. We take an integrated approach that fuses probabilistic knowledge of 3D human pose with a
multi-stage CNN architecture and uses the knowledge of plausible 3D landmark locations to refine
the search for better 2D locations. The entire process is trained end-to-end, is extremely
efficient and obtains state-of-the-art results on Human3.6M outperforming previous approaches both
on 2D and 3D errors.

## Examples on MPII dataset

<table cellspacing="0" cellpadding="0">
	<tr>
		<td style="width:25%;" align="center"><img src="{{"/assets/MPII/1_042500241.jpg" | prepend: site.baseurl }}" class="img_table" /></td>
		<td style="width:25%;" align="center"><img src="{{"/assets/MPII/0001.jpg" | prepend: site.baseurl }}" class="img_table"/></td>
		<td style="width:25%;" align="center"><img src="{{"/assets/MPII/3_003836155.jpg" | prepend: site.baseurl }}" class="img_table" /></td>
		<td style="width:25%;" align="center"><img src="{{"/assets/MPII/0003.jpg" | prepend: site.baseurl }}" class="img_table"/></td>
	</tr>
	<tr>
		<td style="width:25%;" align="center"><img src="{{"/assets/MPII/28_027792201.jpg" | prepend: site.baseurl }}" class="img_table" /></td>
		<td style="width:25%;" align="center"><img src="{{"/assets/MPII/img0028.jpg" | prepend: site.baseurl }}" class="img_table"/></td>
		<td style="width:25%;" align="center"><img src="{{"/assets/MPII/32_056733993.jpg" | prepend: site.baseurl }}" class="img_table" /></td>
		<td style="width:25%;" align="center"><img src="{{"/assets/MPII/img0032.jpg" | prepend: site.baseurl }}" class="img_table"/></td>
	</tr>
	<tr>
		<td style="width:25%;" align="center"><img src="{{"/assets/MPII/38_023374079.jpg" | prepend: site.baseurl }}" class="img_table" /></td>
		<td style="width:25%;" align="center"><img src="{{"/assets/MPII/0038.jpg" | prepend: site.baseurl }}" class="img_table"/></td>
		<td style="width:25%;" align="center"><img src="{{"/assets/MPII/42_071336755.jpg" | prepend: site.baseurl }}" class="img_table" /></td>
		<td style="width:25%;" align="center"><img src="{{"/assets/MPII/img0042.jpg" | prepend: site.baseurl }}" class="img_table"/></td>
	</tr>
	<tr>
		<td style="width:25%;" align="center"><img src="{{"/assets/MPII/50_083578744.jpg" | prepend: site.baseurl }}" class="img_table" /></td>
		<td style="width:25%;" align="center"><img src="{{"/assets/MPII/0050.jpg" | prepend: site.baseurl }}" class="img_table"/></td>
		<td style="width:25%;" align="center"><img src="{{"/assets/MPII/84_086634144.jpg" | prepend: site.baseurl }}" class="img_table" /></td>
		<td style="width:25%;" align="center"><img src="{{"/assets/MPII/0084.jpg" | prepend: site.baseurl }}" class="img_table"/></td>
	</tr>
	<tr>
		<td style="width:25%;" align="center"><img src="{{"/assets/MPII/16_013562662.jpg" | prepend: site.baseurl }}" class="img_table" /></td>
		<td style="width:25%;" align="center"><img src="{{"/assets/MPII/img0016.jpg" | prepend: site.baseurl }}" class="img_table"/></td>
		<td style="width:25%;" align="center"><img src="{{"/assets/MPII/34_076858133.jpg" | prepend: site.baseurl }}" class="img_table" /></td>
		<td style="width:25%;" align="center"><img src="{{"/assets/MPII/0034.jpg" | prepend: site.baseurl }}" class="img_table"/></td>
	</tr>
	<tr>
		<td style="width:25%;" align="center"><img src="{{"/assets/MPII/45_044908796.jpg" | prepend: site.baseurl }}" class="img_table" /></td>
		<td style="width:25%;" align="center"><img src="{{"/assets/MPII/img0045.jpg" | prepend: site.baseurl }}" class="img_table"/></td>
		<td style="width:25%;" align="center"><img src="{{"/assets/MPII/92_093682246.jpg" | prepend: site.baseurl }}" class="img_table" /></td>
		<td style="width:25%;" align="center"><img src="{{"/assets/MPII/0092.jpg" | prepend: site.baseurl }}" class="img_table"/></td>
	</tr>
</table>

## Videos

<video controls="" autoplay="" muted="" class="video" width="100%">
	<source src="{{"/assets/media/video_pipeline.mp4" | prepend: site.baseurl }}" type="video/mp4">
</video>

<video controls="" autoplay="" muted="" class="video" width="100%">
	<source src="{{"/assets/media/video_results.mp4" | prepend: site.baseurl }}" type="video/mp4">
</video>


## BibTeX

{% highlight bibtex %}
@InProceedings{Tome_2017_CVPR,
	author = {Tome, Denis and Russell, Chris and Agapito, Lourdes},
	title = {Lifting From the Deep: Convolutional 3D Pose Estimation From a Single Image},
	booktitle = {The IEEE Conference on Computer Vision and Pattern Recognition (CVPR)},
	month = {July},
	year = {2017}
}
{% endhighlight %}


## Acknowledgements

This work has been supported by the [SecondHands project](https://secondhands.eu/), funded from the
EU Horizon 2020 Research and Innovation programme under grant agreement No 643950.

<div style="text-align: center;">
	<div class="aknowledgments_img">
	<img src="{{"/assets/Second-hands-logo_final_sml.jpg" | prepend: site.baseurl }}"/>
	</div>
	<div class="aknowledgments_img">
	<img src="{{"/assets/eu-flag.gif" | prepend: site.baseurl }}"/>
	</div>
</div>