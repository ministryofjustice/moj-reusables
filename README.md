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

### Postcode service client

Python package providing an API client for Postcode Service [https://github.com/ministryofjustice/postcodeinfo-client-python](https://github.com/ministryofjustice/postcodeinfo-client-python)

## Ruby

### Postcode service client

Ruby gem providing an API client for Postcode Service [https://github.com/ministryofjustice/postcodeinfo-client-ruby](https://github.com/ministryofjustice/postcodeinfo-client-ruby)

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

