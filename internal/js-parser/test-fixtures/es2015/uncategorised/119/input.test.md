# `index.test.ts`

**DO NOT MODIFY**. This file has been autogenerated. Run `rome test internal/js-parser/index.test.ts --update-snapshots` to update.

## `es2015 > uncategorised > 119`

### `ast`

```javascript
JSRoot {
	comments: Array []
	corrupt: false
	diagnostics: Array []
	directives: Array []
	filename: "es2015/uncategorised/119/input.js"
	hasHoistedVars: false
	interpreter: undefined
	mtime: undefined
	sourceType: "script"
	syntax: Array []
	loc: Object {
		filename: "es2015/uncategorised/119/input.js"
		end: Object {
			column: 20
			line: 1
		}
		start: Object {
			column: 0
			line: 1
		}
	}
	body: Array [
		JSClassDeclaration {
			id: JSBindingIdentifier {
				name: "A"
				loc: Object {
					filename: "es2015/uncategorised/119/input.js"
					identifierName: "A"
					end: Object {
						column: 7
						line: 1
					}
					start: Object {
						column: 6
						line: 1
					}
				}
			}
			loc: Object {
				filename: "es2015/uncategorised/119/input.js"
				end: Object {
					column: 20
					line: 1
				}
				start: Object {
					column: 0
					line: 1
				}
			}
			meta: JSClassHead {
				implements: undefined
				superClass: undefined
				superTypeParameters: undefined
				typeParameters: undefined
				loc: Object {
					filename: "es2015/uncategorised/119/input.js"
					end: Object {
						column: 20
						line: 1
					}
					start: Object {
						column: 0
						line: 1
					}
				}
				body: Array [
					JSClassMethod {
						kind: "method"
						key: JSStaticPropertyKey {
							value: JSIdentifier {
								name: "set"
								loc: Object {
									filename: "es2015/uncategorised/119/input.js"
									identifierName: "set"
									end: Object {
										column: 12
										line: 1
									}
									start: Object {
										column: 9
										line: 1
									}
								}
							}
							loc: Object {
								filename: "es2015/uncategorised/119/input.js"
								end: Object {
									column: 12
									line: 1
								}
								start: Object {
									column: 9
									line: 1
								}
							}
						}
						loc: Object {
							filename: "es2015/uncategorised/119/input.js"
							end: Object {
								column: 18
								line: 1
							}
							start: Object {
								column: 9
								line: 1
							}
						}
						body: JSBlockStatement {
							body: Array []
							directives: Array []
							loc: Object {
								filename: "es2015/uncategorised/119/input.js"
								end: Object {
									column: 18
									line: 1
								}
								start: Object {
									column: 16
									line: 1
								}
							}
						}
						meta: JSClassPropertyMeta {
							abstract: false
							accessibility: undefined
							optional: false
							readonly: false
							static: false
							typeAnnotation: undefined
							start: Object {
								column: 9
								line: 1
							}
							loc: Object {
								filename: "es2015/uncategorised/119/input.js"
								end: Object {
									column: 12
									line: 1
								}
								start: Object {
									column: 9
									line: 1
								}
							}
						}
						head: JSFunctionHead {
							async: false
							generator: false
							hasHoistedVars: false
							rest: undefined
							returnType: undefined
							thisType: undefined
							typeParameters: undefined
							loc: Object {
								filename: "es2015/uncategorised/119/input.js"
								end: Object {
									column: 15
									line: 1
								}
								start: Object {
									column: 12
									line: 1
								}
							}
							params: Array [
								JSBindingIdentifier {
									name: "v"
									loc: Object {
										filename: "es2015/uncategorised/119/input.js"
										identifierName: "v"
										end: Object {
											column: 14
											line: 1
										}
										start: Object {
											column: 13
											line: 1
										}
									}
									meta: JSPatternMeta {
										optional: undefined
										typeAnnotation: undefined
										loc: Object {
											filename: "es2015/uncategorised/119/input.js"
											end: Object {
												column: 14
												line: 1
											}
											start: Object {
												column: 13
												line: 1
											}
										}
									}
								}
							]
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
