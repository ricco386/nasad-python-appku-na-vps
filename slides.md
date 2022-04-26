# How to deploy Python app to VPS

Richard Kellner

45. Bratislavský Python Meetup

---

# About Me

* Working as hlavný projektant IS dohľadu at Národná banka Slovenska
* Python 10+ years exp. before that PHP developer in London
* RedHat Certified System Administrator + OpenShift Developer
* Chairman at SPy o.z.: [PyCon SK](https://pycon.sk) & [Učíme s hárdverom](https://www.ucimeshardverom.sk/)
* PSF Fellow
* More at [www.linkedin.com/in/richardkellner](https://www.linkedin.com/in/richardkellner)

Note: V prezentácií sú moje vlastné názory a nie sú nijako previazané na môjho aktuálneho (alebo minulého) zamestnávateľa. Nemám žiadne záväzky voči Red Hatu, prednáška nie je sponzorované firmou Red Hat.

---

# Ways to deploy Python app

* Server:
  * Physical
  * VPS
  * IaaS (Cloud)

Most traditional way of doing things, you can DYI all by your self, but require a lot of knowlegde. 

--

Service:
  * systemd
  * supervisord
  * mmonit

Container:
  * Docker, LXC, Podman
  * Kubernetes, OpenShift

---

  * PaaS:
    * Heroku
    * Python Anywhere
    * Google app Engine
    * etc...

Developer oriented way of deploy the app and leave the rest to platform provider.

---

* FaaS
  * AWS Lambda
  * OpenFaaS
  * etc...

Minimalistic way of deploying just a functions and leave the rest to the hosting company. 

---

# How to deploy on server?

--

![](https://miro.medium.com/max/1400/1*rYdZRYct2FKHiGxlJIvORg.png)

--

![](https://miro.medium.com/max/1200/1*xGH9XltLrqRt-_GdmJ2olw.png)

---

# What is WSGI?

The Web Server Gateway Interface is a simple calling convention for web servers to forward requests to web applications or frameworks written in the Python