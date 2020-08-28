![Apiary.](media/apiary.png "Apiary Data lake.")

# Overview

Apiary provides modules which can be combined to create a federated cloud data lake. These include:
* Read/write [Hive](https://hive.apache.org) metastore service
* Read only [Hive](https://hive.apache.org) metastore service
* [Waggle Dance](https://github.com/HotelsDotCom/waggle-dance) federated Hive metastore service
* [Shunting Yard](https://github.com/ExpediaGroup/shunting-yard) event-based data replication service
* [Beekeeper](https://github.com/ExpediaGroup/beekeeper) event-based data lifecycle service
* [Drone Fly](https://github.com/ExpediaGroup/drone-fly) decouples your Hive metastore (HMS) MetaStoreEventListener implementations from HMS.
* Related infrastructure including load balancers
* Various extensions and plugins for adding additional functionality to the Hive metastore

## Components
Apiary consists of the following components which are managed in separate git repositories:
* [Apiary Authorization](https://github.com/ExpediaGroup/apiary-authorization)
* [Apiary Data Lake](https://github.com/ExpediaGroup/apiary-data-lake)
* [Apiary Extensions](https://github.com/ExpediaGroup/apiary-extensions)
* [Apiary Extensions Terraform](https://github.com/ExpediaGroup/apiary-extensions-terraform)
* [Apiary Federation](https://github.com/ExpediaGroup/apiary-federation)
* [Apiary Lifecycle](https://github.com/ExpediaGroup/apiary-lifecycle)
* [Apiary Metastore Docker](https://github.com/ExpediaGroup/apiary-metastore-docker)
* [Apiary Ranger Docker](https://github.com/ExpediaGroup/apiary-ranger-docker)
* [Apiary Replication](https://github.com/ExpediaGroup/apiary-replication)
* [Apiary Shunting Yard Docker](https://github.com/ExpediaGroup/apiary-shuntingyard-docker)
* [Apiary Waggle Dance Docker](https://github.com/ExpediaGroup/apiary-waggledance-docker)
* [Apiary Drone Fly](https://github.com/ExpediaGroup/apiary-drone-fly)

# Contact

## Mailing List
If you would like to ask any questions about or discuss Apiary please join our mailing list at

  [https://groups.google.com/forum/#!forum/apiary-user](https://groups.google.com/forum/#!forum/apiary-user)

# Legal
This project is available under the [Apache 2.0 License](http://www.apache.org/licenses/LICENSE-2.0.html).

Copyright 2018-2019 Expedia, Inc.
