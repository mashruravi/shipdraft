# DataTau

https://datatau.net

## Django based Hacker News clone

DataTau is a clone of popular Hacker News site. It was started in 2014 and went down with no explanation
in May 2019. After a month of inactivity, we decided to create our own clone of the site under a `.net` domain using
a framework familiar to us (Python based Django), reaching Hacker News front page when launching.

We decided to open source the project to avoid the mistakes of the original version and being more community-driven.
Thanks to this you can contribute to make DataTau better and its development will not depend only on a few people, with
the risk of going unmaintained again.

Another goal of this project is becoming Django based Hacker News style news board template you can use to power your
own community.

We built this site very fast and copying a lot of original Hacker News frontend, so you can expect bugs, unsemantic
html, etc. Please visit kanban board of this repository and issues if you think you can be helpful.

## Project setup (Linux version)

* Clone repository:  
```bash
git clone git@github.com:datatau-net/DataTau.git
```

* Install system dependencies:  
```bash
sudo apt install virtualenv python3-dev
```

* Create Python virtual environment
```bash
mkdir ~/.venvs
virtualenv -p python3 ~/.venvs/datatau_env
source ~/.venvs/datatau_env/bin/activate
pip install -r requirements.txt
```

* Clean start
```bash
bash restart_db_dev.sh
```

* Open development url: http://0.0.0.0:8000

## Contributors
<!-- prettier-ignore -->
<table border="0">
  <tr>
    <td align="center"><a href="https://davidadrian.cc"><img
        src="https://avatars3.githubusercontent.com/u/6515763?s=400&v=4" width="100px;"
        alt="https://davidadrian.cc"/><br><sub><b>David Cañones Ⓖ</b></sub></a><br></td>
    <td align="center"><a href="https://pedro-munoz.tech"><img
        src="https://avatars3.githubusercontent.com/u/34843649?s=400&v=4" width="100px;"
        alt="https://pedro-munoz.tech"/><br><sub><b>Pedro Muñoz Ⓖ</b></sub></a><br></td>
    <td align="center"><a href="https://mashruravi.github.io"><img
        src="https://avatars3.githubusercontent.com/u/8961232?s=400&v=4" width="100px;"
        alt="https://mashruravi.github.io"/><br><sub><b>Ravi Mashru</b></sub></a><br></td>
  </tr>
</table>
