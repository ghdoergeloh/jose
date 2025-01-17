# Class: JWSSignatureVerificationFailed

An error subclass thrown when JWS signature verification fails.

## Table of contents

### Constructors

- [constructor](util_errors.JWSSignatureVerificationFailed.md#constructor)

### Properties

- [code](util_errors.JWSSignatureVerificationFailed.md#code)
- [message](util_errors.JWSSignatureVerificationFailed.md#message)

### Accessors

- [code](util_errors.JWSSignatureVerificationFailed.md#code)

## Constructors

### constructor

• **new JWSSignatureVerificationFailed**(`message?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `message?` | `string` |

## Properties

### code

• **code**: `string` = `'ERR_JWS_SIGNATURE_VERIFICATION_FAILED'`

A unique error code for the particular error subclass.

___

### message

• **message**: `string` = `'signature verification failed'`

## Accessors

### code

• `Static` `get` **code**(): ``"ERR_JWS_SIGNATURE_VERIFICATION_FAILED"``

A unique error code for the particular error subclass.

#### Returns

``"ERR_JWS_SIGNATURE_VERIFICATION_FAILED"``
