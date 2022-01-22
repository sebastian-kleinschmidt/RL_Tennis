<div id="top"></div>

<br />
<div align="center">

<h3 align="center">Deep Reinforcement Learning Project: Tennis</h3>

  <p align="center">
    This projects demonstrates multiple agentt learning to play a cooperative tennis match.
    <br />
    <a href="https://github.com/sebastian-kleinschmidt/RL_Tennis"><strong>Explore the docs »</strong></a>
    <br />
    <br />
    <a href="https://github.com/sebastian-kleinschmidt/RL_Tennis">View Demo</a>
    ·
    <a href="https://github.com/sebastian-kleinschmidt/RL_Tennis/issues">Report Bug</a>
  </p>
</div>



<!-- TABLE OF CONTENTS -->
<details>
  <summary>Table of Contents</summary>
  <ol>
    <li>
      <a href="#about-the-project">About The Project</a>
      <ul>
        <li><a href="#built-with">Built With</a></li>
      </ul>
    </li>
    <li>
      <a href="#getting-started">Getting Started</a>
      <ul>
        <li><a href="#prerequisites">Prerequisites</a></li>
      </ul>
    </li>
    <li><a href="#usage">Usage</a></li>
  </ol>
</details>



<!-- ABOUT THE PROJECT -->
## About The Project

[![Product Name Screen Shot][product-screenshot]](https://example.com)

This projects demonstrates multiple agentt learning to play a cooperative tennis match using **Deep Reinforcement Learning**.

### Environment Details

#### Reward
In this environment, two agents control rackets to bounce a ball over a net. If an agent hits the ball over the net, it receives a reward of +0.1. If an agent lets a ball hit the ground or hits the ball out of bounds, it receives a reward of -0.01. Thus, the goal of each agent is to keep the ball in play.

#### State and Action Space
The observation space consists of 8 variables corresponding to the position and velocity of the ball and racket. Each agent receives its own, local observation. Two continuous actions are available, corresponding to movement toward (or away from) the net, and jumping.

#### Goal
The task is episodic, and in order to solve the environment, the agents must get an average score of +0.5 (over 100 consecutive episodes, after taking the maximum over both agents). Specifically,

- After each episode, we add up the rewards that each agent received (without discounting), to get a score for each agent. This yields 2 (potentially different) scores. We then take the maximum of these 2 scores.
- This yields a single score for each episode.

The environment is considered solved, when the average (over 100 episodes) of those scores is at least +0.5.

<p align="right">(<a href="#top">back to top</a>)</p>

### Built With

* [Jupyter Notebook](https://jupyter.org/)
* [Conda](https://docs.conda.io/)
* [PyTorch](https://pytorch.org/)

<p align="right">(<a href="#top">back to top</a>)</p>



<!-- GETTING STARTED -->
## Getting Started

To get a local copy up and running follow these simple example steps.

### Prerequisites and Installation

This project needs Conda installed on your system to create the needed environment. To then create a conda environment including all dependencies, use the following commands:
1. Create and activate a conda environment:
  ```sh
  conda create --name drl python=3.6
  source activate drl
  ```
> :warning: **If you are on a Windows machine**: Use ```activate drl``` instead of ```source activate drl```

2. Install required dependencies:
  ```sh
  pip install -r requirements.txt
  ```

3. Create an IPython kernel for the drl environment:
  ```sh
  python -m ipykernel install --user --name drl --display-name "drl"
  ```


<!-- USAGE EXAMPLES -->
## Usage
You can start the Jupyter Notebook by executing ```jupyter notebook``` in an active drl Conda environment (see prerequisites section). Execute the documented cells to either train a new agent or use the preptrained one.

<p align="right">(<a href="#top">back to top</a>)</p>

<!-- MARKDOWN LINKS & IMAGES -->
<!-- https://www.markdownguide.org/basic-syntax/#reference-style-links -->
[contributors-shield]: https://github.com/sebastian-kleinschmidt/RL_Tennis.svg?style=for-the-badge
[contributors-url]: https://github.com/sebastian-kleinschmidt/RL_Tennis/graphs/contributors
[forks-shield]: https://github.com/sebastian-kleinschmidt/RL_Tennis.svg?style=for-the-badge
[forks-url]: https://github.com/sebastian-kleinschmidt/RL_Tennis/network/members
[stars-shield]: https://github.com/sebastian-kleinschmidt/RL_Tennis.svg?style=for-the-badge
[stars-url]: https://github.com/sebastian-kleinschmidt/RL_Tennis/stargazers
[issues-shield]: https://github.com/sebastian-kleinschmidt/RL_Tennis.svg?style=for-the-badge
[issues-url]: https://github.com/sebastian-kleinschmidt/RL_Tennis/issues
[license-shield]: https://github.com/sebastian-kleinschmidt/RL_Tennis.svg?style=for-the-badge
[license-url]: https://github.com/sebastian-kleinschmidt/RL_Tennis/blob/master/LICENSE.txt
[linkedin-shield]: https://img.shields.io/badge/-LinkedIn-black.svg?style=for-the-badge&logo=linkedin&colorB=555
[linkedin-url]: https://www.linkedin.com/in/sebastiankleinschmidt/
[product-screenshot]: images/tennis.gif