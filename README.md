# Image Filters
A simple image postprocessing extension for [stable diffusion webui](https://github.com/AUTOMATIC1111/stable-diffusion-webui).
Applies various effects to generated images in pixel space just before they're saved. Works with txt2img, img2img, and in the extras tab.
Pilgram filters courtesy of [akiomik](https://github.com/akiomik/pilgram).

## Notes
If, after updating, certain values are not displaying correctly in the webui, you should remove all lines containing `customscript/image_filters.py` from your `user-config.js` file in the root directory.
You can also edit the maximum values in the same file to your liking.

To move this script up or down in hierarchy you should rename the `stable-diffusion-webui-image-filters` directory in `extensions`. The scripts are loaded in alphabetical order. 

## Preview
![preview](https://user-images.githubusercontent.com/123005779/224696707-752b9521-8a92-4849-b122-98711b4af8fd.jpg)

## Comparison
Base | Filtered
---- | --------
![base](https://user-images.githubusercontent.com/123005779/224670233-00e09bbb-b889-4b34-8e94-9e5c16fe7ec6.jpg) | ![filtered](https://user-images.githubusercontent.com/123005779/224571916-4e669118-a78c-4abb-b0a5-b45c2d6927ed.jpg)
