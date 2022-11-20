<!-- PROJECT LOGO -->
<br />
<div align="center">
  <a href="#">
    <img src="https://upcdn.io/W142hJk/raw/demo/4mqvR9PaEm.png" alt="logo" height="135px">
  </a>

  <h2 align="center">Informer</h2>
  <p align="center">
    <a
      href="https://github.com/theriturajps/Informer/issues/new?assignees=&labels=bug">Report
      Bug</a>
    ·
    <a href="https://github.com/theriturajps/Informer/issues">Request Feature</a>
  </p>

  <img alt="informer" src="https://img.shields.io/github/stars/theriturajps/informer">
  <img alt="informer" src="https://img.shields.io/github/issues/theriturajps/informer">
  <img alt="informer" src="https://img.shields.io/github/languages/code-size/theriturajps/informer">
  <img alt="informer" src="https://img.shields.io/apm/l/atomic-design-ui.svg?)](https://github.com/tterb/atomic-design-ui/blob/master/LICENSEs">
  

</div>

<h3 align="center">Informer is a OSINT information gathering tool that gathers whois, Sub-domain ,DNS, geolocation and shodan information of the target.</h3>

## Installation 🧑‍🔧​

Install informer with git

```bash
git clone https://github.com/theriturajps/Informer.git
cd informer
pip install -r requirements.txt
```


## Usages 

#### Help Menu 👀​
```bash
python3 informer.py --help
```

#### Simple Usage (whois Information Gethering)
```bash
python3 informer.py -t google.com
```

#### Gather Sub-Domain Info
```bash
python3 informer.py -sd -t google.com
```

#### Gather DNS Info
```bash
python3 informer.py -d -t google.com
```

#### Gather Geolocation Info
```bash
python3 informer.py -g -t google.com
```

#### Gather Shodan Info
```bash
python3 informer.py -s -t google.com
```

#### Gather All Info togather
```bash
python3 informer.py -d -g -s -sd -t google.com
```

#### Save output to file
```bash
python3 informer.py -d -g -s -sd -t google.com -o filename.txt
```

## Contributing 💡

You can propose a feature request opening an issue or a pull request.

Here is a list of Informer's contributors:

<a href="https://github.com/theriturajps">
  <img src="https://avatars.githubusercontent.com/u/107362757?s=96&v=4" />
</a>
