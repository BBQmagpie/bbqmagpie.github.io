---
layout: post
title: Response 1 - DLME Metadata
excerpt: "Response 1"
modified: 2/25/2023, 01:37:45
tags: [intro, beginner, jekyll, tutorial]
comments: true
category: blog
---

# Digital Library of the Middle East (DLME) and Its Metadata


## So First of All, What is Metadata?

I don't want to offend anyone, but, if you are not an expert in digital humanities, you might probably not know what **metadata** is. Don't worry, I have checked it up on Wikipedia for you. **Metadata** is a kind of data that provides information about other data besides the data's original content[^1].

For example, if you are browsing through an electronic book website, you can probably see that the books are given different category tags like fiction or short novel collections and so on. This kind of information tells you how the books are divided by their genres and you may also infer a closer relationship or more possible similarity between two books under the same category. 

That's for the case you first find the data and then discover its metadata to better understand it, but at the same time, you can also inversely use metadata to find the data you want. For instance, when the books are uploaded to the electronic book website, the data itself is only the text contents in the books but in a typed version. However, as we keep on filling in the information about the books like their titles, authors, published dates, and categories, the metadata of the books makes them discoverable on the internet since now people can find the books they want in billions of books online by only providing these short pieces of information.

In other words, metadata increases the **discoverability**, "the degree to which something, especially a piece of content or information, can be found in a search of a file, database, or other information system"[^2], of the data itself.


## Metadata of Paintings in DLME

And remember we are here to talk about the metadata in DLME.

Since I am familiar with art, I choose three Turkish paintings from the library as an example. I will discuss their existing metadata, using the metadata to find their differences and similarities. I will also talk about the problems or missing parts in the metadata. In addition, I will suggest what other metadata we can add to these paintings to make them more discoverable.

![Fish Still Life](/images/Balikli_Naturmort.png "Fish Still Life")
<div align="center"> “Balıklı Natürmort.” DLME, https://dlmenetwork.org/library/catalog/ResimKlksyn%2F779. </div>

![Dancing](/images/Dansci.png "Dancing") 
<div align="center"> “Dansçı.” DLME, https://dlmenetwork.org/library/catalog/ResimKlksyn%2F604. </div>

![Woman by the Sea](/images/Deniz_Kiyisinda_Kiz.png "Woman by the Sea") 
<div align="center"> “Deniz Kıyısında Kız.” DLME, https://dlmenetwork.org/library/catalog/ResimKlksyn%2F760. </div>


### - What can we know by their metadata?

The metadata of each of these paintings is clearly stated in the library, which can be divided into three parts.

The first part is the paintings' basic information. From their pages in the digital library, we can easily know, if available, their title, creator, date of creation, size, and the materials used to create them. It is important to mention, though, that most of the information is recorded in Turkish since the metadata are probably from a Turkish library.

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

The second part is about their classifications inside the DLME. They are all of the same type, which is *Resim* (Turkish for *picture*). There are also a narrower type and a broader type listed for them. These three paintings all belong to the *Paintings* narrower type and *image* broader type.

The third part gives information about the original library where these paintings are from--the [Sakip Sabanci Museum](https://www.sakipsabancimuzesi.org/en). Even though the original library supports both English and Turkish, in its English version, only part of the metadata is actually translated into English. For example, the third painting is given the English name *Still-life With Fish*. On the other hand, the first two paintings keep their Turkish names in the English version pages.


### - What are missing? What are not clear?

Here we come to its first problem: there is a mismatch due to the different languages used.

A simple example already exists. When I translate the Turkish name of the third painting into English, I call it "Fish Still Life". However, if it is otherwise officially named in English as "Still-life With Fish", I may not be able to use my translated version to search for further information online.

Another thing is for the materials of the first and the third paintings that you may have noticed in the translated chart: what is *duralite*? In the original library, their materials/techniques are given as "oil on hardboard". Meanwhile, my translation is completely based on Google Translate as I do not understand Turkish. What if I do not know its original library in the first place? A less common language used for its metadata may lead to misunderstanding of how it is made.

Secondly, I would say the classifications provided are also confusing. It is clear that *painting*, their narrower type, is a kind of *image*, their broader type. Nevertheless, what about their "general" type given--*resim (picture)*? Assume I get the right translation, does it mean that *image* belongs to *picture* or that *picture* belongs to *image* and *painting* belongs to *picture*? I cannot explain it in common sense, and neither does the search page tell me. As shown in the picture below, in the part where you can refine your search, the "general" type is not used at all.

![Searching page in DLME](/images/refine_your_result.png "Searching page in DLME")
<div align="center"> ↑ How types are used in searching in DLME. </div>

Not to say that there is not enough information to discover the items. For distinguishing the paintings, unless you can also specify their creation dates in the "date range" catalog, which only applies to the situation where you are doing research on paintings in a certain era, the maximum you can do is to ask the digital library for a painting of a certain country, and it will return you with hundreds of items under this query. For example, if we want Turkish paintings, 204 items will be returned, and there is no way to narrow down the result to these three painting instances unless we know their exact title or creator's name.

![Maximum search engine query in DLME](/images/searching.png "Searching for a certain painting")
<div align="center"> ↑ Most narrowed search engine query one can make for a Turkish painting. </div>


### - What Can We Add?

These paintings definitely have more differences than simply their titles and creators. For example, their objects already vary: the first painting is of a figure with a scene, while the second one is more of a single figure, and the third is of a still life. Their objects can be used to keep on distinguishing them and dividing them up into even smaller groups. 

This is the same for their styles. The first one is more of realism; on the contrary, the second and the third go for impressionism. It is not necessary that each painting can only have one style, but the obvious styles can be a tag of them so that when the researchers look for a certain style, all paintings consisting of that style can be shown together.


## In Conclusion...

Digital libraries are without a doubt a good way of collecting data and making collections visible online. Still, I would say that the metadata provided could be more detailed to make the items more discoverable and more easily grouped. With improvements, digital libraries, not simply DLME, will be more and more convenient for researchers to do research online instead of going to the libraries and museums in person. More people will also be able to discover these valuable legacies of human history.



**Reference**

[^1]: “Metadata.” Wikipedia, Wikimedia Foundation, 17 Feb. 2023, https://en.wikipedia.org/wiki/Metadata. 

[^2]: “Discoverability.” Wikipedia, Wikimedia Foundation, 3 Feb. 2023, https://en.wikipedia.org/wiki/Discoverability. 
