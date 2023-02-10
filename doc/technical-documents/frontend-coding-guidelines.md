# Frontend Coding Guidelines

## What are Coding Standards? 

Think of coding standards as a set of rules, techniques, and best practices to create cleaner, more readable, more efficient code with minimal errors. They offer a uniform format by which software engineers can use to build sophisticated and highly functional code.

## Advantages of implementing Coding Standards 

Offers uniformity to the code created by different engineers.

Enables the creation of reusable code.

Makes it easier to detect errors.

Make code simpler, more readable, and easier to maintain.

Boost programmer efficiency and generates faster results.

## Coding Standards & Best Practices to Follow 

Pascal Case: PascalCase is a naming convention in which a name is formed of multiple words that are joined together as a single word with the first letter of each of the multiple words capitalised

Example: HelloWorld

Camel Case: CamelCase is a naming convention in which a name is formed of multiple words that are joined together as a single word with the first letter of each of the multiple words capitalised expect the first word.

Example: helloWorld

Snake Case: Snake case is a naming convention in which spaces between words is replaced with an underscore or hyphen.

Example:

hello-world

Hello-World

hello_world

Hello_World

## Naming Conventions

A folder and sub folder name should always start with small letters and snake case

Example:

login

fund-transfer

account-opening

pre-registration

Shared functionality folder name should always start with core as prefix along with all small letters and snake case

Example:

core-components

core-navigations

core-plugins

Component file name should be written using pascal case which should include postfix component identifier. If a component requires multiple files (styles, test) locate all files within component folder.

Example:

Button.component.tsx

Button.style.tsx

Button.spec.ts

Plugin files name should include plugin identifier with all small letters and snake case:

Example:

camera.plugin.ts

gps.plugin.ts

Util files name should include util identifier with all small letters and snake case:

Example:

regex.util.ts

time-convertor.util.ts

Services files name should include service identifier with all small letters and snake case:

Example:

login.service.ts

fund-transfer.service.ts

Module wise navigation files name should include navigation identifier with all small letters and snake case:

Example:

login.navigation.ts

fund-transfer.navigation.ts

Unit test files should use the same name as its corresponding file with all small letters and snake case:

Example:

cookie-banner.ts

cookie-banner.spec.ts

fetch-data.ts

fetch-data.spec.ts

Object and Function name should be camel case:

Example:

objectName

onClick()

Variable name should be camel case:

Example:

const variable = 'test';

let variableBoolean = true;

The class/interface name should be declared as the file name that will be easy during importing and to maintain the standard declaration. Class name should be pascal case:

Example:

Employee.ts

UserLogin.ts

## Architecture & Clean Code

No DRY violations. Create utility files to avoid duplicate code

Follow the component/presentation pattern where appropriate. Components should follow the single responsibility principle

Use Higher Order Components where appropriate

Split code into respective files, JavaScript, test, and styles

Create an index.js within each folder for exporting. This will reduce repeating names on the imports

Only include one React component per file

Favour functionless components

Do not use mixins

No unneeded comments

Methods that are longer than the screen should be refactored into smaller units

Commented out code should be deleted, not committed

Semicolon should be used in all places at the end of statement.

Use .js or .ts extension a for JavaScript and TypeScript classes, functions, variables and constants

Use .jsx or .tsx extension a for React Native components

Only use let or const

Favour arrow functions

Can the optional chain operator be used instead of an explicit null check

Use optional chaining if things can be null

Use the guard pattern/prop types/typescript to ensure your passed in parameters are valid

Create PURE functions and avoid side-effects

Avoid mutating state when working with arrays

Remove all console.log()
