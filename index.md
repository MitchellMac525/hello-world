## Atomic Force Microscopy

AFM is a type of scanning probe microscopy with very high resolution that is on the scale of nanometers, or fractions of nanometers. It works by scanning a small cantilever, which is a long projecting beam with a tip, over the surface of a smaple. The tip at the end of the cantilever makes contact with the surace, bending the cantilever and changing the amount of laser light reflected into the photodiode. The height of the cantilever is then adjusted to restore the response signal, resulting in the measures cantilever height tracing the surface of the sample.   
![AFM Diagram](https://upload.wikimedia.org/wikipedia/commons/5/5e/AFMsetup.jpg)  
![AFM Sample Reading](https://upload.wikimedia.org/wikipedia/commons/0/05/3D_Topografic_AFM_image.jpg)  

## The Problem
When using AFM to detect molecules of a sample, issues can arise. There may be multiple molecules present in one image, making it hard to differentiate from the beginning of one molecule to the end of the other. Though AFM is a high resolution scanner, images from scanning a sample may still come out to be rather blurry. Some AFM scans may result in higher detail of one molecule, displaying certain features that are void in other images of the same type of molecule. Since AFM operates at such a small scale, little things like dust can distrupt a scan, poluting an image with noise.  


## The Research 
There was a research paper published by X that demonstrated a solution to these many problems that may arise. They followed a set procedure in order to analyse and assess each image in order to pull certain qualities from various images in order to make the most detailed image that accurately represents the molecule. ImageJ / Nature Paper  

## Our Solution
Our team used the procedures defined in the Nature paper as a road map to solving these problems for our sponsors. We started with performing a Gaussian filter on images that were to be used, then filtered them in order to remove any noise. We then moved to cropping out individual, whole molecules of an image in order to perfom bicubic expansion, identified molecule centers and tracked invidual molecules as they related to their original iamge. Next we rotate and align cropped images for overlapping and use of the opensource ImageJ software that the Nature paper used.     

You can use the [editor on GitHub](https://github.com/MitchellMac525/hello-world/edit/gh-pages/index.md) to maintain and preview the content for your website in Markdown files.

Whenever you commit to this repository, GitHub Pages will run [Jekyll](https://jekyllrb.com/) to rebuild the pages in your site, from the content in your Markdown files.

### Markdown

Markdown is a lightweight and easy-to-use syntax for styling your writing. It includes conventions for

```markdown
Syntax highlighted code block

# Header 1
## Header 2
### Header 3

- Bulleted
- List

1. Numbered
2. List

**Bold** and _Italic_ and `Code` text

[Link](url) and ![Image](src)
```

For more details see [Basic writing and formatting syntax](https://docs.github.com/en/github/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax).

### Jekyll Themes

Your Pages site will use the layout and styles from the Jekyll theme you have selected in your [repository settings](https://github.com/MitchellMac525/hello-world/settings/pages). The name of this theme is saved in the Jekyll `_config.yml` configuration file.

### Support or Contact

Having trouble with Pages? Check out our [documentation](https://docs.github.com/categories/github-pages-basics/) or [contact support](https://support.github.com/contact) and we’ll help you sort it out.
