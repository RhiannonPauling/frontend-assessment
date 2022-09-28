
Sorry for the mix of Bootstrap and vanilla CSS, I decided to learn Bootstrap on the fly!


Exercise 1 - assessment folder

- Clone the repository and navigate within a terminal to 'assessment' directory
- Run 'npm run serve' in the root directory after installation of npm ('npm install')

Exercise 2 - assessment-2 folder

- Clone the repository and navigate within a terminal to 'assessment-2' directory
- Run 'npm run serve' in the root directory after installation of npm ('npm install')



* Explain why the result of `('b' + 'a' + + 'a' + 'a').toLowerCase()` is `banana`.

- The + +'a' results in Javascript attempting to evaluate +'a' as a positive number which because 'a' is not a number, it returns NaN (not a number), which casts to a string and then the whole string is coverted to lowercase hence the 'nan' in the middle of 'ba' and 'a'.
