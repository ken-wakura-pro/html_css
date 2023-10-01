# Image Markup
Images on a webpage can be used for logos, photographs, illustrations, diagrams, or charts.
Images are added using ```img``` element or can be included using CSS using the background-image property.
Images can be used to set the tone for a site in less time than it takes to read a description.
If you are building a site from scratch, it is good practice to create a folder, ```images```, for all the images the site uses. As the website grows, keeping images in a separate folder helps you understand how the site is organized. On a big site, you might like to add subfolders inside the 'images' folder.
- ```img``` element is an empty element and must have the following attributes:
	+ ```src```: Tells the browser where it can find the image file. This is usually a relative URL
	+ ```alt```: Provides a text description of the image which describes the image if you cannot see it. the text used in the alt attribute is often referred to as <b>alt text</b>. It should give an accurate description of the image content so it can be understood by screen reader software (used by people with visual impairments) and search engines. If the image is just to make the page look more attractive (and it has no meaning, such as a graphic dividing line), then the alt attribute should still be used but the quotes should be left empty
	+ ```title```: Provide additional information about the image. Most browsers will display the content of this attribute in a tooltip when the user hovers over the image.
	+ ```height```: this specifies the height of the image in pixels
	+ ```width```: specifies the width of the image in pixels
(The size of the images is increasingly being specified using CSS rather than HTML.)

### Image formats
When creating images for the web, remember the following 3 rules:
1. Save the images in the right format (jpeg, gif, or png)
2. Save the images at the right size (in pixels)
3. Use the correct resolution (72 pixels per inch)
Image formats:
- JPEG: This should be used whenever you have many different colors in a picture. Example photograph that features snow, grass, or an overcast sky.
- GIF or PNG: This should be used when saving images with few colors or large areas of the same color. Pictures that have an area that is filled with exactly the same color (flat color). Logs, illustrations, diagrams
Images you use on your website should be saved with the same width and height that you want them to appear on the page.

### Image Resolution
- When cropping images, it is important not to lose valuable information. It is best to source images that are the correct shape if possible.
- Images created for the web should be saved at a resolution of 72 ppi. The higher the resolution of the image, the larger the size of the file.
- JPGs, GIFs, and PNGs belong to a type of image format known as bitmap. They are made up of lots of miniature squares. 
- Vector images differ from bitmap images and are resolution-independent. Vector images are commonly created in programs such as Adobe Illustrator
- The advantage of creating line drawings in vector format is that you can increase the dimensions of the image without affecting the quality of it.
- Scalable Vector Graphics (SVG) are a relatively new format used to display vector images directly on the web (eliminating the need to create bitmap versions of them). 
- Animated GIFs show several frames of an image in sequence and therefore can be used to create simple animations

### Transparency
Creating an image that is partially transparent ("See-through") for the web involves selecting one of two formats: transparent GIF or PNG.

### Figure and Figure caption
- ```figure```: The figure element can be used to contain images and their caption so that the two are associated. You can have more than one image inside the 'figure' element as long as they all share the same caption.
- ```figcaption```: Used to add a caption to an image
