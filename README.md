ECE281-student-accounts
=======================

Link to accounts for ECE382 students.

- [Capt Silva](https://www.github.com/sivwizinbiznilva)
- [Dr. Neebel]
- [Capt Trimble]

## M4

## M6

## T6

```VHDL
-- (this is a VHDL comment)
 
-- import std_logic from the IEEE library
library IEEE;
use IEEE.std_logic_1164.all;
 
-- this is the entity
entity ANDGATE is
  port ( 
    I1 : in std_logic;
    I2 : in std_logic;
    O  : out std_logic);
end entity ANDGATE;
 
-- this is the architecture
architecture RTL of ANDGATE is
begin
  O <= I1 and I2;
end architecture RTL;
```
