# inverse_cooking
This model allows you to know how a dish came to life. The ingredients, the process, everything that was reqd. to make it from an image of the dish itself.
If you are already an ML learner or even a beginner in this field, you might have thought of how this model was built.
Well the first thing that comes to mind is image recognition of the food and then predicting the dishes on the model trained on a large dataset. 

Congratulations,
if you've thought along these lines you have made a good invesment of your time in this field. But you are half right. Though indeed we did an image prediction on the images, we instead of an entire inage were more focused on the ingredient pipeline..
# OVERVIEW
Food is something without which life cannot survive. We need food to help us going through our lives. It is a nature’s gift to all the lifeforms present on the earth. As we know cooking is not just a task anymore. The society has built a career over it and people are flowing into that stream of jobs to build their lives. Especially in the country of India where it’s diversified and extravagant cultures have given birth to a number of dishes and tastes for the palette of each and every human being. And coming forward to this age of technology and digitized media, the society now lives in the digital world much more openly than in the real one. Facebook, Instagram and Pinterest have all been the pillars of highlighting a person’s life that normally wouldn’t have been visible to others or even their own selves in the first place. As such a person’s eating style, his cooking pattern, his taste culture was only limited to the person himself. In the older days, when food was only cooked in people’s homes, now a days, with the advancement of one’s lifestyle leading to them having no time to cook look for eating outside as per their requirements. And so, now more than ever, it has become an imperative need for one to know the detailing of the cooked food they eat. However, it is difficult if not impossible to know the exact makings of the food one ingests and so this makes it all the more evident that a person is in need of a system that will identify the makings of a dish right to the grains.
The models previously built on food recognition was based on a retrieval system that took out the ingredient embeddings from the image. This resulted in poor results as most of the initial ingredients prepared before cooking are completely unrecognizable in the end. The resulting change in the texture and colour of the dish also made it impossible to produce accurate results. Also, the prediction relied heavily on the variety and diversity of the dataset and how accurately the cross-embedding were built. In the end, the recipe classification produced poor results since accurate ingredients presented as sets were unable to match properly or lacked a corresponding image object for it to correspond with.
	Therefore, with the help of this model one is able to procure the recipe and name of the dish depicted in the image. In this model, we have produced a method for extracting the details of the dish using two modalities: the ingredients and the image of the food itself. Using these two modalities together, this model is able to achieve the higher threshold of accuracy in comparison to the previously built models.
