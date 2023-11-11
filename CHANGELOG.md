# [2.2.0](https://github.com/common-creation/aws-cdk-ses-domain-identity/compare/v2.1.1...v2.2.0) (2023-11-11)


### Features

* add always upsert options ([fbf36d8](https://github.com/common-creation/aws-cdk-ses-domain-identity/commit/fbf36d8fa9dde6966761885452c76c623a339d83))
* update to node18 ([8cfca3d](https://github.com/common-creation/aws-cdk-ses-domain-identity/commit/8cfca3d1c72a39af6aaf5c7066c34490e76a1132))

## [2.1.1](https://github.com/common-creation/aws-cdk-ses-domain-identity/compare/v2.1.0...v2.1.1) (2023-01-18)


### Bug Fixes

* 'Invalid XML' errors at cdk destroy ([da458e4](https://github.com/common-creation/aws-cdk-ses-domain-identity/commit/da458e4de720f54202e5a9cd378bcaec7500ba37))

# [2.1.0](https://github.com/common-creation/aws-cdk-ses-domain-identity/compare/v2.0.0...v2.1.0) (2023-01-18)


### Bug Fixes

* variable name ([42c9f67](https://github.com/common-creation/aws-cdk-ses-domain-identity/commit/42c9f67878038c5ae02ff75f82b305bab97e7e1e))


### Features

* exclude empty recordsets ([016784a](https://github.com/common-creation/aws-cdk-ses-domain-identity/commit/016784a00969fa8d4fc3555e560fb24a95cdaaf7))

# [2.0.0](https://github.com/common-creation/aws-cdk-ses-domain-identity/compare/v1.0.0...v2.0.0) (2023-01-17)


### Bug Fixes

* change npm publish option ([00069a4](https://github.com/common-creation/aws-cdk-ses-domain-identity/commit/00069a4bff4f20269e31988bca0635b4534a6de4))


### Continuous Integration

* ready to 2.0.0 ([e22f38f](https://github.com/common-creation/aws-cdk-ses-domain-identity/commit/e22f38fedbd68e3cf34dee4a9f8d1f71a5d2eb4f))


### BREAKING CHANGES

* this is dummy message

# 1.0.0 (2023-01-17)


### Bug Fixes

* camelCase to PascalCase ([c865bb8](https://github.com/common-creation/aws-cdk-ses-domain-identity/commit/c865bb830ea466ef5cbc465e594130cd01e1904e))
* change prettier config in vscode ([c068aff](https://github.com/common-creation/aws-cdk-ses-domain-identity/commit/c068aff5eb2546d87b9a3b6a10dde5053c7020e1))
* **delete-record:** removing the ommitting of required parameters from DELETE record ([#16](https://github.com/common-creation/aws-cdk-ses-domain-identity/issues/16)) ([af62caa](https://github.com/common-creation/aws-cdk-ses-domain-identity/commit/af62caabe18b36f7f5f2bca1b1c1e7ac96c080b3))
* **deps:** fix invalid CDK version in peer dependency list ([85e7d96](https://github.com/common-creation/aws-cdk-ses-domain-identity/commit/85e7d969ca06eac696349a2fa6b7d88ed53ffeca))
* fork from mooyoul/aws-cdk-ses-domain-identity and update some dependencies ([b14fe5c](https://github.com/common-creation/aws-cdk-ses-domain-identity/commit/b14fe5ce12d4766927bfd4eaaaef3ae541bcfe6f))
* **iam:** add addtional required SES IAM actions ([ca41f94](https://github.com/common-creation/aws-cdk-ses-domain-identity/commit/ca41f94e62e2a271e367d748be8b0c5a8efce882))
* **iam:** fix invalid IAM action name for querying SES Domain Validation ([d693380](https://github.com/common-creation/aws-cdk-ses-domain-identity/commit/d693380dab2f83c9906e2e9922ab9539f0434c7e))
* **iam:** fix missing IAM action for setting DKIM enabled ([ec9325f](https://github.com/common-creation/aws-cdk-ses-domain-identity/commit/ec9325ffc27d874128bd4e6a4b7aea6d224daad5))
* refactor [#30](https://github.com/common-creation/aws-cdk-ses-domain-identity/issues/30) with FQDN usage for Route53 record name ([ace6085](https://github.com/common-creation/aws-cdk-ses-domain-identity/commit/ace6085456b9740bf5e2faa4d6e1d2d6218a0c24))
* repository URL in package.json ([dac2491](https://github.com/common-creation/aws-cdk-ses-domain-identity/commit/dac2491ce67726b591d43129745100b0a1e578cd))
* respect existing TXT records ([#31](https://github.com/common-creation/aws-cdk-ses-domain-identity/issues/31)) ([8635dda](https://github.com/common-creation/aws-cdk-ses-domain-identity/commit/8635ddaab94c2e83cbfae344b9403050b6356688))
* some missing libraries ([3609f1f](https://github.com/common-creation/aws-cdk-ses-domain-identity/commit/3609f1fb502acd0110ec885e8aa61d38c1d9cffb))
* **typing:** fix broken types location ([9162f52](https://github.com/common-creation/aws-cdk-ses-domain-identity/commit/9162f52793ee45e78dc09f9804f12eb315859322))


### Features

* add `identityArn` property ([6c1b938](https://github.com/common-creation/aws-cdk-ses-domain-identity/commit/6c1b938a61feba472c22b3336cc9de5e7f1f2894)), closes [#8](https://github.com/common-creation/aws-cdk-ses-domain-identity/issues/8)
* initial commit ([c6ca45e](https://github.com/common-creation/aws-cdk-ses-domain-identity/commit/c6ca45e9d153fa6b7e68c2f71f045e4926e0f4ee))
* migrate to CDK v2 ([c01e581](https://github.com/common-creation/aws-cdk-ses-domain-identity/commit/c01e581d2fbf0ddb58f4e90dbb67ef644d0097bc)), closes [#37](https://github.com/common-creation/aws-cdk-ses-domain-identity/issues/37)
* update requestor function to use Node.js 14 ([71decd1](https://github.com/common-creation/aws-cdk-ses-domain-identity/commit/71decd18c9529f3c046038dee295d7da7e4f8288))


### BREAKING CHANGES

* Requires CDK v2

# [2.0.0](https://github.com/mooyoul/aws-cdk-ses-domain-identity/compare/v1.1.0...v2.0.0) (2022-02-22)


### Features

* migrate to CDK v2 ([c01e581](https://github.com/mooyoul/aws-cdk-ses-domain-identity/commit/c01e581d2fbf0ddb58f4e90dbb67ef644d0097bc)), closes [#37](https://github.com/mooyoul/aws-cdk-ses-domain-identity/issues/37)


### BREAKING CHANGES

* Requires CDK v2

# [1.1.0](https://github.com/mooyoul/aws-cdk-ses-domain-identity/compare/v1.0.6...v1.1.0) (2022-02-22)


### Features

* add `identityArn` property ([6c1b938](https://github.com/mooyoul/aws-cdk-ses-domain-identity/commit/6c1b938a61feba472c22b3336cc9de5e7f1f2894)), closes [#8](https://github.com/mooyoul/aws-cdk-ses-domain-identity/issues/8)
* update requestor function to use Node.js 14 ([71decd1](https://github.com/mooyoul/aws-cdk-ses-domain-identity/commit/71decd18c9529f3c046038dee295d7da7e4f8288))

## [1.0.6](https://github.com/mooyoul/aws-cdk-ses-domain-identity/compare/v1.0.5...v1.0.6) (2021-09-30)


### Bug Fixes

* refactor [#30](https://github.com/mooyoul/aws-cdk-ses-domain-identity/issues/30) with FQDN usage for Route53 record name ([ace6085](https://github.com/mooyoul/aws-cdk-ses-domain-identity/commit/ace6085456b9740bf5e2faa4d6e1d2d6218a0c24))
* respect existing TXT records ([#31](https://github.com/mooyoul/aws-cdk-ses-domain-identity/issues/31)) ([8635dda](https://github.com/mooyoul/aws-cdk-ses-domain-identity/commit/8635ddaab94c2e83cbfae344b9403050b6356688))

## [1.0.5](https://github.com/mooyoul/aws-cdk-ses-domain-identity/compare/v1.0.4...v1.0.5) (2021-05-08)


### Bug Fixes

* **delete-record:** removing the ommitting of required parameters from DELETE record ([#16](https://github.com/mooyoul/aws-cdk-ses-domain-identity/issues/16)) ([af62caa](https://github.com/mooyoul/aws-cdk-ses-domain-identity/commit/af62caabe18b36f7f5f2bca1b1c1e7ac96c080b3))

## [1.0.4](https://github.com/mooyoul/aws-cdk-ses-domain-identity/compare/v1.0.3...v1.0.4) (2020-07-06)


### Bug Fixes

* **iam:** fix missing IAM action for setting DKIM enabled ([ec9325f](https://github.com/mooyoul/aws-cdk-ses-domain-identity/commit/ec9325ffc27d874128bd4e6a4b7aea6d224daad5))

## [1.0.3](https://github.com/mooyoul/aws-cdk-ses-domain-identity/compare/v1.0.2...v1.0.3) (2020-06-28)


### Bug Fixes

* **iam:** fix invalid IAM action name for querying SES Domain Validation ([d693380](https://github.com/mooyoul/aws-cdk-ses-domain-identity/commit/d693380dab2f83c9906e2e9922ab9539f0434c7e))

## [1.0.2](https://github.com/mooyoul/aws-cdk-ses-domain-identity/compare/v1.0.1...v1.0.2) (2020-06-12)


### Bug Fixes

* **deps:** fix invalid CDK version in peer dependency list ([85e7d96](https://github.com/mooyoul/aws-cdk-ses-domain-identity/commit/85e7d969ca06eac696349a2fa6b7d88ed53ffeca))

## [1.0.1](https://github.com/mooyoul/aws-cdk-ses-domain-identity/compare/v1.0.0...v1.0.1) (2020-06-12)


### Bug Fixes

* **iam:** add addtional required SES IAM actions ([ca41f94](https://github.com/mooyoul/aws-cdk-ses-domain-identity/commit/ca41f94e62e2a271e367d748be8b0c5a8efce882))
* **typing:** fix broken types location ([9162f52](https://github.com/mooyoul/aws-cdk-ses-domain-identity/commit/9162f52793ee45e78dc09f9804f12eb315859322))

# 1.0.0 (2020-06-09)


### Features

* initial commit ([c6ca45e](https://github.com/mooyoul/aws-cdk-ses-domain-identity/commit/c6ca45e9d153fa6b7e68c2f71f045e4926e0f4ee))
