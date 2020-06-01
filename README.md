# George-Floyd Library
## Live Brutality Identification  
## Built with :heart: by [Matthew Davis](https://www.linkedin.com/in/tech-lead-matt-davis/) - [linkedin](https://www.linkedin.com/in/tech-lead-matt-davis/) - [github](https://github.com/Deamoner) - [Medium](https://medium.com/@mdavis_71283)

Inspired by the brutality of the George Floyd video and the riots this library seeks to give a methodology and machine learning library for automated identification and mechanism for alert of current brutal situations that are being recorded.

Violence as a response in any situation does not move us in the right direction. We will identify all violence and brutality, then only non-violent responses should be looked at as responses to these tough situations.

TODO: Add Medium Article on the subject

**Help Wanted** - Come help build products that change the world. 

## Roadmap

v0.1
- [ ] Privy Filter - Photo Privacy Library
- [ ] Notebook get all Characters and Poses in Scene
- [ ] Notebook get all Characters Skeletal Depth Location
- [ ] Traintest labeled dataset of scenes and pipeline of character skeletal location data
- [ ] Logistic Regression on Vector Skeletal Differentials Classification Model Training
- [ ] v0.1 Python Package Release

v0.5
- [ ] Review Methodology Accuracy and Corner Cases to Determine new v0.5 Methodology Improvements
- [ ] Roadmap Planning for Next Gen

## Possible Features Improvement List:
1. Facial Aggression - Identify face and level of aggression to add to the model.
2. Sex Identification
2. Gun Identification
3. Blood and Cuts Identification
4. Video Support
5. Audio Support  



## Methodology

Please note this methodology will improve over time and we will use this repo to build out a labeled training and test dataset to increase accuracy.

v0.1
1. Ensure the Media is Recent  - Identifying brutality in the past may have value but we want to make a library for the actionable real world and there will already be a lot of movies/videos that will trigger the algorithms so we will focus on photos marked within the last 24 hours just in case timezone issues and keep the first version simplistic.
2. Compute 3D Human Positions - We combine human pose estimation, and machine learning depth of the image to get a 3D representation of all the humans identified in the pictures.
3. Calculate the Likelihood of Brutality - The first version will use a vector posture differential between multiple characters in the scene. If it appears certain characters are close enough and in a dominating position over another



## Installation - Not working yet

Use the package manager [pip](https://pip.pypa.io/en/stable/) to install George Floyd library.

```bash
pip install george-floyd
```

## Usage

```python
import george-floyd

(bruttality, confidence) = george-floyd.process(img)

```

## Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

Please make sure to update the tests as appropriate.

## License
[MIT](https://choosealicense.com/licenses/mit/)
