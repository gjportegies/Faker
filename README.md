# Faker extension #

Magento 2 extension to generate fake data.

This extension uses `fzaninotto/faker`

Docs for this package can be found here: https://packagist.org/packages/fzaninotto/faker

Content is generated via the following console commands

## Generate Customer ##

`xigen:faker:customer [-w|--website WEBSITE] [-l|--limit [LIMIT]] [--] <generate>`

xigen:faker:customer generate

xigen:faker:customer -w 1 generate

xigen:faker:csutomer -w 1 -l 10 generate

## Generate Product ##

### todo: link configurable/group to simples ###

`xigen:faker:product [-w|--website WEBSITE] [-l|--limit [LIMIT]] [-t|--type [TYPE]] [--] <generate>`

xigen:faker:product generate

xigen:faker:product -w 1 generate

xigen:faker:product -w 1 -l 10 generate

xigen:faker:product -w 1 -l 10 -t simple generate

## Generate Category ##

`xigen:faker:category [-s|--store STORE] [-l|--limit [LIMIT]] [--] <generate>`

xigen:faker:category generate

xigen:faker:category -s 0 generate

xigen:faker:category -s 0 -l 10 generate

## Generate Order ##

`xigen:faker:order [-s|--store STORE] [-l|--limit [LIMIT]] [--] <generate>`

xigen:faker:order generate

xigen:faker:order -s 1 generate

xigen:faker:order -s 1 -l 1 generate
