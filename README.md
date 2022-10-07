
<a name="readme-top"></a>

<!-- PROJECT LOGO -->
<br />
<div align="center">

  <h3 align="center">Developing a Handwritten Digits Classifier with PyTorch</h3>

  <p align="center">
    <br />
    <a href="https://github.com/adebowalep/Handwritten-Digits-Classifier-with-PyTorch/blob/master/MNIST_Handwritten_Digits.ipynb"><strong>Explore the jupyter notebook »</strong></a>
    <br />
    <br />
    <a href="https://github.com/adebowalep/Handwritten-Digits-Classifier-with-PyTorch/tree/master/data/MNIST/raw">View Data</a>
  </p>
</div>



<!-- TABLE OF CONTENTS -->
<details>
  <summary>Table of Contents</summary>
  <ol>
    <li>
      <a href="#about-the-project">About The MNIST dataset</a>
      <ul>
        <li><a href="#built-with"></a></li>
      </ul>
    </li>
    <li>
      <a href="#getting-started">Getting Started</a>
      <ul>
        <li><a href="#installation">Installation</a></li>
      </ul>
    </li>
    <li><a href="#usage">Usage</a></li>
    <li><a href="#roadmap">Roadmap</a></li>
    <li><a href="#contributing">Contributing</a></li>
    <li><a href="#contact">Contact</a></li>
  </ol>
</details>



<!-- ABOUT THE PROJECT -->
## About The Project

<img src="/img/digits.png" alt ="Handwritten Digits" width="500" height="600">

MNIST is a popular handwritten numeric dataset containing 60,000 handwritten numbers for machine learning model training and 10,000 handwritten numbers for model testing. This dataset is very useful for testing a model or a new algorithm, if the model has been tested on MNIST and achieves high accuracy, the new algorithm is probably correct. If the algorithm doesn't work on MNIST, it won't work at all.


<p align="right">(<a href="#readme-top">back to top</a>)</p>



### Built With

The libraries used in the project are:

* PyTorch
* Matplotlib
*  NumPy



<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- GETTING STARTED -->


### Installation

_Below is an example of how you can instruct your audience on installing and setting up your app. This template doesn't rely on any external dependencies or services._

1. Get a free API Key at [https://example.com](https://example.com)
2. Clone the repo
   ```sh
   git clone https://github.com/your_username_/Project-Name.git
   ```

<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- ROADMAP -->
## Roadmap



- [x] Step 1:
    * Loaded the dataset from torchvision.datasets
    * Used transforms  to convert the data to tensors, normalized, and flatten the data.
    * Created a `DataLoader` for the dataset

- [x] Step 2:
    * Visualized the dataset using the DataLoader without any normalization and flattening
    * Explored the size and shape of the data and provided a brief justification of the preprocessing steps

- [x] Step 3:
    * Using PyTorch,I built a neural network to predict the class of each given input image
    * Created an optimizer to update the network’s weights
    * Used the training DataLoader to train the neural network

- [x] Step 4:
    * Evaluated the neural network’s accuracy on the test set.
    * Tuned the model hyperparameters and network architecture to improve the test set accuracy.

- [x] Step 5:
    * Used torch.save to save the trained model.
    

See the [jupyter notebook ](https://github.com/adebowalep/Handwritten-Digits-Classifier-with-PyTorch/blob/master/MNIST_Handwritten_Digits.ipynb) for the full implementation.

<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- CONTRIBUTING -->
## Contributing

If you have a suggestion that would make this better, please fork the repo and create a pull request.
Don't forget to give the project a star! Thanks again!

1. Fork the Project
2. Create your Feature Branch (`git checkout -b `)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

<p align="right">(<a href="#readme-top">back to top</a>)</p>


<!-- CONTACT -->
## Contact

OJO Suleiman Adebowale - [twitter](https://twitter.com/Paragonadey) - suleimanojo3@gmail.com

Project Link: [https://github.com/your_username/repo_name](https://github.com/adebowalep/Handwritten-Digits-Classifier-with-PyTorch)

<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- MARKDOWN LINKS & IMAGES -->
<!-- https://www.markdownguide.org/basic-syntax/#reference-style-links -->
[contributors-shield]: https://img.shields.io/github/contributors/othneildrew/Best-README-Template.svg?style=for-the-badge
[contributors-url]: https://github.com/othneildrew/Best-README-Template/graphs/contributors
[forks-shield]: https://img.shields.io/github/forks/othneildrew/Best-README-Template.svg?style=for-the-badge
[forks-url]: https://github.com/othneildrew/Best-README-Template/network/members
[stars-shield]: https://img.shields.io/github/stars/othneildrew/Best-README-Template.svg?style=for-the-badge
[stars-url]: https://github.com/othneildrew/Best-README-Template/stargazers
[issues-shield]: https://img.shields.io/github/issues/othneildrew/Best-README-Template.svg?style=for-the-badge
[issues-url]: https://github.com/othneildrew/Best-README-Template/issues
[license-shield]: https://img.shields.io/github/license/othneildrew/Best-README-Template.svg?style=for-the-badge
[license-url]: https://github.com/othneildrew/Best-README-Template/blob/master/LICENSE.txt
[linkedin-shield]: https://img.shields.io/badge/-LinkedIn-black.svg?style=for-the-badge&logo=linkedin&colorB=555
[linkedin-url]: https://linkedin.com/in/othneildrew
[product-screenshot]: images/screenshot.png
[Next.js]: https://img.shields.io/badge/next.js-000000?style=for-the-badge&logo=nextdotjs&logoColor=white
[Next-url]: https://nextjs.org/
[React.js]: https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB
[React-url]: https://reactjs.org/
[Vue.js]: https://img.shields.io/badge/Vue.js-35495E?style=for-the-badge&logo=vuedotjs&logoColor=4FC08D
[Vue-url]: https://vuejs.org/
[Angular.io]: https://img.shields.io/badge/Angular-DD0031?style=for-the-badge&logo=angular&logoColor=white
[Angular-url]: https://angular.io/
[Svelte.dev]: https://img.shields.io/badge/Svelte-4A4A55?style=for-the-badge&logo=svelte&logoColor=FF3E00
[Svelte-url]: https://svelte.dev/
[Laravel.com]: https://img.shields.io/badge/Laravel-FF2D20?style=for-the-badge&logo=laravel&logoColor=white
[Laravel-url]: https://laravel.com
[Bootstrap.com]: https://img.shields.io/badge/Bootstrap-563D7C?style=for-the-badge&logo=bootstrap&logoColor=white
[Bootstrap-url]: https://getbootstrap.com
[JQuery.com]: https://img.shields.io/badge/jQuery-0769AD?style=for-the-badge&logo=jquery&logoColor=white
[JQuery-url]: https://jquery.com 
