---
layout: default
---
## Column Types

At the moment you use Strings for the majority of the CQL types.


| CQL Type        | Java Type   |  Example  |
| ------------- |---------------| -----|
| ascii         | String | "a string column" |
| bigint        | String      |   "2222222222" |
| blob          | String      |    Hexidecimal String like cqlsh takes. "0x0012345435345345435435" |
| boolean       | Boolean              |   true    |
| counter  | String              |    "11111111"   |
| decimal  |      String         |   "13.6"    |
| double   |        String       |   "20.5"    |
| float    |       String        |    "30.5"   |
| int      |        String or int       |   "5" or 5    |
| timestampuuid     |      String or UUID         |   "550e8400-e29b-41d4-a716-446655440000" or UUID.fromString("59ad61d0-c540-11e2-881e-b9e6057626c4") |
| varchar  |      String         |  "a varchar"     |
| varint   |        String       |    "11111111"   |
| timeuuid |         String or UUID      |   "59ad61d0-c540-11e2-881e-b9e6057626c4" or UUID.fromString("59ad61d0-c540-11e2-881e-b9e6057626c4")    |
| inet     |        String       |   "127.0.0.1" or "fdda:5cc1:23:4::1f"    |