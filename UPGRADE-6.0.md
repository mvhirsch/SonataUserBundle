UPGRADE FROM 5.x to 6.0
=======================

## `BaseUser` removed

The deprecated `Sonata\UserBundle\Entity\BaseUser` ORM mapping (`BaseUser.orm.xml`) is removed.
If your User class extends `Sonata\UserBundle\Entity\BaseUser`, please extend
`Sonata\UserBundle\Entity\BaseUser3` instead and update your configuration to reference your own class.

Make sure you run your migrations after the change.

