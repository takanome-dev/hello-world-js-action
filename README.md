# Hello World JavaScript Action

This action print "Hello World" or "Hello" + the name of the person to greet to the logs.

## Inputs

## `who-to-greet`

**Required** the name of the person to greet. Default `"World"`.

## Outputs

## `time`

The time we greeted you.

## Example of usage

```yml
uses: actions/hello-world-js-action@v1.1
with:
  who-to-greet: 'Takanome the Open Source Guy'
```
