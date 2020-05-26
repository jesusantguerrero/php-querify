# php-querify

Php version of https://github.com/jesusantguerrero/adonisjs-querify

Provide a Trait to make enriched api get sql search from query string in url in Laravel

### Queryfy calls params

#### search
`?search=jesus`

#### filter
`/endpoint?filter[fieldName]=value&filter[fieldName]=value`

#### like
`/endpoint?filter[Name]=%value%`

#### greater than
`/endpoint?filter[field]=>value`

#### minor than
`/endpoint?filter[field]=<value`

#### between
`/endpoint?filter[field]=value1~value2`

#### not
`/endpoint?filter[field]=~value2`

#### null
`/endpoint?filter[field]=$value2`

Sort
