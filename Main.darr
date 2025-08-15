import 'dart:io';

void main() {
  // Asking for user details
  stdout.write("Enter your name: ");
  String name = stdin.readLineSync()!;

  stdout.write("Enter your phone number: ");
  String phone = stdin.readLineSync()!;

  stdout.write("Enter your age: ");
  int age = int.parse(stdin.readLineSync()!);

  stdout.write("Enter your height (in cm): ");
  double height = double.parse(stdin.readLineSync()!);

  stdout.write("Enter your weight (in kg): ");
  double weight = double.parse(stdin.readLineSync()!);

  stdout.write("Enter your address: ");
  String address = stdin.readLineSync()!;

  stdout.write("Enter your hobbies (comma separated): ");
  String hobbiesInput = stdin.readLineSync()!;
  List<String> hobbies = hobbiesInput.split(',').map((h) => h.trim()).toList();

  // Printing biodata
  print("\n===== My Biodata =====");
  print("Name       : $name");
  print("Phone      : $phone");
  print("Age        : $age years");
  print("Height     : ${height} cm");
  print("Weight     : ${weight} kg");
  print("Address    : $address");
  print("Hobbies    :");
  for (var hobby in hobbies) {
    print(" - $hobby");
  }
  print("======================");
}
