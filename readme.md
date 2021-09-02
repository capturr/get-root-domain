# Extract Price from String

Extract root domain name from an URL.

[![npm](https://img.shields.io/npm/v/@dopamyn/get-root-domain)](https://www.npmjs.com/package/@dopamyn/get-root-domain)

## Installation

```bash
npm install --save @dopamyn/get-root-domain
```

## Usage

```typescript
getRootDomain( url: string | URL ): string;
```

## Usage example

```typescript
import getRootDomain from '@dopamyn/get-root-domain';

console.log(
    extractRootDomain('http://www.google.co.uk/blah'), // "google.co.uk"
    extractRootDomain('http://www.e.leclerc/test'), // "e.leclerc"
);
```