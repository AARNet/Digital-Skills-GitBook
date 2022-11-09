# Types of Data

<br />

## Getting started: What is data?
[Wikipedia](https://en.wikipedia.org/wiki/Data) defines data as a “unit of information” about a person or object that could be a fact, statistic, or other item of information. And according to the Oxford English Dictionary entry, “data” has multiple definitions. Three of the separate but interlinked meanings are particularly helpful in our context of discussing digital data. The three definitions are: 

&#x2022; a known or assumed fact that is used as the basis for calculation or reasonings

&#x2022; a collection of facts used as information or for reference

&#x2022; “quantities, characters, or symbols” in the form of electrical signals that can be used, stored, or transmitted with computer equipment  

The first two are general definitions that apply equally to the real and digital worlds, but we are most interested in the digital data that is represented by the third definition. 

To complicate things further, data can be structured or unstructured. Data that is ready for analysis is structured, so let’s talk about that first. More information about unstructured data has been included in part three of this topic.

This chapter will give you a general understanding of what is meant by the term “data” and some context for thinking about your own use of data.

<a href="https://commons.wikimedia.org/wiki/File:Data_types_-_en.svg#/media/File:Data_types_-_en.svg"><img src="https://upload.wikimedia.org/wikipedia/commons/thumb/6/6d/Data_types_-_en.svg/1200px-Data_types_-_en.svg.png" alt="Data types - en.svg"></a>

  [By João Batista Neto](//commons.wikimedia.org/wiki/File:Data_types_-_pt_br.svg)

<br />

## A bit more info: Two types of data
There are two basic types of structured data: qualitative and quantitative. In this article, we will discuss both data types, some of the different forms they might take, and give some examples of ways in which that data might be analysed.

Let’s discuss qualitative data in a bit more detail. Qualitative data is data that refers to the quality of something - it is generally not an objectively defined measurement but an opinion or generalisation which is often text based. There are generally three subtypes: binary, nominal, ordinal. 

&#x2022; Binary data records something that has two mutually exclusive traits (ie. true or false).

&#x2022; Nominal data describes objects using categories and/or labels (ie. colours of cars). It can also be used to give counts of a particular attribute.

&#x2022; Ordinal data records the order or ranking of something (ie. Education systems have ordered primary, secondary, and tertiary levels, however the difference between each level cannot be quantified specifically).

Now let’s talk more about quantitative data. Quantitative data is based on an objective measurement of something and is numerical in nature. It can be easily used for mathematical and statistical calculations and those results then used for further analysis. Many scientific studies make use of quantitative data. Generally, the sorts of data collected are either measurements or counts.

&#x2022; Measurements are taken according to a specified scale such as length, weight, and currency. Interval scales and ratio scales describe the different measurement types in more detail but we don’t need to delve into that much detail for this example.

&#x2022; Counts are the frequency of which something occurred (7 lightning strikes) or answers how many of something (5 frogs).

A good way to remember the difference between the two types of data is that qualitative data is indicative of the qualities and characteristics of something, whereas quantitative data is all about recording the quantity or measurements of something! 

<br />

## Diving deeper: Structured vs Unstructured Data
Each of the two data types discussed above are generally considered in terms of structured data. The main thing to keep in mind with structured data is that it has already been sorted into a predefined format and there should only be one subtype of one data type recorded in each column of the dataset. Below is an excerpt dataset example of structured data, and you will notice that there are both qualitative and quantitative data. 

| Dataset Order | Sepal Length | Sepal Width | Petal Length | Petal Width | Species       |
|---------------|--------------|-------------|--------------|-------------|---------------|
| 33            | 5.2          | 4.1         | 1.5          | 0.1         | I. setosa     |
| 34            | 5.5          | 4.2         | 1.4          | 0.2         | I. setosa     |
| 99            | 5.1          | 2.5         | 3.0          | 1.1         | I. versicolor |
| 100           | 5.7          | 2.8         | 4.1          | 1.3         | I. versicolor |
| 101           | 6.3          | 3.3         | 6.0          | 2.5         | I. virginica  |

[Excerpt dataset from Iris Flower Dataset - Wikipedia [all measurements in centimetres]](https://en.wikipedia.org/wiki/Iris_flower_data_set) 

Each row of the dataset is the information collected about one iris flower. Each number in the first column “Dataset Order” is ordinal qualitative data: the number identifies the sample in the dataset, no calculations can be based on that number. Columns two to four are all quantitative measurements (in centimetres): parts of sampled iris flowers that could potentially be used in mathematical calculations to compare samples. The last column is nominal qualitative data: the “Species Name”.

The example above specifically shows tabular data as it is human readable or easy for a person to visualise. However, there are ways to structure data without putting it into a tabular form. Examples of this include JSON files and markup languages which structure data in a machine readable form. It can be challenging to decipher the structure of such data without the aid of a computer program to parse it into a human readable form. For example, remote sensing data is generated by machines and includes things like seismic and atmospheric measurements, digital surveillance photos and videos, and satellite imagery. This output is structured and readable for machines, but can be difficult for a human to decipher. It often requires a specific program to output the data in a human readable form.

Unstructured data has not been sorted or formatted and may even be in a narrative form. The primary source can take many different forms including text and media. 

Text data could be a journal entry of someone’s observation of something, an opinion, an experience, a narrative. 
Media that may take the form of photos, videos, or sound files. 

The data extracted from the primary source needs to be transformed into a coherent structure to allow for computational analysis. The extracted data could be comprised of counts specific words in a particular collection of texts or digital surveillance photos that contain a particular object. Whatever the data is, it must be organised, or structured, so that individual attributes are grouped with similar, comparable attributes. Whether the dataset needs to be structured to be machine- or human-readable depends on the project and the types of analysis to be performed on that dataset.

<br />

## More information:

[Definition data](https://www.techtarget.com/searchdatamanagement/definition/data)

[Statistical Language - Quantitative and Qualitative Data](https://www.abs.gov.au/websitedbs/D3310114.nsf/Home/Statistical+Language+-+quantitative+and+qualitative+data)

[Structured vs. Unstructured Data: What’s the Difference?](https://www.ibm.com/cloud/blog/structured-vs-unstructured-data)



