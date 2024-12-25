This project is React-based Password Generator that dynamically generate secure passwords based on user prefrences. User can customize the password length, include numbers, and special characters, and copy the generated password to the clipboard.

FEATURES
1. Password Customization - adjust password length using slider, toggle option to include numbers and special characters.
2. Dynamic Password Generation
3. Password easily able to copy on clipboard

USE OF REACT HOOKS
1. useState
   Manages the dynamic variables in the application, such as :- length, numberAllowed,           charAllowed & password.
2. useEffect
   Automatically generates password whenever settings(length, numberAllowed, charAllowed) 
   change.
3. useCallback
   Optimizes performance by rendering the function even if one of its dependencies changes.
4. useRef
   it is a React hook a way to create a refrence to a DOM element or provides a way to 
   directly access or interact with a DOM element in your react component.
5. Copy
   Allows the user to easliy copy the password, Select method on the input field to highlight the password text. Copies the text by "window.navigator.clipboard.writetext".
