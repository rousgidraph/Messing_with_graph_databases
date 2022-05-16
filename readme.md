This project demonstrates using neo4j a fraph database to store data 


  /**Docker command for this thing */

docker run \
--publish=7474:7474 --publish=7687:7687 \
--volume=$HOME/neo4j/data:/data \
neo4j

