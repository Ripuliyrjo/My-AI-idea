<!-- This is the markdown template for the final project of the Building AI course, 
created by Reaktor Innovations and University of Helsinki. 
Copy the template, paste it to your GitHub README and edit! -->

# Finding face from picture

Final project for the Building AI course

## Summary

Finding a face from picture is really useful for example if you have really messy folders in your computer, smartphone etc. 

## Background

To make this you need to:
* process the picture
* process the face
* find the face


## How is it used?

We humans can easily distinguish between places, objects, and people based on images, but computers have traditionally had difficulties with understanding these images. By recognizing a face from a picture, it helps people to find pictures of themselves and others. 

Images will make your README look nice!
Once you upload an image to your repository, you can link link to it like this (replace the URL with file path, if you've uploaded an image to Github.)
![Cat](https://upload.wikimedia.org/wikipedia/commons/5/5e/Sleeping_cat_on_her_back.jpg)

If you need to resize images, you have to use an HTML tag, like this:
<img src="https://upload.wikimedia.org/wikipedia/commons/5/5e/Sleeping_cat_on_her_back.jpg" width="300">

This is how you create code examples:
```
def main():
   countries = ['Denmark', 'Finland', 'Iceland', 'Norway', 'Sweden']
   pop = [5615000, 5439000, 324000, 5080000, 9609000]   # not actually needed in this exercise...
   fishers = [1891, 2652, 3800, 11611, 1757]

   totPop = sum(pop)
   totFish = sum(fishers)

   # write your solution here

   for i in range(len(countries)):
      print("%s %.2f%%" % (countries[i], 100.0))    # current just prints 100%

main()
```

## Challenges

My project does not solve the problem with missing or lost photos. It would be big step if the AI could find photos from the internet and recognize them. 

## What next?

To build an AI that collects photos automatically and informs if someone is using your face somewhere. 


## Acknowledgments

* Buildinf of AI course
