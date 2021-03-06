
## Style


### [Array bracket spacing](http://eslint.org/docs/rules/array-bracket-spacing)

> enforce spacing inside array brackets


:white_check_mark: Enabled (error)

<br />



### [Block spacing](http://eslint.org/docs/rules/block-spacing)

> enforce spacing inside single-line blocks


:white_check_mark: Enabled (error)

<br />



### [Brace style](http://eslint.org/docs/rules/brace-style)

> enforce one true brace style


:white_check_mark: Enabled (error)

<br />



### [Camelcase](http://eslint.org/docs/rules/camelcase)

> require camel case names


:white_check_mark: Enabled (error)

<br />



### [Comma spacing](http://eslint.org/docs/rules/comma-spacing)

> enforce spacing before and after comma


:white_check_mark: Enabled (error)

<br />



### [Comma style](http://eslint.org/docs/rules/comma-style)

> enforce one true comma style


:white_check_mark: Enabled (error)

<br />



### [Computed property spacing](http://eslint.org/docs/rules/computed-property-spacing)

> disallow padding inside computed properties


:white_check_mark: Enabled (error)

<br />



### [Consistent this](http://eslint.org/docs/rules/consistent-this)

> enforces consistent naming when capturing the current execution context


:white_check_mark: Enabled (error)

```javascript

// Bad
/*
const self = this;
*/
// Good
const _this = this;


```
<br />



### [Eol last](http://eslint.org/docs/rules/eol-last)

> enforce newline at the end of file, with no multiple empty lines


:white_check_mark: Enabled (error)

<br />



### [Func names](http://eslint.org/docs/rules/func-names)

> require function expressions to have a name


:x: Disabled

<br />



### [Func style](http://eslint.org/docs/rules/func-style)

> enforces use of function declarations or expressions


:x: Disabled

<br />



### [Id blacklist](http://eslint.org/docs/rules/id-blacklist)

> Blacklist certain identifiers to prevent them being used


:x: Disabled

```javascript

// Bad
/*
function _test(data) {}
*/

// Good
function _test(productData) {}

```
<br />



### [Id length](http://eslint.org/docs/rules/id-length)

> this option enforces minimum and maximum identifier lengths (variable names, property names etc.)


:x: Disabled

<br />



### [Id match](http://eslint.org/docs/rules/id-match)

> require identifiers to match the provided regular expression


:x: Disabled

<br />



### [Indent](http://eslint.org/docs/rules/indent)

> this option sets a specific tab width for your code


:white_check_mark: Enabled (warning)

<br />



### [Jsx quotes](http://eslint.org/docs/rules/jsx-quotes)

> specify whether double or single quotes should be used in JSX attributes


:white_check_mark: Enabled (error)

<br />



### [Key spacing](http://eslint.org/docs/rules/key-spacing)

> enforces spacing between keys and values in object literal properties


:white_check_mark: Enabled (error)

<br />



### [Keyword spacing](http://eslint.org/docs/rules/keyword-spacing)

> require a space before & after certain keywords


:white_check_mark: Enabled (error)

<br />



### [Linebreak style](http://eslint.org/docs/rules/linebreak-style)

> disallow mixed 'LF' and 'CRLF' as linebreaks


:x: Disabled

<br />



### [Lines around comment](http://eslint.org/docs/rules/lines-around-comment)

> enforces empty lines around comments


:x: Disabled

<br />



### [Max depth](http://eslint.org/docs/rules/max-depth)

> specify the maximum depth that blocks can be nested


:white_check_mark: Enabled (error)

<br />



### [Max len](http://eslint.org/docs/rules/max-len)

> specify the maximum length of a line in your program


:white_check_mark: Enabled (error)

<br />



### [Max nested callbacks](http://eslint.org/docs/rules/max-nested-callbacks)

> specify the maximum depth callbacks can be nested


:white_check_mark: Enabled (error)

<br />



### [Max params](http://eslint.org/docs/rules/max-params)

> limits the number of parameters that can be used in the function declaration.


:white_check_mark: Enabled (error)

<br />



### [Max statements per line](http://eslint.org/docs/rules/max-statements-per-line)

> restrict the number of statements per line


:white_check_mark: Enabled (error)

<br />



### [Max statements](http://eslint.org/docs/rules/max-statements)

> specify the maximum number of statement allowed in a function


:x: Disabled

<br />



### [New cap](http://eslint.org/docs/rules/new-cap)

> require a capital letter for constructors


:white_check_mark: Enabled (error)

<br />



