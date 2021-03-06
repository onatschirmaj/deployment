## Deployment Release Notes

* ##### vm.m.p - 2021-MM-DD

  * Bump mariaDB version to 1:10.5.10
  * .dockerignore file added
  * yang2.amsl.com mailname replaced by yangcatalog.org

* ##### v3.2.1 - 2021-05-04

  * Crontab MAILTO variable set during Docker image build [#72](https://github.com/YangCatalog/deployment/issues/72)

* ##### v3.2.0 - 2021-04-15

  * Python base image bumped to version 3.9 in all affected modules [#66](https://github.com/YangCatalog/deployment/issues/66)
  * YumaPro validator updated to version 20.10-6 [#53](https://github.com/YangCatalog/deployment/issues/53)

* ##### 3.1.0 - 2021-03-18

  * Running Yangcatalog project using Kubernetes [#52](https://github.com/YangCatalog/deployment/issues/52)
  * xym tool update to version 0.5 deployment [#50](https://github.com/YangCatalog/deployment/issues/50)

* ##### v3.0.1 - 2021-02-26

  * Bump mariaDB version to 1:10.5.9
  * rsyslog and systemd added to all Dockerfiles [#48](https://github.com/YangCatalog/deployment/issues/48)

* ##### v3.0.0 - 2021-02-10

  * ConfD update [deployment #34](https://github.com/YangCatalog/deployment/issues/34)
  * Update pyang to version 2.4.0 [deployment #36]( https://github.com/YangCatalog/deployment/issues/36)
  * Bump mariaDB version
  * DOCUMENTATION guide updated
  * Add redis data to yangcatalog sample file
  * Add resdis service variable for docker-compose
  * Remove elasticsearch as a service (Elasticsearch is still used but from AWS!!!)
  * Update YumaPro version
  * Update docker-compose file
  * Various major/minor bug fixes and improvements

* ##### v2.0.0 - 2020-08-14

  * Add health check endpoint to nginx
  * Completely refactor and update yangcatalog config sample file
  * Update docker-compose file
  * Various major/minor bug fixes and improvements

* ##### v1.1.0 - 2020-07-16

  * Update docker-compose file
  * Add nginx conf files to shared volume
  * DOCUMENTATION guide updated
  * Pyang updated
  * Update nginx files
  * Add uwsgi timeout 5 mins for yangvalidator
  * Various major/minor bug fixes and improvements

* ##### v1.0.1 - 2020-07-03

  * Update docker-compose file
  * Add admin_ui submodule
  * Update yangcatalog config file
  * Various major/minor bug fixes and improvements

* ##### v1.0.0 - 2020-06-23

  * Initial submitted version
