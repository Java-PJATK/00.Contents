# Contents

Java - lecture notes with example programs from archive java_examples

Tomasz R Werner

Warsaw, March 3, 2024 19:58

## 1 General introduction 1

1.1 Computers and programming languages 1

1.2 What is Java? 2

## 2 Compiling and running a Java program 4

## 3 Types, variables, literals 6

### 3.1 Primitive types 6

3.1.1 Names 6

3.1.2 Overview of primitive types 7

3.1.3 Integral types 8

3.1.4 Floating point types 10

### 3.2 Object types 11

3.3 Variables and literals 11

3.4 Conversions 15

3.5 The stack and the heap 16

## 4 Quick introduction to I/O 17

## 5 Instructions and operators 19

### 5.1 Operators 19

5.1.1 Assignment operator 19

5.1.2 Arithmetic operators 20

5.1.3 Conditional and relational operators 22

5.1.4 Bit-wise operators 25

5.1.5 Casting operator 27

5.1.6 Precedence and associativity 27

## 5.2 Instructions 30

5.2.1 Conditional statements 30

5.2.2 Switch statement and expression 31

5.2.3 Loops 36

## 6 Static functions 44

## 7 Arrays 52

7.1 Creating arrays 52

7.2 Arrays of references to objects 55

7.3 Multi-dimensional arrays 55

## 8 Classes 60

8.1 Basic concepts 60

8.2 Classes and objects 60

8.3 Access to classes and their members 63

8.4 Constructors and methods 64

8.5 Static members 69

8.6 Initializing blocks 73

8.7 Singleton classes 76

8.8 Records 77

## 9 Strings and StringBuilders 82

9.1 Class String 82

9.2 Class StringBuilder 85

## 10 Introduction to inheritance 87

10.1 Importance of equal and hashCode methods 93

## 11 Exceptions 97

11.1 try-catch blocks 98

11.2 finally block 99

11.3 Propagating exceptions 100

11.4 Throwing exceptions 100

11.5 Examples 101

11.6 Assertions 107

## 12 Basic data structures 108

12.1 Singly linked lists 108

12.2 Stacks 111

12.3 Queues 113

## 13 IO streams primer 116

13.1 Binary and text IO streams 116

13.2 StreamTokenizer class 124

13.3 IO cheat sheet 125

13.3.1 Reading/writing binary files byte-by-byte 125

13.3.2 Reading a binary file into an array of bytes 126

13.3.3 Reading/writing text files line-by-line 126

13.3.4 Reading/writing text files character-by-character 127

## 14 List of listings 128

## Index 130

https://github.com/Java-PJATK/00.Contents

https://github.com/Java-PJATK/00.GeneralIntroduction

https://github.com/Java-PJATK/00.Index

https://github.com/Java-PJATK/01.AAC-HelloWorld

https://github.com/Java-PJATK/02.AAG-Literals

https://github.com/Java-PJATK/03.AAL-Variables

https://github.com/Java-PJATK/04.AAI-ReadKbd

https://github.com/Java-PJATK/05.AAJ-ReadGraph

https://github.com/Java-PJATK/06.ABY-RelOps

https://github.com/Java-PJATK/07.ACB-CondOp

https://github.com/Java-PJATK/08.BAA-Bits

https://github.com/Java-PJATK/09.AAP-BasicOps

https://github.com/Java-PJATK/10.ABX-Ifs

https://github.com/Java-PJATK/11.ACC-SimpleSwitch

https://github.com/Java-PJATK/12.ACD-Switch

https://github.com/Java-PJATK/13.ACE-SwitchArrow

https://github.com/Java-PJATK/14.ACF-SwitchMult

https://github.com/Java-PJATK/15.ACG-SwitchExpr

https://github.com/Java-PJATK/15.ACG-SwitchExpr

https://github.com/Java-PJATK/16.ACH-SwitchEnum

https://github.com/Java-PJATK/17.AFA-While

https://github.com/Java-PJATK/18.AFB-WhileBis

https://github.com/Java-PJATK/18.AFB-WhileBis

https://github.com/Java-PJATK/19.AFE-DoWhileDice

https://github.com/Java-PJATK/19.AFE-DoWhileDice

https://github.com/Java-PJATK/20.AFH-ForPyram

https://github.com/Java-PJATK/20.AFH-ForPyram

https://github.com/Java-PJATK/21.AFJ-ForWhileEuler

https://github.com/Java-PJATK/21.AFJ-ForWhileEuler

https://github.com/Java-PJATK/22.CYS-PassArr

https://github.com/Java-PJATK/22.CYS-PassArr

https://github.com/Java-PJATK/23.BHK-StatFun

https://github.com/Java-PJATK/23.BHK-StatFun

