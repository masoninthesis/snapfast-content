# 3 Shortcuts to Speeding Up Your Magento Store:

**The bottom line is this–** 

There is no magic bullet for speeding up Magento. Each and every website is built with different types of products, themes, extensions, users, and traffic levels. The competition is fierce and studies show your customers won't wait more than 2 seconds for your website to load. 

~~*The only way to beat the competition and satisfy your customers is to have a team of Magento experts in your corner. Let us keep Magento firing on all cylinders while you focus on your business.*~~

There are many considerations to make sure Magento runs quickly, but **_here are just a few things to make sure you're doing right:_**

1. **Use Redis as the cache-backend:** 
  * Saving the default Magento caches in Redis can provide a significant boost in site speed as well as improve the amount of traffic your server can handle! 
  * Redis is a storage program that stores information in the server's memory. Saving files in memory makes it easier and faster for the server to retrieve and read those files. This will not only speed up your site (and admin area) but also reduces the load on the server– enabling it to handle greater levels of traffic. Redis is free software, and by default, Magento can save cache files and session files in Redis. When setup and properly configured with Magento, Redis can provide a great boost in speed.
2. **Use an opcode caching system like Xcache, APC, etc:**
  * PHP processing time is often the biggest bottleneck with Magento. A well configured PHP accellerator (opcode cache) can help reduce processing time for Magento php files.
  * Each time a page on your Magento site is loaded, many different PHP files are run. An opcode cache works with PHP to cache those popular files in a way that's faster for the server to process. This can boost your speed by up to 60%.
3. **Reduce the number of requests:**
  * Combine css/js into one file and minify it to a single line of code.
  * Use SVGs, sprites, embed image icons as base64, and use lazyloading for images below the fold. 
  * All these tricks as well as others can cut the number of requests by 50% or more drastically improving load times.
  * Use the free tool like www.webpagetest.org to test your website and note the number of total requests. For a visitor to load your website their browser has to process and download all those items. By combining items or deferring them from loading (lazy loading, async processing, etc.) you can drastically reduce the number of items needed to show a webpage.


Register here for a free speed report that includes a custom analysis of your Magento store along with suggestions and more tips. 

If you’re one of the first 10 people to register, you’ll also get a free 30 minute consultation with one of our Magento experts ($300.00 value) as our gift to you.
