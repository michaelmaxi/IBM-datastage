# IBM-datastage
Let's have some fun with IBM's DataStage

DataStage Engine -> DESIGNER / DIRECTOR / ADMINISTRATOR -> Developers

DESIGNER -> DataStage Jobs -> Server / Parallel / Sequencer -> Compile & Run -> Import & Export

DIRECTOR -> View & Log Job -> Identify errors & warnings -> Run & Reset Jobs

ADMINISTRATOR -> Create Datastage Projects -> Create & Set Environment variables -> All other Admin activities

_______________________

**Schema** - Collection of **Dimensions** & **Facts**.  

**Dimensions** - attributes and values

**Facts** - measurable data and keys of Dimensions tables used to examine data

**Schema Types**

Star Schema (One fact surrounded by Dimensions) 

Snowflake Schema (Fact + Dimensions + Sub-Dimension)

Hybrid Schema (Start Schema + Snowflake Schema) 

_______________________

**Partitioning** - Dividing of records across Datastage Nodes

**Partition Key-less** - Round Robin / Same / Entire / Modulus / Auto / Random
**Parition Keyed** - Hash / Range / DB2

