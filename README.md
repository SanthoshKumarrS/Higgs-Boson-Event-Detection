**Higgs-Boson-Event-Detection**

I have worked on a Higgs boson event detection project in this repository to identify provided data as signal or noise. CERN released this dataset in 2014, based on an official ATLAS full-detector simulation.

**Description**: The LHC collides bunches of protons every 50 nanoseconds within each of its four experiments, each crossing producing a random number of proton-proton collisions (with a Poisson expectation between 10 and 35, depending on the LHC parameters) called events8. Two colliding protons produce a small firework in which part of the kinetic energy of the protons is converted into new particles. Most of the resulting particles are very unstable and decay quickly into a cascade of lighter particles.

Based on these properties, the properties of the decayed parent particle are inferred, and the inference chain is continued until reaching the heaviest primary particles. given the elusive nature of neutrinos, their minuscule mass, and the way they oscillate between flavors, one could very well imagine that the mass of leptons comes from an entirely different mechanism. Hence the importance of measuring as precisely as possible the coupling of the Higgs to tau arises.

Particle colliders enable us to probe the fundamental nature of matter by observing exotic particles produced by high-energy collisions. Because the experimental measurements from these collisions are necessarily incomplete and imprecise, machine learning algorithms play a major role in the analysis of experimental data. The high-energy physics community typically relies on standardized machine learning software packages for this analysis and devotes substantial effort towards improving statistical power by hand-crafting high-level features derived from the raw collider measurements.

**Task**: With the given dataset, we have to classify whether the given event was a signal or a background noise in the process of decay for Higgs particle acceleration.
**Metric**: Precision

**Repository Structure**:

Dataset/: Contains the Higgs Boson dataset & Research papers.
Notebook/: Jupyter notebooks detailing data exploration, preprocessing, and model training.
Model/: Saved models with their architecture and weights.

***Project Highlights***

**Data Visualization**: The initial step involved exploring the dataset through insightful visualizations. Using Python libraries like Matplotlib and Seaborn, we gained a deep understanding of the data's distribution, correlations, and potential patterns.

**Data Preprocessing**: Prior to model training, we performed data preprocessing techniques to ensure high-quality input. This included handling missing values, scaling features, and encoding categorical variables.

**Neural Network Model**: Leveraging Keras Tuner, we fine-tuned the Neural Network architecture and hyperparameters to optimize precision, our primary evaluation metric. The choice of precision reflects our emphasis on reducing false positives while classifying signal events.

**Callbacks for Optimization**: Callbacks were implemented to enhance the training process. EarlyStopping helped prevent overfitting, while ModelCheckpoint ensured that the best-performing model was saved.

**Precision**: Through rigorous experimentation and optimization, we achieved an impressive 98% precision in classifying signal and noise events. This remarkable achievement underscores the effectiveness of our approach.

**Conclusion**
This project showcases a comprehensive analysis of the Higgs Boson dataset, culminating in the development of a high-precision Neural Network model using Keras Tuner and callbacks. The achievement of 98% precision highlights the effectiveness of our approach and its potential significance in the field of particle physics research.

Contributions and suggestions are welcome, as we continue to refine and expand our exploration of the Higgs Boson dataset.
