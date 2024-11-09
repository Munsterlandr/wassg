# What this
Documentation to list all the calls, their subcalls, and what they do. Any subcall is listed below its parent call. Any that need a label will end with $, and any that need input with {}. Any call must still end with {}, so WASSG can properly parse it.

# Calls
## @wassg{}
All files must start with this. The data segment must contain the language version.

### @wassg$template{}
This label identifies the current file as a template, meaning it doesn't get copied to

## @text{}
Grouping of text. When labelless and the file isn't a template

## @pass{}
Makes the section not be used, at all.

## @template${}
Defines the page as a template with the given label as its name, ie the filepath to it in the source folder with the filetype extension removed.

