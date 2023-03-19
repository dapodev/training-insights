### NEST JS project structure example

│ app.module.ts
│ main.ts
|
├───auth
│ │ auth.controller.ts
│ │ auth.module.ts
│ │ auth.service.ts
│ │
│ ├───constants
│ │ common.ts
│ │ cookies.ts
│ │ fields.ts
│ │ index.ts
│ │ params.ts
│ │ validation.ts
│ │
│ ├───decorators
│ │ │ authWithRoles.decorator.ts
│ │ │ chargebee.decorator.ts
│ │ │ chargebeeEvent.decorator.ts
│ │ │ getUser.decorator.ts
│ │ │ roles.decorator.ts
│ │ │
│ │ ├───transform
│ │ │ forgotPasswordTransform.decorator.ts
│ │ │ signInTransform.decorator.ts
│ │ │
│ │ └───validation
│ │ forgotPassword.decorator.ts
│ │ resetPasswordValidation.decorator.ts
│ │ signInValidation.decorator.ts
│ │ signUpValidation.decorator.ts
│ │
│ ├───dto
│ │ forgotPassword.dto.ts
│ │ index.ts
│ │ signInPayload.dto.ts
│ │ signUpPayload.dto.ts
│ │
│ ├───entities
│ │ commonUser.entity.ts
│ │ resetToken.entity.ts
│ │
│ ├───guards
│ │ jwtAuth.guard.ts
│ │ roles.guard.ts
│ │
│ ├───strategies
│ │ accessToken.strategy.ts
│ │ index.ts
│ │ refreshToken.strategy.ts
│ │
│ ├───types
│ │ basic.ts
│ │ index.ts
│ │ passportStrategies.ts
│ │
│ └───utils
│ auth.ts
│ cookies.ts
│ user.ts
│
├───certificates
│ │ certificates.controller.ts
│ │ certificates.gateway.ts
│ │ certificates.module.ts
│ │ certificates.service.ts
│ │
│ ├───constants
│ │ common.ts
│ │ fields.ts
│ │ gateway.ts
│ │ index.ts
│ │ params.ts
│ │ pdf.ts
│ │ serialNumbers.ts
│ │
│ ├───dto
│ │ deleteCertificateParams.dto.ts
│ │ generateCertificatesDto.ts
│ │ getCertificatesQuery.dto.ts
│ │ index.ts
│ │
│ ├───entities
│ │ certificate.entity.ts
│ │
│ ├───types
│ │ certificates.ts
│ │
│ └───utils
│ barcode.ts
│ certificates.ts
│ qrcode.ts
│ serialNumbers.ts
│
├───common
│ ├───constants
│ │ bcrypt.ts
│ │ collections.ts
│ │ common.ts
│ │ currencies.ts
│ │ customerErrorMessages.ts
│ │ dates.ts
│ │ emails.ts
│ │ errorMessages.ts
│ │ index.ts
│ │ patterns.ts
│ │ swagger.ts
│ │
│ ├───decorators
│ │ ├───string
│ │ │ cases.decorator.ts
│ │ │ trim.decorator.ts
│ │ │
│ │ └───validation
│ │ stringFieldBasis.decoratot.ts
│ │
│ ├───entities
│ │ userBase.entity.ts
│ │
│ ├───exceptions
│ │ │ exception.filter.ts
│ │ │
│ │ └───utils
│ │ getValidationErrors.ts
│ │
│ └───utils
│ arrays.ts
│ certificates.ts
│ fileNames.ts
│ generatePassword.ts
│ isEqualObjectId.ts
│ parseSortOrder.ts
│ serialNumbers.ts
│ strings.ts
│ trimAllExtraSpaces.ts
│
├───customers
│ │ customers.controller.ts
│ │ customers.module.ts
│ │ customers.service.ts
│ │
│ ├───constants
│ │ defaults.ts
│ │ fields.ts
│ │ index.ts
│ │ params.ts
│ │ subscriptions.ts
......
│ ├───entities
│ │ customer.entity.ts
│ │
│ └───utils
│ query.ts
│ stats.ts
│ subscriptions.ts
│
└───types
│ common.ts
│
├───auth
│ tokens.ts
│
.......
