## v2.1.1 (Jan 23, 2020)
BUG FIXES:

* Fixes a bug where ingress security group rule for 3306 is mistakenly attached to postgres' security group instead of mysql's security group

## v2.1.0 (Sep 11, 2019)

FEATURES:

* Add support to manage DynamoDB Table

## v2.0.2 (May 7, 2019)

BUG FIXES:

* Use correct SG in redis egress and add ingress rules for memcached and Redis

## v2.0.1 (Mar 25, 2019)

ENHANCEMENTS:

* Used terraform autoscaling v0.1.5 (#4)

## v2.0.0 (Mar 14, 2019)

NOTES: 

* Create bastion using ASG

## v1.0.0 (Oct 16, 2018)

NOTES:

* Remove stage tag, since it is not shared with other account.
