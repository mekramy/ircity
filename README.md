# IR City Data Repository

This repository contains comprehensive data of Iran's provinces, counties, and cities in JSON format.

## Features

- Detailed information about each province, county, and city in Iran.
- Data is structured in easy-to-use JSON format.
- Regular updates to ensure data accuracy.

## Usage

Clone the repository:

```sh
git clone https://github.com/mekramy/ircity.git
```

## Structure

```ts
interface Province {
  id: number;
  name: string;
  code: number;
}

interface County {
  id: number;
  name: string;
  code: number;
  province: number;
}

interface City {
  id: number;
  name: string;
  code: number;
  county: number;
  province: number;
  type: number;
  bakhsh: number;
}
```
