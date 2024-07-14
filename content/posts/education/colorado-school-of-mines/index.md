---
title: Colorado School of Mines
date: 2024-07-14T13:00:00-06:00
categories: [Education]
tags: [Mines, Computer Science, Math]
---

After just over two months since graduating from the [Colorado School of Mines](https://www.linkedin.com/feed/update/urn:li:activity:7196277618038427648/), I find myself reflecting on my time in Golden. While there will be a future post dedicated solely to my personal growth and favorite moments during my three years in Colorado, that moment will likely coincide with my departure in August. This post focuses exclusively on my academic endeavors, aiming to capture the ways in which I attempted to better myself. To concisely summarize the entirety of my experiences is an impossible task. I considered discussing the interesting technical knowledge I now have under my belt; not only does that conversation fail to provide a sensible close to this era of my life, but it can't provide you, the reader, with anything worthwhile. Rather, I wish to speak about one class I took at Mines in particular and why I consider it my favorite.

As a computer science student (well, as a now former computer science student), it may be surprising to discover that my favorite class I had taken at Mines was [Linear Algebra](https://en.wikipedia.org/wiki/Linear_algebra). I find it important to note that although the intersection between computer science and mathematics is large, especially if you're more into the theoretical and mathematical aspects of CS than the software engineering aspect, there are still distinctions in how these subjects are taught. I found that even in my CS courses grounded in gaining a deeper understanding of how the code you're writing interfaces with hardware where the freedom of choice in your approach or design may be stifled, such as Embedded Systems, creativity was seemingly always present. When you sit down and write code, even in low-level languages, there are always a million right ways to the answer. 

For example, a simple, straightforward approach.

```c
#include <stdio.h>

int main() {
    printf("Hello, World!");
    return 0;
}
```

On the other hand, an elaborate, roundabout approach.

```c
#include <stdio.h>
#include <math.h>

int main() {
    float coefficients[] =
        {72.0, 50.5, 36.0, 27.0, 22.2, 7.3, 4.6, 10.9, 12.3, 11.4, 9.8, 8.3, 2.5};
    for (int i = 1; i < 14; i++) {
        printf("%c", (char)round(i * coefficients[i - 1]));
    }
    return 0;
}
```

Anyway, my view of mathematics has always been one-dimensional. I learn of a problem and the method(s) of figuring out the answer to said problem, and I wash my hands of it. The creativity found in programming felt absent in math. I've always found it to be interesting - there are moments when my curiosity leads me down a rabbit hole, but I find the technical jargon and its non-concrete nature to be overwhelming. Linear Algrebra seemed no different; on the first day of class, I prepared myself to understand the bare minimum about determinants and eigenvalues, and, for a while, my expectations were spot on. I put in quite a bit of effort, but as soon as I wrapped my head around a given topic, I moved on. I actually became frustrated due to how hand-wavy the entire subject seemed at first, but that quickly changed. 

I always seem to understand the applications of a given subject months after I finish a course on it. Linear Algreba with Dr. Mikucki was different - it felt like my first college course driven by an understanding of its application in a multitude of fields. Dr. Mikucki started his lecture one day with an introduction to [singular value decomposition](https://en.wikipedia.org/wiki/Singular_value_decomposition) and how it can be applied in [image compression](https://en.wikipedia.org/wiki/Image_compression). I'll spare you most of the technical details, but this started my deep dive into understanding [lossy](https://en.wikipedia.org/wiki/Lossy_compression) and [lossless compression](https://en.wikipedia.org/wiki/Lossless_compression). Although a more sophisticated method like [JPG](https://en.wikipedia.org/wiki/JPEG) generally outperforms compression using SVD, I was enamored with the idea of using something I just learned in a programming context. 

I went hands-on. I spent the subsequent weekend working on creating my own functioning SVD image compression program; you can find the script and an in-depth technical explanation on [GitHub](https://github.com/keenanschott/SVD-Image-Compression). Dr. Mikucki was kind enough to discuss the topic with me on several occasions and point me in the right direction for further investigation. This was my inflection point in the course. All of a sudden, I found myself invested in the course in a way I hadn't experienced before - I was doing investigations into the applications of linear algebra on my *own time*. Don't get me wrong, I typically find most to all of my coursework to be decently interesting, but I do find myself browsing [random Wikipedia pages](https://en.wikipedia.org/wiki/Special:Random) when lecture fails to provide anything that I can't already get from a book.

I spent most of my formative years believing that fun was supposed to happen outside of school and work, and these were just things we had to do. It's unfortunate that many adults hold this mindset, but if I were [stuck in a cubicle updating thousands of lines of code to combat Y2K](https://www.youtube.com/watch?v=jKYivs6ZLZk), I might also revert to this way of thinking. Especially in a STEM education, where the fantastical technical details of industry seem a million miles away, it can feel like you're just learning for the sake of learning. For example, it's cool that I know about orbital shells and Galois fields, but how am I going to use this knowledge as a software engineer? Linear Algreba presented the applications first, and I found that to be a convincing method of commanding my attention for the better part of the semester. 

Instead of viewing the trudge to my classes as an obligation or a box to check, I found myself having *fun*, and this was informative for many courses to come afterwards. From there on out, I sought out knowledge I found most interesting and used that as the guiding principle for all of my courses. Of course, this doesn't always succeed; some topics were just cut out to be boring, but it definitively shifted my perspective on learning and what I want out of my career. Learning never stops. If I'm employed in a job where my brain is static, doing the same task over and over again just because I know what I'm doing, something's wrong. It's a joy and a privilege to pursue knowledge, and it's fun! Linear Algebra, my favorite course at Mines, made that idea clear to me, and that's more valuable than anything I can remember from Chemisty I. 