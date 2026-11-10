**Q1: What is the most interesting topic covered in your domain this quarter?**

A1: The most interesting topic covered this quarter is the process of experimental design, including how to design proper controls, selecting independent and dependent variables that reflect an experimental hypothesis, how to properly quantify these variables into numerical values, and employing statistical techniques to derive a conclusion.

As a data science student, I am used to being given datasets that are already built. Experimental design explores the process before that, of setting up an experiment that enables data collection. By following the above principles of experimental design, we are able to collect high quality data and create datasets. I think participating in the process from scratch is a very exciting experience.

**Q2: Describe a potential investigation you would like to pursue for your Quarter 2 Project.**

A2: One potential investigation for Quarter 2 would be performing the experiment on different models. Our project uses qwen 3.5 4b locally. I am curious how our experiment would perform with different frontline models. It would be interesting to see if frontline models have the same relatioships with split and bulk prompting that smaller and older models do. 

This aligns with the goals of Prof. Schwartzman and Prof. Eldrige for DSC-180AB, with the first quarter being "illustrated by experiments on small LLMs" and the second quarter being on "larger LLM experiments", stated [here](https://dsc-capstone.org/enrollment/).

**Q3: What is a potential change you’d make to the approach taken in your current Quarter 1 Project?**

A3: One interesting change in approach would be changing the tasks we are giving the LLM agent. In our current experiment, the tasks are a sequence of arithmetic operations. Then, we either give the LLM all steps at once, or one step at a time. It would've been interesting to see how the LLM would've performed on more subjective word problems.

**Q4: What other techniques would you be interested in using in your project?**

A4: One paper in our literature review,[LLMs Get Lost In Multi-Turn Conversation](https://arxiv.org/abs/2505.06120), explores a technique called sharding, which decomposes any single prompt into multiple smaller prompts that together convey the same the same information as the original prompt. If we could develop a sharding technique for our experiment, we could take any task, decompose it, and compare LLM performance on split and bulk prompts, rather than just arithmetic tasks with natural places to split.