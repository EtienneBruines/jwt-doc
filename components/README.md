# Components

The « Easy » component have some limitaitons. For example, it is mandatory to have a JWT \(i.e. claims\) as payload. You may have specific needs not covered by this type of payload.

This framework also provides several components that will help you to use JWS \(signed tokens\) and JWE \(encrypted tokens\) for specific use cases. It also provides other nice features to create and manage keys.

Before to start creating your first tokens, we have to create an algorithm manager and keys or key sets.

* [Algorithm Management](algorithm-management-jwa.md)
* [Header Checker](header-checker.md) and [Claim Checker](claim-checker.md) 
* [Keys and key sets](key-jwk-and-key-set-jwkset/)

When your algorithm manager, your keys and your checkers are ready, you will be able to create or load your first tokens.

* [Signed tokens](signed-tokens-jws/)
* [Encrypted tokens](encrypted-tokens-jwe/)

