
## Player UUID & Matching public keys

This DB contains the public keys of players and the UUID to verify players connecting with the proxy

## Drone UID & Matching public keys

This stores the UID of drones and their public key to authenticate requests to submit data into DB and other drone actions

## Queen public key

This contains the public key of the queen server to authenticate commands


## DB Credentials

This contains the credentials to all databases except the secure one


## Cube ID, Public Key, (IP), Trust-Score

This DB contains the UUIDs, the public key and the trust-score for every drone. Depending on how i will create the structure it will also contain the IP (prob. not). The trust score is a score that shows how trust worthy a cube is (submitting correct data, age, contributions etc.) it will decide weights in the task distribution, which data is correct at conflicts and who is allowed to interact with data of higher sensitivity. 