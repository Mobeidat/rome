# `index.test.ts`

**DO NOT MODIFY**. This file has been autogenerated. Run `rome test internal/js-parser/index.test.ts --update-snapshots` to update.

## `es2017 > async-functions > await-async-function-declaration-name`

### `ast`

```javascript
JSRoot {
	comments: Array []
	corrupt: false
	diagnostics: Array []
	directives: Array []
	filename: "es2017/async-functions/await-async-function-declaration-name/input.js"
	hasHoistedVars: false
	interpreter: undefined
	mtime: undefined
	sourceType: "script"
	syntax: Array []
	loc: Object {
		filename: "es2017/async-functions/await-async-function-declaration-name/input.js"
		end: Object {
			column: 25
			line: 1
		}
		start: Object {
			column: 0
			line: 1
		}
	}
	body: Array [
		JSFunctionDeclaration {
			id: JSBindingIdentifier {
				name: "await"
				loc: Object {
					filename: "es2017/async-functions/await-async-function-declaration-name/input.js"
					identifierName: "await"
					end: Object {
						column: 20
						line: 1
					}
					start: Object {
						column: 15
						line: 1
					}
				}
			}
			loc: Object {
				filename: "es2017/async-functions/await-async-function-declaration-name/input.js"
				end: Object {
					column: 25
					line: 1
				}
				start: Object {
					column: 0
					line: 1
				}
			}
			body: JSBlockStatement {
				body: Array []
				directives: Array []
				loc: Object {
					filename: "es2017/async-functions/await-async-function-declaration-name/input.js"
					end: Object {
						column: 25
						line: 1
					}
					start: Object {
						column: 23
						line: 1
					}
				}
			}
			head: JSFunctionHead {
				async: true
				generator: false
				hasHoistedVars: false
				params: Array []
				rest: undefined
				returnType: undefined
				thisType: undefined
				typeParameters: undefined
				loc: Object {
					filename: "es2017/async-functions/await-async-function-declaration-name/input.js"
					end: Object {
						column: 22
						line: 1
					}
					start: Object {
						column: 20
						line: 1
					}
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
