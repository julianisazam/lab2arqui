# lab2arqui

[![CI/CD Pipeline](https://github.com/julianisazam/lab2arqui/actions/workflows/build.yml/badge.svg)](https://github.com/julianisazam/lab2arqui/actions/workflows/build.yml)
[![Quality Gate Status](https://sonarcloud.io/api/project_badges/measure?project=julianisazam_lab2arqui&metric=alert_status)](https://sonarcloud.io/summary/new_code?id=julianisazam_lab2arqui)
[![Bugs](https://sonarcloud.io/api/project_badges/measure?project=julianisazam_lab2arqui&metric=bugs)](https://sonarcloud.io/summary/new_code?id=julianisazam_lab2arqui)
[![Code Smells](https://sonarcloud.io/api/project_badges/measure?project=julianisazam_lab2arqui&metric=code_smells)](https://sonarcloud.io/summary/new_code?id=julianisazam_lab2arqui)
[![Coverage](https://sonarcloud.io/api/project_badges/measure?project=julianisazam_lab2arqui&metric=coverage)](https://sonarcloud.io/summary/new_code?id=julianisazam_lab2arqui)
[![Duplicated Lines (%)](https://sonarcloud.io/api/project_badges/measure?project=julianisazam_lab2arqui&metric=duplicated_lines_density)](https://sonarcloud.io/summary/new_code?id=julianisazam_lab2arqui)
[![Lines of Code](https://sonarcloud.io/api/project_badges/measure?project=julianisazam_lab2arqui&metric=ncloc)](https://sonarcloud.io/summary/new_code?id=julianisazam_lab2arqui)
[![Reliability Rating](https://sonarcloud.io/api/project_badges/measure?project=julianisazam_lab2arqui&metric=reliability_rating)](https://sonarcloud.io/summary/new_code?id=julianisazam_lab2arqui)
[![Security Rating](https://sonarcloud.io/api/project_badges/measure?project=julianisazam_lab2arqui&metric=security_rating)](https://sonarcloud.io/summary/new_code?id=julianisazam_lab2arqui)
[![Technical Debt](https://sonarcloud.io/api/project_badges/measure?project=julianisazam_lab2arqui&metric=sqale_index)](https://sonarcloud.io/summary/new_code?id=julianisazam_lab2arqui)
[![Maintainability Rating](https://sonarcloud.io/api/project_badges/measure?project=julianisazam_lab2arqui&metric=sqale_rating)](https://sonarcloud.io/summary/new_code?id=julianisazam_lab2arqui)
[![Vulnerabilities](https://sonarcloud.io/api/project_badges/measure?project=julianisazam_lab2arqui&metric=vulnerabilities)](https://sonarcloud.io/summary/new_code?id=julianisazam_lab2arqui)

Implementation of a Simple App with the next operations:

* Get random nations
* Get random currencies
* Get random airplanes
* Get application version
* health check
	
Including integration with GitHub Actions, Sonarqube (SonarCloud), Coveralls and Snyk
	
### Folders Structure
	
In the folder `src` is located the main code of the app
	
In the folder `test` is located the unit tests
	
### How to install it
	
Execute:
	
```shell
$ mvnw spring-boot:run
```
to download the node dependencies
	
### How to test it
	
Execute:
	
```shell
	$ mvnw clean install
```
	
### How to get coverage test
	
Execute:
	
```shell
$ mvwn -B package -DskipTests --file pom.xml
```
