# Contents

Java - lecture notes with example programs from archive java_examples

Tomasz R Werner

Warsaw, March 3, 2024 19:58

## 1 General introduction 1

1.1 Computers and programming languages 1

1.2 What is Java? 2

## 2 Compiling and running a Java program 4

## 3 [Types, variables, literals](https://github.com/Java-PJATK/02.AAG-Literals) 6

### 3.1 [Primitive types](https://github.com/Java-PJATK/02.AAG-Literals) 6

3.1.1 [Names](https://github.com/Java-PJATK/02.AAG-Literals) 6

3.1.2 [Overview of primitive types](https://github.com/Java-PJATK/02.AAG-Literals) 7

3.1.3 [Integral types](https://github.com/Java-PJATK/02.AAG-Literals) 8

3.1.4 [Floating point types](https://github.com/Java-PJATK/02.AAG-Literals) 10

### 3.2 [Object types](https://github.com/Java-PJATK/02.AAG-Literals) 11

3.3 [Variables and literals](https://github.com/Java-PJATK/02.AAG-Literals) 11

3.4 [Conversions](https://github.com/Java-PJATK/3.4.Conversions) 15

3.5 [The stack and the heap](https://github.com/Java-PJATK/3.5TheStackandTheHeap) 16

## 4 [Quick introduction to I/O](https://github.com/Java-PJATK/04.AAI-ReadKbd) 17

## 5 [Instructions and operators](https://github.com/Java-PJATK/06.ABY-RelOps) 19

### 5.1 Operators 19

5.1.1 Assignment operator 19

5.1.2 Arithmetic operators 20

5.1.3 Conditional and relational operators 22

5.1.4 [Bit-wise operators](https://github.com/Java-PJATK/08.BAA-Bits) 25

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

8.3 [Access to classes and their members](https://github.com/Java-PJATK/33.34.BGI-VerySimple) 63

8.4 [Constructors and methods](https://github.com/Java-PJATK/33.34.BGI-VerySimple) 64

8.5 [Static members](https://github.com/Java-PJATK/38.BHE-StatEx/) 69

8.6 [Initializing blocks](https://github.com/Java-PJATK/40.41.BHG-StatOrd) 63 73

8.7 [Singleton classes](https://github.com/Java-PJATK/43.44.45.BGX-Singlet) 76

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

13.2 [StreamTokenizer class](https://github.com/Java-PJATK/80.HUS-Tokens) 124

13.3 [IO cheat sheet](https://github.com/Java-PJATK/80.HUS-Tokens) 125

13.3.1 [Reading/writing binary files byte-by-byte](https://github.com/Java-PJATK/80.HUS-Tokens) 125

13.3.2 [Reading a binary file into an array of bytes](https://github.com/Java-PJATK/80.HUS-Tokens) 126

13.3.3 [Reading/writing text files line-by-line](https://github.com/Java-PJATK/80.HUS-Tokens) 126

13.3.4 [Reading/writing text files character-by-character](https://github.com/Java-PJATK/80.HUS-Tokens) 127

## 14 List of listings 128

## Index 130

https://github.com/Java-PJATK/00.Contents

https://github.com/Java-PJATK/00.GeneralIntroduction

https://github.com/Java-PJATK/00.Index

## Listings
## List of listings

1 [AAC-HelloWorld/Hello.java](https://github.com/Java-PJATK/01.AAC-HelloWorld) 4

2 [AAG-Literals/Literals.java](https://github.com/Java-PJATK/02.AAG-Literals) 13

3 [AAL-Variables/Variables.java](https://github.com/Java-PJATK/03.AAL-Variables) 14

4 [AAI-ReadKbd/ReadKbd.java](https://github.com/Java-PJATK/04.AAI-ReadKbd) 17

5 [AAJ-ReadGraph/ReadGraph.java](https://github.com/Java-PJATK/05.AAJ-ReadGraph) 18

6 [ABY-RelOps/RelOps.java](https://github.com/Java-PJATK/06.ABY-RelOps) 23

7 [ACB-CondOp/Largest.java](https://github.com/Java-PJATK/07.ACB-CondOp) 24

8 [BAA-Bits/Bits.java](https://github.com/Java-PJATK/08.BAA-Bits) 26

9 [AAP-BasicOps/BasicOps.java](https://github.com/Java-PJATK/09.AAP-BasicOps) 28

10 [ABX-Ifs/LeapYear.java](https://github.com/Java-PJATK/10.ABX-Ifs) 31

11 [ACC-SimpleSwitch/SimpleSwitch.java](https://github.com/Java-PJATK/11.ACC-SimpleSwitch) 32

12 [ACD-Switch/Switch.java](https://github.com/Java-PJATK/12.ACD-Switch) 33

13 [ACE-SwitchArrow/SwitchArrow.java](https://github.com/Java-PJATK/13.ACE-SwitchArrow) 34

14 [ACF-SwitchMult/SwitchMult.java](https://github.com/Java-PJATK/14.ACF-SwitchMult) 35

15 [ACG-SwitchExpr/SwitchExpr.java](https://github.com/Java-PJATK/15.ACG-SwitchExpr) 35

16 [ACH-SwitchEnum/SwitchEnum.java](https://github.com/Java-PJATK/16.ACH-SwitchEnum) 36

17 [AFA-While/Prime.java](https://github.com/Java-PJATK/17.AFA-While) 37

18 [AFB-WhileBis/Prime.java](https://github.com/Java-PJATK/18.AFB-WhileBis) 38

19 [AFE-DoWhileDice/Dice.java](https://github.com/Java-PJATK/19.AFE-DoWhileDice) 40

20 [AFH-ForPyram/Stars.java](https://github.com/Java-PJATK/20.AFH-ForPyram) 42

21 [AFJ-ForWhileEuler/ForWhileEuler.java](https://github.com/Java-PJATK/21.AFJ-ForWhileEuler) 42

22 [CYS-PassArr/PassArr.java](https://github.com/Java-PJATK/22.CYS-PassArr) 46

23 [BHK-StatFun/StatFun.java](https://github.com/Java-PJATK/23.BHK-StatFun) 47

24 [BHL-RecFun/RecFun.java](https://github.com/Java-PJATK/24.BHL-RecFun) 48

25 [AFR-SelSort/SelSort.java](https://github.com/Java-PJATK/25.AFR-SelSort) 49

26 [AFM-Overload/Overload.java](https://github.com/Java-PJATK/26.AFM-Overload) 50

27 [AFN-Resol/Resol.java](https://github.com/Java-PJATK/27.AFN-Resol) 51

28 [CYD-BasicArray/BasicArr.java](https://github.com/Java-PJATK/28.CYD-BasicArray) 54

29 [CYB-SimpleArrays/SimpleArrays.java](https://github.com/Java-PJATK/29.CYB-SimpleArrays) 56

30 [CYJ-Arr3D/Arr3D.java](https://github.com/Java-PJATK/30.CYJ-Arr3D) 58

31 [BGO-TrivPoint/TrivPoint.java](https://github.com/Java-PJATK/31.32.BGO-TrivPoint) 61

32 [BGO-TrivPoint/Main.java](https://github.com/Java-PJATK/31.32.BGO-TrivPoint) 62

33 [BGI-VerySimple/VerySimple.java](https://github.com/Java-PJATK/33.34.BGI-VerySimple/) 64

34 [BGI-VerySimple/Main.java](https://github.com/Java-PJATK/33.34.BGI-VerySimple/) 64

35 [BGP-Point/Point.java](https://github.com/Java-PJATK/35.BGP-Point) 65

36 [BGR-BasicClass/Person.java](https://github.com/Java-PJATK/36.37.BGR-BasicClass) 67

37 [BGR-BasicClass/Main.java](https://github.com/Java-PJATK/36.37.BGR-BasicClass) 68

38 [BHE-StatEx/StatExample.java](https://github.com/Java-PJATK/38.BHE-StatEx) 69

39 [AFL-FunRecur/SimpleRec.java](https://github.com/Java-PJATK/39.AFL-FunRecur) 70

40 [BHG-StatOrd/Stats.java](https://github.com/Java-PJATK/40.41.BHG-StatOrd) 73

41 [BHG-StatOrd/Main.java](https://github.com/Java-PJATK/40.41.BHG-StatOrd) 74

42 [BHF-StatBlocks/StatBlocks.java](https://github.com/Java-PJATK/42.BHF-StatBlocks) 74

43 [BGX-Singlet/Connect.java](https://github.com/Java-PJATK/43.44.45.BGX-Singlet) 76

44 [BGX-Singlet/Config.java](https://github.com/Java-PJATK/43.44.45.BGX-Singlet) 77

45 [BGX-Singlet/Main.java](https://github.com/Java-PJATK/43.44.45.BGX-Singlet) 77

46 [ELR-Records/Records.java](https://github.com/Java-PJATK/46.ELR-Records) 78

47 [ELN-Rec/Rec.java](https://github.com/Java-PJATK/47.ELN-Rec) 81

48 [BHH-Strings/Strings.java](https://github.com/Java-PJATK/48.BHH-Strings) 83

49 [BHI-StrBuilder/StrBuilder.java](https://github.com/Java-PJATK/49.BHI-StrBuilder) 85

50 [DJV-Inherit/Point.java](https://github.com/Java-PJATK/50.51.52.DJV-Inherit) 88

51 [DJV-Inherit/Pixel.java](https://github.com/Java-PJATK/50.51.52.DJV-Inherit) 89

52 [DJV-Inherit/Main.java](https://github.com/Java-PJATK/50.51.52.DJV-Inherit) 89

53 [DJW-InherAnimal/Animal.java](https://github.com/Java-PJATK/53.54.55.56.DJW-InherAnimal) 91

54 [DJW-InherAnimal/Dog.java](https://github.com/Java-PJATK/53.54.55.56.DJW-InherAnimal) 91

55 [DJW-InherAnimal/Cat.java](https://github.com/Java-PJATK/53.54.55.56.DJW-InherAnimal) 92

56 [DJW-InherAnimal/Main.java](https://github.com/Java-PJATK/53.54.55.56.DJW-InherAnimal) 92

57 [AAR-EquToString/EquToString.java](https://github.com/Java-PJATK/57.AAR-EquToString) 93

58 [HUM-HashEquals/Person.java](https://github.com/Java-PJATK/58.59.HUM-HashEquals) 95

59 [HUM-HashEquals/AHash.java](https://github.com/Java-PJATK/58.59.HUM-HashEquals) 96

60 [AXW-ScanExcept/ScanExcept.java](https://github.com/Java-PJATK/60.AXW-ScanExcept) 102

61 [AXX-TryCatch/TryCatch.java](https://github.com/Java-PJATK/61.AXX-TryCatch) 103

62 [AYC-Excpts/Excpts.java](https://github.com/Java-PJATK/62.63.64.AYN-CheckedExc) 104

63 [AYN-CheckedExc/MyUncheckedException.java](https://github.com/Java-PJATK/62.63.64.AYN-CheckedExc) 105

64 [AYN-CheckedExc/CheckedExc.java](https://github.com/Java-PJATK/62.63.64.AYN-CheckedExc) 106

65 [BGU-SingList/Node.java](https://github.com/Java-PJATK/65.66.67.BGU-SingList) 109

66 [BGU-SingList/MyList.java](https://github.com/Java-PJATK/65.66.67.BGU-SingList) 109

67 [BGU-SingList/Main.java](https://github.com/Java-PJATK/65.66.67.BGU-SingList) 110

68 [BGW-Stack/Node.java](https://github.com/Java-PJATK/68.69.70.BGW-Stack) 111

69 [BGW-Stack/MyStack.java](https://github.com/Java-PJATK/68.69.70.BGW-Stack) 111

70 [BGW-Stack/Main.java](https://github.com/Java-PJATK/68.69.70.BGW-Stack) 112

71 [BGZ-ArrStack/ArrStack.java](https://github.com/Java-PJATK/71.72.BGZ-ArrStack) 112

72 [BGZ-ArrStack/Main.java](https://github.com/Java-PJATK/71.72.BGZ-ArrStack) 113

73 [BGY-SimpQueue/MyQueue.java](https://github.com/Java-PJATK/73.74.BGY-SimpQueue) 114

74 [BGY-SimpQueue/Main.java](https://github.com/Java-PJATK/73.74.BGY-SimpQueue) 114

75 [KEP-WriteBin/WriteBin.java](https://github.com/Java-PJATK/75.KEP-WriteBin) 117

76 [BHJ-BytesChars/BytesChars.java](https://github.com/Java-PJATK/76.BHJ-BytesChars) 118 

77 [KFE-GrepNew/GrepNew.java](https://github.com/Java-PJATK/77.KFE-GrepNew) 120

78 [KFD-Grep/Grep.java](https://github.com/Java-PJATK/78.KFD-Grep) 122

79 [KFI-File2Str/File2Str.java](https://github.com/Java-PJATK/79.KFI-File2Str) 123

80 [HUS-Tokens/Tokenizer.java](https://github.com/Java-PJATK/80.HUS-Tokens) 124

## Tasks

[Task 1 Histogram](https://github.com/Java-PJATK/Task1.Histogram)

[Task 2 Number Arranger](https://github.com/Java-PJATK/Task2.NumberArranger)

[Task 3 Cross Pattern](https://github.com/Java-PJATK/Task3.CrossPattern)

[Task 4 Random Cards](https://github.com/Java-PJATK/Task4.RandomCards)

[Task 5 Date Simple Conversion](https://github.com/Java-PJATK/Task5.DateSimple)

[Task 6 Tournament Scores](https://github.com/Java-PJATK/Task6.Tournament.2DArrayOfStrings)

[Task 7 Library](https://github.com/Java-PJATK/Task7.Library)

[Task 8 String Normalizing Static Functions](https://github.com/Java-PJATK/Task8.StringNormalizingStaticFunctions)

[Task 9 Exceptions](https://github.com/Java-PJATK/Task9.Exceptions)

[Task 10 Calculating Devices](https://github.com/Java-PJATK/Task10.Computers)
