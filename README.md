# ES6 Notes and features

Notes about ES6 features, based on Wes Bos ES6 course. 

## Variables

#### var
* function scoped, can leak out
* can be redefined (not good!)
* allows references even if not assinged yet
#### let 
* block scoped
#### const
* block scoped
* immutable
#### switch variables
[first, second] = [second, first]
### debugger
debugger; -> program stops and opens devtools. 

## Array functions

See [ext1.html](https://github.com/devgranlund/javascript-es6/blob/master/ext1.html) and [ext2.html](https://github.com/devgranlund/javascript-es6/blob/master/ext2.html) for reference.

## Strings

### String templates

See [template_strings.html](https://github.com/devgranlund/javascript-es6/blob/master/template_strings.html).

This is good technique also for sanitizing user input. 

### New methods
.startsWith()

.endsWith()

.includes()

.repeat()

## Deconstructing

### Deconstructing objects

See [deconstructing_objects.html](https://github.com/devgranlund/javascript-es6/blob/master/deconstructing_objects.html).

The same thing works for arrays too. Just replace {} with [].