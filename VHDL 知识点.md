# VHDL 知识点

## 类型转换

### std_logic_1164

+ to_std logicvector
  + bit_vector-->std_logic_vector
+ to_bitvector
  + std_logic_vector-->为bit_vector
+ to_stdlogic
  + bit-->std_logic
+ to_bit
  + std_logic-->bit

### std_logic_arith

+ std_logic_arith(操作数，位长)
  + integer、singed、unsigned-->std_logic_vector
+ conv_integer
  + signed、unsigned-->integer



### std_logic_unsigned

+ conv_integer
  + std_logic_vector-->integer

