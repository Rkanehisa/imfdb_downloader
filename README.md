# imfdb_downloader
A web crawler for downloading images from IMFDb

<hl>

How to use:
- Edit the file start_urls.txt and insert a list of IMFDb urls, e.g., http://www.imfdb.org/wiki/AK47

- Go to the project root folder
- Call the spyder using the command:
```bash
  $scrapy crawl wiki
```

- The images will be saved on the project's root
- You can edit the directory on the file `settings.py`
</hl>


<br>

This script is a web crawler for downloading images from the website IMFDb (Internet Movie Firearm Database).

<hl>  
  Notes:

- If you use this script or the dataset, please cite the paper: "Firearm Detection Using Convolutional Neural Networks".

- If you use this script for creating a firearm dataset, please contact us for integrating your dataset with our existing one.

</hl>


```
@conference{icaart19,
author={Rodrigo Fumihiro de Azevedo Kanehisa. and Areolino de Almeida Neto.},
title={Firearm Detection using Convolutional Neural Networks},
booktitle={Proceedings of the 11th International Conference on Agents and Artificial Intelligence - Volume 2: ICAART,},
year={2019},
pages={707-714},
publisher={SciTePress},
organization={INSTICC},
doi={10.5220/0007397707070714},
isbn={978-989-758-350-6},
}
```
