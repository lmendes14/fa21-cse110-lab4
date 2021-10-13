1. values added: 20
2. final result: 20
3. values added: 20
4. The code returns an error because the 'let' keyword keeps result's scope within the if statement. When the code tries to access result, it's out of scope and an error is thrown.
5. The code returns an error because the 'const' keyword prevents result from being reassigned. We initialize result to be 0, so when we try to reassign result with num1+num2, an error is thrown.
6. This line is never reached since line 7 returned an error, stopping our function. Had this line been reached, another out of scope error would have been thrown since the 'const' keyword keeps result within the if statement block.
