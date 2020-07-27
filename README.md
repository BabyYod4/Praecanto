# Praecanto

![Praecanto Logo](https://user-images.githubusercontent.com/59289792/88527669-e098b080-cffd-11ea-8a75-05ce735e08f8.png)

Opensource Trading Assistant based on CUDA

## About

The Goal of Praecanto is to search through the web and news articles to give you insights and predictions where certain companies in an industry are going and weather you should invest. In saying that, Praecanto is nothing more than an assistant which helps you with research and creats deep graphs where its predictions come from. 

It is modelled based on CAPM where is calculated the risk factor and wether it is worth the investment. By using a combination of MLP and LSTM Neural Networks it can give predictions when a company is going to release new products, how much impact new products will create and how feasible certain claims made are. 

You simple have to pick a "topic" you are intrested or knowledgable in (for example the smart horticulture sector) and Praecanto will do a deep search to see what this industry is up to. Within one day you will get a detailed report back with sources about what Praecanto expects this market will go into, which companies have the most potentials and how much money you could be making within a year - the risk factor. With this information you can then do some quick personal research before cutting the knot.

Each "topic" is managed by a finetuned Neural Network running on a seperate device. 

