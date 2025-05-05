# My VSCode Snippets

### PHP

```php
{
	// PHP Snippets
	"PHP Tags": {
		"prefix": "phptags",
		"body": [
			"<?php  ?>"
		]		
	},
	"PHP For Loop": {
		"prefix": "phpfor",
		"body": [
			"for (\\$i = ${1:0}; \\$i < ${2:10}; \\$i++) {",
			"    ${3:// Code}",
			"}"
		],
		"description": "Cria um loop for em PHP"
	},
	"PHP While Loop": {
		"prefix": "phpwhile",
		"body": [
			"while (${1:condition}) {",
			"    ${2:// Code}",
			"}"
		],
		"description": "Cria um loop while em PHP"
	},
	"PHP Do-While Loop": {
		"prefix": "phpdowhile",
		"body": [
			"do {",
			"    ${1:// Code}",
			"} while (${2:condition});"
		],
		"description": "Cria um loop do-while em PHP"
	},
	"PHP If Statement": {
		"prefix": "phpif",
		"body": [
			"if (${1:condition}) {",
			"    ${2:// Code}",
			"}"
		],
		"description": "Cria uma estrutura condicional if em PHP"
	},
	"PHP If-Else Statement": {
		"prefix": "phpifelse",
		"body": [
			"if (${1:condition}) {",
			"    ${2:// Code}",
			"} else {",
			"    ${3:// Code}",
			"}"
		],
		"description": "Cria uma estrutura condicional if-else em PHP"
	},
	"PHP If-ElseIf-Else Statement": {
		"prefix": "phpifelseif",
		"body": [
			"if (${1:condition}) {",
			"    ${2:// Code}",
			"} elseif (${3:condition}) {",
			"    ${4:// Code}",
			"} else {",
			"    ${5:// Code}",
			"}"
		],
		"description": "Cria uma estrutura condicional if-elseif-else em PHP"
	},
	"PHP Switch Statement": {
		"prefix": "phpswitch",
		"body": [
			"switch (\\$${1:variable}) {",
			"    case ${2:value1}:",
			"        ${3:// Code}",
			"        break;",
			"    case ${4:value2}:",
			"        ${5:// Code}",
			"        break;",
			"    default:",
			"        ${6:// Code}",
			"}"
		],
		"description": "Cria uma estrutura switch em PHP"
	},
	"PHP Foreach Loop": {
		"prefix": "phpforeach",
		"body": [
			"foreach (\\$${1:array} as \\$${2:value}) {",
			"    ${3:// Code}",
			"}"
		],
		"description": "Cria um loop foreach em PHP"
	},
	"PHP Foreach with Key": {
		"prefix": "phpforeachkey",
		"body": [
			"foreach (\\$${1:array} as \\$${2:key} => \\$${3:value}) {",
			"    ${4:// Code}",
			"}"
		],
		"description": "Cria um loop foreach com chave e valor em PHP"
	},
	"PHP Function": {
		"prefix": "phpfunction",
		"body": [
			"function ${1:functionName}(${2:parameters}) {",
			"    ${3:// Code}",
			"}"
		],
		"description": "Cria uma função em PHP"
	},
	"PHP Anonymous Function": {
		"prefix": "phpanonfunc",
		"body": [
			"\\$ ${1:functionName} = function(${2:parameters}) {",
			"    ${3:// Code}",
			"};"
		],
		"description": "Cria uma função anônima em PHP"
	},
	"PHP Array": {
		"prefix": "phparray",
		"body": [
			"\\$${1:arrayName} = [",
			"    ${2:'key' => 'value'},",
			"    ${3:'key' => 'value'}",
			"];"
		],
		"description": "Cria um array em PHP"
	},
	"PHP Try-Catch": {
		"prefix": "phptrycatch",
		"body": [
			"try {",
			"    ${1:// Code}",
			"} catch (Exception \\$e) {",
			"    ${2:// Handle exception}",
			"}"
		],
		"description": "Cria uma estrutura try-catch em PHP"
	},
	"PHP Class": {
		"prefix": "phpclass",
		"body": [
			"class ${1:ClassName} {",
			"    ${2:// Properties and methods}",
			"}"
		],
		"description": "Cria uma classe em PHP"
	},
	"PHP Method": {
		"prefix": "phpmethod",
		"body": [
			"public function ${1:methodName}(${2:parameters}) {",
			"    ${3:// Code}",
			"}"
		],
		"description": "Cria um método público em PHP"
	}
}
```
