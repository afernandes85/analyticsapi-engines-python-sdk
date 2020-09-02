<img alt="FactSet" src="https://www.factset.com/hubfs/Assets/images/factset-logo.svg" height="56" width="290">

# Analytics API Engines Python SDK

[![build](https://img.shields.io/github/workflow/status/afernandes85/analyticsapi-engines-python-sdk/CI)](https://github.com/afernandes85/analyticsapi-engines-python-sdk/actions?query=workflow%3ACI)
[![PyPi](https://img.shields.io/pypi/v/fds.analyticsapi.engines)](https://pypi.org/project/fds.analyticsapi.engines/)
![API version](https://img.shields.io/badge/API-v2-blue)
[![Apache-2 license](https://img.shields.io/badge/license-Apache2-brightgreen.svg)](https://www.apache.org/licenses/LICENSE-2.0)

Use this library to integrate with FactSet's Analytics APIs. Below APIs are supported by this SDK.

* [PA Engine API](https://developer.factset.com/api-catalog/pa-engine-api)
* [SPAR Engine API](https://developer.factset.com/api-catalog/spar-engine-api)
* [Vault API](https://developer.factset.com/api-catalog/vault-api)

## Contents

* [fds.analyticsapi.engines](fds.analyticsapi.engines) - Auto-generated code using [Analytics API Engines SDK Generator](https://github.com/afernandes85/analyticsapi-engines-sdk-generator)
* [examples](examples) - Sample project containing code snippets to quickly get started with the SDK  
* [tests](tests) - Integration tests

## Requirements

* Python 3.4 or higher

## Installation

* Install the latest SDK using pip:

  ```sh
  pip install fds.analyticsapi.engines
  ```

* Alternatively, download or clone this repository and install the SDK by  running Setuptools in the SDK installation directory:

  ```sh
  git clone https://github.com/afernandes85/analyticsapi-engines-python-sdk.git
  cd fds.analyticsapi.engines
  python setup.py install --user
  ```

## Usage

Refer [examples](examples) project for sample code snippets to quickly get started with the SDK

## Tests

First, clone the repo locally and `cd` into the directory.

```sh
git clone https://github.com/afernandes85/analyticsapi-engines-python-sdk.git
cd tests
```

Next, install dependencies.

```sh
pip install -r requirements.txt
```

Before running the tests, set the below environment variables. Use the [Developer Portal Manage API Keys page](https://developer.factset.com/manage-api-keys) to get these values.

```sh
export ANALYTICS_API_USERNAME_SERIAL = "username-serial"
export ANALYTICS_API_PASSWORD = "apikey"
```

Run the tests with below command.

```sh
python -m test
```

## Contributing

* Files in [fds.analyticsapi.engines](fds.analyticsapi.engines) are auto-generated and should not be manually edited here. Refer [Analytics API Engines SDK Generator](https://github.com/afernandes85/analyticsapi-engines-sdk-generator) for instructions on how to modify these files.
* [examples](examples) and [tests](tests) projects are open to enhancements and bug fixes. Please create a pull requests with the proposed changes.