### [New parens](http://eslint.org/docs/rules/new-parens)

> disallow the omission of parentheses when invoking a constructor with no arguments


:white_check_mark: Enabled (error)

<br />



### [Newline after var](http://eslint.org/docs/rules/newline-after-var)

> allow/disallow an empty newline after var statement


:x: Disabled

<br />



### [Newline before return](http://eslint.org/docs/rules/newline-before-return)

> require an empty line before return statements


:x: Disabled

<br />



### [Newline per chained call](http://eslint.org/docs/rules/newline-per-chained-call)

> enforces new line after each method call in the chain to make it more readable and easy to maintain


:white_check_mark: Enabled (error)

<br />



### [No array constructor](http://eslint.org/docs/rules/no-array-constructor)

> disallow use of the Array constructor


:white_check_mark: Enabled (error)

<br />



### [No bitwise](http://eslint.org/docs/rules/no-bitwise)

> disallow use of bitwise operators


:white_check_mark: Enabled (error)

<br />



### [No continue](http://eslint.org/docs/rules/no-continue)

> disallow use of the continue statement


:white_check_mark: Enabled (error)

<br />



### [No inline comments](http://eslint.org/docs/rules/no-inline-comments)

> disallow comments inline after code


:x: Disabled

```javascript

document.window.append('hello'); // inline comment

```
<br />



### [No lonely if](http://eslint.org/docs/rules/no-lonely-if)

> disallow if as the only statement in an else block


:white_check_mark: Enabled (error)

<br />



### [No mixed spaces and tabs](http://eslint.org/docs/rules/no-mixed-spaces-and-tabs)

> disallow mixed spaces and tabs for indentation


:white_check_mark: Enabled (error)

<br />



### [No multiple empty lines](http://eslint.org/docs/rules/no-multiple-empty-lines)

> disallow multiple empty lines and only one newline at the end


:white_check_mark: Enabled (error)

<br />



### [No negated condition](http://eslint.org/docs/rules/no-negated-condition)

> disallow negated conditions


:x: Disabled

<br />



### [No nested ternary](http://eslint.org/docs/rules/no-nested-ternary)

> disallow nested ternary expressions


:white_check_mark: Enabled (error)

<br />



### [No new object](http://eslint.org/docs/rules/no-new-object)

> disallow use of the Object constructor


:white_check_mark: Enabled (error)

<br />



### [No plusplus](http://eslint.org/docs/rules/no-plusplus)

> disallow use of unary operators, ++ and --


:x: Disabled

<br />



### [No restricted syntax](http://eslint.org/docs/rules/no-restricted-syntax)

> disallow certain syntax forms


 

<br />



### [No spaced func](http://eslint.org/docs/rules/no-spaced-func)

> disallow space between function identifier and application


:white_check_mark: Enabled (error)

<br />



### [No ternary](http://eslint.org/docs/rules/no-ternary)

> disallow the use of ternary operators


:x: Disabled

<br />



### [No trailing spaces](http://eslint.org/docs/rules/no-trailing-spaces)

> disallow trailing whitespace at the end of lines


:white_check_mark: Enabled (error)

<br />



### [No underscore dangle](http://eslint.org/docs/rules/no-underscore-dangle)

> allow dangling underscores in identifiers


:x: Disabled

<br />



### [No unneeded ternary](http://eslint.org/docs/rules/no-unneeded-ternary)

> disallow the use of Boolean literals in conditional expressions also, prefer `a || b` over `a ? a : b`


:white_check_mark: Enabled (error)

<br />



### [No whitespace before property](http://eslint.org/docs/rules/no-whitespace-before-property)

> disallow whitespace before properties


:white_check_mark: Enabled (error)

<br />



### [Object curly spacing](http://eslint.org/docs/rules/object-curly-spacing)

> require padding inside curly braces


:white_check_mark: Enabled (error)

<br />



### [Object property newline](http://eslint.org/docs/rules/object-property-newline)

> enforce "same line" or "multiple line" on object properties.


:x: Disabled

<br />



### [One var declaration per line](http://eslint.org/docs/rules/one-var-declaration-per-line)

> require a newline around variable declaration


:white_check_mark: Enabled (error)

```javascript

// Bad
/*
function bad() {
	const d = 1, e = 2;
}
*/

// Good
function good() {
	let a, b, c;
	const d = 1;
	const e = 2;
}

```
<br />



### [One var](http://eslint.org/docs/rules/one-var)

> allow just one var statement per function


:white_check_mark: Enabled (error)

