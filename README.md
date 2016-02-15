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

### GOV UK style gem

A gem wrapper around
[http://github.com/alphagov/govuk_elements](http://github.com/alphagov/govuk_elements)
that pulls stylesheet and javascript files into a Rails app.

https://github.com/ministryofjustice/govuk_elements_rails

### Date field gem

Rails plugin to allow GOV.UK standard three-box date fields

Available from [GitHub](https://github.com/ministryofjustice/gov_uk_date_fields)

## Python

### Postcode service client

Python package providing an API client for Postcode Service [https://github.com/ministryofjustice/postcodeinfo-client-python](https://github.com/ministryofjustice/postcodeinfo-client-python)

## Ruby

### Postcode service client

Ruby gem providing an API client for Postcode Service [https://github.com/ministryofjustice/postcodeinfo-client-ruby](https://github.com/ministryofjustice/postcodeinfo-client-ruby)

## Generic front-end GOVUK resources

### govuk_elements

https://github.com/alphagov/govuk_elements

Contains the "official" implementation of the [GOV.UK design elements](http://github.com/alphagov/govuk_elements). Maintained by GDS.

This repository is usable directly by copying its assets directly in your application.

The [prototype kit](https://github.com/alphagov/govuk_prototype_kit) allows creating quick node.js sites using the elements.

### MoJ elements

https://github.com/ministryofjustice/moj_template

This includes assets specific to MOJ services (headers and footers). It's available for Django, Rails, and more.

### mojular

[Mojular](https://github.com/mojular) is a rewrite of the GOV.UK elements and MoJ elements. It's well documented and can be integrated directly in Django, Rails, etc. but doesn't depend on the framework's asset pipeline (it's packaged as a node.js module). A major drawback is that because it doesn't incorporate govuk_elements, any changes made to it by GDS must be implemented in mojular. Getting-started instructions can be found at https://github.com/mojular/examples and documentation is at http://mojular.github.io/examples/


## Service

### Postcode lookup service

REST API for looking up a given UK Postcode and getting addresses, lat/long, and local authority info

Available from [https://github.com/ministryofjustice/postcodeinfo](https://github.com/ministryofjustice/postcodeinfo)
