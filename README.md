# Pika-to-Kvbase
## 1.  Introduction

This project is helpful for people who want to migrate data from Pika to Redis. It maily includes two parts: data migration and comparison between the source and target data, which is based on **pika-port** and **redis-full-check**.

Thanks Qihoo 360 for distributed Pika and the pika-port, thanks alibaba for distributed redis-full-check which is emloyed to check the difference between Pika and Redis. 

Pika-to-Kvbase fix some bugs of the above projects,  which thus become compiling-problems free project.

## 2. data migration tool: pika-port

To migrate data from Pika to Redis, you should first **install pika-port**

- Install pika 2.x: [pika](https://github.com/xsstef/pika)
- Install pika-port: [port](https://github.com/xsstef/pika-tools)

## 3. data check between source and target

We employed redis-full-check to ensure there is no change during data migration.

* Install redis-full-check: [redis-full-check](https://github.com/xsstef/RedisFullCheck)

  