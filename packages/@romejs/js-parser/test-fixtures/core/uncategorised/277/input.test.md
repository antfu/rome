# `index.test.ts`

**DO NOT MODIFY**. This file has been autogenerated. Run `rome test packages/@romejs/js-parser/index.test.ts --update-snapshots` to update.

## `core > uncategorised > 277`

```javascript
Program {
  comments: Array []
  corrupt: false
  diagnostics: Array []
  directives: Array []
  filename: 'input.js'
  hasHoistedVars: false
  interpreter: undefined
  mtime: undefined
  sourceType: 'script'
  syntax: Array []
  loc: Object {
    filename: 'input.js'
    end: Object {
      column: 24
      index: 24
      line: 1
    }
    start: Object {
      column: 0
      index: 0
      line: 1
    }
  }
  body: Array [
    TryStatement {
      finalizer: undefined
      loc: Object {
        filename: 'input.js'
        end: Object {
          column: 24
          index: 24
          line: 1
        }
        start: Object {
          column: 0
          index: 0
          line: 1
        }
      }
      block: BlockStatement {
        body: Array []
        directives: Array []
        loc: Object {
          filename: 'input.js'
          end: Object {
            column: 7
            index: 7
            line: 1
          }
          start: Object {
            column: 4
            index: 4
            line: 1
          }
        }
      }
      handler: CatchClause {
        loc: Object {
          filename: 'input.js'
          end: Object {
            column: 24
            index: 24
            line: 1
          }
          start: Object {
            column: 8
            index: 8
            line: 1
          }
        }
        param: BindingIdentifier {
          name: 'eval'
          loc: Object {
            filename: 'input.js'
            end: Object {
              column: 19
              index: 19
              line: 1
            }
            start: Object {
              column: 15
              index: 15
              line: 1
            }
          }
        }
        body: BlockStatement {
          body: Array []
          directives: Array []
          loc: Object {
            filename: 'input.js'
            end: Object {
              column: 24
              index: 24
              line: 1
            }
            start: Object {
              column: 21
              index: 21
              line: 1
            }
          }
        }
      }
    }
  ]
}
```