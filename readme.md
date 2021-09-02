# Extract Price from String

Extract root domain name from an URL.

[![npm](https://img.shields.io/npm/v/get-root-domain)](https://www.npmjs.com/package/get-root-domain)

## Installation

```bash
npm install --save get-root-domain
```

## Usage

```typescript
getRootDomain( url: string | URL ): string;
```

## Usage example

```typescript
import getRootDomain from 'get-root-domain';

console.log(
    getRootDomain('http://www.google.co.uk/blah'), // "google.co.uk"
    getRootDomain('http://www.e.leclerc/test'), // "e.leclerc"
);
```