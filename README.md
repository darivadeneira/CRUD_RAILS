---
title: Ruby on Rails
description: Framework de aplicaciones web de código abierto del lado del servidor escrito en el lenguaje de programación Ruby
tags:
  - ruby
  - rails
---

# Ejemplo de Python Flask

Esta es una aplicación web de ruby con metodos CRUD

## ✨ Características

- RUBY
- RAILS

## 💁‍♀️ Cómo usar

- Instala el subsistema de Windows para Linux, ejecute powershell y ejecute `wsl --install -d Ubuntu`
- Instala [Ruby](https://rubyinstaller.org/downloads/) 3.2.4
- Ejecuta en consola `gem install rails`
- Dentro del proyecto entra a `cd inventory_app`
- Instala las dependencias ejecutando en consola `bundle install --gemfile "ruta del proyecto"`
- Migra la base de datos ejecutando en consola `rails db:migrate`
- Ejecuta el programa `rails server`
- Para ejecutar los tests ejecutar `rails test` y automaticamente generará los test ubicados en `test/controllers/items_controllers_test.rb` de las funciones CRUD con los datos ubicados en `test/fixtures/items.yml`
