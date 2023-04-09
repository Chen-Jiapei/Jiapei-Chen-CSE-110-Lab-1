# Jiapei Chen's User Webpage

## Self Introduction

<img src="JiapeiChenPortrait.jpg" alt="alt text" width="400" height="567">

Hello, everyone. My name is **Jiapei Chen**. I am a third year *Math & CS student* in **_ERC_(Eleanor Roosevelt College)** in ***University of California, San Diego***. I am interested in ~~coding and debugging by intuition~~ Mathematics and Physics in Programming, and I would love to learn something new and face the upcoming challenge on my path to become a competent programmer.

I am also interested in anime, manga. I even learned Japanese in UCSD to become able to watch anime without translated subtitles. If you are also interested in them, I am happy to discuess these topics with you. Here are some of my favorite animes and mangas:

### Anime

- PSYCHO-PASS
- Hellsing **(OVA version produced in 2005)**
- Jujutsu Kaisen
- Nichijou
  
### Manga

1. Baki
2. Dark Gathering
3. Jujitsu Kaisen
4. Record of Ragnarok

I also enjoy playing computer games, such as Genshin impact and Hearthstone. Maybe this is a part of the reason I want to become a programmer. These games update frequently, mainly because there are some new contents are added to the game and bugs come along with new contents(~~even though I never see what bugs they have repaired after an update~~). Sometimes I see some amusing bugs in these games, while some other bugs are not so funny. 

> It's not a bug, it's an undocumented feature<sup>[1]</sup>.

Therefore one of my target is writing a programs that do exactly what I want them to do. However, I am not sophisticated enough and therefore there are always some weird things about coding I don't know. For example, I would have never known that the following code will work.

```
# include <iostream>

int main() {
    while(1)
        ;
}

void unreachable() {
    std::cout << "Hello world!" << std::endl;
}
```

It turns out it will work if you compile it in this way:

```
$ clang++ loop.cpp -O1 -Wall -o loop
$ ./loop
Hello world!
```

It is weird, right? There are still a lot of things I don't know. Therefore, if want to do better than the programmers who produce bugs in my favorite games, I will need to work harder and think harder. 

## About This Webpage

This webpage is created as a part **of CSE 110 Lab-1 assignment**, as stated in [README.md](README.md). This course is about Software Engineering and I am interested in this topic. I hope I can survive this course and learn how to collaborate with others in this course.

There are a lot of things I need to do in this quarter. Here is a list of tasks I set for myself in CSE 110 in this quarter:

- [X] Task 1: Enter CSE 110.
- [ ] Task 2: Go to every lecture and learn something.
- [ ] Task 3: Make 3 new friends and collaborate with them.
- [ ] Task 4: Survive this course and make something meaningful.

Hopefully I will be able to finish them all at the end of the quarter.

<sub>If I have enough and energy to update this webpage.</sub>

## Citations

[1] This famous saying has many variants. One possible original source of this saying is the title of a study in 2013 of a group of scholars at a German university [“It’s Not a Bug, It’s a Feature: How misclassification impacts bug prediction"](https://ieeexplore.ieee.org/document/6606585/authors#authors).

K. Herzig, S. Just and A. Zeller, "It's not a bug, it's a feature: How misclassification impacts bug prediction," 2013 35th International Conference on Software Engineering (ICSE), San Francisco, CA, USA, 2013, pp. 392-401, doi: 10.1109/ICSE.2013.6606585.
