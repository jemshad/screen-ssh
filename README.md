# screen-ssh
SSH helper to login to multiple machines inside linux screen

## Usage
.screenrc used to run this script in terminal 0

Script will give a prompt similar to
```
Host(s) to SSH>
```

### Accepted Patterns
```
* abc[01-05].xyz.com
* abc[09-11].{colo1,colo2}.company.com
* abc01.{colo1,colo2}.company.com
* abc[02,05-07,11].company.com
* abc[09-11].company.com*2    -> opens two shells each to the given boxes

Multiple patterns can be given space separated
```

## Bug Reporting
jemshad dot ok at gmail dot com
