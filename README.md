# Infinite Memes

An android application, that brings unlimited memes from the internet and can be shared with others. 

## Screenshots
* Splash Screen
<img src="https://user-images.githubusercontent.com/59255776/178134135-8a3836f7-e79a-4384-847c-6560d9ccbf0f.jpg" >


* Meme Displayed
<img src="https://user-images.githubusercontent.com/59255776/178133989-00ad987e-25a4-490d-bab0-6ec09ad2d94c.jpg"  >


*Another Meme Displayed
<img src="https://user-images.githubusercontent.com/59255776/178133990-3bfb95f7-a8aa-4dd0-81b5-3a44dee7165e.jpg"  >


* Sharing the meme
<img src="https://user-images.githubusercontent.com/59255776/178133988-348e7dd8-e741-4172-bf14-50bb5c0428d9.jpg" >


## Implemented Libraries

 * Glide library is used, which is an Image Loader Library for Android. It provides animated GIF support and handles image loading/caching.
 * Volley library is used, which is an HTTP library that makes networking for Android apps easier and faster. 
 
 
 ## Working Explained
  * How does Glide works?
 When we provide the URL to the Glide, it does the following:

1. It checks if the image with that URL key is available in the memory cache or not.
2. If present in the memory cache, it just shows the bitmap by taking it from the memory cache.
3. If not present in the memory cache, it checks in the disk cache.
4. If present in the disk cache, it loads the bitmap from the disk, also puts it in the memory cache and load the bitmap into the view.
5. If not present in the disk cache, it downloads the image from the network, puts it in the disk cache, also puts it in the memory cache and load the bitmap into the view.

 * How does Volley works?
  It manages the processing and caching of network requests by doing following operations.
1. Request queuing and prioritization
2. Effective request cache and memory management
3. Extensibility and customization of the library to our needs
4. Canceling the requests



## Any Queries?🤔
 
 Ask me on 
<a href="https://www.linkedin.com/in/thekanishkagupta/"><img src="https://user-images.githubusercontent.com/35039342/55471530-94b34280-5627-11e9-8c0e-6fe86a8406d6.png" width="60"></a>


## How to Contribute
1. Fork the the project
2. Create your feature branch (git checkout -b my-new-feature)
3. Make required changes and commit (git commit -am 'Add some feature')
4. Push to the branch (git push origin my-new-feature)
5. Create new Pull Request


## License

    Copyright (c) 2022 Kanishka Gupta
    
    Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:
    
    The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.
    
    THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
