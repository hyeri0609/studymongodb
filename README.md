# studymongodb

## install on cloud9
* excerpt from link below
```
/* from https://community.c9.io/t/setting-up-mongodb/1717 */

sudo apt-get install -y mongodb-org

mkdir data
echo 'mongod --bind_ip=$IP --dbpath=data --nojournal --rest "$@"' > mongod
chmod a+x mongod

./mongod


```
