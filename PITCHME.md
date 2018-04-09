# Pidevkooste ja Jenkins

---

## Eelmised slaidid
Varasemaid slaide saab vaadata [siit](http://dijkstra.cs.ttu.ee/~gert/jenkins/).

---

## Pidevkooste (Continuous integration)
* [Pidevkooste serverid](https://www.slant.co/topics/799/~best-continuous-integration-tools)
* [Gitlab DevOps strategy](https://about.gitlab.com/2017/10/04/devops-strategy/)

---

## Pidevtarne (Continuous delivery)
[Continuous delivery with GitlabCI](http://blog.kontena.io/continuous-delivery-with-gitlabci/)

---

## Pidevtarne kümme käsku
[The Ten Commandments of Continuous Delivery](https://www.youtube.com/watch?v=fD3P51Yv6so) by Viktor Farcic (Cloudbees)

---

### I - Thou shalt be agile
No silos, No departments!

---

### II - Thou shalt refactor
Rearchitecture your development code into testable code!

---

### III - Thou shalt educate everyone
There is no CD department!

---

### IV - Thou shalt be small
* Big teams cannot do "continuous anything". Only small teams can do "continuous" (up to 10 engineers).
* That means monoliths must be split into smaller parts (microservices).

---

### V - Thou shalt practice TDD (Test-Driven Development)
No tests means no commits.

---

### VI - Thou shalt define your CD pipeline as code
* No more clicking around
* Don't use GUIs for defining CD pipelines.

---

### VII - Thou shalt have a fast pipeline
One coffee, not longer (~15 minutes).

(This depends on the project, but most projects should achieve this!)

---

### VIII - Thou shalt consider fixing a failed pipeline as highest priority
Fix it first, then continue developing.

---

### IX - Thou shalt run the CD pipeline locally
* Run and test as much as possible locally.
* Respect your coworkers.

---

### X - Thou shalt commit only to the master branch
* If you trust your process then you can commit to master.
* You can use feature branches as long as you merge to master once a day.

---

### Veel videoloenguid
* [Managing and Maintaining a DevOps Assembly Line](https://www.youtube.com/watch?v=BJOkB-AUyOo) by Viktor Farcic (Cloudbees)
* [Enterprise DevOps and the Modern Mainframe](https://www.youtube.com/watch?v=mfaUG3Dbk5I) by Brian Dawson (Cloudbees) and Steve Kansa (Compuware)
* [Blue Ocean: A New User Experience for Jenkins](https://www.youtube.com/watch?v=mn61VFdScuk) by James Dumay

---

## Jenkins materjalid

---

### Statistika
Jenkinsi [kasutususstatistika](http://stats.jenkins.io/)

---

### Dokumentatsioon
Dokumentatsioon asub [siin](https://jenkins.io/doc/)

---

#### Getting started
Alustamise juhend on [siin](https://jenkins.io/doc/book/getting-started/)

---

#### Installimine
Kuidas installida leiab [siit](https://jenkins.io/doc/book/installing)

---

#### Konveier (pipeline)
Jenkinsi tööd [konveieritena](https://jenkins.io/doc/book/pipeline/)

---

#### Blue Ocean
Jenkinsi tööde visualiseerimine [Blue Ocean](https://jenkins.io/doc/book/blueocean/getting-started/)

---

## Näited ja näpunäited
* [Jenkins konveieri kasutusnäited](https://jenkins.io/doc/pipeline/examples/)
* [Näpunäited konveieri kasutamisel](https://www.cloudbees.com/blog/top-10-best-practices-jenkins-pipeline-plugin)
* [Gitlab CI baasil](https://docs.gitlab.com/ee/ci/examples/README.html)

---

## Ülesanne

Jenkinsi installimine, seadistamine ja ühe töö seadistamine

1. Jenkinsi installimine vastavalt [juhendile](https://jenkins.io/doc/book/installing).
2. Jenkinsi seadistamine vastavalt [slaididele](http://dijkstra.cs.ttu.ee/~gert/jenkins/).
3. Töö seadistamine analoogselt [slaididele](http://dijkstra.cs.ttu.ee/~gert/jenkins/).

