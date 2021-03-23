# Reusable components/tools at MoJ

A place to publish reusable components/tools at MoJ.  Please add your
own in the appropriate section. If you don't see the appropriate
section, please create one.

## Django

### django-form-error-reporting
A form mixin that reports form errors as events to Google Analytics

[https://github.com/ministryofjustice/django-form-error-reporting](https://github.com/ministryofjustice/django-form-error-reporting)

### django-moj-irat
Tools to support adding a Django-based service to Ministry of Justice's Incidence Response and Tuning

[https://github.com/ministryofjustice/django-moj-irat](https://github.com/ministryofjustice/django-moj-irat)

### django-zendesk-tickets
Feedback form that submits to Zendesk

[https://github.com/ministryofjustice/django-zendesk-tickets](https://github.com/ministryofjustice/django-zendesk-tickets)

### django-govuk-template
Adds GOV.UK templates, css and other components from GDS's packages

[https://github.com/ministryofjustice/django-govuk-template](https://github.com/ministryofjustice/django-govuk-template)

### django-govuk-forms
Allows Django forms to be output with the correct HTML to be styled by GOV.UK css (e.g. from `django-govuk-template`) 

[https://github.com/ministryofjustice/django-govuk-forms](https://github.com/ministryofjustice/django-govuk-forms)

### django-gov
(DEPRECATED) Adds GovUK templates, css and other tools for Django based service

[https://github.com/ministryofjustice/django-gov](https://github.com/ministryofjustice/django-gov)

## Rails

### MoJ Rails 5 template (simple)

Use the [MoJ Rails 5 template](https://github.com/ministryofjustice/moj_rails_template) to commission a licensed Rails 5 project with 100% SimpleCov coverage, RSpec, mutation testing, brakeman, rubocop, optional documentary comment scrubbing, a CircleCI configuration, etc.

### GOV.UK elements stylesheets gem

Use the [GOV.UK elements gem](https://github.com/ministryofjustice/govuk_elements_rails) to pull GDS's [govuk_elements](http://github.com/alphagov/govuk_elements) stylesheets and javascript files into a Rails app.

### GOV.UK elements form builder gem

You can use [GOV.UK elements form builder](https://github.com/ministryofjustice/govuk_elements_form_builder) helper methods to develop GOV.UK elements styled form applications in Rails.

### Date field gem

Use the [date field Rails plugin](https://github.com/ministryofjustice/gov_uk_date_fields) to add GOV.UK standard three-box date fields to forms.

### GOV.UK Payment Gateway API client gem

Use the [GOV.UK Payment Gateway API client gem](https://github.com/ministryofjustice/govuk-pay-api-client) to simplify building apps that need to accept payments using the GOV.UK Payment Gateway.

### GLiMR API client gem

Use the [GLiMR API client gem](https://github.com/ministryofjustice/glimr-api-client) to simplify building apps that talk to the GLiMR case management system (in use in several UK tribunals).

## Python

### Bank holidays

Python package for loading bank holidays from GOV.UK: [ministryofjustice/govuk-bank-holidays](https://github.com/ministryofjustice/govuk-bank-holidays)

### Postcode service client

Python package providing an API client for Postcode Service [https://github.com/ministryofjustice/postcodeinfo-client-python](https://github.com/ministryofjustice/postcodeinfo-client-python)

### Register client

Python package for reading [Open Register](http://www.openregister.org/) data curated by GDS: [ministryofjustice/openregister-client](https://github.com/ministryofjustice/openregister-client)

## Ruby

### Postcode service client

Ruby gem providing an API client for Postcode Service [https://github.com/ministryofjustice/postcodeinfo-client-ruby](https://github.com/ministryofjustice/postcodeinfo-client-ruby)

### LAA Fee Calculator client

Ruby gem providing a client for the LAA Fee Calculator API. Use the [LAA fee calculator client gem](https://github.com/ministryofjustice/laa-fee-calculator-client), hosted on [Rubygems.org](https://rubygems.org/gems/laa-fee-calculator-client), to simplify calling the [LAA Fee Calculator API](https://github.com/ministryofjustice/laa-fee-calculator). The API provides calculation of legal aid fees for advocates and litigators in criminal cases.


### String Scrubber

Ruby gem that prevents `#to_json` calls on ASCII strings that have been incorrectly re-encoded from borking the calling application (mainly happens because of the UTF BOM-Byte Order Mark). [https://github.com/ministryofjustice/string_scrubber](https://github.com/ministryofjustice/string_scrubber)

## Generic front-end GOVUK resources

See the [Front-end Guide](front-end)

## Service

### Postcode lookup service

REST API for looking up a given UK Postcode and getting addresses, lat/long, and local authority info

Available from [https://github.com/ministryofjustice/postcodeinfo](https://github.com/ministryofjustice/postcodeinfo)

### Malware scanning service

A pair of docker containers, and a docker compose file, that provides a REST(ish) interface to a ClamAV malware scanner service

Available from [https://github.com/ministryofjustice/malware-scanner-service](https://github.com/ministryofjustice/malware-scanner-service)

### Mailcatcher container

Provides an instance of [mailcatcher](https://mailcatcher.me/), listening
for SMTP connections on port 1025 and UI connections on port 1080.

There is no authoritative mailcatcher container and existing containers
vary wildly in size and are frequently not kept up-to-date. This is a
very simple, small container that can be easily maintained within the
MoJ.

Available from
[https://github.com/ministryofjustice/mailcatcher](https://github.com/ministryofjustice/mailcatcher)
and
[https://hub.docker.com/r/ministryofjustice/mailcatcher/](https://hub.docker.com/r/ministryofjustice/mailcatcher/)

### SonarQube

SonarQube is a tool for continuous inspection of code quality. Using the free version (community edition) there are certain limitations such as PR decorations and branch specific analysis. [These scripts](https://github.com/ministryofjustice/laa-sonarqube-reusable-scripts) can help bridge the gap for such features.