https://github.com/Java-PJATK/24.BHL-RecFun

https://github.com/Java-PJATK/25.AFR-SelSort

https://github.com/Java-PJATK/26.AFM-Overload

https://github.com/Java-PJATK/27.AFN-Resol


## Listings
## List of listings

1 [AAC-HelloWorld/Hello.java](https://github.com/Java-PJATK/01.AAC-HelloWorld) 4

2 [AAG-Literals/Literals.java](https://github.com/Java-PJATK/02.AAG-Literals) 13

3 [AAL-Variables/Variables.java](https://github.com/Java-PJATK/03.AAL-Variables) 14

4 [AAI-ReadKbd/ReadKbd.java](https://github.com/Java-PJATK/04.AAI-ReadKbd) 17

5 AAJ-ReadGraph/ReadGraph.java 18

6 ABY-RelOps/RelOps.java 23

7 ACB-CondOp/Largest.java 24

8 BAA-Bits/Bits.java 26

9 AAP-BasicOps/BasicOps.java 28

10 ABX-Ifs/LeapYear.java 31

11 ACC-SimpleSwitch/SimpleSwitch.java 32

12 ACD-Switch/Switch.java 33

13 ACE-SwitchArrow/SwitchArrow.java 34

14 ACF-SwitchMult/SwitchMult.java 35

15 ACG-SwitchExpr/SwitchExpr.java 35

16 ACH-SwitchEnum/SwitchEnum.java 36

17 AFA-While/Prime.java 37

18 AFB-WhileBis/Prime.java 38

19 AFE-DoWhileDice/Dice.java 40

20 AFH-ForPyram/Stars.java 42

21 AFJ-ForWhileEuler/ForWhileEuler.java 42

22 CYS-PassArr/PassArr.java 46

23 BHK-StatFun/StatFun.java 47

24 BHL-RecFun/RecFun.java 48

25 AFR-SelSort/SelSort.java 49

26 AFM-Overload/Overload.java 50

27 AFN-Resol/Resol.java 51

28 CYD-BasicArray/BasicArr.java 54

29 CYB-SimpleArrays/SimpleArrays.java 56

30 CYJ-Arr3D/Arr3D.java 58

31 BGO-TrivPoint/TrivPoint.java 61

32 BGO-TrivPoint/Main.java 62

33 BGI-VerySimple/VerySimple.java 64

34 BGI-VerySimple/Main.java 64

35 BGP-Point/Point.java 65

36 BGR-BasicClass/Person.java 67

37 BGR-BasicClass/Main.java 68

38 BHE-StatEx/StatExample.java 69

39 AFL-FunRecur/SimpleRec.java 70

40 BHG-StatOrd/Stats.java 73

41 BHG-StatOrd/Main.java 74

42 BHF-StatBlocks/StatBlocks.java 74

43 BGX-Singlet/Connect.java 76

44 BGX-Singlet/Config.java 77

45 BGX-Singlet/Main.java 77

46 ELR-Records/Records.java 78

47 ELN-Rec/Rec.java 81

48 BHH-Strings/Strings.java 83

49 BHI-StrBuilder/StrBuilder.java 85

50 DJV-Inherit/Point.java 88

51 DJV-Inherit/Pixel.java 89

52 DJV-Inherit/Main.java 89

53 DJW-InherAnimal/Animal.java 91

54 DJW-InherAnimal/Dog.java 91

55 DJW-InherAnimal/Cat.java 92

56 DJW-InherAnimal/Main.java 92

57 AAR-EquToString/EquToString.java 93

58 HUM-HashEquals/Person.java 95

59 HUM-HashEquals/AHash.java 96

60 AXW-ScanExcept/ScanExcept.java 102

61 AXX-TryCatch/TryCatch.java 103

62 AYC-Excpts/Excpts.java 104

63 AYN-CheckedExc/MyUncheckedException.java.105

64 AYN-CheckedExc/CheckedExc.java 106

65 BGU-SingList/Node.java 109

66 BGU-SingList/MyList.java 109

67 BGU-SingList/Main.java 110

68 BGW-Stack/Node.java 111

69 BGW-Stack/MyStack.java 111

70 BGW-Stack/Main.java 112

71 BGZ-ArrStack/ArrStack.java 112

72 BGZ-ArrStack/Main.java 113

73 BGY-SimpQueue/MyQueue.java 114

74 BGY-SimpQueue/Main.java 114

75 KEP-WriteBin/WriteBin.java 117

76 BHJ-BytesChars/BytesChars.java 118 

77 KFE-GrepNew/GrepNew.java 120

78 KFD-Grep/Grep.java 122

79 KFI-File2Str/File2Str.java 123

80 HUS-Tokens/Tokenizer.java 124

