# Data-Generator

A simple data generator command line tool to generate random data based on a specific template.

The application is using [Chance.js](http://chancejs.com/) to generate random data. Any data type is supported by Chance.js.

## Installation

```
npm install --global data-generator
```

## Usage

```
  Usage: data-generator [options]

  Options:

    -h, --help                 output usage information
    -V, --version              output the version number
    -t, --template <template>  JSON template for data to be generated
    -c, --count [count]        The number of elements to create, defaults to 1
    -f, --fileName             Name of the file of the data to be generated, Default => 'Default.json'

```

## Example

In Linux can be used like below:

```
data-generator -t '{ "name": "name", "age": "age", "phone": "phone", "_id": "guid" }' -c 2 -f StudentData.json
```

In Windows can be used like below:

```
data-generator -t '{ \"name": \"name", \"age": \"age", \"phone": \"phone", \"_id": \"guid" }' -c 2 -f StudentData.json
```
