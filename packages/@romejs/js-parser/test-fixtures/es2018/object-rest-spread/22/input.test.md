# `index.test.ts`

**DO NOT MODIFY**. This file has been autogenerated. Run `rome test packages/@romejs/js-parser/index.test.ts --update-snapshots` to update.

## `es2018 > object-rest-spread > 22`

```javascript
Program {
  comments: Array []
  corrupt: false
  directives: Array []
  filename: 'input.js'
  hasHoistedVars: true
  interpreter: undefined
  mtime: undefined
  sourceType: 'script'
  syntax: Array []
  loc: Object {
    filename: 'input.js'
    end: Object {
      column: 0
      index: 20
      line: 2
    }
    start: Object {
      column: 0
      index: 0
      line: 1
    }
  }
  diagnostics: Array [
    Object {
      origins: Array [Object {category: 'js-parser'}]
      description: Object {
        advice: Array []
        category: 'parse/js'
        message: PARTIAL_BLESSED_DIAGNOSTIC_MESSAGE {value: 'Unexpected token, expected ,'}
      }
      location: Object {
        filename: 'input.js'
        mtime: undefined
        sourceType: 'script'
        end: Object {
          column: 11
          index: 11
          line: 1
        }
        start: Object {
          column: 10
          index: 10
          line: 1
        }
      }
    }
  ]
  body: Array [
    VariableDeclarationStatement {
      loc: Object {
        filename: 'input.js'
        end: Object {
          column: 19
          index: 19
          line: 1
        }
        start: Object {
          column: 0
          index: 0
          line: 1
        }
      }
      declaration: VariableDeclaration {
        kind: 'var'
        loc: Object {
          filename: 'input.js'
          end: Object {
            column: 19
            index: 19
            line: 1
          }
          start: Object {
            column: 0
            index: 0
            line: 1
          }
        }
        declarations: Array [
          VariableDeclarator {
            id: BindingObjectPattern {
              loc: Object {
                filename: 'input.js'
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
              rest: BindingIdentifier {
                name: 'x'
                loc: Object {
                  filename: 'input.js'
                  end: Object {
                    column: 9
                    index: 9
                    line: 1
                  }
                  start: Object {
                    column: 8
                    index: 8
                    line: 1
                  }
                }
              }
              properties: Array [
                BindingObjectPatternProperty {
                  key: StaticPropertyKey {
                    value: Identifier {
                      name: ''
                      loc: Object {
                        filename: 'input.js'
                        end: Object {
                          column: 11
                          index: 11
                          line: 1
                        }
                        start: Object {
                          column: 10
                          index: 10
                          line: 1
                        }
                      }
                    }
                    variance: undefined
                    loc: Object {
                      filename: 'input.js'
                      end: Object {
                        column: 11
                        index: 11
                        line: 1
                      }
                      start: Object {
                        column: 10
                        index: 10
                        line: 1
                      }
                    }
                  }
                  value: BindingIdentifier {
                    name: ''
                    loc: Object {
                      filename: 'input.js'
                      end: Object {
                        column: 11
                        index: 11
                        line: 1
                      }
                      start: Object {
                        column: 10
                        index: 10
                        line: 1
                      }
                    }
                  }
                  loc: Object {
                    filename: 'input.js'
                    end: Object {
                      column: 11
                      index: 11
                      line: 1
                    }
                    start: Object {
                      column: 10
                      index: 10
                      line: 1
                    }
                  }
                }
              ]
            }
            loc: Object {
              filename: 'input.js'
              end: Object {
                column: 19
                index: 19
                line: 1
              }
              start: Object {
                column: 4
                index: 4
                line: 1
              }
            }
            init: ObjectExpression {
              properties: Array []
              loc: Object {
                filename: 'input.js'
                end: Object {
                  column: 19
                  index: 19
                  line: 1
                }
                start: Object {
                  column: 17
                  index: 17
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
```