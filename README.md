# Orange Sherbet
![GitHub](https://img.shields.io/github/license/metares/findomatic?style=flat-square)

Application for managing and updating PaperMC servers.

*Currently only planning releases for Unix based platforms (Linux & MacOS). Considering most VPS services utilize Unix-like operating systems, this is the natural choice. However, if demand for a Windows version is high, I will work on a Windows release.*

### Installation
#### using curl

```shell
bash -c "$(curl -fsSL https://raw.githubusercontent.com/lennibot/orange-sherbet/main/install.sh)"
```

#### using wget

```shell
bash -c "$(wget https://raw.githubusercontent.com/lennibot/orange-sherbet/main/install.sh -O -)"
```

## Wiki
[View the Wiki here!](https://github.com/lennibot/orange-sherbet/wiki) This will contain the most up to date information on this project as well as help you understand the inner workings of Orange Sherbet.


## Required Python Packages
* requests
* Flask
* Flask-SocketIO
* Gevent

## Planned Features
* Web UI for managing server remotely.
* Automatic version control for PaperMC

## Contributing
Contributions are more than welcomed. 
Please for the time being, create a pull request and describe what you would like to add. I will write a CONTRIBUTING.md document when I feel it's required.

## License
[GPL-3.0](https://choosealicense.com/licenses/gpl-3.0/)
