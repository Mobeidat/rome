# `index.test.ts`

**DO NOT MODIFY**. This file has been autogenerated. Run `rome test packages/js-parser/index.test.ts --update-snapshots` to update.

## `typescript > class > expression-extends`

### `ast`

```javascript
JSRoot {
	comments: Array []
	corrupt: false
	diagnostics: Array []
	directives: Array []
	filename: "typescript/class/expression-extends/input.ts"
	hasHoistedVars: false
	interpreter: undefined
	mtime: undefined
	sourceType: "module"
	syntax: Array ["ts"]
	loc: Object {
		filename: "typescript/class/expression-extends/input.ts"
		end: Object {
			column: 0
			index: 56
			line: 3
		}
		start: Object {
			column: 0
			index: 0
			line: 1
		}
	}
	body: Array [
		JSExpressionStatement {
			loc: Object {
				filename: "typescript/class/expression-extends/input.ts"
				end: Object {
					column: 26
					index: 26
					line: 1
				}
				start: Object {
					column: 0
					index: 0
					line: 1
				}
			}
			expression: JSClassExpression {
				id: undefined
				loc: Object {
					filename: "typescript/class/expression-extends/input.ts"
					end: Object {
						column: 24
						index: 24
						line: 1
					}
					start: Object {
						column: 1
						index: 1
						line: 1
					}
				}
				meta: JSClassHead {
					body: Array []
					implements: undefined
					typeParameters: undefined
					loc: Object {
						filename: "typescript/class/expression-extends/input.ts"
						end: Object {
							column: 24
							index: 24
							line: 1
						}
						start: Object {
							column: 1
							index: 1
							line: 1
						}
					}
					superClass: JSCallExpression {
						arguments: Array []
						loc: Object {
							filename: "typescript/class/expression-extends/input.ts"
							end: Object {
								column: 18
								index: 18
								line: 1
							}
							start: Object {
								column: 15
								index: 15
								line: 1
							}
						}
						callee: JSReferenceIdentifier {
							name: "f"
							loc: Object {
								filename: "typescript/class/expression-extends/input.ts"
								identifierName: "f"
								end: Object {
									column: 16
									index: 16
									line: 1
								}
								start: Object {
									column: 15
									index: 15
									line: 1
								}
							}
						}
					}
					superTypeParameters: TSTypeParameterInstantiation {
						loc: Object {
							filename: "typescript/class/expression-extends/input.ts"
							end: Object {
								column: 21
								index: 21
								line: 1
							}
							start: Object {
								column: 18
								index: 18
								line: 1
							}
						}
						params: Array [
							TSTypeReference {
								typeParameters: undefined
								loc: Object {
									filename: "typescript/class/expression-extends/input.ts"
									end: Object {
										column: 20
										index: 20
										line: 1
									}
									start: Object {
										column: 19
										index: 19
										line: 1
									}
								}
								typeName: JSReferenceIdentifier {
									name: "T"
									loc: Object {
										filename: "typescript/class/expression-extends/input.ts"
										identifierName: "T"
										end: Object {
											column: 20
											index: 20
											line: 1
										}
										start: Object {
											column: 19
											index: 19
											line: 1
										}
									}
								}
							}
						]
					}
				}
			}
		}
		JSExpressionStatement {
			loc: Object {
				filename: "typescript/class/expression-extends/input.ts"
				end: Object {
					column: 28
					index: 55
					line: 2
				}
				start: Object {
					column: 0
					index: 27
					line: 2
				}
			}
			expression: JSClassExpression {
				id: JSBindingIdentifier {
					name: "C"
					loc: Object {
						filename: "typescript/class/expression-extends/input.ts"
						identifierName: "C"
						end: Object {
							column: 8
							index: 35
							line: 2
						}
						start: Object {
							column: 7
							index: 34
							line: 2
						}
					}
				}
				loc: Object {
					filename: "typescript/class/expression-extends/input.ts"
					end: Object {
						column: 26
						index: 53
						line: 2
					}
					start: Object {
						column: 1
						index: 28
						line: 2
					}
				}
				meta: JSClassHead {
					body: Array []
					implements: undefined
					typeParameters: undefined
					loc: Object {
						filename: "typescript/class/expression-extends/input.ts"
						end: Object {
							column: 26
							index: 53
							line: 2
						}
						start: Object {
							column: 1
							index: 28
							line: 2
						}
					}
					superClass: JSCallExpression {
						arguments: Array []
						loc: Object {
							filename: "typescript/class/expression-extends/input.ts"
							end: Object {
								column: 20
								index: 47
								line: 2
							}
							start: Object {
								column: 17
								index: 44
								line: 2
							}
						}
						callee: JSReferenceIdentifier {
							name: "f"
							loc: Object {
								filename: "typescript/class/expression-extends/input.ts"
								identifierName: "f"
								end: Object {
									column: 18
									index: 45
									line: 2
								}
								start: Object {
									column: 17
									index: 44
									line: 2
								}
							}
						}
					}
					superTypeParameters: TSTypeParameterInstantiation {
						loc: Object {
							filename: "typescript/class/expression-extends/input.ts"
							end: Object {
								column: 23
								index: 50
								line: 2
							}
							start: Object {
								column: 20
								index: 47
								line: 2
							}
						}
						params: Array [
							TSTypeReference {
								typeParameters: undefined
								loc: Object {
									filename: "typescript/class/expression-extends/input.ts"
									end: Object {
										column: 22
										index: 49
										line: 2
									}
									start: Object {
										column: 21
										index: 48
										line: 2
									}
								}
								typeName: JSReferenceIdentifier {
									name: "T"
									loc: Object {
										filename: "typescript/class/expression-extends/input.ts"
										identifierName: "T"
										end: Object {
											column: 22
											index: 49
											line: 2
										}
										start: Object {
											column: 21
											index: 48
											line: 2
										}
									}
								}
							}
						]
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