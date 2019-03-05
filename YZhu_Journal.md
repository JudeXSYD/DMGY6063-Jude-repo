# Yundi Jude Zhu's Creative Coding Journal

## Tuesday, March 5, 2019
### Journal 10: Robert Hodgin Flight 404

Today, it's my turn for the research presentation. One of the artists I chose is Robert Hodgin.

![](http://01sj.org/files/2010/03/hodginweb.jpg)
Robert Hodgin and his cat

Robert is the Interactive Director and Co-Founder of the Design + Technology studio Rare Volume, a Design & Technology Studio in New York City. Graduated in 1998 with a degree in Sculpture from the Rhode Island School of Design. His work ranges from simple 2D data visualizations to immersive 3D terrain simulations. His primary interests include theoretical physics, astronomy, particle engines, and audio visualizations. He works in Cinder, OpenGL, and GLSL. Hodgin’s own, highly absorbing website is Flight404, apparently named after either the familiar error code or the hijacked Japanese airline Flight 404 in 1973.

I found him very interesting becuase his [personal website](http://roberthodgin.com/) have super detailed explanations for his projects.

![](http://roberthodgin.com/wp-content/uploads/taxi_08.jpg)
Screenshot of Taxi, Taxi!(2016)

[Taxi, Taxi!(2016)](http://roberthodgin.com/portfolio/work/taxi-taxi/) is a digital installation featured on the 3-story display housed within Samsung 837, the new Samsung Experience Center located in Manhattan.

This project uses NYC Open Data taxi data plotted against routes created with Open Street Map which is displayed within a 3D model of New York City. It is designed to run in realtime and was created with the Cinder C++ coding framework.

By the way, I looked up and learned Cinder is a free and open source library for professional-quality creative coding in C++.

Another cool project he did was [Adobe Remix(2015)](http://roberthodgin.com/portfolio/work/adobe-remix/).

![](http://roberthodgin.com/wp-content/uploads/06.png)
Screenshot of Adobe Remix

He explained in details how he came up with the idea, doing the scratch, how he solved technical problem with other artists in collaboration, and how he learned things by himself to finish the project. I feel very relatable reading his notes. It gives me hope that if I could have the same passion and patience for one single project, I should be able to create some fancy stuff like he did.


## Monday, March 4, 2019
### Journal 9: Lauren McCarthy

When I was watching this week's video about p5.js, Daniel Shiffman recommended another great coder on earth: Lauren McCarthy, who created p5.js.

![](https://payload550.cargocollective.com/1/19/625408/13312174/LAUREN.gif)

Lauren McCarthy is an American artist and computer programmer. McCarthy's work explores the impact of technology on individual identity and human interaction. In "Follower", a 2016 work, users could use an app to voluntarily request a person to follow them around New York for an entire day, without knowing the identity of the follower. In her 2017 work "Lauren", she installed cameras, microphones and speakers in her own apartment, then interacted with visitors by performing the role of an Amazon Alexa-styled virtual assistant. In the work "How we Act together", a collaboration with Kyle MacDonald, encourages viewers to follow computer-generated prompts to interact with video persona by nodding, screaming, greeting or making eye contact with the projection.

McCarthy is just so cool in many ways. I like how she started her work based on social critics about real world problems. Human-machine interaction has been brought into a new level after AI being applied to all industries. Cameras everywhere. Censorship everywhere. Social media for everything. Do we feel more comfortable being watched by human or machine? What's the principle for privacy in the digital age?

These are the questions we need to think about, and we can keep asking the questions by creating artworks like McCarthy's.


## Tuesday, February 26, 2019
### Journal 8: Today I created a drawing machine!

For the Drawing Machine project, I reproduced Piet Mondrian's "Composition with Red, Blue and Yellow" (1930). I chose it because the colors are so beautiful.

![](https://upload.wikimedia.org/wikipedia/commons/thumb/a/a4/Piet_Mondriaan%2C_1930_-_Mondrian_Composition_II_in_Red%2C_Blue%2C_and_Yellow.jpg/400px-Piet_Mondriaan%2C_1930_-_Mondrian_Composition_II_in_Red%2C_Blue%2C_and_Yellow.jpg)

A well-known work of, Mondrian contributes to the abstract visual language in a large way despite using a relatively small canvas. Thick, black brushwork defines the borders of the different geometric figures. Comparably, the black brushwork on the canvas is minimal but it is masterfully applied to become one of the defining features of the work.

Here are my analysis on the components of this painting:

####Lines and shapes:
Big red square, the blue rectangular under the red's left corner, the yellow rectangular under the red's right corner, and four other white rectangulars fill out the space. The rectangulars have black strokes. Two strokes are thicker than others.

####Color in RGB:
* Red (210, 23, 36)
* Yellow (245, 208, 47)
* Blue (9, 76, 149)
* White (223, 227, 226)
* Stroke (0)

####Texture:
On canvas. No reflection.

####Note on the design of drawing machine to recreate this art piece:
I wanted to make a drawing machine to randomly recreate the composition. The shapes are going to relocate themselves according to the randomly assigned big red square. It took me a while to figure out how to caculate the coordinate for each shape. The hardest part of this project is that I couldn't find a good place for using recursion. So I created a circle pattern in background. Also, I am having trouble writing a function to export the image. I wonder if there is a screenshot function in Processing?

## Monday, February 18, 2019
### Journal 7: Tech problem form The Wandering Earth(2019)

This week, I interviwed Guo Fan, the director of China's first homemade sci-fi blockbuster--"The Wandering Earth"(2019).

![](https://d1oyefh7iseipu.cloudfront.net/amcpp/cinema/movie/image/11254.jpg)
(Poster of The Wandering Earth)

Having already grossed $650 million, "The Wandering Earth", adapted from Hugo Award winner Liu Cixin’s short story [CHECK: not novel], is the second highest-grossing film in Chinese box-office history and considered by many as a pioneer for a new era in Chinese sci-fi.

The film plots a desperate mission to save planet Earth from being devoured by the dying sun by propelling it out of the solar system and into a new star system in the remote galaxy.

During the interview, the director mentioned a very interesting coding problem he encountered during the production:
how to make 100 screens turn on and off at the same time?

![](https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcSmXfcJqj-dps_N5lqkRdbCeoNhOQ0Vp_Al9WiAkSZZ3dRlgZQZ)
(Screenshot from "The Wandering Earth". There are more than 100 screens in the space station set.)

Guo said, right now, China doesn't have a Hollywood standard UI team to help design the interface used in filmmaking. They have to purchase the screens, connect the cables, and code the program all by themselves.

His team couldn't figure out how to use one button to control different screens which are showing different content at the same time.

In the end, he said there were a mannually controled laptop behind each screen.

I thought about "class" in Processing to solve this problem. 

A class is a composite of fields (data) and methods (functions that are a part of the class) which may be instantiated as objects. The first letter of a class name is usually uppercase to separate it from other kinds of variables. 

If the director is able to code a program in Processing, he should be able to name "class" for the screens. The screens should be the variables, and he can use function to control the different content to be displayed on each screen.

I guess it's much hard to practice in film set. But, with the learning of Processing, I think it's highly possible that we can solve some certain practical problems in the future.

## Tuesday, February 19, 2019

### Journal 6: Today I (maybe) finished my first game! 

It took me almost two weeks to catch up all the coding concepts and techniques to make a super simple game in Processing. It feels like the debugging process takes centuries, but I am glad that I made something that looks like a game! Yay!

It's really unbelievable. While I was looking for reference online, many students say that making a game is like their final project for their very first Processing coding class. But we are able to make one by week 3. 

Surprsingly, I feel that coding is not the hardest part during the game making process. I actually spent more time on concepting what the game should be about and what variables and functions I should use to make it fun. This really reminds me of my daily job as a journalist--the hardest part is how to find the story. A good story can only be told when the story itself is good.

I went to cover the [New York Tory Fair](https://www.toyfairny.com/) these days, and a STEAM toy exhibitor really inspired me. He told me in an interview: Coding is important to us, because computer is the most powerful tool in our society, like pen and paper used to be. If you are able to code, it means that you are able to command computers. With the ability to code, you are able to use the most powerful tool in the world to create whatever that's gonna change the world.

![](https://thumbor.forbes.com/thumbor/960x0/https%3A%2F%2Fblogs-images.forbes.com%2Fandyrobertson%2Ffiles%2F2019%2F02%2Ftoyfair-1.jpg)

Even though my very frist game is really shitty, and I still have tons of work to catch on, I finally get the idea of what I am doing and what I should do next. Hopefully I can be able to code soon, like I am able to write and shoot.

## Monday, February 18, 2019
### Journal 5: Coolture Impact
I came across an interactive display named [Coolture Imact](https://www.cooltureimpact.com/) on 42nd street, 8th Avenue. According to the website, it is "the largest interactive public art platform that intertwines reality and fantasy on the windows of the Port Authority Bus Terminal in Times Square."

Coolture Impact is an incubator that explores and exploits new technologies, art content and social interaction. It creates a new paradigm in storytelling, where digital art is activated by, and exposed to, a large audience. Viewers are invited to experience and interact with art in a personal and exciting way to become an intrinsic part of the soulful artworks of our talented, featured artists.

Since I work and live in the neighborhood, I have seen at least two different projects being featured on the interactive screens. The one impressed me most is a doodled New York City streets in simple colors. There are also ballons flying randomly on the street, and it looks like interacting with the passengers. I tried to wave at the screen, and the ballons were flowing my hands.

![](https://www.leyard.com/media/1187128/coolture-timessquare.jpg)

I wonder what techniques used for this kind of installation? What coding language does it use? Can Processing do something like this? Can I make something cool with Processing that can be featured on this screen one day?

## Tuesday, February 12, 2019
### Journal 4: Self challenge: Thinking in Math

First of all, I found this [Macdown reference](https://macdown.uranusjr.com/blog/macdown-help/) that is very helpful.

OK. The challenge. Since I have no background in coding, my very first challenge in coding is to think like a computer.

According to Professor Stearns, computers operate with math. They can only understand human's order translated with math. As a liberal art student for whole my life, it's extremely hard for me to do that. (Chinese people are good at math is a big stereotype. I am not.)

So, to train myself think like a computer, I am practicing how to use coordinate to locate an image on diagram instead of just doodle one on paper; instead of simply draw something bigger, I am considering what amount of components to increase to achieve a certain amount of larger size. I am also drawing mind maps to visualize logics behind my behaviors. 

Since we are moving faster on the chapters, I am trying my best to adjust my logics. 

>`if (JudeHungry > 50 ) {`
>>`eatSomething`
>>>`else {
>>> goToSleep;`
>>> 

## Monday, February 11, 2019
### Journal 3: What program is that?

So, I looked through professor Stearns' website and found [this artwork](https://phillipstearns.com/artwork#/ayearincode/) very interesting:

![](https://static1.squarespace.com/static/544a9357e4b0e537e01f1381/54ab0ab1e4b0f4be675d3ec5/55bbf1fde4b09f3341eed794/1438380561710/vectorDisplace001.png?format=2500w)

The website didn't say much about what program used to create this cyborg oil painting. Can we do something similar with Processing? I am super excited to know how!

## Tuesday, February 5, 2019
### Journal 2: Jude's inspiration

I am a full-time multimedia journalist who covers US-China related stories. My job requires me to be inspired by all the local and international media and news agencies. So, I am really into New York Times, New Yorker, VOX, VICE, and many Chinese media companies, such as Xinhua News Agency (新华社), South China Morning Post（南华早报）, and some social media channels like 当下频道 (sorry I didn't find their English name). I read their stories and watch their videos on a daily basis to get story ideas. I want my work to go viral and engage social awareness on some topics. Last year, I did a [short documentary](https://www.facebook.com/watch/?v=10156444655351291) on how Trump's immigration policy has been impacting millions of hardworking international students in getting their work visa.

Recently, I am also inspired by NetFlix TV shows such as: "Black Mirror: Bandersnatch" and "Russian Doll". I am amazed by the concept of interactive storytelling. Few years ago, I took an interactive storytelling class with [Eko](https://helloeko.com/). There are many great projects like the "Black Mirror: Bandersnatch". The company has been exploring interactive storytelling in use of commercials, music video, and short films for many years. I think people are going to get bored with the passive viewership soon, and interactive storytelling is going to be everywhere.

I am also inspired by "Summer Wars" (2009) and "Ready Player One" (2018), which both addressed on how virtual reality gaming could give us a platform to live a second life. Even though the VR headsets are still in its developing stage, I hope I could be capable of making VR stories that is not only a 360 video.

![](https://media.giphy.com/media/3tMxUacS1ahcNSdBVh/giphy.gif)
A clip from "Ready Player One" (2018)

## Monday, February 4, 2019
### Journal 1: About Yundi Jude Zhu

![](https://66.media.tumblr.com/2f7033d432826a8fc7ef20bf626a5c85/tumblr_nus14aE8YX1uefyhgo1_1280.jpg)
Jude's crazy selfie

Hi!

My name is Yundi Zhu, or Jude. I am originally from Beijing, China, and has been living in NYC for four years. I graduated with a B.A in Communications at the University of Colorado Denver, and a M.A in Media Studies at Pratt Institute. My professional history includes positions in journalism, advertising, marketing, public relations, and music production. My work varies from viral short videos to integrated digital storytelling.

As a full-time multimedia reporter and a freelance video creator in New York City, I am taking my second master program at New York University to explore how multimedia storytelling could impact public consciousness and address social justice issues through the building of digital communities. Since I don't have any CS background, I am interested in learning anything about coding. I want to know how to build an interactive platform, as simple as a website, or as complicated as an art installation, to better tell a multimedia story.

One project I aspire to is this interactive story: [Bhumika Can Speak For Herself](https://projects.asiaweekly.com/bhumika-can-speak-for-herself/) 

Bhumika Shrestha is transgender rights activist and politician, and the first Nepali to travel abroad on an "other" gender passport. Nepal's LGTBI community has won several recent victories. The country now provides a third gender option on official documents, and is the first in Asia to explicitly protect gender and sexual minorities in its constitution. This interactive project allows audience to "live chat" with Bhmika, and ask her any questions.

If you are interested in learning more about me, please check out my website: [www.juuud.com](http://www.juuud.com/) and my [LinkedIn](https://www.linkedin.com/in/juuud/).

Thank you!