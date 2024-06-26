# CornerGrocer

CS210 Corner Grocer

Summarize the project and what problem it was solving.

The project CornerGrocer, essentially was taking data from a file, re-orienting the data, communicating within the program between two languages, Python, and C++, and then outputting the data. There is some more complexity to the project, but the problem was generally that a company needed a tool in order to analyze data to help them understand metrics of sales for items bought during a day, helping them optimize the structure of their store and what to put where to have better sales.

What did you do particularly well?

I think what I did well is integrating the data into different forms and orienting that using the given tools available to me with the languages I had been using. For example, I really was dead set on using a Hash Map, but initially when making the program, I realized Python really did not need that and I ended up scrapping the idea, because I could just use a dictionary, but later down the road I realized that C++ was doing the last function, which got me excited because I was able to use the Hash Map within the program. The reason this excited me so much was because I had never gotten the chance to create a program that used Objects within a data structure before, and it gave me more practice implementing data structures within the code.

Where could you enhance your code? How would these improvements make your code more efficient, secure, and so on?

I realized after the fact when I got feedback from my second project that the way that I had been writing code was not exactly the way I had been supposed to been writing it. Unfortunately, I got this after I submitted my project 3 but ultimately, I do not think it will affect the overall program. More specifically what I am talking about is that when I wrote classes I did not realize that the standard was to write all the functionality for the class in one CPP file, short of maybe the getters and setters in a separate file. What I ended up doing was segmenting the different functions because I wrongly believed that the standard was to split everything up but after asking my friends that are working in the field currently, they helped explain more in depth that it was not the most efficient way to do it, and why. Ultimately consolidating class code into one file generally will make it easier to maintain and understand because the smaller number of files you have the less complicated it can be for other people to read and understand. In addition to that, it is easier to have bugs if you have multiple cpp files for one class and it may also make it less secure.

Which pieces of the code did you find most challenging to write, and how did you overcome this? What tools or resources are you adding to your support network?

The most challenging pieces of code that I wrote in this project probably had to do with the interconnectivity of the program itself between different functions using the objects and data structure implemented. It was less about understanding exactly what I had been trying to do, but more about understanding what the syntax was exactly that I had to commit myself to write to make the program work most efficiently. For example, one of the things that I could not figure out while writing this program was how to have Python output the data files into the .dat file in the way I had wanted it to. What would happen was it would take the name of the item, and the frequency of the number, and segregate them onto different lines, which really drove me crazy because I was not totally sure that the HashMap could be integrated with the format of that data in the file. Luckily, I continued to write the program and see if it would work anyway because I was interested what exactly would happen if I tried to make it work anyway, and it turns out that it did and that the format of the file ultimately did not matter because the object treated each line as the different parts of the object that needed to be filled.

What skills from this project will be particularly transferable to other projects or course work?

The most valuable skill from this project that I think is going to be transferable is communication between the two languages. I really enjoyed that I have working examples now of the interoperability of Python and C++ because it really helped give me a much better understanding of full stack development within the spectrum of a real-life scenario.

How did you make this program maintainable, readable, and adaptable?

I think that I could have done a better job with this. Per what I had been saying in the third question about how I could have enhanced my code. I did my best to put comments where I had thought they would best be needed to help explain the code but not to clutter it, though I have learned after the fact that it would be better to write documentation specifically along with a design document which generally again, I have found is standard within the field. This and that in an actual workplace setting, depending on where you are it can be much better to submit one line of code per day when you are first starting out so other more advanced people can comment on your code and you do not make mistakes, (this is after posting the design document of course)
