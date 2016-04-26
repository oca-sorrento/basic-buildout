# basic-buildout
A basic buildout to build Odoo

# how to build
- `curl https://bootstrap.pypa.io/bootstrap-buildout.py | python2`
- To avoid downloading all of odoo again, please copy a clone of the Odoo
  repository to the `parts/odoo` folder. Do not worry about the branch or
  whether it is `Odoo` or `OCB`.
- `bin/buildout`
