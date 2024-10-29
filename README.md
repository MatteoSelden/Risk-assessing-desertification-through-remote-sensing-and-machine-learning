# Risk-assessing-desertification-through-remote-sensing-and-machine-learning

The project aims to provide a low-level tool to determine whether an area requires monitoring being at risk of desertification. The case study chosen for training and testing is Zimbabwe, as it’s a country known to be vulnerable to desertification but scarcely considered by current literature. I don’t aim for specific studies, but rather proving that the project can adapt well to a large area without detailed knowledge about it to start with.

All code is written in MATLAB, apart from specific API calls required to download the data from certain databases. I have used AI tools to guide myself through the design of the code, as this was intended as a learning experience and the results of this work are intended to be shared publicly as an open-source tool for low-level evaluations.

I want to clarify that this was mainly a learning experiences to introduce myself to machine learning, mainly through two different projects:
An image recognition model able to distinguish between landscape features to extract the distribution of vegetation, desertic areas and water from satellite images
A predictive model able to capture trends from predictions made in different plausible climatic scenarios, highlighting the chance of worsening of desertification over a certain region

Data used for training and testing acquired from the following databases:
Landsat OLI/TIRS 8-9 C2 L1 satellite images: EarthExplorer (https://earthexplorer.usgs.gov/)
Historical climatic data: ERA5-Land monthly averaged data from 1950 to present (https://cds.climate.copernicus.eu/datasets/reanalysis-era5-land-monthly-means?tab=overview)

More information about the code will be in the wiki, including a tutorial to run the code, which I hope will be fairly easy to follow as it’s one of the main objectives of this project.

You must be very dedicated to have read through all this super formal introduction, so… thanks! I hope you can find my code useful, whether it’s for some guidelines on hyper-parametrization, ideas to build your own models or suggestions for easy-to-use and accessible resources and databases. Feel free to contact me or push issues directly.
