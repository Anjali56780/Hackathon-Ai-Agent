# Failure Modes

## 1. Wrong Classification
Problem: Query goes to wrong category  
Solution: Added fallback to general response  

## 2. Empty or Invalid Input
Problem: User enters nothing  
Solution: Ask user to re-enter query  

## 3. API Failure
Problem: Gemini API not responding  
Solution: Show error message and retry  

## 4. Ambiguous Query
Problem: Query is unclear  
Solution: Ask follow-up question
