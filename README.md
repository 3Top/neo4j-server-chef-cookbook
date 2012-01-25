# Neo4J Server Chef Cookbook

This is an OpsCode Chef cookbook for Neo4J Server Community Edition.

It uses officially released tarballs to install Neo4J under /usr/local/neo4j-server,
provides Upstart service script and allows you to tweak many parameters using Chef node
attributes.


## Neo4J Server Version

This cookbook currently provides Neo4J Server 1.6 (Community Edition) but can be used
to install other versions by overriding data bag attributes.


## Recipes

Main recipe is `neo4j-server::tarball`.


## Dependencies

OpenJDK 6 or Sun JDK 6.


## Copyright & License

Michael S. Klishin, 2012.

Released under the [MIT license](http://www.opensource.org/licenses/mit-license.php).
