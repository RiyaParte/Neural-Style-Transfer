# Neural-Style-Transfer

link to download the pretrained model: https://www.vlfeat.org/matconvnet/pretrained/

To test on your own images:
1. Click on "File -> Open" in the upper tab of the notebook
2. Go to "/images" and upload your images (requirement: (WIDTH = 300, HEIGHT = 225)), rename them "content.png" and "style.png" for example.
3. Change the code in part from :
content_image = scipy.misc.imread("images/louvre.jpg")
style_image = scipy.misc.imread("images/claude-monet.jpg")
to:
content_image = scipy.misc.imread("images/content.jpg")
style_image = scipy.misc.imread("images/style.jpg")
4. Rerun the cells (you may need to restart the Kernel in the upper tab of the notebook).
