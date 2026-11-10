# Ahmad Ageel

**Email:** aageel@ucsd.edu

**Section:** D09 - Data-driven Design of Nonlinear Architected Materials

**Mentors:** Igor Sfiligoi and Nicholas Boechler

## Questions
**What is the most interesting topic covered in your domain this quarter?**

I found it interesting how we could just simulate data to train the model on instead of conducting physical experiments which would consume so much resources and time. While this helps save time and resources, it puts a new challenge for researchers to make sure the data-generating model is accurate. It also adds a dependency where if that code is not accurate, then all the analysis on it could be unreliable.

**Describe a potential investigation you would like to pursue for your Quarter 2 Project.**

I would like to investigate using gradient based optimization on a machine learning model trained on our generated dataset. I want to see whether we can find spring configurations with lower KE ratios without having to run the full DEM simulation at every optimization step.

**What is a potential change you’d make to the approach taken in your current Quarter 1 Project?**

One change I would make is to look for an existing, validated dataset before generating our own. I feel like generating data through simulations and then analyzing it introduces more opportunities for errors. Using data that has already been validated against real-world physical behavior could help us have more confidence in our findings and focus more on the analysis itself.

**What other techniques would you be interested in using in your project?**

I’d be interested in exploring gradient based optimization further and comparing it with quantum-inspired optimization techniques, which Igor mentioned during our meeting. Since our problem is highly nonlinear, gradient based optimization can get stuck in local minima. I would like to investigate whether these alternative techniques can find better solutions by exploring more of the design space.
