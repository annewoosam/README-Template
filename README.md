
<!-- PROJECT LOGO -->
<br />
<p align="center">

  </a>

  <h3 align="center">The Dynamic Checklist Generator</h3>

</p>

<!-- TABLE OF CONTENTS -->
## Table of Contents

* [About the Project](#about-the-project)
  * [Built With](#built-with)
  * [Deployed With](#deployed-with)
* [Getting Started](#getting-started)
  * [Prerequisites](#prerequisites)
  * [Installation](#installation)
* [Usage](#usage)
* [Roadmap](#roadmap)
* [Contributing](#contributing)
* [License](#license)
* [Contact](#contact)
* [Acknowledgements](#acknowledgements)

<!-- ABOUT THE PROJECT -->
## About The Project

The Dynamic Checklist system allows end-users to create their own checklists with the ability to add help prompts and link to video clips containing just-in-time refreshers of key training information.

As the preparer moves through the checklist, their answers are saved to a database and fed to the reviewer, who will be notified that the checklist is ready for use in review. The reviewer can fill out additional information that is saved to the database. If an item needs to be corrected, the reviewer can send a notification to the preparer. Both preparer and reviewer can see Kanban boards to keep track of what remains to be done based on the answers entered in the question template.

Once an item is ready for delivery, the reviewer can send a notification to the person the work is being prepared for by adding or selecting him/her from a drop down list. A blind copy of the message can be made to a centralized inbox, allowing anyone who has access to the inbox to retrieve the e-mail and forward it as needed.

Finally, the checklist allows the reviewer to view reporting on which questions are currently marked for correction, so that appropriate training can be performed quickly.

### Built With

### Local Environment Tools
* Mac OS High Sierra or above
* [Vagrant (Chef/Linux/Ubuntu 18.04)](https://www.vagrantup.com/docs)
* [Visual Studio Code](https://code.visualstudio.com/)

### Development

* [Python](https://www.python.org)
* [Flask](https://flask.palletsprojects.com/en/1.1.x/)
* [JavaScript](https://developer.mozilla.org/en-US/docs/Web/JavaScript)
* [jQuery](https://jquery.com)
* [PostgreSQL](https://www.postgresql.org)
* [Faker API](https://faker.readthedocs.io/en/master/)
* [SQLAlchemy](https://www.sqlalchemy.org)
* [HTML](https://developer.mozilla.org/en-US/docs/Web/HTML)
* [CSS](https://developer.mozilla.org/en-US/docs/Web/CSS)
* [Jinja2](https://jinja.palletsprojects.com/en/2.11.x/)
* [JSON](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/JSON)
* [Charts.js](https://www.chartjs.org/docs/latest/)
* [Bootstrap](https://getbootstrap.com)
* [Font Awesome](https://fontawesome.com)

### Deployed With

* [AWS Lightsail](https://aws.amazon.com/lightsail/)
* [Ubuntu 18.04](https://help.ubuntu.com/)
* [NGINX](https://nginx.org/en/)
* [GoDaddy](https://www.godaddy.com)
* [Certbot](https://certbot.eff.org/)
* [SSL Labs](https://www.ssllabs.com/ssltest/)

### Resources
* [Digital Ocean Community](https://www.digitalocean.com)
* [AWS IQ](https://aws.amazon.com/about-aws/whats-new/2019/09/introducing-aws-iq/)

<!-- GETTING STARTED -->
## Getting Started

To get a local copy up and running follow these simple example steps.

### Prerequisites

* python

### Installation

1. Clone the repo

```sh
git clone https://github.com/annewoosam/dynamic-checklist-generator.git
```
2. Create directory
```sh
mkdir dynamic-checklist-generator
```
3. Create virtual environment
```sh
virtualenv env
source env/bin/activate
```

4. Install Requirements
```sh
pip install -r requirements.txt
```

5. Launch server
```sh
python3 server.py
```
7. Seed database.

8. Access the app at localhost:5000

9. Practice creating your own JSON files to seed longer checklists, registering and logging in, creating a template including setting up links to private or public YouTube videos for training, creating a checklist and recording activity, reviewing Kanban boards, setting up a centralized inbox on gmail, changing message text and viewing training areas in reporting, as well as deleting records from psql using the back-end. Update a record from corrections required to ready to watch the related training question disappear from the Reporting tab.

<!-- USAGE EXAMPLES -->
## Usage

The Dynamic Checklist Generator helps you keep track of complicated processes.

<!-- ROADMAP -->
## Roadmap

* Landing page register and log-in button split
* Drop-Down direct feed to database
* Refresh data in same page using AJAX
* Twilio 2FA
* Twilio SMS text notifications
* Twilio reminders
* Twilio chat
* Training log
* Time per project calculator
* Role-based permissions including the ability to delete records created by user

<!-- CONTRIBUTING -->
## Contributing

Contributions are what make the open source community such an amazing place to be learn, inspire, and create. Any contributions you make are **greatly appreciated**.

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request


<!-- LICENSE -->
## License

The MIT License (MIT) Copyright (c) 2020 Anne Woo-Sam

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.

<!-- CONTACT -->
## Contact

Anne Woo-Sam - [@annewoosam](https://twitter.com/annewoosam) - annewoosamcode@gmail.com

Project Link: [https://github.com/annewoosam/dynamic-checklist-generator.git](https://github.com/annewoosam/dynamic-checklist-generator.git)


<!-- ACKNOWLEDGEMENTS -->
## Acknowledgements
* [Pexels](https://www.pexels.com)
* Hackbright instructors: Marisa Gloor, Katrina Huber-Juma and Andrew Blum
* Mentors Ebh Teng and Tejaswi Agarwal

<!-- MARKDOWN LINKS & IMAGES -->
<!-- https://www.markdownguide.org/basic-syntax/#reference-style-links -->

