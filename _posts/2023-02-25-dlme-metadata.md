---
layout: post
title: Response 1 - DLME Metadata
excerpt: "Response 1"
modified: 2/25/2023, 01:37:45
tags: [intro, beginner, jekyll, tutorial]
comments: true
category: blog
---

The DLME Metadata Assignment is an assignment in one step. It builds upon the work we did in class on February 7th. 

This assignment can be done alone or in pairs (either the ones from class or new ones).  

This exercise has two main elements: (1) illustrating how federated libraries can help us understand different kinds of relationships between objects found in global collections and (2) exploring the [discoverability](https://en.wikipedia.org/wiki/Discoverability) of the items given their metadata.

**Step 1**: You should identify two or three items from the [Digital Library of the Middle East](https://dlmenetwork.org/library). This platform "federates and makes accessible data about collections from around the world." NB: A good assignment will use a well chosen pair of items, similar in some ways and different in others. 

**Step 2**: You should obtain a version of the image of the item in your post, captioning it and making sure that you have cited it properly according to the license listed on the DLME. You may want to use detailed images of the items in addition to the whole image. If you would like to view the two objects together, use [Project Mirador](https://projectmirador.org/) with the IIIF manifest. NB: not all images in the DLME have a IIIF manifest. 

**Step 3**: You should discuss the metadata given for the image(s). You might create a table which compares and constrasts what you are able to know about the items and their potential relationship. Remember that metadata is often imported in the language of the original library and there can be a mismatch between the library's version and what you see here. Do they come from the same library? different libraries? How does that affect their metadata? 

**Step 4** How complete or certain is the metadata? Can you make a search engine query for elements of the metadata, or combinations of the metadata and find the objects? 

**Step 5** What other kinds of metadata can you find about the objects, either at the home libraries or by doing some basic research. What kinds of metadata categories might you add that would make the items more discoverable? 

Your assignment should be about 1000 words long, with several images, embedded links. Use a markdown cheatsheet such as this [one](https://www.markdownguide.org/cheat-sheet) to stylize your post, adding different layout features and embedded links if needed. You can refer to the readings if you want to, but this is not necessary for this assignment. 

# Digital Library of the Middle East (DLME) and Its Metadata


## So First of All, What is Metadata?

I don't want to offend anyone, but, if you are not an expert in digital humanities, you might probably not know what **metadata** is. Don't worry, I have checked it up on Wikipedia for you. **Metadata** is a kind of data that provides information about other data besides the data's original content[^1].

For example, if you are browsing through an electronic book website, you can probably see that the books are given different category tags like fiction or short novel collections and so on. This kind of information tells you how the books are divided by their genres and you may also infer a closer relationship or more possible similarity between two books under the same category. 

That's for the case you first find the data and then discover its metadata to better understand it, but at the same time, you can also inversely use metadata to find the data you want. For instance, when the books are uploaded to the electronic book website, the data itself is only the text contents in the books but in a typed version. However, as we keep on filling in the information about the books like their titles, authors, published dates, and categories, the metadata of the books makes them discoverable on the internet since now people can find the books they want in billions of books online by only providing these short pieces of information.

In other words, metadata increases the **discoverability**, "the degree to which something, especially a piece of content or information, can be found in a search of a file, database, or other information system"[^2], of the data itself.


## Metadata of Paintings in DLME

And remember we are here to talk about the metadata in DLME.

Since I am familiar with arts, I choose three Turkish paintings from the library as an example. I will discuss their existing metadata, using the metadata to find their differences and similarities. I will also talk about the problems or missing parts in the metadata. In addition, I will suggest what other metadata we can add to these paintings to make them more discoverable.

![Fish Still Life](/images/Balikli_Naturmort.png "Fish Still Life")
<div align="center"> “Balıklı Natürmort.” DLME, https://dlmenetwork.org/library/catalog/ResimKlksyn%2F779. </div>

![Dancing](/images/Dansci.png "Dancing") 
<div align="center"> “Dansçı.” DLME, https://dlmenetwork.org/library/catalog/ResimKlksyn%2F604. </div>

![Woman by the Sea](/images/Deniz_Kiyisinda_Kiz.png "Woman by the Sea") 
<div align="center"> “Deniz Kıyısında Kız.” DLME, https://dlmenetwork.org/library/catalog/ResimKlksyn%2F760. </div>


### - What can we know by their metadata?

The metadata of each of these paintings are clearly stated in the library, which can be divided into three parts.

The first part is the paintings' basic information. From their pages in the digital library, we can easily know, if available, their title, creator, date of creation, size and the materials used to create them. It is important to mention, though, that most of the information is recorded in Turkish, since the metadata are probably from a Turkish library.

|Title|Creator|Date|Materials/Techniques|Measurements|
|-----|-------|----|--------------------|------------|
|Deniz Kıyısında Kız|İzzet Ziya, 1880-1934|1917|Duralit üzerine yağlıboya|45.5 x 63 cm|
|Dansçı|Güran, Nazmi Ziya, 1881-1937|1930|Tuval üzerine yağlıboya|121 x 91 cm|
|Balıklı Natürmort|Duran, Feyhaman, 1886-1970|1960|Duralit üzerine yağlıboya|61 x 49.5 cm|

For a clearer idea, I translate the chart into English while the translation is not official:

|Title|Creator|Date|Materials/Techniques|Measurements|
|-----|-------|----|--------------------|------------|
|Woman by the Sea|İzzet Ziya, 1880-1934|1917|Oil on duralite|45.5 x 63 cm|
|Dancer|Güran, Nazmi Ziya, 1881-1937|1930|Oil on canvas|121 x 91 cm|
|Fish Still Life|Duran, Feyhaman, 1886-1970|1960|Oil on duralite|61 x 49.5 cm|

The second part is about their classifications inside the DLME. They all consist of the same type, which is *Resim* (Turkish for *picture*). There are also a narrower type and a broader type listed for them. These three paintings all belong to the *Paintings* narrower type and *image* broader type.

The third part gives information of the original library where these paintings are from--the [Sakip Sabanci Museum](https://www.sakipsabancimuzesi.org/en). Even though the original library supports both English and Turkish, in its English version, only part of the metadata is actually translated into English. For example, the third painting is given an English name *Still-life With Fish*. On the other hand, the first two paintings keep their Turkish names in the English version pages.


### - What are missing? What are not clear?

Here we come to its first problem: there is a mismatch due to different languages used.

A simple example already exists. When I translate the Turkish name of the third painting into English, I call it "Fish Still Life". However, if it is otherwise officially named in English as "Still-life With Fish", I may not be able to use my translated version to search for its further information online.

Another thing is for the materials of the first and the third paintings that you may have noticed in the translated chart: what is *duralite*? In the original library, their materials/techniques are given as "oil on hardboard". Meanwhile, my translation is completely based on Google translator as I do not understand Turkish. What if I do not know its original library in the first place? A less common language used for its metadata may lead to misunderstanding of how it is made.

Secondly, I would say the classifications provided are also confusing. It is clear that *painting*, their narrower type, is a kind of *image*, their broader type. Nevertheless, what about their "general" type given--*resim (picture)*? Assume I get the right translation, does it mean that *image* belongs to *picture* or that *picture* belongs to *image* and *painting* belongs to *picture*? I cannot explain it in a common sense, and so does the searching page tell me. In the part where you can refine your searching, the "general" type is not used at all.



not enough information, only materials, title, author and type can be used to discover


### - What should we add?

information of authors

propose possible search engine query


## In Conclusion...

digital libraries good way of collecting data and making collections visible online
still the metadata provided could be improved and searching must be fixed
will be more and more convenient to do research online instead of going to lib and museums in person



**Reference**

[^1]: “Metadata.” Wikipedia, Wikimedia Foundation, 17 Feb. 2023, https://en.wikipedia.org/wiki/Metadata. 

[^2]: “Discoverability.” Wikipedia, Wikimedia Foundation, 3 Feb. 2023, https://en.wikipedia.org/wiki/Discoverability. 
