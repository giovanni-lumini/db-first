## DB STRUCTURE
Modellare la struttura di una tabella per memorizzare tutti i dati riguardanti delle auto usate messe in vendita da un concessionario

## table name
- used cars

## table structure
(nomi delle colonne e tipo di dati che sono accettati)

- id | <!-- NUMERI --> bigint - auto_increment - primary_key (unique, not null) 
- vehicle type | <!-- STRINGHE --> varchar (20) - not null
- brand | <!-- STRINGHE --> varchar (20) - not null
- model | <!-- STRINGHE --> varchar (20) - not null
- year | <!-- DATE --> date - not null
- price | <!-- NUMERI --> float - not null
- km | <!-- NUMERI --> float - not null
- type | <!-- STRINGHE --> varchar (20) - null
- fuel | <!-- STRINGHE --> varchar (20) - not null
- transmission | <!-- STRINGHE --> varchar (20) - not null
- seats | <!-- NUMERI --> tinyint - null
- doors | <!-- NUMERI --> tinyint - null
- color | <!-- STRINGHE --> varchar (20) - null
- emissions class | <!-- NUMERI --> tinyint - not null
- description | <!-- STRINGHE --> text - null
 



"""js
const used_cars = [
    {
        id: " ",
        vehicle type: " ",
        brand: " ",
        ...
    },
]
