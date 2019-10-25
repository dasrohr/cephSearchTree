# cephSearchTree

written by Toni Warnecke - University Medicine Essen

program to make some informations from ceph more eye-friendly or easiert to access.
program was created 'on-demand' - no real developemt process was involved. so might be a bit hacky and probably not realy optimized.
program does NOT change anything on your cluster. but there is no warranty though.

needs to be executed on the admin-node.

note that NOT everything in this programm is tailored to work out-of-the box with every cluster setup.
some things are hard-coded to OUR needs. Feel free to adjust things to fit your needs.

```
Usage:
  cephSearchTree osd <osd>...
  
  cephSearchTree pg <pg>...
  cephSearchTree placement
  cephSearchTree -h | --help
  cephSearchTree --version
Options:
  -h --help   show this help
  --version   show version```
