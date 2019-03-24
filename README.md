
# Images Scrapping for dataset building

JS code for collecting images urls from Google Images and Python script to retrieve the images

## Steps

1. To collect the urls, go to the file `get_google_images_urls` and follow the indicated steps.

2. To download the urls' images, run the python script by executing the following command:

`python download_images_from_urls_file.py --urls URLS_FILE --output IMAGES_OUTPUT_FOLDER`, for example: `python download_images_from_urls_file.py --urls yoda_urls.txt --output dataset_images/yoda`

3. Finally, check manually the images to remove the irrelevant ones.
