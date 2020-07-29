# `index.test.ts`

**DO NOT MODIFY**. This file has been autogenerated. Run `rome test packages/js-parser/index.test.ts --update-snapshots` to update.

## `typescript > types > type-operator`

### `ast`

```javascript
JSRoot {
	comments: Array []
	corrupt: false
	diagnostics: Array []
	directives: Array []
	filename: "typescript/types/type-operator/input.ts"
	hasHoistedVars: false
	interpreter: undefined
	mtime: undefined
	sourceType: "module"
	syntax: Array ["ts"]
	loc: Object {
		filename: "typescript/types/type-operator/input.ts"
		end: Object {
			column: 0
			index: 99
			line: 5
		}
		start: Object {
			column: 0
			index: 0
			line: 1
		}
	}
	body: Array [
		JSVariableDeclarationStatement {
			loc: Object {
				filename: "typescript/types/type-operator/input.ts"
				end: Object {
					column: 15
					index: 15
					line: 1
				}
				start: Object {
					column: 0
					index: 0
					line: 1
				}
			}
			declaration: JSVariableDeclaration {
				kind: "let"
				loc: Object {
					filename: "typescript/types/type-operator/input.ts"
					end: Object {
						column: 15
						index: 15
						line: 1
					}
					start: Object {
						column: 0
						index: 0
						line: 1
					}
				}
				declarations: Array [
					JSVariableDeclarator {
						id: JSBindingIdentifier {
							name: "x"
							loc: Object {
								filename: "typescript/types/type-operator/input.ts"
								end: Object {
									column: 14
									index: 14
									line: 1
								}
								start: Object {
									column: 4
									index: 4
									line: 1
								}
							}
							meta: JSPatternMeta {
								definite: undefined
								loc: Object {
									filename: "typescript/types/type-operator/input.ts"
									end: Object {
										column: 14
										index: 14
										line: 1
									}
									start: Object {
										column: 4
										index: 4
										line: 1
									}
								}
								typeAnnotation: TSTypeOperator {
									operator: "keyof"
									loc: Object {
										filename: "typescript/types/type-operator/input.ts"
										end: Object {
											column: 14
											index: 14
											line: 1
										}
										start: Object {
											column: 7
											index: 7
											line: 1
										}
									}
									typeAnnotation: TSTypeReference {
										typeParameters: undefined
										loc: Object {
											filename: "typescript/types/type-operator/input.ts"
											end: Object {
												column: 14
												index: 14
												line: 1
											}
											start: Object {
												column: 13
												index: 13
												line: 1
											}
										}
										typeName: JSReferenceIdentifier {
											name: "T"
											loc: Object {
												filename: "typescript/types/type-operator/input.ts"
												identifierName: "T"
												end: Object {
													column: 14
													index: 14
													line: 1
												}
												start: Object {
													column: 13
													index: 13
													line: 1
												}
											}
										}
									}
								}
							}
						}
						init: undefined
						loc: Object {
							filename: "typescript/types/type-operator/input.ts"
							end: Object {
								column: 14
								index: 14
								line: 1
							}
							start: Object {
								column: 4
								index: 4
								line: 1
							}
						}
					}
				]
			}
		}
		JSVariableDeclarationStatement {
			loc: Object {
				filename: "typescript/types/type-operator/input.ts"
				end: Object {
					column: 21
					index: 37
					line: 2
				}
				start: Object {
					column: 0
					index: 16
					line: 2
				}
			}
			declaration: JSVariableDeclaration {
				kind: "let"
				loc: Object {
					filename: "typescript/types/type-operator/input.ts"
					end: Object {
						column: 21
						index: 37
						line: 2
					}
					start: Object {
						column: 0
						index: 16
						line: 2
					}
				}
				declarations: Array [
					JSVariableDeclarator {
						id: JSBindingIdentifier {
							name: "y"
							loc: Object {
								filename: "typescript/types/type-operator/input.ts"
								end: Object {
									column: 20
									index: 36
									line: 2
								}
								start: Object {
									column: 4
									index: 20
									line: 2
								}
							}
							meta: JSPatternMeta {
								definite: undefined
								loc: Object {
									filename: "typescript/types/type-operator/input.ts"
									end: Object {
										column: 20
										index: 36
										line: 2
									}
									start: Object {
										column: 4
										index: 20
										line: 2
									}
								}
								typeAnnotation: TSTypeOperator {
									operator: "unique"
									loc: Object {
										filename: "typescript/types/type-operator/input.ts"
										end: Object {
											column: 20
											index: 36
											line: 2
										}
										start: Object {
											column: 7
											index: 23
											line: 2
										}
									}
									typeAnnotation: TSSymbolKeywordTypeAnnotation {
										loc: Object {
											filename: "typescript/types/type-operator/input.ts"
											end: Object {
												column: 20
												index: 36
												line: 2
											}
											start: Object {
												column: 14
												index: 30
												line: 2
											}
										}
									}
								}
							}
						}
						init: undefined
						loc: Object {
							filename: "typescript/types/type-operator/input.ts"
							end: Object {
								column: 20
								index: 36
								line: 2
							}
							start: Object {
								column: 4
								index: 20
								line: 2
							}
						}
					}
				]
			}
		}
		JSVariableDeclarationStatement {
			loc: Object {
				filename: "typescript/types/type-operator/input.ts"
				end: Object {
					column: 25
					index: 63
					line: 3
				}
				start: Object {
					column: 0
					index: 38
					line: 3
				}
			}
			declaration: JSVariableDeclaration {
				kind: "let"
				loc: Object {
					filename: "typescript/types/type-operator/input.ts"
					end: Object {
						column: 25
						index: 63
						line: 3
					}
					start: Object {
						column: 0
						index: 38
						line: 3
					}
				}
				declarations: Array [
					JSVariableDeclarator {
						id: JSBindingIdentifier {
							name: "z"
							loc: Object {
								filename: "typescript/types/type-operator/input.ts"
								end: Object {
									column: 24
									index: 62
									line: 3
								}
								start: Object {
									column: 4
									index: 42
									line: 3
								}
							}
							meta: JSPatternMeta {
								definite: undefined
								loc: Object {
									filename: "typescript/types/type-operator/input.ts"
									end: Object {
										column: 24
										index: 62
										line: 3
									}
									start: Object {
										column: 4
										index: 42
										line: 3
									}
								}
								typeAnnotation: TSTypeOperator {
									operator: "readonly"
									loc: Object {
										filename: "typescript/types/type-operator/input.ts"
										end: Object {
											column: 24
											index: 62
											line: 3
										}
										start: Object {
											column: 7
											index: 45
											line: 3
										}
									}
									typeAnnotation: TSArrayType {
										loc: Object {
											filename: "typescript/types/type-operator/input.ts"
											end: Object {
												column: 24
												index: 62
												line: 3
											}
											start: Object {
												column: 16
												index: 54
												line: 3
											}
										}
										elementType: TSNumberKeywordTypeAnnotation {
											loc: Object {
												filename: "typescript/types/type-operator/input.ts"
												end: Object {
													column: 22
													index: 60
													line: 3
												}
												start: Object {
													column: 16
													index: 54
													line: 3
												}
											}
										}
									}
								}
							}
						}
						init: undefined
						loc: Object {
							filename: "typescript/types/type-operator/input.ts"
							end: Object {
								column: 24
								index: 62
								line: 3
							}
							start: Object {
								column: 4
								index: 42
								line: 3
							}
						}
					}
				]
			}
		}
		JSVariableDeclarationStatement {
			loc: Object {
				filename: "typescript/types/type-operator/input.ts"
				end: Object {
					column: 34
					index: 98
					line: 4
				}
				start: Object {
					column: 0
					index: 64
					line: 4
				}
			}
			declaration: JSVariableDeclaration {
				kind: "let"
				loc: Object {
					filename: "typescript/types/type-operator/input.ts"
					end: Object {
						column: 34
						index: 98
						line: 4
					}
					start: Object {
						column: 0
						index: 64
						line: 4
					}
				}
				declarations: Array [
					JSVariableDeclarator {
						id: JSBindingIdentifier {
							name: "z1"
							loc: Object {
								filename: "typescript/types/type-operator/input.ts"
								end: Object {
									column: 33
									index: 97
									line: 4
								}
								start: Object {
									column: 4
									index: 68
									line: 4
								}
							}
							meta: JSPatternMeta {
								definite: undefined
								loc: Object {
									filename: "typescript/types/type-operator/input.ts"
									end: Object {
										column: 33
										index: 97
										line: 4
									}
									start: Object {
										column: 4
										index: 68
										line: 4
									}
								}
								typeAnnotation: TSTypeOperator {
									operator: "readonly"
									loc: Object {
										filename: "typescript/types/type-operator/input.ts"
										end: Object {
											column: 33
											index: 97
											line: 4
										}
										start: Object {
											column: 8
											index: 72
											line: 4
										}
									}
									typeAnnotation: TSTupleType {
										rest: undefined
										loc: Object {
											filename: "typescript/types/type-operator/input.ts"
											end: Object {
												column: 33
												index: 97
												line: 4
											}
											start: Object {
												column: 17
												index: 81
												line: 4
											}
										}
										elementTypes: Array [
											TSTupleElement {
												name: undefined
												optional: false
												loc: Object {
													filename: "typescript/types/type-operator/input.ts"
													end: Object {
														column: 24
														index: 88
														line: 4
													}
													start: Object {
														column: 18
														index: 82
														line: 4
													}
												}
												typeAnnotation: TSNumberKeywordTypeAnnotation {
													loc: Object {
														filename: "typescript/types/type-operator/input.ts"
														end: Object {
															column: 24
															index: 88
															line: 4
														}
														start: Object {
															column: 18
															index: 82
															line: 4
														}
													}
												}
											}
											TSTupleElement {
												name: undefined
												optional: false
												loc: Object {
													filename: "typescript/types/type-operator/input.ts"
													end: Object {
														column: 32
														index: 96
														line: 4
													}
													start: Object {
														column: 26
														index: 90
														line: 4
													}
												}
												typeAnnotation: TSNumberKeywordTypeAnnotation {
													loc: Object {
														filename: "typescript/types/type-operator/input.ts"
														end: Object {
															column: 32
															index: 96
															line: 4
														}
														start: Object {
															column: 26
															index: 90
															line: 4
														}
													}
												}
											}
										]
									}
								}
							}
						}
						init: undefined
						loc: Object {
							filename: "typescript/types/type-operator/input.ts"
							end: Object {
								column: 33
								index: 97
								line: 4
							}
							start: Object {
								column: 4
								index: 68
								line: 4
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