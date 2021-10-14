# Philosohpy and Features

Referencia certificación DBA

https://university.mongodb.com/exam/guide#application-and-server-administration-dba-only

Documentación de MongoDB (Server)

https://docs.mongodb.com/manual/

## Intro e Arquitecture Guide

En cuanto a Arquitecture Guide suele entrar una consulta sobre

- Alta disponibilidad => Replica Set
- Escalado horizontal => Sharding

## JSON

- Lo que ya vimos en JS

## BSON

https://docs.mongodb.com/manual/reference/bson-types/

Los documentos (registros) en MongoDB se almacenan en el formato BSON, se usa este formato
porque aumenta los tipos de datos disponibles en JSON. (Ojo pregunta)

Los driver de MongoDB parsean los documentos BSON con los tipos de datos BSON a los objetos de cada
lenguaje de esos drivers.

Por ejemplo

BSON <-> Java
BSON <-> JSON/JavaScript * Esto explica que la shell de mongo acepte tanto JSON como JavaScript


