# dBug

This is my fork of ospinto's dBug class.
Original here: https://github.com/ospinto/dBug

## Install

	composer require chillem/dbug

## How to use

    new dBug($myVariable);

More examples at http://dbug.ospinto.com/examples.php

## Features

PHP version of ColdFusion’s cfdump.

Outputs colored and structured tabular variable information.

Variable types supported are: Arrays, Classes/Objects, Database and XML Resources.

Ability to force certain types of output. Example: You can force an
object variable to be outputted as an array type variable.

Stylesheet can be easily edited.

Table cells can be expanded and collapsed.

It’s FREE!!!

## Changelog

**1.2.2**
Use modern constructor

**1.2.1** 
Move dBug.php to src/ directory to comply with PSR4 autoloading standards
Create dBug/ namespace