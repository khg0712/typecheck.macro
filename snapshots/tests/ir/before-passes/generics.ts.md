# Snapshot report for `tests/ir/before-passes/generics.ts`

The actual snapshot is saved in `generics.ts.snap`.

Generated by [AVA](https://avajs.dev).

## generics-advanced

> Snapshot 1

    Map {
      'Generic' => {
        body: {
          properties: [
            {
              keyName: 'a',
              optional: false,
              type: 'propertySignature',
              value: {
                type: 'type',
                typeName: 'Record',
                typeParameters: [
                  {
                    type: 'primitiveType',
                    typeName: 'string',
                  },
                  {
                    type: 'type',
                    typeName: 'Record',
                    typeParameters: [
                      {
                        type: 'primitiveType',
                        typeName: 'number',
                      },
                      {
                        type: 'genericType',
                        typeParameterIndex: 3,
                      },
                    ],
                  },
                ],
              },
            },
          ],
          type: 'objectPattern',
        },
        type: 'interface',
        typeParameterDefaults: [
          {
            type: 'genericType',
            typeParameterIndex: 0,
          },
          {
            type: 'primitiveType',
            typeName: 'string',
          },
          {
            type: 'type',
            typeName: 'Bar',
          },
        ],
        typeParameterNames: [
          'W',
          'X',
          'Y',
          'Z',
        ],
        typeParametersLength: 4,
      },
      'Bar' => {
        body: {
          properties: [],
          type: 'objectPattern',
        },
        type: 'interface',
        typeParameterDefaults: [],
        typeParameterNames: [],
        typeParametersLength: 0,
      },
      'Foo' => {
        body: {
          properties: [],
          type: 'objectPattern',
        },
        type: 'interface',
        typeParameterDefaults: [
          {
            type: 'genericType',
            typeParameterIndex: 0,
          },
        ],
        typeParameterNames: [
          'T',
          'X',
        ],
        typeParametersLength: 2,
      },
    }
