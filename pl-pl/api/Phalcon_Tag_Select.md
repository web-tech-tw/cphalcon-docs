---
layout: article
language: 'pl-pl'
version: '4.0'
title: 'Phalcon\Tag\Select'
---
# Abstract class **Phalcon\Tag\Select**

<a href="https://github.com/phalcon/cphalcon/tree/v4.0.0/phalcon/tag/select.zep" class="btn btn-default btn-sm">Source on GitHub</a>

Generates a SELECT html tag using a static array of values or a Phalcon\Mvc\Model resultset

## Metody

public static **selectField** (*array* $parameters, [*array* $data])

Generates a SELECT tag

private static **_optionsFromResultset** ([Phalcon\Mvc\Model\Resultset](Phalcon_Mvc_Model_Resultset) $resultset, *array* $using, *mixed* $value, *string* $closeOption)

Generate the OPTION tags based on a resultset

private static **_optionsFromArray** (*array* $data, *mixed* $value, *string* $closeOption)

Generate the OPTION tags based on an array