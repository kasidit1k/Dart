# DART

- Dart เบื้องต้น
```

```
- การแสดงผลข้อมูล
```
print("Hello Dart");
```
- Comment
```
//print("Hello Dart");

/* 
print("Hello Dart");
print("Hello Dart");
*/

/// print("Hello Dart");
```
- ตัวแปรและชนิดข้อมูล
```
void main() {
  // Numbers: int และ double
  int age = 25;
  double height = 175.5;
  
  // Strings
  String name = "John Doe";
  
  // Booleans
  bool isStudent = true;
  
  // Records (ใช้ใน Dart 3+)
  var person = ('John', 25);
  
  // Functions (เก็บฟังก์ชันเป็นตัวแปร)
  Function sayHello = () => print("Hello, World!");
  
  // Lists (อาร์เรย์)
  List<int> numbers = [1, 2, 3, 4, 5];
  
  // Sets (เก็บค่าที่ไม่ซ้ำกัน)
  Set<String> fruits = {'apple', 'banana', 'orange'};
  
  // Maps (key-value pair)
  Map<String, int> scores = {'Alice': 90, 'Bob': 85};
  
  // Runes (ใช้แทน Unicode ของตัวอักษร)
  Runes heart = Runes('\u2665');
  
  // Symbols (ใช้สำหรับเมตาดาต้า)
  Symbol sym = #mySymbol;
  
  // Null (ไม่มีค่า)
  Null nothing = null;

  // แสดงค่าแต่ละตัว
  print("int: $age");
  print("double: $height");
  print("String: $name");
  print("bool: $isStudent");
  print("Record: $person");
  print("Function call:"); sayHello();
  print("List: $numbers");
  print("Set: $fruits");
  print("Map: $scores");
  print("Runes: ${String.fromCharCodes(heart)}");
  print("Symbol: $sym");
  print("Null: $nothing");
}
```
- Dynamic Type
```

```
- Constant & Final
- กฎการตั้งชื่อตัวแปร
- จัดการอักขระและข้อความด้วย String
- ตัวดำเนินการทางคณิตศาสตร์
- ตัวดำเนินการเปรียบเทียบ
- ตัวดำเนินการเพิ่มและลดค่า
- Compound Assignment
- If Statement
- If..Else
- If แบบหลายเงื่อนไข
- ตัวดำเนินการทางตรรกศาสตร์
- Ternary Operator
- Switch..Case
- While Loop
- For Loop
- Do..While
- Break และ Continue
 การใช้งาน Loop แต่ละแบบ
-การสร้างฟังก์ชั่น
-ฟังก์ชั่นแบบ Return ค่า
- ฟังก์ชั่นแบบส่ง และ Return ค่า
- Arrow Function
- Optional Parameter
- Named Parameter
- First-Class Function
- โครงสร้างข้อมูล List
- List Properties & Function
- เข้าถึงสมาชิกใน List ด้วย For
- เข้าถึงสมาชิกใน List ด้วย ForEach
- ฟังก์ชั่นเพิ่มสมาชิกใน List
- ฟังก์ชั่นลบสมาชิกใน List
- โครงสร้างข้อมูล Map
- แปลง List เป็น Map
- แปลง Map เป็น List
- ทฤษฎีการเขียนโปรแกรมเชิงวัตถุ
- การสร้าง Class
- การสร้าง Object
- Public / Private
- Getter / Setter
- Constructor
- การสืบทอดคุณสมบัติ
- Overriding Method