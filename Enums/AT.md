### AT Enum
```
public enum AT
{
  None = 0,
  Physical = 1,
  Lightning = 2,
  Cold = 4,
  Fire = 8,
  Void = 16, // 0x00000010
  Necrotic = 32, // 0x00000020
  Poison = 64, // 0x00000040
  Elemental = 128, // 0x00000080
  Spell = 256, // 0x00000100
  Melee = 512, // 0x00000200
  Throwing = 1024, // 0x00000400
  Bow = 2048, // 0x00000800
  DoT = 4096, // 0x00001000
  Minion = 8192, // 0x00002000
  Totem = 16384, // 0x00004000
  PetResisted = 32768, // 0x00008000
  Potion = 65536, // 0x00010000
  Buff = 131072, // 0x00020000
  Channelling = 262144, // 0x00040000
  Transform = 524288, // 0x00080000
  LowLife = 1048576, // 0x00100000
  HighLife = 2097152, // 0x00200000
  FullLife = 4194304, // 0x00400000
  Hit = 8388608, // 0x00800000
  Curse = 16777216, // 0x01000000
  Ailment = 33554432, // 0x02000000
  Crit_deprecated = 67108864, // 0x04000000
  Kill_deprecated = 134217728, // 0x08000000
  Die_deprecated = 268435456, // 0x10000000
}
```