<!-- Improved compatibility of back to top link: See: https://github.com/othneildrew/Best-README-Template/pull/73 -->
<a name="readme-top"></a>

<!-- PROJECT HEADER -->
<br />
<div align="center">
  <h3 align="center">AWS SAM Nested Application Parameter Sample</h3>
  <p align="center">
    A simple project to show how to use a nested parameter within AWS SAM.
    <br />
  </p>
</div>

### Built With

[![MIT License][mit-lic-shield]][mit-lic-url]
[![Python][python-shield]][python-url]
[![AWS Serverless Application Model][aws-sam-shield]][aws-sam-url]
<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- GETTING STARTED -->
## Getting Started

Step 1 - Simply clone

Step 2 -Setup AWS credentials via one of the many methods. For example:

``` aws config ```

or 

``` export AWS_PROFILE=profile_name```

Step 3 - Deploy using AWS SAM

```sam deploy --guided --stack-name sam-nested-testing-stack --capabilities CAPABILITY_IAM CAPABILITY_AUTO_EXPAND```

It will prompt with a few questions. Answer all questions with Y (of course know you are answering yes first of all).

Step 4 - Confirm it worked!  Just review the App-two Parameters.  Should look like this:

[![Results Screen Shot][results-screenshot]]()

### Prerequisites

I recommend building using [Visual Studio Code's devcontainer](https://code.visualstudio.com/docs/devcontainers/containers).

I've included a .devcontainer.json file that already builds correctly with the prerequisite software.


See the [open issues](https://github.com/othneildrew/Best-README-Template/issues) for a full list of proposed features (and known issues).

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- CONTRIBUTING -->
## Contributing

Contributions are what make the open source community such an amazing place to learn, inspire, and create. Any contributions you make are **greatly appreciated**.

If you have a suggestion that would make this better, please fork the repo and create a pull request. You can also simply open an issue with the tag "enhancement".
Don't forget to give the project a star! Thanks again!

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- LICENSE -->
## License

Distributed under the MIT License. See `LICENSE` for more information. 

<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- CONTACT -->
## Contact

Michael Slattery - [@Slats2U](https://twitter.com/@Slats2U)

Project Link: [https://github.com/mslattery/aws-sam-nested-parameters](https://github.com/mslattery/aws-sam-nested-parameters)

<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- ACKNOWLEDGMENTS -->
## Acknowledgments

Thanks!

* [Best-Readme-Template](https://github.com/othneildrew/Best-README-Template)

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- MARKDOWN LINKS & IMAGES -->
<!-- https://www.markdownguide.org/basic-syntax/#reference-style-links -->
[mit-lic-shield]:https://img.shields.io/badge/license-MIT-blue
[mit-lic-url]:https://choosealicense.com/licenses/mit/
[aws-sam-shield]: https://img.shields.io/badge/AWS-Serverless_Application_Model-yellow/?style=flat&logo=amazonaws
[aws-sam-url]:https://aws.amazon.com/serverless/sam
[python-shield]: https://img.shields.io/badge/Python-3.9-blue
[python-url]:https://www.python.org/
[results-screenshot]: results.png

## Reference Documents

* [Visual Studio Code - Developing inside a Container](https://code.visualstudio.com/docs/devcontainers/containers)

* [AWS SAM - Using nested applications](https://docs.aws.amazon.com/serverless-application-model/latest/developerguide/serverless-sam-template-nested-applications.html)

* [AWS Prescriptive Guidence - Automate deployment of nested applications using AWS SAM](https://docs.aws.amazon.com/prescriptive-guidance/latest/patterns/automate-deployment-of-nested-applications-using-aws-sam.html)
