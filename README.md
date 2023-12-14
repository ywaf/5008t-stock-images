# 5008t-stock-images
Alcatel 1X (2019) 5008T stock fw images dumped

# Why?
Got the phone for $20, bricked it trying to flash gsi, and Alcatel is a shitty company that doesn't post factory images

# How to flash?
https://github.com/bkerler/mtkclient  

```python mtk w <partition name> <partition file>```  
ex..  
```python mtk w boot boot.img```

# Partitions included:
boot  
boot2  
system  
recovery  
recovery1  


These should be enough for most situations (email me if you want other partitions, trying not to leak my phones info :))

# Root?
Havent been able to yet, can patch and flash the images, but magisk never gets initialised for some reason :(

have fun  



alcatel dont sue me, will remove these if needed :)
