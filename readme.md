## Project Name

PSU Sphere

## Short Description

PSU Sphere is a small Django application for managing student organizations, their associated colleges and programs, students, and membership records. It includes model definitions, Django admin registrations, and a management command to seed initial data for development.

## Features

- Django project scaffold with SQLite database configuration
- Models for College, Program, Organization, Student, and OrgMember
- Admin integration with custom `ModelAdmin` classes for `Student` and `OrgMember`
- Management command `create_initial_data` which seeds the database with fake data using Faker
- Basic views scaffold (can be extended to provide CRUD and public-facing views)

## Authors

- Jun Mark Brilliantes
- Angelica Bande

