# $$HTML$$

![html](https://1.bp.blogspot.com/-BvjPllHHXRs/X4_vl8sH0FI/AAAAAAAABmk/2hoBV42tgDgWoz25dWkXVAh556F_PWrewCNcBGAsYHQ/s1200/html.jpeg)

## Images in HTML

In the beginning, the Web was just text, and it was really quite boring. Fortunately, it wasn't too long before the ability to embed images (and other more interesting types of content) inside web pages was added. There are other types of multimedia to consider, but it is logical to start with the humble < img > element, used to embed a simple image in a webpage. In this article we'll look at how to use it in depth, including the basics, annotating it with captions using < figure >, and detailing how it relates to CSS background images.

### How do we put an image on a webpage?

In order to put a simple image on a webpage, we use the < img > element. This is an empty element (meaning that it has no text content or closing tag) that requires a minimum of one attribute to be useful — src (sometimes spoken as its full title, source). The src attribute contains a path pointing to the image you want to embed in the page, which can be a relative or absolute URL, in the same way as href attribute values in < a > elements.

So for example, if your image is called dinosaur.jpg, and it sits in the same directory as your HTML page, you could embed the image like so:

< img src="dinosaur.jpg" >

## HTML color codes and names

1. Color picker : Find that perfect color with our color picker and discover beautiful color harmonies, tints, shades and tones; input Hex color codes, RGB and HSL values, and generate HTML, CSS and SCSS styles.

2. Color Chart : Looking for some already great color combinations? Our color chart features flat design colors, Google's Material design scheme and the classic web safe color palette, all with Hex color codes.

3. Color Names : Can't remember all 140 HTML color names? We've got you covered, check out our guide for a quick reference of all the HTML color names grouped by color.

## HTML Text

### HTML contains several elements for defining text with a special meaning.

### HTML Formatting Elements

Formatting elements were designed to display special types of text:

+ < b > - Bold text
+ < strong > - Important text
+ < i > - Italic text
+ < em > - Emphasized text
+ < mark > - Marked text
+ < small > - Smaller text
+ < del > - Deleted text
+ < ins > - Inserted text
+ < sub > - Subscript text
+ < sup > - Superscript text

### HTML < b > and < strong > Elements

The HTML < b > element defines bold text, without any extra importance.

< b >This text is bold< /b >

The HTML < strong > element defines text with strong importance. The content inside is typically displayed in bold.

< strong >This text is important!< /strong >

## JPEG vs PNG vs GIF

### 1. JPEG :
is a lossy compression specification that takes advantage of human perception. It can achieve compression ratios of 1:10 without any perceivable difference in quality. Beyond this, the compression artefacts become more prominent. Because JPEG compression works by averaging out colours of nearby pixels (read Discrete Cosine Transform), JPEG images are best suited for photographs and paintings of natural scenes where the variations in colour and intensity are smooth. However, if an image contains text or lines, where a sharp contrast between adjacent pixels is desired to highlight the proper shape, this lossy compression technique does not yield good results.

### 2. PNG : 
is a lossless image format using DEFLATE compression. No data is lost during compression and no compression artefacts are introduced in the image. For this reason, a PNG image would retain higher quality than an image than JPEG and would look a lot sharper, it would also occupy more space on the disk. This makes it unsuitable for storing or transferring high-resolution digital photographs but a great choice for images with text, logos and shapes with sharp edges.

### 3. GIF : 
is also a lossless image format that uses LZW compression algorithm. It was favoured over PNG for simple graphics in websites in its early days because the support of PNG was still growing. Given that PNG is now supported across all major devices and that PNG compression is about 5–25% better than GIF compression, GIF images are now mainly used only if the image contains animations.

### For more info [click here](https://blog.imagekit.io/jpeg-vs-png-vs-gif-which-image-format-to-use-and-when-c8913ae3e01d)