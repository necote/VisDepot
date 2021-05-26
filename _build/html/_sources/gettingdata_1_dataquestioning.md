# Data Questioning
 
The truth is that just having the technical (or other: drawing, crafting, “making”) skills to create a visualization is not enough. A correctly made (from a technological standpoint) visualization with little thought behind it is kind of like a grammatically correct book about a poorly researched topic: it might not offer anything useful, and potentially worse, it might do more harm than good. 

The idea behind your project is everything. Whether you are doing work for an art collective or a corporate employer you will not get far without flexing some creative *and* critical muscles. Unfortunately, as Timnit Gebru et al. discuss in their article ["Datasheets for Datasets"](https://arxiv.org/abs/1803.09010), while datasets can be easy to find online, they often do not come with clear background information. Therefore, since the thought behind the project is going to drive the product, significant data questioning on our part is an essential place to start.  

This section will cover the basics of data questioning for data/visualization projects. You will notice that many of these questions overlap and circle-back to one another...that is the point!

## Preliminary Questions to Get Us Started 

The questioning necessary for a data project can roughly fall into three buckets:

**Questioning**
- **You:** What data am I looking to use for this project and why? 
- **The Dataset:** Where/how do I get a dataset and how do I know it is reliable? 
- **The Data "Story":** What story or overall narrative am I trying to communicate with this data, why, and do the story and data fit? 

**Goals**
- To provide a few macro-level questions about data/collection/visualization to consider before starting visualization work. 
- To start thinking about where and how to source data for a visualization. 

## Questions for You  
**Question...** 
- **Your role in this:** 
    - Why you are using this data/making this visualization (i.e. what is your goal and why these materials)?
    - Are you generating a meaningful use of this data and/or a meaningful project?   
    - Why are you telling this data story? 
    - Why do you feel you are able to, well positioned to, or even *should* tell this story?

First of all, if you do not care about the data or project, chances are no one else does either. Further, data storage and tools are not free from ethical issues or environmental impact. This is important to always have in mind, but especially in considering how and if to pursue a new project.
  
Keep in mind both your own situation and how you connect with this material. As discussed in the previous section, ["The Feminist Data Manifest-No"](https://www.manifestno.com/) is a particularly helpful guide for thinking through these kinds of questions and helped to inspire the below. I would **strongly** encourage you to check it out now if you have not already!  
 
## Questions for the Dataset (both previously existing data files and any datasets you create)  
**Question...** 
- **The data creator:** Who made the dataset, when, where, how, and why did they do it? And, does that all seem reliable/ethical? How do you know?
- **The circulation and creation of data:** How did the data get to you? Where did you find it? Why is it available? Who was the intended audience? How was this data gathered/created and transformed into the dataset? And, does it seem trustworthy given all of this? If so, why?
- **The data file (high level):** Can you actually understand the data file? For example: What are the different variables? What do the columns and rows mean? What are the data types for each row (categorical, numerical, time/date & etc.)? And, are these categories consistent? 
- **The data file (close reading):** Is it usable? Here this may mean: are there inconsistencies or discrepancies? Is there missing information (nan/missing/wrong value types) that can be fixed? If they can’t be fixed can/should this dataset be used (i.e. is that essential information)? Does the data seem up to date? How do you know?
- **The "narrative" of the dataset:** What does the data *say* it represents and how does it do that? (i.e. What variables are being used to mean or to indicate what results?) Does this seem reliable, correct, responsible, reasonable? How do you know?  
- **Representation:** Who/what/where does the data represent? Was this made *by* a community or *about* a community? Is there a discrepancy between who made the data and who the data is about or concerned with?   

**Do a few quick validity checks!**  
There are many data files online that are incomplete: perhaps they were created for a very specific purpose or have not been kept up to date. In addition to the above questioning, do a few random searches in the data for known information. 

As a very simple and very "low stakes" example: I’ve come across a dataset that said it identifies all the breweries in Vermont, but when I searched the data for some of my favorites, they were missing. This allowed me to realize the file was based on a data source that was neither kept up to date nor comprehensive in its collection processes. However, depending on the data being used, these stakes can be raised exponentially. 


## Questions for Your Data "Story" or Overall Narrative  
**Question...** 
- **The audience/use:** Who are you telling this story or narrative to and why? 
- **Your approach:** Do the data points you've chosen to focus on reflect the narrative you are trying to get across? How are you sure?  
- **Uncertain/missing data:** Do you have all the information you need to tell this data story? Is there missing or uncertain data? If so, have you considered whether the story can still be told given this? If you think it can: Why? And, how do you plan to represent missing and uncertain information?  

**And, do it all over again!** Go back through the above “Qs for You” and “Qs for the Dataset,” but this time consider how they pertain to YOUR narrative and your use of the data.
 
## Questioning Data's Usability
There are *so many* datasets that we should just not use for a visualization! I cannot cover the breadth of such reasons here, but a few thoughts to keep in mind might be: 

Some data might be considered “bad” because it is unusable on a technical level. This might include, for example, incomplete data (data that are missing but essential for the work), inconsistent data, incorrect parameters (the data collected does not “do” what the people who complied the set say it does/what you need for the project), outdated information, & etc.  

And, importantly, other data may seem *theoretically* usable from a technical standpoint, but have been unethically sourced or unthoughtfully representing the subject. In a similar vein, data might also be “bad” because there is no meaningful or justifiable reason to use it (either generally or for your project specifically). 

These are just a few examples of what might indicate "unusable" data, and should not be read as an exhaustive list. For that reason, continuously trying to question your data and your application of that content in visualization is an important starting point for any project.  
 
## Read Further 
- First, if you have not read the above mentioned ["Datasheets for Datasets"](https://arxiv.org/abs/1803.09010) by Timnit Gebru et al. this is a good resource to become familiar with. 
- The Open Data Institute (ODI)'s ["Data Ethics Canvas"](https://theodi.org/wp-content/uploads/2019/07/ODI-Data-Ethics-Canvas-2019-05.pdf) might be a useful tool for considering data ethics issues from the start of any project. This is only one such resource/toolkit created by ODI. Others, including more information on data ethics, can be found [here](https://theodi.org/service/tools-resources/) on their site. 
- Depending on the data you are using and/or where you are located you may need to be aware of GDPR. Tactical Tech's ["Last-Minute GDPR Checklist for Civil Society Organisations"](https://ourdataourselves.tacticaltech.org/posts/20a_GDPR_checklist/) is a useful place to start.
- For a broader understanding of ethics in the field danah boyd et al.'s ["Supporting Ethical Data Research: An Exploratory Study of Emerging Issues in Big Data and Technical Research"](https://datasociety.net/wp-content/uploads/2016/09/SupportingEthicsDataResearch_Sept2016.pdf) is a useful read. 
- For one example of dealing with uncertainty you might check out the Junk Charts post ["Who is a millennial? An example of handling uncertainty"](https://junkcharts.typepad.com/junk_charts/2019/10/who-is-a-millennial-an-example-of-handling-uncertainty.html).
