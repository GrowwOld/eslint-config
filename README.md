# eslint-config
Standard Eslint config adopted in Groww. Customized as per requirement and preferences of devs in Groww.

## Usage
1. Install the correct versions of each package, which are listed by the command:

  ```sh
  npx install-peerdeps --dev @groww-tech/eslint-config
  ```  

  If using npm <5 use this
  ```sh
  npm info "@groww-tech/eslint-config@latest" peerDependencies
  ```
  then install those packages.

  ```sh
  npm install --save-dev "@groww-tech/eslint-config"
  ```

2. Add `"extends": "@groww-tech/eslint-config"` to your `.eslintrc`
