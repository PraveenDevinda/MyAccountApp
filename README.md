# MyAccountApp

I built a mobile application using React Native and Expo Router as part of Practical Tutorial 04. 

## What I Built:
- **Registration Screen ('app/index.js')**: Captured user inputs ('userName', 'email', 'birthYear', 'phoneNumber', 'password', 'confirmPassword') using 'useState' and validated form fields.
- **Age Calculation & Validation**: Calculated the user's age based on the current year and passed it to the review screen.
- **Review Screen ('app/review.js')**: Retrieved parameters using 'useLocalSearchParams', displayed a review card, implemented conditional validation to ensure users are at least 18 years old, and enabled navigating back via 'router.back()'.
- **Success Screen ('app/success.js')**: Displayed a success message welcoming the user by name upon completion.