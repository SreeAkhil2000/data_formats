# YAML ain't markup language

Formats like XML, JSON and YAML are called serialization formats or languages. Why these are called that way?\
Because when the different microservices in the same in the app, uses different programming languages and if\
they wanted to send the files, then use one of the above popular formats. For the REST API's, they use the \
JSON format and the YAML files mainly they use for the config files. Basically we have libraries in every\
programming language for supporting these formats and also these formats are light weight and easier to read\
and write compared to other format like csv, excel sheets etc..

YAML follows the indentation. It supports key value pairs(:), Comments(#), Objects, list of Objects, list (-)\
Placeholders ({{}}) and also group multiple yaml components in one file (---)

Picture describing actual kubernetes config file from @TechWorld With Nana

![](yamlConfig.png)

It also supports multi line by using pipe (|) operator and also if they wanted to use single line then the\
operator used is greater than (>). The below diagram shows actual use case of that:

![Excecutes shell command and the multi line text is shell script](multiLineYAML.png)
