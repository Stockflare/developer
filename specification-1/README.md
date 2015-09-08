# Decrypt & Echo

This test involves building a simple API in your language of choice, that is capable of creating and storing (in a database) RSA Keypairs upon request. Other calls accompanied by an ID and a collection of encrypted text simply decrypt and respond with the corresponding clear text.

### For You: The Test

> Build an API that is capable of creating and storing an RSA Keypair, responding with the public key contents and subsequent ID that the key is stored under. There should also exist a separate call that accepts an ID of a key and a collection of encrypted texts; this call should respond with the corresponding unencrypted texts. Tests should exist for this API to ensure that it works correctly.

### For Us: The Problem

> A requirement has been introduced, requiring the API to be able to create RSA keys of varying size, with a custom exponent (which must be an odd number). The technical test should require this functionality to be implemented and tested.

## Things to Remember

* You can use _any_ language and technology that you think appropriate to efficiently solve this problem. We recommend using a development tool similar to [docker-compose](https://docs.docker.com/compose/) if you wish to incorporate the use of installation-required software.

* You are composing a technical test for us to complete for you. Document and instruct us in a way you would expect to receive and complete a technical test.

* Your technical test should be available to us through Github or Bitbucket, as a public or private repository.

* You should include as much documentation as necessary for our developer(s) to be able to painlessly run your solution (assume a UNIX machine).

  **Note:** _Documentation is incredibly important at Stockflare. Being able to clearly describe your development process so that it may be easily reproduced is key._
