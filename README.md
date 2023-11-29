mie-edi-challenge: A Challenge for new EDI hires
=====

This is a challenge to gauge your expertise with a number of technologies routinely used at MIE and Enterprise Health by the EDI / Interoperability side of the business.

Please set up a linux MariaDB instance either by using [Docker](https://hub.docker.com/_/mariadb) or by using [Vagrant](https://mariadb.com/kb/en/vagrant-overview-for-mariadb-users/).
After MariaDB is set up, visit [https://www.healthdata.gov/](https://www.healthdata.gov/)  and download the [COVID-19 Reported Patient Impact and Hospital Capacity by State TimeSeries](https://healthdata.gov/Hospital/COVID-19-Reported-Patient-Impact-and-Hospital-Capa/g62h-syeh) and [COVID-19 Reported Patient Impact and Hospital Capacity by Facility](https://healthdata.gov/Hospital/COVID-19-Reported-Patient-Impact-and-Hospital-Capa/anag-cw7u), then import it into MariaDB / MySQL.  Then, run SQL queries to analyze the data.  Keep notes during your analysis process and the steps you took to create correlations between the data. Afterward, please reach out to Valerie [vmckain@mieweb.com](mailto:vmckain@mieweb.com) to let her know you’re ready, and we will do a WebEx to discuss how you accomplished the task (steps you took), insights about the data, and issues.

You may also consider [another](https://www.healthdata.gov/browse?tags=hhs+covid-19) [data](https://guides.lib.berkeley.edu/publichealth/healthstatistics/rawdata) [set](https://www.baseball-reference.com/leagues/NL/bat.shtml) if there is something else that fascinates you.

Note: While I would love to see a linux / MariaDB instance to gauge your ability to operate in that environment and ability to set up docker or vagrant, I particularly want to see your analysis and DB query skills. If the linux/DB/vagrant tasks present an insurmountable challenge to this task, please just load the data in the DB of your choice and perform the analysis without using linux / Docker / Vagrant / etc. Note though – Linux is an integral piece of our application stack, and your familiarity with it is going to weigh heavily in our assessment, although not as heavily as your DB skills.


Completing your challenge
=====

Since this is a git template repository, it isn't possible to fork it, so you will need to "Use template" and clone it to your local development environment. Then create a private github repository of your own and change it to be upstream of your local copy. Upload any SQL that you have to correlate data sets. Once you are ready for us to see your code, add these users as collaborators to your project:

* https://github.com/tslabach
* https://github.com/lpeckham1
* https://github.com/dcornewell
* https://github.com/ariserac
* https://github.com/horner

At at that point, please reach back out to your recruiter at MIE / Enterprise Health to reschedule a technical interview and code review.
