<p align="center">
  <a href="https://github.com/NIT-DGPortal/portal-main/blob/master/pro1/badge.png">
    <img src="https://github.com/NIT-DGPortal/portal-main/blob/master/pro1/badge.png"
         alt="Gitter">
  </a>
  <h4 align="center">An Django based web-app exclusively for NIT Durgapur</h4>
</p>
<p align="center">
  <a href="#key-features">Key Features</a> •
  <a href="#how-to-use">How To Use</a> •
  <a href="#license">License</a> •
  <a href="#credits">Credits</a> •
</p>


## Key Features
<ul>
  <li> Based on Python</li>
  <li> Powered by Django</li>
  <li> Access secured only to registered students </li>
  <li> Study materials, placement/internship news, contacts all in here</li>
  <li> Open to contribution :v:</li>
</ul>
  
## How to Use

* Start off by cloning this repository into your local directory.
  
  ```bash
  > git clone https://github.com/NIT-DGPortal/portal-main.git 
  ```

* If you prefer virtual-environment ([pipenv](https://pipenv.readthedocs.io/) suggested) get yourself these packages in it. 
  Initiate a python 3 environment
  
  ```bash
  > pipenv --three 
  ```

  Here is what your Pipfile will appear when you're ready to go

  ```bash
  django = "*"
  gunicorn = "*" 
  django-heroku = "*"
  django-crispy-forms = "*"
  django-registration = "*"
  requests = "*"
  ```
* Activate your virtual environment
  
  ```bash
  > pipenv shell
  ```

* Run these commands in your terminal.

  ```bash
  > python manage.py runserver
  ```
  
* Navigate to http://localhost:8000 to see it in action.
## License

Exactly putting we want it to be simple are permissive. Interested contributors are heartedly welcomed. :blush: 
## Credits

* This was made in just a span of 27 hours,yes it was that short :sparkles:
* Authentication and Profile credits to [Satyajit Das](https://github.com/r3trd)
* CSS,Bootstrap Rendering realised by [Anoop Kumar](https://github.com/anoop1311)
* General codebase and framework by [Monsij Biswal](https://github.com/monsij)


