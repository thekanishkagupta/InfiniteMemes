# Infinite Memes

An android application, that brings unlimited memes from the internet and can be shared with others. 

## Screenshots
<p>
<img src="https://user-images.githubusercontent.com/59255776/178132826-2eb3e7c0-a7bd-4882-87f1-40d811586e40.pngg" alt="feed example" width = "400" >
<img src="https://user-images.githubusercontent.com/59255776/178132828-9a841eff-9066-455f-97fd-efd30a6e7896.png" alt="feed example" width = "400" >

</p>


## Implemented Libraries<img width="810" alt="Untitled design (48)" src="https://user-images.githubusercontent.com/59255776/178132819-9da70391-2017-4e78-99d1-922a3cdb7753.png">

 * Glide library is used, which is an Image Loader Library for Android. It provides animated GIF support and handles image loading/caching.
 
 Working Explained
  * How does Glide work?
 When we provide the URL to the Glide, it does the following:

1. It checks if the image with that URL key is available in the memory cache or not.
2. If present in the memory cache, it just shows the bitmap by taking it from the memory cache.
3. If not present in the memory cache, it checks in the disk cache.
4. If present in the disk cache, it loads the bitmap from the disk, also puts it in the memory cache and load the bitmap into the view.
5. If not present in the disk cache, it downloads the image from the network, puts it in the disk cache, also puts it in the memory cache and load the bitmap into the view.
 


