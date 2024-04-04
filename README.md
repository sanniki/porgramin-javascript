function triangleArea(side1, side2, side3) {
// Calculate the semi-perimeter
let s = (side1 + side2 + side3) / 2;

// Use Heron's Formula to find the area
return Math.sqrt(s * (s - side1) * (s - side2) * (s - side3));
}

// Example usage
let side1Length = 3;
let side2Length = 4;
let side3Length = 5;
let area = triangleArea(side1Length, side2Length, side3Length);
console.log(`The area of the triangle is: ${area}`);


