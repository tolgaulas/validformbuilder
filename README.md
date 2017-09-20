[![Build Status](https://travis-ci.org/validformbuilder/validformbuilder.svg?branch=master)](https://travis-ci.org/validformbuilder/validformbuilder)
[![Latest Stable Version](https://poser.pugx.org/validformbuilder/validformbuilder/v/stable.svg)](https://packagist.org/packages/validformbuilder/validformbuilder)
[![License](https://poser.pugx.org/validformbuilder/validformbuilder/license.svg)](https://packagist.org/packages/validformbuilder/validformbuilder)
[![A project by Neverwoods](http://img.shields.io/badge/project_by-Neverwoods-blue.svg)](http://neverwoods.com)

Quick links:
------------

- [About](#validform-builder)
- [Installation](#installation)
- [Documentation](#user-content-documentation)
- [Examples](https://github.com/validformbuilder/validformbuilder/tree/master/examples)

ValidForm Builder
================

The ValidForm Builder is a PHP and JavaScript library that simplifies the often tedious creation of standards based web forms. Correct field validation of forms is an often overlooked problem and can lead to serious security issues. Building a form and adding validation to it was never that easy.

- The API generates XHTML Strict 1.0 compliant code.
- Field validation on the client side to minimize traffic overhead.
- Field validation on the server to enforce validation rules and prevent tempering with the form through SQL injection.
- Client side validation displays inline to improve user satisfaction. No more annoying popups that don't really tell you anything.
- Creation of complex form structures.
- Uses the popular jQuery Javascript library for DOM manipulation.
- **Completely customizable** using CSS rules.
- Automatic creation of field summaries for form mailers.
- Super fast web form creation.
- Get rid of SQL injection problems.
- Create standards based CSS forms. **No tables inside.**
- Make form entry fun for the user. More feedback from your website.
- **Write client- and server-side validation at the same time**

Installation
------------
You're free to download the source and [get started](https://github.com/neverwoods/validformbuilder/blob/master/docs/documentation.md#installing-validform-builder-in-your-project) but we highly recommend that you use [Composer](https://getcomposer.org/) to install ValidForm Builder. Add the following to your project's `composer.json` file:
```
{
    "require": {
        "validformbuilder/validformbuilder": "~4"
    }
}
```
By [using the tilde](https://getcomposer.org/doc/01-basic-usage.md#package-versions) you'll automatically install bug fixes and new features. See [Composer documentation](https://getcomposer.org/doc/01-basic-usage.md#package-versions) for details.


Documentation
=============
You can eat get going fast with the new extensive documentation generated by PHPDoc. We've proved lots of inline documentation together with example code to get you started fast an easy.

Here are some documentation quick links:

- [The Documentation (entry point)](http://validformbuilder.org/docs/namespaces/ValidFormBuilder.html)
- [Get started with the ValidForm object](http://validformbuilder.org/docs/classes/ValidFormBuilder.ValidForm.html)
- [Creating a checkbox / radio button list](http://validformbuilder.org/docs/classes/ValidFormBuilder.Group.html)
- [Four ways to create a `<select>` list](http://validformbuilder.org/docs/classes/ValidFormBuilder.Select.html)
- [Create a basic text field](http://validformbuilder.org/docs/classes/ValidFormBuilder.Text.html)
- Advanced - Getting started with [Conditions](http://validformbuilder.org/docs/classes/ValidFormBuilder.Condition.html) and [Comparisons](http://validformbuilder.org/docs/classes/ValidFormBuilder.Comparison.html)
- [Match two password fields client &amp; server-side](http://validformbuilder.org/docs/classes/ValidFormBuilder.Password.html)

If you have any questions, please ask them on [stackoverflow](http://stackoverflow.com) and be sure to tag your question with the `validform` tag. We regulary monitor these questions and try to answer them as soon as we can :)

Examples
========
Check out [the examples folder](https://github.com/validformbuilder/validformbuilder/tree/master/examples) for many real-live use cases for ValidForm Buider. Each snippet is ready to copy-paste into your project!


Happy coding!
------

Felix & Robin
