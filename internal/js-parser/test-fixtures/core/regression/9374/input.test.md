# `index.test.ts`

**DO NOT MODIFY**. This file has been autogenerated. Run `rome test internal/js-parser/index.test.ts --update-snapshots` to update.

## `core > regression > 9374`

### `ast`

```javascript
JSRoot {
	comments: Array []
	corrupt: false
	diagnostics: Array []
	directives: Array []
	filename: "core/regression/9374/input.js"
	hasHoistedVars: false
	interpreter: undefined
	mtime: undefined
	sourceType: "script"
	syntax: Array []
	loc: Object {
		filename: "core/regression/9374/input.js"
		end: Object {
			column: 0
			line: 4
		}
		start: Object {
			column: 0
			line: 1
		}
	}
	body: Array [
		JSFunctionDeclaration {
			id: JSBindingIdentifier {
				name: "test"
				loc: Object {
					filename: "core/regression/9374/input.js"
					identifierName: "test"
					end: Object {
						column: 14
						line: 1
					}
					start: Object {
						column: 10
						line: 1
					}
				}
			}
			loc: Object {
				filename: "core/regression/9374/input.js"
				end: Object {
					column: 1
					line: 3
				}
				start: Object {
					column: 0
					line: 1
				}
			}
			head: JSFunctionHead {
				async: false
				generator: true
				hasHoistedVars: false
				params: Array []
				rest: undefined
				returnType: undefined
				thisType: undefined
				typeParameters: undefined
				loc: Object {
					filename: "core/regression/9374/input.js"
					end: Object {
						column: 16
						line: 1
					}
					start: Object {
						column: 14
						line: 1
					}
				}
			}
			body: JSBlockStatement {
				directives: Array []
				loc: Object {
					filename: "core/regression/9374/input.js"
					end: Object {
						column: 1
						line: 3
					}
					start: Object {
						column: 17
						line: 1
					}
				}
				body: Array [
					JSExpressionStatement {
						loc: Object {
							filename: "core/regression/9374/input.js"
							end: Object {
								column: 18
								line: 2
							}
							start: Object {
								column: 2
								line: 2
							}
						}
						expression: JSYieldExpression {
							delegate: false
							loc: Object {
								filename: "core/regression/9374/input.js"
								end: Object {
									column: 17
									line: 2
								}
								start: Object {
									column: 2
									line: 2
								}
							}
							argument: JSNewExpression {
								arguments: Array []
								optional: undefined
								typeArguments: undefined
								loc: Object {
									filename: "core/regression/9374/input.js"
									end: Object {
										column: 17
										line: 2
									}
									start: Object {
										column: 8
										line: 2
									}
								}
								callee: JSReferenceIdentifier {
									name: "Foo"
									loc: Object {
										filename: "core/regression/9374/input.js"
										identifierName: "Foo"
										end: Object {
											column: 15
											line: 2
										}
										start: Object {
											column: 12
											line: 2
										}
									}
								}
							}
						}
					}
				]
			}
		}
	]
}
```

### `diagnostics`

```
✔ No known problems!

```
