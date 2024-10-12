# MEME_MATE
The code imports necessary libraries for text generation, image processing, and web scraping, including random, textwrap, requests, PIL, transformers, BeautifulSoup, and others.

A GPT-2 text generation model is initialized using Hugging Face's pipeline to generate meme captions based on a prompt.

The generate_caption function creates a meme caption by generating a short text from the GPT-2 model, based on the input prompt, and returns the first sentence.

The download_image function scrapes Google Images for an image related to the search query, randomly selects one image from the results, and downloads it.

The add_caption_to_image function takes the downloaded image, wraps the generated caption to fit within the image, and overlays the caption on the image using a specified font, aligning it centrally at the bottom of the image.

The generate_meme function ties together the image search, caption generation, and caption addition processes to create a complete meme and save it to the specified output path.

In the main block, the user is prompted for an image search query and a meme prompt, then the generate_meme function is executed to create and save the meme as a .jpg file.






