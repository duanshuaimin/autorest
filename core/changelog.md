# AutoRest Core 

## 4/2/2020
- rebuild to pick up latest data-store to fix the caching filename size

## 3/13/2020
- OAI2-to-OAI3 converter update in perks.

## 2/11/2020
- TransformerViaPointer was turning null into {} 

## 2/10/2020 
- rebuild to fix NPM publishing problem.
- remove additionalProperties: false so v2 generators don't choke.

## 1/30/2020
- rebuild to pick up perks change to fix multibyte utf8 over byte boundary problem

## 1/27/2020
- rebuild to pick up a perks change to support turning underscore in semver to dash on gh releases

## 1/13/2020
- rebuild to pick up newer extension library that supports python interpreter detection

## 12/18/2019
- force rebuild to pick up fix in oai2 converter

## 12/6/2019
- update the oai2-to-oai3 converter (parameterized host parameters should be client parameters if they are $ref'd)