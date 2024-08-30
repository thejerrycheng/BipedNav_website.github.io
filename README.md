# Monocular Depth Estimation and Control of Human-Robot Locomotion

![Project Banner](static/images/your_banner_image.png)

## Overview

This project explores innovative methods to integrate monocular depth estimation with Virtual Holonomic Constraints (VHC)-based control to enhance bipedal robot locomotion. The goal is to develop a robust framework that enables robots to navigate complex environments, such as stairs and obstacles, using depth perception from a single camera and advanced control strategies. The research is conducted using simulations in NVIDIA Isaac Sim, with plans for real-world testing.

## Table of Contents

- [Overview](#overview)
- [Installation](#installation)
- [Usage](#usage)
- [Project Structure](#project-structure)
- [Features](#features)
- [Research Paper](#research-paper)
- [Contributors](#contributors)
- [License](#license)

## Installation

To run the project locally, follow these steps:

1. **Clone the Repository:**

   ```bash
   git clone https://github.com/thejerrycheng/BipedNav_website.github.io.git
   cd BipedNav_website.github.io
   ```

2. **Install Dependencies:**

   If your project requires any dependencies (e.g., for simulations, data processing, etc.), list them here along with installation instructions.

   ```bash
   pip install -r requirements.txt  # Example for Python dependencies
   ```

3. **Run the Local Server:**

   If you're using GitHub Pages, you can preview your site locally with a tool like `Jekyll` or `http-server`.

   ```bash
   http-server -p 8080  # Example using http-server for a simple HTML site
   ```

4. **View the Project:**

   Open your browser and navigate to `http://localhost:8080` to see the project in action.

## Usage

This website serves as an interactive platform for presenting our research on monocular depth estimation and control for bipedal robots. The site includes:

- A detailed abstract and introduction to the research.
- Videos demonstrating the simulation results.
- Access to the research paper, supplementary materials, and the codebase.

## Project Structure

```bash
BipedNav_website.github.io/
├── index.html                  # Main landing page
├── README.md                   # Project README file
├── static/                     # Static files (images, CSS, JS, videos)
│   ├── css/
│   ├── images/
│   ├── js/
│   └── videos/
├── _config.yml                 # Configuration file (if using Jekyll or similar)
├── _posts/                     # Blog posts or updates (optional)
├── _data/                      # Data files (optional)
└── _includes/                  # HTML includes (optional)
```

## Features

- **Monocular Depth Estimation:** Utilizing deep learning techniques to estimate depth from a single camera.
- **VHC-based Control:** Implementing Virtual Holonomic Constraints for stable and adaptive bipedal locomotion.
- **Simulation and Real-World Testing:** Testing the integration of perception and control in NVIDIA Isaac Sim with plans for real-world validation.
- **Interactive Website:** Showcasing the research through videos, abstracts, and downloadable content.

## Research Paper

You can access the full research paper [here](https://arxiv.org/pdf/<ARXIV_PAPER_ID>.pdf). The paper discusses the methodology, experiments, and results in detail.

## Contributors

- **Qilong Cheng** - [qilong.cheng@mail.utoronto.ca](mailto:qilong.cheng@mail.utoronto.ca)
- **Co-Author Name** - Add email or contact information.
- **Brokoslaw Laschowski** - [brokoslaw.laschowski@utoronto.ca](mailto:brokoslaw.laschowski@utoronto.ca)

This project is supported by the Bionic Lab at the University of Toronto.

## License

This project is licensed under the [Creative Commons Attribution-ShareAlike 4.0 International License](http://creativecommons.org/licenses/by-sa/4.0/). You are free to share and adapt the material as long as appropriate credit is given, and any derivative work is distributed under the same license.
