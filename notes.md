# Notes

## A good data model

- captures ALL the information the system needs
- captures ONLY the information the system needs <--- Abstraction 
    - for example: a mecahnic is not concerned about the color of the car
- reflects reality ( from the point of view of the system)
- is flexible, can evolve with the system
- guarantees data integrity, without sacrificing performance <--- using Constraints
- is driven by the way we access the data
    - for example: if you have an emergency fund, you wouldn't save it in a 401K

## Components

- entities (nouns: zoo, animal, species), like a resource --> tables
- properties --> columns or fields
- relationships --> Foreign keys

## Workflow

- identify entities
- identify properties
- identify relationships

## Relationships

- one to one
- one to many
- many to many

## Mantras

- every table must have a primary key
- one to many relationship requires a Foreign Key
- the Foreign Key goes on the many side
- many to many needs a third table
- the third table can have other information
- work on two or three entities at a time
