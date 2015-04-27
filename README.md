discussions
===========

Purpose
-------

A skeleton app to explore some ideas on public discussion and identity.


Requirements
------------

### Secrets
  Secrets, e.g. SECRET_KEY_BASE, API tokens for Postmark, etc. are read from
a `.env` file sourced from `.powenv` in development.


Testing and Maintenance
-----------------------

### Rspec, Fabrication, Faker
  The fabrication gem is a test factory

### Brakeman
  static analysis tool
  run `brakeman -f html -o doc/brakeman.html`

### Simplecov
  run as part of running rspec
  output to /coverage/index.html

### sandi_meter
  run `sandi_meter --graph`  
  will open a web browser window with results

### Relationship Diagrams
  run `rake diagram:all` to output SVG diagrams to /doc
  (open in Safari if you don't have a dedicated SVG viewer)

  more options: https://github.com/preston/railroady
