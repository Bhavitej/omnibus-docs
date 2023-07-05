# Class: Account

[resources](../wiki/resources).[AccountsV1](../wiki/resources.AccountsV1).Account

## Hierarchy

- `BaseClassV1`

  ↳ **`Account`**

## Table of contents

### Constructors

- [constructor](../wiki/resources.AccountsV1.Account#constructor)

### Methods

- [forgotPassword](../wiki/resources.AccountsV1.Account#forgotpassword)
- [getCustomerProfile](../wiki/resources.AccountsV1.Account#getcustomerprofile)
- [getLoginType](../wiki/resources.AccountsV1.Account#getlogintype)
- [isSignedIn](../wiki/resources.AccountsV1.Account#issignedin)
- [login](../wiki/resources.AccountsV1.Account#login)
- [logout](../wiki/resources.AccountsV1.Account#logout)
- [register](../wiki/resources.AccountsV1.Account#register)
- [updatePassword](../wiki/resources.AccountsV1.Account#updatepassword)
- [updateProfile](../wiki/resources.AccountsV1.Account#updateprofile)

## Constructors

### constructor

• **new Account**()

Initialises the Account SDK

**`Example`**

Use this below JS snippet to create an instance of Account SDK 
```js
const accountSDK = new OMNIBUS.AccountsV1.Account();
```

#### Overrides

BaseClassV1.constructor

#### Defined in

[resources/accounts-v1.ts:24](https://gitlab.com/baliganikhil/blackmirror-sdk/-/blob/349365c/src/resources/accounts-v1.ts#L24)

## Methods

### forgotPassword

▸ **forgotPassword**(`emailaddress`, `callback`, `mockConfig?`): `undefined` \| ``false``

Triggers password reset email to the customer if the provided email address is registered

**`Example`**

For live SDK in production use the below snippet for reference
```js
const accountSDK = new OMNIBUS.AccountsV1.Account();
accountSDK.forgotPassword(emailaddress, (error, responseObj) => {
    if (error) {
         // Appropriate actions on forgotPassword failure depending on error.errorCode 
    }

    // Appropriate actions on forgotPassword success
});
```

**`Example`**

For mock SDK while testing use the below snippet for reference
```js
const accountSDK = new OMNIBUS.AccountsV1.Account();
accountSDK.forgotPassword(emailaddress, (error, responseObj) => {
    if (error) {
         // Appropriate actions on forgotPassword failure depending on error.errorCode 
    }

    // Appropriate actions on forgotPassword success
}, mockConfig);
```

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `emailaddress` | `string` | The email address to which password reset email has to be sent |
| `callback` | (`error`: ``null`` \| [`ForgotPasswordError`](../wiki/models.ForgotPasswordError), `responseObj`: ``null``) => `void` | The Callback function |
| `mockConfig?` | [`MockForgotPasswordConfig`](../wiki/models.MockForgotPasswordConfig) | The Mock configuration that can be passed to mock this operation |

#### Returns

`undefined` \| ``false``

#### Defined in

[resources/accounts-v1.ts:167](https://gitlab.com/baliganikhil/blackmirror-sdk/-/blob/349365c/src/resources/accounts-v1.ts#L167)

___

### getCustomerProfile

▸ **getCustomerProfile**(`callback`, `mockConfig?`): `undefined` \| ``false``

Retrives the Customer profile information of the signed in customer

**`Example`**

For live SDK in production use the below snippet for reference
```js
const accountSDK = new OMNIBUS.AccountsV1.Account();
accountSDK.getCustomerProfile((error, responseObj) => {
    if (error) {
         // Appropriate actions on getCustomerProfile failure depending on error.errorCode 
    }

    // Appropriate actions on getCustomerProfile success
});
```

**`Example`**

For mock SDK while testing use the below snippet for reference
```js
const accountSDK = new OMNIBUS.AccountsV1.Account();
accountSDK.getCustomerProfile((error, responseObj) => {
    if (error) {
         // Appropriate actions on getCustomerProfile failure depending on error.errorCode 
    }

    // Appropriate actions on getCustomerProfile success
}, mockConfig);
```

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `callback` | (`error`: ``null`` \| [`GetCustomerProfileError`](../wiki/models.GetCustomerProfileError), `responseObj`: ``null`` \| [`UserProfile`](../wiki/models.UserProfile)) => `void` | The Callback function |
| `mockConfig?` | [`MockGetCustomerProfileConfig`](../wiki/models.MockGetCustomerProfileConfig) | The Mock configuration that can be passed to mock this operation |

#### Returns

`undefined` \| ``false``

#### Defined in

[resources/accounts-v1.ts:379](https://gitlab.com/baliganikhil/blackmirror-sdk/-/blob/349365c/src/resources/accounts-v1.ts#L379)

___

### getLoginType

▸ **getLoginType**(`callback`, `mockConfig?`): `undefined` \| ``false``

Retrieves the Login type of the signed in customer

**`Example`**

For live SDK in production use the below snippet for reference
```js
const accountSDK = new OMNIBUS.AccountsV1.Account();
accountSDK.getLoginType((error, responseObj) => {
    if (error) {
         // Appropriate actions on getLoginType failure depending on error.errorCode 
    }

    // Appropriate actions on getLoginType success
});
```

**`Example`**

For mock SDK while testing use the below snippet for reference
```js
const accountSDK = new OMNIBUS.AccountsV1.Account();
accountSDK.getLoginType((error, responseObj) => {
    if (error) {
         // Appropriate actions on getLoginType failure depending on error.errorCode 
    }

    // Appropriate actions on getLoginType success
}, mockConfig);
```

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `callback` | (`error`: ``null`` \| [`GetLoginTypeError`](../wiki/models.GetLoginTypeError), `responseObj`: ``null`` \| [`EMPHUS`](../wiki/models.LoginType#emphus)) => `void` | The Callback function |
| `mockConfig?` | [`MockGetLoginTypeConfig`](../wiki/models.MockGetLoginTypeConfig) | The Mock configuration that can be passed to mock this operation |

#### Returns

`undefined` \| ``false``

#### Defined in

[resources/accounts-v1.ts:221](https://gitlab.com/baliganikhil/blackmirror-sdk/-/blob/349365c/src/resources/accounts-v1.ts#L221)

___

### isSignedIn

▸ **isSignedIn**(`callback`, `mockConfig?`): `undefined` \| ``false``

Retrieves the login status of the customer

**`Example`**

For live SDK in production use the below snippet for reference
```js
const accountSDK = new OMNIBUS.AccountsV1.Account();
accountSDK.isSignedIn((error, responseObj) => {
    if (error) {
         // Appropriate actions on isSignedIn failure depending on error.errorCode 
    }

    // Appropriate actions on isSignedIn success
});
```

**`Example`**

For mock SDK while testing use the below snippet for reference
```js
const accountSDK = new OMNIBUS.AccountsV1.Account();
accountSDK.isSignedIn((error, responseObj) => {
    if (error) {
         // Appropriate actions on isSignedIn failure depending on error.errorCode 
    }

    // Appropriate actions on isSignedIn success
}, mockConfig);
```

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `callback` | (`error`: ``null`` \| [`IsSignedInError`](../wiki/models.IsSignedInError), `responseObj`: ``null`` \| `boolean`) => `void` | The Callback function |
| `mockConfig?` | [`MockIsSignedInConfig`](../wiki/models.MockIsSignedInConfig) | The Mock configuration that can be passed to mock this operation |

#### Returns

`undefined` \| ``false``

#### Defined in

[resources/accounts-v1.ts:431](https://gitlab.com/baliganikhil/blackmirror-sdk/-/blob/349365c/src/resources/accounts-v1.ts#L431)

___

### login

▸ **login**(`loginParams`, `callback`, `mockConfig?`): `undefined` \| ``false``

Performs customer login (Signs in the customer)

**`Example`**

For live SDK in production use the below snippet for reference
```js
const accountSDK = new OMNIBUS.AccountsV1.Account();
accountSDK.login(loginParams, (error, responseObj) => {
    if (error) {
         // Appropriate actions on login failure depending on error.errorCode 
    }

    // Appropriate actions on login success
});
```

**`Example`**

For mock SDK while testing use the below snippet for reference
```js
const accountSDK = new OMNIBUS.AccountsV1.Account();
accountSDK.login(loginParams, (error, responseObj) => {
    if (error) {
         // Appropriate actions on login failure depending on error.errorCode 
    }

    // Appropriate actions on login success
}, mockConfig);
```

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `loginParams` | [`LoginParams`](../wiki/models.LoginParams) | The login parameters |
| `callback` | (`error`: ``null`` \| [`LoginAccountError`](../wiki/models.LoginAccountError), `responseObj`: ``null``) => `void` | The Callback function |
| `mockConfig?` | [`MockLoginAccountConfig`](../wiki/models.MockLoginAccountConfig) | The Mock configuration that can be passed to mock this operation |

#### Returns

`undefined` \| ``false``

#### Defined in

[resources/accounts-v1.ts:114](https://gitlab.com/baliganikhil/blackmirror-sdk/-/blob/349365c/src/resources/accounts-v1.ts#L114)

___

### logout

▸ **logout**(`callback`, `mockConfig?`): `undefined` \| ``false``

Logs out the signed in customer

**`Example`**

For live SDK in production use the below snippet for reference
```js
const accountSDK = new OMNIBUS.AccountsV1.Account();
accountSDK.logout((error, responseObj) => {
    if (error) {
         // Appropriate actions on logout failure depending on error.errorCode 
    }

    // Appropriate actions on logout success
});
```

**`Example`**

For mock SDK while testing use the below snippet for reference
```js
const accountSDK = new OMNIBUS.AccountsV1.Account();
accountSDK.logout((error, responseObj) => {
    if (error) {
         // Appropriate actions on logout failure depending on error.errorCode 
    }

    // Appropriate actions on logout success
}, mockConfig);
```

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `callback` | (`error`: ``null`` \| [`LogoutError`](../wiki/models.LogoutError), `responseObj`: ``null``) => `void` | The Callback function |
| `mockConfig?` | [`MockLogoutConfig`](../wiki/models.MockLogoutConfig) | The Mock configuration that can be passed to mock this operation |

#### Returns

`undefined` \| ``false``

#### Defined in

[resources/accounts-v1.ts:483](https://gitlab.com/baliganikhil/blackmirror-sdk/-/blob/349365c/src/resources/accounts-v1.ts#L483)

___

### register

▸ **register**(`user`, `callback`, `mockConfig?`): `undefined` \| ``false``

Performs customer registration (Signs up the customer)

**`Example`**

For live SDK in production use the below snippet for reference
```js
const accountSDK = new OMNIBUS.AccountsV1.Account();
accountSDK.register(user, (error, responseObj) => {
    if (error) {
         // Appropriate actions on registration failure depending on error.errorCode 
    }

    // Appropriate actions on registration success
});
```

**`Example`**

For mock SDK while testing use the below snippet for reference
```js
const accountSDK = new OMNIBUS.AccountsV1.Account();
accountSDK.register(user, (error, responseObj) => {
    if (error) {
         // Appropriate actions on registration failure depending on error.errorCode 
    }

    // Appropriate actions on registration success
}, mockConfig);
```

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `user` | [`User`](../wiki/models.User) | The customer information |
| `callback` | (`error`: ``null`` \| [`RegisterAccountError`](../wiki/models.RegisterAccountError), `responseObj`: ``null``) => `void` | The Callback function |
| `mockConfig?` | [`MockRegisterAccountConfig`](../wiki/models.MockRegisterAccountConfig) | The Mock configuration that can be passed to mock this operation |

#### Returns

`undefined` \| ``false``

#### Defined in

[resources/accounts-v1.ts:59](https://gitlab.com/baliganikhil/blackmirror-sdk/-/blob/349365c/src/resources/accounts-v1.ts#L59)

___

### updatePassword

▸ **updatePassword**(`newPassword`, `callback`, `mockConfig?`): `undefined` \| ``false``

Updates the password of the signed in customer

**`Example`**

For live SDK in production use the below snippet for reference
```js
const accountSDK = new OMNIBUS.AccountsV1.Account();
accountSDK.updatePassword(newPassword, (error, responseObj) => {
    if (error) {
         // Appropriate actions on updatePassword failure depending on error.errorCode 
    }

    // Appropriate actions on updatePassword success
});
```

**`Example`**

For mock SDK while testing use the below snippet for reference
```js
const accountSDK = new OMNIBUS.AccountsV1.Account();
accountSDK.updatePassword(newPassword, (error, responseObj) => {
    if (error) {
         // Appropriate actions on updatePassword failure depending on error.errorCode 
    }

    // Appropriate actions on updatePassword success
}, mockConfig);
```

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `newPassword` | `string` | The new customer password |
| `callback` | (`error`: ``null`` \| [`UpdatePasswordError`](../wiki/models.UpdatePasswordError), `responseObj`: ``null``) => `void` | The Callback function |
| `mockConfig?` | [`MockUpdatePasswordConfig`](../wiki/models.MockUpdatePasswordConfig) | The Mock configuration that can be passed to mock this operation |

#### Returns

`undefined` \| ``false``

#### Defined in

[resources/accounts-v1.ts:274](https://gitlab.com/baliganikhil/blackmirror-sdk/-/blob/349365c/src/resources/accounts-v1.ts#L274)

___

### updateProfile

▸ **updateProfile**(`userProfile`, `callback`, `mockConfig?`): `undefined` \| ``false``

Updates the customer profile information of the signed in customer

**`Example`**

For live SDK in production use the below snippet for reference
```js
const accountSDK = new OMNIBUS.AccountsV1.Account();
accountSDK.updateProfile(userProfile, (error, responseObj) => {
    if (error) {
         // Appropriate actions on updateProfile failure depending on error.errorCode 
    }

    // Appropriate actions on updateProfile success
});
```

**`Example`**

For mock SDK while testing use the below snippet for reference
```js
const accountSDK = new OMNIBUS.AccountsV1.Account();
accountSDK.updateProfile(userProfile, (error, responseObj) => {
    if (error) {
         // Appropriate actions on updateProfile failure depending on error.errorCode 
    }

    // Appropriate actions on updateProfile success
}, mockConfig);
```

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `userProfile` | [`UserProfile`](../wiki/models.UserProfile) | The updated customer profile information to be saved |
| `callback` | (`error`: ``null`` \| [`UpdateProfileError`](../wiki/models.UpdateProfileError), `responseObj`: ``null``) => `void` | The Callback function |
| `mockConfig?` | [`MockUpdateProfileConfig`](../wiki/models.MockUpdateProfileConfig) | The Mock configuration that can be passed to mock this operation |

#### Returns

`undefined` \| ``false``

#### Defined in

[resources/accounts-v1.ts:327](https://gitlab.com/baliganikhil/blackmirror-sdk/-/blob/349365c/src/resources/accounts-v1.ts#L327)
