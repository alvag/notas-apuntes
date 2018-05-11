## Listado de apuntes referentes a JavaScript

**- Poner en letra mayúscula la primera letra de una cadena**  

```
const capitalize = (s) => {
  if (typeof s !== 'string') return ''
  return s.charAt(0).toUpperCase() + s.slice(1)
}

capitalize('max') //'Max'
capitalize('m')      //'M'
capitalize(0)        //''
capitalize({})       //''
```  
