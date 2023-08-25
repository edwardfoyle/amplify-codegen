## API Report File for "@aws-amplify/graphql-docs-generator"

> Do not edit this file. It is a report generated by [API Extractor](https://api-extractor.com/).

```ts

import { GraphQLSchema } from 'graphql';

// @public (undocumented)
export function buildSchema(schema: string): GraphQLSchema;

// Warning: (ae-forgotten-export) The symbol "GeneratedOperations" needs to be exported by the entry point index.d.ts
// Warning: (ae-forgotten-export) The symbol "MapValueType" needs to be exported by the entry point index.d.ts
//
// @public (undocumented)
export function generateGraphQLDocuments<INCLUDE_META extends boolean>(schema: string, options: {
    maxDepth?: number;
    useExternalFragmentForS3Object?: boolean;
    typenameIntrospection?: boolean;
    includeMetaData?: INCLUDE_META;
}): GeneratedOperations<MapValueType<INCLUDE_META>>;

// (No @packageDocumentation comment for this package)

```