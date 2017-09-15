
#### Security Error Codes:

 - **avoid-sha3**: Use "keccak256" instead of deprecated "sha3"
 - **avoid-suicide**: Use "selfdestruct" instead of deprecated "suicide"
 - **avoid-throw**: "throw" is deprecated, avoid to use it
 - **func-visibility**: Explicitly mark visibility in function
 - **state-visibility**: Explicitly mark visibility of state
 - **check-send-result**: Check result of "send" call
 - **avoid-call-value**: Avoid to use ".call.value()()"
 - **compiler-fixed**: Compiler version must be fixed
 - **compiler-gt-0_4**: Use at least '0.4' compiler version
 - **no-complex-fallback**: Fallback function must be simple
 - **mark-callable-contracts**: Explicitly mark all external contracts as trusted or untrusted
 - **multiple-sends**: Avoid multiple calls of "send" method in single transaction
 - **no-simple-event-func-name**: Event and function names must be different
 