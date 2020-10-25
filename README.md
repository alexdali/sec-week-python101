<!-- TABLE OF CONTENTS -->
## Table of Contents

* [About the Project](#about-the-project)
* [Built With](#built-with)
* [Getting Started](#getting-started)
* [Prerequisites](#prerequisites)
* [Installation](#installation)
* [Usage](#usage)
* [Roadmap](#roadmap)
* [Contributing](#contributing)
* [License](#license)
* [Contact](#contact)



<!-- ABOUT THE PROJECT -->
## About The Project


Use the srm (safe rm) command to safely delete files. 
The command works like a normal rm, that is, 
* it gets the path to the file as input, but instead of deleting it, 
* it compresses it with the gzip utility and 
* moves it to the ~/RECYCLE directory (trash). 
* files that have been there for more than seven days are automatically deleted from RECYCLE. 
Deleting old files is activated after each srm call.

### Built With
The srm command was created using bash scripting



<!-- GETTING STARTED -->
## Getting Started

To get a local copy up and running follow these simple example steps.

### Prerequisites

All you need is a Linux system and a user account in it

### Installation

1. Create your own bin directory in your home directory: mkdir ~/bin, 
2. Then use the following commands to add the string *export PATH="${PATH}:~/bin"* to the .bash_profile file. 
```
echo 'export PATH="${PATH}:~/bin"' >> ~/.bash_profile
```
3. Then use the following command to run ~/.bash_profile
```
. ~/.bash_profile
```
The .bash_profile file is automatically executed every time you connect to the server, 
and this command will add your personal bin directory to the global $PATH, so we can call these scripts from anywhere. 
3. After that, you need to put this script (srm file) in this directory
and run it from anywhere as a command!


<!-- USAGE EXAMPLES -->
## Usage

*TO-DO*


<!-- ROADMAP -->
## Roadmap

1. Compression of deleted files using the gzip utility
2. And move them to the ~/RECYCLE directory



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

Distributed under the MIT License. See `LICENSE` for more information.



<!-- CONTACT -->
## Contact

Alexey - email@example.com

Project Link: [https://github.com/alexdali/sec-week-python101](https://github.com/alexdali/sec-week-python101)
