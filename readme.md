## DB STRUCTURE
Modellare la struttura di una tabella per memorizzare tutti i dati riguardanti delle auto usate messe in vendita da un concessionario

## table name
- used cars

## table structure
(nomi delle colonne e tipo di dati che sono accettati)

- id | 
- vehicle type |
- brand | 
- model | 
- year | 
- price | 
- km | 
- type | 
- fuel | 
- transmission | 
- seats | 
- doors | 
- color | 
- emissions class | 




"""js

const used_cars = [
    {
        id: " ",
        vehicle type: " ",
        brand: " ",
        ...
    },
]


- id | bigint - auto_increment - primary_key (unique, not null)
- isbn | char(13) - primary_key - unique - not null
- title | varchar(200) - not null
- plot | text(500) - null
- author | varchar(255) - not null
- year | year - null
- ?genre (horror ecc) |
- ?categories |
- publisher | varchar(100) - null
- pages | smallint - null
- series | varchar(50) - null
- available | tinyint - dafault(0)
- position | varcahr(50) - null
- ?age_range | varcahr(10) - null
- ?format | varcahr(20) - null
- language | char(5) - default("it-IT")
