# `index.test.ts`

**DO NOT MODIFY**. This file has been autogenerated. Run `rome test internal/js-parser/index.test.ts --update-snapshots` to update.

## `esprima > es2015-arrow-function > migrated_0001`

### `ast`

```javascript
JSRoot {
	comments: Array []
	corrupt: false
	diagnostics: Array []
	directives: Array []
	filename: "esprima/es2015-arrow-function/migrated_0001/input.js"
	hasHoistedVars: false
	interpreter: undefined
	mtime: undefined
	sourceType: "script"
	syntax: Array []
	loc: Object {
		filename: "esprima/es2015-arrow-function/migrated_0001/input.js"
		end: Object {
			column: 0
			line: 2
		}
		start: Object {
			column: 0
			line: 1
		}
	}
	body: Array [
		JSExpressionStatement {
			loc: Object {
				filename: "esprima/es2015-arrow-function/migrated_0001/input.js"
				end: Object {
					column: 11
					line: 1
				}
				start: Object {
					column: 0
					line: 1
				}
			}
			expression: JSArrowFunctionExpression {
				loc: Object {
					filename: "esprima/es2015-arrow-function/migrated_0001/input.js"
					end: Object {
						column: 11
						line: 1
					}
					start: Object {
						column: 0
						line: 1
					}
				}
				body: JSStringLiteral {
					value: "test"
					loc: Object {
						filename: "esprima/es2015-arrow-function/migrated_0001/input.js"
						end: Object {
							column: 11
							line: 1
						}
						start: Object {
							column: 5
							line: 1
						}
					}
				}
				head: JSFunctionHead {
					async: false
					hasHoistedVars: false
					rest: undefined
					thisType: undefined
					loc: Object {
						filename: "esprima/es2015-arrow-function/migrated_0001/input.js"
						end: Object {
							column: 4
							line: 1
						}
						start: Object {
							column: 0
							line: 1
						}
					}
					params: Array [
						JSBindingIdentifier {
							name: "e"
							loc: Object {
								filename: "esprima/es2015-arrow-function/migrated_0001/input.js"
								identifierName: "e"
								end: Object {
									column: 1
									line: 1
								}
								start: Object {
									column: 0
									line: 1
								}
							}
						}
					]
				}
			}
		}
	]
}
```

### `diagnostics`

```
✔ No known problems!

```
