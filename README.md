# COP2664-1-Lesson-3-Programming-Exercise-4.1
This is a GitHub repository link for Programming Exercise 4.1 of Lesson 4

// This program is used to calculate and read the amount of loans payments the user has to make.

import Foundation // This is used to import the Foundation library.
print("Enter loan amount: ") // This is used to print the loan amount.
var loan = Float(readLine()!)! // This is used to read the loan amount.
print("Enter payment amount: ") // This is used to print the payment amount.
var payment = Float(readLine()!)! // This is used to read the payment amount.
print("Enter interest rate: ") // This is used to print the interest rate.
var interest = Float(readLine()!)! // This is used to read the interest rate.
var count = 0 // This is used to count the number of payments.
while loan > 0 { // This is used to create a while loop.
  loan = loan + (loan * (interest / 100)) // This is used to calculate the loan amount.
  loan = loan - payment // This is used to calculate the loan amount.
  count += 1 // This is used to count the number of payments.
}
print("It will take \(count) payments to pay off the loan." ) // This is used to print the number of payments.
