# AIA_GO_City_GANS

Carbon Emissions reduction is a topic on the table for a long. The EPA stated that 27% of carbon emissions is from transportation, while the EU has found the percentage to reach 29%. Hence, decreasing the traveled distance and accommodating zero-carbon transportation are proposed solutions. The UN habitat for a better Urban future has set 5 main principles to address the transportation issue. These principles incorporate solving urbanization challenges of population growth, urban sprawl, poverty, inequality, pollution, and congestion. Consequently, a green city graph of nodes and streets or edges should provide walkable and cyclist-friendly streets, provide public transportation and transit lines, promote interconnected hierarchal roads, furthermore encompass sufficient parking spaces.This project addresses city generation by utilizing two different approaches

# Approaches
This project has adopted two approaches to address generative city design and planning. Conv-GAN has experimented with processing the City masterplan as lines /edges and nodes which is a common approach everyone explores using the google maps app. Grey infrastructure or streets represents 30% of the city’s total area.

![image](https://user-images.githubusercontent.com/108461498/182232356-c4c2e89e-e3a5-42d0-b9ea-ceda02749226.png)


1. DCGAN

A generative adversarial network (GAN) relies on discriminators and generators, GAN generates new data similar to those used in its training. One of the most popular applications of GAN is people’s photos that don’t exist. People’s facial photos have common features that resemble city plans.

![image](https://user-images.githubusercontent.com/108461498/182232629-e4e35e83-e593-460d-90e6-6651b2c23899.png)

Results 1
![image](https://user-images.githubusercontent.com/108461498/182233019-b5aebcb5-a599-4b43-b123-a18705f4c898.png)


Results 2 
![image](https://user-images.githubusercontent.com/108461498/182233045-cd92d725-ad9e-4c31-a652-5061258a9f3e.png)



2. Decoding space Script

This approach is built on ‘Amsterdam’ city planning attributes that are fed later on using  DS in rhino/GH to explore generative cities from another existing one. This approach is adequate for urban growth or expansion of cities to follow the old one, it is more like cloning city attributes and features to support its continuity.

![image](https://user-images.githubusercontent.com/108461498/182232707-99a2c2c4-d1f8-432c-838c-6dc9922f8483.png)


# Recommendations based on results

It is essential to analyze cities more profoundly. As for DCGAN , it is recommended to enlarge the dataset size. and hence the number of hyper parameters to get more accurate and realistic generations of cities. 



![image](https://user-images.githubusercontent.com/108461498/182232817-f63dc84c-451a-4abc-9010-083c25a3256a.png)

