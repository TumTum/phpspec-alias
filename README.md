phpspec-alias
=============

Change run/desc command quickly

### What is the alias? What i win?

- Normal: `./bin/phpspec run 'vendor\Project\CoreBundle\Repository\UserRepository'`
- Alias: `./bin/pec 'Repository\UserRepositor'`

#### To creates a specification 

- Normal: `./bin/phpspec describe 'vendor\Project\CoreBundle\Repository\UserRepository'`
- Alias: `./bin/pec 'Repository\UserRepositor' -d`

And than start without `-d`, to run the specification

- `./bin/pec 'Repository\UserRepositor'`


#### But you must specifies the namespace.

-`./bin/pec -n 'vendor\Project\CoreBundle'`

The run command: `./bin/pec 'Repository\UserRepositor'` 
will be than change to: 
`./bin/phpspec run '[vendor\Project\CoreBundle\]Repository\UserRepositor'`

