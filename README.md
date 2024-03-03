# Scrapping

## Database informations

database name : carbon-emissions

table name : countries

* country_name (varchar 255)
* territorial_approach (double 10)
* territorial_approach_by_inhabitant (double 10)
* consumption_approach (double 10)

### Request to create database

```sql
CREATE TABLE `emissions_by_country` (
  `country_name` varchar(255) NOT NULL,
  `territorial_approach` double DEFAULT NULL,
  `territorial_approach_by_inhabitant` double DEFAULT NULL,
  `consumption_approach` double DEFAULT NULL
) ENGINE=InnoDB DEFAULT CHARSET=utf8;
```

