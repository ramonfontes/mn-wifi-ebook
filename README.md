The Mininet-WiFi book is now free and open, and you can contribute!   

You can still have a printed version (_en_ and _pt_ editions) if you prefer. Visit https://mininet-wifi.github.io/book/ for more details.

# Chapter Organization

This book is organized as follows:

[**Chapter I**](https://github.com/ramonfontes/mn-wifi-ebook/blob/main/background.md) introduces theoretical fundamentals of wireless networks, software-defined wireless networks and also Mininet-WiFi. This chapter goes in-depth
into concepts relevant to the learning objectives of this book. For a deeper understanding of the different topics explored, the reader will be provided
references to relevant literature in the field;

[**Chapter II**](https://github.com/ramonfontes/mn-wifi-ebook/blob/main/beginner.md) introduces the beginner level of Mininet-WiFi proficiency and is devoted solely to providing the working details of Mininet-WiFi, where
its key functional aspects are described. If you are already proficient with Mininet-WiFi, you can focus on chapters III and IV instead. You do not need
to be familiar with Mininet to use Mininet-WiFi, but if you are, you will certainly have a smoother feel as to how Mininet-WiFi works. The tutorials
included in this chapter can be used as complementary activities in theory classes at the undergraduate level (e.g. EA074 at FEEC/UNICAMP), as well
as in practical laboratory courses (e.g. EA080 at FEEC/UNICAMP);

[**Chapter III**](https://github.com/ramonfontes/mn-wifi-ebook/blob/main/intermediate.md) introduces the intermediate level of Mininet-WiFi proficiency, covers tutorials that employ wireless networking, software-defined wireless
networking, as well as a number of concepts related to computer networking. This chapter also describes the use of some network applications, such as
tcpdump and Wireshark. In addition to meeting the pedagogical goals of more advanced computer network classes such as those involving laboratory
activities, the tutorials in this chapter are also suitable for graduat classes(e.g. IA369, IA376 at FEEC/UNICAMP) and specialization courses (e.g.
INF-556 at IC/UNICAMP), as they allow experimental research to be carried in more complex scenarios, such as the development of SDN solutions using
the OpenFlow protocol;

Finally, [**Chapter IV**](https://github.com/ramonfontes/mn-wifi-ebook/blob/main/expert.md) introduces the expert level of Mininet-WiFi proficiency, has tutorials about kernel manipulation, containers, security, IoT, vehicular
networks, etc., with valuable information on adapting the OpenFlow protocol to wireless networks. This chapter is labeled as advanced because it requiresmore in-depth knowledge and the use of third-party applications. Therefore,
the tutorials in this chapter are best suited for specialization and graduate courses, not only in classes but also as technical training for master’s and doc-
toral students, thus helping the development of experimental research aimed at advancing the state of the art. However, nothing prevents curious readers from
reproducing these tutorials, since they have similar walkthroughs, as well as the support provided by the codes from the previous chapters.


# Precautions
It is recommended that all tutorials available in this book be completed using the latest version of Mininet-WiFi available on Github. Should you, the reader,
find any inconsistencies in the tutorials, you may contact the authors of this book at any time for clarification.
Although this book brings hands-on experience at all times, we recommend that you review each command or configuration beforehand so that the entire
process can be understood. Do not try to complete the tutorials without clearly understanding what is being done!

## I must use Linux. But why?
Because the code base of Mininet-WiFi, Mininet, was developed for Linux systems. The development of Mininet-WiFi has maintained the same operating
structure as that of Mininet. The Ubuntu operating system should be preferred, especially its Long Term Support (LTS) versions, as they are the most stable
Ubuntu distributions.

## Why open source code?
We will answer this question with a simple answer: because most of the time we (you, I and everyone) have the freedom to use the tool/program we want.
Whether it is because we need to do work or academic research, or because we want to know more about Mininet-WiFi, or even because we need to modify it
to suit our needs, we can choose. However, this seems like a ready answer, which we often receive as an answer by others when we wonder about the
advantages of opening the source code of a particular program. Arguing chronologically, we could say that without Mininet-WiFi, I, Ra-
mon, would not have obtained a doctoral degree; many researchers would not have done their research; Mininet, the emulator Mininet-WiFi was based on,
would probably not exist either, and so on. What we mean is that without open source philosophy, we would not have access to Mininet and would not have
developed Mininet-WiFi. Just as Mininet would not have been developed with-out the previous development of its backbone and its subsequent availability
for anyone to use. Most likely you would not even be reading this book now and many fewer persons would be interested in the subjects we covered in it.
Can you imagine how much research on other topics would be undermined by only focusing on the field of research covered in this book and ignoring other
possibilities? Perhaps you will have a better idea as you complete the tutorials proposed throughout this book.
There is a whole chain that would be seriously impacted if the codes were not free to use. The main paper [14] about Mininet alone has had about 1500
direct citations, not to mention countless indirect citations by blogs and even
the media.

## Experiences: Impact, Reproducibility and Quality
If you are wondering whether it is worth researching and exposing your code to the public, even though it is still in the early stages of development, here
are some reports of experiences we have gained throughout Mininet-WiFi development.

**Impact**. Making code, data, documentation and demonstration videos public  has certainly contributed and still greatly contributes to increasing Mininet-
WiFi’s visibility. Although there has been no systematic and qualitative assessment of the Mininet-WiFi community, users have contributed to the project
several times, whether by discussing or even suggesting code improvements and new implementations.

**Reproducibility**. Making data public and reproducible is not always a simple task. By the way, writing a book whose tutorials users can complete without
any setbacks is not easy. Most likely there will be one or another tutorial that will not flow as expected. This is due to several factors, such as differences in
tool versions, issues that may be related to the operating system, hardware, etc. Throughout the development of Mininet-WiFi, we had a hard time reproducing
experiments by other researchers, as there was often not enough information to do so. For this reason, we have chosen not only to make our experimentspublic, but also to describe how they can be reproduced. Making research
reproducible generally adds credibility to its respective work and obtained results.

**Quality**. In a broader sense of research quality, all the experiences gained throughout the development of Mininet-WiFi allowed us to learn and refine
our research. Although ensuring the reproducibility of a project increases workload, reproducible work has a number of significant advantages, such as:
(i) synergy with open source functionality, as the latter increases the chances of direct and indirect reproducibility and, consequently, (ii) greater impact, since
the chances of researchers using the solutions proposed by reproducible works increase; (iii) improvement of programming habits, wherein special attention
is given to code quality; (iv) encouragement of the use of scientific workflows, as researchers are carefully concerned with providing reliable results so that
anyone can produce results similar to those they have obtained. So if you have the opportunity, and if your code is not a license, patent, or any other copyrighted content, try making your code public!


# Authors  
Ramon dos Reis Fontes (ramon.fontes@imd.ufrn.br)    
Christian Rodolfo Esteve Rothenberg (chesteve@dca.fee.unicamp.br)  