```javascript

// Bad
/*
function bad() {
	const a = 1,
		b = 2,
		c = 3;
}
*/

// Good
function good() {
	const d = 4;
	const e = 5;
	const f = 6;
}


```
<br />



### [Operator assignment](http://eslint.org/docs/rules/operator-assignment)

> require assignment operator shorthand where possible or prohibit it entirely


:x: Disabled

<br />



### [Operator linebreak](http://eslint.org/docs/rules/operator-linebreak)

> enforce operators to be placed before or after line breaks


:x: Disabled

<br />



### [Padded blocks](http://eslint.org/docs/rules/padded-blocks)

> enforce padding within blocks


:x: Disabled

<br />



### [Quote props](http://eslint.org/docs/rules/quote-props)

> require quotes around object literal property names


:white_check_mark: Enabled (error)

<br />



### [Quotes](http://eslint.org/docs/rules/quotes)

> specify whether double or single quotes should be used


:white_check_mark: Enabled (error)

<br />



### [Require jsdoc](http://eslint.org/docs/rules/require-jsdoc)

> do not require jsdoc


:white_check_mark: Enabled (error)

```javascript

// BAD
/*
function test() {
	return 'test';
}
*/

// GOOD
/**
 * @returns {string} - something
 */
function test() {
	return 'test';
}

```
<br />



### [Semi spacing](http://eslint.org/docs/rules/semi-spacing)

> enforce spacing before and after semicolons


:white_check_mark: Enabled (error)

<br />



### [Semi](http://eslint.org/docs/rules/semi)

> require or disallow use of semicolons instead of ASI


:white_check_mark: Enabled (error)

<br />



### [Sort vars](http://eslint.org/docs/rules/sort-vars)

> sort variables within the same declaration block


:x: Disabled

<br />



### [Space before blocks](http://eslint.org/docs/rules/space-before-blocks)

> require or disallow space before blocks


:white_check_mark: Enabled (error)

```javascript

// Bad
/*
if (a){
	b();
}

function a(){}

for (;;) {
	b();
}

try {} catch (a){}

class Foo{
	constructor(){}
}
*/

// Good
if (a) {
	b();
}

function a() {}

for (;;) {
	b();
}

try {} catch (a) {}

class Foo {
	constructor() {}
}

```
<br />



### [Space before function paren](http://eslint.org/docs/rules/space-before-function-paren)

> require or disallow space before function opening parenthesis


:white_check_mark: Enabled (error)

```javascript

// Bad
/*
function foo () {
	// ...
}

var bar = function() {
	// ...
};

class Foo {
	constructor () {
		// ...
	}
}

var baz = {
	bar () {
		// ...
	}
};
*/

// Good
function foo() {
	// ...
}

var bar = function () {
	// ...
};

class Foo {
	constructor() {
		// ...
	}
}

var baz = {
	bar() {
		// ...
	},
};

```
<br />



### [Space in parens](http://eslint.org/docs/rules/space-in-parens)

> require or disallow spaces inside parentheses


:white_check_mark: Enabled (error)

```javascript

// Bad
/*
foo( 'bar' );
var x = ( 1 + 2 ) * 3;
*/

// Good
foo('bar');
var x = (1 + 2) * 3;

```
<br />



### [Space infix ops](http://eslint.org/docs/rules/space-infix-ops)

> require spaces around operators


:white_check_mark: Enabled (error)

```javascript

// Bad
/*
var sum = 1+2;
*/
var sum = 1 + 2;

```
<br />



### [Space unary ops](http://eslint.org/docs/rules/space-unary-ops)

> Require or disallow spaces before/after unary operators


:x: Disabled

<br />



### [Spaced comment](http://eslint.org/docs/rules/spaced-comment)

> require or disallow a space immediately following the // or /* in a comment


:white_check_mark: Enabled (error)

```javascript

// Bad
/*
//comment
///<reference path="../../../../node_modules/@types/react/index.d.ts" />
*/
// Good
// comment
/// <reference path="../../../../node_modules/@types/react/index.d.ts" />

```
<br />



### [Unicode bom](http://eslint.org/docs/rules/unicode-bom)

> require or disallow the Unicode Byte Order Mark


:x: Disabled

<br />



### [Wrap regex](http://eslint.org/docs/rules/wrap-regex)

> require regex literals to be wrapped in parentheses


:white_check_mark: Enabled (error)

```javascript

// Bad
/*
function a() {
	return /foo/.test('bar');
}
*/

// Good
function a() {
	return (/foo/).test('bar');
}

```
<br />


