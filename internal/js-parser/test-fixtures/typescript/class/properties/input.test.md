# `index.test.ts`

**DO NOT MODIFY**. This file has been autogenerated. Run `rome test internal/js-parser/index.test.ts --update-snapshots` to update.

## `typescript > class > properties`

### `ast`

```javascript
JSRoot {
	comments: Array []
	corrupt: false
	diagnostics: Array []
	directives: Array []
	filename: "typescript/class/properties/input.ts"
	hasHoistedVars: false
	interpreter: undefined
	mtime: undefined
	sourceType: "module"
	syntax: Array ["ts"]
	loc: Object {
		filename: "typescript/class/properties/input.ts"
		end: Object {
			column: 0
			line: 9
		}
		start: Object {
			column: 0
			line: 1
		}
	}
	body: Array [
		JSClassDeclaration {
			id: JSBindingIdentifier {
				name: "C"
				loc: Object {
					filename: "typescript/class/properties/input.ts"
					identifierName: "C"
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
				filename: "typescript/class/properties/input.ts"
				end: Object {
					column: 1
					line: 8
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
					filename: "typescript/class/properties/input.ts"
					end: Object {
						column: 1
						line: 8
					}
					start: Object {
						column: 0
						line: 1
					}
				}
				body: Array [
					JSClassProperty {
						key: JSStaticPropertyKey {
							value: JSIdentifier {
								name: "x"
								loc: Object {
									filename: "typescript/class/properties/input.ts"
									identifierName: "x"
									end: Object {
										column: 5
										line: 2
									}
									start: Object {
										column: 4
										line: 2
									}
								}
							}
							loc: Object {
								filename: "typescript/class/properties/input.ts"
								end: Object {
									column: 5
									line: 2
								}
								start: Object {
									column: 4
									line: 2
								}
							}
						}
						value: undefined
						definite: undefined
						typeAnnotation: undefined
						loc: Object {
							filename: "typescript/class/properties/input.ts"
							end: Object {
								column: 6
								line: 2
							}
							start: Object {
								column: 4
								line: 2
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
								column: 4
								line: 2
							}
							loc: Object {
								filename: "typescript/class/properties/input.ts"
								end: Object {
									column: 5
									line: 2
								}
								start: Object {
									column: 4
									line: 2
								}
							}
						}
					}
					JSClassProperty {
						key: JSStaticPropertyKey {
							value: JSIdentifier {
								name: "x"
								loc: Object {
									filename: "typescript/class/properties/input.ts"
									identifierName: "x"
									end: Object {
										column: 5
										line: 3
									}
									start: Object {
										column: 4
										line: 3
									}
								}
							}
							loc: Object {
								filename: "typescript/class/properties/input.ts"
								end: Object {
									column: 5
									line: 3
								}
								start: Object {
									column: 4
									line: 3
								}
							}
						}
						value: undefined
						definite: undefined
						typeAnnotation: undefined
						loc: Object {
							filename: "typescript/class/properties/input.ts"
							end: Object {
								column: 7
								line: 3
							}
							start: Object {
								column: 4
								line: 3
							}
						}
						meta: JSClassPropertyMeta {
							abstract: false
							accessibility: undefined
							optional: true
							readonly: false
							static: false
							typeAnnotation: undefined
							start: Object {
								column: 4
								line: 3
							}
							loc: Object {
								filename: "typescript/class/properties/input.ts"
								end: Object {
									column: 6
									line: 3
								}
								start: Object {
									column: 4
									line: 3
								}
							}
						}
					}
					JSClassProperty {
						key: JSStaticPropertyKey {
							value: JSIdentifier {
								name: "x"
								loc: Object {
									filename: "typescript/class/properties/input.ts"
									identifierName: "x"
									end: Object {
										column: 5
										line: 4
									}
									start: Object {
										column: 4
										line: 4
									}
								}
							}
							loc: Object {
								filename: "typescript/class/properties/input.ts"
								end: Object {
									column: 5
									line: 4
								}
								start: Object {
									column: 4
									line: 4
								}
							}
						}
						value: undefined
						definite: undefined
						loc: Object {
							filename: "typescript/class/properties/input.ts"
							end: Object {
								column: 14
								line: 4
							}
							start: Object {
								column: 4
								line: 4
							}
						}
						typeAnnotation: TSNumberKeywordTypeAnnotation {
							loc: Object {
								filename: "typescript/class/properties/input.ts"
								end: Object {
									column: 13
									line: 4
								}
								start: Object {
									column: 7
									line: 4
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
								column: 4
								line: 4
							}
							loc: Object {
								filename: "typescript/class/properties/input.ts"
								end: Object {
									column: 5
									line: 4
								}
								start: Object {
									column: 4
									line: 4
								}
							}
						}
					}
					JSClassProperty {
						key: JSStaticPropertyKey {
							value: JSIdentifier {
								name: "x"
								loc: Object {
									filename: "typescript/class/properties/input.ts"
									identifierName: "x"
									end: Object {
										column: 5
										line: 5
									}
									start: Object {
										column: 4
										line: 5
									}
								}
							}
							loc: Object {
								filename: "typescript/class/properties/input.ts"
								end: Object {
									column: 5
									line: 5
								}
								start: Object {
									column: 4
									line: 5
								}
							}
						}
						value: JSNumericLiteral {
							value: 1
							format: undefined
							loc: Object {
								filename: "typescript/class/properties/input.ts"
								end: Object {
									column: 17
									line: 5
								}
								start: Object {
									column: 16
									line: 5
								}
							}
						}
						definite: undefined
						loc: Object {
							filename: "typescript/class/properties/input.ts"
							end: Object {
								column: 18
								line: 5
							}
							start: Object {
								column: 4
								line: 5
							}
						}
						typeAnnotation: TSNumberKeywordTypeAnnotation {
							loc: Object {
								filename: "typescript/class/properties/input.ts"
								end: Object {
									column: 13
									line: 5
								}
								start: Object {
									column: 7
									line: 5
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
								column: 4
								line: 5
							}
							loc: Object {
								filename: "typescript/class/properties/input.ts"
								end: Object {
									column: 5
									line: 5
								}
								start: Object {
									column: 4
									line: 5
								}
							}
						}
					}
					JSClassProperty {
						key: JSStaticPropertyKey {
							value: JSIdentifier {
								name: "x"
								loc: Object {
									filename: "typescript/class/properties/input.ts"
									identifierName: "x"
									end: Object {
										column: 5
										line: 6
									}
									start: Object {
										column: 4
										line: 6
									}
								}
							}
							loc: Object {
								filename: "typescript/class/properties/input.ts"
								end: Object {
									column: 5
									line: 6
								}
								start: Object {
									column: 4
									line: 6
								}
							}
						}
						value: undefined
						definite: true
						typeAnnotation: undefined
						loc: Object {
							filename: "typescript/class/properties/input.ts"
							end: Object {
								column: 7
								line: 6
							}
							start: Object {
								column: 4
								line: 6
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
								column: 4
								line: 6
							}
							loc: Object {
								filename: "typescript/class/properties/input.ts"
								end: Object {
									column: 5
									line: 6
								}
								start: Object {
									column: 4
									line: 6
								}
							}
						}
					}
					JSClassProperty {
						key: JSStaticPropertyKey {
							value: JSIdentifier {
								name: "x"
								loc: Object {
									filename: "typescript/class/properties/input.ts"
									identifierName: "x"
									end: Object {
										column: 5
										line: 7
									}
									start: Object {
										column: 4
										line: 7
									}
								}
							}
							loc: Object {
								filename: "typescript/class/properties/input.ts"
								end: Object {
									column: 5
									line: 7
								}
								start: Object {
									column: 4
									line: 7
								}
							}
						}
						value: undefined
						definite: true
						loc: Object {
							filename: "typescript/class/properties/input.ts"
							end: Object {
								column: 15
								line: 7
							}
							start: Object {
								column: 4
								line: 7
							}
						}
						typeAnnotation: TSNumberKeywordTypeAnnotation {
							loc: Object {
								filename: "typescript/class/properties/input.ts"
								end: Object {
									column: 14
									line: 7
								}
								start: Object {
									column: 8
									line: 7
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
								column: 4
								line: 7
							}
							loc: Object {
								filename: "typescript/class/properties/input.ts"
								end: Object {
									column: 5
									line: 7
								}
								start: Object {
									column: 4
									line: 7
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