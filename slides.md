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

Container:
  * Docker, LXC, Podman
  * Kubernetes, OpenShift


--

  * PaaS:
    * Heroku
    * Google app Engine
    * etc...

Developer oriented way of deploy the app and leave the rest to platform provider.

--

* FaaS
  * AWS Lambda
  * OpenFaaS
  * etc...

Minimalistic way of deploying just a functions and leave the rest to the hosting company. 

---

# How to deploy on server?

Webserver -> Application server

--

# How to run application server?

* WSGI app
* WSGI app in container (not necessary Docker :))

---
