# HOF (Home Office Forms) [![Build Status](https://travis-ci.org/UKHomeOfficeForms/hof-bootstrap.svg?branch=master)](https://travis-ci.org/UKHomeOfficeForms/hof-bootstrap) [![npm version](https://badge.fury.io/js/hof.svg)](https://badge.fury.io/js/hof) [![Known Vulnerabilities](https://snyk.io/test/npm/hof/badge.svg)](https://snyk.io/test/npm/hof)

HOF (Home Office Forms) is a framework designed to assist developers in creating form-based workflows in a rapid, repeatable and secure way. It aims to reduce simple applications as much as possible to being configuration-only.

## Resources

### HOF documentation

[https://ukhomeofficeforms.github.io/hof-guide/](https://ukhomeofficeforms.github.io/hof-guide/)

### Built with HOF
 * https://github.com/UKHomeOffice/gro
 * https://github.com/UKHomeOffice/end-tenancy
 * [Firearms Licensing (Home Office)](https://github.com/UKHomeOffice/firearms)
 * [Contact UK Trade & Investment (UK Trade & Investment)](https://github.com/UKTradeInvestment/contact-ukti)
 * [Biometric Residence Permit (Home Office)](https://github.com/UKHomeOffice/brp_app)
 * [Report terrorist material (Home Office)](https://github.com/UKHomeOffice/rotm)
 * [UKVI Complaints (Home Office)](https://github.com/UKHomeOffice/Complaints)

### Development

* Does not work on Node 12, fine on Node 10.
* Run tests with `npm test`, you'll need to start redis first `docker-compose -f docker/redis.yml up`