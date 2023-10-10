# Writeup: The Structure of the "THE"-Multiprogramming System



<center> 吴墨笛 2100013081 </center>



Dijkstra's "The Structure of the 'THE' - Multiprogramming System" is a research paper, which introduces an operating system invented by him and his team. The motivation of this paper is to briefly present the hierarchical structure of that multiprogramming system.

Compared with the "state-of-the-art" systems, Dijkstra's system has the following benefits. First of all, its simplicity is surely a big highlight. Being divided into 5 levels, the "THE" system provides a clear and explicit hierarchical structure and eliminates unnecessary complexity found in other contemporary systems. Secondly, it better utilizes system resources, leading to higher efficiency. Since it's a multiprogramming system, it allows different processes to share those hardware usages, so that it can achieve a better overall performance. What's more, its priority-based scheduling approach makes it more practically meaningful. That ensures that high-priority tasks would be of the first importance to the system. Last but not least, there's a built-in mechanism for deadlock detection, which ensures that things above can run perfectly.

Though it is true that the "THE" system wins in some aspects, it is not flawless. It seems that programs run on it are highly dependent on hardware, which makes them less likely to be compatible since their size and the structures of them are rigid. Moreover, it is designed without the mechanism of dynamic memory allocation, hence there is a limit to its flexibility and efficiency as the memory should be allocated at compile-time.

Also, there's much to talk about in this paper from today's perspective. Besides the major technical concepts of his work, Dijkstra's paper shares many details about his experience while engaging in the research and experiment. Plus, his paper, while innovative for its time, relied on simpler experiments and demonstrations due to limited computational capabilities. On the contrary, contemporary papers tend to delve into highly specific research areas with a deeper level of analysis and experimentation, including more complex mathematical models, more extensive statistical analysis, and so on.