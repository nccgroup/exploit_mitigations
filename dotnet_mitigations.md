We list mitigations added in all Microsoft .NET framework versions.

| Version (and date) | Mitigation | References |
|--------------------|------------|------------------------------------------|
| MS12-035 | check the type being set during the ISerializable.GetObjectData call is in an assembly signed with the same public key (avoid partial trust abusing round-trip serialization) | [1] |


[1]: https://web.archive.org/web/20210206071224/https://media.blackhat.com/bh-us-12/Briefings/Forshaw/BH_US_12_Forshaw_Are_You_My_Type_WP.pdf