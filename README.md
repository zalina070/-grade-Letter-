# -grade-Letter-
const students = [
  { name: "Amina", grade: 95 },
  { name: "Dias", grade: 85 },
  { name: "Zalina", grade: 72 },
  { name: "Arman", grade: 60 },
  { name: "Aliya", grade: 45 },
  { name: "Nurlan", grade: 30 }
];

for (let i = 0; i < students.length; i++) {
  const score = students[i].grade;
  let letter = "";

  if (score > 90) {
    letter = "A";
  } else if (score > 70) {
    letter = "B";
  } else if (score > 50) {
    letter = "C";
  } else {
    letter = "F";
  }

  console.log(`${students[i].name} has grade: ${letter}`);
}
